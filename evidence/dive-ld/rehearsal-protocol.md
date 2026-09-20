# Dive-LD Bounded Rehearsal Protocol v1.0

**Status: NOT YET RUN**

## Objective

Make the transition from nominal autonomy to consequential anomaly visible as a judgment problem.

## Environment

Use a tabletop, simulator, digital twin, approved test environment, or synthetic mission record. Do not conduct unsafe at-sea experimentation and do not encode classified or proprietary procedures.

## Sequence

1. Establish a synthetic mission state and expected platform behavior.
2. Declare the rehearsal's authoritative test rule before the run.
3. Introduce one anomaly: degraded contact, conflicting telemetry, missed expected state, or unresolved elapsed time.
4. Add one bounded friction variable where required.
5. Observe whether the participant detects the transition.
6. Record classification and MONITOR / RECOVER / ABORT-CONTAIN / ESCALATE disposition.
7. Introduce a state update if the scenario tests revision/recovery.
8. Capture rationale, authority path, latency, and final state.
9. Debrief after the observation is frozen.

## Red Condition

The target failure mode is observed when the scenario crosses its predeclared test boundary but the participant continues treating the condition as routine vehicle degradation without the required change in decision regime.

## Guardrail

The rehearsal boundary is synthetic. It must not be represented as a U.S. Navy, Anduril, or other operational threshold.

## Promotion Rule

Simulation can validate instrument behavior. It cannot establish field effectiveness.
