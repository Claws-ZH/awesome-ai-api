# TeapotRouter

> Hosted dual-protocol gateway for coding agents: one API key serves an Anthropic Messages endpoint (Claude Code) and an OpenAI-compatible endpoint (Codex CLI).

**[Official Website](https://teapotrouter.com)** · **[Pricing](https://teapotrouter.com/api/pricing)** · **[Config Templates](https://github.com/teapot-router/teapot-router-config)**

---

## Quick Facts | 基本信息

| Field | Value |
|-------|-------|
| **Founded** | 2026-09 |
| **Base Region** | Global |
| **Target Users** | Developers (coding agents: Claude Code / Codex CLI) |
| **Site Language** | Both (7 languages: en/zh/ja/ko/es/pt/fr) |
| **API Compatible With** | Both (Anthropic Messages + OpenAI-compatible) |
| **Claude Code Support** | ✅ |
| **Codex CLI Support** | ✅ |
| **Last Verified** | 2026-11-16 |

*Operator-submitted entry (2026-11-16). I operate this service; fields below marked "pending" are left for the maintainer pipeline to measure rather than self-reported.*

## Pricing | 定价

*Prices in USD per 1M tokens. Full machine-readable list (10 models): [`/api/pricing`](https://teapotrouter.com/api/pricing) — JSON, refreshable.*

| Model | Input | Output | Official | Diff |
|-------|-------|--------|----------|------|
| claude-sonnet-5-5 | $0.68 | $3.40 | — | *for maintainer methodology* |
| gpt-6-astra | $0.65 | $3.25 | — | *for maintainer methodology* |

- Minimum top-up $3 · prepaid pay-as-you-go · credit never expires · refunds on remaining balance.
- New accounts receive 40,000 signup credits.

## Supported Models | 支持模型

- **Anthropic-protocol group**: claude-sonnet-5-5, claude-sonnet-5, claude-opus-5-5, claude-opus-5, claude-fable-5, claude-fable-5-2, claude-haiku-4-5
- **OpenAI-protocol group**: gpt-6.1-sol, gpt-6.1-terra, gpt-6-astra

## Payment Methods | 支付方式

- 💳 Credit card (Stripe)

## Features | 特色功能

- One key, two protocol endpoints (Anthropic Messages + OpenAI-compatible) — Claude Code and Codex CLI work on the same account and balance
- Per-request ledger: cost, tokens, latency for every call in the console
- No-signup Model Lab to evaluate models before paying: https://teapotrouter.com/en/demo/model-lab
- Machine-readable pricing endpoint (`/api/pricing`)

## Pros & Cons | 优缺点

**Pros | 优势**
- Dual protocol on one key and one balance
- Transparent, machine-verifiable pricing
- Balance never expires; refundable on remaining balance

**Cons | 劣势**
- Young service (operating since 2026-09) — short public track record
- Card payments only (no Alipay/WeChat/crypto yet)
- Small model catalog (10 models at submission)

## Review Score | 评分

| Dimension | Score (/10) | Note |
|-----------|-------------|------|
| **Overall** | *pending* | Operator-submitted — scores left to maintainer verification |

## Benchmark Data | 基准数据

Not yet measured. Baseline probes from this submission (2026-11-16): site root HTTP 308 (locale redirect) → 200; `/api/pricing` 200; `https://api.teapotrouter.com/v1/models` 401 without a key. A directory-verification key (balance capped at $0.28) is available in the PR body for the maintainer probe pipeline.

## User Reviews | 用户评价

None collected yet — service is new. Will link community threads as they appear.
