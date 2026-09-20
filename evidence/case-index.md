# Evidence Case Index

**The architecture explains the system. The evidence layer makes it inspectable.**

## Evidence Dashboard

**[Open the Evidence Dashboard](dashboard.md)** — portfolio-level view of claim → evidence level → inspectable artifact → last evidence event → next evidence required.

Every case follows the same Golden Thread:

```text
FAILURE MODE → SIGNAL → JUDGMENT → TOOL → FRICTION → EVIDENCE → UPDATE
```

## Case Matrix

| Case | Domain | Evidence status | Failure mode | Judgment under test | Primary instrument |
|---|---|---|---|---|---|
| [ReadyLink](readylink/README.md) | DFR / information exposure | PUBLICLY REPORTED case + deep illustrative instrument | Normal sharing persists beyond intended audience/time | Does current sharing still match authorized mission intent? | Logic Anchor + Telemetry Specification |
| [Dive-LD](dive-ld/README.md) | Maritime autonomy | PUBLICLY REPORTED case + deep illustrative instrument | Platform degradation/loss becomes recovery and exposure problem | When does anomalous state require a different decision regime? | Logic Anchor + Friction Matrix |
| [DFR Triage](dfr-triage/README.md) | Agentic triage / DFR | ILLUSTRATIVE → predeclared simulation pack | Wrong/high-confidence recommendation receives shallow human approval | Accept, inspect, escalate, or reject? | Logic Anchor + Friction Matrix + Telemetry Specification |
| [Silent Churn](silent-churn/README.md) | Customer / commercial | ILLUSTRATIVE + predeclared simulation pack | Green dashboard conceals deteriorating relationship | Is the account healthy, or is the dashboard lagging reality? | Logic Anchor + Telemetry Specification |

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


## Deep Evidence Packs

### DFR Triage v1.0

**[Open the evidence pack](dfr-triage/README.md)** — 12 predeclared synthetic scenarios, experimental Logic Anchor, Friction Matrix, telemetry schema, observation CSV, results template, claim → evidence map, and update log.

**Current boundary:** Run 001 is a **SIMULATED / MODEL BASELINE**, not a human-participant or field-readiness result.


### ReadyLink v1.0

**[Open the evidence pack](readylink/README.md)** — public source record, claim → evidence map, Logic Anchor, Friction Matrix, telemetry plan, bounded rehearsal protocol, observation CSV, results, and update log.

**Current boundary:** the historical case is **PUBLICLY REPORTED**; the proposed Lab instrument is **ILLUSTRATIVE / NOT YET RUN**. No prevention or field-effectiveness claim is made.


### Dive-LD v1.0

**[Open the evidence pack](dive-ld/README.md)** — dated public source record, claim → evidence map, Logic Anchor, Friction Matrix, telemetry plan, bounded rehearsal protocol, observation CSV, results, and update log.

**Current boundary:** vehicle loss/recovery is **PUBLICLY REPORTED**; the Lab instrument is **ILLUSTRATIVE / NOT YET RUN**. No internal-readiness-cause or prevention claim is made.


### Silent Churn v1.0

**[Open the evidence pack](silent-churn/README.md)** — claim → evidence map, Logic Anchor, Friction Matrix, 12 balanced synthetic scenarios, telemetry specification, observation CSV, results, and update log.

**Current boundary:** **ILLUSTRATIVE / PREDECLARED SIMULATION — NOT YET RUN**. No predictive churn or retention-effect claim is made.
