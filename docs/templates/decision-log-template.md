# Decision Log Template

Use this template to record all significant decisions made during a project. Logging decisions prevents revisiting settled issues, improves onboarding, and creates an audit trail.

---

## Decision Log — [Project Name]

**Project Manager:** [Name]  
**Last updated:** YYYY-MM-DD

---

## Decisions

| ID | Date | Decision | Context & Problem | Options Considered | Decision Owner | Impact | Follow-up Actions | Status |
|----|------|----------|-------------------|--------------------|----------------|--------|-------------------|--------|
| D-001 | YYYY-MM-DD | [Short statement of the decision made] | [Why this decision was needed; what problem it solves] | Option A: … / Option B: … / Option C: … | [Name / Role] | [Who and what is affected; any downstream dependencies] | [Action items, owners, due dates] | Open / Implemented / Superseded |
| D-002 | | | | | | | | |
| D-003 | | | | | | | | |

---

## Field Guidance

| Field | Description |
|-------|-------------|
| **ID** | Sequential identifier (D-001, D-002 …) |
| **Date** | Date the decision was made (YYYY-MM-DD) |
| **Decision** | A one-sentence statement of what was decided. Start with an active verb (e.g., "Use PostgreSQL as the primary database.") |
| **Context & Problem** | Brief background: what triggered the decision, constraints, and any relevant data. |
| **Options Considered** | The realistic alternatives that were evaluated before making the decision. |
| **Decision Owner** | The person who made or is accountable for the decision (usually PM, PdM, or Tech Lead). |
| **Impact** | Who or what is affected. Include systems, teams, timelines, or budget implications. |
| **Follow-up Actions** | Concrete next steps that result from this decision, with owners and due dates. |
| **Status** | Open (under discussion) / Implemented / Superseded (replaced by another decision) |

---

## When to Log a Decision

Log a decision when it:
- Affects scope, timeline, budget, or architecture.
- Was reached after considering multiple options.
- May be questioned or revisited later.
- Involves a trade-off between quality, cost, or speed.

---

## RACI

| Artifact | Author | Approver | Consumers |
|----------|--------|----------|-----------|
| Decision Log | PM | PdM / Tech Lead | All team members, Stakeholders |
