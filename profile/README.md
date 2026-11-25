**All repos including MIT ones are temporarly private while i reorg the team**  

_Probably tohse repo will remain all private and most suitable repo will be created for the different (CE) Community EditionS_

---

We build an AI-driven, blockchain-assisted ecosystem for international sales—from informal microentrepreneurs to mid-sized LatAm businesses. Our first verticals are Paraguayan social commerce expanding across LatAm and property developers targeting foreign investors.

Payments settle on Bitcoin. USDT runs on Bitcoin via RGB first, with Arkade next for instant payments and 2-of-3 escrow. Fiat and stablecoins on other chains stay available as optional rails. The buyer can also be an AI agent: our checkouts and payout rails speak HTTP 402 (L402 over Lightning, x402 for stablecoins), with no checkout page and no human in the loop.

A self-custodial BTC and  (RGB/Spark) stablecoin wallet and a version-controlled knowledge graph orchestrate modular payment rails, AI agents, and self-evolving skills. Every decision and document is signed and timestamped on Bitcoin with OpenTimestamps. The core and most plugins are MIT-licensed. The cloud platform and selected plugins are proprietary.

We build on top of well-maintained open-source software:
Tether WDK, USDB on Spark, RGB and BTCPay Greenfield API for `/pay`.  
Pi Coding Agent, Vercel AI SDK, Markdown Self-Improving Skills, and System One model—discriminative AI for `/ai`.
Nuxt Content, NuxtMDC, a customized version of Graphify for long-term and privacy-oriented contexts for the team and the agents.
Cryptomator and Seafile for files and private repos and Nuxt Content Assets for `/space`.

---

<!--more--> 

**LEGACY Brand ARA.PEAHA.AI is now MBOTYHA and obsolete Stack**
  
# Ára Pe'aha Aĩ

**One key. Your money, your knowledge, your AI.**

Self-custodial payment and AI tools for businesses in emerging markets, starting in Paraguay.

The same rule drives both: whoever holds the key holds the asset. In payments, the seed holds the funds. In AI, the company's knowledge stays in its own git repo, and model vendors are meant to see one isolated task at a time, never the whole.

---

## Two stacks, two servers

Each stack runs in Docker on its own VPS. Both can be self-hosted.

| Stack | What it does | Repos |
|-------|--------------|-------|
| **PAY** | Multi-rail inbound payments (Bitcoin, stablecoins, P2P and fiat rails) with self-custodial settlement, on top of BTCPay Server | [/pay](https://github.com/ara-peaha-ai/pay) (MIT) |
| **AI** | Company memory as Markdown in git, a knowledge graph of it (testing), and a CPU router (planned) that sends each task to commercial or self-hosted models with only the context that task needs | [/os](https://github.com/ara-peaha-ai/os) (MIT engine) + content (private memory) |

Architecture, rails, and roadmap for PAY: [pay README](https://github.com/ara-peaha-ai/pay#readme).
The AI model, markers, and router: [os README](https://github.com/ara-peaha-ai/os#readme).

---

## Principles

- **Self-custodial by default**: funds and knowledge never sit with a platform
- **Agnostic in practice**: the usable rail or model matters more than ideology
- **Modular**: rails, services, and models can be enabled or left out per use case
- **Open source**: public components are MIT; a paid closed-source offering funds their long-term maintenance
- **Dogfooded**: the company building this runs on it every day

---

## Community & Contact

- [ara.peaha.ai](https://ara.peaha.ai) · [ara@peaha.ai](mailto:ara@peaha.ai)
- [GitHub Discussions](https://github.com/orgs/ara-peaha-ai/discussions)
- [Signal in Spanish](https://signal.group/#CjQKINeqtWYuRXjYo9GtrlCEOWMJ2nWQXNG6iyds3wrRYxooEhD6gXXKAHllZUT53I5Lsxbh)
- [Signal in Portuguese](https://signal.group/#CjQKIG98LmLuz2PTC6sfsmCqDSPcfr-K2Ik3f7jzBZxBgnHtEhCvxiDfadchzN5SsVX80uBC)
