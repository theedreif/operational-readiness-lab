# ReadyLink Source Record

**Source record date:** 2026-09-20

This record preserves the public provenance used by the Lab case. It is a source map, not a substitute for the original sources.

## Source 1 — WIRED

**Title:** A Leak of San Francisco Police Drone Footage Exposes the New Reality of Urban Surveillance  
**Published:** 2026-07-13  
**URL:** https://www.wired.com/story/sfpd-drone-video-leak-surveillance/

### Publicly reported facts used by this case

WIRED reported that:

- researchers Sam Curry and Maik Robert found a public web address exposing real-time SFPD drone footage;
- the exposed material involved feeds from five drones;
- the material included color and thermal video plus location/telemetry information and pilot identifiers;
- the ReadyLink appeared to have been configured without an authentication requirement and with an expiration of one year;
- the researchers said they did not bypass authentication to view the stream;
- SFPD characterized the address as an internal restricted link and said it later put more restrictive sharing protocols in place;
- the reporting attributed the exposure to configuration/use of the sharing feature rather than demonstrating a Skydio software vulnerability.

## Source 2 — Skydio ReadyLink guidance

**Title:** How to share your Skydio live streams  
**URL:** https://support.skydio.com/hc/en-us/articles/26335293031195-How-to-share-your-Skydio-live-streams

### Product behavior documented by Skydio

Skydio documents that a ReadyLink created in Skydio Cloud can:

- be named and scoped to a single drone or all drones in an organization;
- optionally use a 4–6 digit access PIN;
- have a configured start date and end date;
- be edited;
- be revoked, with revocation documented as immediate;
- expose viewer count while streaming.

Skydio's guidance recommends short-duration ReadyLinks whenever possible and warns that longer durations may allow access beyond intended use.

## Source 3 — Skydio Getting Started guidance

**Title:** Getting Started with Skydio  
**URL:** https://support.skydio.com/hc/en-us/articles/29509092586139-Getting-Started-with-Skydio

Skydio describes ReadyLink as a feature for sharing live streams internally and externally and notes that multiple ReadyLinks can be active simultaneously.

## Provenance Rule

If a future source contradicts or materially updates these facts, preserve this record and add a dated update rather than silently rewriting the historical source state.
