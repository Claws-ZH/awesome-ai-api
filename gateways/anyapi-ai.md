# AnyAPI.ai

> One OpenAI-compatible API for 400+ models across Anthropic, OpenAI, Google, xAI, DeepSeek, Qwen, Moonshot and Z.ai, with per-token billing in ₳nytokens and a free tier.

**[anyapi.ai](https://anyapi.ai)** · **[Pricing](https://anyapi.ai/pricing)** · **[Docs](https://docs.anyapi.ai)**

---

## Quick Facts

| Field | Value |
|-------|-------|
| **Founded** | 2025-05 |
| **Base Region** | United States (global) |
| **Target Users** | Developers, startups, teams |
| **Site Language** | English |
| **API Compatible With** | OpenAI + Anthropic |
| **Claude Code Support** | ✅ (`ANTHROPIC_BASE_URL=https://api.anyapi.ai`) |
| **Last Verified** | 2026-11-04 |

## Pricing

Billing is per token in **₳nytokens**, published per model on the pricing page. Plan prices are in USD.

| Plan | Price | Included |
|------|-------|----------|
| Free | $0 | 100K ₳nytokens/day, free-tier models, no credit card |
| Pay-as-you-go | usage-based from $20 | All 400+ models, purchased ₳nytokens never expire |
| Developer | $19.90/mo | 100M ₳nytokens, roll-over |
| Pro | $95.90/mo | 500M ₳nytokens, priority support |
| Enterprise | $279.90/mo | 1.5B ₳nytokens, custom integrations |

Published per-model prices, for example:

| Model | Input ₳ | Output ₳ |
|-------|---------|----------|
| Claude Opus 5.5 | 24 | 120 |
| Claude Sonnet 4.6 | 18 | 90 |
| GPT-6 Astra | 7 | 35 |
| Gemini 3.8 Flash | 4.5 | 22.5 |
| Grok 4.7 | 9.6 | 28.8 |
| DeepSeek V4 Pro | 9.6 | 19.2 |
| Kimi K3 | 4.8 | 81 |

Prices change; the pricing page is the source of truth.

## Supported Models

- **Anthropic**: Claude Opus 4.x/5.x, Sonnet 4.x, Haiku 4.x, Fable 5.x
- **OpenAI**: GPT-5.x, GPT-6 Astra, o-series, GPT-OSS
- **Google**: Gemini 3.x Pro/Flash, Gemma
- **xAI**: Grok 4.x
- **DeepSeek**: V3.x, V4 Pro/Flash, R1
- **Qwen**: Qwen3 family, Qwen3-Coder, Qwen3-VL
- **Moonshot**: Kimi K2.x, K3
- **Z.ai**: GLM-4.x/5.x
- **Others**: Mistral, Meta Llama, MiniMax, NVIDIA Nemotron, Perplexity Sonar

## Payment Methods

- 💳 Credit card (Stripe)
- ₿ Crypto (USDC, USDT, Bitcoin, Ethereum)
- 🏦 Bank transfer (enterprise)

## Features

- **Automatic failover** across upstream providers
- **Model routing** by cost, latency, uptime and capability tags
- **Zero Completion Insurance**: no charge for failed or empty completions
- **Prompt caching**, tool calling, structured outputs, web search
- **OpenAI SDK, AnyCLI, AnyChat**, plus n8n node and editor integrations (Claude Code, Cline, OpenCode, Kilo Code)

## Pros & Cons

**Pros**
- One key and one balance for every major model family
- Anthropic Messages API served natively, so Claude Code works without a local proxy
- Free tier usable without a card
- Crypto payments accepted

**Cons**
- Prices are published in ₳nytokens, not USD per 1M tokens, so comparing against official list prices requires the plan maths
- No public status page yet
- Newer operator (domain active since 2025-05), shorter track record than the established relays

## Links

- Website: https://anyapi.ai
- Pricing: https://anyapi.ai/pricing
- Docs: https://docs.anyapi.ai
- API base: https://api.anyapi.ai/v1
