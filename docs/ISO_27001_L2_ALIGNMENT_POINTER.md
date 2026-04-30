# ISO 27001 Level 2 Alignment Pointer - ghost-backend

Last updated: 2026-03-30
Layer: Level 2 (`GGDC-System/ghost-backend`)
Purpose: Link this service documentation set to canonical ISO 27001 governance and shared-control artifacts.

## Canonical ISO 27001 References

- `~/Business/docs/compliance/iso27001/ISO_27001_LEVEL1_GOVERNANCE_BASELINE.md`
- `~/Business/docs/compliance/iso27001/ISO_27001_CONTROL_CROSSWALK_LEVEL1_TO_L3.md`
- `~/Business/docs/compliance/iso27001/ISO_27001_EVIDENCE_AND_VALIDATION_GUIDE.md`
- `~/Business/GGDC-System/docs/ISO_27001_L2_SHARED_CONTROLS.md`
- `~/Business/GGDC-System/docs/ISO_27001_L2_EVIDENCE_MAP.md`
- `~/Business/GGDC-System/docs/ISO_27001_L2_OPERATIONAL_RUNBOOK_LINKS.md`

## ghost-backend Scope Contribution

- This repository documents backend security and operational controls that may be inherited by Level 3 systems consuming ghost-backend services.
- Project-specific certification assertions are out of scope for this file.
- This pointer does not store secrets or attestations.

## Local Evidence Pointers

- `docs/SECURITY_GUIDE.md`
- `docs/SECURITY.md`
- `docs/SECURITY_REMEDIATION_REPORT.md`
- `docs/PAGERDUTY_INTEGRATION.md`
- `docs/PORT_SECURITY.md`

## Usage Rule

Any Level 3 project inheriting backend controls from ghost-backend should reference this pointer and the canonical Level 2 shared-control documents rather than duplicating control narratives.
