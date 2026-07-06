# Operating System (Execution Framework)

## Purpose

This document defines the execution model for how work is planned, decomposed, reviewed, and completed within this repository.

The repository functions as a **documentation + task orchestration system** supported by AI agents and GitHub workflows.

---

## Core Architecture

### 1. Intake Layer (Issues)
- All work begins as a GitHub Issue
- Each issue represents a single atomic objective
- Complex goals must be decomposed before execution

### 2. Execution Layer (Branches)
- Every implementation task is done in a feature branch
- Branch names follow:
  - `feature/<short-name>`
  - `fix/<short-name>`
  - `docs/<short-name>`

### 3. Review Layer (Pull Requests)
- All changes require PR review
- PRs must include:
  - Purpose
  - Changes summary
  - Risk assessment
  - Public-safe verification

### 4. Knowledge Layer (Docs)
- `/docs` contains system knowledge
- Must be structured, versioned, and reviewable
- No sensitive or confidential content allowed

---

## Execution Principles

### Atomic Work
Each task must:
- Solve one problem only
- Be independently reviewable
- Not depend on hidden context

### Public Safety
Never include:
- Credentials
- Private investor or legal content
- Proprietary technical systems
- Confidential financial data

### Determinism
- Avoid vague language
- Avoid assumptions without labeling them
- Always define inputs and outputs

---

## AI Agent Behavior

Agents must:
- Follow AGENTS.md rules
- Validate public safety before writing files
- Break large tasks into smaller issues
- Prefer clarity over optimization

---

## Workflow Summary

1. Issue created
2. Planning done (if needed)
3. Branch created
4. Implementation executed
5. PR opened
6. Review completed
7. Merge to main

---

## Success Criteria

A system is considered healthy when:

- All tasks are traceable via issues
- No direct commits to main without review
- No confidential data exists in repo
- Documentation stays synchronized with execution
