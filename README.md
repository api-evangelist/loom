# Loom (loom)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
