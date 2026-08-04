# CharlieHR (charliehr)

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

CharlieHR is a small-business HR platform that handles people management, time off, onboarding, and employee records. Its REST API exposes a company's team members, leave requests, leave allowances, and company structure (offices and teams) using OAuth 2.0 client credentials over HTTPS.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/charliehr/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/charliehr/refs/heads/main/apis.yml)

## Tags

- HR
- HRIS
- People
- Leave
- Time Off

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### CharlieHR Team Members

Read a company's team members, individual team member records, and their associated notes, with pagination support.

- **Human URL:** [https://www.charliehr.com/api_docs/](https://www.charliehr.com/api_docs/)
- **Base URL:** `https://charliehr.com/api/v1`

#### Tags

- Team Members
- Employees
- People

#### Properties

- [Documentation](https://www.charliehr.com/api_docs/)
- [OpenAPI](openapi/charliehr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/charliehr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/charliehr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CharlieHR Leave / Absences

List and retrieve leave requests across the company or for a single team member, including request dates, status, and leave type.

- **Human URL:** [https://www.charliehr.com/api_docs/](https://www.charliehr.com/api_docs/)
- **Base URL:** `https://charliehr.com/api/v1`

#### Tags

- Leave
- Absences
- Time Off

#### Properties

- [Documentation](https://www.charliehr.com/api_docs/)
- [OpenAPI](openapi/charliehr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/charliehr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/charliehr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CharlieHR Leave Allowances

List current leave allowances for all team members or fetch the leave allowance for a specific team member.

- **Human URL:** [https://www.charliehr.com/api_docs/](https://www.charliehr.com/api_docs/)
- **Base URL:** `https://charliehr.com/api/v1`

#### Tags

- Leave Allowances
- Balances
- Time Off

#### Properties

- [Documentation](https://www.charliehr.com/api_docs/)
- [OpenAPI](openapi/charliehr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/charliehr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/charliehr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CharlieHR Company

Retrieve the authenticated company record and its organizational structure - offices and teams - used to group and locate team members.

- **Human URL:** [https://www.charliehr.com/api_docs/](https://www.charliehr.com/api_docs/)
- **Base URL:** `https://charliehr.com/api/v1`

#### Tags

- Company
- Offices
- Teams

#### Properties

- [Documentation](https://www.charliehr.com/api_docs/)
- [OpenAPI](openapi/charliehr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/charliehr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/charliehr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/CharlieHR)
- [LinkedIn](https://www.linkedin.com/company/charliehr)
- [Website](https://www.charliehr.com/)
- [Documentation](https://www.charliehr.com/api_docs/)
- [Plans](plans/charliehr-plans-pricing.yml)
- [Rate Limits](rate-limits/charliehr-rate-limits.yml)
- [Fin Ops](finops/charliehr-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
