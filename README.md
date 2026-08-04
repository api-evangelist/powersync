# PowerSync (powersync)

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

PowerSync is a sync engine that automatically synchronizes backend databases (Postgres, MongoDB, MySQL, SQL Server) with client-side SQLite, enabling offline-first and local-first applications. It consists of a managed cloud service (or self-hosted Docker deployment) and open-source client SDKs for JavaScript/Web, React Native, Flutter/Dart, Kotlin, Swift, Node.js, .NET, and Rust. Authentication is handled via JWT tokens with support for Auth0, Firebase, Supabase, Amazon Cognito, Azure AD, and custom backends.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/powersync/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/powersync/refs/heads/main/apis.yml)

Naftiko Run: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=powersync-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=powersync-api-evangelist&utm_content=repo)

## Tags

- Developer Tools
- Database
- Sync
- Offline-First
- SQLite
- Local-First
- Real-Time

## APIs

- **PowerSync Sync Service API** — Streaming sync protocol over HTTP/WebSocket for client SDK connectivity. [Documentation](https://docs.powersync.com/architecture/powersync-service)
- **PowerSync JavaScript / Web SDK** — Browser and JavaScript client SDK using Wasm-backed SQLite. [Documentation](https://docs.powersync.com/client-sdk-references/js-web)
- **PowerSync React Native SDK** — Client SDK for React Native and Expo offline-first mobile apps. [Documentation](https://docs.powersync.com/client-sdk-references/react-native)
- **PowerSync Flutter / Dart SDK** — Client SDK for Flutter/Dart with Rust-backed native connection pools. [Documentation](https://docs.powersync.com/client-sdk-references/flutter)
- **PowerSync Kotlin SDK** — Client SDK for Kotlin Multiplatform applications. [Documentation](https://docs.powersync.com/client-sdk-references/kotlin-multiplatform)
- **PowerSync Swift SDK** — Client SDK for iOS and macOS applications. [Documentation](https://docs.powersync.com/client-sdk-references/swift)

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/powersync-plans-pricing.yml](plans/powersync-plans-pricing.yml)
- Rate Limits: [rate-limits/powersync-rate-limits.yml](rate-limits/powersync-rate-limits.yml)
- FinOps: [finops/powersync-finops.yml](finops/powersync-finops.yml)

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://powersync.com/ |
| Documentation | https://docs.powersync.com/ |
| GitHub Organization | https://github.com/powersync-ja |
| LinkedIn | https://www.linkedin.com/showcase/journeyapps-powersync/ |
| Blog | https://powersync.com/blog |
| Pricing | https://powersync.com/pricing |
| Status Page | https://status.powersync.com/ |
| X / Twitter | https://twitter.com/powersync_ |
| Changelog | https://releases.powersync.com/ |

## Maintainers

- Kin Lane / kin@apievangelist.com
