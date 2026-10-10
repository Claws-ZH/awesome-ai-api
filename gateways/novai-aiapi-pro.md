# NovAI (AI API Pro)

> Zero-platform-fee gateway aggregating 121 Chinese frontier AI models behind one OpenAI-compatible endpoint.

**[Official Website](https://aiapi-pro.com)** · **[Pricing](https://aiapi-pro.com/china-ai-leaderboard.html)** · **[Docs](https://aiapi-pro.com/docs)**

---

## Quick Facts | 基本信息

| Field | Value |
|-------|-------|
| **Founded** | 2026 |
| **Base Region** | Hong Kong (edge), models from China |
| **Target Users** | Developers / overseas teams accessing Chinese models |
| **Site Language** | EN |
| **API Compatible With** | OpenAI |
| **Claude Code Support** | ⚠️ (via OpenAI-compatible base URL; not a native Anthropic endpoint) |
| **Last Verified** | 2026-10-11 |

## Pricing | 定价

*Prices in USD per 1M tokens. NovAI passes through the raw provider list price with **0% platform fee** (no markup), so "Official" = what you pay; Diff = 0%.*

| Model | Input | Output | Official | Diff |
|-------|-------|--------|----------|------|
| deepseek-v4-flash | $0.08 | $0.17 | $0.08 / $0.17 | 0% |
| deepseek-v4-pro | $0.57 | $1.15 | $0.57 / $1.15 | 0% |
| glm-5.3-flash | $0.08 | $0.28 | $0.08 / $0.28 | 0% |
| glm-5.3 | $1.25 | $4.00 | $1.25 / $4.00 | 0% |
| kimi-k2.7-code | $0.67 | $3.40 | $0.67 / $3.40 | 0% |
| qwen3-max | $0.565 | $2.65 | $0.565 / $2.65 | 0% |

Free quotas: $2 signup credit (no card) + 5 permanently free & unlimited models (glm-4.7-flash, glm-4.6v-flash, glm-4.1v-thinking-flash, cogview-3-flash, cogvideox-flash). Live machine-readable price feed: https://aiapi-pro.com/china-ai-leaderboard.json

## Supported Models | 支持模型

- **DeepSeek**: V4 Pro / V4 Flash / V4.1 Flash / V4-Flash-Vision
- **Zhipu GLM**: 5.3 / 5.3-Flash / 5.3-FlashX / 5.2 / 4.7-Flash (free) / 4.6V (free vision)
- **Kimi**: K3 / K2.8 / K2.7-Code / K2.6 / K2.5
- **Qwen**: 3.8-Max / 3.7-Max / 3-Max / Plus / Omni-Turbo / Coder
- **ByteDance Seedance / Doubao**: video + chat
- **MiniMax**: Text / Speech / Music
- **Tencent Hunyuan**: video / 3D / ASR; WAND Vega image
- **Others**: CogVideoX / CogView (free flash), PixVerse, Vidu, Tripo 3D

## Payment Methods | 支付方式

- 💳 Credit card (Visa / Mastercard / UnionPay)
- ₿ Crypto (USDT TRC20)

## Features | 特色功能

- 0% platform fee (pass-through provider list price)
- Single OpenAI-compatible endpoint (`/v1`) for 121 models
- Live first-party price leaderboard (machine-readable JSON)
- Failed video/3D jobs refunded in full; unused balance 7-day refund
- Official MCP server (MCP Registry: io.github.vvvvking/novai-python) + PyPI SDK (aiapi-pro)

## Pros & Cons | 优缺点

**Pros | 优势**
- No markup: you pay the raw provider list price
- Free-unlimited models + $2 no-card credit lower the trial barrier
- Transparent, machine-readable pricing and hard-metrics page

**Cons | 劣势**
- Chinese image models apply a visible "AI-generated" watermark per China labeling rules
- No native Anthropic-compatible endpoint (OpenAI-compatible only)

## Review Score | 评分

| Dimension | Score (/10) | Note |
|-----------|-------------|------|
| **Price** | 9.5 | 0% markup; free-unlimited tier |
| **Latency** | 8.5 | ~80 ms HK edge (self-reported) |
| **Transparency** | 9.5 | Live price JSON + transparency JSON |
| **Model breadth** | 9.0 | 121 Chinese frontier models |
