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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Tsinghua University (清华大学) is a public national research university in Beijing, China, a member of the C9 League and one of the highest-ranked universities in Asia. This repository catalogs Tsinghua's public developer and API footprint as an [APIs.json](https://apisjson.org) profile. Tsinghua runs no developer portal, no open data portal and no API key issuance; every system it operates for its own community terminates at one campus identity service (`id.tsinghua.edu.cn`). What it does publish, unauthenticated and machine-readable, is three documents — two from the student-run TUNA open-source mirror and one from the university's own Shibboleth identity provider — plus a DataCite membership held in the university's own name.

Re-profiled 2026-08-19 under the API Evangelist **university pipeline**, which settles *who operates* each surface before saving any contract. Every surface in this repo is `x-operator: institution`. No vendor tenancy — no Figshare, Elsevier Pure, Symplectic, Ex Libris or Dataverse — was found for this institution, which makes it one of the few in the cohort with no misattributed vendor contract to strip.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/tsinghua/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=tsinghua-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party
- `x-type: university` · `x-category: Public Research University`

## Tags

Education, Higher Education, University, China, Beijing, C9 League, Research, Open Source, Mirror, Identity Federation, Shibboleth, SAML, Research Data, DOI, Library

## Surfaces

All four are operated by Tsinghua on Tsinghua's own registrable domain.

- **Tsinghua University TUNA Open Source Mirror** (`institution`) — two live, unauthenticated JSON documents on `mirrors.tuna.tsinghua.edu.cn`: `/static/tunasync.json` (per-mirror sync status) and `/static/status/isoinfo.json` (installable-image catalog, 67 entries across os/font/app). Operated by the student TUNA association on university infrastructure.
- **Tsinghua University Identity Provider — SAML 2.0 federation metadata** (`institution`) — `idp.tsinghua.edu.cn/idp/shibboleth`, entityID `https://idp.tsinghua.edu.cn/idp/shibboleth`, `shibmd:Scope` `tsinghua.edu.cn`. Every SSO and SLO location resolves to a Tsinghua host; the university runs the SAML service itself rather than fronting it with a federation vendor.
- **Tsinghua University DataCite DOI registration and resolution** (`institution`) — DataCite direct member, symbol `TSINGHUA`, joined 2016-09-05, 194 DOIs on prefix `10.23650`, landing pages on `datacite.lib.tsinghua.edu.cn`. Registered and real; the resolution host does not answer HTTP from outside China.
- **Tsinghua University GitLab** (`institution`, gated) — `git.tsinghua.edu.cn`, authenticating only against THU ID. No contract is saved: the API is GitLab's product API, not Tsinghua's engineering.

## Domain-standard conformance (Kin Score `education` regime)

Evidenced: `saml`, `shibboleth`, `datacite`, `crossref`. Not evidenced: `oai-pmh`, `scim`, `lti`, `oneroster`, `ed-fi`, `caliper`, `qti`, `orcid`. See [conformance/tsinghua-conformance.yml](conformance/tsinghua-conformance.yml) — every hit carries the exact location it was observed at.

## Artifacts

- [openapi/](openapi/) — three contracts, with pristine pre-refine copies in `openapi/_original/`
- [conformance/](conformance/) · [authentication/](authentication/) · [errors/](errors/) · [lifecycle/](lifecycle/)
- [json-schema/](json-schema/) · [examples/](examples/) · [vocabulary/](vocabulary/) · [json-ld/](json-ld/) · [rules/](rules/)
- [plans/tsinghua-plans-pricing.yml](plans/tsinghua-plans-pricing.yml) · [rate-limits/tsinghua-rate-limits.yml](rate-limits/tsinghua-rate-limits.yml) · [finops/tsinghua-finops.yml](finops/tsinghua-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-19

## Common Properties

- Website: https://www.tsinghua.edu.cn/en/
- Library: https://lib.tsinghua.edu.cn/en/
- Identity federation: https://idp.tsinghua.edu.cn/idp/shibboleth
- AI policy: https://www.tsinghua.edu.cn/info/1182/122980.htm — 《清华大学人工智能教育应用指导原则》 (2025-12-04)
- GitHub (TUNA): https://github.com/tuna
- LinkedIn: https://www.linkedin.com/school/tsinghua-university/

## Notes

- The TUNA mirror edge returns **HTTP 403** with an HTML denial page to requests carrying a desktop-browser `User-Agent`, and **HTTP 200** to the identical request with a plain tool `User-Agent`. This is the inverse of a normal bot filter and it locks out any agent that spoofs a browser.
- `datacite.lib.tsinghua.edu.cn` completes TCP and a valid TLS handshake but returns zero bytes to an HTTP GET after 60 seconds from outside China. Live host, unreadable surface — not recorded as dead.
- The June 2026 profile recorded `status/isoinfo.json` as a 404. The document is live at the correct path, `/static/status/isoinfo.json`; that correction is why this repo now carries two mirror contracts.
- No OAI-PMH endpoint was found on any Tsinghua host, and re3data lists no Tsinghua repository at all.
- `api.`, `open.`, `data.`, `opendata.`, `oai.`, `dataverse.` and `hpc.tsinghua.edu.cn` do not resolve. A control probe on two nonsense subdomains confirms `tsinghua.edu.cn` has no wildcard DNS, so the hosts that do resolve are real.
- Research-lab GitHub orgs (THUDM, THUNLP, THUML) host substantial open-source code but are project repositories, not an institution-wide API platform, so they are recorded as pointers rather than as surfaces.
- Tsinghua University Press (`sciopen.com`, Crossref member 11138, 26,024 DOIs) is a separate publishing company and is deliberately **not** credited to the university.
- No endpoints, docs URLs, or properties were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
