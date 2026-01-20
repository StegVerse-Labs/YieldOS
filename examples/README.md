# Examples

This folder contains demo and example event instances used for validation and demonstrations.

## Naming convention
- Event instances: `<event_title>.json`
  - Examples: `run_record.json`, `incident_event.json`, `retrofit_event.json`
- Schemas: `<event_title>.schema.json`
  - Examples: `run_record.schema.json`, `incident_event.schema.json`

## Why this matters
StegBrain and the YieldOS validator rely on consistent naming so automation is deterministic
and validation doesn’t silently skip files.
