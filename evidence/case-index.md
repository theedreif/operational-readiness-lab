# Evidence Case Index

**The architecture explains the system. The evidence layer makes it inspectable.**

Every case follows the same Golden Thread:

```text
FAILURE MODE → SIGNAL → JUDGMENT → TOOL → FRICTION → EVIDENCE → UPDATE
```

## Case Matrix

| Case | Domain | Evidence status | Failure mode | Judgment under test | Primary instrument |
|---|---|---|---|---|---|
| [ReadyLink](../experiments/readylink.md) | DFR / information exposure | PUBLICLY REPORTED case + illustrative instrument | Normal sharing persists beyond intended audience/time | Does current sharing still match authorized mission intent? | Logic Anchor + Telemetry Specification |
| [Dive-LD](../experiments/dive-ld.md) | Maritime autonomy | PUBLICLY REPORTED case + illustrative instrument | Platform degradation/loss becomes recovery and exposure problem | When does anomalous state require a different decision regime? | Logic Anchor + Friction Matrix |
| [DFR Triage](../experiments/dfr-triage.md) | Agentic triage / DFR | ILLUSTRATIVE | Wrong/high-confidence recommendation receives shallow human approval | Approve, inspect, escalate, or override? | Logic Anchor + Friction Matrix + Telemetry Specification |
| [Silent Churn](../experiments/silent-churn.md) | Customer / commercial | ILLUSTRATIVE | Green dashboard conceals deteriorating relationship | Is the account healthy, or is the dashboard lagging reality? | Logic Anchor + Telemetry Specification |

## Evidence Discipline

The case and the instrument do not automatically share the same evidence level.

A public incident can be **PUBLICLY REPORTED** while the proposed Logic Anchor, friction rehearsal, or telemetry design remains **ILLUSTRATIVE**. A simulation can show that an instrument behaves as designed without proving that it predicts field performance.

Use the [Evidence Ladder](../instruments/evidence-ladder.md):

```text
LOOP EVIDENCE
      ↓
SUPERVISOR CALIBRATION
      ↓
NEAR-MISS COMPARISON
      ↓
FIELD OUTCOME CORRELATION
      ↓
VALIDATED READINESS CLAIM
```

## Promotion Rule

Do not promote a case because the story is compelling.

Promote a claim only when the evidence earns it.

**Trace everything. Duplicate nothing. Earn the claim in arrears.**
