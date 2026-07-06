# Repository Ownership Matrix

## Purpose

This document defines a lightweight ownership model for repository areas, review responsibilities, and maintenance expectations.

## Ownership Principles

- Every important repository area should have a clear owner role.
- Ownership means stewardship, not unrestricted control.
- Changes should remain issue-driven, branch-based, and pull-request reviewed.
- Public repository content should remain general, non-sensitive, and easy to review.

## Ownership Matrix

| Area | Owner Role | Review Role | Maintenance Notes |
|---|---|---|---|
| Backlog | Planning owner | Review owner | Keep phase status and open tasks current. |
| Documentation | Documentation owner | Quality reviewer | Keep docs clear, consistent, and public-safe. |
| Automation | Automation owner | Workflow reviewer | Keep workflows simple and reviewable. |
| Release process | Release owner | Governance reviewer | Confirm checklist completion before merge. |
| Repository structure | Maintenance owner | Quality reviewer | Confirm required files and folders remain present. |

## Standard Responsibilities

### Planning Owner
- Converts broad work into clear issues
- Defines scope and acceptance criteria
- Keeps backlog aligned with completed work

### Documentation Owner
- Maintains repository documentation
- Checks clarity and consistency
- Keeps public-safe boundaries visible

### Automation Owner
- Maintains GitHub Actions workflows
- Keeps automation lightweight
- Avoids hidden or unclear execution paths

### Release Owner
- Confirms checklist readiness
- Ensures release notes or changelog entries are considered
- Verifies issue-to-PR traceability

### Maintenance Owner
- Keeps core repository structure healthy
- Confirms required files remain present
- Flags outdated or duplicate documents

## Review Expectations

A pull request should identify which repository area it affects and whether any ownership review is needed before merge.
