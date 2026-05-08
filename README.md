# Loom (loom)

Loom is an async video messaging platform (now part of Atlassian) used by teams to record screen, voice, and camera. The Loom developer platform exposes the recordSDK and embedSDK for embedding recording and playback into other apps, plus SCIM provisioning and SSO available on Enterprise.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/loom/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=loom-api-evangelist&utm_content=repo)

## Type

- **x-type:** company

## Tags:

 - Productivity, Video, Async, Communication, SaaS

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

| API | Description |
|---|---|
| Loom recordSDK | Embed Loom recording (screen/cam/mic) directly into a web app. |
| Loom embedSDK | Embed the Loom player with engagement events into a web app. |
| Loom oEmbed API | oEmbed metadata for a Loom video URL. |
| Loom SCIM Provisioning API | SCIM 2.0 user/group provisioning for Enterprise. |
| Loom SSO (SAML) | SAML 2.0 SSO configuration for Enterprise workspaces. |

## Common Properties

- [Website](https://www.loom.com/)
- [Developer Portal](https://dev.loom.com/)
- [Pricing](https://www.loom.com/pricing)
- [GitHub](https://github.com/loomhq)
- [Plans](plans/loom-plans-pricing.yml) — API Commons Plans 0.1
- [RateLimits](rate-limits/loom-rate-limits.yml) — API Commons Rate Limits 0.1
- [FinOps](finops/loom-finops.yml) — FOCUS-aligned FinOps Framework 1.0

## Artifacts

| Artifact | Path | Notes |
|---|---|---|
| Plans | `plans/loom-plans-pricing.yml` | Starter (free) / Business $18 / Business+AI $24 / Enterprise |
| Rate Limits | `rate-limits/loom-rate-limits.yml` | Plan-level video/length quotas; SCIM/oEmbed limits not publicly documented |
| FinOps | `finops/loom-finops.yml` | Per-seat subscription billing |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
