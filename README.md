# Operational Readiness Lab

**The repositories explain the doctrine. The Lab shows what happens when you run it.**

The Operational Readiness Lab is the experimental proving ground for the Ed Reif Field System. It turns doctrine into bounded scenarios, observable behavior, explicit thresholds, and evidence that can be inspected.

> **PREPARE → SCALE → OPERATE → COMMUNICATE → PROVE**

## The Lab Spine

Every experiment is organized around the same sequence:

```
FAILURE MODE → SIGNAL → THRESHOLD → FRICTION → RED → EVIDENCE → UPDATE
```

The purpose is not to make a scenario dramatic. The purpose is to make a consequential failure mode observable.

## What the Lab Tests

The Lab asks five questions:

1. **Failure Mode** — What can materially go wrong?
2. **Signal** — What observable behavior or system state reveals it?
3. **Threshold** — What authoritative boundary changes the required action?
4. **Friction** — What realistic variation exposes whether judgment survives?
5. **Evidence** — What would justify updating the doctrine, workflow, or readiness claim?

## Experiments

| Experiment | Readiness Question | Status |
|---|---|---|
| [ReadyLink](experiments/readylink.md) | Can we detect dangerous exposure hiding inside apparently normal operation? | Public-case analysis |
| [Dive-LD](experiments/dive-ld.md) | When failure is already an accepted possibility, have we rehearsed what happens next? | Public-case analysis |
| [Silent Churn](experiments/silent-churn.md) | Can a green dashboard conceal a failing relationship? | Design demonstration |
| [DFR Triage](experiments/dfr-triage.md) | Can confidence remain high while classification quality degrades? | Illustrative experiment |

## Instruments

The Lab uses reusable instruments rather than one-off demonstrations:

- [Experiment Card](instruments/experiment-card.md)
- [Logic Anchor](instruments/logic-anchor.md)
- [Friction Matrix](instruments/friction-matrix.md)
- [Telemetry Specification](instruments/telemetry-spec.md)
- [Evidence Ladder](instruments/evidence-ladder.md)

## Evidence Discipline

A simulation is not a field result. A public incident is not proof that an organization lacked a control. A model output is not an authoritative threshold.

Every Lab artifact should state its evidence status:

`ILLUSTRATIVE → SIMULATED → PUBLICLY REPORTED → FIELD-OBSERVED → VALIDATED`

Unknown thresholds remain **UNKNOWN / REQUIRES AUTHORITATIVE VERIFICATION** until an accountable source establishes them.

## Relationship to the Field System

- [Operational Readiness](https://github.com/theedreif/operational-readiness) — doctrine
- [Judgment at the Edge](https://github.com/theedreif/judgment-at-the-edge) — decision architecture
- [Decision Science](https://github.com/theedreif/decision-science) — positioning under uncertainty
- [High-Consequence Communication](https://github.com/theedreif/high-consequence-communicatio) — closing The Gap
- [Field Notes](https://github.com/theedreif/field-notes) — observations and applications
- [ORaaS](https://github.com/theedreif/oraas) — continuous organizational deployment

**The Lab produces evidence. ORaaS keeps the instrument running.**

## Author

**Ed Reif** — author, operational readiness architect, instructional systems designer, and decision-science practitioner.

> **Engineering in. Capability out. Evidence always.**
