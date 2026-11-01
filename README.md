# Tsinghua University

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

Tsinghua University (清华大学) is a public national research university in Beijing, China, a member of the C9 League and the Double First-Class construction programme, and one of the highest-ranked universities in Asia. Its programmable footprint is small, real, and almost entirely invisible from outside the campus network. Tsinghua operates no developer portal, no open data portal and no API key issuance of any kind: api.tsinghua.edu.cn, open.tsinghua.edu.cn and data.tsinghua.edu.cn do not resolve. Every system the university runs for its own community — the learning platform (learn.tsinghua.edu.cn), course registration (zhjwxk.cic.tsinghua.edu.cn), the institutional GitLab (git.tsinghua.edu.cn), Tsinghua Cloud (cloud.tsinghua.edu.cn), the information portal and the campus card — terminates at one electronic identity service, id.tsinghua.edu.cn, and is unreachable without institutional affiliation. What Tsinghua does publish, unauthenticated and machine-readable, is three things, and all three are the institution's own rather than a vendor's. First, the TUNA open-source mirror (mirrors.tuna.tsinghua.edu.cn), run by the student TUNA association on the university's own domain and infrastructure, which serves two live JSON documents: the tunasync synchronization status of every mirrored repository, and a catalog of the installable images for 66 distributions, font collections and applications. Second, and more consequential for a university, Tsinghua runs its own Shibboleth Identity Provider at idp.tsinghua.edu.cn and publishes SAML 2.0 federation metadata about it — entityID https://idp.tsinghua.edu.cn/idp/shibboleth, shibmd:Scope tsinghua.edu.cn — with every SingleSignOnService and SingleLogoutService location resolving to a Tsinghua host rather than to a federation vendor. Third, the university library holds a DataCite direct membership in its own name (symbol TSINGHUA, joined 2016) under which 194 DOIs are registered on prefix 10.23650, resolving to datacite.lib.tsinghua.edu.cn. Two honest qualifications belong in this description. The DOI landing-page host completes TCP and TLS but returns nothing to an HTTP GET after 60 seconds from outside China, so those 194 DOIs are registered but unresolvable from here. And the mirror's edge answers HTTP 403 to requests carrying a desktop-browser User-Agent while answering the same request 200 for a plain tool User-Agent — the inverse of the usual bot filter, and enough to lock out any agent that spoofs a browser. Notably, Tsinghua holds no Figshare, Elsevier Pure, Symplectic, Ex Libris or Dataverse tenancy that could be found: unlike most of this cohort, there is no vendor contract masquerading as this institution's engineering. Tsinghua research groups (THUDM, THUNLP, THUML, TUNA) publish substantial open-source code on GitHub, but those are project repositories, not an institutional API programme, and they are recorded as pointers rather than as surfaces.

**Areas:** Education · Higher Education · University · China · Beijing · C9 League · Research · Open Source · Mirror · Identity Federation · Shibboleth · SAML

## Tsinghua University on APIs.io

Everything profiled for Tsinghua University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/tsinghua/](https://apis.io/providers/tsinghua/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [Tsinghua University TUNA Open Source Mirror](https://apis.io/apis/tsinghua/tsinghua-mirror-status-api/) — The TUNA open-source software mirror is the one surface Tsinghua publishes that behaves like a public API. It is operated by TUNA (Tsinghua University TUNA…
- [Tsinghua University Identity Provider — SAML 2.0 Federation Metadata](https://apis.io/apis/tsinghua/identity-federation/) — Tsinghua operates its own Shibboleth Identity Provider and publishes machine-readable SAML 2.0 metadata about it at a public, unauthenticated URL on its own…
- [Tsinghua University DataCite DOI Registration and Resolution](https://apis.io/apis/tsinghua/datacite-doi/) — Tsinghua University holds a DataCite membership in its own name — symbol TSINGHUA, memberType direct_member, organizationType academicInstitution, joined…
- [Tsinghua University GitLab](https://apis.io/apis/tsinghua/gitlab/) — Tsinghua runs its own GitLab instance at git.tsinghua.edu.cn, on its own registrable domain and behind its own identity service — the sign-in page's only…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Tsinghua Agentic Access](https://apis.io/agentic-access/tsinghua/tsinghua-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [IsoCatalogEntry](https://apis.io/schemas/tsinghua/tsinghua-mirror-isoinfo/)
- [MirrorStatus](https://apis.io/schemas/tsinghua/tsinghua-mirror-status/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Tsinghua Mirror Status Structure](https://apis.io/json-structure/tsinghua/tsinghua-mirror-status-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Tsinghua Context](https://apis.io/jsonld/tsinghua/tsinghua-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Tsinghua TUNA Mirror Sync Vocabulary](https://apis.io/vocabularies/tsinghua/tsinghua-vocabulary/)

#### Examples (1)

Example requests and responses.

- [Tsinghua Getmirrorisocatalog Example](https://apis.io/examples/tsinghua/tsinghua-getMirrorIsoCatalog-example/)

#### Collections (1)

Postman and Open Collection request collections.

- [TUNA Mirror Sync Status Mirror Status API](https://apis.io/collections/tsinghua/open-tsinghua-mirror-status-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Tsinghua University — jsonschema rules](https://apis.io/rules/tsinghua/tsinghua-jsonschema-spectral-rules/)
- [Tsinghua University API Rules](https://apis.io/rules/tsinghua/tsinghua-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Tsinghua Authentication](https://apis.io/security/tsinghua/tsinghua-authentication/)
- [Tsinghua Domain Security](https://apis.io/security/tsinghua/tsinghua-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Tsinghua Plans Pricing](https://apis.io/plans/tsinghua/tsinghua-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Tsinghua Rate Limits](https://apis.io/rate-limits/tsinghua/tsinghua-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Tsinghua Finops](https://apis.io/finops/tsinghua/tsinghua-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.tsinghua.edu.cn/en/)
- [Documentation](https://mirrors.tuna.tsinghua.edu.cn/help/AOSP/)
- [GitHub](https://github.com/tuna)

## API Evangelist rating

**Kin Score 35.0** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 60.0 |
| Contract governance | 17.4 |
| Operational transparency | 26.3 |
| Developer ergonomics | 21.4 |
| Access clarity | 21.1 |

**Agent readiness 24.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/tsinghua/](https://apis.io/providers/tsinghua/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Tsinghua University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/tsinghua/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
