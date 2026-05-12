# Incident Response Checklist

Purpose: Provide a consistent, fast, and well-communicated incident triage and resolution flow.

## Detection and Triage (0–15 minutes)
- Incident Response Lead or on-call engineer confirms impact and classification (sev1/sev2 etc).
- Create an incident channel and incident document (start time, symptoms, owner).
- Notify stakeholders per escalation path (Project Manager, Product Manager, SRE).

## Containment and Mitigation (15–60 minutes)
- Identify immediate mitigation steps and implement short-term fixes if safe.
- Assign roles: who will investigate root cause, who will handle communication, who will run mitigations.
- Keep the incident document updated with timeline and actions.

## Recovery (60–240 minutes)
- Execute rollback or mitigation plan if needed.
- Validate that customer-impacting symptoms are resolved.
- Communicate status updates at defined intervals (every 30–60 minutes for sev1).

## Post-incident (after recovery)
- Conduct a blameless post-incident review within 3–7 days.
- Publish a post-incident report with timeline, root cause, and action items.
- Assign owners and due dates for remediation tasks; track to completion.
- Update runbooks, monitoring, and documentation to prevent recurrence.

## Communication templates
- Use predefined incident status templates for public and internal updates.
- Keep internal logs of who was paged and which actions were taken.

## Owners
- Incident Response Lead: coordinator for triage and review.
- SRE / Observability: telemetry and mitigation actions.
- Developers: fixes and follow-up remediation.
