# Zurelay

> One OpenAI-compatible API (plus Anthropic Messages for Claude) for 56 chat models and 26 image, video and speech models, priced below each lab's list price, with a public per-model price list.

**[Official Website](https://zurelay.com)** · **[Pricing](https://zurelay.com/models)** · **[Pricing JSON](https://zurelay.com/prices.json)** · **[Docs](https://zurelay.com/docs)** · **[Status](https://zurelay.com/status)**

---

## Quick Facts | 基本信息

| Field | Value |
|-------|-------|
| **Founded** | 2026-10 (live since 2026-10-03; domain registered 2026-09-29, per RDAP) |
| **Base Region** | Global |
| **Target Users** | Developers |
| **Site Language** | EN (docs and site in 12 languages) |
| **API Compatible With** | Both (OpenAI `https://api.zurelay.com/v1`; Anthropic `POST /v1/messages` for Claude) |
| **Claude Code Support** | ✅ (`ANTHROPIC_BASE_URL`, [guide](https://zurelay.com/docs/integrations/claude-code)) |
| **Last Verified** | 2026-11-03 |

## Pricing | 定价

*Prices in USD per 1M tokens, from https://zurelay.com/prices.json on 2026-11-03. "Official" is the lab's own list price.*

| Model | Input | Output | Official | Diff |
|-------|-------|--------|----------|------|
| Claude Opus 5.5 | $1.40 | $7.00 | $4 / $20 | -65% |
| Claude Sonnet 5.5 | $0.79 | $3.95 | $2 / $10 | -61% |
| Claude Haiku 5.5 | $0.04 | $0.20 | $0.10 / $0.50 | -60% |
| GPT-6.1 Sol | $0.50 | $2.50 | $2 / $10 | -75% |
| GPT-6 Astra | $2.50 | $12.50 | $10 / $50 | -75% |
| Gemini 4 Argon | $0.80 | $4.00 | $2 / $10 | -60% |
| Gemini 3.8 Flash | $0.22 | $1.10 | $0.75 / $3.75 | -71% |
| DeepSeek V4.1 Flash | $0.03 | $0.12 | $0.30 / $1.20 | -90% |
| Grok 4.7 | $0.70 | $2.10 | $2 / $6 | -65% |
| Kimi K3.1 Pro | $0.80 | $4.00 | $2 / $10 | -60% |
| GLM-5.3 | $0.38 | $1.21 | $1.40 / $4.40 | -73% |
| Qwen 3.8 Max | $1.20 | $3.60 | $2 / $6 | -40% |

Cached input is billed at each model's cached price. Long-prompt tiers follow the labs (GPT models 2x input and 1.5x output past 272K tokens; Claude Haiku 5.5 5x past 100K). Image models are priced per image and video per second of output, on the same price list. No subscription; prepaid credit from $10.

## Supported Models | 支持模型

- **OpenAI**: GPT-6 Astra, GPT-6.1 Sol, GPT-6.1 Terra, GPT-6 Sol, GPT-6 Luna, GPT-5.6 Sol/Terra/Luna, GPT Image 2.5 Flare/Sunburst, GPT Image 2, Text Embedding 3 Small/Large
- **Anthropic**: Claude Opus 5.5, Sonnet 5.5, Haiku 5.5, Fable 5.1, Fable 5, Opus 5, Opus 4.8/4.7/4.6, Haiku 4.5
- **Google**: Gemini 4 Argon, Gemini 3.1 Pro, Gemini 3.8/3.7 Flash, Gemini 3.5/3.1 Flash-Lite, Nano Banana 2.1/Pro/2/2 Lite, Veo 3.1 Fast, Gemini TTS
- **DeepSeek**: V4.1 Flash, V4.1 Flash 1017, V4 Flash, V4 Flash 0731, V4 Pro 0813
- **Others**: xAI Grok 4.7 and Grok Imagine; Moonshot Kimi K3.1 Pro, K3, K2.6, K2.5; Alibaba Qwen 3.8 Max/Flash/Omni Flash and Wan 3.0; Z.ai GLM-5.3, GLM-5.2, GLM-5.3 Flash; MiniMax M3.1 Flash, M3, M2.5, H3; Xiaomi MiMo V2.6; Meta Muse Wonder; StepFun Step 5 Preview; Mistral Ministral 3; Seedance, Kling, Vidu, PixVerse, FLUX 3

The live list, with what each model reads (images, PDFs, audio, video): `GET https://api.zurelay.com/v1/models` (no key needed) or https://zurelay.com/models.

## Upstream | 上游来源

Each model is served over several routes run by independent sellers: capacity bought ahead (prepaid credits, committed-spend contracts) and resold below list price. Zurelay doesn't publish which seller serves which route. Every route is tested before it serves requests (identity under different system prompts, dated-knowledge questions, exact-answer reasoning, token counts, tool calls, streaming) and re-tested daily; a route that fails is taken out of rotation. Method: https://zurelay.com/docs/verification. Requests aren't served under a lab's own customer terms (Terms 3.3 to 3.6: https://zurelay.com/legal/terms).

## Payment Methods | 支付方式

- 💳 Credit card (Stripe), with optional auto-recharge

## Features | 特色功能

- OpenAI Chat Completions, Images, embeddings and speech, plus Anthropic Messages (with `cache_control` prompt caching) for Claude
- Failover: a failed request moves to another route of the same model and isn't billed
- Live per-model status and outage history: https://zurelay.com/status
- Request logs, per-key budgets, model allow-lists and IP rules
- Guides for Claude Code, Cursor, Cline, Kilo Code, OpenCode, Open WebUI, LobeHub, Cherry Studio and more: https://zurelay.com/docs/integrations

## Pros & Cons | 优缺点

**Pros | 优势**
- Public, machine-readable price list with the lab's list price beside each model
- One key for chat, image, video and speech models across labs
- Claude through native Anthropic Messages, so Claude Code and prompt caching work as on Anthropic's API

**Cons | 劣势**
- Young service (live since 2026-10-03)
- Resold capacity from independent sellers, not the labs' own API terms; no zero-data-retention or HIPAA offering
- No OpenAI Responses, Realtime, Batch or fine-tuning APIs
- Card payment only; purchases are non-refundable (Terms 8.6)

## Review Score | 评分

Left for independent reviewers: this entry is an operator submission.

## Benchmark Data | 基准数据

Live per-model status: https://zurelay.com/status (no independent benchmark run yet).

## User Reviews | 用户评价

- None linked yet.

## Changelog | 更新日志

- `2026-11-03` — Initial entry (operator submission)

---

**Conflict of interest disclosure** | **利益相关声明**: Submitted by the Zurelay team (the operator). 本条目由 Zurelay 运营方提交。
