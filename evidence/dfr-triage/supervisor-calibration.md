# DFR Triage — Supervisor Calibration Pack v1.0

**Status: OPEN FOR INDEPENDENT REVIEW**

This is the first Supervisor Calibration instrument in the Operational Readiness Lab.

## Calibration Question

Given only the evidence available in each synthetic scenario, does an independent qualified reviewer support the predeclared disposition logic:

**ACCEPT / INSPECT / ESCALATE / REJECT?**

## Review Set

Use the 12 scenarios in [Scenario Set v1.0](scenarios.md).

The expected disposition column must be hidden from the reviewer during the blind pass.

## Reviewer Instructions

For each scenario:

1. select ACCEPT / INSPECT / ESCALATE / REJECT;
2. identify the cue(s) that drove the judgment;
3. state what information is missing;
4. rate confidence as LOW / MODERATE / HIGH;
5. state whether the decision boundary is clear enough to score;
6. commit the answer before seeing the experimental key.

After all 12 are complete, reveal the predeclared key and classify every disagreement using the [Supervisor Calibration Protocol](../../instruments/supervisor-calibration.md).

## Calibration Record

Use [supervisor-calibration.csv](supervisor-calibration.csv).

## Predeclared Summary Measures

After review calculate:

- exact disposition agreement;
- agreement excluding scenarios classified as ambiguous;
- number of REASONABLE ALTERNATIVE findings;
- scenario ambiguities;
- Logic Anchor defects;
- scoring-key defects;
- authority gaps;
- reviewer confidence distribution.

No pass/fail percentage is predeclared.

## Critical Rule

A 12/12 agreement is not automatically better than disagreement.

A well-supported disagreement that exposes a defective scenario or key is valuable evidence because it improves the instrument before field claims are attempted.

## Promotion Boundary

A completed independent review may support moving the instrument into **SUPERVISOR CALIBRATION** on the Evidence Ladder.

It does not establish live DFR readiness, human performance in operations, predictive validity, agency performance, vendor performance, or safety.

> **Calibration is not consensus. It is inspectable disagreement.**
