# Codex Workflow

## Purpose

This document defines how Codex-style work should move through the repository.

## Standard Flow

1. Create or select one issue.
2. Create a branch from `main`.
3. Make a small focused change.
4. Open a pull request.
5. Run checks.
6. Review and merge.

## Branch Naming

| Type | Format | Example |
|---|---|---|
| Documentation | `docs/<topic>` | `docs/repo-health` |
| Feature | `feature/<topic>` | `feature/task-system` |
| Fix | `fix/<topic>` | `fix/readme-links` |
| Automation | `automation/<topic>` | `automation/repo-health` |

## Work Rules

- One issue per objective
- One branch per issue
- One pull request per branch
- Keep changes small
- Keep public files safe and general
- Update docs when behavior changes

## Review Rules

A pull request should explain:

- What changed
- Why it changed
- Which files changed
- How it was checked
- What remains open

## Merge Readiness

A PR is ready when:

- Required files exist
- Repo health workflow passes
- Markdown is readable
- The scope is clear
- The change does not introduce unsafe content
