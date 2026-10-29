# Charles University

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Charles University (Univerzita Karlova), founded in 1348 in Prague, is the largest and oldest university in Czechia. Unusually for a university, a substantial part of its programmable footprint is genuinely institution-operated rather than a vendor contract running under its name. The Institute of Formal and Applied Linguistics (UFAL) in the Faculty of Mathematics and Physics runs the LINDAT/CLARIAH-CZ research infrastructure and publishes five documented, keyless, production REST APIs on its own host — machine translation, UDPipe (tokenization, tagging, lemmatization and dependency parsing across 961 Universal Dependencies models), NameTag (named-entity recognition), MorphoDiTa (morphological analysis and generation) and Korektor (Czech spellchecking and diacritics). Three DSpace repositories on university-owned infrastructure expose OAI-PMH 2.0, and the LINDAT repository additionally exposes a DSpace 7 HAL REST API. The university operates its own Shibboleth SAML identity provider at idp.cuni.cz, registered in the Czech national federation eduID.cz, and is a DataCite registrant (CUNI) and Crossref member. What it does NOT have is a central developer portal, an open-data portal, or any public API over the Study Information System (SIS) or student records — those are gated behind eduID/Shibboleth. Library discovery (UKAZ) is an Ex Libris Primo tenancy and cuni.figshare.com is a Figshare tenancy; both are real institutional relationships whose contracts belong to the vendors.

**Areas:** University · Higher Education · Education · Research · Czechia · Europe · Language Technology · Natural Language Processing · Machine Translation · Research Repository · Identity Federation · OAI-PMH

## Charles University on APIs.io

