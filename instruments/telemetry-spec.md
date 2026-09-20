# Telemetry Specification

Telemetry captures behavior that can support or challenge a readiness claim.

For each experiment define:

| Field | Definition |
|---|---|
| Event | What happened |
| Timestamp | When it happened |
| Signal | What became observable |
| Operator/System Action | What was done |
| Decision Latency | Time from signal to required decision |
| Confidence | Stated or measured confidence, if relevant |
| Rule/Anchor | Authoritative boundary applied |
| Result | What happened next |
| Recovery | Whether and how the system returned to a safe/desired state |
| Evidence Status | Illustrative, simulated, publicly reported, field-observed, validated |

Prefer a few decision-relevant measures over a large dashboard.

**A buyer should pay for a defensible claim, not a dashboard.**
