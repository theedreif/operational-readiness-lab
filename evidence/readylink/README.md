# ReadyLink Evidence Pack v1.0

**Case evidence: PUBLICLY REPORTED**  
**Instrument evidence: ILLUSTRATIVE / NOT YET RUN**

> **Golden Thread:** FAILURE MODE → SIGNAL → JUDGMENT → TOOL → FRICTION → EVIDENCE → UPDATE

## Purpose

Convert the ReadyLink case from a narrative incident analysis into an inspectable evidence package that separates:

1. what public sources establish;
2. what the Lab infers as a useful readiness question;
3. what the proposed instrument would measure;
4. what remains unknown until an authorized rehearsal or field observation occurs.

## Public Case

WIRED reported in July 2026 that security researchers found a public web address exposing SFPD live drone feeds. The reporting described five drone feeds, color and thermal imagery, location/telemetry information, and pilot identifiers. WIRED reported that the ReadyLink appeared to have no authentication requirement and a one-year expiration. SFPD said the address was an internal restricted link and later said it had put more restrictive sharing protocols in place.

Skydio's published ReadyLink guidance documents configurable start/end dates, an optional 4–6 digit PIN for ReadyLinks created in Skydio Cloud, immediate revocation, and a recommendation to use short-duration ReadyLinks whenever possible because longer durations may permit access beyond intended use.

## Failure Mode

A sharing mechanism remains technically functional while its access state diverges from the intended audience, duration, sensitivity, or mission need.

## Judgment Under Test

**Does the current sharing state still match the mission's authorized audience, duration, and sensitivity?**

## Evidence Pack

- [Source Record](source-record.md)
- [Claim → Evidence Map](claim-evidence-map.md)
- [Logic Anchor](logic-anchor.md)
- [Friction Matrix](friction-matrix.md)
- [Telemetry Plan](telemetry-plan.md)
- [Rehearsal Protocol](rehearsal-protocol.md)
- [Observation Template](observations.csv)
- [Results](results.md)
- [Update Log](update-log.md)

## Evidence Boundary

This pack does not claim that ORaaS or any Lab instrument was used by SFPD or Skydio. It does not establish SFPD's undocumented internal procedures, the identity or intent of the person who configured the link, how many unauthorized people viewed it, or whether this Lab instrument would have prevented the incident.

The public incident and the proposed readiness instrument have different evidence levels.

> **Trace everything. Duplicate nothing. Earn the claim in arrears.**
