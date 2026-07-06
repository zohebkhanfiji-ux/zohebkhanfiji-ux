# AGENTS.md

Operational instructions for AI agents, Codex, reviewers, and automation working in this repository.

## Mission

Create and maintain a clean, public-safe operating framework for Centauri-related documentation, planning, and future software workflows without exposing confidential business, legal, financial, investor, technical, or personal information.

## Primary Agent Roles

| Agent | Responsibility | Output Standard |
|---|---|---|
| Content Agent | Drafts clear public-safe documentation. | Neutral, precise, no unsupported claims. |
| QC Agent | Reviews accuracy, structure, consistency, and missing risks. | Finds gaps before work is marked complete. |
| Graphics/Brand Agent | Defines visual/document structure only; no proprietary brand assets unless approved. | Clean, professional, reproducible specs. |
| GitHub/Codex Agent | Maintains files, issues, PRs, and repo hygiene. | Small commits, clear PRs, safe changes. |
| Security Agent | Blocks secrets, personal data, private contracts, investor materials, and restricted data. | Public-safe by default. |

## Non-Negotiable Rules

1. Do not commit secrets, tokens, API keys, credentials, private URLs, or passwords.
2. Do not commit confidential investor, legal, financial, NASA/partner, customer, project, or personal records.
3. Do not represent drafts as final, signed, approved, funded, licensed, or legally binding unless a verified source in the repo supports it.
4. Do not fabricate citations, approvals, partnerships, contracts, board decisions, investor commitments, technical performance, or financial figures.
5. Keep work modular: one topic per issue, one coherent change per pull request.
6. Prefer Markdown, clear headings, tables, checklists, and traceable assumptions.
7. If private information is required, write: `Private source required — do not store in public repository.`

## Work Process

1. Read `README.md`, `docs/PROJECT_BRIEF.md`, and the relevant issue.
2. Confirm whether the requested work is public-safe.
3. Create or use a feature branch for substantive changes.
4. Make the smallest useful change.
5. Update docs and backlog when scope changes.
6. Open a pull request using `.github/pull_request_template.md`.
7. Run repository health checks before requesting review.

## Documentation Quality Bar

Every deliverable should answer:

- What is the objective?
- Who is the audience?
- What inputs are required?
- What is public-safe versus private?
- What are the assumptions?
- What are the risks or gaps?
- What is the next action?

## Public-Safe Language Rules

Use:

- `planned`, `proposed`, `draft`, `target`, `under review`, `subject to verification`

Avoid unless independently verified in the repo:

- `approved`, `confirmed`, `secured`, `completed`, `exclusive`, `guaranteed`, `final`, `funded`, `signed`

## File Naming

Use lowercase, hyphen-separated names for new files where possible:

- `docs/product-profile-framework.md`
- `docs/qc-checklist.md`
- `tasks/execution-plan.md`

## Completion Criteria

A task is complete only when:

- Required docs/files are updated.
- Public/private boundaries are checked.
- Risks and assumptions are visible.
- The PR checklist is complete.
- No secrets or confidential content are introduced.
