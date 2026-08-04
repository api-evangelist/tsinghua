# Tsinghua University (tsinghua)

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

Tsinghua University is a leading public research university in Beijing, China, ranked #23 in the QS World University Rankings 2025. This repository catalogs Tsinghua's public developer and API footprint as an [APIs.json](https://apisjson.org) profile. Tsinghua does not run a centralized public developer portal; its student, course, and library systems are gated behind campus SSO. The most notable publicly accessible, machine-readable service is the student-run TUNA open-source mirror.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/tsinghua/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=tsinghua-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, China, Open Source

## APIs

- **TUNA Mirror Sync Status API** — Public JSON endpoint exposing sync status of hundreds of mirrored open-source repositories at the TUNA mirror. Docs: https://mirrors.tuna.tsinghua.edu.cn/ — Base URL: https://mirrors.tuna.tsinghua.edu.cn/static/tunasync.json

No centralized institutional API program is publicly documented. Course/SIS, library, and identity systems sit behind campus SSO.

## Plans

- [plans/tsinghua-plans-pricing.yml](plans/tsinghua-plans-pricing.yml)

## Rate Limits

- [rate-limits/tsinghua-rate-limits.yml](rate-limits/tsinghua-rate-limits.yml)

## FinOps

- [finops/tsinghua-finops.yml](finops/tsinghua-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.tsinghua.edu.cn/en/
- Library: https://lib.tsinghua.edu.cn/en/
- GitHub (TUNA): https://github.com/tuna
- LinkedIn: https://www.linkedin.com/school/tsinghua-university/

## Notes

- Verified live (HTTP 200): official website, library site, TUNA mirror site, the `tunasync.json` JSON endpoint, and the TUNA GitHub org.
- LinkedIn school page returns HTTP 999 (anti-bot challenge), not a dead link — the page exists.
- The older `status/isoinfo.json` mirror endpoint returns 404 and was not cataloged.
- Research-lab GitHub orgs (THUNLP, THUML, Tsinghua Database Group, thu-ml) host open-source code but are project repositories, not an institution-wide API platform, so they are not cataloged as APIs.
- No endpoints, docs URLs, or properties were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
