# Agent Instructions

This repo owns the Agent Trail CLI and source-agent adapter behavior compiled into the CLI.

## Workflow

- Start from the linked Linear issue or maintainer direction.
- Keep changes scoped to CLI commands, adapter behavior, packaging, or CLI docs.
- Do not change the Agent Trail file format contract here; make spec changes in the spec repo.
- Do not commit real local sessions, secrets, credentials, private logs, or unredacted user data.

## Commands

- Use `mise run setup` for local tool and hook setup.
- Use `mise run check` before opening or updating a pull request.
- Use `mise run check:actions` after editing GitHub Actions workflows.

## Pull Requests

- Use `.github/PULL_REQUEST_TEMPLATE.md`.
- Link the Linear issue.
- State CLI behavior, adapter behavior, or packaging impact.
- Include exact verification commands and results.
