# dracula-hugo-theme

> For global standards, way-of-workings, and pre-commit checklist, see `~/.kiro/steering/behavior.md`

## Role

Web developer.

## What This Does

Custom Dracula-inspired Hugo theme. Used by the `startpage` repo.

## Repository Structure

- `layouts/` — Hugo template files (baseof, index, partials)
- `assets/` — CSS/JS assets
- `archetypes/` — Hugo content archetypes
- `theme.toml` — Theme metadata
- `go.mod` — Hugo module definition

## Important Notes

- No Terraform, no Python, no CI/CD pipeline, no Makefile
- This is a Hugo module — consumed by other repos via `go.mod` reference
- Changes here affect the `startpage` repo

## Related Repositories

- `~/src/melvyndekort/startpage` — The site that uses this theme
