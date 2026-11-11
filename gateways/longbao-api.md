# 龙宝 API（小天才龙宝的开发基地）

> 国内可访问的 AI API 中转站：一个 Key 调 Claude、GPT、DeepSeek、Qwen、GLM 等 38 个模型，OpenAI 与 Anthropic 双协议，按量计费并公开逐模型单价。

**[Official Website](https://api.888425.xyz/pricing)** · **[Pricing](https://api.888425.xyz/pricing)** · **[Model Rankings](https://api.888425.xyz/rankings)**

---

## Quick Facts | 基本信息

| Field | Value |
|-------|-------|
| **Founded** | 2025-12 |
| **Base Region** | China (国际线路) |
| **Target Users** | 个人开发者 / 小团队 / 初学者 |
| **Site Language** | ZH |
| **API Compatible With** | Both (OpenAI + Anthropic) |
| **Claude Code Support** | ✅ |
| **Last Verified** | 2026-11-11 |

## Pricing | 定价

*Prices in USD per 1M tokens unless noted. 均为该模型可购买分组中的实际价格，非基础倍率价。*

| Model | Input | Output | Official | Diff |
|-------|-------|--------|----------|------|
| claude-opus-5-5 | $0.60 | $3.00 | — | — |
| claude-sonnet-5-5 | $0.30 | $1.50 | — | — |
| deepseek-v4.1-flash | $0.075 | $0.30 | — | — |
| gemini-3.8-flash | $0.225 | $1.125 | — | — |

按次 / 按秒计价的模型（选摘）：

| Model | Price | Unit |
|-------|-------|------|
| glm-5.3 | $0.0625 | 每次 |
| kimi-k3.1-pro | $0.25 | 每次 |
| gpt-image-2.6 | $0.035 | 每次 |
| qwen-image-3.0 | $0.018 | 每次 |

说明：
- 完整逐模型价格见 <https://api.888425.xyz/pricing>，页面每小时从定价接口重新生成，含输入、输出、缓存读取、缓存写入四项单价与分组倍率。
- 站内分「标准区 / 高速区 / 生图专区 / 低价体验区」等分组，同一模型在不同分组倍率不同，上表取最低可购价。
- 6 个「赠品」体验模型按 0.01–0.05 美元/百万 token 计费，用于先跑通接入。

## Supported Models | 支持模型

- **Anthropic**: claude-fable-5-2, claude-opus-5-5, claude-sonnet-5-5, claude-haiku-5-5
- **OpenAI**: gpt-6-astra, gpt-6.1-sol, gpt-image-2 / 2.5 / 2.6（含 GIF 版本）
- **Google**: gemini-3.8-flash, gemini-3.8-flash-high
- **DeepSeek**: V4.1-Flash（含谷峰计费版）
- **Alibaba**: qwen3.8-max / qwen3.8-flash, qwen-image-2.0-pro / 3.0, wan3.0-video
- **Zhipu**: glm-5.3, glm-5.3-flash, glm-5.3-prime
- **Moonshot**: kimi-k3.1-pro
- **MiniMax**: mimo-v2.6-pro

## Payment Methods | 支付方式

- 💳 支付宝 / 微信
- 充值按人民币计价；站内展示单位为美元符号，汇率见控制台

## Features | 特色功能

- **双协议**：同一 Key 同时支持 OpenAI（`/v1/chat/completions`、`/v1/responses`）与 Anthropic（`/v1/messages`）
- **公开价格页**：逐模型单价、分组倍率、生图按次价全部公示
- **用量日志**：每次调用可查 token 明细、缓存命中与扣费金额
- **生图与视频**：gpt-image、qwen-image、wan3.0-video 按次/按秒计价
- **初学者友好**：提供零基础接入说明与体验群

## Pros & Cons | 优缺点

**Pros | 优势**
- 价格与计费方式公开，账单调得出明细
- 模型覆盖面较全，推理、生图、视频混在一个 Key 下
- 国产模型按人民币官方价数值计价，不做汇率加价

**Cons | 劣势**
- 站点上线时间较短（2025-12 建站，运营记录自 2025-10 起），长期稳定性仍待观察
- 无公开 status 页与 SLA 承诺
- 部分模型（如 gpt-6 系列、claude-fable-5-2）尚未单独配置倍率，站内显示为「见控制台」，需登录后确认价格
- 无发票、无企业级售后

## Review Score | 评分

*以下为自评，非第三方实测，仅供参考。*

| Dimension | Score (/10) | Note |
|-----------|-------------|------|
| **Price** | 8.0 | 主流模型明显低于官方 |
| **Latency** | — | 未做长期实测 |
| **Stability** | — | 运营时间短，无足够样本 |
| **Model Coverage** | 8.5 | 38 个模型，含生图与视频 |
| **Support** | 6.0 | QQ 群答疑 |
| **Payment UX** | 7.0 | 支付宝/微信，充值到账 |
| **Overall** | — | 待第三方实测 |

## Benchmark Data | 基准数据

未提供。不做无数据支撑的 SLA 或延迟承诺。

## User Reviews | 用户评价

暂无公开评测。

## Changelog | 更新日志

- `2026-11-11` — Initial entry

---

**Conflict of interest disclosure** | **利益相关声明**: 本条目的提交者是该站点的运营方。
