# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Entry Criteria
Execution begins when Planning is complete:
- Sprint 1 backlog populated and estimated
- Definition of Done agreed by PM, PdM, Devs, and QA
- Risk Register initialized and reviewed

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks; update [Risk Register](templates/risk-register-template.md) and [Decision Log](templates/decision-log-template.md)
- Demo/Review at the end of each sprint or milestone
- Weekly [Status Update](templates/weekly-status-update-template.md) distributed to stakeholders every Friday

## Definition of Done (DoD)
A work item is done when all of the following are met:
- [ ] All acceptance criteria met
- [ ] Code reviewed and approved (at least one reviewer)
- [ ] Automated tests written and passing
- [ ] CI pipeline passing (build, lint, test, security scan)
- [ ] QA sign-off obtained
- [ ] Documentation updated (if applicable)
- [ ] Item demonstrated in a sprint review or demo

_The DoD must be agreed by PM, PdM, Devs, and QA at the start of Planning and reviewed each quarter or after major process changes._

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)
- Log significant design or architectural decisions in the [Decision Log](templates/decision-log-template.md)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)
- Distribute [Weekly Status Update](templates/weekly-status-update-template.md) every Friday

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly (see [Risk Register Template](templates/risk-register-template.md))
- [ ] Decision log maintained for significant decisions (see [Decision Log Template](templates/decision-log-template.md))
- [ ] Weekly status update distributed to stakeholders (see [Status Update Template](templates/weekly-status-update-template.md))

## Exit Criteria
Execution phase is complete when:
- All planned scope delivered or explicitly deferred
- All P0/P1 defects resolved
- Release readiness review passed (see [Release Readiness Checklist](checklists/release-readiness-checklist.md))
- Retrospective scheduled
