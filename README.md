# Weglot (weglot)

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

Weglot is a website translation platform that detects, translates, and displays multilingual content with no code changes. Its REST API at https://api.weglot.com powers machine and human translation of arrays of sentences between languages, exposes the catalog of supported languages, and is the same translation service used by the Weglot JavaScript, WordPress, Shopify, and CMS integrations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/weglot/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/weglot/refs/heads/main/apis.yml)

## Tags

- Translation
- Localization
- Internationalization
- Machine Translation
- Multilingual

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Weglot Translate API

Translates an array of sentences from a source language to a target language via POST /translate, authenticated with an api_key query parameter. Each word carries a WordType classification (text, value, placeholder, meta, title, link, image) and an optional BotType so machine and human translations are reused consistently across a site.

- **Human URL:** [https://developers.weglot.com/api/reference](https://developers.weglot.com/api/reference)
- **Base URL:** `https://api.weglot.com`

#### Tags

- Translation
- Machine Translation
- Localization

#### Properties

- [Documentation](https://developers.weglot.com/api/reference)
- [API Reference](https://developers.weglot.com/api/reference)
- [OpenAPI](openapi/weglot-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/weglot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weglot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Weglot Languages API

Public, unauthenticated endpoints that list every supported language (code, local name, English name) and check whether a given source/target language pair is supported for translation.

- **Human URL:** [https://developers.weglot.com/api/reference](https://developers.weglot.com/api/reference)
- **Base URL:** `https://api.weglot.com`

#### Tags

- Languages
- Internationalization
- Catalog

#### Properties

- [Documentation](https://developers.weglot.com/api/reference)
- [API Reference](https://developers.weglot.com/api/reference)
- [OpenAPI](openapi/weglot-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/weglot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weglot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Weglot Status API

A public, unauthenticated health-check endpoint that returns HTTP 200 when the Weglot translation API is operational.

- **Human URL:** [https://developers.weglot.com/api/reference](https://developers.weglot.com/api/reference)
- **Base URL:** `https://api.weglot.com`

#### Tags

- Status
- Health Check
- Monitoring

#### Properties

- [Documentation](https://developers.weglot.com/api/reference)
- [API Reference](https://developers.weglot.com/api/reference)
- [OpenAPI](openapi/weglot-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/weglot.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/weglot.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/weglot)
- [LinkedIn](https://www.linkedin.com/company/weglot)
- [Website](https://www.weglot.com)
- [Documentation](https://developers.weglot.com)
- [Plans](plans/weglot-plans-pricing.yml)
- [Rate Limits](rate-limits/weglot-rate-limits.yml)
- [Fin Ops](finops/weglot-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
