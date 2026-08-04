# EPFL (epfl)

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

EPFL (École Polytechnique Fédérale de Lausanne) is a public research university in Lausanne, Switzerland, ranked #19 in the QS World University Rankings 2025. This repository catalogs EPFL's public developer and API footprint as an [APIs.json](https://apisjson.org) provider profile.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/epfl/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=epfl-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Data, Switzerland, Europe

## APIs

- **EPFL Actu News API** — public REST API for EPFL news, projects and channels. Docs: https://actu.epfl.ch/api-docs/ (base `https://actu.epfl.ch/api/v1/`)
- **EPFL Memento Events API** — public REST API for EPFL events and calendars. Docs: https://memento.epfl.ch/api/docs/ (base `https://memento.epfl.ch/api/v1/`)
- **EPFL Infoscience Repository API** — DSpace 7 HATEOAS/HAL REST API and OAI-PMH endpoint for EPFL research output. REST: https://infoscience.epfl.ch/server/api · OAI-PMH: https://infoscience.epfl.ch/oai/request?verb=Identify

## Plans, Rate Limits, and FinOps

- Plans & Pricing: [plans/epfl-plans-pricing.yml](plans/epfl-plans-pricing.yml)
- Rate Limits: [rate-limits/epfl-rate-limits.yml](rate-limits/epfl-rate-limits.yml)
- FinOps: [finops/epfl-finops.yml](finops/epfl-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.epfl.ch
- GitHub: https://github.com/epfl-si
- LinkedIn: https://www.linkedin.com/school/epfl/
- Review: [review.yml](review.yml)

## Notes

All endpoints were probed live on 2026-06-03. The Actu and Memento APIs publish live interactive documentation and default to unauthenticated REST access. Infoscience runs DSpace 7.6.2 with a public REST API and OAI-PMH harvesting. EPFL has no single unified developer portal, and some services (e.g. `go.epfl.ch`) are gated to the EPFL community with a token. No endpoints, docs, or properties were fabricated; only confirmed resources are listed.

## Maintainers

- Kin Lane — kin@apievangelist.com
