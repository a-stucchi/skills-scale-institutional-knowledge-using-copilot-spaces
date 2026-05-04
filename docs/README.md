# OctoAcme Project Management Documentation

This folder is the central index for all OctoAcme project management process documentation.

## Process Overview

OctoAcme follows a structured, lifecycle-driven approach to project delivery, organized into five phases: **Initiation, Planning, Execution, Release, and Close & Retrospective**. Every project begins with a lightweight one-pager that captures the problem statement, SMART objectives, success metrics, stakeholder list, and initial risks. Work only advances to planning once success metrics are clear, stakeholders are aligned, and team availability is confirmed. Planning then converts the approved initiative into a prioritized backlog, a release milestone map, and a defined Definition of Done — with T-shirt sizing or story points used to estimate scope and a Risk Register maintained throughout.

The core team is built around four key personas: the **Project Manager (PM)**, who coordinates schedules, risks, and communications; the **Product Manager (PdM)**, who owns the backlog, roadmap, and success metrics; **Developers**, who implement and test features; and **QA/Testing**, who validate acceptance criteria. Clear ownership is a foundational principle — every project has a named PM and Product Lead — and cross-functional collaboration is emphasized at every stage.

During execution, OctoAcme teams operate with a consistent team rhythm: daily 15-minute standups, weekly delivery syncs, and sprint-end demos. Work flows through a GitHub Projects board (Backlog → Ready → In Progress → In Review → QA → Done), with PRs kept small (≤400 lines where possible), linked to issues, and gated by CI tests, linting, and at least one approval. Quality is enforced through unit tests, integration tests, end-to-end smoke tests, and security scanning in CI. Blockers are escalated through a three-level path: team triage → PM escalation to Product Lead → sponsor-level escalation for business-impacting issues.

Stakeholder communication follows a regular cadence — weekly PM/PdM syncs, twice-weekly team standups, and monthly stakeholder updates — with a standardized weekly status template covering progress, next steps, risks, and decisions needed. After each sprint, release, or incident, teams run a timeboxed retrospective to surface what went well, what could improve, and 2–3 prioritized action items with owners and due dates. These action items feed back into the project backlog, closing the continuous improvement loop.

## Key Principles

- Customer-first decision-making
- Iterative, incremental delivery
- Clear role ownership
- Evidence-based planning and prioritization
- Consistent risk management, communication, and improvement cycles

## Process Documents

| Document | Description |
|----------|-------------|
| [Project Management Overview](./octoacme-project-management-overview.md) | Principles, roles, and key artifacts |
| [Project Initiation](./octoacme-project-initiation.md) | Problem, goals, stakeholders, success criteria |
| [Project Planning](./octoacme-project-planning.md) | Breaking down initiatives, estimating, and setting milestones |
| [Execution and Tracking](./octoacme-execution-and-tracking.md) | Routines, metrics, and progress |
| [Risks and Communication](./octoacme-risks-and-communication.md) | Risk registers, communication plans, escalation |
| [Release and Deployment](./octoacme-release-and-deployment.md) | Releasing features, verification, rollout/rollback |
| [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Learnings to actions |
| [Roles and Personas](./octoacme-roles-and-personas.md) | Role definitions and responsibilities |
