# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers (PdM / Product Lead)

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers (PM)

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA Engineers

### Role Summary
QA Engineers validate that features meet acceptance criteria and quality standards before release. They partner with Developers and PMs to prevent defects from reaching production.

### Responsibilities
- Author and execute test plans (unit, integration, end-to-end, regression)
- Triage and track defects to resolution
- Define and enforce the Definition of Done quality gates
- Participate in sprint planning to estimate QA effort
- Sign off on release readiness

### Goals
- Prevent regressions and critical defects in production
- Shorten the feedback loop between development and quality validation
- Build repeatable, automated test coverage over time

### Typical Communication
- Sprint ceremonies and daily standups
- QA sign-off reports before each release
- Defect triage discussions with Developers

---

## Scrum Master

### Role Summary
The Scrum Master facilitates agile ceremonies, removes impediments, and guides the team in agile practices to improve delivery flow.

### Responsibilities
- Facilitate sprint ceremonies (planning, daily standups, retrospectives, reviews)
- Track and escalate impediments blocking the team
- Coach the team on agile principles and continuous improvement
- Shield the team from unplanned interruptions during a sprint

### Goals
- Improve team velocity and delivery predictability
- Reduce cycle time for impediment resolution
- Foster a culture of self-organization and continuous improvement

### Typical Communication
- Daily standups and sprint ceremonies
- Impediment logs and resolution updates
- Coordination with PM on planning adjustments

### Interacts with
- PM (delivery plans and commitments)
- Developers (removes blockers)
- PdM / Product Lead (aligns sprint priorities)

---

## Business Analyst (BA)

### Role Summary
Business Analysts gather and translate business requirements into actionable work items, bridging the gap between stakeholders and the delivery team.

### Responsibilities
- Gather and document business requirements
- Translate business needs into user stories and acceptance criteria
- Document current and future-state workflows
- Validate that delivered features meet business intent

### Goals
- Ensure requirements are clear, complete, and testable before development starts
- Minimize rework caused by ambiguous or missing requirements
- Build a shared understanding of business processes across the team

### Typical Communication
- Requirements workshops and stakeholder interviews
- User story write-ups and acceptance criteria reviews
- Regular check-ins with PM and PdM on backlog readiness

### Interacts with
- PdM / Product Lead (defines requirements)
- PM (refines plan and backlog)
- Developers (clarifies specs)

---

## UX Designer

### Role Summary
UX Designers advocate for the end-user experience, create wireframes and prototypes, and run usability tests to validate designs before and after implementation.

### Responsibilities
- Research user needs and translate them into design requirements
- Create wireframes, mockups, and interactive prototypes
- Run usability tests and synthesize findings
- Collaborate with Developers on implementation fidelity
- Document design decisions and component guidelines

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce development rework through early design validation
- Maintain consistency with design system and brand standards

### Typical Communication
- Design reviews and critique sessions
- Usability test reports and findings summaries
- Collaboration in sprint planning and backlog refinement

### Interacts with
- PdM / Product Lead (feature specs and priorities)
- Developers (implementation guidance)
- Stakeholders (user feedback and sign-off)

---

## Support Engineer

### Role Summary
Support Engineers provide operational support, monitor deployed features, and triage incidents and bugs reported by customers or monitoring systems.

### Responsibilities
- Monitor production systems and respond to alerts
- Triage incoming bug reports and incidents
- Escalate P0/P1 issues to the development team
- Document workarounds and known issues for support documentation
- Participate in post-incident reviews

### Goals
- Maintain high service availability and customer satisfaction
- Reduce mean time to resolution (MTTR) for incidents
- Surface recurring issues that should be addressed in the product backlog

### Typical Communication
- Incident tickets and status updates
- Escalation notifications to Developers and PM
- Post-incident summaries and retrospective input

### Interacts with
- Developers (bug fixes and root-cause analysis)
- PM (status updates and risk escalation)
- Stakeholders (issue reporting and resolution updates)

---

## Stakeholder Champion

### Role Summary
The Stakeholder Champion ensures that diverse stakeholder perspectives are represented throughout the project, reviewing progress and flagging risks or concerns from the stakeholder community.

### Responsibilities
- Represent stakeholder interests in planning and review meetings
- Review project progress and validate alignment with business goals
- Surface concerns, risks, or conflicting priorities from stakeholders
- Participate in acceptance testing and release sign-off

### Goals
- Ensure the project delivers value to the stakeholder community
- Prevent scope gaps caused by missing stakeholder input
- Build stakeholder confidence and trust in the delivery team

### Typical Communication
- Regular briefings with PM (status and risks)
- Product roadmap discussions with PdM
- Acceptance sign-off communication with QA

### Interacts with
- PM (status and risk visibility)
- PdM / Product Lead (product vision and priorities)
- QA (acceptance criteria and sign-off)

---

## RACI Overview

The table below summarizes who writes (R), approves (A), is consulted (C), and is informed (I) for each key project artifact.

| Artifact | PM | PdM | Developers | QA | Scrum Master | BA | UX Designer | Support Engineer | Stakeholder Champion |
|----------|----|----|-----------|----|--------------|----|------------|-----------------|---------------------|
| Project One-pager | R | A | C | I | I | C | C | I | I |
| Backlog & User Stories | R | A | C | C | C | R | C | I | C |
| Risk Register | R | A | C | C | I | C | I | C | I |
| Decision Log | R | A | C | C | I | C | C | I | I |
| Weekly Status Update | R | A | I | I | I | I | I | I | I |
| Test Plan | C | I | C | R | I | C | I | I | I |
| Release Readiness | R | A | C | R | I | I | I | C | C |
| Retrospective Notes | R | C | R | R | R | C | C | C | C |
| Design Specs / Wireframes | I | C | C | C | I | C | R | I | C |
| Incident Report | C | I | R | C | I | I | I | R | I |

_Key: R = Responsible, A = Accountable, C = Consulted, I = Informed_

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

