# Dive-LD Telemetry Plan

| Field | Definition |
|---|---|
| run_id | unique rehearsal |
| observation_id | unique decision event |
| synthetic_vehicle_id | approved test identifier |
| mission_phase | synthetic/approved mission phase |
| expected_state | state expected by scenario |
| observed_state | state presented to participant |
| contact_state | NOMINAL / DEGRADED / LOST / UNKNOWN |
| telemetry_quality | COMPLETE / PARTIAL / CONFLICTING / NONE |
| anomaly_timestamp | scenario time anomaly becomes observable |
| trigger_detected | signal noticed by participant |
| classification | participant's state classification |
| disposition | MONITOR / RECOVER / ABORT-CONTAIN / ESCALATE |
| decision_latency_seconds | trigger-to-disposition |
| authority_engaged | experimental authority path |
| recovery_action | synthetic action selected |
| rationale | decision basis |
| final_state | scenario outcome |
| false_alarm | TRUE/FALSE/NA |
| evidence_status | SIMULATED / FIELD-OBSERVED / etc. |

## Candidate Derived Measures

After authorized observations exist:

- anomaly-detection rate;
- median time to classification;
- median time to required disposition;
- escalation rate under authority ambiguity;
- handoff-related misses;
- recovery/containment selection by friction condition;
- false-alarm rate;
- recovery after an initially weak classification.

No operational pass/fail threshold is asserted.
