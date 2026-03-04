# Red Team Lab Infrastructure (Safe IaC)

## Overview
Reusable infrastructure for the local lab:
- Reproducible VM provisioning (IaC)
- Automated setup for users/logging/secrets rotation (lab-safe)
- CI lint/test + 1-click environment creation (local)

## Scope (No evasion guidance)
Focus on reproducibility and safe operational practices for a lab environment.

## Tech Stack
- Terraform / Ansible / Vagrant (choose)
- CI: GitHub Actions
- Secrets hygiene: .env.example, no real secrets in repo

## Deliverables
- IaC code: iac/
- CI pipeline: .github/workflows/
- Architecture doc + risk register: docs/reports/

## Status
- [ ] IaC baseline
- [ ] Provisioning scripts
- [ ] CI checks
- [ ] Threat model + risk register
