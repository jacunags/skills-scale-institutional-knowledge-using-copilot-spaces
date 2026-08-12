# OctoAcme Project Management Docs

Welcome — this folder contains OctoAcme's project management process documentation and quick references for running projects from initiation through closure.

## Overview
OctoAcme runs projects with a lightweight, disciplined lifecycle that moves work from initiation through planning, execution, release, and continuous improvement. Work begins with a short Project One‑pager to capture the problem, measurable goals, stakeholders, and a high‑level timeline; that one‑pager plus an initial risk list and backlog skeleton are the minimum deliverables needed to gate planning. Planning breaks approved initiatives into shippable increments (backlog items with acceptance criteria, estimates, and owners), defines a Definition of Done, and maps release milestones.

Day‑to‑day execution is organized around a clear project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and frequent team rhythms: short daily standups to surface progress and blockers, weekly delivery syncs for status and risks, and demos at the end of sprints or milestones. Pull requests are intentionally small, include acceptance criteria and linked issues, and require passing CI (tests, linting, security scans) plus approvals before merging. Cross‑team dependencies and escalations follow defined paths and risks are tracked in the Risk Register.

Roles are explicit: Product Managers define outcomes and success metrics, Project Managers coordinate delivery and communications, Developers implement and test features, and QA validates acceptance criteria. This clarity supports efficient planning (capacity and estimation) and visible ownership of action items and risks. Communication cadence includes PM+PdM weekly alignment, regular standups, and monthly stakeholder updates.

Quality assurance and release practices emphasize automated and manual safeguards. Developers add unit and integration tests; critical flows get end‑to‑end smoke tests and CI includes security scanning. Releases follow a pre‑release checklist, deploy to staging for verification, then to production via automated pipelines when possible. A rollback and incident playbook is specified for failures and retrospectives capture improvements that feed back into the backlog.

## Process Documents
- 1. [Project Initiation Guide](octoacme-project-initiation.md)
- 2. [Project Planning](octoacme-project-planning.md)
- 3. [Execution & Tracking](octoacme-execution-and-tracking.md)
- 4. [Release & Deployment Guide](octoacme-release-and-deployment.md)
- 5. [Risk Management & Communication](octoacme-risks-and-communication.md)
- 6. [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- 7. [Roles & Personas](octoacme-roles-and-personas.md)

## Quick Navigation by Project Phase
| Phase | Primary Documents | Key Activities |
|-------|-------------------|----------------|
| Initiation | Project Initiation Guide | One-pager, stakeholder alignment, decision gate |
| Planning | Project Planning, Roles & Personas | Backlog creation, estimation, risks |
| Execution | Execution & Tracking, Risk Management | Daily standups, PR reviews, progress tracking |
| Release | Release & Deployment, Risk Management | Deployment checklist, smoke tests, announce |
| Closure | Retrospective & Continuous Improvement | Capture learnings, action items |

## How to Use These Docs
1. For new projects: start with the Project Initiation Guide.
2. For ongoing work: follow phase-specific docs and use the checklists.
3. For issues or escalations: check Risk Management & Communication.
4. To propose improvements: use the Add Content to Project Management Process Docs issue template: ../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml

## Contributing
Please propose updates via the provided issue template. Document updates should align with existing process docs and be reviewed as appropriate.
