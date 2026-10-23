# NovAI (AI API Pro)

> Zero-platform-fee gateway aggregating 110+ Chinese frontier AI models behind one OpenAI-compatible endpoint.

**[Official Website](https://aiapi-pro.com)** · **[Pricing](https://aiapi-pro.com/china-ai-leaderboard.html)** · **[Docs](https://aiapi-pro.com/docs)**

---

## Quick Facts | 基本信息

| Field | Value |
|-------|-------|
| **Founded** | 2026 |
| **Base Region** | Hong Kong edge, upstream providers in China |
| **Target Users** | Developers / overseas teams accessing Chinese models |
| **Site Language** | EN |
| **API Compatible With** | OpenAI |
| **Claude Code Support** | ⚠️ (via OpenAI-compatible base URL; not a native Anthropic endpoint) |
| **Last Verified** | 2026-10-20 |

## Pricing | 定价

*USD per 1M tokens, read from the model pages on 2026-10-20. NovAI passes through the provider list price with **0% platform fee**; "Official" = provider list price, so Diff = 0%. Machine-readable feed: https://aiapi-pro.com/china-ai-leaderboard.json*

| Model | Input | Output | Official | Diff |
|-------|-------|--------|----------|------|
| deepseek-v4-flash | $0.08 | $0.17 | $0.08 / $0.17 | 0% |
| deepseek-v4-pro | $0.57 | $1.15 | $0.57 / $1.15 | 0% |
| glm-5.3-flash | $0.08 | $0.28 | $0.08 / $0.28 | 0% |
| glm-5.3 | $1.25 | $4.00 | $1.25 / $4.00 | 0% |
| kimi-k3 | $2.90 | $14.50 | $2.90 / $14.50 | 0% |
| qwen3.8-max | $1.84 | $5.52 | $1.84 / $5.52 | 0% |

Free tier: $2 signup credit (no card) + 5 permanently free & unlimited models (glm-4.7-flash, glm-4.6v-flash, glm-4.1v-thinking-flash, cogview-3-flash, cogvideox-flash). Image/video/3D/audio models are billed per generation/second on the same key.

## Supported Models | 支持模型

- **DeepSeek**: V4 Pro / V4 Flash / V4.1 Flash / V4-Flash-Vision
- **Zhipu GLM**: 5.3 / 5.3-Flash / 5.3-FlashX / 5.2 / 4.7-Flash (free) / 4.6V (free vision)
- **Kimi**: K3 / K2.8 / K2.7-Code / K2.6 / K2.5
- **Qwen**: 3.8-Max / 3.7-Max / Plus / Coder / VL / OCR
- **ByteDance**: Seedance 2.5 / 2.0 video, Seedream 5.0 image, Doubao chat
- **MiniMax**: M3 chat, Speech 2.8, Music 3.0, Hailuo video
- **Tencent Hunyuan**: video / 3D / ASR / role-play; WAND Vega image
- **Others**: CogVideoX / CogView (free flash), PixVerse, Vidu, Kling, Tripo 3D

The live count is whatever `GET https://aiapi-pro.com/v1/models` returns (111 as of 2026-10-20).

## Payment Methods | 支付方式

- 💳 Credit card (Visa / Mastercard / UnionPay)
- ₿ Crypto (USDT TRC20)

## Features | 特色功能

- 0% platform fee (pass-through provider list price)
- Single OpenAI-compatible endpoint (`/v1`) for the whole catalogue
- Live first-party price leaderboard (machine-readable JSON)
- Public uptime probe + incident log (`/status.html`) and billing-integrity page (`/provenance.html`)
- Failed video/3D jobs refunded in full; unused balance 7-day refund
- Official MCP server (MCP Registry: io.github.vvvvking/novai-python) + PyPI SDK (aiapi-pro)

## Pros & Cons | 优缺点

**Pros | 优势**
- No markup: you pay the raw provider list price
- Free-unlimited models + $2 no-card credit lower the trial barrier
- Transparent, machine-readable pricing and uptime data

**Cons | 劣势**
- Chinese image models apply a visible "AI-generated" watermark per China labelling rules
- No native Anthropic-compatible endpoint (OpenAI-compatible only)
- Small operator; no enterprise SLA

## Review Score | 评分

*Not self-scored. Awaiting independent probe/score from the maintainers' pipeline.*

## Changelog | 更新日志

- `2026-10-20` — Entry refreshed on latest master: model count aligned to live `/v1/models`, prices re-read from model pages, self-scoring removed

---

**Conflict of interest disclosure** | **利益相关声明**: Operator submission — this entry is maintained by the NovAI team. Descriptive fields only; pricing is verifiable at the live JSON feed above.
