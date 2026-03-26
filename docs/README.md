# OctoAcme Process Documentation

This directory contains the process documents that describe how OctoAcme plans and delivers projects. Use this README as a starting point to navigate the full documentation set.

## Overview

OctoAcme runs projects through a lightweight but repeatable lifecycle: **Initiation → Planning → Execution → Release → Close & Retrospective**. Each stage has a clear entry gate so teams move forward only when the right level of alignment and clarity has been reached.

**Major workflows** follow the principle of "build small, verify often." Work is decomposed into shippable increments with acceptance criteria. Progress is tracked on a GitHub Projects board with columns — Backlog, Ready, In Progress, In Review, QA, Done — giving the whole team a shared view of flow. Pull requests are kept as small as practical (target ≤ 400 lines), must link to their originating issue and acceptance criteria, and require at least one approving review plus passing CI before merge.

**Personas and roles** are defined to keep decision-making clear and accountable. The Project Manager (PM) owns the delivery plan, schedule, risk register, and stakeholder communication. The Product Manager (PdM) defines outcomes, owns backlog prioritization, and tracks success metrics. Developers design, implement, test, and document their work. QA/Testing validates quality against acceptance criteria. Stakeholders provide inputs and sign-off at key milestones.

**Communication strategy** is designed around a regular cadence that surfaces blockers early. Daily standups keep the delivery team aligned; weekly PM–PdM syncs and delivery reviews track progress and risks; sprint or milestone demos close each increment with a shared demo and stakeholder review. Risks are captured in a Risk Register (ID, description, impact, likelihood, owner, mitigation, status) and escalated through a defined path — team → PM → Product Lead → Sponsor — when they cannot be resolved locally.

**Quality assurance (QA) practices** are built into every stage rather than added at the end. Unit tests and, where needed, integration tests are written alongside code; critical user flows are covered by end-to-end smoke tests; CI runs linting, tests, and security scanning on every PR. The Definition of Done (DoD) requires acceptance criteria to be met, CI to pass, release notes to be drafted, a rollback plan to be in place, and smoke tests to be ready before any release proceeds to staging and then production. After each sprint, release, or incident, the team runs a retrospective to convert learnings into actionable backlog items.

---

## Document Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Core principles, roles, key artifacts, and lifecycle summary |
| [Project Initiation](octoacme-project-initiation.md) | Problem statement, stakeholder alignment, charter, and initiation gate |
| [Project Planning](octoacme-project-planning.md) | Scope, backlog, milestones, estimates, and Definition of Done |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | Board workflow, PR process, cadence, and progress tracking |
| [Risks and Communication](octoacme-risks-and-communication.md) | Risk register, escalation path, and stakeholder communication templates |
| [Release and Deployment](octoacme-release-and-deployment.md) | Release checklist, deployment steps, rollback plan, and post-release verification |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retro formats, action tracking, and continuous improvement backlog |
| [Roles and Personas](octoacme-roles-and-personas.md) | Detailed responsibilities, goals, and communication patterns for each role |
