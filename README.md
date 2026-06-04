# EPFL (epfl)

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
