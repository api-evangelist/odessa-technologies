# Odessa Technologies

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
