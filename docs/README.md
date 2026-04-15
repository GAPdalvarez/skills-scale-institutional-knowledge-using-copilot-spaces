# OctoAcme Project Management Docs

OctoAcme uses a lightweight, repeatable delivery lifecycle for cross-functional work: **Initiation → Planning → Execution → Release → Close & Retrospective**. In initiation, teams confirm the business problem, measurable outcomes, and stakeholder alignment through core artifacts such as a one-pager, initial risks, and milestone framing. Work moves forward only after a clear go/no-go decision gate.

In planning, teams convert approved initiatives into a prioritized backlog of shippable increments with explicit acceptance criteria, estimates, owners, and dependencies. During execution, delivery is coordinated through a project board workflow (**Backlog, Ready, In Progress, In Review, QA, Done**) and a disciplined PR process that favors small changes, issue linkage, CI checks, and review before merge.

Ownership is shared across defined personas: **Project Managers (PMs)** drive schedules, coordination, risk handling, and communications; **Product Managers (PdMs)** own outcomes, prioritization, and success metrics; **Developers** design, build, and test; **QA/Testing** validates acceptance criteria and quality; and **Stakeholders** provide directional input and approvals. Communication follows regular cadences (standups, weekly delivery syncs, stakeholder updates), uses a single source of truth for status, and applies an escalation path from team triage to PM, Product Lead, and Sponsor.

Quality assurance is layered throughout delivery and release: unit and integration coverage where applicable, CI-based lint/test/security scanning, code reviews, smoke tests before production release, and manual QA when needed for feature acceptance. Releases are run with pre-release checks, deployment and verification checklists, and rollback/incident readiness. Each project closes with a blameless retrospective that converts lessons into owned, trackable improvements.

## Documentation Index

- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
- [OctoAcme — Project Initiation Guide](./octoacme-project-initiation.md)
- [OctoAcme — Project Planning](./octoacme-project-planning.md)
- [OctoAcme — Execution & Tracking](./octoacme-execution-and-tracking.md)
- [OctoAcme — Risk Management & Communication](./octoacme-risks-and-communication.md)
- [OctoAcme — Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [OctoAcme — Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [OctoAcme Personas](./octoacme-roles-and-personas.md)

## How to use these docs

- Start with the overview, then follow the lifecycle documents from initiation through retrospective.
- Keep your project one-pager/README updated as the single source of truth for status, decisions, and success metrics.
- Add process-specific guidance to `.copilot/` when you want Copilot Spaces to use it as working context.
