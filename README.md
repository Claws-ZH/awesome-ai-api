# awesome-ai-api

> The world's largest open-source hub for AI API gateways & reseller reviews.  
> Curated · community-driven · fully transparent · **every gateway probed daily**.

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT"></a>
  <a href="./CONTRIBUTING.md"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome"></a>
  <!-- STATS:BEGIN -->
  <img src="https://img.shields.io/badge/Gateways-186-blue" alt="Total">
  <img src="https://img.shields.io/badge/API_verified-92-success" alt="API verified">
  <img src="https://img.shields.io/badge/Updated-daily_10:00_SGT-orange" alt="Updated">
  <!-- STATS:END -->
</p>

<p align="center">
  <a href="./README.zh-CN.md">🇨🇳 中文</a> · <b>English</b> · <a href="https://mackding.github.io/awesome-ai-api/">🌐 Live site</a>
</p>

---

## What makes us different

We don't just list gateways — **we probe every one of them daily** for a real OpenAI-compatible `/v1/models` endpoint. No `200 OK on the homepage` inflation.

- 🔌 **Ground-truth API detection** — every 🔌 badge = endpoint confirmed live
- 🔍 **Transparency** — no paid placement; [raw data](./data/gateways.json) is Git-history-tracked
- 🌏 **Global** — bilingual (EN/中文), covers Western + Chinese markets
- 🛠 **Developer-first** — structured JSON, daily history snapshots, PR-editable
- 🤝 **Community-driven** — pricing & reviews by people who actually pay for these services

---

## 🎯 Quick Picks

Confused by 200+ gateways? Start here.

