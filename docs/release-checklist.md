# Release Checklist

Purpose: Ensure consistent, safe, and observable releases.

## Pre-release (>= 5 business days before target)
- Confirm feature freeze date and scope is agreed by PM and Engineering.
- TPM / Project Manager has verified cross-team dependencies are scheduled.
- Release Manager has a release plan and cutover schedule (date/time, services affected).
- QA Lead has validated critical paths with automated and manual tests; known regressions documented.
- Security Champion has completed any required security reviews for release items.
- Observability / SRE has validated metrics, alerts and dashboards for new features.
- Compliance Officer sign-off if release touches regulated areas.

## Release readiness (24–72 hours before)
- Run pre-release checklist meeting and record decisions.
- Ensure automated pipeline green for release candidate (CI/CD).
- Runbook validated and accessible; rollback steps documented.
- Stakeholders notified (support, on-call, PMs, legal if needed).

## Deployment (release day)
- Execute canary and staged rollout as planned.
- Monitor SLO/SLIs and health checks continuously.
- Notify stakeholders at defined milestones (start, canary success, general availability).
- If anomalies occur, trigger incident process and follow rollback criteria.

## Post-release (0–72 hours after)
- Validate production metrics and user-facing checks.
- Collect and publish release notes and known issues.
- Schedule post-release review if any incidents or regressions observed.
- Update documentation and runbooks with any changes discovered during release.

## Gating criteria to abort or roll back
- Severity SLO breaches across core services.
- Critical user-impacting regressions or data-loss risk.
- Failed canary or health checks that cannot be remediated quickly.

## Owners
- Release Manager: primary owner for timeline and coordination.
- QA Lead: validation and sign-off for quality gates.
- Observability / SRE: monitoring and health checks.
