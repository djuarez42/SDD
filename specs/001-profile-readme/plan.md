# Plan 001 — Profile README

## Approach

Create `djuarez42/djuarez42` as a public repo. The README has five sections,
ordered by what a recruiter scans top-to-bottom.

## Sections

### 1. Header / Bio
- Name + role line: `Systems programmer @ 42 · C / C++ / Unix`
- One-sentence description (no buzzwords).

### 2. About
- 2–3 lines: background at 42, focus on low-level systems, current projects.
- Link to 42 intra or school page if available.

### 3. Tech Stack (badges)
Badges via `https://img.shields.io/badge/<label>-<color>?style=for-the-badge&logo=<logo>`:

| Badge | Label | Color | Logo |
|-------|-------|-------|------|
| C | C | A8B9CC | c |
| C++ | C++ | 00599C | cplusplus |
| Bash | Bash | 4EAA25 | gnubash |
| Linux | Linux | FCC624 | linux |
| Git | Git | F05032 | git |
| Vim | Vim | 019733 | vim |

### 4. GitHub Stats
Three widgets stacked (center-aligned):
1. `github-readme-stats` — general stats card (stars, commits, PRs, issues).
2. `github-readme-stats` — top languages card.
3. `github-readme-streak-stats` — contribution streak.

CDN: `https://github-readme-stats.anuraghazra.workers.dev`

### 5. Contact
- Email (ask user at execution).
- LinkedIn (ask user at execution; omit section if none).
- 42 intra handle (ask user at execution).

## Tools

- `gh repo create djuarez42/djuarez42 --public --description "✦ Profile README"`
- Write `README.md` locally, then `git push`.

## Identity inputs needed at execution

- Real name (for header)
- 42 intra login/handle
- Contact email (public?)
- LinkedIn URL (optional)
