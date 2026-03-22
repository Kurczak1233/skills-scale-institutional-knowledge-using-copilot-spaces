# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared
- QA Lead has provided release readiness sign-off
- Support Specialist has reviewed release notes and confirmed support documentation is up to date

### DevOps Engineer Responsibilities
The **DevOps Engineer** owns the deployment process end-to-end:
- Maintains CI/CD pipelines and deployment runbooks
- Schedules deployment windows and communicates them to the Project Manager
- Executes staged rollouts and monitors post-deploy signals (errors, latency, availability)
- Is the primary responder for deployment failures and coordinates rollback decisions
- Partners with the QA Lead to provision and maintain test and staging environments

See `octoacme-raci-mapping.md` for the full release-related RACI.

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

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
