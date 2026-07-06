# Release Checklist

## Purpose

This checklist defines the standard release-readiness review for repository changes.

## Release Readiness Checklist

### Scope
- [ ] Related issue exists
- [ ] Scope is clear
- [ ] Acceptance criteria are listed
- [ ] Change is small enough to review

### Documentation
- [ ] Documentation is updated where needed
- [ ] Backlog is updated if phase status changed
- [ ] New documents use clear headings
- [ ] Public-safe language is maintained

### Automation
- [ ] Required workflow files remain present
- [ ] Automation changes are lightweight
- [ ] Workflow intent is understandable from file names and steps
- [ ] No hidden merge or bypass behavior is introduced

### Review
- [ ] Pull request summary explains what changed
- [ ] Pull request body explains why it changed
- [ ] Changed files match the stated scope
- [ ] Ownership or maintenance review is considered

### Release Notes
- [ ] Changelog entry is considered
- [ ] Version impact is identified if applicable
- [ ] Follow-up tasks are captured as issues

## Merge Readiness

A pull request is ready to merge when:

1. The checklist is complete or explicitly not applicable.
2. The change is traceable to an issue.
3. The branch is current enough for review.
4. The repository remains clear, public-safe, and maintainable.

## Post-Merge Actions

- Close the related issue as completed.
- Confirm the backlog reflects the merged state.
- Create follow-up issues for any deferred work.
