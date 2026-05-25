# Octopus Energy (octopus-energy)

Octopus Energy is a UK-founded retail energy supplier and the parent of Kraken Technologies, the AI-powered energy operating system that runs both Octopus and many of the world's largest utilities. Octopus operates a free, open REST API at `api.octopus.energy/v1/` that exposes the full UK product catalog, electricity and gas tariff pricing (including the half-hourly wholesale-linked Agile Octopus and Tracker tariffs), meter-point details, half-hourly smart-meter consumption, and industry grid supply points. The Kraken developer portal at `developer.octopus.energy` adds a second REST surface generated from an OpenAPI spec plus a GraphQL API at `/v1/graphql/` with API Collections grouping partner-facing queries and mutations for accounts, ledgers, billing, smart meters, EV charging, heat pumps, batteries, and Intelligent Octopus dispatch. Through Kraken Technologies the same platform powers 90M+ customer accounts at EDF, E.ON, Origin Energy, Tokyo Gas, Plentitude, National Grid, Severn Trent, and other utilities in 30 countries — making Octopus one of the most consequential open and programmable surfaces in retail energy.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/octopus-energy/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Energy, Electricity, Gas, Renewable Energy, Smart Meter, Tariffs, Kraken, UK, DER, Electric Vehicles, Heat Pumps, Solar, Battery

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Octopus Energy Public API
Free JSON-over-HTTPS REST API at `https://api.octopus.energy/v1/` exposing the UK product catalog, electricity and gas tariffs (including half-hourly Agile Octopus and Tracker rates), MPAN and MPRN meter-point lookups, half-hourly smart-meter consumption, and industry grid supply points. HTTP Basic auth with the per-customer API key as the username; products and tariffs endpoints are open and unauthenticated.

