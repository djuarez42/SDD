# Plan 002 — Pinned Repos + Organization

## Pinned selection (6 repos, ordered by progression)

| Order | Repo | Why pin it | Description to set |
|-------|------|-----------|-------------------|
| 1 | `libft` | Foundation — custom C standard library | Custom C standard library built from scratch (42 project) |
| 2 | `ft_printf` | Builds on libft — variadic functions, formatting | Reimplementation of printf in C with full format specifier support |
| 3 | `get_next_line` | File I/O, static variables, buffer management | Read lines from a file descriptor one at a time in C |
| 4 | `push_swap` | Algorithms + complexity — sorting with two stacks | Sorting algorithm in C using two stacks with minimum operations |
| 5 | `philo` | Concurrency — threads, mutexes, race conditions | Dining philosophers problem: threads, mutexes, and race condition handling |
| 6 | `minishell-clean` | Capstone — process management, parsing, signals | POSIX-compliant shell in C: lexer, parser, builtins, pipes, redirections |

This order tells the story: *memory management → I/O → algorithms → concurrency → systems*.

## Topics per repo

| Repo | Topics |
|------|--------|
| libft | `42`, `c`, `library`, `algorithms` |
| ft_printf | `42`, `c`, `printf`, `variadic-functions` |
| get_next_line | `42`, `c`, `file-io`, `unix` |
| push_swap | `42`, `c`, `algorithms`, `sorting` |
| philo | `42`, `c`, `multithreading`, `concurrency` |
| minishell-clean | `42`, `c`, `shell`, `unix`, `bash` |

## Execution

Apply via `gh repo edit`:
```bash
gh repo edit djuarez42/libft --description "Custom C standard library built from scratch (42 project)" --add-topic 42 --add-topic c --add-topic library --add-topic algorithms
# ... repeat for each repo
```

Pin repos: GitHub UI → profile page → "Customize your pins" → select the 6 above in order.

## Note on pinning via API

GitHub's GraphQL API does allow pinning repos but requires the `updateUserPinnedItems`
mutation with an OAuth token that has `user` scope. The current token may not have
this scope. Document the manual step clearly.
