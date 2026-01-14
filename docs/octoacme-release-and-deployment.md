# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged (validated by Business Analyst, QA)
- Passing CI and security scans (reviewed by Tech Lead)
- Release notes drafted (PM, with input from PdM and Support Lead)
- Rollback / mitigation plan documented (Tech Lead, PM)
- Smoke tests prepared and passing (QA, UX Designer for user flows)
- Support documentation and runbooks updated (Support Lead)
- Known issues documented for support team (Support Lead, QA)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) — PM coordinates
- [ ] Backup or snapshot (if applicable) — Tech Lead verifies
- [ ] Deploy to staging and run smoke tests — QA, UX Designer validate
- [ ] Support team briefed on changes — Support Lead facilitates
- [ ] Deploy to production (automated pipeline preferred) — Tech Lead monitors
- [ ] Run post-deploy verifications — QA, Tech Lead
- [ ] Announce release to stakeholders and support — PM, Support Lead

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (Support Lead coordinates)
  - Rollback to last known-good release if necessary (Tech Lead executes, PM approves)
  - Triage root cause and capture action items (Tech Lead leads technical analysis, Scrum Master tracks action items)
  - Communicate status to stakeholders (PM, Support Lead)
  - Conduct post-incident review (all relevant roles participate)

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
