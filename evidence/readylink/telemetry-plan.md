# ReadyLink Telemetry Plan

One row per observed share-state decision.

| Field | Definition |
|---|---|
| run_id | unique rehearsal/run |
| observation_id | unique decision observation |
| share_id | synthetic or approved test-share identifier |
| mission_state | ACTIVE / TRANSITION / COMPLETE / UNKNOWN |
| intended_audience | approved audience description |
| observed_scope | share scope visible to operator |
| auth_state | observed access-control state |
| expiration_state | configured/observed expiration state |
| share_age_minutes | age of approved test share |
| viewer_signal | viewer/access signal if available |
| trigger_detected | condition that caused review |
| operator_disposition | CONTINUE / RESTRICT / REVOKE / ESCALATE |
| decision_latency_seconds | trigger-to-disposition time |
| action_latency_seconds | disposition-to-action time |
| rationale | reason for disposition |
| authoritative_rule | rule/policy used, or UNKNOWN |
| result | observed post-action state |
| evidence_status | SIMULATED / FIELD-OBSERVED / etc. |

## Candidate Derived Measures

Only calculate after authorized data collection:

- persistent-share detection rate;
- median detection latency;
- median restriction/revocation latency;
- percentage of decisions tied to an identified authoritative rule;
- unresolved-authority escalation rate;
- handoff-related misses;
- false-positive revocation/restriction rate.

No pass/fail threshold is currently asserted.
