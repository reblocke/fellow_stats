# AGENTS

## Project Purpose
Workshop to get pulmonary fellows started on statistics

## Public and Data-Safety Rules
- Treat this repository as public. Do not add PHI, restricted datasets, credentials, private drafts, or publisher-formatted article text.
- Teaching materials only
- Manuscript status: No manuscript version expected

## How to Orient Quickly
- Start with `README.md` for project scope, workflow, data notes, citation, and license information.
- Use `CITATION.cff` for structured citation metadata when present.
- Inspect scripts/notebooks before running them; do not assume generated outputs are current.

## Workflow
The workshop source is `fellow_stats.qmd`. Render relevant content/layout changes with `quarto render fellow_stats.qmd` after inspecting its executable chunks and available R dependencies. Documentation-only instruction edits need reference and whitespace checks.

## Verification Before Publishing Changes
- Run `git diff --check`.
- Validate `CITATION.cff` as YAML after citation edits.
- Do not commit generated outputs, logs, caches, virtual environments, `.DS_Store`, or checkpoint files unless intentionally released.
- For clinical or collaborator data, confirm that no row-level restricted data or identifiers are included.
