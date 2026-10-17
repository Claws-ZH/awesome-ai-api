# YonShoreAPI

> Operator-submitted candidate: an AI API relay for developers using GPT- and Claude-family model endpoints.

**[Website](https://api.yonshore.com)** · **[Public pricing](https://api.yonshore.com/pricing)** · **[Machine-readable per-model pricing](https://api.yonshore.com/api/pricing)** · **[Quickstart](https://github.com/jerrynullmmo/yonshoreapi-quickstart)** · **[Corresponding source](https://api.yonshore.com/source/)**

## Quick Facts

| Field | Value |
|---|---|
| Submission status | Candidate awaiting independent review; operator submission |
| Public registration opened | 2026-08-13, according to the attached operator record |
| Target users | Developers integrating language models and coding workflows |
| Site language | Chinese |
| Operator | Jerry, personal website operator |
| Regional availability | Mainland China access, registration and API calls are currently unsupported |
| Base URL | `https://api.yonshore.com/v1` |
| API formats | Per-model formats: Chat Completions, Responses or Anthropic Messages; consult the live catalogue |
| Underlying software | Customized New API (AGPL-3.0-only); corresponding-source releases published |
| Contact for this submission | @jerrynullmmo in the associated GitHub pull request |
| Public pages checked | 2026-10-17 |

## Pricing

The [public pricing page](https://api.yonshore.com/pricing) and [pricing JSON](https://api.yonshore.com/api/pricing) provide per-model rates, billing expressions, supported endpoint formats and eligible groups. Rates vary with model, group and, where applicable, context tier and cache usage. Consult the current table when selecting a model.

Group multipliers are not a claim about a universal cash discount versus a model vendor's official price. The public about page states a minimum top-up of CNY 1; no promotional-credit availability is claimed in this entry.

## Model Catalog and API Formats

The public catalog lists GPT- and Claude-family request identifiers. Use the exact identifier and supported endpoint shown in the live pricing table.

- `gpt-5.6-sol`, `gpt-5.6-terra` and `gpt-6-astra`: Responses format, `POST /v1/responses`.
- `gpt-6-sol` and `gpt-6.1-sol`: Chat Completions, `POST /v1/chat/completions`.
- Claude-family catalog entries: Anthropic Messages, `POST /v1/messages`, and OpenAI-compatible chat, `POST /v1/chat/completions`.
- A public [Postman request example](https://www.postman.com/navigation-cosmonaut-39149305-s-team/yonshoreapi-quickstart/http-request/30504202-f573b1b2-c769-4fb0-90c7-f813181feb34) and the GitHub quickstart are available.

Catalog identifiers are operator declarations; this submission does not independently attest upstream model identity, routing origin, or comprehensive frontier-model coverage. Detailed upstream sourcing is not disclosed in these materials.

## Payment, Invoicing and Refunds

The public [about page](https://api.yonshore.com/about) states the following; these are operator-reported policies, not independently tested transactions:

- WeChat top-up starts at CNY 1. USDT (TRC20) orders start at 1 site credit, with the payable USDT amount shown on the order; this does not mean a 1 USDT minimum.
- Invoicing is available for amounts of CNY 500 or more, with a stated 6% tax rate. This does not state an additional 6% service charge.
- Refund applications cover unused, actual recharge funds within 30 days. Consumed amounts and gift credits are excluded; the applicant bears applicable USDT transfer fees.
- The [support center](https://api.yonshore.com/support) accepts private tickets with images and links to the user's own recharge orders or usage records.
- The current referral batch provides permanent 5% cash commission on referred users' settled paid usage, with terms locked when the referral relationship is established at registration. Gift-credit usage and unsettled usage are excluded; refunds and reversals reduce corresponding commission. Withdrawals require manual review and payment. Full terms are in the [site announcement](https://api.yonshore.com/).
- Specific invoice subtype and issuance lead time are not specified here.

## Operating History and Source Availability

The operator-provided [historical evidence screenshot](./yonshoreapi-history.png) records:

| Date | Recorded milestone |
|---|---|
| 2026-07-24 | Invitation-only deployment on `api.yonshore.com` |
| 2026-08-05 | Four successful Claude-channel requests on the historical `newapi.yonshore.com` host |
| 2026-08-13 | Public email registration enabled on the main site |

Public registration predates this submission by 37 days. These dated milestones document earlier development and operation; they do not establish uninterrupted uptime, current customer numbers, or 30 days of paid usage.

The [public source index](https://api.yonshore.com/source/) identifies the New API base and publishes Yonshore-specific versions for monitoring, wallet/recharge integration, registration/email handling and error redaction. This is offered as evidence of maintained customization; whether it meets this directory's independent-operation criterion remains for maintainers to assess.

## Review Score and Benchmark Data

Pending independent review. No self-assigned score, latency benchmark, 30-day uptime percentage, customer count or paid-usage figure is supplied. No public continuous monitoring page is submitted.

The candidate URL is added to `data/candidates.txt` so the repository's existing scheduled probe can produce its own observations if maintainers accept it. Probe results and generated rankings are not pre-populated by the operator.

## User Reviews

No independent customer review is supplied with this submission.

## Changelog

- 2026-10-17: Corrected model-specific endpoints, personal-operator disclosure, regional availability, payment/refund wording and current support/referral information from public site pages.

- 2026-09-19: Initial operator-submitted candidate and operating-history attachment.

## Conflict of Interest

Submitted by the YonShoreAPI operator (@jerrynullmmo). This is a request for independent inclusion review, not a user testimonial or a claim of endorsement.
