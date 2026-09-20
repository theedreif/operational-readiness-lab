# Silent Churn Telemetry Specification

| Field | Definition |
|---|---|
| run_id | unique experiment run |
| participant_id | pseudonymous participant |
| scenario_id | SC-01 through SC-12 |
| headline_state | synthetic dashboard state |
| weak_signals_present | compact signal list |
| expected_disposition | hidden experimental key |
| operator_disposition | MAINTAIN / INVESTIGATE / ESCALATE / INTERVENE |
| operator_confidence | participant-stated confidence |
| decision_latency_seconds | scenario-ready to disposition |
| signals_noticed | signals explicitly identified |
| benign_explanation_considered | TRUE/FALSE |
| pattern_recognized | TRUE/FALSE/NA |
| rationale | participant reasoning |
| final_matches_experimental_key | TRUE/FALSE |
| evidence_status | SIMULATED |

## Candidate Derived Measures

After observations exist:

- agreement with experimental key;
- weak-signal detection rate;
- false-positive escalation/intervention rate;
- pattern-recognition rate;
- investigation rate under green headline metrics;
- decision latency by signal density;
- anchoring effect in the strong-history scenario.

These measures describe the simulation only.
