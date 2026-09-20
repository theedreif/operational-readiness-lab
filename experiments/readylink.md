# ReadyLink — When Nothing Technically Went Wrong

**Evidence status: PUBLICLY REPORTED / CASE ANALYSIS**

> **Golden Thread:** FAILURE MODE → SIGNAL → JUDGMENT → TOOL → FRICTION → EVIDENCE → UPDATE

## Public Boundary
Public reporting in July 2026 described SFPD drone livestreams exposed through a ReadyLink that lacked authentication and had a long expiration period. WIRED reported that researchers found access to feeds from five drones, including video and telemetry. Public reporting attributed the exposure to configuration/use of the sharing feature rather than a demonstrated software vulnerability. This Lab case does **not** claim ORaaS was used by SFPD or Skydio, or infer controls that are not documented publicly.

## Failure Mode
A sharing mechanism remains technically functional while access persists beyond the intended operational audience or period.

## Signal
Candidate signals:
- share age;
- authentication state;
- expiration state;
- audience mismatch;
- viewer/access events where available;
- externally discoverable or unexpectedly persistent sharing.

## Judgment
**Does the current sharing state still match the mission's authorized audience, duration, and sensitivity?**

The judgment is not merely “is the link working?” It is “is continued exposure still authorized and proportionate?”

## Tool
**Logic Anchor + Telemetry Specification**

Example Logic Anchor:
- **Trigger:** a live share exists beyond the expected operational window or without the required access control.
- **Filter:** verify mission status, authorized audience, policy, legal/privacy requirements, and whether the share remains operationally necessary.
- **Anchor:** continue, restrict, revoke, or escalate according to the accountable organization's authoritative rule.

No universal duration or access threshold is asserted here.

## Friction
Create a bounded test share in an approved environment. Add realistic pressure: time compression, shift change, multiple simultaneous incidents, handoff between operators, or a share that remains useful after the original event appears complete.

## Evidence
Capture:
- share creation and expiration;
- authentication state;
- authorized audience;
- detection latency;
- revocation/restriction latency;
- viewer/access events where available;
- responsible authority;
- operator rationale.

**Current evidence level:** the incident itself is **PUBLICLY REPORTED**. The proposed instrument and rehearsal remain **ILLUSTRATIVE** until run and observed.

## Update
Turn the exposure pattern into a repeatable readiness check:
1. define authoritative sharing boundaries;
2. instrument persistent/exposed states;
3. rehearse detection and revocation;
4. compare rehearsal behavior with real near-misses or incidents;
5. update the Logic Anchor and controls from evidence.

## Inspectable Claim
**Supported:** apparently normal sharing behavior can create an exposure state if access configuration and operational intent diverge.

**Not established by this case:** that a specific organization lacked a particular internal control, or that this proposed instrument would have prevented the incident.

### Public sources
- WIRED, 13 July 2026: https://www.wired.com/story/sfpd-drone-video-leak-surveillance/
- Skydio ReadyLink / product guidance: https://support.skydio.com/hc/en-us/articles/29509092586139-Getting-Started-with-Skydio
