# LinkAGI

> Operator-submitted candidate: a China-facing AI API relay with OpenAI-compatible access and model-specific billing.

**[Official Website](https://api.linktoagi.com/)** · **[Pricing](https://api.linktoagi.com/pricing)** · **[Docs](https://docs.linktoagi.com/)** · **[OpenAPI](https://docs.linktoagi.com/openapi/linkagi.openapi.json)**

---

## Quick Facts | 基本信息

| Field | Value |
|-------|-------|
| **Submission status** | Candidate awaiting independent review; operator submission |
| **Public registration** | Public signup is available at `/sign-up`; the service was publicly documented and listed before this submission |
| **Base Region** | China-facing |
| **Target Users** | Developers, Claude Code/Codex users, and applications using OpenAI-compatible clients |
| **Site Language** | Chinese |
| **API Compatible With** | OpenAI-compatible; public docs also describe Anthropic-style and Gemini-style routes, with client/model limits to be checked per model |
| **Claude Code Support** | ⚠️ Model and group dependent; consult current docs and pricing |
| **Base URL** | `https://api.linktoagi.com/v1` |
| **Last Verified** | 2026-09-22 |

## Pricing | 定价

The public pricing page and machine-readable pricing endpoint provide the current model, group, context-tier and cache rules. The following is a dated public snapshot, in CNY per 1M tokens for the short-context tier (`len <= 272000`); it is not a promise that prices remain fixed:

| Model | Group | Input | Output |
|-------|-------|------:|-------:|
| `gpt-6-astra` | Codex · Plus pool | ¥2.00 | ¥10.00 |
| `gpt-5.6-terra` | Codex · Sale pool | ¥0.30 | ¥1.80 |
| `gpt-5.6-sol` | Codex · Sale pool | ¥0.75 | ¥4.50 |

Prices vary by model group, context tier and cache usage. Verify the live table before adding balance. No automatic signup credit or fixed trial amount is claimed here; users can contact support to ask about a trial arrangement.

## Supported Models and Routes

- **OpenAI-family catalog:** GPT and Codex entries, with OpenAI-compatible routes documented publicly.
- **Anthropic-family catalog:** Claude Sonnet and Opus entries; the current model table lists Anthropic and OpenAI endpoint types for several models.
- **Other catalog entries:** Gemini, DeepSeek, Grok and GLM are listed in the public model catalog.
- Exact model IDs, groups and endpoint types change over time and should be read from the live pricing page and OpenAPI document.

The unauthenticated public probe of `GET /v1/models` returned HTTP 401 on 2026-09-22, with an invalid-token response. This confirms an authenticated API route exists; it is not evidence that a request with a valid key succeeds. No API key is included in this submission.

## Payment and Account Features

- Public service pages describe Alipay and WeChat payment.
- Users can create project keys, select a model group, and inspect per-request token usage and charges in the console.
- Trial credit is handled by customer support when arranged; signup does not automatically add a fixed amount.
- Terms, privacy and refund information are linked from the public site.

## Pros & Cons | 优缺点

**Pros**

- Public pricing, documentation and OpenAPI links.
- RMB billing and domestic payment options.
- Project keys and per-request usage logs.

**Cons**

- Mixed account-pool and reverse-channel groups; upstream identity and route quality should be checked for the exact model.
- No independent uptime, latency or model-authenticity benchmark is supplied with this submission.
- The public endpoint requires an API key, so the directory's scheduled probe must perform its own authenticated verification if the maintainers choose to test it.

## Review Score and Benchmark Data

Pending independent review. No self-assigned score, uptime percentage, latency result, customer count or paid-usage figure is supplied. The operator does not ask the directory to mark the gateway as verified based on this self-submitted information.

## User Reviews

No independent customer review is supplied with this submission.

## Changelog

- `2026-09-22` — Initial operator-submitted candidate.

---

**Conflict of interest disclosure**: This entry was submitted by the LinkAGI operator. It is a request for independent review, not a user testimonial or an endorsement by the directory.
