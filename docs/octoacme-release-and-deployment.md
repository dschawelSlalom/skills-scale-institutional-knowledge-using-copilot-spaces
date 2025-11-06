# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

> **See also:** [OctoAcme Roles and Personas](octoacme-roles-and-personas.md) for detailed role descriptions and collaboration guidance.

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

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support
- [ ] [DevOps Specialist](octoacme-roles-and-personas.md#devops-specialist) monitors deployment and system health
- [ ] [Technical Lead](octoacme-roles-and-personas.md#technical-lead) available for technical escalations
- [ ] [Product Manager](octoacme-roles-and-personas.md#product-managers) communicates release to stakeholders

## Cross-Role Collaboration During Release
- **DevOps Specialist**: Executes deployment, monitors system health, coordinates rollback if needed
- **Technical Lead**: Reviews deployment plan, available for technical issues during release window
- **Product Manager**: Validates feature functionality, prepares release communications
- **Project Manager**: Coordinates timing, stakeholder notifications, and go/no-go decision
- **Developers**: On-call during deployment window for immediate bug fixes if needed
- **Business Analyst** (if applicable): Validates that deployed features meet acceptance criteria

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call ([DevOps Specialist](octoacme-roles-and-personas.md#devops-specialist))
  - Rollback to last known-good release if necessary
  - Triage root cause with [Technical Lead](octoacme-roles-and-personas.md#technical-lead) and team
  - Capture action items and schedule postmortem
  - [Project Manager](octoacme-roles-and-personas.md#project-managers) communicates status to stakeholders
  - [Product Manager](octoacme-roles-and-personas.md#product-managers) assesses business impact and prioritizes fix

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