Everything profiled for Charles University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/charles/](https://apis.io/providers/charles/)** — or go straight to one of the APIs or properties below.

### APIs (17)

- [LINDAT Translation Languages API](https://apis.io/apis/charles/charles-languages-api/) — Source and target language operations of the LINDAT Machine Translation API, operated by the Institute of Formal and Applied Linguistics (UFAL) at Charles…
- [LINDAT Translation Models API](https://apis.io/apis/charles/charles-models-api/) — Translation-model operations of the LINDAT Machine Translation API, operated by UFAL at Charles University. Models are neural MT systems such as CUBBITT,…
- [LINDAT Translation Root API](https://apis.io/apis/charles/charles-root-api/) — Root navigation resource of the LINDAT Machine Translation API, returning HAL links to the languages and models collections.
- [LINDAT UDPipe API](https://apis.io/apis/charles/lindat-udpipe/) — Public keyless REST API for tokenization, part-of-speech tagging, lemmatization and dependency parsing of CoNLL-U data, operated by UFAL at Charles…
- [LINDAT NameTag API](https://apis.io/apis/charles/lindat-nametag/) — Public keyless REST API for named-entity recognition and tokenization (NameTag 3) operated by UFAL at Charles University via LINDAT/CLARIAH-CZ. The OpenAPI…
- [LINDAT MorphoDiTa API](https://apis.io/apis/charles/lindat-morphodita/) — Public keyless REST API for morphological analysis, morphological generation, part-of-speech tagging and tokenization, principally for Czech, operated by…
- [LINDAT Korektor API](https://apis.io/apis/charles/lindat-korektor/) — Public keyless REST API for Czech statistical spellchecking, diacritics generation and ranked correction suggestions, operated by UFAL at Charles…
- [CU Digital Repository OAI-PMH](https://apis.io/apis/charles/digital-repository-oai/) — The Charles University Digital Repository (Digitalni repozitar UK), a DSpace instance running on university-owned infrastructure (dspace.cuni.cz resolves to…
- [CU Research Publications Repository OAI-PMH](https://apis.io/apis/charles/publications-repository-oai/) — The Charles University Research Publications Repository (Repozitar publikacni cinnosti UK), a DSpace instance on university-owned infrastructure, exposes a…
- [LINDAT/CLARIAH-CZ Repository OAI-PMH](https://apis.io/apis/charles/lindat-repository-oai/) — OAI-PMH 2.0 endpoint of the LINDAT/CLARIAH-CZ digital library operated by UFAL at Charles University, holding language resources and tools back to 2006. The…
- [LINDAT/CLARIAH-CZ Repository REST API](https://apis.io/apis/charles/lindat-repository-rest/) — DSpace 7 HAL+JSON REST API of the LINDAT/CLARIAH-CZ digital library, served from UFAL's own host at Charles University. The root discovery document returns…
- [Charles University Shibboleth Identity Provider](https://apis.io/apis/charles/identity-provider/) — Charles University operates its own Shibboleth SAML 2.0 identity provider. Metadata is served at idp.cuni.cz as application/xml with entityID…
- [DataCite Registrant — Charles University (CUNI)](https://apis.io/apis/charles/datacite-membership/) — Charles University is a DataCite registrant under provider symbol CUNI, memberType consortium_organization, country CZ, linked to ROR…
- [Crossref Membership — Charles University](https://apis.io/apis/charles/crossref-membership/) — Charles University holds two Crossref memberships: 5727, "Charles University in Prague, Karolinum Press" (the university press), and 55007, the Institute of…
- [ROR Registration — Charles University](https://apis.io/apis/charles/ror-registration/) — Charles University is registered in the Research Organization Registry as https://ror.org/024d6js02, located in Czechia. Recorded as a registry membership;…
- [UKAZ Library Discovery — Ex Libris Primo VE tenancy](https://apis.io/apis/charles/library-discovery-primo/) — UKAZ, the Charles University library discovery service, is an Ex Libris Primo VE tenancy. ukaz.cuni.cz redirects to cuni.primo.exlibrisgroup.com with…
- [Charles University Figshare — Figshare tenancy](https://apis.io/apis/charles/figshare-repository/) — cuni.figshare.com is a Figshare tenancy for Charles University; DNS resolves it by CNAME to figshare.com. The host answered an AWS WAF bot challenge (HTTP…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Charles Agentic Access](https://apis.io/agentic-access/charles/charles-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [LanguageResource](https://apis.io/schemas/charles/charles-language/)
- [ModelResource](https://apis.io/schemas/charles/charles-model/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Charles Language Structure](https://apis.io/json-structure/charles/charles-language-structure/)
- [Charles Model Structure](https://apis.io/json-structure/charles/charles-model-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Charles Context](https://apis.io/jsonld/charles/charles-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Charles University LINDAT Translation Vocabulary](https://apis.io/vocabularies/charles/charles-vocabulary/)

#### Examples (8)

Example requests and responses.

- [Charles Get Language Collection Example](https://apis.io/examples/charles/charles-get-language-collection-example/)
- [Charles Get Model Collection Example](https://apis.io/examples/charles/charles-get-model-collection-example/)
- [Charles Korektor Suggestions Example](https://apis.io/examples/charles/charles-korektor-suggestions-example/)
- [Charles Morphodita Tag Example](https://apis.io/examples/charles/charles-morphodita-tag-example/)
- [Charles Nametag Models Example](https://apis.io/examples/charles/charles-nametag-models-example/)
- [Charles Nametag Recognize Example](https://apis.io/examples/charles/charles-nametag-recognize-example/)
- [Charles Post Model Item Example](https://apis.io/examples/charles/charles-post-model-item-example/)
- [Charles Udpipe Process Example](https://apis.io/examples/charles/charles-udpipe-process-example/)

#### Collections (3)

Postman and Open Collection request collections.

- [LINDAT Translation languages API](https://apis.io/collections/charles/open-charles-languages-api/)
- [LINDAT Translation languages models API](https://apis.io/collections/charles/open-charles-models-api/)
- [LINDAT Translation languages root API](https://apis.io/collections/charles/open-charles-root-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Charles University — jsonschema rules](https://apis.io/rules/charles/charles-jsonschema-spectral-rules/)
- [Charles University API Rules](https://apis.io/rules/charles/charles-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Charles Domain Security](https://apis.io/security/charles/charles-domain-security/)
- [Charles Vulnerability Disclosure](https://apis.io/security/charles/charles-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Charles Plans Pricing](https://apis.io/plans/charles/charles-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Charles Rate Limits](https://apis.io/rate-limits/charles/charles-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Charles Finops](https://apis.io/finops/charles/charles-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.cuni.cz/UKEN-1.html)
- [Documentation](https://lindat.mff.cuni.cz/en/services)
- [API reference](https://lindat.mff.cuni.cz/services/udpipe/api-reference.php)
- [Support](https://lindat.mff.cuni.cz/user_feedback)
- [Terms of service](https://lindat.mff.cuni.cz/en/terms-of-use)
- [GitHub](https://github.com/UKUK-Repository-Dept)

## API Evangelist rating

**Kin Score 32.9** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 82.1 |
| Contract quality | 48.6 |
| Contract governance | 9.8 |
| Operational transparency | 7.9 |
| Developer ergonomics | 33.3 |
| Access clarity | 15.8 |

**Agent readiness 20.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 26.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/charles/](https://apis.io/providers/charles/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Charles University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/charles/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
