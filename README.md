# Tsinghua University (tsinghua)

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
