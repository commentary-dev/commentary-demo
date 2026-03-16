# Commentary Demo Repository

This repository powers the public sample review shown from `commentary.dev/demo`.

## Branches

- `main` is the stable default state.
- `demo-seed` contains the curated commit sequence used for the demo pull request.
- `demo-live` is the disposable branch reset by GitHub Actions and opened as the active pull request.

## What The Demo Shows

- multiple Markdown files
- rendered-document review on long-form content
- file renames and file removals
- commit-aware change-set review
- a non-Markdown-only commit so Commentary can demonstrate commit-specific empty states

The `Reset demo PR` workflow rebuilds `demo-live` from `main`, cherry-picks the curated commits from `demo-seed`, opens a fresh pull request, and optionally warms Commentary's `/demo` route.
