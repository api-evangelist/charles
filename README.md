# Charles University (charles)

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
