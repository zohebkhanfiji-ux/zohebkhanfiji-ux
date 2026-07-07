# Solar Module Opportunity Command

End-to-end operating system for identifying, qualifying, pricing, proposing, submitting, and converting solar module supply opportunities.

## Mission

Create a repeatable agent-led business development workflow for solar module supply opportunities across federal, utility, EPC, developer, distributor, and strategic-buyer channels.

## Operating Scope

| Channel | Opportunity Type | Primary Output | Lead Agent |
|---|---|---|---|
| Federal / SAM.gov | RFIs, RFQs, RFPs, IFBs, sources-sought notices | Bid/no-bid package | SAM.gov Monitoring Agent |
| DOE / Energy Funding | Manufacturing, supply-chain, domestic production, demonstration funding | Funding capture brief | DOE Funding Agent |
| Utility / IPP | Bulk module procurement and framework supply agreements | Commercial pursuit brief | Utility / IPP Agent |
| EPC / Developer | Project-specific module supply packages | Quote and proposal package | EPC / Developer Agent |
| Distributor | Channel supply and container-level sales | Price sheet and channel offer | Distributor Channel Agent |
| Strategic Buyer | Data centers, defense, microgrids, federal facilities | Strategic account proposal | Strategic Buyer Agent |

## Core Workflow

1. Source monitoring
2. Opportunity intake
3. Duplicate and deadline check
4. Qualification scoring
5. Bid / no-bid decision
6. Product fit review
7. Supply-chain and lead-time validation
8. Pricing build
9. Compliance review
10. Proposal package build
11. Executive approval
12. Submission
13. Q&A / BAFO / clarification
14. Award or no-bid archive
15. Delivery execution handoff

## Required Review Gates

| Gate | Required Before Moving Forward |
|---|---|
| Intake Gate | Source, buyer, due date, and submission path captured |
| Qualification Gate | Scorecard completed and bid/no-bid decision recorded |
| Product Gate | Module family, wattage, warranty, certification, and domestic-content fit confirmed |
| Pricing Gate | Price per watt, freight, payment terms, margin, and approvals completed |
| Compliance Gate | Certifications, domestic-content, Buy America, UFLPA, insurance, and buyer forms reviewed |
| Legal/Risk Gate | Contract exceptions, LDs, indemnity, warranty exposure, and payment risk reviewed |
| Submission Gate | Final package checked, uploaded, and confirmation receipt saved |

## Repository Map

```text
solar-module-opportunity-command/
├── README.md
├── AGENT-OPERATING-MANUAL.md
├── agents/
│   ├── AGENT-REGISTRY.md
│   ├── 00-command-agent.md
│   ├── 01-monitoring-agents.md
│   ├── 02-qualification-agent.md
│   ├── 03-product-fit-agent.md
│   ├── 04-pricing-agent.md
│   ├── 05-compliance-risk-agent.md
│   ├── 06-proposal-submission-agent.md
│   └── 07-post-submission-agent.md
├── templates/
│   ├── opportunity-intake-template.md
│   ├── bid-no-bid-template.md
│   ├── pricing-request-template.md
│   ├── compliance-checklist.md
│   └── proposal-outline.md
├── data-models/
│   └── opportunity.schema.json
└── dashboards/
    └── pipeline-kpis.md
```

## GitHub Project Board Columns

```text
Raw Intake
Initial Review
Qualified
Pricing Required
Proposal Build
Risk Review
Ready for Approval
Submitted
Award / PO
No-Bid / Lost
```

## Priority Labels

```text
source:samgov
source:doe
source:utility
source:epc
source:distributor
type:module-supply
type:solar-storage
status:intake
status:qualified
status:pricing
status:proposal
status:submitted
status:award-pending
priority:p1
risk:compliance
risk:delivery
risk:legal
dc-required
exec-review
```

## Activation Order

| Phase | Agent | Objective |
|---:|---|---|
| 1 | Command Agent | Control pipeline and review gates |
| 2 | Monitoring Agents | Detect new opportunities |
| 3 | Qualification Agent | Score and prioritize |
| 4 | Product Fit Agent | Confirm product match |
| 5 | Pricing Agent | Build price and margin package |
| 6 | Compliance / Risk Agent | Prevent disqualifying errors |
| 7 | Proposal / Submission Agent | Package and submit |
| 8 | Post-Submission Agent | Manage Q&A, BAFO, award follow-up |

## Operating Rule

No opportunity may move to Proposal Build unless Product Fit, Pricing, Supply Chain, and Compliance have been reviewed and documented.
