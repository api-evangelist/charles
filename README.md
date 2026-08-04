# Charles University (charles)

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

Charles University (Univerzita Karlova), founded in 1348 in Prague, is the largest and oldest university in Czechia and is ranked #246 in the QS World University Rankings 2025. This repository catalogs the institution's public developer/API footprint as an [APIs.json](https://apisjson.org) provider profile. That footprint is limited: there is no central developer portal, but the university operates standards-based DSpace OAI-PMH repository endpoints and, via the UFAL institute's LINDAT/CLARIAH-CZ platform, documented public NLP REST web services.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/charles/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=charles-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Data, Repository, OAI-PMH, Natural Language Processing, Czechia, Europe

## APIs

- **CU Digital Repository OAI-PMH** — DSpace OAI-PMH 2.0 metadata harvesting for digitized collections. Docs: https://dspace.cuni.cz/
- **CU Research Publications Repository OAI-PMH** — DSpace OAI-PMH metadata harvesting for self-archived research outputs. Docs: https://publications.cuni.cz/page/about?locale-attribute=en
- **LINDAT Machine Translation API** — Public neural machine translation REST API (UFAL / LINDAT-CLARIAH-CZ). Docs: https://lindat.mff.cuni.cz/services/translation/docs
- **LINDAT NameTag API** — Public named-entity recognition / tokenization REST API (UFAL / LINDAT-CLARIAH-CZ). Docs: https://lindat.mff.cuni.cz/services/nametag/api-reference.php

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/charles-plans-pricing.yml](plans/charles-plans-pricing.yml)
- Rate Limits: [rate-limits/charles-rate-limits.yml](rate-limits/charles-rate-limits.yml)
- FinOps: [finops/charles-finops.yml](finops/charles-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.cuni.cz/UKEN-1.html
- GitHub: https://github.com/UKUK-Repository-Dept
- LinkedIn: https://www.linkedin.com/school/univerzita-karlova/
- Authentication (Shibboleth / eduID.cz SAML): https://uvt.cuni.cz/UVTEN-37.html

## Notes

All cataloged endpoints were probed on 2026-06-03 and returned HTTP 200 (the OAI-PMH endpoints returned valid OAI-PMH 2.0 Identify responses); no endpoints were fabricated. The LinkedIn page returns HTTP 999 (LinkedIn anti-bot) but the page exists. Student-facing systems — the Study Information System (SIS), course catalogue, and timetable — and single sign-on are gated behind eduID.cz / Shibboleth (SAML) and expose no documented public API. The DSpace integration tooling on the UKUK-Repository-Dept GitHub org is internal-facing.

## Maintainers

- Kin Lane — kin@apievangelist.com
