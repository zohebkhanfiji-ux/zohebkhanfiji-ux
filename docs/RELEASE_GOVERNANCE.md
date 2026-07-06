# Release Governance

## Purpose

This document defines a lightweight release governance model for repository changes.

## Release Principles

- Keep changes small and reviewable
- Use issues to define work before execution
- Use pull requests to review implementation
- Keep documentation aligned with actual repository state
- Avoid direct changes to the main branch when a branch and pull request can be used

## Release Readiness

A change is ready for release when:

- The related issue has clear scope
- The pull request explains what changed and why
- Required files and documentation are present
- Automated checks are expected to pass
- The change remains public-safe and non-sensitive

## Release Flow

1. Create or select an issue
2. Create a branch from main
3. Make a focused change
4. Open a pull request
5. Review checks and documentation
6. Merge when ready
7. Close the tracking issue as completed

## Roles

### Planning
Defines scope and acceptance criteria.

### Execution
Implements the approved change in a branch.

### Review
Checks clarity, consistency, and repository safety.

### Maintenance
Keeps backlog and status documents aligned after merge.

## Output

The repository should maintain a clear issue-to-branch-to-PR-to-merge record for every meaningful change.
