# Security & Confidentiality Rules (Public Repository)

## Purpose

This document defines strict rules for ensuring that no sensitive, private, or restricted information is ever stored in this public repository.

---

## Absolute Prohibitions

The following must NEVER be committed:

- API keys or credentials
- Private tokens or secrets
- Private legal agreements or contracts
- Investor materials or funding discussions
- Financial models or projections
- Proprietary engineering designs
- Internal corporate strategy documents
- Personal data (emails, phone numbers, addresses)
- Government, defense, or restricted technical data

---

## Sensitive Data Handling Rule

If a task requires restricted data:

> Replace with: "Private source required — do not store in public repository."

Do NOT attempt to approximate or reconstruct sensitive content.

---

## Data Classification

| Type | Allowed in Public Repo |
|------|----------------------|
| General documentation | ✅ Yes |
| System architecture (high-level) | ✅ Yes |
| Product concepts (non-sensitive) | ✅ Yes |
| Internal financial models | ❌ No |
| Legal agreements | ❌ No |
| Investor decks | ❌ No |
| Private code systems | ❌ No |

---

## AI Agent Constraints

Agents must:

1. Refuse to store restricted data
2. Flag any ambiguous content as sensitive
3. Default to safe abstraction
4. Prioritize public safety over completeness

---

## Safe Alternatives

Instead of sensitive content, use:

- High-level descriptions
- System diagrams without proprietary details
- Placeholder structures
- Abstract workflow definitions

---

## Incident Handling

If sensitive data is accidentally committed:

1. Remove immediately via PR revert
2. Purge from branch history if needed
3. Mark issue as security incident
4. Rebuild content in safe form

---

## Compliance Principle

Public repository integrity is mandatory.
No exceptions.
