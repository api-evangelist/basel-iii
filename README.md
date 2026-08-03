# Basel III

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

Basel III is a comprehensive global regulatory framework developed by the Basel Committee on Banking Supervision (BCBS) in response to the 2007-2009 financial crisis. It strengthens bank capital requirements by requiring higher quality and quantity of capital, introduces new liquidity standards (LCR and NSFR), adds a leverage ratio backstop, and includes countercyclical capital buffers and G-SIB surcharges. The final Basel III package (sometimes called Basel IV) addresses output floor and credit risk model constraints introduced in 2017.

## Governance

| Attribute | Detail |
|---|---|
| Governing Body | Basel Committee on Banking Supervision (BCBS) |
| Oversight | Group of Central Bank Governors and Heads of Supervision (GHOS) |
| Secretariat | Bank for International Settlements (BIS), Basel, Switzerland |
| Membership | 45 institutions from 28 jurisdictions |
| Implementation Deadline | January 1, 2028 (Basel IV output floor) |

## Key Specifications

| Standard | Minimum | Description |
|---|---|---|
| CET1 Capital Ratio | 4.5% | Highest quality capital over risk-weighted assets |
| Tier 1 Capital Ratio | 6.0% | CET1 plus AT1 capital |
| Total Capital Ratio | 8.0% | Tier 1 plus Tier 2 capital |
| Capital Conservation Buffer | 2.5% CET1 | Buffer above minimums to absorb losses |
| Leverage Ratio | 3.0% | Tier 1 capital over total exposures |
| LCR | 100% | 30-day liquidity coverage |
| NSFR | 100% | 1-year stable funding ratio |
| Output Floor | 72.5% | Minimum ratio of IRB to SA RWA |

## Key Documents

- [Basel III Framework (BIS)](https://www.bis.org/bcbs/basel3.htm)
- [Basel III Final Package - December 2017](https://www.bis.org/bcbs/publ/d424.htm)
- [Liquidity Coverage Ratio - January 2013](https://www.bis.org/publ/bcbs238.htm)
- [Net Stable Funding Ratio - October 2014](https://www.bis.org/publ/bcbs295.htm)

## National Implementation

- [EU — CRD IV/V and CRR/CRR2](https://www.eba.europa.eu/regulation-and-policy/own-funds-and-eligible-liabilities)
- [US — Federal Reserve Basel Rules](https://www.federalreserve.gov/supervisionreg/Basel.htm)
- [UK — PRA CRR Implementation](https://www.pra.boe.co.uk/pages/policy/crr)

## Vocabulary

See [vocabulary/basel-iii-vocabulary.yaml](vocabulary/basel-iii-vocabulary.yaml) for authoritative definitions of Basel III terms.

## JSON-LD Context

See [json-ld/basel-iii-context.jsonld](json-ld/basel-iii-context.jsonld) for linked data context mapping Basel III concepts.

## Examples

See [examples/basel-iii-capital-requirements-example.json](examples/basel-iii-capital-requirements-example.json) for a structured representation of Basel III capital requirements.

## Maintainers

- Kin Lane (kin@apievangelist.com)
