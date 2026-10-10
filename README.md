# Awesome Muse CN

> A curated, bilingual collection of [Muse](https://muse.ai) (Meta's personal AI assistant) ecosystem resources — skills, connectors, prompts, workflows — each with a hands-on note.
>
> [中文版](README.zh-CN.md) · [Contributing](CONTRIBUTING.md)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

Muse launched on 2026-09-08 and its community ecosystem is growing fast. Unlike link-only lists, every entry here carries a one-line hands-on note: what it does, who it's for, and any caveats. Star counts below were verified on 2026-10-10.

## Contents

- [Official](#official)
- [Awesome Lists](#awesome-lists)
- [Skills](#skills)
- [Connectors](#connectors)
- [Gadgets](#gadgets)
- [Prompts & Use Cases](#prompts--use-cases)
- [Dev Tools & CLI](#dev-tools--cli)
- [Evals & Benchmarks](#evals--benchmarks)
- [Gaps & Opportunities](#gaps--opportunities)
- [Contributing](#contributing)

## Official

- [facebookincubator/muse-gadget-sdk](https://github.com/facebookincubator/muse-gadget-sdk) — Meta's official SDK for DIY hardware gadgets (ESP32/Linux) that connect to Muse. ⭐1899 and climbing fast · Apache-2.0

## Awesome Lists

- [anil-matcha/awesome-muse-connectors](https://github.com/anil-matcha/awesome-muse-connectors) — 150+ community connector skills + official integration directory + 13 agent workflow templates. Highest-starred community repo. ⭐1347
- [aicodedecode/awesome-muse-skills](https://github.com/aicodedecode/awesome-muse-skills) — 2,384 skills (899 original + 1,485 curated third-party) with a searchable site. ⭐12
- [cszach/awesome-muse](https://github.com/cszach/awesome-muse) — Curated guides, use cases, tools and news across 12 sections; actively maintained. ⭐8

## Skills

- [jacobwell/muse-skills](https://github.com/jacobwell/muse-skills) — Readable playbook replica of Muse's 72 built-in skills + retold system prompt. ⚠️ Reverse-engineered, unverified. ⭐8
- [pjpoulose/PIL](https://github.com/pjpoulose/PIL) — Installable skill turning Instagram saved posts into a private searchable knowledge base. ⭐1
- [JustinAllen03-stack/muse-imprint](https://github.com/justinallen03-stack/muse-imprint) — Fun skill: stamp a voice "imprint" on a friend's Muse (consensual, fades over time). ⭐1
- [GMAn0n/muse-linkedin-skill](https://github.com/GMAn0n/muse-linkedin-skill) — Drop-in LinkedIn skill for Muse: publish posts and read your profile. ⭐0 · new
- [svenkatreddy/universal-video-skills](https://github.com/svenkatreddy/universal-video-skills) — Vendor-neutral AI video-production skill pack in Agent Skills format (prompt craft, cinematic direction, storyboarding, character consistency, QA); works with Muse among others. ⭐2 · new
- [nanbada/muse-creative-skills](https://github.com/nanbada/muse-creative-skills) — SKILL.md packs for image/video production: phone-shot realism, pose references, editorial posters, vertical video prompters. ⭐0 · new
- [RobertDeRose/muse-atlassian-skill](https://github.com/RobertDeRose/muse-atlassian-skill) — Workspace skills giving Muse Jira and Confluence access: search, read, create and update from chat. ⭐0

## Connectors

- [dkm90x/muse-mac-connector](https://github.com/dkm90x/muse-mac-connector) — macOS menu-bar bridge: 25 local actions (files, terminal, screenshots…) run after your approval via Cloudflare tunnel. ⭐1
- [NeedsChloesure/muse-proxy](https://github.com/NeedsChloesure/muse-proxy) — Cloudflare Worker API-key gateway for self-hosted CalDAV/CardDAV, no plaintext passwords. ⭐0
- [camirian/agent-connector-launch-kit](https://github.com/camirian/agent-connector-launch-kit) — Starter kit for building OpenAPI connectors, with notes from a real Muse directory submission. ⭐1
- [1clawAI/muse-connector](https://github.com/1clawAI/muse-connector) — Puts 1Claw's approval queue, wallet and activity log inside Muse. ⭐1
- [yahavf6/muse-brain](https://github.com/yahavf6/muse-brain) — Shared decision graph across agents; Muse joins via REST custom connector (experimental). ⚠️ Non-commercial license. ⭐11
- [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) — Cross-AI-tool memory layer; Muse connects via remote MCP as a custom connector. ⭐47727 · stars reflect its wider agent-memory audience
- [linboxin/nexus-mcp](https://github.com/linboxin/nexus-mcp) — Generic MCP server that Muse can integrate with as a custom client. ⭐1
- [maddivikash/auto-apply](https://github.com/maddivikash/auto-apply) — Job auto-apply tool; its docs are a complete reference for building a Muse connector (Clerk OAuth 2.1 + PKCE). ⭐1
- [GkhanKINAY/postqueen-docs](https://github.com/GkhanKINAY/postqueen-docs) — Docs showing how Muse writes/schedules posts via a custom connector. ⭐1
- [racstan/pi-muse-connector](https://github.com/racstan/pi-muse-connector) — Hosted REST API bridging Meta Muse with a Raspberry Pi. ⭐0 · new
- [0xBrsm/musebox](https://github.com/0xBrsm/musebox) — Files-only drop box between a Linux machine and your Muse. ⭐0 · new
- [MehediHasan27/court-connector-demo](https://github.com/MehediHasan27/court-connector-demo) — MCP server template letting Muse book courts at a venue (clone → YAML venue → deploy → submit to the Muse directory). ⚠️ Docs/demo free, source is a paid template. ⭐0 · new
- [harris-ryder/dowser](https://github.com/harris-ryder/dowser) — Read-only MCP connector that finds the money hiding in your life; works with Muse and other agents. ⭐0
- [ManasDasri/hark-call](https://github.com/ManasDasri/hark-call) — Phone-call reminders for AI assistants (Muse, Hark, Grok), serverless via Google Apps Script + Twilio. ⭐0 · new

## Gadgets

Community hardware ports and builds on top of Meta's gadget SDK.

- [youlim-bot/MUSE-Gadget-for-Rabbit-r1](https://github.com/youlim-bot/MUSE-Gadget-for-Rabbit-r1) — Community port of the Muse gadget SDK to Rabbit r1 (LineageOS + Android app). ⭐3 · new
- [leungcheukfai/muse-gadget-zh-hant](https://github.com/leungcheukfai/muse-gadget-zh-hant) — Traditional-Chinese community edition of the ESP32 gadget SDK: Chinese UI, voice replies, one-click web flashing. ⭐1 · new
- [nobaksan/stackchan-muse](https://github.com/nobaksan/stackchan-muse) — M5Stack StackChan robot as a Muse gadget, with neck-servo voice commands. ⭐0 · new
- [burndown/muse-gadget-cloud](https://github.com/burndown/muse-gadget-cloud) — ESP32 Muse gadgets behind a Cloudflare Worker gateway. ⭐0 · new
- [viticci/muse-pocket](https://github.com/viticci/muse-pocket) — E-paper Muse companion for the Xteink X4 Pro e-reader: shows your Muse's character and live status, built on the Gadget SDK. ⭐54
- [samyeei/Muse-charm-mosaico](https://github.com/samyeei/Muse-charm-mosaico) — Voice AI companion on ESP-Mosaico hardware: push-to-talk, eight animated character states, Muse-generated personas. ⭐12
- [wobsoriano/muse-gadget-psp](https://github.com/wobsoriano/muse-gadget-psp) — Muse running natively on a Sony PSP: hold R to talk, replies on screen and out loud; C port of the Gadget SDK (needs PSP-3000 + custom firmware). ⭐7
- [wupsbr/waveshare-muse-gadget-sdk](https://github.com/wupsbr/waveshare-muse-gadget-sdk) — Gadget SDK on three Waveshare ESP32-S3 boards (LCD/AMOLED): spoken replies via ElevenLabs, touch volume, battery level. ⭐7
- [vocino/muse-arr](https://github.com/vocino/muse-arr) — Talk to your Sonarr/Radarr/Jellyfin media stack from Muse: a Linux gadget on your home LAN that queues movies and shows without SSH. ⭐5
- [cameronapak/muse-r1](https://github.com/cameronapak/muse-r1) — Resurrect a Rabbit r1 as a push-to-talk Muse gadget: native Android Home app on LineageOS 21, with full build docs and rollback notes. ⭐4
- [hypery11/muse-gadget-everywhere](https://github.com/hypery11/muse-gadget-everywhere) — Open-source Android runtime turning phones, tablets and TVs into programmable Muse gadgets: display, media, voice, camera, local automation. ⭐3
- [moerdowo/muse-gadget-xiaozhi](https://github.com/moerdowo/muse-gadget-xiaozhi) — Muse's gadget UI (pixel character, push-to-talk, captions) running on xiaozhi.me ESP32-S3 voice-AI hardware. ⭐0
- [Josh-Archer/homeassistant-addon-muse-gadget](https://github.com/Josh-Archer/homeassistant-addon-muse-gadget) — Home Assistant add-on that bridges Meta Muse via the Gadget SDK. ⭐2
- [burndown/luci-muse-gadget](https://github.com/burndown/luci-muse-gadget) — Runs the Gadget SDK Linux client on OpenWrt routers with a LuCI page, so your router shows up as a Muse gadget. ⭐0
- [ledienbien-ai/muse-gadget-sdk](https://github.com/ledienbien-ai/muse-gadget-sdk) — Unofficial Gadget SDK fork adding ESP32-S3 boards upstream doesn't support, with Vietnamese/English on-screen UI, spoken replies and a web flasher. ⭐2
- [dsmelvin/muse-gadget-sdk-macos](https://github.com/dsmelvin/muse-gadget-sdk-macos) — "macOS Device SDK": turns a Mac into a Muse gadget via native CoreBluetooth — pair with the Muse app to run commands and move files. ⭐0 · new
- [NajiaP/muse-gadget-state-bridge](https://github.com/NajiaP/muse-gadget-state-bridge) — Plain-text state bridge for the Gadget SDK simulator: an agent writes a state file, a watcher relaunches the simulator as a borderless desktop pet showing live face/caption/progress. ⭐0 · new

## Prompts & Use Cases

- [everyai-com/muse-use-cases](https://github.com/everyai-com/muse-use-cases) — Field guide: 351 real use cases, 257 with full original prompts, plus a paste-in capability pack. ⚠️ Low activity. ⭐2
- [freeflow-community/skill-explorer](https://github.com/freeflow-community/skill-explorer) — Web app for browsing personal-agent prompts incl. a Muse section; new prompts via GitHub issues. ⭐3
- [styrigx/muse-playbook](https://github.com/styrigx/muse-playbook) — 501 practical Muse tips and real use cases in Chinese, organized into 10 categories. ⭐0 · new
- [doforu-labs/muse-agent-guide](https://github.com/doforu-labs/muse-agent-guide) — 30+ ready-to-copy Muse usage recipes and workflow templates. ⭐0 · new

## Dev Tools & CLI

- [duclm1x1/Muse-Chat-MCP](https://github.com/duclm1x1/Muse-Chat-MCP) — Drives a logged-in Chrome via Playwright to expose muse.ai as an MCP server + OpenAI-compatible shim + CLI. ⚠️ May violate Meta ToS. ⭐50
- [kevintsai1202/muse-image-mcp](https://github.com/kevintsai1202/muse-image-mcp) — Community MCP server calling Muse image models via Meta Model API (for developers, not Muse users). ⭐0
- [cszach/calliope](https://github.com/cszach/calliope) — Unofficial GNOME desktop client for muse.ai on WebKitGTK. ⭐0 · new
- [drumpat01/muse-chat](https://github.com/drumpat01/muse-chat) — Unofficial chat client with an animated avatar (Linux + Windows). ⭐0 · new
- [buzhidaosm/muse-cli-bridge](https://github.com/buzhidaosm/muse-cli-bridge) — Muse CLI for muse.ai: Keychain login, MCP support, bidirectional task bridge. ⭐0 · new
- [whxjwksjs/muse-windows](https://github.com/whxjwksjs/muse-windows) — Windows desktop wrapper for muse.ai (Electron app). ⭐0 · new
- [bynne2602/museflow](https://github.com/bynne2602/museflow) — Visual node-based browser extension that drives image/video generation with your signed-in muse.ai session: canvas workflows + timeline clip assembly. ⭐14 · new
- [lucaisgrowing/muse-switcher](https://github.com/lucaisgrowing/muse-switcher) — Chrome MV3 extension for one-click switching between multiple muse.ai accounts (snapshots/restores login state, skips re-OTP). ⭐0 · new
- [BlueSkyz-Labs/muse-auto-allow](https://github.com/BlueSkyz-Labs/muse-auto-allow) — Chrome MV3 extension that auto-clicks Allow on muse.ai approval cards, plus a round-robin follow-up prompt library. ⚠️ Bypasses Muse's approval UX — use with judgment. ⭐0 · new

## Evals & Benchmarks

- [dpawlan/ai-assistant-benchmark](https://github.com/dpawlan/ai-assistant-benchmark) — Public Wirecutter-style scoreboard: 40 assistants × 15 dimensions, incl. a Muse profile. ⭐2
- [ultrametricai/ultrametric](https://github.com/ultrametricai/ultrametric) — Product arena; Muse ranks #8/9 among personal AI assistants (PA 7.6). ⭐4 · renamed from productarena
- [mahdi-salmanzade/meta-muse-teardown](https://github.com/mahdi-salmanzade/meta-muse-teardown) — Static privacy teardown of Muse clients, with evidence and repro scripts (independent security research). ⭐4

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
