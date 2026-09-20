# DFR Triage — Confident Wrong Classification

**Evidence status: ILLUSTRATIVE EXPERIMENT**

> **Golden Thread:** FAILURE MODE → SIGNAL → JUDGMENT → TOOL → FRICTION → EVIDENCE → UPDATE

## Boundary
This is a designed experiment, not a claim about any specific DFR provider, agency, deployment, model, or field result. Numerical thresholds remain **UNKNOWN / REQUIRES AUTHORITATIVE VERIFICATION**.

## Failure Mode
An agentic triage system is wrong and confident while a human approval occurs too quickly to add meaningful independent judgment.

## Signal
Calibration gap between stated confidence and observed classification quality, especially inside the fast-approval population or a stressed subgroup.

## Judgment
**Does the recommendation deserve acceptance, independent review, escalation, or rejection given the evidence available now?**

The human role is not to click approve. It is to add judgment where automation may be brittle.

## Tool
**Logic Anchor + Friction Matrix + Telemetry Specification**

Example Logic Anchor:
- **Trigger:** automated response tier and confidence are presented for approval.
- **Filter:** source quality, contradictory cues, corrected details, uncertainty, local terminology, severity, and evidence of model brittleness.
- **Anchor:** approve, inspect, escalate, or override according to authoritative policy.

## Friction
Candidate injections:
- overlapping voices;
- an address stated and then corrected;
- local terminology poorly represented in training data;
- calm or flat affect during a severe incident;
- contradictory details arriving late;
- simultaneous workload that encourages rapid approval.

## Evidence
Capture:
- recommended response tier;
- confidence;
- authoritative/validated ground truth where available;
- approval latency;
- injected condition;
- cues inspected;
- human intervention/override;
- final classification;
- recovery after error.

**Current evidence level:** **ILLUSTRATIVE**. No field-effectiveness claim is made.

## Update
After repeated trials:
1. identify conditions associated with fast acceptance and degraded classification;
2. refine the Logic Anchor;
3. add or remove friction variables;
4. test whether the signal survives new variations;
5. only promote the claim when evidence advances up the Evidence Ladder.

## Inspectable Claim
**Hypothesis to test:** high model confidence plus fast human approval can conceal weak independent judgment.

That hypothesis is deliberately not presented as a validated field claim.


## Evidence Pack v1.0

The experiment now has a predeclared reproducible evidence package: scenario set, Logic Anchor, Friction Matrix, telemetry schema, observation template, results template, claim map, and update log.

**[Open the DFR Triage Evidence Pack v1.0](../evidence/dfr-triage/README.md)**

The pack contains **no invented run results**. Its current contribution is instrument design and predeclared measurement. Evidence advances to **SIMULATED** only when the scenarios are actually run and observations are recorded.
