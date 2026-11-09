# TokenDos

> Supplier-based AI API marketplace with public node samples and a documented Agent workflow for sharing member sessions.

**[Official Website](https://www.tokendos.com)** · **[Pricing](https://www.tokendos.com/tokendos-pricing)** · **[Market](https://www.tokendos.com/tokendos-market)** · **[Docs](https://www.tokendos.com/tokendos-docs)**

**Conflict of interest disclosure | 利益相关声明:** This entry is submitted by a TokenDos operator, not an independent reviewer. Public-source observations below do not establish successful paid calls, continuous uptime, model identity or completion of a member-sharing transaction. Submitted as `needs_review` for maintainer assessment.

## Quick Facts | 基本信息

| Field | Value |
|-------|-------|
| **Founded** | 2026-06, as reported in the operator's public terms; domain age and continuous operating history were not independently verified |
| **Base Region** | China-facing service; individual operator, no company entity according to public terms |
| **Target Users** | Developers comparing supplier quotes; users supplying or consuming member-session capacity |
| **Site Language** | Chinese UI with language options; localization coverage not audited |
| **API Compatible With** | OpenAI `/v1` and Anthropic `/anthropic`, documented by the operator; compatibility not exercised in this submission |
| **Claude Code Support** | Documented; no authenticated Claude Code call made for this submission |
| **API Base** | `https://api.tokendos.com` |
| **Registration** | [Public route](https://www.tokendos.com/register) returned HTTP 200 HTML; account creation was not completed |
| **Support** | [Support page](https://www.tokendos.com/support) and `business@tokendos.com`, as disclosed in terms; response times not measured |
| **Last Verified** | 2026-10-09, public pages and unauthenticated endpoints only |

## Pricing | 定价

The [public price snapshot](https://www.tokendos.com/api/tokendos/public/transit-snapshot) identifies the billing currency as USD and provides `price_usd_per_m` fields. The following are operator-published marketplace minima captured at **2026-10-09 14:58 UTC**, in **USD per 1M tokens**. Input, output and cache minima are aggregated fields and may come from different suppliers; they are not a guaranteed combined quote for one node or a completed request.

| Model identifier in the catalog | Input | Output | Cache read |
|-------|-------:|-------:|-------:|
| `claude-opus-4-6` | $0.0225 | $0.1125 | $0.00225 |
| `gpt-5.5` | $0.0372197 | $0.223318 | $0.003722 |
| `gemini-3.1-pro-preview` | $0.0595954 | $0.3575722 | $0.0059595 |

Prices change with supplier availability. Confirm the selected node's input/output/cache rates, long-context rules, routing, retry treatment and actual bill before relying on a minimum. Catalog model identifiers are supplier labels, not independent authentication of the upstream model.

The [public terms](https://www.tokendos.com/api/tokendos/public/terms) disclose a $1 minimum top-up, 1:1 recharge-to-balance conversion and an optional 10% voucher on the first top-up. Activity eligibility and voucher restrictions need checking at checkout. No fixed free tier is claimed here. Refund requests are handled by support after review; an unconditional refund is not promised.

The snapshot's official-price references and `rate_vs_official` use an operator reference and currency-conversion basis. This entry does not use those fields to derive a cross-provider percentage discount.

## Supported Models and Sourcing | 模型与来源

The public catalog contains GPT, Claude, Gemini and other model labels. Available nodes and supported features vary; catalog presence is not a successful authenticated call.

Public terms describe a mixed supply of supplier-owned official API keys, subscription-account-to-API/OAuth routes and local hosted nodes. A named model or protocol does not establish a direct first-party route. Users need to select and evaluate the actual supplier and channel. No proprietary-engine certification or direct upstream partnership is asserted here.

## Features and Pros | 功能与优势

- **Cost choice:** multiple suppliers publish quotes; small top-ups and conditional activities allow users to compare task costs without committing to a large balance. These mechanisms do not establish the lowest market price.
- **Observable node samples:** [public pelican records](https://www.tokendos.com/api/tokendos/pelican/latest?modelName=claude-opus-4-6) include outputs, prompt, time, latency and token counts. The endpoint returned node records on 2026-10-09. They help inspect that particular capability sample; they do not authenticate model identity or measure general task reliability.
- **Member-session sharing:** the SESSION documentation describes both parties installing TokenDos Agent, suppliers registering their locally logged-in Codex/Claude client and setting quotes, and consumer sessions executing on the supplier's machine. Users can participate as suppliers as well as consumers. This is a documented workflow, not a completed transaction in this submission or a claim of market exclusivity.

## Cons and Limits | 缺点与限制

- Mixed channel sources require users to evaluate provider, protocol, features and data handling themselves.
- SESSION supply depends on an online supplier, Agent, available seat and member quota. At **2026-10-09 14:58 UTC**, the public [CODEX_SESSION query](https://www.tokendos.com/api/tokendos/provider/marketplace/page?page=1&size=4&protocol=CODEX_SESSION) and [CLAUDE_SESSION query](https://www.tokendos.com/api/tokendos/provider/marketplace/page?page=1&size=4&protocol=CLAUDE_SESSION) both returned `total: 0` with empty lists. That snapshot does not demonstrate available tradeable SESSION supply.
- SESSION docs say suppliers may access remotely executed code or conversations; the platform temporarily retains recent request/response data for troubleshooting. Local retention of login credentials does not make consumer content inaccessible to the supplier.
- Public terms state a default account concurrency of **1** and **no invoices**. Parallel workloads and procurement needs should account for these limits.
- Payment availability should be checked in checkout. The public refund terms mention PayPal, but no payment, settlement or withdrawal was exercised for this submission.

## Review Score and Benchmark Data | 评分与实测

**Not assigned.** No independent latency, TTFT, throughput, uptime, support or comparative quality score is supplied. No paid model request, member-session transaction, supplier settlement or withdrawal was made for this submission.

At **2026-10-09 14:57 UTC**, unauthenticated `GET https://api.tokendos.com/v1/models` returned HTTP **401** JSON with `code: missing_authorization` and a message requiring a Bearer key. This confirms an accessible authentication response, not successful generation. The API root returned 404; the website's `/v1/models` returned HTML. The repository's current same-host probe therefore needs manual assessment for this service. No generated leaderboard, history, uptime or verification score is hand-edited in this contribution.

## User Reviews | 用户评价

No independently verified customer reviews are supplied with this entry.

## Changelog | 更新日志

- `2026-10-09` — Operator-submitted candidate with dated public pricing, separate-host probe evidence, upstream disclosure and member-sharing limits; pending maintainer review.
