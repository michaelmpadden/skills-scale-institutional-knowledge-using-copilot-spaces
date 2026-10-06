# OctoAcme Project Management Docs

Welcome to the OctoAcme project management process documentation. This folder contains the guidance, checklists, and templates used to run projects consistently across OctoAcme.

## Overview

OctoAcme uses a lightweight, structured project management approach focused on:
- **Clear ownership** — each project has a named Project Manager (PM) and Product Manager (PdM)
- **Iterative delivery** — small, testable increments with regular demos and feedback
- **Risk management** — proactive identification, assessment, and mitigation of blockers and dependencies
- **Regular communication** — daily standups, weekly syncs, and transparent status updates to stakeholders
- **Continuous improvement** — retrospectives after sprints and releases to capture learnings and drive iterative process improvements

The process spans five key phases: **Initiation** → **Planning** → **Execution** → **Release** → **Close & Retrospective**.

## Project Lifecycle

### 1. Initiation
Validate business need, align stakeholders, and decide go/no-go for planning.
- **Output:** Project One-pager with problem statement, success metrics, stakeholders, timeline, and risks
- **Decision gate:** Approval to move into planning phase

**Read:** [OctoAcme — Project Initiation Guide](./octoacme-project-initiation.md)

### 2. Planning
Turn the approved initiative into an actionable plan, backlog, and risk/dependency view.
- **Output:** Prioritized backlog with acceptance criteria, release timeline, Definition of Done, risk register, and integration points
- **Key activities:** Kickoff, estimation, dependency mapping, test planning

**Read:** [OctoAcme — Project Planning](./octoacme-project-planning.md)

### 3. Execution
Build, test, and deliver increments through team rhythms and quality checks.
- **Team cadence:** Daily standups (15 min), weekly delivery syncs, demos at sprint/milestone boundaries
- **Quality:** Unit tests, integration tests, end-to-end smoke tests, security scanning in CI, manual QA as needed
- **Tracking:** GitHub Projects board, velocity, burndown, and success metrics

**Read:** [OctoAcme — Execution & Tracking](./octoacme-execution-and-tracking.md)

### 4. Release
Standardize production deployment to reduce risk and improve observability.
- **Pre-release:** Acceptance criteria met, CI/security scans pass, release notes drafted, smoke tests prepared
- **Post-deploy:** Verification, announcement, and rollback playbook if needed

**Read:** [OctoAcme — Release & Deployment Guide](./octoacme-release-and-deployment.md)

### 5. Close & Retrospective
Capture learnings and convert them into actionable improvements.
- **Retrospective:** What went well, what could improve, 2–3 prioritized action items with owners and timelines
- **Continuous improvement:** Track action items, measure impact, celebrate improvements

**Read:** [OctoAcme — Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## Key Resources

### Process Documents
- **[OctoAcme Project Management Overview](./octoacme-project-management-overview.md)** — Concise intro to OctoAcme's approach, principles, roles, and artifacts
- **[OctoAcme Personas](./octoacme-roles-and-personas.md)** — Definitions and responsibilities for Developers, Product Managers, Project Managers, and Stakeholders
- **[OctoAcme Risk Management & Communication](./octoacme-risks-and-communication.md)** — Risk registers, escalation paths, stakeholder communication templates

### How to Use These Docs
1. **New to OctoAcme?** Start with [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) for a quick orientation.
2. **Starting a new project?** Follow [OctoAcme — Project Initiation Guide](./octoacme-project-initiation.md), then [OctoAcme — Project Planning](./octoacme-project-planning.md).
3. **In execution?** Reference [OctoAcme — Execution & Tracking](./octoacme-execution-and-tracking.md) and [OctoAcme Risk Management & Communication](./octoacme-risks-and-communication.md) for day-to-day guidance.
4. **Preparing for release?** Use [OctoAcme — Release & Deployment Guide](./octoacme-release-and-deployment.md).
5. **Running a retrospective?** See [OctoAcme — Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md).

### Roles & Responsibilities
For guidance on specific roles, see [OctoAcme Personas](./octoacme-roles-and-personas.md):
- **Developers** — design, build, test, and deliver features
- **Product Managers** — define what to build and measure outcomes
- **Project Managers** — coordinate delivery, manage risks, and enable team efficiency
- **QA/Testing** — validate quality and acceptance criteria
- **Stakeholders** — provide inputs and approvals

## Single Source of Truth

These docs serve as the **single source of truth** for OctoAcme's project management processes. Keep them updated as processes evolve and new learnings emerge. To propose updates or additions, see the [Issue Template for Process Doc Updates](./.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).

## Quick Links

| Phase | Document | Purpose |
|-------|----------|---------|
| Initiation | [Project Initiation Guide](./octoacme-project-initiation.md) | Validate need, align stakeholders, decide go/no-go |
| Planning | [Project Planning](./octoacme-project-planning.md) | Create actionable plan, backlog, and risk view |
| Execution | [Execution & Tracking](./octoacme-execution-and-tracking.md) | Manage day-to-day delivery, quality, and progress |
| Risk & Comms | [Risk Management & Communication](./octoacme-risks-and-communication.md) | Identify risks, manage escalations, communicate status |
| Release | [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Standardize production rollout and verification |
| Retrospective | [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings, drive improvements |
| Reference | [Project Management Overview](./octoacme-project-management-overview.md) | High-level intro and key principles |
| Reference | [OctoAcme Personas](./octoacme-roles-and-personas.md) | Role definitions and responsibilities |

---

**Questions?** Refer to the appropriate phase guide or reach out to your Project Manager or Product Lead.
