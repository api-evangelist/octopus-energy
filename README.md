# Octopus Energy (octopus-energy)

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

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/octopus-energy/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/octopus-energy/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Energy
- Electricity
- Gas
- Renewable Energy
- Smart Meter
- Tariffs
- Kraken
- UK
- DER
- Electric Vehicles
- Heat Pumps
- Solar
- Battery

## Timestamps

- **Created:** 2026-05-25T00:00:00.000Z
- **Modified:** 2026-05-25

## APIs

### Octopus Energy Public API

The Octopus Energy Public API is a free, JSON-over-HTTPS REST API exposing the company's full UK product catalog, electricity and gas tariff pricing, electricity and gas meter-point information, half-hourly smart-meter consumption data, and industry grid supply points. Customers authenticate with their own API key over HTTP Basic auth to access their meters and consumption; the products and tariffs surfaces are open and unauthenticated. The Agile Octopus and Octopus Tracker tariffs publish half-hourly and daily wholesale-linked unit rates that downstream automations consume to schedule EV charging, heat-pump heating, and battery dispatch.

- **Human URL:** [https://developer.octopus.energy/docs/api/](https://developer.octopus.energy/docs/api/)
- **Base URL:** `https://api.octopus.energy/v1/`

#### Tags

- Energy
- Electricity
- Gas
- Tariffs
- Meter Points
- Consumption
- Smart Meter
- UK

#### Properties

- [Documentation](https://developer.octopus.energy/docs/api/)
- [Getting Started](https://developer.octopus.energy/rest/guides/api-basics)
- [OpenAPI](openapi/octopus-energy-public-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/octopus-energy-public-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/octopus-energy-public-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/octopus-energy-product-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/octopus-energy-consumption-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/octopus-energy-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Octopus Energy Kraken REST API

The Octopus Energy developer portal exposes a Kraken-backed REST API alongside the public GraphQL surface. The REST API is generated from an OpenAPI specification published in the developer portal Reference section, with API Collections that group endpoints by feature. Partners use the REST API for account onboarding, meter-point registration, consumption pulls, and tariff lookups against the Kraken energy operating system.

- **Human URL:** [https://developer.octopus.energy/rest/](https://developer.octopus.energy/rest/)

#### Tags

- Energy
- Kraken
- Accounts
- Meter Points
- Consumption
- Tariffs
- Smart Meter
- REST

#### Properties

- [Documentation](https://developer.octopus.energy/rest/)
- [Documentation](https://developer.octopus.energy/rest/reference)
- [Getting Started](https://developer.octopus.energy/rest/guides)
- [Authentication](https://developer.octopus.energy/rest/guides/authentication)
- [Postman Collection](collections/octopus-energy-public-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/octopus-energy-public-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Octopus Energy Kraken GraphQL API

The Octopus Energy GraphQL API is the primary Kraken interface for partner and customer-facing integrations. A single /v1/graphql/ endpoint exposes queries and mutations grouped into API Collections by feature — accounts, ledgers, billing, smart meters, half-hourly consumption, EV chargers, heat pumps, batteries, Intelligent Octopus dispatch schedules, and Octopus Electroverse devices. Kraken's GraphQL introspection plus a public changelog let third-party developers build smart-charging, demand-response, and home-energy-management apps directly against Kraken-powered utilities.

- **Human URL:** [https://developer.octopus.energy/graphql/](https://developer.octopus.energy/graphql/)
- **Base URL:** `https://api.octopus.energy/v1/graphql/`

#### Tags

- Energy
- Kraken
- GraphQL
- Accounts
- Meter Points
- Smart Meter
- Devices
- Flexibility

#### Properties

- [Documentation](https://developer.octopus.energy/graphql/)
- [Documentation](https://developer.octopus.energy/graphql/reference)
- [Getting Started](https://developer.octopus.energy/graphql/guides)
- [Documentation](https://developer.octopus.energy/graphql/collections/)
- [Authentication](https://developer.octopus.energy/graphql/guides/authentication)
- [Changelog](https://developer.octopus.energy/announcements/)
- [Postman Collection](collections/octopus-energy-public-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/octopus-energy-public-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://octopus.energy)
- [Portal](https://developer.octopus.energy/)
- [Documentation](https://developer.octopus.energy/docs/api/)
- [Documentation](https://developer.octopus.energy/rest/)
- [Documentation](https://developer.octopus.energy/graphql/)
- [Changelog](https://developer.octopus.energy/announcements/)
- [Sign Up](https://developer.octopus.energy/auth/login/)
- [Sign Up](https://octopus.energy/dashboard/)
- [Support](https://octopus.energy/help-and-faqs/articles/api-information/)
- [Security](https://octopus.energy/help-and-faqs/articles/security-at-octopus-energy/)
- [Documentation](https://octopus.energy/policies/)
- [Privacy Policy](https://octopus.energy/privacy/)
- [Blog](https://octopus.energy/blog/)
- [Press](https://octopus.energy/press/)
- [Careers](https://octopus.energy/careers/)
- [About Us](https://octopus.energy/about-us/)
- [Contact Us](https://octopus.energy/contact-us/)
- [Portal](https://kraken.tech/)
- [Blog](https://kraken.tech/news)
- [Documentation](https://kraken.tech/customer-management)
- [Documentation](https://kraken.tech/residential-flexibility)
- [Documentation](https://kraken.tech/field-operations)
- [Documentation](https://kraken.tech/infrastructure-flexibility)
- [Documentation](https://octopus.energy/agile/)
- [Documentation](https://octopus.energy/smart/tracker/)
- [Documentation](https://octopus.energy/smart/intelligent-octopus-go/)
- [Documentation](https://octopus.energy/electric-vehicles/electroverse/)
- [Documentation](https://octopus.energy/heat-pumps/)
- [Documentation](https://octopusev.com/)
- [GitHub Organization](https://github.com/octoenergy)
- [Tool](https://github.com/octoenergy/public-conventions)
- [SDK](https://github.com/octoenergy/xocto)
- [Code Examples](https://github.com/octoenergy/oejp-api-example)
- [Tool](https://github.com/octoenergy/octotools)
- [Code Examples](https://github.com/octoenergy/techzero-hackathon-2024)
- [Tool](https://github.com/octoenergy/timeserio)
- [Tool](https://github.com/octoenergy/terraform-provider-splitpolicies)
- [LinkedIn](https://www.linkedin.com/company/octopus-energy)
- [LinkedIn](https://www.linkedin.com/company/krakentech)
- [Twitter](https://twitter.com/octopus_energy)
- [YouTube](https://www.youtube.com/@OctopusEnergy)
- [Plans](plans/octopus-energy-plans-pricing.yml)
- [Rate Limits](rate-limits/octopus-energy-rate-limits.yml)
- [Fin Ops](finops/octopus-energy-finops.yml)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
