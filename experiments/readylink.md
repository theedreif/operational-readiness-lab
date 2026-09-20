# ReadyLink — When Nothing Technically Went Wrong

**Evidence status: PUBLIC CASE ANALYSIS**

## Readiness Question
Can a system remain technically functional while a dangerous exposure state lacks a useful alarm?

Public reporting in 2026 described SFPD drone livestream links that were accessible without authentication and later discovered outside the intended operational context. This Lab entry uses the incident as a scenario boundary; it does not claim ORaaS was used by SFPD or Skydio, or that a specific internal control did or did not exist.

## Failure Mode
A sharing mechanism continues to work as designed while access persists beyond intended operational use.

## Signal
Candidate signals include share age, authentication state, viewer activity, and audience mismatch.

## Threshold
The accountable organization must establish the authoritative threshold from security, privacy, legal, and operational requirements. This repository does not infer one from public reporting.

## Friction
Create a bounded test share under time pressure, allow the URL to propagate within an approved test environment, and measure internal detection and revocation behavior.

## Red
A test share crosses the organization's defined exposure threshold without detection or required action.

## Evidence
Active shares, age, authentication state, viewer events where available, detection latency, revocation latency, and responsible authority.

## Update
Convert the observed exposure into a repeatable readiness check.

### Public sources
- WIRED, 13 July 2026: https://www.wired.com/story/sfpd-drone-video-leak-surveillance/
- Skydio ReadyLink security update: https://www.skydio.com/blog/readylink-security-update-sfpd
- ABC7: https://abc7news.com/post/san-francisco-police-department-drone-livestreams-exposed-online-months-wired-investigation-shows/19501550/
- DroneXL: https://dronexl.co/2026/07/13/sfpd-skydio-drone-feed-live-internet/
