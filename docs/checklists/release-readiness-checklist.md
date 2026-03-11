# Release Readiness Checklist

Use this checklist before every production deployment. All gates must be met (or explicitly waived with a documented reason) before release proceeds.

---

## Release Information

**Release version / tag:** [e.g., v1.2.0]  
**Release type:** Patch / Minor / Major  
**Planned deployment date/time:** YYYY-MM-DD HH:MM (timezone)  
**Deployment engineer:** [Name]  
**PM on-call:** [Name]  
**Rollback lead:** [Name]

---

## 1. Code & Quality Gates

- [ ] All acceptance criteria met and verified by QA
- [ ] All required PRs merged to the release branch
- [ ] No open P0/P1 bugs targeting this release
- [ ] CI pipeline passing (build, unit tests, integration tests)
- [ ] Security scan completed; no new critical/high vulnerabilities unresolved
- [ ] Dependency licenses reviewed (if new dependencies added)
- [ ] Code coverage meets team-defined threshold

---

## 2. Testing Gates

- [ ] Smoke tests passing in staging environment
- [ ] End-to-end critical-path tests passing
- [ ] Performance / load tests run (for significant changes)
- [ ] Accessibility checks completed (if applicable)
- [ ] Manual QA sign-off obtained from QA lead

---

## 3. Documentation & Release Notes

- [ ] Release notes drafted and reviewed
- [ ] User-facing documentation updated (if applicable)
- [ ] API changelog updated (if applicable)
- [ ] Internal runbooks updated to reflect new behavior

---

## 4. Deployment Readiness

- [ ] Deployment window scheduled and communicated
- [ ] Deployment runbook / steps documented and reviewed
- [ ] Environment configuration changes identified and staged
- [ ] Database migration scripts tested in staging (if applicable)
- [ ] Feature flags configured correctly for rollout strategy
- [ ] Monitoring dashboards and alerts reviewed / updated

---

## 5. Rollback & Incident Readiness

- [ ] Rollback plan documented and tested in staging
- [ ] Rollback trigger criteria defined (e.g., error rate > X%, SLO breach)
- [ ] On-call rotation confirmed for deployment window +2 hours
- [ ] Incident response runbook link shared with team
- [ ] Previous known-good release tag identified: [tag/SHA]

---

## 6. Stakeholder Communication

- [ ] Internal stakeholders notified of release date/time
- [ ] Support team briefed on new features and known issues
- [ ] Customer-facing communication prepared (if applicable)
- [ ] Release announcement drafted (Slack / email / changelog post)

---

## 7. Post-Deployment Verification

- [ ] Smoke tests run in production immediately after deployment
- [ ] Key success metrics checked (error rates, latency, conversion)
- [ ] Monitoring alerts fired as expected (or confirmed quiet)
- [ ] Release announcement sent to stakeholders
- [ ] Release notes published

---

## Waiver Process

If any gate cannot be met, document the waiver here:

| Gate | Reason for Waiver | Approved by | Date |
|------|-------------------|-------------|------|
| | | | |

---

## Entry Criteria (release readiness review can begin when)

- Code freeze reached on release branch
- All acceptance criteria closed in the project board
- Staging deployment successful

## Exit Criteria (release is approved to deploy when)

- All gates checked (or waivers approved)
- Deployment engineer and PM on-call confirmed
- Rollback plan in place

---

## RACI

| Artifact | Author | Approver | Consumers |
|----------|--------|----------|-----------|
| Release Readiness Checklist | PM / Deployment Engineer | PdM + QA Lead | PM, Devs, QA, Support, Stakeholders |
