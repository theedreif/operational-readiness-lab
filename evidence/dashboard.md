# Evidence Dashboard

**Operational Readiness Lab — Evidence Maturity View**

> **Architecture tells you what the system believes. Evidence tells you what it has earned.**

**Last reviewed:** 2026-09-20

## Portfolio View

| Case | Domain | Strongest evidence now | Inspectable artifact | Last test / evidence event | Next evidence required |
|---|---|---|---|---|---|
| [DFR Triage](dfr-triage/README.md) | Agentic triage / DFR | **SIMULATED — MODEL BASELINE** | [Run 001 results](dfr-triage/results.md) · [observations](dfr-triage/observations.csv) | Run 001: 12-scenario model baseline complete | **Supervisor Calibration pack OPEN**; obtain independent blind expert review, then classify agreement/disagreement |
| [ReadyLink](readylink/README.md) | DFR / information exposure | **PUBLICLY REPORTED CASE**; instrument illustrative | [Source record](readylink/source-record.md) · [rehearsal protocol](readylink/rehearsal-protocol.md) | public incident + product guidance mapped; Lab rehearsal not run | authorized non-sensitive rehearsal measuring detection and restriction/revocation behavior |
| [Dive-LD](dive-ld/README.md) | Maritime autonomy | **PUBLICLY REPORTED CASE**; instrument illustrative | [Source record](dive-ld/source-record.md) · [rehearsal protocol](dive-ld/rehearsal-protocol.md) | public vehicle-loss case mapped; Lab rehearsal not run | tabletop/simulator run with predeclared anomaly boundary, authority path and telemetry |
| [Silent Churn](silent-churn/README.md) | Customer / commercial | **ILLUSTRATIVE / PREDECLARED SIMULATION** | [12-scenario set](silent-churn/scenarios.md) · [telemetry spec](silent-churn/telemetry-spec.md) | evidence pack specified; no run yet | blinded simulation; then de-identified historical outcome comparison if authorized |

## Claim → Evidence → Next Test

### DFR Triage

**Claim under test:** High model confidence plus fast human approval can conceal weak independent judgment.

**What is earned:** The 12-scenario instrument has been traversed end-to-end in a model-generated baseline. The baseline checks instrument coherence; it does not establish human performance or field readiness.

**Next test:** Independent judgment under blinded scoring.

### ReadyLink

**Supported case claim:** A technically functioning share can become an exposure state when access configuration and operational intent diverge.

**What is earned:** Public incident provenance plus documented product behavior. The Lab instrument has not been tested.

**Next test:** Approved rehearsal in which a test share crosses a predeclared authorization boundary and detection/action are observed.

### Dive-LD

**Supported case claim:** An attritable autonomous platform can still create consequential decisions after degradation or loss.

**What is earned:** Publicly reported vehicle-loss/malfunction case plus an inspectable readiness instrument. No internal-readiness-cause claim is established.

**Next test:** Synthetic/tabletop anomaly transition that records classification, authority, disposition, latency and recovery.

### Silent Churn

**Hypothesis:** Apparently healthy aggregate metrics can lag meaningful deterioration visible in weaker behavioral signals.

**What is earned:** A balanced 12-scenario experimental design and telemetry schema. No predictive churn effect is established.

**Next test:** Blinded simulation, followed only later by de-identified historical outcome comparison if appropriate evidence becomes available.

## Evidence Ladder

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

A case may contain multiple evidence levels at once. A publicly reported incident does not make the proposed Lab instrument field-validated. A simulation can show instrument behavior without proving predictive validity.

## Supervisor Calibration — Open

**[DFR Triage Supervisor Calibration Pack](dfr-triage/supervisor-calibration.md)** is ready for independent review.

The reviewer does not see the scoring key until committing all 12 judgments. Disagreement is classified as calibrated agreement, reasonable alternative, scenario ambiguity, anchor defect, key defect, or authority gap.

**No calibration result is claimed yet.** The next evidence event requires an independent reviewer.

## Portfolio Gaps

| Gap | Current state | Closure condition |
|---|---|---|
| Independent human judgment | not yet captured | blinded participant observations |
| Decision latency | not available in model baseline | timed human/simulator run |
| Supervisor calibration | **protocol + DFR review pack ready; no completed independent review yet** | independent expert completes blind review and disagreements are classified |
| Near-miss comparison | not yet attached | authorized historical cases mapped to the same instrument |
| Field outcome correlation | not established | longitudinal or retrospective outcome evidence |
| Validated readiness claim | not established | evidence ladder completed for a bounded claim |

## Promotion Rules

1. **Do not promote the story. Promote the evidence.**
2. Preserve the difference between **case evidence** and **instrument evidence**.
3. Unknown operational thresholds remain **UNKNOWN / REQUIRES AUTHORITATIVE VERIFICATION**.
4. A model baseline is not a human-participant result.
5. Simulation is not field validation.
6. Record what changed because of evidence in each case's update log.

## Golden Thread

```text
FAILURE MODE → SIGNAL → JUDGMENT → TOOL → FRICTION → EVIDENCE → UPDATE
```

The dashboard is not the evidence. It is the map to the evidence.

> **Trace everything. Duplicate nothing. Earn the claim in arrears.**
