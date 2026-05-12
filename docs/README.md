# OctoAcme Project Management Docs — README

This README centralizes OctoAcme's project management process documentation. It provides a short summary of the project management processes and quick links to the full process documents in this repository.

OctoAcme uses a lightweight, repeatable delivery model that moves work from idea to production through defined stages: Initiation → Planning → Execution → Release → Close. Initiatives begin with a Project One‑pager that captures the problem, objectives, success metrics, stakeholders, and a high‑level timeline. Approved initiatives are turned into a prioritized backlog with acceptance criteria and estimates; work is planned into shippable increments and tracked on a project board.

Day‑to‑day execution emphasizes a steady team rhythm and clear workflows: short daily standups to surface progress and blockers, weekly delivery syncs to review progress and risks, and demos at the end of each sprint or milestone. The team uses a PR workflow that favors small, focused PRs, requires issue links and acceptance criteria in PR descriptions, and gates merges on CI (tests, linting, security scans) and approvals. Key artifacts—Project One‑pager, roadmap/release plan, backlog, Definition of Done, and a living risk register—serve as the single sources of truth.

Roles and responsibilities are explicit: Product Managers define outcomes and success metrics; Project Managers coordinate delivery, schedules, and communications; Developers implement and test; QA validates acceptance criteria; stakeholders provide inputs and approvals. Communication is structured (weekly PM+PdM syncs, delivery team check‑ins, monthly stakeholder updates), with defined escalation paths for blockers and security incidents. Quality is enforced through unit/integration tests, CI checks, smoke tests for critical flows, and pre‑release checklists and rollback plans. Retrospectives capture action items and feed continuous improvement back into the backlog and documentation.

## Documents (links)

- [Project Management Overview](./octoacme-project-management-overview.md) — concise introduction to how OctoAcme runs projects  
- [Project Initiation Guide](./octoacme-project-initiation.md) — templates and deliverables to start a project  
- [Project Planning](./octoacme-project-planning.md) — planning activities, backlog templates, and risk management  
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — team rhythm, workflows, and reporting  
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — release types, checklists, and rollback playbook  
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — running retrospectives and tracking action items  
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — maintaining the risk register and stakeholder communications  
- [Roles & Personas](./octoacme-roles-and-personas.md) — role definitions and responsibilities

## How to propose changes

To propose additions or updates to these process documents, please use the "Add Content to Project Management Process Docs" issue template stored in `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`. That template helps capture: which document to update, a summary of the new content, rationale, suggested content, and acceptance criteria. Link the issue to the relevant docs and reference it in PRs so changes remain traceable.

## Maintenance

- Keep the Project One‑pager and other key artifacts in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
- Ensure the README is kept up to date whenever documents in `docs/` are added, renamed, or removed.

---
Last updated: 2026-05-12
