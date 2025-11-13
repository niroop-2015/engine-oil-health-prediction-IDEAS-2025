# Contributing Guidelines

## Branching
- `main` = protected; only reviewed PRs get merged
- feature branches: `feat/<short-desc>`
- bugfix branches: `fix/<short-desc>`

## Commits
- Use conventional style: `feat:`, `fix:`, `docs:`, `refactor:`, `test:`…

## Pull Requests
- Add description, link issues, checklist:
  - [ ] Code runs end-to-end
  - [ ] No credentials or raw confidential data
  - [ ] Docs/README updated if behavior changes

## Data Policy
- Do **not** commit confidential raw data.
- Put small **sample** or **synthetic** data in `data/processed/`.
- Document data sources in `data/README.md`.