**Human URL:** [https://developer.octopus.energy/docs/api/](https://developer.octopus.energy/docs/api/)

- [Documentation](https://developer.octopus.energy/docs/api/)
- [OpenAPI](openapi/octopus-energy-public-api-openapi.yml)
- [JSON Schema — Product](json-schema/octopus-energy-product-schema.json)
- [JSON Schema — Consumption](json-schema/octopus-energy-consumption-schema.json)
- [JSON-LD](json-ld/octopus-energy-context.jsonld)
- [Naftiko Capability — Products Catalog](capabilities/products-catalog.yaml)
- [Naftiko Capability — Electricity Tariffs](capabilities/electricity-tariffs.yaml)
- [Naftiko Capability — Gas Tariffs](capabilities/gas-tariffs.yaml)
- [Naftiko Capability — Electricity Meter Points](capabilities/electricity-meter-points.yaml)
- [Naftiko Capability — Gas Meter Points](capabilities/gas-meter-points.yaml)
- [Naftiko Capability — Consumption Readings](capabilities/consumption-readings.yaml)
- [Naftiko Capability — Grid Supply Points](capabilities/grid-supply-points.yaml)

### Octopus Energy Kraken REST API
Kraken-backed REST API on the developer.octopus.energy portal, with reference documentation generated from an OpenAPI specification and feature-oriented API Collections. Partners use this surface for account onboarding, meter-point registration, consumption pulls, and tariff lookups against the Kraken energy operating system.

**Human URL:** [https://developer.octopus.energy/rest/](https://developer.octopus.energy/rest/)

- [Documentation](https://developer.octopus.energy/rest/)
- [Reference](https://developer.octopus.energy/rest/reference)
- [Authentication](https://developer.octopus.energy/rest/guides/authentication)
- [Naftiko Capability — Kraken Accounts](capabilities/kraken-accounts.yaml)
- [Naftiko Capability — Kraken Meter Points](capabilities/kraken-meter-points.yaml)

### Octopus Energy Kraken GraphQL API
Primary partner interface to the Kraken platform — a single `/v1/graphql/` endpoint exposing queries and mutations grouped into API Collections for accounts, ledgers, billing, smart meters, half-hourly consumption, EV chargers, heat pumps, batteries, Intelligent Octopus dispatch schedules, and Octopus Electroverse devices. Introspection plus a public changelog support third-party smart-charging, demand-response, and home-energy-management apps.

**Human URL:** [https://developer.octopus.energy/graphql/](https://developer.octopus.energy/graphql/)

- [Documentation](https://developer.octopus.energy/graphql/)
- [Reference](https://developer.octopus.energy/graphql/reference)
- [API Collections](https://developer.octopus.energy/graphql/collections/)
- [Changelog](https://developer.octopus.energy/announcements/)
- [Naftiko Capability — GraphQL Accounts](capabilities/graphql-accounts.yaml)
- [Naftiko Capability — GraphQL Devices](capabilities/graphql-devices.yaml)
- [Naftiko Capability — GraphQL Flexibility](capabilities/graphql-flexibility.yaml)

## Plans, Rate Limits, and FinOps

- [Plans & Pricing](plans/octopus-energy-plans-pricing.yml)
- [Rate Limits](rate-limits/octopus-energy-rate-limits.yml)
- [FinOps](finops/octopus-energy-finops.yml)

## Spectral Ruleset

- [Octopus Energy Rules](rules/octopus-energy-rules.yml)

## Vocabulary

- [Octopus Energy Vocabulary](vocabulary/octopus-energy-vocabulary.yml)

## Common Resources

- **Portal:** [https://octopus.energy](https://octopus.energy)
- **Developer Portal:** [https://developer.octopus.energy/](https://developer.octopus.energy/)
- **Changelog:** [https://developer.octopus.energy/announcements/](https://developer.octopus.energy/announcements/)
- **Customer Dashboard:** [https://octopus.energy/dashboard/](https://octopus.energy/dashboard/)
- **API Information FAQ:** [https://octopus.energy/help-and-faqs/articles/api-information/](https://octopus.energy/help-and-faqs/articles/api-information/)
- **Security:** [https://octopus.energy/help-and-faqs/articles/security-at-octopus-energy/](https://octopus.energy/help-and-faqs/articles/security-at-octopus-energy/)
- **Policies:** [https://octopus.energy/policies/](https://octopus.energy/policies/)
- **Privacy Policy:** [https://octopus.energy/privacy/](https://octopus.energy/privacy/)
- **Blog:** [https://octopus.energy/blog/](https://octopus.energy/blog/)
- **Kraken Technologies:** [https://kraken.tech/](https://kraken.tech/)
- **Kraken Customer Management:** [https://kraken.tech/customer-management](https://kraken.tech/customer-management)
- **Kraken Residential Flexibility:** [https://kraken.tech/residential-flexibility](https://kraken.tech/residential-flexibility)
- **Kraken Field Operations:** [https://kraken.tech/field-operations](https://kraken.tech/field-operations)
- **Kraken Infrastructure Flexibility:** [https://kraken.tech/infrastructure-flexibility](https://kraken.tech/infrastructure-flexibility)
- **GitHub Org:** [https://github.com/octoenergy](https://github.com/octoenergy)
- **`xocto` SDK:** [https://github.com/octoenergy/xocto](https://github.com/octoenergy/xocto)
- **`octotools` Utilities:** [https://github.com/octoenergy/octotools](https://github.com/octoenergy/octotools)
- **`public-conventions`:** [https://github.com/octoenergy/public-conventions](https://github.com/octoenergy/public-conventions)
- **Octopus Energy Japan API Example:** [https://github.com/octoenergy/oejp-api-example](https://github.com/octoenergy/oejp-api-example)
- **LinkedIn:** [https://www.linkedin.com/company/octopus-energy](https://www.linkedin.com/company/octopus-energy)
- **Kraken Tech LinkedIn:** [https://www.linkedin.com/company/krakentech](https://www.linkedin.com/company/krakentech)
- **Twitter:** [https://twitter.com/octopus_energy](https://twitter.com/octopus_energy)
- **YouTube:** [https://www.youtube.com/@OctopusEnergy](https://www.youtube.com/@OctopusEnergy)

## Highlights

- Public REST API at `api.octopus.energy/v1/` — free, JSON over HTTPS, HTTP Basic auth with per-customer API key
- Half-hourly Agile Octopus and 30-minute Octopus Tracker pricing endpoints; Agile prices can go negative
- Half-hourly smart-meter consumption pulls for electricity (MPAN + serial) and gas (MPRN + serial)
- Industry grid supply points endpoint for postcode-to-GSP resolution
- Kraken developer portal at `developer.octopus.energy` with both REST (OpenAPI-backed) and GraphQL surfaces
- Kraken GraphQL API at `/v1/graphql/` with introspection, API Collections, and public changelog
- Coverage of EV chargers, heat pumps, solar, batteries, and Intelligent Octopus dispatch via GraphQL
- Kraken Technologies SaaS platform powering 90M+ accounts across EDF, E.ON, Origin Energy, Tokyo Gas, Plentitude, National Grid, Severn Trent, and 15+ other partners in 30 countries
- Open-source ecosystem: `xocto` Python/Django utilities, `octotools` UK energy-market helpers, `public-conventions` style guide, `oejp-api-example` reference app
- UK-first with parallel Octopus Energy Japan, Australia, New Zealand, Germany, France, Italy, Spain, and US deployments on the same Kraken platform
