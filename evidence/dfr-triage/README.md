# DFR Triage Evidence Pack v1.0

**Evidence status: SIMULATED EVIDENCE DESIGN — RUN DATA NOT YET COLLECTED**

> **Golden Thread:** FAILURE MODE → SIGNAL → JUDGMENT → TOOL → FRICTION → EVIDENCE → UPDATE

## Purpose

Turn the DFR Triage illustrative case into a reproducible bounded experiment. This pack predeclares the hypothesis, scenario set, scoring logic, telemetry schema, evidence boundary, and update rule before results are collected.

## Failure Mode

A high-confidence automated recommendation is wrong or insufficiently supported while the human approval is too shallow to add meaningful independent judgment.

## Hypothesis

**High model confidence plus fast human approval can conceal weak independent judgment.**

The experiment is designed to challenge that hypothesis, not confirm it.

## Judgment Under Test

**Does the recommendation deserve acceptance, independent review, escalation, or rejection given the evidence available now?**

## Instrument Stack

1. [Logic Anchor](logic-anchor.md)
2. [Friction Matrix](friction-matrix.md)
3. [Scenario Set](scenarios.md)
4. [Telemetry Specification](telemetry-spec.md)
5. [Observation Template](observations.csv)
6. [Results Template](results.md)
7. [Claim → Evidence Map](claim-evidence-map.md)
8. [Update Log](update-log.md)

## Predeclared Measures

- operator disposition: ACCEPT / INSPECT / ESCALATE / REJECT;
- agreement or disagreement with the automated recommendation;
- decision latency;
- cues inspected;
- contradictory cue detected;
- operator confidence;
- rationale captured;
- recovery after an initially weak decision.

No universal pass/fail threshold is asserted. Any operational threshold remains **UNKNOWN / REQUIRES AUTHORITATIVE VERIFICATION**.

## Run Protocol

Run all 12 scenarios without changing the scoring logic mid-run. Record one row per participant per scenario in `observations.csv`. Preserve the original observation data. Analyze only after the run is complete.

If the instrument itself fails during the run, document the failure rather than silently repairing the data.

## Promotion Boundary

This pack can produce **SIMULATED** evidence about behavior inside a designed scenario set. It cannot establish field readiness, agency performance, vendor performance, safety, policy compliance, or operational effectiveness.

Promotion beyond SIMULATED requires evidence higher on the Lab Evidence Ladder.

> **Trace everything. Duplicate nothing. Earn the claim in arrears.**
