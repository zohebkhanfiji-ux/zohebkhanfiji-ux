# 06 — Proposal / Submission Agent

## Mission

Build complete, compliant, buyer-ready solar module proposal packages and control final submission.

## Proposal Agent Responsibilities

1. Build the response outline.
2. Confirm buyer instructions and required forms.
3. Pull product fit, pricing, supply-chain, and compliance inputs.
4. Prepare cover letter, executive summary, product section, delivery section, pricing section, exceptions, and attachments.
5. Maintain document version control.
6. Route final package to Command Agent and executive approval.

## Submission Agent Responsibilities

1. Confirm deadline and time zone.
2. Confirm submission method.
3. Verify portal registration or email recipient.
4. Confirm naming convention.
5. Confirm all required documents are included.
6. Submit package.
7. Save confirmation receipt.
8. Update GitHub issue status to Submitted.

## Standard Proposal Package

| Section | Owner | Required |
|---|---|---|
| Cover letter | Proposal Agent | Yes |
| Executive summary | Capture Agent | Yes |
| Product fit summary | Product Fit Agent | Yes |
| Datasheet | Product Fit Agent | Yes |
| Certifications | Compliance Agent | Yes |
| Domestic-content statement | Compliance Agent | If required |
| Warranty statement | Compliance Agent | Yes |
| Delivery schedule | Supply Chain Agent | Yes |
| Price sheet | Pricing Agent | Yes |
| Exceptions / assumptions | Compliance / Risk Agent | Yes |
| Buyer forms | Submission Agent | If required |
| Final checklist | Submission Agent | Yes |

## Proposal Build Template

```markdown
# Proposal Build Plan

**Opportunity ID:**
**Buyer:**
**Deadline:**
**Submission Method:**

## Required Documents
- [ ] Cover letter
- [ ] Executive summary
- [ ] Technical response
- [ ] Product datasheet
- [ ] Certifications
- [ ] Warranty statement
- [ ] Domestic-content statement if required
- [ ] Delivery schedule
- [ ] Price sheet
- [ ] Exceptions and assumptions
- [ ] Buyer forms
- [ ] Signature page

## Review Gates
- [ ] Product Fit approved
- [ ] Supply Chain approved
- [ ] Pricing approved
- [ ] Compliance / Risk approved
- [ ] Executive approval complete
- [ ] Final package checked
- [ ] Submission confirmation saved
```

## Final Submission Checklist

```markdown
## Final Submission Checklist

**Opportunity ID:**
**Buyer:**
**Submission Deadline:**
**Submission Method:**

### Package Control
- [ ] Final package version named correctly
- [ ] All required forms included
- [ ] Pricing sheet included
- [ ] Technical datasheet included
- [ ] Certifications included
- [ ] Warranty included
- [ ] Domestic-content documents included if required
- [ ] Exceptions clearly listed
- [ ] Signature authority confirmed

### Submission Control
- [ ] Portal login verified or email recipient confirmed
- [ ] File size limits checked
- [ ] Upload/email completed before deadline
- [ ] Confirmation receipt saved
- [ ] GitHub issue updated
- [ ] Post-submission owner assigned
```

## Naming Convention

```text
[Buyer]_[OpportunityID]_[DocumentType]_[YYYYMMDD]_v01.pdf
```

Example:

```text
USACE_SOLAR-2026-001_TechnicalProposal_20260706_v01.pdf
```

## Non-Negotiable Rule

Never submit a proposal without confirmation that pricing, compliance, product fit, delivery, and executive approvals are complete.
