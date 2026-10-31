# Octopus Energy

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

Octopus Energy is a UK-founded retail energy supplier and the parent of Kraken Technologies, the AI-powered energy operating system that runs both Octopus and many of the world's largest utilities. Octopus operates a free, open REST API at api.octopus.energy/v1/ that exposes the full UK product catalog, electricity and gas tariff pricing (including the half-hourly wholesale-linked Agile Octopus and Tracker tariffs), meter-point details, half-hourly smart-meter consumption, and industry grid supply points. The Kraken developer portal at developer.octopus.energy adds a second REST surface generated from an OpenAPI spec plus a GraphQL API at /v1/graphql/ with API Collections grouping partner-facing queries and mutations for accounts, ledgers, billing, smart meters, EV charging, heat pumps, batteries, and Intelligent Octopus dispatch. Through Kraken Technologies the same platform powers 90M+ customer accounts at EDF, E.ON, Origin Energy, Tokyo Gas, Plentitude, National Grid, Severn Trent, and other utilities in 30 countries — making Octopus one of the most consequential open and programmable surfaces in retail energy.

**Areas:** Energy · Electricity · Gas · Renewable Energy · Smart Meter · Tariffs · Kraken · United Kingdom · DER · Electric Vehicles · Heat Pumps · Solar

## Octopus Energy on APIs.io

Everything profiled for Octopus Energy is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/octopus-energy/](https://apis.io/providers/octopus-energy/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [Octopus Energy Kraken REST API](https://apis.io/apis/octopus-energy/octopus-energy-kraken-rest-api/) — The Octopus Energy developer portal exposes a Kraken-backed REST API alongside the public GraphQL surface. The REST API is generated from an OpenAPI…
- [Octopus Energy Kraken GraphQL API](https://apis.io/apis/octopus-energy/octopus-energy-kraken-graphql-api/) — The Octopus Energy GraphQL API is the primary Kraken interface for partner and customer-facing integrations. A single /v1/graphql/ endpoint exposes queries…
- [Octopus Energy Consumption API](https://apis.io/apis/octopus-energy/octopus-energy-consumption-api/) — Half-hourly smart-meter consumption readings.
- [Octopus Energy ElectricityMeterPoints API](https://apis.io/apis/octopus-energy/octopus-energy-electricitymeterpoints-api/) — Electricity meter points (MPAN) and registered meters.
- [Octopus Energy ElectricityTariffs API](https://apis.io/apis/octopus-energy/octopus-energy-electricitytariffs-api/) — Electricity tariff unit rates and standing charges.
- [Octopus Energy GasMeterPoints API](https://apis.io/apis/octopus-energy/octopus-energy-gasmeterpoints-api/) — Gas meter points (MPRN) and registered meters.
- [Octopus Energy GasTariffs API](https://apis.io/apis/octopus-energy/octopus-energy-gastariffs-api/) — Gas tariff unit rates and standing charges.
- [Octopus Energy Industry API](https://apis.io/apis/octopus-energy/octopus-energy-industry-api/) — UK industry references such as grid supply points.
- [Octopus Energy Products API](https://apis.io/apis/octopus-energy/octopus-energy-products-api/) — Octopus Energy product catalog and tariff lookups.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### GraphQL (1)

GraphQL schemas.

- [Octopus Energy GraphQL API](https://apis.io/graphqls/octopus-energy/octopus-energy-graphql/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Octopus Energy Agentic Access](https://apis.io/agentic-access/octopus-energy/octopus-energy-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [OctopusEnergyConsumptionReading](https://apis.io/schemas/octopus-energy/octopus-energy-consumption/)
- [OctopusEnergyProduct](https://apis.io/schemas/octopus-energy/octopus-energy-product/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Octopus Energy Context](https://apis.io/jsonld/octopus-energy/octopus-energy-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Octopus Energy Vocabulary](https://apis.io/vocabularies/octopus-energy/octopus-energy-vocabulary/)

#### Examples (3)

Example requests and responses.

- [Octopus Energy List Electricity Consumption Example](https://apis.io/examples/octopus-energy/octopus-energy-list-electricity-consumption-example/)
- [Octopus Energy List Electricity Standard Unit Rates Example](https://apis.io/examples/octopus-energy/octopus-energy-list-electricity-standard-unit-rates-example/)
- [Octopus Energy List Products Example](https://apis.io/examples/octopus-energy/octopus-energy-list-products-example/)

#### Collections (8)

Postman and Open Collection request collections.

- [Octopus Energy Public Consumption API](https://apis.io/collections/octopus-energy/open-octopus-energy-consumption-api/)
- [Octopus Energy Public Consumption ElectricityMeterPoints API](https://apis.io/collections/octopus-energy/open-octopus-energy-electricitymeterpoints-api/)
- [Octopus Energy Public Consumption ElectricityTariffs API](https://apis.io/collections/octopus-energy/open-octopus-energy-electricitytariffs-api/)
- [Octopus Energy Public Consumption GasMeterPoints API](https://apis.io/collections/octopus-energy/open-octopus-energy-gasmeterpoints-api/)
- [Octopus Energy Public Consumption GasTariffs API](https://apis.io/collections/octopus-energy/open-octopus-energy-gastariffs-api/)
- [Octopus Energy Public Consumption Industry API](https://apis.io/collections/octopus-energy/open-octopus-energy-industry-api/)
- [Octopus Energy Public Consumption Products API](https://apis.io/collections/octopus-energy/open-octopus-energy-products-api/)
- [Octopus Energy Public API](https://apis.io/collections/octopus-energy/open-octopus-energy-public-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Octopus Energy — jsonschema rules](https://apis.io/rules/octopus-energy/octopus-energy-jsonschema-spectral-rules/)
- [Octopus Energy API Rules](https://apis.io/rules/octopus-energy/octopus-energy-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Octopus Energy Authentication](https://apis.io/security/octopus-energy/octopus-energy-authentication/)
- [Octopus Energy Domain Security](https://apis.io/security/octopus-energy/octopus-energy-domain-security/)
- [Octopus Energy Vulnerability Disclosure](https://apis.io/security/octopus-energy/octopus-energy-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Octopus Energy Plans Pricing](https://apis.io/plans/octopus-energy/octopus-energy-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Octopus Energy Rate Limits](https://apis.io/rate-limits/octopus-energy/octopus-energy-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Octopus Energy Finops](https://apis.io/finops/octopus-energy/octopus-energy-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://octopus.energy)
- [Documentation](https://developer.octopus.energy/docs/api/)
- [Support](https://octopus.energy/help-and-faqs/articles/api-information/)
- [Changelog](https://developer.octopus.energy/announcements/)
- [Blog](https://octopus.energy/blog/)
- [Security](https://octopus.energy/help-and-faqs/articles/security-at-octopus-energy/)
- [Privacy policy](https://octopus.energy/privacy/)
- [GitHub](https://github.com/octoenergy)

## API Evangelist rating

**Kin Score 44.9** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 58.9 |
| Contract quality | 61.3 |
| Contract governance | 13.6 |
| Operational transparency | 39.5 |
| Developer ergonomics | 48.8 |
| Access clarity | 28.9 |

**Agent readiness 24.1** — agent-aware

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
| Rate Limit Signal | derived (partial credit) |
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
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 22.1** — Energy & Utilities

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/octopus-energy/](https://apis.io/providers/octopus-energy/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Octopus Energy: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/octopus-energy/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
