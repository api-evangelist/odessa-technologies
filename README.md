# Odessa Technologies

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

Profile of [Odessa Technologies](https://www.odessainc.com/), a Philadelphia-headquartered lease and loan management software company founded in 1998 with 1,000+ employees across six countries. The Odessa Platform manages roughly $200B in assets for banks, captive finance companies, and independent lenders across equipment finance and auto finance.

## Summary

Odessa is a single-platform asset-finance ISV — originations, servicing, and remarketing run on one asset-level data model with a low-code configuration layer, packaged integrations to credit/GL/eSign/CRM/tax/valuation providers, an Odessa AI layer for agentic workflows, and managed SaaS hosting on Microsoft Azure (with single-tenant dedicated-environment option). Marketing positions the platform as "API-first" with "documented APIs to connect to any application or data source," but those APIs, the developer documentation, the SDK, and the sandbox are gated behind the customer portal at `odessainc.my.site.com/customer`. There is no public OpenAPI specification, no public developer portal URL, no public SDK, no populated GitHub organization, no status page, no public pricing page, and no public changelog. This profile captures the surface that is visible publicly: the platform/product pages, the integrations catalog, the cloud-platform page, the partner list, and the engineering blog.

## APIs Documented

The repo's [apis.yml](apis.yml) catalogs **10** API surfaces / platform pillars:

| Name | Surface |
|------|---------|
| Odessa Platform | Unified lease & loan management platform |
| Originations | Digital lease/loan origination + credit |
| Servicing | Invoicing, collections, portfolio |
| Remarketing | End-of-term, disposition, title, AP |
| Equipment Finance | Vertical packaging for equipment lessors |
| Auto Finance | Vertical packaging for auto lenders & captives |
| Developer Tools | Low-code, documented APIs, test automation |
| Integrations | Pre-built bureau / GL / eSign / KYC / CRM / tax / valuation |
| Odessa Cloud Platform | Managed SaaS on Microsoft Azure |
| Odessa AI | Agentic AI across the asset-finance lifecycle |

## Verticals

- **Equipment Finance** — banks, captive lessors, independent equipment lessors
- **Auto Finance** — captive finance, prime/near-prime auto, alternative structures (usage-based, subscription, fleet, as-a-service, fractional)

## Integrations (Public Catalog)

| Category | Named providers |
|----------|------------------|
| Credit Bureaus | FICO LiquidCredit, PayNet, D&B, Experian, Equifax, TransUnion |
| General Ledger | Microsoft Dynamics Great Plains, SAP, Quickbooks, Finacle, Oracle FLEXCUBE |
| Electronic Signature | DocuSign, Adobe Acrobat Sign |
| KYC / AML | LexisNexis, WorldCheck, SmartyStreets |
| CRM | Salesforce, Dynamics365 |
| Tax | Vertex, Taxware, PTMS |
| Dealer Portal | RouteOne, Dealertrack |
| Valuation | Kelly Blue Book, Black Book, ALG |

## Cloud & Compliance

- Hosting: **Microsoft Azure** (deep partnership)
- Deployment: SaaS, with single-tenant dedicated-environment option and customer-controlled release tracks
- Auth: SAML, SSO
- Certifications: **SOC 1, SOC 2, SOC 3, ISO 27001, ISO 9001**
- Status page: not publicly published

## Named Partners

Accenture, ConsultDisrupt, Assurant, J.D. Power ChromeData, BlackWinch, Capgemini, Acquis Insurance, TeamWill, Vertex.

## Notable Absences

- No public OpenAPI / AsyncAPI specification
- No public developer portal URL (no `docs.odessainc.com` or `developer.odessainc.com`)
- No public SDK or code sample repositories
- No populated GitHub organization (`github.com/odessainc` exists as a user with zero public repos)
- No public status page
- No public pricing page
- No public changelog or release notes
- No public RSS feed for the blog (email subscription only)

Because there is no public OpenAPI/SDK to reverse-engineer, this repo intentionally does **not** generate empty `openapi/`, `capabilities/`, `rules/`, `json-schema/`, `examples/`, `plans/`, `rate-limits/`, or `finops/` directories. Only `apis.yml` and `README.md` are produced — per the API Evangelist pipeline rules, placeholder artifacts are not committed.

## Pipeline

| Step | Status |
|------|--------|
| update-apis | Done — `apis.yml` with 10 APIs |
| profile-github-org | Done — `github.com/odessainc` is a user with zero public repos |
| discover-crds | N/A — not a Kubernetes-native platform |
| update-artifacts | Skipped — no public OpenAPI / AsyncAPI / JSON Schema / Postman discoverable |
| generate-operation-examples | Skipped — no OpenAPI |
| title-case-summaries | Skipped — no OpenAPI |
| generate-spectral-rules | Skipped — no OpenAPI |
| generate-naftiko-capabilities | Skipped — no OpenAPI |
| generate-json-schema | Skipped — no schemas |
| generate-json-structure | Skipped — no schemas |
| generate-json-ld | Skipped — no vocabulary backing |
| generate-examples | Skipped — no schemas |
| generate-vocabulary | Skipped — no public technical vocabulary |
| generate-plans | Skipped — no public pricing |
| generate-rate-limits | Skipped — no public rate-limit policy |
| generate-finops | Skipped — no public billing surface |
| update-apis (pass 2) | Done — no new artifacts to index |
| update-readme | Done — this file |

## Sources

- https://www.odessainc.com/
- https://www.odessainc.com/company/
- https://www.odessainc.com/our-technology/
- https://www.odessainc.com/lease-loan-management-platform/
- https://www.odessainc.com/lease-loan-origination-software/
- https://www.odessainc.com/lease-loan-servicing-software/
- https://www.odessainc.com/asset-remarketing-software/
- https://www.odessainc.com/equipment-finance-software/
- https://www.odessainc.com/auto-finance-software/
- https://www.odessainc.com/developer-tools/
- https://www.odessainc.com/integrations/
- https://www.odessainc.com/cloud-platform/
- https://www.odessainc.com/partners/
- https://www.odessainc.com/blog/
- https://www.odessainc.com/sitemap.xml
- https://github.com/odessainc
