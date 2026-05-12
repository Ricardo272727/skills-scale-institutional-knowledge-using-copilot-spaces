# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Suggested Personas (proposed additions)

The following personas are suggested additions to improve clarity, accountability, and cross-functional coordination in project management process docs. Each persona includes a short role summary, responsibilities, goals, typical communication patterns, and how they interact with existing roles.

### Technical Program Manager (TPM)

#### Role Summary
TPMs focus on technical execution across multiple teams, translating product priorities into coordinated technical plans and removing cross-team impediments.

#### Responsibilities
- Coordinate cross-team technical dependencies and roadmaps
- Drive architectural trade-offs and ensure technical consistency
- Track and report program-level risks and milestones
- Facilitate cross-functional technical communication

#### Goals
- Ensure reliable, predictable delivery of complex initiatives
- Reduce cross-team blocking and integration risk
- Improve technical alignment and reuse

#### Typical Communication
- Program-level status reviews and risk briefings
- Technical working group meetings and architecture reviews

#### Interaction with existing roles
- Works closely with Product Managers on scope and prioritization
- Collaborates with Project Managers on schedules and dependency tracking
- Aligns with Engineering Managers and Tech Leads on implementation details

---

### Release Manager / Release Engineer

#### Role Summary
Responsible for coordinating and executing releases, ensuring build stability, deployment safety, and rollback plans.

#### Responsibilities
- Maintain release schedules and cut-over plans
- Validate release readiness (tests, canary plans, runbooks)
- Coordinate deployments with SRE/DevOps and Product/PM teams
- Manage rollback and post-release validation procedures

#### Goals
- Reduce release-related incidents and hotfixes
- Increase deployment confidence and automation

#### Typical Communication
- Release readiness meetings and pre-release checklists
- Incident post-mortems and release notes

#### Interaction with existing roles
- Works with Project Managers to align release dates to project plans
- Coordinates with Developers, QA, and SRE/DevOps during deployments
- Communicates status and risks to Product Managers and stakeholders

---

### QA Lead / Test Engineer

#### Role Summary
Leads test strategy and quality engineering to ensure features meet acceptance criteria, performance, and reliability standards.

#### Responsibilities
- Define test strategies (unit, integration, e2e, performance)
- Maintain and monitor test suites and CI checks
- Coordinate exploratory testing and release validation
- Highlight quality risks and required mitigations

#### Goals
- Improve defect detection earlier in the lifecycle
- Maintain high automated test coverage and stable CI

#### Typical Communication
- Test reports, flaky-test tracking, and QA sign-offs
- Collaboration with Developers and Release Managers on fixes

#### Interaction with existing roles
- Works with Developers to create test plans and acceptance criteria
- Coordinates with Project Managers on release acceptance and gating criteria

---

### UX Researcher / Design Lead

#### Role Summary
Focuses on user research, usability, and design consistency to ensure solutions meet user needs.

#### Responsibilities
- Conduct user research and usability testing
- Provide design guidance and component recommendations
- Validate features against UX metrics and accessibility standards

#### Goals
- Improve user satisfaction and reduce usability regressions
- Ensure accessibility and consistent product experience

#### Typical Communication
- Design reviews, research reports, and user testing summaries

#### Interaction with existing roles
- Works with Product Managers on problem definition and success metrics
- Partners with Developers and QA to implement and test designs

---

### Security Champion / Security Lead

#### Role Summary
Embedded security advocate who ensures security considerations are included in design, implementation, and release activities.

#### Responsibilities
- Review designs and PRs for security risks
- Coordinate vulnerability scanning and remediation
- Maintain security runbooks and incident escalation paths

#### Goals
- Reduce security vulnerabilities and time-to-fix
- Ensure compliance with organizational security policies

#### Typical Communication
- Security reviews, vulnerability reports, and remediation plans

#### Interaction with existing roles
- Works with Developers and Architects on secure design
- Coordinates with Project Managers on security-related schedule impacts
- Alerts Product Managers and stakeholders to security risks

---

### Incident Response Lead / Support Lead

#### Role Summary
Leads operational incident response, triage, and post-incident analysis to restore service and reduce recurrence.

#### Responsibilities
- Coordinate incident triage and resolution
- Maintain incident runbooks and communication templates
- Lead post-incident reviews and follow-up actions

#### Goals
- Minimize mean time to detect and resolve incidents
- Ensure lessons learned are integrated into processes

#### Typical Communication
- Incident status updates, incident retrospectives, and on-call rotations

#### Interaction with existing roles
- Works with SRE/DevOps and Developers during incidents
- Communicates impact and recovery plans to Project Managers and Product Managers

---

### Compliance Officer / Legal Liaison

#### Role Summary
Ensures projects meet legal, regulatory, and compliance requirements relevant to the product or market.

#### Responsibilities
- Review features for regulatory and compliance risks
- Maintain compliance checklists and evidence artifacts
- Coordinate audits and remediation efforts

#### Goals
- Avoid compliance-related delays or penalties
- Ensure traceability and auditability of key decisions

#### Typical Communication
- Compliance reviews, legal sign-offs, and audit reports

#### Interaction with existing roles
- Works with Product Managers and Project Managers early in planning to identify constraints
- Collaborates with Security and Engineering on technical controls

---

### Observability / SRE Engineer

#### Role Summary
Ensures systems are observable, reliable, and performant through monitoring, alerting, and runbook automation.

#### Responsibilities
- Design and maintain metrics, logs, and tracing
- Define SLOs, SLIs, and alerting thresholds
- Maintain runbooks and support on-call rotations

#### Goals
- Improve system reliability and reduce alert noise
- Provide actionable telemetry for faster troubleshooting

#### Typical Communication
- SLO/SLA reviews, on-call handovers, and incident reports

#### Interaction with existing roles
- Works with Developers to instrument code and with Release Managers to validate production readiness
- Supports Incident Response Lead during incidents

---

### Onboarding Coordinator / Knowledge Manager

#### Role Summary
Responsible for capturing, organizing, and distributing process knowledge to help onboard new team members and preserve institutional knowledge.

#### Responsibilities
- Maintain onboarding guides, runbooks, and training materials
- Coordinate onboarding sessions and mentorship pairings
- Ensure documentation is discoverable and kept up-to-date

#### Goals
- Reduce ramp time for new hires and cross-functional collaborators
- Preserve decisions and rationale to avoid knowledge loss

#### Typical Communication
- Onboarding schedules, documentation updates, and training sessions

#### Interaction with existing roles
- Works with Project Managers and TPMs to surface process changes
- Collaborates with all roles to capture decisions and create accessible docs

---

## Using these personas
- Add these personas to docs/octoacme-roles-and-personas.md to provide clearer ownership and decision paths.
- Reference persona sections in relevant process docs (planning, release, incident, and risk sections).
- Use personas as prompts in Copilot Spaces for role-specific guidance and scenario exercises.
