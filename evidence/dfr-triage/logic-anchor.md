# DFR Triage Logic Anchor

## Trigger

An automated triage recommendation and stated confidence are presented for human disposition.

## Filter

Before accepting the recommendation, inspect decision-relevant cues for:

- source quality;
- corrected or superseded information;
- contradictory details;
- uncertainty or missing information;
- local terminology or context the model may misread;
- severity cues that do not match tone or affect;
- late-arriving information;
- evidence that confidence is not supported by the observable record.

## Anchor

The operator selects one disposition:

- **ACCEPT** — evidence currently supports the recommendation;
- **INSPECT** — uncertainty or contradiction requires independent review;
- **ESCALATE** — the decision exceeds the experiment's assumed authority or requires an authoritative human/policy path;
- **REJECT** — available evidence contradicts the recommendation.

This is an experimental decision taxonomy, not an operational DFR policy.

Any real-world authority, response tier, safety threshold, dispatch rule, legal requirement, or agency procedure is:

**UNKNOWN / REQUIRES AUTHORITATIVE VERIFICATION**

## Observable Judgment

The experiment is not measuring whether a participant clicks the expected button. It is measuring whether the participant notices the evidence that should change the disposition and can state a defensible reason.
