# DFR Triage Telemetry Specification

One observation row per participant per scenario.

| Field | Definition |
|---|---|
| run_id | unique experiment run |
| participant_id | pseudonymous participant identifier |
| scenario_id | DFR-01 through DFR-12 |
| automation_recommendation | recommendation shown in the synthetic scenario |
| automation_confidence | stated synthetic confidence |
| expected_disposition | experimental scoring key |
| operator_disposition | ACCEPT / INSPECT / ESCALATE / REJECT |
| operator_confidence | participant-stated confidence, if collected |
| decision_latency_seconds | time from decision-ready signal to disposition |
| contradictory_cue_present | TRUE/FALSE |
| contradictory_cue_detected | TRUE/FALSE/NA |
| cues_inspected | compact record of evidence inspected |
| rationale | participant's reason |
| changed_after_new_evidence | TRUE/FALSE/NA |
| final_matches_experimental_key | TRUE/FALSE |
| recovery_observed | TRUE/FALSE/NA |
| notes | bounded observer notes |
| evidence_status | SIMULATED |

## Derived Measures

Calculate only after data collection:

- disposition agreement rate with the predeclared experimental key;
- contradiction-detection rate;
- high-confidence-wrong acceptance count;
- median decision latency by scenario condition;
- revision rate after late contradictory evidence;
- recovery rate after an initially weak disposition.

## Guardrail

These measures describe performance inside this simulation only. They are not validated predictors of field readiness.
