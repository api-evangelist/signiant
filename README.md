# Signiant

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

Signiant provides intelligent file-movement software that helps the world's top content creators and distributors move large files fast and securely over public and private networks. The SaaS Signiant Platform unifies four products behind a common OAuth-secured REST API: the Signiant Platform API (storage, endpoints, users, and roles across products), Jet (automated system-to-system transfers with event webhooks), Media Shuttle (person-initiated transfers with Platform, Management, and System-to-Person APIs plus a browser SDK), and Flight Deck (the Manager REST API for scheduling and running jobs). All APIs authenticate with a client_id/client_secret pair exchanged for a one-hour OAuth 2.0 JWT bearer token at platform-api-service.services.cloud.signiant.com, and access is governed by product-scoped account roles.

**Areas:** File Transfer · Media Supply Chain · Managed File Transfer · Content Delivery · Storage · Webhook · Authentication · Media and Entertainment

## Signiant on APIs.io

Everything profiled for Signiant is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/signiant/](https://apis.io/providers/signiant/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [Signiant Platform API](https://apis.io/apis/signiant/signiant-platform-api/) — Unified API to manage storage, endpoints, users, and roles across multiple Signiant products. Authenticates via OAuth 2.0 client_credentials, returning a…
- [Signiant Jet API](https://apis.io/apis/signiant/signiant-jet-api/) — Automates system-to-system job creation, endpoint management, job notifications, and event webhooks for unattended, accelerated file transfers.
- [Signiant Media Shuttle API](https://apis.io/apis/signiant/signiant-media-shuttle-api/) — Automates Media Shuttle portal management and person-initiated transfers via the Platform API, Management API, and System-to-Person Automation API, with…
- [Signiant Flight Deck Manager REST API](https://apis.io/apis/signiant/signiant-flight-deck-manager-rest-api/) — Schedules and runs jobs, manages users, and controls Signiant Manager software (Flight Deck) via a REST API.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Signiant Webhooks](https://apis.io/asyncapis/signiant/signiant-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [signiant](https://apis.io/servers/signiant/signiant/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Signiant Authentication](https://apis.io/security/signiant/signiant-authentication/)
- [Signiant Domain Security](https://apis.io/security/signiant/signiant-domain-security/)
- [Signiant Trust Center](https://apis.io/security/signiant/signiant-trust-center/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.signiant.com/)
- [Documentation](https://developer.signiant.com/)
- [Getting started](https://developer.signiant.com/signiant-platform/getting-started/)
- [API reference](https://developer.signiant.com/signiant-platform/api-documentation/)
- [Pricing](https://www.signiant.com/platform-pricing_page/)
- [Support](https://support.signiant.com/)
- [Blog](https://www.signiant.com/blog/)
- [Compliance](https://www.signiant.com/technology/security/)
- [Trust centre](https://trust.signiant.com/)
- [Terms of service](https://www.signiant.com/terms-of-use/)
- [Privacy policy](https://www.signiant.com/privacy/)
- [GitHub](https://github.com/Signiant)
- [Status](https://status.signiant.com/)

## API Evangelist rating

**Kin Score 49.7** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 45.3 |
| Contract governance | 18.2 |
| Operational transparency | 42.1 |
| Developer ergonomics | 64.3 |
| Access clarity | 39.5 |

**Agent readiness 21.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 29.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/signiant/](https://apis.io/providers/signiant/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Signiant: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/signiant/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
