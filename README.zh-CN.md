# Awesome Muse 中文精选

> [Muse](https://muse.ai)（Meta 个人 AI 助手）生态资源的中英双语精选集 —— skills、connectors、prompts、workflow，每条都附带实测点评。
>
> [English](README.md) · [贡献指南](CONTRIBUTING.zh-CN.md)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.zh-CN.md)

Muse 于 2026-09-08 发布，社区生态增长迅速。和纯链接列表不同，这里的每条收录都带有一句实测点评：它是做什么的、适合谁、有没有什么坑。下面 star 数为 2026-10-09 实测。

## 目录

- [官方项目](#官方项目)
- [Awesome 列表](#awesome-列表)
- [Skills 技能](#skills-技能)
- [Connectors 连接器](#connectors-连接器)
- [Gadgets 硬件小部件](#gadgets-硬件小部件)
- [Prompts 与用例](#prompts-与用例)
- [开发工具 / CLI](#开发工具--cli)
- [评测与基准](#评测与基准)
- [空白与机会](#空白与机会)
- [参与贡献](#参与贡献)

## 官方项目

- [facebookincubator/muse-gadget-sdk](https://github.com/facebookincubator/muse-gadget-sdk) —— Meta 官方 SDK：自制硬件小部件（ESP32/Linux）接入 Muse。⭐1798 且增长迅猛 · Apache-2.0

## Awesome 列表

- [anil-matcha/awesome-muse-connectors](https://github.com/anil-matcha/awesome-muse-connectors) —— 150+ 社区 connector skills + 官方集成目录 + 13 个 agent workflow 模板。社区 star 最高。⭐1345
- [aicodedecode/awesome-muse-skills](https://github.com/aicodedecode/awesome-muse-skills) —— 2384 个 skills（899 原创 + 1485 精选转载），配套可搜索网站。⭐10
- [cszach/awesome-muse](https://github.com/cszach/awesome-muse) —— 指南、用例、工具、新闻 12 个板块的策展列表，更新勤快。⭐6

## Skills 技能

- [jacobwell/muse-skills](https://github.com/jacobwell/muse-skills) —— Muse 内置 72 个 skills 的可读复刻 playbook + system prompt 复述。⚠️ 逆向工程所得，未经官方证实。⭐8
- [pjpoulose/PIL](https://github.com/pjpoulose/PIL) —— 可安装 skill：把 Instagram 收藏帖子变成私人可检索知识库。⭐1
- [JustinAllen03-stack/muse-imprint](https://github.com/justinallen03-stack/muse-imprint) —— 趣味 skill：给朋友的 Muse「盖章」语音印记（需对方同意，会逐渐消退）。⭐1
- [GMAn0n/muse-linkedin-skill](https://github.com/GMAn0n/muse-linkedin-skill) —— 即插即用的 LinkedIn 技能：在 Muse 里发帖、读自己的资料。⭐0 · 新增

## Connectors 连接器

- [dkm90x/muse-mac-connector](https://github.com/dkm90x/muse-mac-connector) —— macOS 菜单栏桥接：经你批准后执行 25 个本地动作（文件、终端、截屏等），经 Cloudflare 隧道通信。⭐0
- [NeedsChloesure/muse-proxy](https://github.com/NeedsChloesure/muse-proxy) —— Cloudflare Worker 做的 API-key 网关，自建 CalDAV/CardDAV 不用存明文密码。⭐0
- [camirian/agent-connector-launch-kit](https://github.com/camirian/agent-connector-launch-kit) —— 为 Muse 构建 OpenAPI connector 的 starter kit，含一次真实提审经验。⭐0
- [1clawAI/muse-connector](https://github.com/1clawAI/muse-connector) —— 把 1Claw 的审批队列、钱包、活动日志接进 Muse。⭐1
- [yahavf6/muse-brain](https://github.com/yahavf6/muse-brain) —— 跨 agent 共享决策图谱，Muse 经 REST custom connector 接入（实验性）。⚠️ 非商业许可。⭐11
- [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) —— 跨 AI 工具的记忆层，Muse 以远程 MCP custom connector 接入。⭐47314 · 它的 star 主要来自更广泛的 agent-memory 受众
- [linboxin/nexus-mcp](https://github.com/linboxin/nexus-mcp) —— 通用 MCP 服务器，Muse 可作为 custom client 接入。⭐1
- [maddivikash/auto-apply](https://github.com/maddivikash/auto-apply) —— 求职自动投递工具；其文档是「如何做 Muse connector」的完整参考实现（Clerk OAuth 2.1 + PKCE）。⭐1
- [GkhanKINAY/postqueen-docs](https://github.com/GkhanKINAY/postqueen-docs) —— 文档站，演示 Muse 如何经 custom connector 写帖/排期。⭐1
- [racstan/pi-muse-connector](https://github.com/racstan/pi-muse-connector) —— 树莓派 ↔ Muse 的托管 REST API 桥接。⭐0 · 新增
- [0xBrsm/musebox](https://github.com/0xBrsm/musebox) —— Linux 机器与 Muse 之间的纯文件传输桥。⭐0 · 新增

## Gadgets 硬件小部件

基于 Meta gadget SDK 的社区硬件移植与构建。

- [youlim-bot/MUSE-Gadget-for-Rabbit-r1](https://github.com/youlim-bot/MUSE-Gadget-for-Rabbit-r1) —— 社区把 Muse gadget SDK 移植到 Rabbit r1（LineageOS + Android 应用）。⭐2 · 新增
- [leungcheukfai/muse-gadget-zh-hant](https://github.com/leungcheukfai/muse-gadget-zh-hant) —— 繁体中文社区版 ESP32 gadget SDK：中文界面、语音回复、网页一键烧录。⭐0 · 新增
- [nobaksan/stackchan-muse](https://github.com/nobaksan/stackchan-muse) —— 把 M5Stack StackChan 机器人做成 Muse 小部件，含颈部舵机语音指令。⭐0 · 新增
- [burndown/muse-gadget-cloud](https://github.com/burndown/muse-gadget-cloud) —— ESP32 Muse 小部件 + Cloudflare Worker 网关方案。⭐0 · 新增

## Prompts 与用例

- [everyai-com/muse-use-cases](https://github.com/everyai-com/muse-use-cases) —— 真实用例田野指南：351 个用例、257 个附完整原始 prompt，另有一份可一次性粘贴的 capability pack。⚠️ 活跃度疑似偏低。⭐2
- [freeflow-community/skill-explorer](https://github.com/freeflow-community/skill-explorer) —— 网页版个人助手 prompts 浏览器（含 Muse 板块），通过 GitHub issue 征集新 prompt。⭐3
- [styrigx/muse-playbook](https://github.com/styrigx/muse-playbook) —— 501 条中文 Muse 实用技巧与真实用例，十大分类整理。⭐0 · 新增
- [doforu-labs/muse-agent-guide](https://github.com/doforu-labs/muse-agent-guide) —— 30+ 可直接复制的 Muse 使用食谱与 workflow 模板。⭐0 · 新增

## 开发工具 / CLI

- [duclm1x1/Muse-Chat-MCP](https://github.com/duclm1x1/Muse-Chat-MCP) —— 用 Playwright 驱动已登录的 Chrome，把 muse.ai 变成 MCP server + OpenAI 兼容接口 + CLI。⚠️ 可能违反 Meta ToS。⭐49
- [kevintsai1202/muse-image-mcp](https://github.com/kevintsai1202/muse-image-mcp) —— 社区 MCP server：经 Meta Model API 调用 Muse 图像模型（给开发者在 Claude Code/Cursor 里用，非 Muse 用户工具）。⭐0
- [cszach/calliope](https://github.com/cszach/calliope) —— 非官方 muse.ai GNOME 桌面客户端（WebKitGTK）。⭐0 · 新增
- [drumpat01/muse-chat](https://github.com/drumpat01/muse-chat) —— 非官方聊天客户端，带动态虚拟形象（Linux/Windows）。⭐0 · 新增
- [buzhidaosm/muse-cli-bridge](https://github.com/buzhidaosm/muse-cli-bridge) —— muse.ai 命令行桥接：Keychain 登录、MCP、双向任务桥。⭐0 · 新增
- [whxjwksjs/muse-windows](https://github.com/whxjwksjs/muse-windows) —— muse.ai 的 Windows Electron 桌面封装。⭐0 · 新增

## 评测与基准

- [dpawlan/ai-assistant-benchmark](https://github.com/dpawlan/ai-assistant-benchmark) —— 公开记分牌（Wirecutter 风格）：40 个助手 × 15 个维度，含 Muse 档案页。⭐2
- [ultrametricai/ultrametric](https://github.com/ultrametricai/ultrametric) —— 产品竞技场：Muse 在个人 AI 助手赛道排 #8/9（PA 7.6）。⭐4 · 已由 productarena 改名
- [mahdi-salmanzade/meta-muse-teardown](https://github.com/mahdi-salmanzade/meta-muse-teardown) —— Muse 客户端的静态隐私分析，附证据与复现脚本（独立安全研究）。⭐4

## 空白与机会

目前覆盖缺失、值得做或值得贡献的方向：

- **Subagents** —— Muse 未向用户暴露 subagent 自定义机制，社区零模板，完全空白。
- **资讯 / 更新聚合** —— 没有 Muse 专属的 newsletter 或版本更新追踪器。
- **系统性评测** —— 没有 Muse 专属的能力/安全基准（dpawlan 的通用框架值得借鉴）。
- **垂直行业 workflow 包** —— 通用模板已多，医疗/法律/教育等深度场景缺失。
- **Skill 分发机制** —— Meta 已宣布 SMB skills（2026-09-29）但尚无安装/商店流程，社区 skill 只能靠粘贴安装。

## 参与贡献

欢迎贡献！请先阅读[贡献指南](CONTRIBUTING.zh-CN.md)，里面有条目模板和审核规则。

## 许可证

[MIT](LICENSE)
