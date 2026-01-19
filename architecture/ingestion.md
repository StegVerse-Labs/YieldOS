# Ingestion (v0.1)

Inputs:
- run_record (operators / integrations)
- incident_event, interlock_event, permit_artifact (HydraSafe)
- maintenance_event, downtime_event (ReactorOps)
- lab_report (external labs)

Principles:
- validate against DiamondOps-Core schemas
- store references, not secret data
- support batch imports (CSV/JSON) in future implementation
