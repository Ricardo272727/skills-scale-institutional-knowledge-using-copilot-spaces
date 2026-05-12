# OctoAcme Project Management Docs — README

This README centralizes OctoAcme's project management process documentation. It provides a short summary of the project management processes and quick links to the full process documents in this repository's docs/ folder.

## Quick summary

OctoAcme uses a lightweight, repeatable project management approach to move from idea to value:

- Initiation: Validate the problem, define success metrics, align stakeholders, and produce a Project One-pager.
- Planning: Create a prioritized backlog, estimate work, identify dependencies/risks, and produce a release plan.
- Execution & Tracking: Use a project board workflow (Backlog -> Ready -> In Progress -> In Review -> QA -> Done), small PRs, CI checks, daily standups, and weekly delivery syncs to track progress.
- Release & Deployment: Follow pre-release checks, run smoke tests in staging, deploy via an automated pipeline where possible, and document release notes and rollback plans.
- Retrospective & Continuous Improvement: Run retrospectives after sprints/releases/incidents, capture action items, and track improvements.
- Risks & Communication: Maintain a risk register, communicate regular status updates, and escalate blockers through defined escalation paths.
- Roles & Personas: Clear role definitions (Product Manager, Project Manager, Developers, QA) with responsibilities and communication norms.

## Documents (links)

- [Project Management Overview](./octoacme-project-management-overview.md) — concise introduction to how OctoAcme runs projects
- [Project Initiation Guide](./octoacme-project-initiation.md) — templates and deliverables to start a project
- [Project Planning](./octoacme-project-planning.md) — planning activities, backlog templates, and risk management
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — team rhythm, workflows, and reporting
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — release types, checklists, and rollback playbook
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — running retrospectives and tracking action items
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — maintaining the risk register and stakeholder communications
- [Roles & Personas](./octoacme-roles-and-personas.md) — role definitions and responsibilities

## How to use

- Use this README as the single index when onboarding or reviewing process docs.
- To propose changes or add new process docs, open an issue using the "Add Content to Project Management Process Docs" template (.github/ISSUE_TEMPLATE/) and select the appropriate document or "<new document>".

## Maintenance

- Keep the one-pager and key artifacts in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.

---

Last updated: 2026-05-12
