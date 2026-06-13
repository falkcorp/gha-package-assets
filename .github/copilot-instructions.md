<!-- file: .github/copilot-instructions.md -->
<!-- version: 2.4.0 -->
<!-- guid: 4d5e6f7a-8b9c-0d1e-2f3a-4b5c6d7e8f9a -->
<!-- last-edited: 2026-06-13 -->

# gha-package-assets — Additional Context

Org-wide coding standards (file headers, language rules, commit format) are at
**<https://github.com/falkcarp/.github>** and apply automatically to this repo.

For full project context: **CLAUDE.md** at the repo root.

## Project overview

GHA composite action: package and upload release assets. Language: Python/YAML.

## Critical constraints

- This is a GitHub Actions composite action — `action.yml` is the entry point.
- Python scripts live in `src/` and are invoked by action steps.
- All commits must use conventional commit format (`type(scope): description`).
