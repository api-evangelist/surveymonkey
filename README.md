# SurveyMonkey (surveymonkey)

SurveyMonkey is a leading surveys and feedback platform. The SurveyMonkey API v3 is a REST/JSON API covering surveys, pages, questions, collectors, contacts, responses, webhooks, users, teams, groups and benchmarks. Authenticated with OAuth 2.0 (3-step flow) and scope-based permissions.

**APIs.json:** [apis.yml](apis.yml)

## APIs
- **API v3** — `https://api.surveymonkey.com/v3` — surveys, responses, collectors, contacts, webhooks, users, teams. OAuth 2.0; some scopes require paid plans. [Docs](https://api.surveymonkey.com/v3/docs).

## OpenAPI
SurveyMonkey does not publish a downloadable OpenAPI/Swagger spec at a stable public URL as of 2026-05-08; pipeline did not retrieve a spec into `openapi/`.

## Tags
Surveys, Market Research, Feedback, NPS, Forms, OAuth

## Common Properties
- [Website](https://www.surveymonkey.com/) · [API Docs](https://api.surveymonkey.com/v3/docs) · [Pricing](https://www.surveymonkey.com/pricing/)
- [GitHub](https://github.com/SurveyMonkey) · [Status](https://status.surveymonkey.com/)
- [Plans](plans/surveymonkey-plans-pricing.yml) — reconciled
- [Rate Limits](rate-limits/surveymonkey-rate-limits.yml) — reconciled
- [FinOps](finops/surveymonkey-finops.yml) — reconciled, FOCUS-aligned

## Plans (reconciled)
- **Team Advantage** — $30/user/mo (annual, min 3 users); 50K responses/year.
- **Team Premier** — $92/user/mo (annual, min 3 users); 100K responses/year.
- **Enterprise** — custom; flexible response limits.
- **Individual plans** — Standard / Advantage / Premier.
- **Overage** — $0.15/response above bundle.

## Rate Limits (reconciled)
- Draft / Private apps: 120 req/min, daily floor 500/day (raisable).
- Public apps (App Directory): up to 500,000 req/day.
- 429 responses; X-Ratelimit-* headers expose remaining capacity.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Maintainers
- **Kin Lane** — kin@apievangelist.com
