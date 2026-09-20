# DFR Triage Scenario Set v1.0

**12 synthetic scenarios. Known experimental ground truth. No claim that these represent any agency's live workflow.**

The "expected disposition" is an experimental scoring key derived from the Logic Anchor, not operational policy.

| ID | Automation State | Primary Friction | Evidence Pattern | Expected Disposition |
|---|---|---|---|---|
| DFR-01 | supported / moderate confidence | none | evidence internally consistent | ACCEPT |
| DFR-02 | supported / high confidence | benign extra detail | no material contradiction | ACCEPT |
| DFR-03 | wrong / high confidence | corrected location | original detail superseded | INSPECT |
| DFR-04 | wrong / high confidence | late contradiction | new cue conflicts with recommendation | INSPECT |
| DFR-05 | uncertain / high confidence | overlapping information | source quality unclear | INSPECT |
| DFR-06 | wrong / high confidence | unfamiliar terminology | key phrase may be misinterpreted | INSPECT |
| DFR-07 | wrong / high confidence | calm affect / severe content | tone conflicts with content severity | INSPECT |
| DFR-08 | uncertain / moderate confidence | missing critical information | evidence insufficient | INSPECT |
| DFR-09 | wrong / high confidence | two independent contradictions | evidence directly opposes recommendation | REJECT |
| DFR-10 | supported / high confidence | irrelevant distractor | core evidence remains consistent | ACCEPT |
| DFR-11 | uncertain | authority ambiguity | decision requires authoritative path outside experiment | ESCALATE |
| DFR-12 | wrong / high confidence | workload + late correction | initial recommendation becomes unsupported | INSPECT |

## Scenario Authoring Rule

Before a run, expand each row into a short synthetic vignette with:
1. observable inputs;
2. automated recommendation;
3. stated confidence;
4. timed friction injection where applicable;
5. hidden scoring key;
6. evidence that justifies the expected experimental disposition.

Do not use real personally identifiable incident data.

## Balance

The set intentionally contains both correct and incorrect automation so participants cannot learn that "challenge the machine" is always the desired answer. The target behavior is calibrated judgment.
