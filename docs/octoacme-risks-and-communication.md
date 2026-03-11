# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a risk register throughout the project lifecycle. Use the copy-pastable [Risk Register Template](templates/risk-register-template.md) which includes:
- ID
- Description
- Category (Technical / Schedule / Resource / External)
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Risk Score
- Owner
- Mitigation plan
- Contingency plan
- Status
- Date identified / Last reviewed

## Risk Lifecycle
- **Identify:** during planning and ongoing execution — any team member can raise a risk
- **Assess:** PM and owner assign Impact, Likelihood, and Score
- **Plan:** agree on Mitigation and Contingency actions
- **Monitor:** review all open risks at each weekly sync and update the register
- **Close:** retire risks that are no longer relevant or fully mitigated

## Escalation Thresholds
- 🔴 Critical / High risks → escalate to PdM / Product Lead within 24 hours
- 🟡 Medium risks → discuss in weekly PM sync
- 🟢 Low risks → monitor passively; review monthly

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates using the [Weekly Status Update Template](templates/weekly-status-update-template.md)
- Use a single source of truth (project README or release doc) for status

## Communication Cadence

| Meeting / Artifact | Frequency | Owner | Audience | Key Inputs | Key Outputs |
|--------------------|-----------|-------|----------|-----------|-------------|
| Daily Standup | Daily (15 min) | Scrum Master / PM | Delivery team | Progress, blockers | Impediment log updates |
| Weekly Delivery Sync | Weekly (30–60 min) | PM | PM, PdM, Tech Lead | Status, risks, decisions | Updated Risk Register, Decision Log |
| Weekly Status Update | Weekly | PM | All stakeholders | Delivery sync notes | [Status update](templates/weekly-status-update-template.md) distributed |
| Sprint Review / Demo | End of each sprint | PM / Scrum Master | Team + Stakeholders | Completed work | Stakeholder feedback |
| Retrospective | End of each sprint/release | Scrum Master | Delivery team | Sprint data, feedback | Action items |
| Monthly Stakeholder Update | Monthly | PM | Sponsors, Stakeholders | Weekly updates | Executive summary |

## Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level → PM → Product Lead → Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
