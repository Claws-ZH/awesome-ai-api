# NovAI

> OpenAI-compatible relay for Chinese frontier models (DeepSeek, Qwen, GLM, Kimi, MiniMax, Doubao, Hunyuan) with image + video generation on the same endpoint.

**[Official Website](https://aiapi-pro.com)** · **[Pricing](https://aiapi-pro.com/pricing)** · **[Playground](https://aiapi-pro.com/playground)**

---

## Quick Facts | 基本信息

| Field | Value |
|-------|-------|
| **Founded** | 2026-03 |
| **Base Region** | Global (overseas-facing; Chinese-model catalog) |
| **Target Users** | Developers building on Chinese LLMs from outside China |
| **Site Language** | English |
| **API Compatible With** | OpenAI (`https://aiapi-pro.com/v1`, `Authorization: Bearer <key>`) |
| **Claude Code Support** | ⚠️ OpenAI SDK works; native Anthropic `/v1/messages` not verified |
| **Last Verified** | 2026-07-20 |

## Pricing | 定价

*Prices in USD per 1M tokens (from the live [pricing page](https://aiapi-pro.com/pricing); check there for current rates and context tiers).*

| Model | Input | Output |
|-------|-------|--------|
| DeepSeek-V4-Pro | $0.42 | $0.85 |
| DeepSeek-V4-Flash | $0.14 | $0.28 |
| Qwen3.7-Max | $0.55 | $2.19 |
| Qwen-Plus | $0.08 | $0.32 |
| GLM-5 | $0.55 | $2.19 |
| Kimi-K2.6 | $1.04 | $4.30 |
| MiniMax-M3 | $0.35 | $1.41 |
| Doubao-Seed-2.0-Pro | $0.40 | $2.00 |
| Hunyuan Hy3 | $0.18 | $0.72 |

Per-token pay-as-you-go; **$2 signup credit** for new accounts (no card required to start). Image (Doubao Seedream) and video (Doubao Seedance) are billed per generation — see the pricing page.

## Supported Models | 支持模型

- **DeepSeek**: V4-Pro, V4-Flash
- **Qwen (Alibaba)**: Qwen3.7-Max, Qwen3-Max, Qwen-Plus, Qwen3.5-Flash/Plus
- **GLM (Zhipu)**: GLM-5, GLM-5.1/5.2, GLM-4.6V (vision)
- **Moonshot (Kimi)**: Kimi-K2.6, Kimi-K2.7-Code
- **MiniMax**: M2.5, M2.7, M3, Text-01
- **Doubao (ByteDance)**: Seed-2.0 Pro/Lite/Code; **image** (Seedream); **video** (Seedance 2.0)
- **Tencent Hunyuan**: Hy3, MT2 Pro, Role

## Payment Methods | 支付方式

- 💳 Credit card (USD pay-as-you-go)
- 🎁 $2 signup credit (no card to start)

## Features | 特色功能

- One OpenAI-compatible `/v1` endpoint across all major Chinese labs
- Text **+ image (Seedream) + video (Seedance)** on the same key — not just chat
- Per-model published pricing page (no "X% cheaper" hand-waving)
- Browser playground for quick model trials

## Pros & Cons | 优缺点

**Pros | 优势**
- Genuine multi-modal coverage (text/image/video) unusual among Chinese-model relays
- Transparent per-model USD price list
- No-card $2 trial to evaluate

**Cons | 劣势**
- Newer operator (domain active since 2026-03) — limited public track record
- No public status page / SLA numbers yet
- OpenAI-compatible only; Anthropic `/v1/messages` (Claude Code) not verified
- Small user base; few independent third-party reviews so far

## Review Score | 评分

*Operator self-submission — scores intentionally left for independent maintainer/community verification (e.g. via the repo's `/v1/models` probe and a canary check). Not self-rated.*

## Benchmark Data | 基准数据

*Pending independent probe by the repo's automated checks.*

## User Reviews | 用户评价

*None yet — please add community links via PR once available.*

## Changelog | 更新日志

- `2026-07-20` — Initial entry (operator self-submission, unverified)

---

**Conflict of interest disclosure** | **利益相关声明**: The submitter is affiliated with NovAI (operator self-submission). Listed here for independent verification — happy to be canary-probed and to have any field corrected or the entry removed at the maintainer's discretion.
