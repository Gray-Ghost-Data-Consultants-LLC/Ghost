# PagerDuty Integration Guidance (Ghost Backend)

**Layer:** Level 2 framework/backend foundation  
**Canonical governance:** `~/Business/docs/integrations/PAGERDUTY_GOVERNANCE.md`

## Purpose

Provide integration guidance for teams that use Ghost Backend services in
environments where PagerDuty escalation is required.

## Current State

This repository currently has no direct PagerDuty runtime integration modules.
PagerDuty escalation behavior is generally handled by shared platform alerting
and project-level runbooks.

## Integration Contract

If PagerDuty integration is added to Ghost Backend services, include:

- Service owner and escalation owner
- Event source map (what can trigger incidents)
- Dedup key strategy
- Severity mapping policy (P1-P4)
- Recovery and verification steps

## Secret Contract

- `PAGERDUTY_API_TOKEN`
- `PAGERDUTY_EVENTS_ROUTING_KEY`

Use GCP Secret Manager for production and gitignored local environment files for development.

## Validation Checklist

- Non-production event trigger test succeeds
- Incident acknowledgment workflow confirmed
- Resolution path tested and documented
- Links to Level 1 and project-level runbooks included

## References

- <https://developer.pagerduty.com/>
- <https://developer.pagerduty.com/docs/introduction>
- <https://developer.pagerduty.com/api-reference/f1a95bb9397ba-changelog>
