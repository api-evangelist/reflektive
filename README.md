# Reflektive

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

Reflektive is a cloud-based performance management platform that enables organizations to scale constructive, ongoing conversations across their workforce. The platform provides a REST API for managing performance reviews, real-time feedback, goal tracking, and engagement survey data, allowing engineering teams to integrate Reflektive data into their own systems and workflows. The API supports GET, POST, PATCH, and DELETE operations against company data using token-based authentication, with versioned endpoints covering real-time feedback, tasks, reports, goals, and review cycles. Hosted API reference documentation is available via SwaggerHub and a dedicated developer portal, enabling developers to explore and test endpoints interactively. Reflektive is now part of PeopleFluent, a learning and talent management suite operating under the Learning Technologies Group.

**Areas:** Performance Management · Human Resources · Employee Feedback · Goal Tracking · Engagement Surveys · Reviews · People Analytics · REST API

## Reflektive on APIs.io

Everything profiled for Reflektive is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/reflektive/](https://apis.io/providers/reflektive/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [Reflektive Real-time Feedback (v1) API](https://apis.io/apis/reflektive/reflektive-real-time-feedback-v1-api/) — V1 endpoint for real-time peer feedback between a single sender and recipient.
- [Reflektive Real-time Feedback (v2) API](https://apis.io/apis/reflektive/reflektive-real-time-feedback-v2-api/) — V2 endpoint for real-time feedback with support for Team Recognition (multiple recipients).
- [Reflektive Reports API](https://apis.io/apis/reflektive/reflektive-reports-api/) — Report generation endpoints that kick off asynchronous jobs and return a task UUID for status polling.
- [Reflektive Tasks API](https://apis.io/apis/reflektive/reflektive-tasks-api/) — Asynchronous task objects used to track the status of report generation jobs.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Reflektive Agentic Access](https://apis.io/agentic-access/reflektive/reflektive-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [Employee](https://apis.io/schemas/reflektive/employee/)
- [Real-time Feedback (v1)](https://apis.io/schemas/reflektive/feedback-v1/)
- [Real-time Feedback (v2)](https://apis.io/schemas/reflektive/feedback-v2/)
- [Task](https://apis.io/schemas/reflektive/task/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Reflektive Context](https://apis.io/jsonld/reflektive/reflektive-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Reflektive Vocabulary](https://apis.io/vocabularies/reflektive/reflektive-vocabulary/)

#### Examples (5)

Example requests and responses.

- [Report Generation Response](https://apis.io/examples/reflektive/report-generation-response/)
- [Task Completed](https://apis.io/examples/reflektive/task-completed/)
- [Task Pending](https://apis.io/examples/reflektive/task-pending/)
- [V1 Real Time Feedback List](https://apis.io/examples/reflektive/v1-real-time-feedback-list/)
- [V2 Real Time Feedback List](https://apis.io/examples/reflektive/v2-real-time-feedback-list/)

#### Collections (4)

Postman and Open Collection request collections.

- [Reflektive Real-time Feedback (v1) Real-time Feedback (v1) Real-time Feedback (v1) API](https://apis.io/collections/reflektive/open-reflektive-real-time-feedback-v1-api/)
- [Reflektive Real-time Feedback (v1) Real-time Feedback (v1) Real-time Feedback (v2) API](https://apis.io/collections/reflektive/open-reflektive-real-time-feedback-v2-api/)
- [Reflektive Real-time Feedback (v1) Real-time Feedback (v1) Reports API](https://apis.io/collections/reflektive/open-reflektive-reports-api/)
- [Reflektive Real-time Feedback (v1) Real-time Feedback (v1) Tasks API](https://apis.io/collections/reflektive/open-reflektive-tasks-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Reflektive — jsonschema rules](https://apis.io/rules/reflektive/reflektive-jsonschema-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Reflektive Authentication](https://apis.io/security/reflektive/reflektive-authentication/)
- [Reflektive Domain Security](https://apis.io/security/reflektive/reflektive-domain-security/)
- [Reflektive Trust Center](https://apis.io/security/reflektive/reflektive-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Reflektive Plans Pricing](https://apis.io/plans/reflektive/reflektive-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Reflektive Rate Limits](https://apis.io/rate-limits/reflektive/reflektive-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Reflektive Finops](https://apis.io/finops/reflektive/reflektive-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.reflektive.com/)
- [Documentation](https://support.reflektive.com/hc/en-us/articles/19691532062483-Technical-API-Documentation)
- [Pricing](https://www.capterra.com/p/158192/Reflektive/)
- [Blog](https://www.peoplefluent.com/blog/)
- [Status](https://support.reflektive.com/)

## API Evangelist rating

**Kin Score 39.2** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 67.2 |
| Contract governance | 23.5 |
| Operational transparency | 28.9 |
| Developer ergonomics | 23.8 |
| Access clarity | 23.7 |

**Agent readiness 22.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 21.6** — Employment & Payroll

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/reflektive/](https://apis.io/providers/reflektive/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Reflektive: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/reflektive/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
