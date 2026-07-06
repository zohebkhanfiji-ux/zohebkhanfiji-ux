# Agent Workflows

## Purpose

This document defines how AI agents, Codex systems, and automation tools should collaborate within this repository.

## Agent Types

### 1. Planning Agent
- Breaks large objectives into issues
- Ensures tasks are atomic

### 2. Execution Agent
- Implements changes in feature branches
- Keeps changes small and reviewable

### 3. Review Agent
- Validates correctness
- Checks documentation consistency
- Ensures public safety rules are followed

### 4. Security Agent
- Blocks sensitive data leaks
- Enforces public-safe boundaries

### 5. CI Agent
- Runs GitHub workflows
- Validates repository health

## Workflow Cycle

1. Issue created
2. Planning agent structures task
3. Execution agent implements in branch
4. CI agent runs validation
5. Review agent checks PR
6. Merge after approval

## Communication Rules

- Use issues for structured work
- Use PRs for implementation review
- Avoid direct commits to main
- Keep all changes traceable

## Safety Rules

- Never store secrets
- Never include private or proprietary data
- Always default to public-safe abstraction
