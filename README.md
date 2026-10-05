# Awesome Muse CN

> A curated, bilingual collection of [Muse](https://muse.ai) (Meta's personal AI assistant) ecosystem resources — skills, connectors, prompts, workflows — each with a hands-on note.
>
> [中文版](README.zh-CN.md) · [Contributing](CONTRIBUTING.md)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

Muse launched on 2026-09-08 and its community ecosystem is growing fast. Unlike link-only lists, every entry here carries a one-line hands-on note: what it does, who it's for, and any caveats. Star counts below were verified on 2026-10-05.

## Contents

- [Official](#official)
- [Awesome Lists](#awesome-lists)
- [Skills](#skills)
- [Connectors](#connectors)
- [Prompts & Use Cases](#prompts--use-cases)
- [Dev Tools & CLI](#dev-tools--cli)
- [Evals & Benchmarks](#evals--benchmarks)
- [Gaps & Opportunities](#gaps--opportunities)
- [Contributing](#contributing)

## Official

- [facebookincubator/muse-gadget-sdk](https://github.com/facebookincubator/muse-gadget-sdk) — Meta's official SDK for DIY hardware gadgets (ESP32/Linux) that connect to Muse. ⭐1198 in 3 days · Apache-2.0

## Awesome Lists

- [anil-matcha/awesome-muse-connectors](https://github.com/anil-matcha/awesome-muse-connectors) — 150+ community connector skills + official integration directory + 13 agent workflow templates. Highest-starred community repo. ⭐1312
- [aicodedecode/awesome-muse-skills](https://github.com/aicodedecode/awesome-muse-skills) — 2,384 skills (899 original + 1,485 curated third-party) with a searchable site. ⭐10
- [cszach/awesome-muse](https://github.com/cszach/awesome-muse) — Curated guides, use cases, tools and news across 12 sections; actively maintained. ⭐3

## Skills

- [jacobwell/muse-skills](https://github.com/jacobwell/muse-skills) — Readable playbook replica of Muse's 72 built-in skills + retold system prompt. ⚠️ Reverse-engineered, unverified. ⭐8
- [pjpoulose/PIL](https://github.com/pjpoulose/PIL) — Installable skill turning Instagram saved posts into a private searchable knowledge base. ⭐1
- [JustinAllen03-stack/muse-imprint](https://github.com/justinallen03-stack/muse-imprint) — Fun skill: stamp a voice "imprint" on a friend's Muse (consensual, fades over time). ⭐1

## Connectors

- [dkm90x/muse-mac-connector](https://github.com/dkm90x/muse-mac-connector) — macOS menu-bar bridge: 25 local actions (files, terminal, screenshots…) run after your approval via Cloudflare tunnel. ⭐0
- [NeedsChloesure/muse-proxy](https://github.com/NeedsChloesure/muse-proxy) — Cloudflare Worker API-key gateway for self-hosted CalDAV/CardDAV, no plaintext passwords. ⭐0
- [camirian/agent-connector-launch-kit](https://github.com/camirian/agent-connector-launch-kit) — Starter kit for building OpenAPI connectors, with notes from a real Muse directory submission. ⭐0
- [1clawAI/muse-connector](https://github.com/1clawAI/muse-connector) — Puts 1Claw's approval queue, wallet and activity log inside Muse. ⭐1
- [yahavf6/muse-brain](https://github.com/yahavf6/muse-brain) — Shared decision graph across agents; Muse joins via REST custom connector (experimental). ⚠️ Non-commercial license. ⭐11
- [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) — Cross-AI-tool memory layer; Muse connects via remote MCP as a custom connector. Star count unverified.
- [linboxin/nexus-mcp](https://github.com/linboxin/nexus-mcp) — Generic MCP server that Muse can integrate with as a custom client. Star count unverified.
- [maddivikash/auto-apply](https://github.com/maddivikash/auto-apply) — Job auto-apply tool; its docs are a complete reference for building a Muse connector (Clerk OAuth 2.1 + PKCE). Star count unverified.
- [GkhanKINAY/postqueen-docs](https://github.com/GkhanKINAY/postqueen-docs) — Docs showing how Muse writes/schedules posts via a custom connector. Star count unverified.

## Prompts & Use Cases

- [everyai-com/muse-use-cases](https://github.com/everyai-com/muse-use-cases) — Field guide: 351 real use cases, 257 with full original prompts, plus a paste-in capability pack. ⚠️ Low activity. ⭐2
- [freeflow-community/skill-explorer](https://github.com/freeflow-community/skill-explorer) — Web app for browsing personal-agent prompts incl. a Muse section; new prompts via GitHub issues. ⭐3

## Dev Tools & CLI

- [duclm1x1/Muse-Chat-MCP](https://github.com/duclm1x1/Muse-Chat-MCP) — Drives a logged-in Chrome via Playwright to expose muse.ai as an MCP server + OpenAI-compatible shim + CLI. ⚠️ May violate Meta ToS. ⭐38
- [kevintsai1202/muse-image-mcp](https://github.com/kevintsai1202/muse-image-mcp) — Community MCP server calling Muse image models via Meta Model API (for developers, not Muse users). Star count unverified.

## Evals & Benchmarks

- [dpawlan/ai-assistant-benchmark](https://github.com/dpawlan/ai-assistant-benchmark) — Public Wirecutter-style scoreboard: 40 assistants × 15 dimensions, incl. a Muse profile. ⭐2
- [ultrametricai/productarena](https://github.com/ultrametricai/productarena) — Product arena; Muse ranks #8/9 among personal AI assistants (PA 7.6). Star count unverified.
- [mahdi-salmanzade/meta-muse-teardown](https://github.com/mahdi-salmanzade/meta-muse-teardown) — Static privacy teardown of Muse clients, with evidence and repro scripts (independent security research). ⭐2

## Gaps & Opportunities

Areas with no (or no good) coverage yet — good places to contribute or build:

- **Subagents** — Muse exposes no subagent customization mechanism; zero community templates exist.
- **News / changelog aggregator** — no Muse-specific newsletter or update tracker.
- **Systematic evals** — no Muse-specific capability or safety benchmark (dpawlan's general framework is a good starting point).
- **Vertical workflow packs** — generic templates exist; deep packs for healthcare, law, education, etc. don't.
- **Skill distribution** — Meta announced SMB skills (2026-09-29) but there's still no install/store flow; community skills are paste-to-install.

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) first — it has the entry template and review rules.

## License

[MIT](LICENSE)
