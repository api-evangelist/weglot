# Weglot (weglot)

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
