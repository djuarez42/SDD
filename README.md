# SDD — Spec-Driven Development Workspace

This repo is the source of truth for improving `djuarez42`'s GitHub presence
using the **Spec-Driven Development** methodology.

## How it works

1. **Write a spec** before touching any deliverable (see `templates/spec-template.md`).
2. **Plan** the implementation inside the spec folder.
3. **Execute** with Claude Code, committing after each meaningful step.
4. **Mark tasks done** in `tasks.md` and update memory.

## Structure

```
specs/
  001-profile-readme/     # GitHub profile README (djuarez42/djuarez42)
  002-pinned-organization/# Pinned repos + topics/descriptions
templates/
  spec-template.md        # Copy this for new specs
CLAUDE.md                 # Agent instructions (RTCO format)
```

## Current scope

| # | Spec | Status |
|---|------|--------|
| 001 | Profile README | 🔄 In progress |
| 002 | Pinned + organization | 🔄 In progress (manual pin pending) |
