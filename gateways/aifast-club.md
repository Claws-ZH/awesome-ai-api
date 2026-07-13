# AI快站 · AIFast Hub (www.aifast.club)

> OpenAI-compatible AI API gateway for developers who want to use models from several providers through one endpoint. The current catalog and maintenance status are available on the platform.

**[Website](https://www.aifast.club)** · **[Published status reference](https://kkwang4444.github.io/api-status/)** · **[Integration guide](https://github.com/KKWANG4444/ai-api-proxy-china-guide)**

---

## Quick facts | 基本信息

| Field | Value |
|---|---|
| **Region** | China-oriented service |
| **Site language** | Chinese |
| **API style** | OpenAI-compatible endpoint |
| **Base URL** | `https://www.aifast.club/v1` |
| **Model availability** | Check the current marketplace and latest maintenance notices |
| **Last reviewed** | 2026-07-12 |

## Current model examples | 当前模型示例

The following IDs were checked against the AIFast public model configuration. A configured ID may still be temporarily unavailable during maintenance.

- **OpenAI**: `gpt-5.6-sol`, `gpt-5.6-terra`, `gpt-5.6-luna`
- **Anthropic**: `claude-sonnet-5`, `claude-opus-4-8`, `claude-fable-5`
- **xAI**: `grok-4.5`, `grok-4.3`, `grok-4-20-reasoning`
- **Google**: `gemini-3.5-flash`
- **DeepSeek**: `deepseek-v4-pro`, `deepseek-v4-flash`
- **Alibaba**: `qwen3.7-max`
- **Zhipu**: `glm-5.2`
- **ByteDance**: `doubao-seed-2-1-pro-260628`
- **Moonshot**: `kimi-k2.7-code`

Doubao Seed 2.1 Turbo is not presented as currently available because the latest AIFast notice says it is temporarily offline for maintenance.

## API example | API 示例

```bash
curl https://www.aifast.club/v1/chat/completions \
  -H "Authorization: Bearer $AIFAST_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "gpt-5.6-terra",
    "messages": [
      {"role": "user", "content": "Hello"}
    ]
  }'
```

Model support, latency and availability vary with the provider, route, account, network and maintenance state. Test the exact model and request format before production use.

## International payment

International users can pay **only with cryptocurrency**. The current balance conversion is:

- **1 USD-denominated balance unit = 0.07 USDC**
- **1 USD-denominated balance unit = 0.07 USDT**

Fiat payment methods are not available to international users. Check the AIFast console before payment because the supported network or deposit instructions can change.

## Notes | 说明

- This entry does not publish a fixed model count because configuration entries do not equal currently available models.
- It does not quote model prices. Pricing and account options should be checked in the AIFast console.
- The linked status project contains published observations, not an uptime guarantee or SLA.
- The submitter operates AIFast; this conflict of interest is disclosed in the pull request.