<!-- QUICKPICKS:BEGIN -->
| Use case | Recommendation | Why |
|---|---|---|
| 🌐 **Global, one API for all models** | [OpenRouter](https://openrouter.ai) | Pioneer of the pattern; most stable, highest fees |
| 👨‍💻 **Best Claude Code in China** | [PackyAPI](https://www.packyapi.com) | Claude-Code native, active upstream, ¥1/sample |
| 🏢 **Enterprise / invoices** | [柏拉图AI](https://api.bltcy.ai) · [云雾](https://yunwu.ai) | Long-running, multi-region, invoices, DeepSeek/MidJourney too |
| 💰 **Cheap Claude (accept risk)** | [Terminal.Pub](https://terminal.pub) · [XcodeBest](https://xcode.best) | ~0.15% of official; new = verify before topping up |
| 🆓 **Free trial credit** | [AnyRouter](https://anyrouter.dev) · [发现AI](https://www.findcg.com) | Credits on signup, no card |
| 🏠 **Self-hosted** | [One API](https://github.com/songquanpeng/one-api) · [New API](https://github.com/Calcium-Ion/new-api) | OSS; the engine 60% of the CN list runs on |
| ⚡ **Inference-only (Llama/Qwen/DeepSeek)** | [Groq](https://groq.com) · [Together](https://together.ai) · [Fireworks](https://fireworks.ai) | Not resellers; own GPUs; US cards only |
| 🌯 **Multi-modal (video/music/image)** | [神马AI](https://api.whatai.cc) · [302.AI](https://302.ai) | MidJourney, Kling, Suno, PPT generators |
<!-- QUICKPICKS:END -->

> ⚠️ **Never pre-pay large amounts.** This industry has weekly rug-pulls. Top up ¥10 first, validate quality, then consider going up.

---

## 💚 Support this project

This repo is free, ad-free, and has no paid placement. If the leaderboard saved you from topping up a rug-pull, consider chipping in:

- **USDT (any EVM chain — ERC20 / BSC / Polygon / Arbitrum / Base / Optimism):**  
  `0xa5c74e7D3f0c8f1c0d7A395A6B7861Ab0A64cA7F`
- ⭐ **Star the repo** — also helps a lot; boosts us in GitHub trending.
- 📝 **Open a PR** with a gateway report — the most valuable contribution.

> 💡 **Double-check the chain before sending.** Sending from an exchange? Withdraw on **ERC20 / BSC / Polygon / Arbitrum / Base / Optimism**. **Do NOT use TRC20** (TRON) — that address doesn't exist on Tron.

---

## Table of Contents

- [🏆 Full Leaderboard](#-full-leaderboard)
- [❓ FAQ](#-faq)
- [📊 Categories](#-categories)
- [📝 Reviews](#-reviews)
- [⚠️ Blacklist](#️-blacklist)
- [🧪 Benchmark](#-benchmark)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)

---

## 🏆 Full Leaderboard

Auto-generated daily at **10:00 SGT (UTC+8)** from live probes. See [methodology](./reviews/methodology.md) · [history](./data/history/) · [raw data](./data/gateways.json).

**🔌 = confirmed `/v1/models` endpoint (real API, not just a marketing page).**

<details>
<summary><b>📊 Click to expand the full leaderboard</b></summary>

<!-- LEADERBOARD:BEGIN -->
_Last updated: 2026-10-10 16:06 (SGT)_

**Total: 186 gateways** · 🔌 **92 with confirmed `/v1/models` endpoint** · 🟢 121 Verified · 🟡 7 Probable · 🧰 3 OSS · 🔍 55 Needs review

**Top engines detected:** `new-api` × 38 · `one-api` × 18 · `dify` × 3 · `openrouter` × 2 · `litellm` × 2

| # | Gateway | Region | API | Models | Engine | Payment | Score | Latency | Tier |
|---|---------|--------|-----|--------|--------|---------|-------|---------|------|
| 🥇 | [PackyAPI (PackyCode)](https://www.packyapi.com) | cn | 🔌 | claude, gpt, gemini | — | wechat | 9.9 | 109 ms | 🟢 Verified |
| 🥈 | [AIHubMix](https://aihubmix.com) | global | 🔌 | **420 models** | one-api | — | 9.9 | 456 ms | 🟢 Verified |
| 🥉 | [Avian](https://avian.io) | global | 🔌 | **19 models** | — | — | 9.9 | 460 ms | 🟢 Verified |
| 4 | [BUZZ](https://buzzai.cc) | cn | 🔌 | claude, gpt, gemini | one-api | card | 9.9 | 478 ms | 🟢 Verified |
| 5 | [呆呆兽中转站｜Claude、Codex、GLM、Kimi 折扣 API](https://www.ddshub.cc) | cn | 🔌 | claude, gpt, anthropic | — | alipay, wechat, card | 9.9 | 685 ms | 🟢 Verified |
| 6 | [APIMart](https://apimart.ai) | global | 🔌 | claude, gpt, gemini | one-api | wechat, card | 9.9 | 1169 ms | 🟢 Verified |
| 7 | [api.v3.cm](https://api.v3.cm) | cn | 🔌 | claude, gpt, gemini | — | — | 9.8 | 135 ms | 🟢 Verified |
| 8 | [api.v36.cm](https://api.v36.cm) | cn | 🔌 | claude, gpt, gemini | — | — | 9.8 | 136 ms | 🟢 Verified |
| 9 | [api.vveai.com](https://api.vveai.com) | cn | 🔌 | claude, gpt, gemini | — | — | 9.8 | 151 ms | 🟢 Verified |
| 10 | [api.gpt.ge](https://api.gpt.ge) | cn | 🔌 | claude, gpt, gemini | — | — | 9.8 | 240 ms | 🟢 Verified |
| 11 | [Featherless](https://featherless.ai) | global | 🔌 | gpt, openai, deepseek | one-api | — | 9.8 | 350 ms | 🟢 Verified |
| 12 | [apipro.maynor1024.live](https://apipro.maynor1024.live) | global | 🔌 | claude, gpt, gemini | — | — | 9.8 | 389 ms | 🟢 Verified |
| 13 | [ePhone AI](https://api.ephone.ai) | cn | 🔌 | claude, gpt, gemini | — | — | 9.8 | 486 ms | 🟢 Verified |
| 14 | [Yuegle API](https://api.yuegle.com) | cn | 🔌 | claude, gpt, gemini | — | — | 9.8 | 585 ms | 🟢 Verified |
| 15 | [jeniya.cn](https://jeniya.cn) | cn | 🔌 | claude, gpt, chatgpt | — | — | 9.8 | 1164 ms | 🟢 Verified |
| 16 | [便携AI聚合API](https://api.bianxieai.com) | cn | 🔌 | claude, gemini, openai | new-api | — | 9.8 | 2442 ms | 🟢 Verified |
| 17 | [api-gptgod-work](https://api.gptgod.work) | global | 🔌 | **323 models** | — | — | 9.7 | 410 ms | 🟢 Verified |
| 18 | [ggwk1.online](https://www.ggwk1.online) | cn | 🔌 | claude, gpt, gemini | new-api | — | 9.7 | 509 ms | 🟢 Verified |
| 19 | [AnyRouter · Universal AI Model Router](https://anyrouter.dev) | global | 🔌 | claude, gpt, anthropic | one-api | — | 9.7 | 895 ms | 🟢 Verified |
| 20 | [ClaudeCN](https://claudecn.top) | cn | 🔌 | claude, gpt, gemini | — | — | 9.7 | 921 ms | 🟢 Verified |
| 21 | [Aiberm](https://aiberm.com) | global | 🔌 | claude, gemini, openai | — | — | 9.6 | 107 ms | 🟢 Verified |
| 22 | [api.cursorai.art](https://api.cursorai.art) | global | 🔌 | claude, gpt, chatgpt | — | — | 9.6 | 186 ms | 🟢 Verified |
| 23 | [api-deerapi-com](https://api.deerapi.com) | cn | 🔌 | claude, gemini, openai | — | — | 9.6 | 203 ms | 🟢 Verified |
| 24 | [api.onechats.top](https://api.onechats.top) | cn | 🔌 | claude, gemini, openai | new-api | — | 9.6 | 226 ms | 🟢 Verified |
| 25 | [new.yunai.link](https://new.yunai.link) | cn | 🔌 | claude, gemini, openai | — | — | 9.6 | 247 ms | 🟢 Verified |
| 26 | [api.soruxgpt.com](https://api.soruxgpt.com) | cn | 🔌 | claude, gemini, openai | new-api | — | 9.6 | 268 ms | 🟢 Verified |
| 27 | [api-chatfire-cn](https://api.chatfire.cn) | cn | 🔌 | claude, gemini, openai | — | — | 9.6 | 488 ms | 🟢 Verified |
| 28 | [柏拉图AI_API中转站 (api.bltcy.ai)](https://api.bltcy.ai) | cn | 🔌 | claude, gpt, openai | — | — | 9.6 | 516 ms | 🟢 Verified |
| 29 | [api-mnapi-com](https://api.mnapi.com) | cn | 🔌 | claude, gemini, openai | — | — | 9.6 | 638 ms | 🟢 Verified |
| 30 | [api.aipaibox.com](https://api.aipaibox.com) | cn | 🔌 | claude, gemini, openai | new-api | — | 9.6 | 789 ms | 🟢 Verified |
| 31 | [TiMi CC](https://timicc.com) | cn | 🔌 | gpt, openai, qwen | — | wechat, card | 9.5 | 238 ms | 🟢 Verified |
| 32 | [marting.pro](https://marting.pro) | global | 🔌 | gpt, chatgpt | — | — | 9.5 | 281 ms | 🟢 Verified |
| 33 | [Doro AI](https://doro.lol) | cn | 🔌 | claude, gpt, gemini | new-api | — | 9.5 | 366 ms | 🟢 Verified |
| 34 | [comfly](https://ai.comfly.chat) | global | 🔌 | gpt, openai | — | — | 9.5 | 1762 ms | 🟢 Verified |
| 35 | [zen-ai.top](https://zen-ai.top) | cn | 🔌 | openai | — | — | 9.4 | 310 ms | 🟢 Verified |
| 36 | [API Management](https://sparkcode.top) | cn | 🔌 | openai | — | — | 9.4 | 325 ms | 🟢 Verified |
| 37 | [钱多多 API (aigcbest.top)](https://aigcbest.top) | cn | 🔌 | openai | new-api | — | 9.4 | 431 ms | 🟢 Verified |
| 38 | [GPTNB ONEAPI](https://oneapi.gptnb.ai) | cn | 🔌 | gpt | — | — | 9.4 | 533 ms | 🟢 Verified |
| 39 | [Unified API](https://unifiedapi.cloud) | cn | 🔌 | openai | — | — | 9.4 | 575 ms | 🟢 Verified |
| 40 | [钱多多 API (api.ifopen.ai)](https://api.ifopen.ai) | cn | 🔌 | openai | new-api | — | 9.4 | 579 ms | 🟢 Verified |
| 41 | [钱多多 API (api.aigcbest.top)](https://api.aigcbest.top) | cn | 🔌 | openai | new-api | — | 9.4 | 600 ms | 🟢 Verified |
| 42 | [AI302 Api (api.302ai.com)](https://api.302ai.com) | global | 🔌 | gpt | — | — | 9.4 | 617 ms | 🟢 Verified |
| 43 | [AI302 Api (api.302ai.cn)](https://api.302ai.cn) | global | 🔌 | gpt | — | — | 9.4 | 1513 ms | 🟢 Verified |
| 44 | [欢迎访问无限API](https://infai.cc) | cn | 🔌 | — | — | — | 9.3 | 123 ms | 🟢 Verified |
| 45 | [api.gemai.cc](https://api.gemai.cc) | global | 🔌 | — | new-api | — | 9.3 | 195 ms | 🟢 Verified |
| 46 | [api-gptsapi-net](https://api.gptsapi.net) | global | 🔌 | — | — | — | 9.3 | 196 ms | 🟢 Verified |
| 47 | [云雾 API (YunWu)](https://yunwu.ai) | cn | 🔌 | — | — | — | 9.3 | 218 ms | 🟢 Verified |
| 48 | [api.nekoapi.com](https://api.nekoapi.com) | global | 🔌 | — | new-api | — | 9.3 | 234 ms | 🟢 Verified |
| 49 | [OneToken](https://onetoken.one) | global | 🔌 | — | new-api | — | 9.3 | 239 ms | 🟢 Verified |
| 50 | [zerocode.sbs](https://zerocode.sbs) | global | 🔌 | — | new-api | — | 9.3 | 247 ms | 🟢 Verified |

> Top 50 shown. See [`data/_leaderboard.md`](data/_leaderboard.md) for the full list of 186 gateways.

<!-- LEADERBOARD:END -->

</details>

> 📌 **Want your gateway listed?** Open a PR with a filled [gateway template](./gateways/_template.md). We accept any provider that meets our [listing criteria](./CONTRIBUTING.md#listing-criteria).

---

## ❓ FAQ

<details>
<summary><b>What exactly is an "AI API gateway" or "中转站"?</b></summary>

A third-party service that exposes Claude, GPT, Gemini, DeepSeek, Qwen, and other frontier LLMs through a **single OpenAI-compatible HTTP API**. Most of them sit in front of the official providers and resell capacity, often at discounted prices, with friendlier payment options (WeChat/Alipay), or with extra features (rate-limit pooling, routing, logging, invoices).
</details>

<details>
<summary><b>How is this different from OpenRouter's /models page, helpaio.com, or apicompare.best?</b></summary>

- **OpenRouter** only lists gateways running inside OpenRouter's own routing graph. We list **every relay we can find**, including the dozens of small CN players.
- **helpaio.com** is a blog with human-written reviews. We publish **machine-verified data** (live `/v1/models` probes, engine fingerprints, uptime) alongside reviews.
- **apicompare.best** compares prices. We compare **reachability, authenticity, and stability** — cheaper doesn't help if the gateway disappears next week.
</details>

<details>
<summary><b>How do you decide the leaderboard score?</b></summary>

We combine: reachability (HTTP 2xx), confirmed `/v1/models` endpoint, real-model count, model-keyword density on the landing page, latency, and 30-day uptime from our daily snapshots. The formula lives in [`scripts/generate_leaderboard.py`](./scripts/generate_leaderboard.py) — no black box.
</details>

<details>
<summary><b>Is this a paid directory? Who pays you to be listed?</b></summary>

**No one.** There is zero paid placement. Listings are either auto-discovered or PR'd by the community. The repo is MIT-licensed and ad-free. If the leaderboard helped you, consider [supporting the project](#-support-this-project).
</details>

<details>
<summary><b>Can I trust the top-ranked gateways with large amounts of money?</b></summary>

**No.** This industry sees weekly rug-pulls. A high score means a gateway is *currently* reachable, has a real API, and has been stable for 30 days — **not** that it is solvent or will still be online next month. Always top up small amounts first (≤ US$2), validate model quality, and scale slowly.
</details>

<details>
<summary><b>I got scammed by a gateway. How do I report it?</b></summary>

Open a [GitHub Discussion](https://github.com/MackDing/awesome-ai-api/discussions) under the `Reports` category with public evidence (screenshots, transaction IDs, Telegram group links). Two independent reports + a 14-day operator response window = the gateway lands on [`data/blacklist.json`](./data/blacklist.json).
</details>

<details>
<summary><b>How do I add my gateway?</b></summary>

Add the URL to [`data/candidates.txt`](./data/candidates.txt), then (optionally) add a human-curated `name`, `region`, and `verdict` to [`data/sites.yaml`](./data/sites.yaml). Open a PR. The daily cron will pick it up.
</details>

<details>
<summary><b>Do you support non-OpenAI-compatible APIs (raw Anthropic, raw Gemini)?</b></summary>

We primarily probe `/v1/models` (OpenAI-compatible), because it's the lingua franca. Gateways that only expose raw Anthropic or Gemini endpoints can still be listed via `data/sites.yaml` with a `verdict: likely_relay` override and a `note` explaining the protocol.
</details>

---

## 📊 Categories

### By Target Market

- 🌍 [Global Gateways](./data/by-region.md#global) — OpenRouter, Together AI, Groq, Fireworks
- 🇨🇳 [China Gateways](./data/by-region.md#china) — Road2All, DeepBricks, AiHubMix, OhMyGPT
- 🏠 [Self-Hosted](./data/by-region.md#self-hosted) — One API, NewAPI, LiteLLM

### By Specialty

- 🤖 [Claude Code Compatible](./data/by-feature.md#claude-code) — Services fully supporting Claude Code CLI
- ⚡ [Low-Latency](./data/by-feature.md#low-latency) — Sub-500ms TTFT
- 💰 [Best-Price](./data/by-feature.md#best-price) — Discounted vs. official rates
- 🔒 [Privacy-First](./data/by-feature.md#privacy) — No data retention / on-prem

### By Payment

- 💳 [Alipay/WeChat](./data/by-payment.md#cn) — For Chinese users
- 💳 [Credit Card](./data/by-payment.md#card) — International
- ₿ [Crypto](./data/by-payment.md#crypto) — Anonymous payment support

---

## 📝 Reviews

Deep-dive reviews and benchmark reports:

- 📊 [2026 Q2 Gateway Benchmark](./reviews/2026-Q2-benchmark.md) *(coming soon)*
- 🔬 [Claude Code Gateway Shootout](./reviews/claude-code-shootout.md) *(coming soon)*
- 💸 [Price Analysis: Official vs Gateway](./reviews/pricing-analysis.md) *(coming soon)*
- 🧪 [Methodology](./reviews/methodology.md)

---

## ⚠️ Blacklist

Gateways that have been flagged for serious issues (rug-pulls, data leaks, fake models).

See [blacklist.md](./data/blacklist.md) for the current list and evidence archive.

> If you've been affected, please open a GitHub Discussion with evidence. We review reports transparently.

---

## 🧪 Benchmark

We run periodic benchmarks testing:

- **Latency** (TTFT, total response time)
- **Throughput** (tokens/sec)
- **Reliability** (uptime %)
- **Accuracy** (model behavior matches official?)
- **Pricing consistency** (quoted vs. billed)

See [`scripts/benchmark.py`](./scripts/benchmark.py) for the test harness. Results in [`data/benchmarks/`](./data/benchmarks/).

---

## 🤝 Contributing

We welcome PRs from users, gateway operators, and researchers. See [CONTRIBUTING.md](./CONTRIBUTING.md).

**Quick ways to help:**
- ✏️ Update a gateway's pricing or model list
- 📝 Submit a new gateway (use the [template](./gateways/_template.md))
- 🚨 Report a scam or outage
- 🧪 Submit benchmark data
- 🌐 Improve translations

---

## 📜 License

Content is released under the [MIT License](./LICENSE). Attribution appreciated but not required.

---

## 🙏 Acknowledgments

Inspired by [apicompare.best](https://apicompare.best), [helpaio.com/transit](https://www.helpaio.com/transit), and [trustmrr.com](https://trustmrr.com) — each taught us one piece of the puzzle: **price data, content depth, and verified trust**. We combine them with GitHub-native openness.

---

<p align="center">
  <em>Built by <a href="https://github.com/MackDing">Mack Ding</a> and contributors · Made for the global OPC community</em>
</p>


---

## 🦞 OPC Ecosystem

> Built by [@MackDing](https://github.com/MackDing) — One-Person Company infrastructure powered by AI agents.

| Project | What it does |
|---------|-------------|
| [**opc.ren**](https://opc.ren) | OPC founder hub — tools, signals, community |
| [**CodexClaw**](https://github.com/MackDing/CodexClaw) | Telegram bot for remote Codex access with MCP + subagent routing |
| [**awesome-ai-api**](https://github.com/MackDing/awesome-ai-api) | Leaderboard of 200+ AI API gateways & relays |
| [**claude-context-health**](https://github.com/MackDing/claude-context-health) | Diagnose & fix Claude Code session degradation |
| [**opc-daily-signal**](https://github.com/MackDing/opc-daily-signal) | AI-powered daily decision intelligence for OPC founders |
| [**doc-preprocess-hub**](https://github.com/MackDing/doc-preprocess-hub) | Enterprise document preprocessing — MinerU + docling |
