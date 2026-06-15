# Octopus Energy (octopus-energy)

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
