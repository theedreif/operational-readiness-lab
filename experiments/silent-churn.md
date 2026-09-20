# Silent Churn

**Evidence status: DESIGN DEMONSTRATION / ILLUSTRATIVE**

> **Golden Thread:** FAILURE MODE → SIGNAL → JUDGMENT → TOOL → FRICTION → EVIDENCE → UPDATE

## Boundary
This is a design demonstration, not evidence from a live customer deployment. It exists to show how the Field System can instrument weak-signal judgment outside defense or autonomy.

## Failure Mode
A renewal account appears healthy in standard reporting while weak behavioral signals indicate emerging churn risk.

## Signal
Candidate signals:
- increasing response latency;
- repeated rescheduling;
- unopened communications;
- declining stakeholder participation;
- changes in engagement pattern;
- positive headline metrics that conflict with relationship behavior.

## Judgment
**Is the account genuinely healthy, or is the dashboard lagging the relationship?**

The operator must decide whether weak signals justify investigation or escalation before a lagging metric turns red.

## Tool
**Logic Anchor + Telemetry Specification**

Example Logic Anchor:
- **Trigger:** weak engagement signals diverge from the account's headline health state.
- **Filter:** normal seasonality, stakeholder changes, known scheduling constraints, product usage, support history, commercial context, and prior pattern.
- **Anchor:** maintain, investigate, escalate, or intervene according to the organization's evidence-backed rules.

## Friction
Replay a realistic account history containing apparently healthy headline metrics while weak signals deteriorate. Add competing accounts, incomplete notes, reassuring historical performance, and a plausible benign explanation for each individual signal.

## Evidence
Capture:
- signals noticed;
- signals ignored;
- classification;
- confidence;
- time to investigation/escalation;
- rationale;
- recovery action;
- eventual account outcome if the experiment is later tied to real historical or live data.

**Current evidence level:** **ILLUSTRATIVE**.

## Update
Use repeated misses to:
1. refine the Logic Anchor;
2. revise the signal set;
3. improve the friction scenario;
4. adjust telemetry;
5. compare simulated judgments with historical near-misses or real outcomes before making a readiness claim.

## Inspectable Claim
**Hypothesis to test:** apparently healthy aggregate metrics can lag meaningful deterioration visible in weaker behavioral signals.

No universal churn threshold or predictive effect is asserted.


## Deep Evidence Pack

**[Open Silent Churn Evidence Pack v1.0](../evidence/silent-churn/README.md)** — claim → evidence map, Logic Anchor, Friction Matrix, 12-scenario set, telemetry specification, observation schema, results, and update log.

The pack remains **ILLUSTRATIVE / PREDECLARED SIMULATION — NOT YET RUN**. No churn-prediction or retention-effect claim is made.
