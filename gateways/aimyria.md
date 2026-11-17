# Aimyria

> One-key AI API gateway: OpenAI-compatible + Anthropic Messages endpoints across Claude / GPT / Gemini / Grok / DeepSeek / GLM / Kimi / Qwen. Subscription-style group multipliers on top of official per-token prices.

**[Official Website](https://aimyria.com)** · **[Pricing](https://aimyria.com/pricing)** · **[Docs](https://aimyria.com/docs/)** · **[llms.txt](https://aimyria.com/llms.txt)**

---

## Quick Facts | 基本信息

| Field | Value |
|-------|-------|
| **Founded** | 2026-09 (site live; operator runs the [agentapiai.com](https://agentapiai.com) measurement project since 2026-10) |
| **Base Region** | China-facing, global reachable |
| **Target Users** | Developers / Claude Code & Codex users / small teams |
| **Site Language** | ZH (primary) / EN |
| **API Compatible With** | OpenAI (`https://aimyria.com/v1`) / Anthropic Messages (`https://aimyria.com`) |
| **Claude Code Support** | ✅ (ANTHROPIC_BASE_URL drop-in; install guides at [learn/zh-hans](https://aimyria.com/learn/zh-hans/cn-coding-tools-api-config/)) |
| **Last Verified** | 2026-11-17 |

## Pricing | 定价

*公式：我们的价 = 官方价 × 分组倍率。全部 48 个按量计价模型逐模型价目表（官方价对照 + 约省百分比 + 30 天可用率）公开在 [aimyria.com/pricing](https://aimyria.com/pricing)。以下为抽样（USD per 1M tokens，截至 2026-11-17）：*

| Model | Input (ours) | Output (ours) | Official | Diff | Group |
|-------|-------|--------|----------|------|-------|
| claude-haiku-4-5 | $0.346 | $1.73 | $1 / $5 | -65% | Claude Code 渠道·稳定 (×0.3465) |
| claude-sonnet-5-5 | $3 | $15 | $3 / $15 | ×1.0 | Claude CCMAX 满血·旗舰 (×1.188) |
| gpt-6.1-terra | $0.088 | $0.44 | $1 / $5 | -91% | GPT Plus (×0.088) |
| glm-5.3 | $0.35 | $1.23 | $1.4 / $4.93 | -75% | GLM (×0.25) |
| deepseek-v4.1-flash | see pricing page | see pricing page | — | -77% | DeepSeek (×0.23) |

Note: DeepSeek 分组倍率 0.23（省 77%）、GLM 分组倍率 0.25（省 75%）；订阅型档位（GPT Plus / Claude Code 渠道等）按分组倍率计费。

## Supported Models | 支持模型

- **Anthropic**: claude-opus-5-5, claude-sonnet-5-5, claude-haiku-4-5, claude-fable-5-1, …
- **OpenAI**: gpt-6.1-sol / terra / astra, gpt-5.6-sol / terra, gpt-image-2, …
- **Google**: gemini-4-argon / carbon / hydrogen, gemini-3.8-flash, …
- **xAI**: grok-4.7 …
- **DeepSeek**: deepseek-v4-pro, deepseek-v4.1-flash, …
- **国产**: glm-5.3 / 5.3-flash, kimi-k3, qwen3.8-max, minimax-m3, …

Full catalog (51 models, machine-readable): https://aimyria.com/api/v1/model-market/catalog

## Payment Methods | 支付方式

- 💳 Alipay / WeChat Pay
- 其他方式见官网充值页

## Features | 特色功能

- One key for all 51 models; both OpenAI-compatible and native Anthropic Messages protocols
- Claude Code / Codex / Cherry Studio / Dify / Cursor drop-in configuration guides (bilingual)
- Machine-readable price feed + `llms.txt` for AI agents
- Daily-probe uptime published per model on the pricing page (真实调用口径 ≥96%)
- Desktop client (aimyria.com/desktop/) for non-CLI users

## Pros & Cons | 优缺点

**Pros | 优势**
- Transparent pricing formula (official × group multiplier) with full per-model table
- Anthropic-native protocol support (not just OpenAI-compat emulation) — Claude Code works out of the box
- Operator runs an independent measurement project (agentapiai.com, 100+ relay stations probed daily); own stats published per model
- Bilingual setup guides for 15+ tools

**Cons | 劣势**
- ZH-first site; EN pages still expanding
- No on-prem / fine-tuning / training-data licensing (stated in llms.txt)
- Not an official model vendor — no vendor SLA

## Review Score | 评分

*Self-submitted by operator — treat accordingly and verify independently.*

| Dimension | Score (/10) | Note |
|-----------|-------------|------|
| **Price** | 9.0 | ×0.088–×0.55 of official on main groups |
| **Latency** | 8.5 | 5–7s avg on Claude-family probes (own data) |
| **Stability** | 9.0 | 98.84% max 30-day availability (own stats) |
| **Model Coverage** | 9.5 | 51 models, 7 families |
| **Support** | 8.0 | — |
| **Payment UX** | 9.0 | Alipay/WeChat, low minimum |
| **Overall** | **8.8** | — |

## Benchmark Data | 基准数据

Last run: 2026-11-17 (self-reported; independent probes of third-party stations live at [agentapiai.com](https://agentapiai.com))

| Metric | Value | Source |
|-------|-----------|--------|
| 30-day availability (main models) | up to 98.84% | aimyria.com/pricing |
| Total API calls served | 255,000+ | aimyria.com |

## User Reviews | 用户评价

*None indexed yet — add community discussion links here.*

## Changelog | 更新日志

- `2026-11-17` — Initial entry (self-submitted with disclosure)

---

**Conflict of interest disclosure** | **利益相关声明**: Submitted by the Aimyria operator (aragorn-agent). All numbers are self-reported and linked to public pages for verification; independent third-party probing of *other* stations is published at [agentapiai.com](https://agentapiai.com). | 本条目由 Aimyria 运营方自荐提交；全部数字可从官网公开页面验证。运营方同时对第三方站点做独立探测（agentapiai.com）。
