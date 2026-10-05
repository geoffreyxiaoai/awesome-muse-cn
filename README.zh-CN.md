# Awesome Muse 中文精选

> [Muse](https://muse.ai)（Meta 个人 AI 助手）生态资源的中英双语精选集 —— skills、connectors、prompts、workflow，每条都附带实测点评。
>
> [English](README.md) · [贡献指南](CONTRIBUTING.zh-CN.md)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.zh-CN.md)

Muse 于 2026-09-08 发布，社区生态增长迅速。和纯链接列表不同，这里的每条收录都带有一句实测点评：它是做什么的、适合谁、有没有什么坑。下面 star 数为 2026-10-05 实测。

## 目录

- [官方项目](#官方项目)
- [Awesome 列表](#awesome-列表)
- [Skills 技能](#skills-技能)
- [Connectors 连接器](#connectors-连接器)
- [Prompts 与用例](#prompts-与用例)
- [开发工具 / CLI](#开发工具--cli)
- [评测与基准](#评测与基准)
- [空白与机会](#空白与机会)
- [参与贡献](#参与贡献)

## 官方项目

- [facebookincubator/muse-gadget-sdk](https://github.com/facebookincubator/muse-gadget-sdk) —— Meta 官方 SDK：自制硬件小部件（ESP32/Linux）接入 Muse。发布 3 天即 ⭐1198 · Apache-2.0

## Awesome 列表

- [anil-matcha/awesome-muse-connectors](https://github.com/anil-matcha/awesome-muse-connectors) —— 150+ 社区 connector skills + 官方集成目录 + 13 个 agent workflow 模板。社区 star 最高。⭐1312
- [aicodedecode/awesome-muse-skills](https://github.com/aicodedecode/awesome-muse-skills) —— 2384 个 skills（899 原创 + 1485 精选转载），配套可搜索网站。⭐10
- [cszach/awesome-muse](https://github.com/cszach/awesome-muse) —— 指南、用例、工具、新闻 12 个板块的策展列表，更新勤快。⭐3

## Skills 技能

- [jacobwell/muse-skills](https://github.com/jacobwell/muse-skills) —— Muse 内置 72 个 skills 的可读复刻 playbook + system prompt 复述。⚠️ 逆向工程所得，未经官方证实。⭐8
- [pjpoulose/PIL](https://github.com/pjpoulose/PIL) —— 可安装 skill：把 Instagram 收藏帖子变成私人可检索知识库。⭐1
- [JustinAllen03-stack/muse-imprint](https://github.com/justinallen03-stack/muse-imprint) —— 趣味 skill：给朋友的 Muse「盖章」语音印记（需对方同意，会逐渐消退）。⭐1

## Connectors 连接器

- [dkm90x/muse-mac-connector](https://github.com/dkm90x/muse-mac-connector) —— macOS 菜单栏桥接：经你批准后执行 25 个本地动作（文件、终端、截屏等），经 Cloudflare 隧道通信。⭐0
- [NeedsChloesure/muse-proxy](https://github.com/NeedsChloesure/muse-proxy) —— Cloudflare Worker 做的 API-key 网关，自建 CalDAV/CardDAV 不用存明文密码。⭐0
- [camirian/agent-connector-launch-kit](https://github.com/camirian/agent-connector-launch-kit) —— 为 Muse 构建 OpenAPI connector 的 starter kit，含一次真实提审经验。⭐0
- [1clawAI/muse-connector](https://github.com/1clawAI/muse-connector) —— 把 1Claw 的审批队列、钱包、活动日志接进 Muse。⭐1
- [yahavf6/muse-brain](https://github.com/yahavf6/muse-brain) —— 跨 agent 共享决策图谱，Muse 经 REST custom connector 接入（实验性）。⚠️ 非商业许可。⭐11
- [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) —— 跨 AI 工具的记忆层，Muse 以远程 MCP custom connector 接入。star 数未核实。
- [linboxin/nexus-mcp](https://github.com/linboxin/nexus-mcp) —— 通用 MCP 服务器，Muse 可作为 custom client 接入。star 数未核实。
- [maddivikash/auto-apply](https://github.com/maddivikash/auto-apply) —— 求职自动投递工具；其文档是「如何做 Muse connector」的完整参考实现（Clerk OAuth 2.1 + PKCE）。star 数未核实。
- [GkhanKINAY/postqueen-docs](https://github.com/GkhanKINAY/postqueen-docs) —— 文档站，演示 Muse 如何经 custom connector 写帖/排期。star 数未核实。

## Prompts 与用例

- [everyai-com/muse-use-cases](https://github.com/everyai-com/muse-use-cases) —— 真实用例田野指南：351 个用例、257 个附完整原始 prompt，另有一份可一次性粘贴的 capability pack。⚠️ 活跃度疑似偏低。⭐2
- [freeflow-community/skill-explorer](https://github.com/freeflow-community/skill-explorer) —— 网页版个人助手 prompts 浏览器（含 Muse 板块），通过 GitHub issue 征集新 prompt。⭐3

## 开发工具 / CLI

- [duclm1x1/Muse-Chat-MCP](https://github.com/duclm1x1/Muse-Chat-MCP) —— 用 Playwright 驱动已登录的 Chrome，把 muse.ai 变成 MCP server + OpenAI 兼容接口 + CLI。⚠️ 可能违反 Meta ToS。⭐38
- [kevintsai1202/muse-image-mcp](https://github.com/kevintsai1202/muse-image-mcp) —— 社区 MCP server：经 Meta Model API 调用 Muse 图像模型（给开发者在 Claude Code/Cursor 里用，非 Muse 用户工具）。star 数未核实。

## 评测与基准

- [dpawlan/ai-assistant-benchmark](https://github.com/dpawlan/ai-assistant-benchmark) —— 公开记分牌（Wirecutter 风格）：40 个助手 × 15 个维度，含 Muse 档案页。⭐2
- [ultrametricai/productarena](https://github.com/ultrametricai/productarena) —— 产品竞技场：Muse 在个人 AI 助手赛道排 #8/9（PA 7.6）。star 数未核实。
- [mahdi-salmanzade/meta-muse-teardown](https://github.com/mahdi-salmanzade/meta-muse-teardown) —— Muse 客户端的静态隐私分析，附证据与复现脚本（独立安全研究）。⭐2

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
