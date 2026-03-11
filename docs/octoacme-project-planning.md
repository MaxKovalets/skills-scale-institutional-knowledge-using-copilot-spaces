# OctoAcme — Project Planning

## Purpose
Turn an approved initiative into an actionable plan and backlog for delivery.

## Objectives
- Break work into shippable increments
- Identify dependencies and risks
- Align timelines, releases, and responsibilities

## Entry Criteria
Move to Planning when the Initiation gate has passed:
- Project One-pager approved by PdM / Product Lead
- Stakeholder alignment confirmed
- Team roster and capacity confirmed

## Activities
1. Kickoff meeting with stakeholders and delivery team — see [Project Kickoff Checklist](checklists/project-kickoff-checklist.md)
2. Create prioritized backlog with acceptance criteria
3. Estimate scope (T-shirt sizing or story points)
4. Define Definition of Ready and Definition of Done (DoD) — see section below
5. Identify dependencies and integration points
6. Create release plan and milestone map
7. Initialize [Decision Log](templates/decision-log-template.md) with kickoff decisions

## Backlog Item Template
- Title:
- Description:
- Acceptance criteria:
- Priority:
- Estimate:
- Owner:
- Related docs/links:

## Definition of Ready (DoR)
A backlog item is ready to be pulled into a sprint when:
- [ ] Problem/user story is clearly described
- [ ] Acceptance criteria are written and agreed with PdM
- [ ] Dependencies identified and unblocked (or risk noted)
- [ ] Estimate provided by the team
- [ ] Designs / specs available (if applicable)

## Definition of Done (DoD)
A work item is considered done when:
- [ ] All acceptance criteria met
- [ ] Code reviewed and approved (at least one reviewer)
- [ ] Automated tests written and passing
- [ ] CI pipeline passing (build, lint, test, security scan)
- [ ] QA sign-off obtained
- [ ] Documentation updated (if applicable)
- [ ] Item demonstrated in a sprint review or demo

## Sprint / Iteration Planning
- Timebox planning to agreed sprint length
- Pull items that meet the Definition of Ready and have clear acceptance criteria
- Ensure team capacity is respected
- Record planning decisions in the [Decision Log](templates/decision-log-template.md)

## Risk & Dependency Management
- Initialize and maintain the [Risk Register](templates/risk-register-template.md):
  - ID, Description, Impact, Probability, Owner, Mitigation
- Mark cross-team dependencies in the project board and escalate during weekly syncs

## Planning Checklist
- [ ] Project kickoff held (see [Kickoff Checklist](checklists/project-kickoff-checklist.md))
- [ ] Backlog prioritized and estimated
- [ ] Release timeline and milestones agreed
- [ ] Definition of Ready documented and shared
- [ ] Definition of Done documented and agreed by team
- [ ] [Risk Register](templates/risk-register-template.md) initialized
- [ ] [Decision Log](templates/decision-log-template.md) initialized
- [ ] Initial test plan / QA approach drafted

## Exit Criteria
Planning is complete and Execution can begin when:
- Kickoff checklist fully completed
- Sprint 1 backlog populated and estimated
- DoD agreed by PM, PdM, Devs, and QA
- Risk Register has at least one review cycle complete
