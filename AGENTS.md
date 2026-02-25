# AGENTS.md

Guidance for AI coding agents working in this repository.

## Project overview

- `index.html` contains the full application (markup, styles, and JavaScript).
- `README.md` documents usage and project direction.
- `LICENSE` contains project licensing terms.

## Working conventions

- Keep the app dependency-light and browser-native (prefer vanilla JS/CSS/HTML).
- Preserve the existing UI style and avoid introducing build frameworks unless explicitly requested.
- Favor small, readable changes and avoid broad refactors for single-feature updates.

## Validation

- For docs-only changes, verify markdown formatting and run a quick `git diff --stat` check.
- For behavior changes, manually sanity-check in a browser by opening `index.html` (or serving locally).

## PR and commit hygiene

- Use clear commit messages scoped to the change.
- Summaries should list changed files and user-visible impact.
- If you cannot run a check, state the limitation explicitly.
