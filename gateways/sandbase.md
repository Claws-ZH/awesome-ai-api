# SandBase

> One API key for 2,000+ models and data APIs, plus free sandboxes and agents. OpenAI-compatible API at `https://api.sandbase.ai/v1`. Independent product (models, data APIs, sandboxes, and agents); not submitted as a one-api/new-api reskin. Engine fingerprint is left for the maintainers' daily probe.

**[Official Website](https://www.sandbase.ai)** · **[Pricing](https://www.sandbase.ai/pricing)** · **[Models](https://www.sandbase.ai/models)** · **[APIs](https://www.sandbase.ai/apis)** · **[Docs](https://www.sandbase.ai/docs/getting-started/)** · **[SDK](https://github.com/sandbaseai/sandbase)** · **[CLI / MCP](https://github.com/sandbaseai/cli)**

---

## Quick Facts | 基本信息

| Field | Value |
|-------|-------|
| **Founded** | 2026-07 (founder LinkedIn lists the SandBase founder role from Jul 2026; sandbase.ai does not publish a founding date) |
| **Base Region** | Global (operator named in the Terms: AXIOMCLOUD PTE. LTD., Singapore) |
| **Target Users** | Developers |
| **Site Language** | English (primary) |
| **API Compatible With** | OpenAI-compatible (`https://api.sandbase.ai/v1`). Homepage also documents OpenAI Agents API compatibility. |
| **Claude Code Support** | ⚠️ Documented via [SKILL.md](https://www.sandbase.ai/SKILL.md) and the CLI (`connect --client claude-code`, also `cursor` and `codex`). Not exercised in this listing. |
| **Last Verified** | 2026-11-08 (public pages and an unauthenticated route check only — not a scored probe) |

## Pricing | 定价

Per-model and per-API prices are published on the official site. This entry does not copy them into a Diff table.

- [Pricing](https://www.sandbase.ai/pricing) — pay per call, no subscription. The page says selected models have live discounts (headline: "Up to 35% off"), catalog discovery is free, failed calls are not charged, and sandboxes are free for now (fair-use caps may apply; pricing to be announced before it changes).
- [Models catalog](https://www.sandbase.ai/models), [APIs catalog](https://www.sandbase.ai/apis), and the [homepage catalog](https://www.sandbase.ai) — each card shows the price you pay and a discount versus the listed price. Use those pages rather than any number copied here.

Free allowance, from the site: free agents and sandboxes; 100 free calls per day per organization on eligible data APIs, resetting at 00:00 UTC. The site says AI model calls are billed separately from that data-API allowance. The Starter plan is listed at $0 with starter credits; the credit amount is not stated on the pricing page reviewed here.

## Supported Models | 支持模型

The site advertises 2,000+ models and data APIs across 100+ platforms. The homepage catalog checked on 2026-11-08 shows entries from providers including Anthropic, OpenAI, Google, DeepSeek, xAI, Alibaba, Moonshot, MiniMax, Z-Ai, ByteDance, and KwaiVGI (language, image, and video). That is the public catalog, not a probed `/v1/models` inventory. `real_models_count` is left unset.

## Payment Methods | 支付方式

Unknown. [Pricing](https://www.sandbase.ai/pricing) and the [Terms](https://www.sandbase.ai/terms) (section 10, last updated October 14, 2026) describe checkout, a payment processor, credits, and taxes. They do not name credit card, Alipay, WeChat Pay, or crypto. Those methods are not claimed here.

## Features | 特色功能

- OpenAI-compatible base URL `https://api.sandbase.ai/v1` (shown in the homepage Python example)
- OpenAI Agents API compatible, per the homepage
- Data APIs and sandboxes in the same account; sandbox example uses the E2B SDK against `https://sandbox.sandbase.ai`
- Open-source SDK: [sandbaseai/sandbase](https://github.com/sandbaseai/sandbase) (Apache-2.0)
- Open-source CLI / local MCP: [sandbaseai/cli](https://github.com/sandbaseai/cli) (Apache-2.0)
- Claude Code, Cursor, and Codex setup via [SKILL.md](https://www.sandbase.ai/SKILL.md) and the CLI

## Pros & Cons | 优缺点

**Pros | 优势**
- Public pricing and model/API catalogs on sandbase.ai
- Open-source SDK and CLI, both Apache-2.0
- Documented path for Claude Code, Cursor, and Codex

**Cons | 劣势**
- Not yet classified by this repo's daily probe (no score, latency, uptime, or engine fingerprint in this submission)
- Payment methods are not named on the pages reviewed
- Founding date is not published on sandbase.ai
- This listing is submitted by the founder (see disclosure)

## Review Score | 评分

Pending maintainer probe. No scores are filled in.

| Dimension | Score (/10) | Note |
|-----------|-------------|------|
| **Price** |  | Pending maintainer probe |
| **Latency** |  | Pending maintainer probe |
| **Stability** |  | Pending maintainer probe |
| **Model Coverage** |  | Pending maintainer probe |
| **Support** |  | Pending maintainer probe |
| **Payment UX** |  | Pending maintainer probe |
| **Overall** |  | Pending maintainer probe |

## Benchmark Data | 基准数据

Last run: pending maintainer probe. No TTFT, tokens/sec, or uptime figures are included.

| Model | TTFT (ms) | Tokens/sec | Uptime |
|-------|-----------|-----------|--------|
|  |  |  |  |

Unauthenticated existence check only (not a scored probe): on 2026-11-08 SGT, `GET https://sandbase.ai/v1/models` and `GET https://api.sandbase.ai/v1/models` each returned HTTP 401, `content-type: application/json`, body `{"error":"missing API key in Authorization header"}`. Same status [issue #34](https://github.com/Claws-ZH/awesome-ai-api/issues/34) reported on 2026-08-28. Latency was not recorded. Model list, engine, and uptime were not measured.

## User Reviews | 用户评价

No independent community reviews are linked in this submission.

- Verification request: [Claws-ZH/awesome-ai-api#34](https://github.com/Claws-ZH/awesome-ai-api/issues/34)

## Changelog | 更新日志

- `2026-11-08` — Initial entry. Probe, score, latency, uptime, and engine left blank for the maintainers' daily probe.

---

**Conflict of interest disclosure** | **利益相关声明**: David Li, founder of SandBase.
