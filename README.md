# EPFL

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

EPFL (École polytechnique fédérale de Lausanne) is a Swiss federal institute of technology in Lausanne and one of the two federal technical universities in the ETH Domain. Measured on what it actually operates rather than what runs under its name, EPFL is unusual among research universities: it runs FOUR public, unauthenticated APIs on its own registrable domain. The Actu news API (actu.epfl.ch) and the Memento events API (memento.epfl.ch) are Django REST Framework services with live interactive CoreAPI documentation; Infoscience (infoscience.epfl.ch) is EPFL's self-hosted DSpace-CRIS repository serving a HAL/HATEOAS REST API and a working OAI-PMH provider; and GETprime (getprime.epfl.ch), from the Gene Expression Core Facility, answers primer-design queries over HTTP. EPFL publishes no OpenAPI for any of them and operates no developer portal, no API gateway (api.epfl.ch resolves only to RFC 1918 space), no plans, no rate-limit documentation and no deprecation policy — every OpenAPI in this repo is derived by API Evangelist and marked as such. Its library discovery runs on Ex Libris Primo/Alma through the SLSP consortium and its identity provider endpoint is hosted by SWITCH edu-ID; both are recorded here as tenant relationships, not as EPFL engineering. There is no public course-catalog or timetable API.

**Areas:** University · Higher Education · Education · Technical University · Research · Research Repository · Open Access · Identity Federation · News · Event · Switzerland · Europe

## EPFL on APIs.io

Everything profiled for EPFL is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/epfl/](https://apis.io/providers/epfl/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [EPFL Actu News API](https://apis.io/apis/epfl/actu-news-api/) — EPFL's public news API, serving the Actu newsroom — news, projects, channels, faculties, categories, themes and publics. Django REST Framework, read-only…
- [EPFL Memento Events API](https://apis.io/apis/epfl/memento-events-api/) — EPFL's public events and agenda API, serving the Memento calendar — events, mementos, registrations, domains, categories, faculties, spoken languages and…
- [EPFL Infoscience Institutional Repository](https://apis.io/apis/epfl/infoscience/) — Infoscience is EPFL's institutional repository and CRIS, self-hosted on EPFL infrastructure and running DSpace-CRIS. It exposes a HAL/HATEOAS REST API…
- [EPFL Graph Search](https://apis.io/apis/epfl/graphsearch/) — EPFL Graph Search is an EPFL-built knowledge-graph search over EPFL concepts, people, units and publications. It has a live HTTP API router — every /api/*…
- [EPFL go.epfl.ch URL Shortener API](https://apis.io/apis/epfl/go-url-shortener/) — EPFL's institutional URL shortener publishes an API page describing token-authenticated link creation. Access is gated to EPFL community members holding an…
- [EPFL SAML Identity Federation Entities](https://apis.io/apis/epfl/identity-federation/) — EPFL is a registered member of SWITCHaai, the Swiss academic identity federation, which is exported to eduGAIN. Seventeen entityIDs containing "epfl" appear…
- [EPFL Identity Provider (SWITCH edu-ID, tenant)](https://apis.io/apis/epfl/eduid-idp/) — EPFL's SAML identity provider is delivered by SWITCH edu-ID as a hosted, EPFL-branded IdP. The relationship is a real institutional fact — EPFL…
- [EPFL Library Discovery on swisscovery (Ex Libris, tenant)](https://apis.io/apis/epfl/swisscovery-library/) — EPFL's library discovery and resolution run on Ex Libris Primo VE with Alma behind it, delivered through SLSP (Swiss Library Service Platform). EPFL's…
- [EPFL Primers API](https://apis.io/apis/epfl/epfl-primers-api/) — The Primers API from EPFL — 1 operation(s) for primers.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Epfl Agentic Access](https://apis.io/agentic-access/epfl/epfl-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [EPFL Memento Event](https://apis.io/schemas/epfl/epfl-event/)
- [EPFL Actu News](https://apis.io/schemas/epfl/epfl-news/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Epfl Event Structure](https://apis.io/json-structure/epfl/epfl-event-structure/)
- [Epfl News Structure](https://apis.io/json-structure/epfl/epfl-news-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Epfl Context](https://apis.io/jsonld/epfl/epfl-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [EPFL API Vocabulary](https://apis.io/vocabularies/epfl/epfl-vocabulary/)

#### Examples (2)

Example requests and responses.

- [Epfl Listevents Example](https://apis.io/examples/epfl/epfl-listEvents-example/)
- [Epfl Listnews Example](https://apis.io/examples/epfl/epfl-listNews-example/)

#### Collections (13)

Postman and Open Collection request collections.

- [EPFL Categories API](https://apis.io/collections/epfl/open-epfl-categories-api/)
- [EPFL Channels API](https://apis.io/collections/epfl/open-epfl-channels-api/)
- [EPFL Domains API](https://apis.io/collections/epfl/open-epfl-domains-api/)
- [EPFL Events API](https://apis.io/collections/epfl/open-epfl-events-api/)
- [EPFL Faculties API](https://apis.io/collections/epfl/open-epfl-faculties-api/)
- [EPFL Mementos API](https://apis.io/collections/epfl/open-epfl-mementos-api/)
- [EPFL News API](https://apis.io/collections/epfl/open-epfl-news-api/)
- [EPFL Projects API](https://apis.io/collections/epfl/open-epfl-projects-api/)
- [EPFL Publics API](https://apis.io/collections/epfl/open-epfl-publics-api/)
- [EPFL Registrations API](https://apis.io/collections/epfl/open-epfl-registrations-api/)
- [EPFL Spoken Languages API](https://apis.io/collections/epfl/open-epfl-spoken-languages-api/)
- [EPFL Themes API](https://apis.io/collections/epfl/open-epfl-themes-api/)
- [EPFL Vulgarizations API](https://apis.io/collections/epfl/open-epfl-vulgarizations-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [EPFL — jsonschema rules](https://apis.io/rules/epfl/epfl-jsonschema-spectral-rules/)
- [EPFL API Rules](https://apis.io/rules/epfl/epfl-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Epfl Authentication](https://apis.io/security/epfl/epfl-authentication/)
- [Epfl Domain Security](https://apis.io/security/epfl/epfl-domain-security/)
- [Epfl Vulnerability Disclosure](https://apis.io/security/epfl/epfl-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Epfl Scopes](https://apis.io/scopes/epfl/epfl-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Epfl Plans Pricing](https://apis.io/plans/epfl/epfl-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Epfl Rate Limits](https://apis.io/rate-limits/epfl/epfl-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Epfl Finops](https://apis.io/finops/epfl/epfl-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.epfl.ch)
- [Documentation](https://actu.epfl.ch/api-docs/)
- [API reference](https://memento.epfl.ch/api/docs/)
- [Support](https://www.epfl.ch/campus/library/)
- [Blog](https://actu.epfl.ch/)
- [Terms of service](https://www.epfl.ch/about/overview/regulations-and-guidelines/)
- [Privacy policy](https://www.epfl.ch/about/presidency/presidents-team/legal-affairs/epfl-privacy-policy/)
- [GitHub](https://github.com/epfl-si)

## API Evangelist rating

**Kin Score 36.0** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 24.6 |
| Contract governance | 31.8 |
| Operational transparency | 23.7 |
| Developer ergonomics | 35.7 |
| Access clarity | 26.3 |

**Agent readiness 21.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | documented (partial credit) |
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

**Regulatory alignment 40.2** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/epfl/](https://apis.io/providers/epfl/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for EPFL: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/epfl/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
