# LaunchBay Boundary (ghost-backend)

## Purpose

Clarify LaunchBay ownership boundaries for ghost-backend operators and contributors.

## What ghost-backend owns

- Shared backend framework concerns in this repository.
- Operational health and security for ghost-backend services.

## What ghost-backend does not own

- LaunchBay webhook routes (`/webhooks/launchbay/:event`)
- LaunchBay workflow mapping and Zapier bridge logic
- LaunchBay outbound action orchestration

Those are owned by Ghost-Platform Level 3 services.

## Escalation Path

1. Validate whether issue is framework/runtime infrastructure in ghost-backend.
2. If issue is LaunchBay integration behavior, escalate to `the-system` maintainers.
3. Use Level 1 governance docs for policy/ownership disputes.

## References

- `~/Business/docs/integrations/LAUNCHBAY_OPERATIONS_GUIDE.md`
- `~/Business/GGDC-System/the-system/docs/webhooks/LAUNCHBAY.md`
