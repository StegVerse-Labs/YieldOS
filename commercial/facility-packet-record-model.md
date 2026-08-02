# Facility Packet Record Model

## Purpose
Define the minimum record set YieldOS must aggregate for a HydraSafe permitting-readiness delivery.

## Packet manifest
- engagement identifier;
- facility identifier;
- packet version and status;
- customer-supplied document inventory;
- HydraSafe artifact inventory;
- ReactorOps evidence inventory;
- external-review requirements;
- unresolved-gap count by severity;
- delivery timestamp and integrity reference.

## Required views
1. Completeness matrix by packet section.
2. Missing-document register.
3. Conflicting or superseded-document register.
4. External-review queue: owner, OEM, PE, insurer, AHJ.
5. Final delivery receipt with exact artifact versions.

## State vocabulary
`intake`, `assessment`, `remediation`, `external-review`, `delivery-ready`, `delivered`, `superseded`.

## Boundary
A high completeness score means the defined documentation set is assembled. It does not mean the facility is compliant, safe to operate, permitted, insured, commissioned, or professionally approved.
