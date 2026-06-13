# ImgBB (imgbb)

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
