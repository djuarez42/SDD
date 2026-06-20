# Spec 001 — Profile README

## Problem

`djuarez42` has no GitHub profile README (`djuarez42/djuarez42` repo does not
exist). Visitors landing on the profile see an empty page with just a list of
repos — no context, no skills, no story. This is a missed opportunity for both
recruiters and the 42 community.

## Objectives

- [ ] Create the `djuarez42/djuarez42` repo with a `README.md`.
- [ ] Introduce the user's identity (name, role, 42 school context).
- [ ] Showcase the core tech stack with shields.io badges.
- [ ] Include GitHub Stats widgets (stats card, top languages, streak).
- [ ] Link to the best public projects.
- [ ] Provide a contact/reach-out section.

## Acceptance Criteria

1. Visiting `https://github.com/djuarez42` shows the profile README immediately.
2. All badges render without broken images.
3. GitHub Stats widgets load (may take a few seconds via workers.dev CDN).
4. The README is readable in both light and dark mode.
5. Tone is professional but not generic — no "passionate developer" clichés.

## Out of scope

- Per-project READMEs (those are spec 003+).
- Animations, GIFs, or overly complex layouts.
- Non-English content.
