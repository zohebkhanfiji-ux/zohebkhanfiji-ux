# 01 — Opportunity Monitoring Agents

## Mission

Continuously identify new solar module supply opportunities and convert them into structured intake issues.

## Monitoring Agents

| Agent | Channel | Primary Target |
|---|---|---|
| SAM.gov Monitoring Agent | Federal | RFIs, RFQs, RFPs, IFBs, sources-sought notices |
| DOE Funding Agent | DOE / energy funding | Manufacturing, domestic supply chain, demonstrations |
| Utility / IPP Agent | Utilities and IPPs | Bulk module procurement and framework agreements |
| EPC / Developer Agent | EPCs and developers | Project-based supply opportunities |
| Distributor Channel Agent | Distributors and wholesalers | Container-level and regional supply demand |
| Strategic Buyer Agent | Data centers, defense, microgrids, federal facilities | Strategic supply and partnership pursuits |

## Search Keywords

```text
solar modules
photovoltaic modules
PV modules
solar panels
solar array
solar supply
solar procurement
domestic content solar
Buy America solar
BABA solar
utility-scale solar modules
solar and battery storage
microgrid solar
renewable energy modules
```

## Intake Creation Rule

Create an opportunity issue when at least four of the following are available:

- Buyer or agency name
- Opportunity title
- Source link or source record
- Due date or response window
- Required product or scope
- Estimated volume or project size
- Delivery location
- Submission method
- Contact or procurement office

## Source-Specific Instructions

### SAM.gov Monitoring Agent

Capture:

- Notice ID
- Agency / office
- Solicitation number
- Notice type
- Response deadline
- NAICS / PSC codes if available
- Set-aside status if available
- Place of performance
- Attachments required
- Whether modules, solar array, PV system, domestic content, or storage are mentioned

### DOE Funding Agent

Capture:

- Funding office
- FOA or notice number
- Concept paper deadline
- Full application deadline
- Eligibility
- Cost share
- Technology scope
- Manufacturing relevance
- Domestic supply-chain relevance
- Strategic fit

### Utility / IPP Agent

Capture:

- Utility / IPP name
- Procurement event name
- MW requirement
- Product specification
- Delivery location
- PPA/IPP tie-in if applicable
- Required supplier registration
- Deadline and submission method

### EPC / Developer Agent

Capture:

- EPC or developer name
- Project size
- Project location
- Needed module wattage and type
- Delivery window
- Commercial urgency
- Buyer contact
- Relationship history

### Distributor Channel Agent

Capture:

- Distributor name
- Product family needed
- Container count or MW/month
- Regional market
- Target price
- Payment terms
- Delivery terms
- Repeat-order potential

### Strategic Buyer Agent

Capture:

- Buyer type
- Strategic value
- Site or program context
- Energy need
- Module volume
- Storage/microgrid tie-in
- Security or domestic-content requirement
- Executive relationship owner

## Monitoring Output Format

```markdown
# Opportunity Intake Summary

## Source
- Source channel:
- Source link / record:
- Date detected:
- Monitoring agent:

## Buyer
- Buyer name:
- Buyer type:
- Procurement contact:

## Opportunity
- Title:
- Notice / solicitation number:
- Notice type:
- Deadline:
- Submission method:

## Technical Fit
- Estimated volume:
- Module wattage / type:
- Domestic content required:
- Certifications required:
- Delivery location:

## Initial Recommendation
- Suggested priority:
- Suggested next agent:
- Key blocker:
```

## Do Not Create Intake For

- General news without a procurement action
- Expired opportunities unless strategically useful
- Opportunities unrelated to solar modules, PV systems, solar + storage, manufacturing, or grid energy
- Buyers with no identity or no response path
- Duplicate notices already in the pipeline
