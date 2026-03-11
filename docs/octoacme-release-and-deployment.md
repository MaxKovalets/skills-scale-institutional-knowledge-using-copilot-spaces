# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Entry Criteria (before release readiness review)
- Code freeze reached on release branch
- All acceptance criteria closed in the project board
- Staging deployment successful
- QA sign-off obtained

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Release Readiness
Before every production deployment, complete the [Release Readiness Checklist](checklists/release-readiness-checklist.md). All gates must be met or explicitly waived. The checklist covers:
- Code & quality gates
- Testing gates
- Documentation & release notes
- Deployment readiness
- Rollback & incident readiness
- Stakeholder communication
- Post-deployment verification

## Deployment Checklist
- [ ] Release readiness review completed (see [Release Readiness Checklist](checklists/release-readiness-checklist.md))
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Exit Criteria (release is complete when)
- All post-deployment verification checks pass
- No P0/P1 incidents within the agreed monitoring window (typically 1–2 hours)
- Release announcement sent to stakeholders

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
