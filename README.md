# East West Bank (east-west-bank)

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

East West Bank is the California state-chartered commercial banking subsidiary of East West Bancorp, Inc. (NASDAQ: EWBC), headquartered in Pasadena, California, with roughly $79.7 billion in total assets and more than 125 locations across the United States and Greater China. A Member FDIC institution and one of the few U.S. banks holding a full banking license in China, it specializes in cross-border U.S.-China commercial banking, treasury, and Global Transaction Services (GTS).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/east-west-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/east-west-bank/refs/heads/main/apis.yml)

## Open Finance Posture

The United States has no single mandated open-banking contract; open finance is voluntary and fragmented. East West Bank's posture:

- **First-party developer portal — YES.** East West Bank runs a live developer portal branded "Bridge Open Banking" at [apiportal.eastwestbank.com](https://apiportal.eastwestbank.com/), aimed at commercial / Global Transaction Services (GTS) clients. Documented capabilities let applications manage sub-accounts, retrieve balances, transfer funds, and obtain information on commercial accounts, with a sandbox of live test accounts and test payments. The program is early-stage ("more APIs coming soon") and access is gated behind sales onboarding.
- **Downloadable OpenAPI/Swagger — NO.** Specifications and reference detail sit behind portal sign-in and sales onboarding; nothing is publicly downloadable, so no spec has been harvested.
- **FDX participation / CFPB Section 1033 posture — none documented** as of this profile.
- **Aggregator access — YES (Plaid).** Consumer-permissioned data access is available indirectly through the Plaid aggregator.

## Tags

- Financial Services
- Banking
- United States
- Commercial Banking
- Treasury Management
- Cross-Border
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

### East West Bank Bridge Open Banking API

East West Bank's first-party commercial banking API program, delivered through the "Bridge Open Banking" developer portal for GTS clients. Documented capabilities cover managing sub-accounts, retrieving account balances, transferring funds, and obtaining information on commercial accounts. Developers create an application for a single authentication credential and test against a sandbox of live test accounts. Access is gated behind sales onboarding; specifications are not publicly downloadable.

- **Human URL:** [https://apiportal.eastwestbank.com/how-it-works](https://apiportal.eastwestbank.com/how-it-works)

#### Tags

- Accounts
- Balances
- Payments
- Transfers

#### Properties

- [Documentation](https://apiportal.eastwestbank.com/how-it-works)
- [API Reference](https://apiportal.eastwestbank.com/apis)
- [Documentation](https://apiportal.eastwestbank.com/products)

## Common Properties

- [Website](https://www.eastwestbank.com/)
- [Developer Portal](https://apiportal.eastwestbank.com/)
- [Documentation](https://apiportal.eastwestbank.com/how-it-works)
- [Support](https://apiportal.eastwestbank.com/support)
- [Privacy Policy](https://apiportal.eastwestbank.com/privacy-policy)
- [GitHub Organization](https://github.com/eastwestbank)
- [LinkedIn](https://www.linkedin.com/company/east-west-bank)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
