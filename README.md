# YieldOS

**YieldOS** is the DiamondOps process-intelligence layer.

It turns operational metadata into:
- yield visibility
- downtime accountability
- safety trend insight
- decision support for survival under price compression

YieldOS is **analytics-first**, not control software.

---

## What YieldOS Is

YieldOS provides:
- run tracking
- yield classification
- downtime attribution
- inspection and retrofit impact analysis
- safety and incident trend reporting

YieldOS does **not**:
- control reactors or safety systems
- require secrets by default
- replace operators or engineers

---

## Design Principles

### Metadata-First
YieldOS stores:
- structured event records
- timestamps
- classifications
- references to evidence

It avoids:
- raw sensor firehoses
- proprietary control data
- sensitive facility secrets

---

### Safety-Aware by Default
YieldOS ingests:
- incidents
- interlock events
- commissioning and inspection artifacts

This allows:
- compliance visibility
- audit readiness
- early warning via trend detection

---

## Core Inputs (v0.3)

### From Operators
- `run_record`
  - run type (gem, plate, research, maintenance)
  - duration and outcome
  - recipe reference pointer

---

### From HydraSafe
- `incident_event`
- `interlock_event`
- `permit_artifact`
- optional aggregated `sensor_reading`

---

### From ReactorOps
- `maintenance_event`
- `downtime_event`
- `asset_inspection_event`
- `retrofit_event`

---

### From External Labs
- `lab_report` metadata
  - grading, FTIR, Raman, PL, thermal, electrical
  - summary metrics only
  - report references

---

## Analytics Provided

### 📈 Yield Analytics
- process yield
- product yield
- quality yield
- trends by asset, recipe, and time

---

### ⏱ Downtime & Availability
- scheduled vs unscheduled downtime
- root-cause attribution
- maintenance effectiveness

---

### 🧯 Safety & Compliance Trends
- incident frequency
- interlock activity
- post-incident outcomes
- inspection risk trends

---

### 🔄 Retrofit Impact Tracking
- before/after availability comparison
- downtime reduction vs expectation
- ROI visibility on retrofit investments

---

## Dashboards

### Operator View
- recent runs
- recent interlocks
- notes and annotations
- last known downtime reason

### Engineer View
- yield vs recipe
- defect correlation summaries
- inspection risk trends
- maintenance vs failure analysis

### Executive View
- availability
- utilization
- yield summary
- safety posture
- capital allocation signals

---

## Integration & Security

- All ingestion validated against DiamondOps-Core schemas
- No secrets required by default
- Supports self-hosted or offline ingestion models
- Public-safe documentation posture

---

## Why YieldOS Matters

In a stable market, YieldOS improves margins.

In a collapsing market, YieldOS determines **who survives**.

It allows producers to:
- see problems early
- justify retrofits
- eliminate silent yield killers
- pivot from jewelry to industrial or advanced materials

---

## Versioning & Compatibility

- YieldOS aligns to **DiamondOps-Core v0.3.x**
- Data model evolves additively
- Analytics expand without breaking ingestion contracts

---

## Status

- **v0.3**: complete operational ingestion model
- Next: validator CLI, example datasets, and anonymized benchmarks
