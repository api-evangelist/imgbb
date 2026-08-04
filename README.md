# ImgBB (imgbb)

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

Free image hosting and sharing platform with a REST API for uploading images, retrieving shareable links, managing auto-deletion, and accessing image metadata.

**APIs.yml:** [apis.yml](apis.yml)

## APIs

- **ImgBB Image Upload API** — [Documentation](https://api.imgbb.com/)
  - Base URL: `https://api.imgbb.com/1`
  - Upload endpoint: `POST /upload`
  - Auth: API key via `key` query parameter or form field
  - Max file size: 32 MB (free) / 64 MB (Pro)
  - Expiration range: 60–15,552,000 seconds

## Plans & Pricing

| Plan | Cost | File Limit | Storage | Ads |
|------|------|-----------|---------|-----|
| Free | $0 | 32 MB | Unlimited | Yes |
| Pro Monthly | $12.99/mo | 64 MB | Unlimited | No |
| Pro Annual | $7.99/mo ($95.88/yr) | 64 MB | Unlimited | No |
| Pro 3-Year | $3.99/mo ($143.64 total) | 64 MB | Unlimited | No |

## Supporting Files

- [plans/imgbb-plans-pricing.yml](plans/imgbb-plans-pricing.yml)
- [rate-limits/imgbb-rate-limits.yml](rate-limits/imgbb-rate-limits.yml)
- [finops/imgbb-finops.yml](finops/imgbb-finops.yml)

## Tags

Image Hosting, Image Upload, File Sharing, Cloud Storage, Media, REST API

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## Maintainers

- **Kin Lane** — kin@apievangelist.com
