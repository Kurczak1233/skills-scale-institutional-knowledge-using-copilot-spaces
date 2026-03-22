# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation repository. This README provides an overview of how the OctoAcme team manages projects and links to all detailed process documents.

## Summary of Project Management Processes

OctoAcme's project management approach is designed to be lightweight, repeatable, and easy for cross-functional teams to follow. Work moves through a clear lifecycle — **Initiation → Planning → Execution → Release → Close/Retrospective** — supported by shared artifacts such as a project one-pager, a prioritized backlog with acceptance criteria, a risk register, and retrospective action items. In initiation, the team validates the business need, aligns stakeholders, and makes a go/no-go decision; planning converts the initiative into an actionable backlog with estimates, a Definition of Done, an initial QA approach, and explicit dependency tracking.

Roles are intentionally explicit to reduce confusion and improve ownership. A **Project Manager (PM)** coordinates delivery — schedules, risks, dependencies, and communications — while a **Product Manager (PdM)** defines outcomes, prioritizes the backlog, and measures success. **Developers** implement features and tests and surface technical risks; **QA/Testing** validates acceptance criteria; and **Stakeholders** provide input and approvals at key milestones. This clarity ensures the team always has a consistent source of truth.

Execution emphasizes consistent team rhythm and visible workflow state. Teams maintain a project board (Backlog → Ready → In Progress → In Review → QA → Done), daily standups for blockers, a weekly delivery sync for progress and risks, and sprint demos. Risk management uses a structured **risk register** (impact, likelihood, owner, mitigation, status) with a defined escalation path: triage within the team first, PM escalation to product/dependent teams, then sponsor escalation for business-impacting issues. Stakeholder updates follow standard templates and aim to keep communication centralized and predictable.

Quality assurance is built into both the development flow and release discipline. OctoAcme prefers small pull requests that include issue links and acceptance criteria, and requires automated checks (tests, linting, security scanning) plus at least one approval before merge. Testing practices include unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows. Releases require that acceptance criteria are met, CI/security scans pass, release notes and rollback plans are prepared, and deployments follow a staged checklist (staging + smoke tests → production → post-deploy verification). Blameless retrospectives after each milestone convert learnings into tracked action items for continuous improvement.

## Project Management Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
