# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged (verified by QA and Business Analyst)
- Passing CI and security scans
- Release notes drafted (Release Manager)
- Rollback / mitigation plan documented (Release Manager with DevOps)
- Smoke tests prepared (QA)
- UX review completed for UI changes (UX Designer)

## Deployment Checklist
- [ ] Deployment window scheduled (Release Manager)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests (QA and Release Manager)
- [ ] Deploy to production (automated pipeline preferred, coordinated by Release Manager)
- [ ] Run post-deploy verifications (QA and Release Manager)
- [ ] Announce release to stakeholders and support (Release Manager with Project Manager)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (Release Manager leads)
  - Rollback to last known-good release if necessary (Release Manager coordinates)
  - Triage root cause and capture action items (Release Manager with Project Manager)
  - Conduct post-incident retrospective (Scrum Master facilitates)

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
