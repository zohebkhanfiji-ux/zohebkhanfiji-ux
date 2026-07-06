# Versioning and Changelog Process

## Purpose

This document defines a lightweight versioning and changelog process for repository releases.

## Versioning Model

Use simple semantic-style versioning when formal versions are needed:

| Version Part | Meaning | Example |
|---|---|---|
| Major | Large structural or operating model change | `2.0.0` |
| Minor | New documentation, workflow, or repository capability | `1.1.0` |
| Patch | Small correction, cleanup, or clarification | `1.0.1` |

## When to Version

A version should be considered when a change:

- Adds a new phase or operating layer
- Changes repository workflow expectations
- Adds or updates release governance
- Updates automation behavior
- Establishes a reusable process for future repositories

## Changelog Format

Use the following structure for changelog entries:

```markdown
## [Version] - YYYY-MM-DD

### Added
- New files, workflows, or process documents.

### Changed
- Updates to existing docs, backlog, or workflow behavior.

### Fixed
- Corrections to stale status, broken checks, or unclear wording.

### Notes
- Follow-up items or release context.
```

## Changelog Rules

- Keep entries clear and short.
- Describe user-visible repository changes.
- Avoid sensitive or private details.
- Link changes back to issues and pull requests where possible.
- Update the changelog when a phase or release process changes.

## Release Tag Guidance

Tags are optional for this repository. If tags are used, prefer:

- `v0.x.x` for early operating model development
- `v1.0.0` when the repository has stable foundation, documentation, automation, hardening, and release governance

## Initial Version Recommendation

After Phase 5 release operations are merged, the repository can be considered ready for a `v1.0.0` baseline if maintainers want a formal release marker.
