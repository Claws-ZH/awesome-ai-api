# Zerouter

> Pay-per-token AI API gateway for Claude, GPT, Gemini, Grok and Kimi, with OpenAI- and Anthropic-compatible endpoints for Claude Code, Codex and Cursor.

**[Official Website](https://www.zerouter.ai)** · **[Pricing](https://www.zerouter.ai/pricing)** · **[Docs](https://www.zerouter.ai/docs)** · **[Models](https://www.zerouter.ai/models)**

---

## Quick Facts | 基本信息

| Field | Value |
|-------|-------|
| **Founded** | 2026-08 (domain registered 2026-08-28) |
| **Base Region** | Global |
| **Target Users** | Developers using Claude Code / Codex / Cursor |
| **Site Language** | EN |
| **API Compatible With** | Both (OpenAI `/v1/chat/completions`, `/v1/responses`; Anthropic `/v1/messages`) |
| **Claude Code Support** | ✅ (`ANTHROPIC_BASE_URL=https://api.zerouter.ai`) |
| **Last Verified** | 2026-10-18 |

## Pricing | 定价

*USD per 1M tokens, copied from https://www.zerouter.ai/pricing on 2026-10-18. The page lists official prices next to each model and refreshes hourly.*

| Model | Input | Output | Official | Diff |
|-------|-------|--------|----------|------|
| Claude Opus 5.5 | $1.16 | $5.81 | $4 / $20 | -71% |
| Claude Sonnet 5.5 | $0.46 | $2.32 | $2 / $10 | -77% |
| Claude Haiku 5.5 | $0.023 | $0.12 | $0.10 / $0.50 | -77% |
| GPT-5.5 | $0.37 | $2.24 | $5 / $30 | -93% |
| GPT-6.1 Sol | $0.37 | $2.24 | $2 / $10 | -78% |
| Gemini 3.8 Flash | $0.11 | $0.56 | $0.75 / $3.75 | -85% |
| Grok 4.6 | $0.30 | $0.90 | $2 / $6 | -85% |
| Kimi K3 | $1.49 | $7.44 | $3 / $15 | -50% |

Pay as you go from a prepaid USD balance; no monthly plan. Cache-read prices are also listed on the pricing page.

## Supported Models | 支持模型

- **Anthropic**: Claude Opus 5.5, Opus 5, Fable 5.1, Fable 5, Sonnet 5.5, Sonnet 5, Haiku 5.5
- **OpenAI**: GPT-6.1 Sol, GPT-6 Astra, GPT-6 Sol, GPT-6 Luna, GPT-5.6 Sol, GPT-5.6 Terra, GPT-5.5
- **Google**: Gemini 4 Argon, Gemini 3.8 Flash, Gemini 3.7 Flash
- **xAI**: Grok 4.7, Grok 4.6, Grok 4.5
- **Moonshot**: Kimi K3

## Upstream disclosure | 上游来源

Requests are served by the vendors' own endpoints: either vendor API accounts, or Claude / Codex subscription capacity that providers host through [provider.zerouter.ai](https://provider.zerouter.ai) (providers keep ~80% of what their capacity earns). The model name you request is the model that is called; no substitution.

## Payment Methods | 支付方式

- ₿ Crypto (no processing fee on crypto channels, per the console)
- Other channels: see the Recharge page in the console

## Features | 特色功能

- One key for Claude, GPT, Gemini, Grok and Kimi; change only base URL + key
- Per-call usage log with input / cache / output token billing
- Integration guides for Claude Code, Codex CLI, Cursor and the OpenAI SDK
- Provider side: host idle Claude / Codex subscription quota and earn a share

## Pros & Cons | 优缺点

**Pros | 优势**
- Concrete per-model price table with official prices side by side
- Both OpenAI and Anthropic wire formats
- No subscription

**Cons | 劣势**
- New service (launched 2026-08); little third-party track record yet
- No public status page yet
- English-only site

## Review Score | 评分

*To be filled by maintainers / community. The operator does not self-score.*

## Benchmark Data | 基准数据

*Pending the repository's own validation run.*

## User Reviews | 用户评价

*To be populated.*

## Changelog | 更新日志

- `2026-10-18` — Initial entry (self-submission)

---

**Conflict of interest disclosure** | **利益相关声明**: Submitted by the Zerouter team (operator). 本条目由 Zerouter 运营方提交。
