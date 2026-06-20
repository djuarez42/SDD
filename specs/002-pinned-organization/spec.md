# Spec 002 — Pinned Repos + Organization

## Problem

`djuarez42`'s public repos have no descriptions, no topics/tags, and no pinned
selection. A visitor has no way to understand what each project is about or
which ones represent the best work. The repo list reads as noise.

## Objectives

- [ ] Select 6 repos to pin that tell a coherent progression story.
- [ ] Add a short description to each of those 6 repos.
- [ ] Add relevant GitHub topics to each pinned repo (e.g. `42`, `c`, `unix`).
- [ ] Document the pinned selection so the user can apply it manually in the UI.

## Acceptance Criteria

1. Each of the 6 selected repos has a non-empty description (visible in the list).
2. Each repo has at least 2 relevant topics.
3. The SDD spec documents exactly which 6 repos to pin and in what order.
4. The user has applied the pin in the GitHub UI.

## Out of scope

- Changing repo visibility (private → public).
- Writing full READMEs for individual projects (spec 003+).
- Repos not in the pinned selection.
