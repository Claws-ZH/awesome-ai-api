# TeapotRouter

> Usage-based AI model gateway where a single key speaks both the OpenAI and Anthropic wire protocols, with a machine-readable price list and a per-request cost ledger.

**[Official Website](https://teapotrouter.com)** · **[Pricing JSON](https://teapotrouter.com/api/pricing)**

---

## Quick Facts | 基本信息

| Field | Value |
|-------|-------|
| **Founded** | 2026-10 (domain registered 2026-10-17, per RDAP) |
| **Base Region** | Global |
| **Target Users** | Developers using Claude Code and the OpenAI SDK |
| **Site Language** | EN |
| **API Compatible With** | Both (OpenAI `/v1`; Anthropic `/v1/messages`) |
| **Claude Code Support** | ✅ (`ANTHROPIC_BASE_URL=https://api.teapotrouter.com`) |
| **Last Verified** | 2026-10-27 |

## Pricing | 定价

*No login required: the full price feed is served as JSON at https://teapotrouter.com/api/pricing (fetched 2026-10-27). USD per 1M tokens, derived from that feed's own fields — `model_ratio` × $2 for input, × `completion_ratio` for output, × `standardGroupRatio` 0.35, with `quotaPerUnit` 500000. No comparison against any list price is intended by this table.*

| Model | Input ratio | Output ratio | Input $/1M | Output $/1M |
|-------|-------------|--------------|------------|-------------|
| gpt-6.1-sol | 1.0 | 2.0 | $0.70 | $1.40 |
| gpt-6-astra | 5.0 | 2.0 | $3.50 | $7.00 |

Prepaid USD balance, billed per request; $1 minimum top-up. The JSON feed is version-free but timestamped per fetch — re-read it rather than trusting this snapshot.

## Supported Models | 支持模型

- **Catalog at last check** (from `/v1/models` with a valid key, 2026-10-27): `gpt-6-astra`, `gpt-6.1-sol`
- The gateway is protocol-dual rather than catalog-wide: Anthropic Messages and OpenAI `/v1` are both served on the same key, for Claude Code (`ANTHROPIC_BASE_URL`) and OpenAI-SDK (`base_url` /v1) clients respectively.

## Engine | 引擎

`/v1/models` without a key returns a JSON error of type `new_api_error`, so the backend appears to run on the new-api engine. Differentiation claimed by the operator: dual-protocol access on one key, the unauthenticated pricing JSON above, a per-request cost record visible in the console, org-level key issuing with audit logs, and automatic failover across upstreams.

## Payment Methods | 支付方式

- 💳 Alipay
- 💳 International credit card

## Features | 特色功能

- One key, two protocols: Anthropic Messages and OpenAI `/v1` on the same account
- Price list published as login-free JSON (`/api/pricing`)
- Every request leaves a queryable cost record
- Organization-level keys with audit logs
- Automatic failover across upstreams
- $1 minimum top-up

## Pros & Cons | 优缺点

**Pros | 优势**
- Pricing is machine-checkable without an account
- Dual wire formats on a single key
- Very low entry cost ($1 top-up)

**Cons | 劣势**
- Brand-new service (domain registered 2026-10-17; under the 30-day activity bar in the listing criteria)
- Catalog was only two models at last check
- English-only site; no public status page found
- Runs on the new-api engine rather than original infrastructure

## Review Score | 评分

*To be filled by maintainers / community. The operator does not self-score.*

## Benchmark Data | 基准数据

*Pending the repository's own validation run.*

## User Reviews | 用户评价

*To be populated.*

## Changelog | 更新日志

- `2026-10-27` — Initial entry (self-submission)

---

**Conflict of interest disclosure** | **利益相关声明**: Submitted by the TeapotRouter operator. 本条目由 TeapotRouter 运营方自荐提交。
