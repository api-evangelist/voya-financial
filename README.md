# Voya Financial

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

Voya Financial (NYSE: VOYA) is a leading health, wealth, and investment company serving approximately 14.7 million individual, workplace, and institutional clients. Voya specializes in retirement plans, group employee benefits, health savings accounts (HSAs), and investment management. Their myVoyage platform integrates financial wellness tools to help participants plan, invest, and protect their financial futures.

**Website:** https://www.voya.com/  
**Type:** Fortune 500 Company  
**Tags:** Finance, Retirement, Benefits, Investment Management, Fortune 500

---

## About

Voya Financial helps individuals and institutions with their retirement planning, employee benefits management, and investment needs through three core service pillars: **Plan**, **Invest**, and **Protect**.

Key offerings include:
- **Retirement Plans:** 401(k), 403(b), 457, IRA, Roth IRA plans for employers and individuals
- **Employee Benefits:** Group life, disability, accident, and voluntary benefit programs
- **Health Accounts:** Health Savings Accounts (HSAs), FSAs, and HRAs
- **Investment Management:** Institutional and retail investment solutions

---

## APIs

Voya Financial does not currently offer a public developer API. Account connectivity is available through open banking aggregators:

| Resource | Type | URL |
|----------|------|-----|
| Plaid Integration | Integration | https://www.plaid.com/ |
| Investor Relations Portal | InvestorRelations | https://investors.voya.com/ |
| SEC EDGAR Filings (CIK: 0001535778) | DataFeed | https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001535778 |
| Yahoo Finance (VOYA) | MarketData | https://finance.yahoo.com/quote/VOYA/ |

---

## JSON Schema

- [voya-retirement-account-schema.json](json-schema/voya-retirement-account-schema.json) — Schema for Voya retirement plan accounts

---

## JSON-LD

- [voya-financial-context.jsonld](json-ld/voya-financial-context.jsonld) — Linked data context for Voya Financial

---

## Vocabulary

- [voya-financial-vocabulary.yml](vocabulary/voya-financial-vocabulary.yml) — Retirement, benefits, and investment domain vocabulary

---

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
