# Awesome Muse 中文精选

> [Muse](https://muse.ai)（Meta 个人 AI 助手）生态资源的中英双语精选集 —— skills、connectors、prompts、workflow，每条都附带实测点评。
>
> [English](README.md) · [贡献指南](CONTRIBUTING.zh-CN.md)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.zh-CN.md)

Muse 于 2026-09-08 发布，社区生态增长迅速。和纯链接列表不同，这里的每条收录都带有一句实测点评：它是做什么的、适合谁、有没有什么坑。下面 star 数为 2026-10-12 实测。

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

- [facebookincubator/muse-gadget-sdk](https://github.com/facebookincubator/muse-gadget-sdk) —— Meta 官方 SDK：自制硬件小部件（ESP32/Linux）接入 Muse。⭐1985 且增长迅猛 · Apache-2.0

## Awesome 列表

- [anil-matcha/awesome-muse-connectors](https://github.com/anil-matcha/awesome-muse-connectors) —— 150+ 社区 connector skills + 官方集成目录 + 13 个 agent workflow 模板。社区 star 最高。⭐1355
- [aicodedecode/awesome-muse-skills](https://github.com/aicodedecode/awesome-muse-skills) —— 2384 个 skills（899 原创 + 1485 精选转载），配套可搜索网站。⭐16
- [cszach/awesome-muse](https://github.com/cszach/awesome-muse) —— 指南、用例、工具、新闻 12 个板块的策展列表，更新勤快。⭐10
- [cwybruce/awesome-muse-use-cases](https://github.com/cwybruce/awesome-muse-use-cases) —— 每日更新的 Muse 真实用例中英双语精选（每条附来源），带可搜索网页版与竞品对照。⚠️ README 顶部有作者推广块。⭐2 · 新增

## Skills 技能

- [jacobwell/muse-skills](https://github.com/jacobwell/muse-skills) —— Muse 内置 72 个 skills 的可读复刻 playbook + system prompt 复述。⚠️ 逆向工程所得，未经官方证实。⭐8
- [pjpoulose/PIL](https://github.com/pjpoulose/PIL) —— 可安装 skill：把 Instagram 收藏帖子变成私人可检索知识库。⭐2
- [JustinAllen03-stack/muse-imprint](https://github.com/justinallen03-stack/muse-imprint) —— 趣味 skill：给朋友的 Muse「盖章」语音印记（需对方同意，会逐渐消退）。⭐1
- [GMAn0n/muse-linkedin-skill](https://github.com/GMAn0n/muse-linkedin-skill) —— 即插即用的 LinkedIn 技能：在 Muse 里发帖、读自己的资料。⭐0 · 新增
- [svenkatreddy/universal-video-skills](https://github.com/svenkatreddy/universal-video-skills) —— Agent Skills 格式的通用 AI 视频制作技能包（prompt 撰写、电影感调度、分镜、角色一致性、质检），Muse 可用。⭐3 · 新增
- [nanbada/muse-creative-skills](https://github.com/nanbada/muse-creative-skills) —— 图像/视频制作 SKILL.md 包：手机实拍感、姿势参考、编辑风海报、竖屏视频 prompt。⭐0 · 新增
- [RobertDeRose/muse-atlassian-skill](https://github.com/RobertDeRose/muse-atlassian-skill) —— 让 Muse 直接读写 Jira 和 Confluence 的工作区技能：搜索、查看、创建、更新。⭐1
- [Uohzzz/Muse.ai_wechat_bridge](https://github.com/Uohzzz/Muse.ai_wechat_bridge) —— 让 Muse 进驻微信的 Skill 包：走微信官方 iLink/Clawbot Bot 通道，扫码登录，自动回复带看门狗；仅支持一对一私聊，Bot 不能主动开口。⭐2 · 新增
- [otamendez11/muse-skills](https://github.com/otamendez11/muse-skills) —— 6 个西班牙语 SKILL.md（提示词优化、访谈流程、视觉演示、数据核查、去 AI 味改写），兼容 Meta Muse、Hermes 与 Claude。⭐0 · 新增
- [sneakers-the-rat/muse-skills](https://github.com/sneakers-the-rat/muse-skills) —— Muse 官方内置 skill 的每小时自动快照归档（artifacts、generate_podcast、spaces 等），写 skill 时的参考实现库。⭐15 · 新增
- [nxrskyaa/muse-motion-skills](https://github.com/nxrskyaa/muse-motion-skills) —— 教 AI agent 做 9:16 竖屏动态信息图的 SKILL.md 工作流（动感排印/像素 RPG 两套风格，Remotion+React+TS 模板，零付费 API）；兼容 Muse 等多助手。⭐0 · 新增
- [tangziyi001/muse-aurelius](https://github.com/tangziyi001/muse-aurelius) —— 一个 Muse agent 实作（"Aurelius"）：Instagram Reel 工厂渲染流水线，可复用 skills（reel-factory、instagram-automation）+ Pi SSH 脚本。⭐0 · 新增

## Connectors 连接器

- [dkm90x/muse-mac-connector](https://github.com/dkm90x/muse-mac-connector) —— macOS 菜单栏桥接：经你批准后执行 25 个本地动作（文件、终端、截屏等），经 Cloudflare 隧道通信。⭐2
- [NeedsChloesure/muse-proxy](https://github.com/NeedsChloesure/muse-proxy) —— Cloudflare Worker 做的 API-key 网关，自建 CalDAV/CardDAV 不用存明文密码。⭐1
- [camirian/agent-connector-launch-kit](https://github.com/camirian/agent-connector-launch-kit) —— 为 Muse 构建 OpenAPI connector 的 starter kit，含一次真实提审经验。⭐1
- [1clawAI/muse-connector](https://github.com/1clawAI/muse-connector) —— 把 1Claw 的审批队列、钱包、活动日志接进 Muse。⭐1
- [yahavf6/muse-brain](https://github.com/yahavf6/muse-brain) —— 跨 agent 共享决策图谱，Muse 经 REST custom connector 接入（实验性）。⚠️ 非商业许可。⭐11
- [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) —— 跨 AI 工具的记忆层，Muse 以远程 MCP custom connector 接入。⭐48450 · 它的 star 主要来自更广泛的 agent-memory 受众
- [linboxin/nexus-mcp](https://github.com/linboxin/nexus-mcp) —— 通用 MCP 服务器，Muse 可作为 custom client 接入。⭐1
- [maddivikash/auto-apply](https://github.com/maddivikash/auto-apply) —— 求职自动投递工具；其文档是「如何做 Muse connector」的完整参考实现（Clerk OAuth 2.1 + PKCE）。⭐1
- [GkhanKINAY/postqueen-docs](https://github.com/GkhanKINAY/postqueen-docs) —— 文档站，演示 Muse 如何经 custom connector 写帖/排期。⭐1
- [racstan/pi-muse-connector](https://github.com/racstan/pi-muse-connector) —— 树莓派 ↔ Muse 的托管 REST API 桥接。⭐1 · 新增
- [0xBrsm/musebox](https://github.com/0xBrsm/musebox) —— Linux 机器与 Muse 之间的纯文件传输桥。⭐0 · 新增
- [MehediHasan27/court-connector-demo](https://github.com/MehediHasan27/court-connector-demo) —— 让 Muse 帮场馆订球场的 MCP server 模板（clone → 写 YAML → 部署 → 提交到 Muse 目录）。⚠️ 文档/demo 免费，源码是付费模板。⭐0 · 新增
- [harris-ryder/dowser](https://github.com/harris-ryder/dowser) —— 只读 MCP connector，帮你找出生活中藏着的钱；Muse 及其他 agent 可用。⭐1
- [ManasDasri/hark-call](https://github.com/ManasDasri/hark-call) —— 给 AI 助手（Muse/Hark/Grok）打电话发提醒，Google Apps Script + Twilio 纯 serverless。⭐0 · 新增
- [duman190/telegram4muse](https://github.com/duman190/telegram4muse) —— 让 Muse 通过家中 Mac 的 Telethon 会话以你的身份发 Telegram 投票/消息（走 Tailscale）；登录态留在 Mac 上，Muse 接触不到任何 token。⭐0 · 新增
- [nevoflux-browser/nevoflux-muse](https://github.com/nevoflux-browser/nevoflux-muse) —— 让 Muse agent 经 MCP + 端到端加密中继操控 NevoFlux 浏览器的客户端（pair/auth/tools/call/approve 命令可用）。⭐0 · 新增
- [useburner/burner](https://github.com/useburner/burner) —— 给 AI 助手配一部"实体备用机"：家里闲置 Android 手机经 Tailscale 接入，助手可替你操作真实 App；目前支持 Muse。⭐10 · 新增

## Gadgets 硬件小部件

基于 Meta gadget SDK 的社区硬件移植与构建。

- [youlim-bot/MUSE-Gadget-for-Rabbit-r1](https://github.com/youlim-bot/MUSE-Gadget-for-Rabbit-r1) —— 社区把 Muse gadget SDK 移植到 Rabbit r1（LineageOS + Android 应用）。⭐4 · 新增
- [leungcheukfai/muse-gadget-zh-hant](https://github.com/leungcheukfai/muse-gadget-zh-hant) —— 繁体中文社区版 ESP32 gadget SDK：中文界面、语音回复、网页一键烧录。⭐5 · 新增
- [nobaksan/stackchan-muse](https://github.com/nobaksan/stackchan-muse) —— 把 M5Stack StackChan 机器人做成 Muse 小部件，含颈部舵机语音指令。⭐0 · 新增
- [burndown/muse-gadget-cloud](https://github.com/burndown/muse-gadget-cloud) —— ESP32 Muse 小部件 + Cloudflare Worker 网关方案。⭐0 · 新增
- [viticci/muse-pocket](https://github.com/viticci/muse-pocket) —— Xteink X4 Pro 墨水屏上的 Muse 伙伴：显示你的 Muse 形象与实时状态，基于 Gadget SDK。⭐55
- [samyeei/Muse-charm-mosaico](https://github.com/samyeei/Muse-charm-mosaico) —— ESP-Mosaico 硬件上的语音 AI 伙伴：按住说话、8 种动态表情、Muse 生成的人设。⭐13
- [wobsoriano/muse-gadget-psp](https://github.com/wobsoriano/muse-gadget-psp) —— Muse 原生跑在 Sony PSP 上：按住 R 说话，屏幕+语音回复；Gadget SDK 的 C 语言移植（需 PSP-3000 + 自制系统）。⭐9
- [wupsbr/waveshare-muse-gadget-sdk](https://github.com/wupsbr/waveshare-muse-gadget-sdk) —— 三款微雪 ESP32-S3 开发板上的 Gadget SDK（LCD/AMOLED 屏）：ElevenLabs 语音回复、触摸调音量、电量显示。⭐9
- [vocino/muse-arr](https://github.com/vocino/muse-arr) —— 在 Muse 里指挥家里的 Sonarr/Radarr/Jellyfin 影音栈：局域网 Linux 小部件，不用 SSH 也能排片。⭐6
- [cameronapak/muse-r1](https://github.com/cameronapak/muse-r1) —— 让 Rabbit r1 复活成按住说话的 Muse 小部件：LineageOS 21 原生 Android Home 应用，构建文档与回滚说明齐全。⭐5
- [hypery11/muse-gadget-everywhere](https://github.com/hypery11/muse-gadget-everywhere) —— 开源 Android runtime，把手机/平板/电视变成可编程 Muse 小部件：显示、媒体、语音、相机、本地自动化。⭐5
- [moerdowo/muse-gadget-xiaozhi](https://github.com/moerdowo/muse-gadget-xiaozhi) —— Muse 小部件 UI（像素小人、按住说话、字幕）跑在小智 ESP32-S3 语音硬件上。⭐0
- [Josh-Archer/homeassistant-addon-muse-gadget](https://github.com/Josh-Archer/homeassistant-addon-muse-gadget) —— Home Assistant 插件，经 Gadget SDK 把 Meta Muse 接进来。⭐3
- [burndown/luci-muse-gadget](https://github.com/burndown/luci-muse-gadget) —— 在 OpenWrt 路由器上跑 Gadget SDK Linux 客户端（带 LuCI 页面），路由器变成 Muse 小部件。⭐1
- [ledienbien-ai/muse-gadget-sdk](https://github.com/ledienbien-ai/muse-gadget-sdk) —— 非官方 Gadget SDK fork：支持官方不支持的 ESP32-S3 板子，越/英双语界面、语音回复、网页烧录。⭐4
- [dsmelvin/muse-gadget-sdk-macos](https://github.com/dsmelvin/muse-gadget-sdk-macos) —— "macOS Device SDK"：经原生 CoreBluetooth 把 Mac 变成 Muse 小部件，与 Muse App 配对后可执行命令、传文件。⭐0 · 新增
- [NajiaP/muse-gadget-state-bridge](https://github.com/NajiaP/muse-gadget-state-bridge) —— Gadget SDK 模拟器的纯文本状态桥：agent 写状态文件，watcher 把模拟器重载成无边框桌面宠物，实时显示表情/字幕/进度。⭐0 · 新增
- [shockley6668/rdk-x5-muse-gadget](https://github.com/shockley6668/rdk-x5-muse-gadget) —— 地平线 RDK X5 上的触屏 Muse 界面：LVGL 前端、动画头像、按住说话，中英双语字幕 + Edge TTS 回复，附硬件实测记录。⭐1 · 新增
- [hrabanazviking/RuneForgeAI-Project-Hlidhskjalf](https://github.com/hrabanazviking/RuneForgeAI-Project-Hlidhskjalf) —— 树莓派 5 + Hailo-10 NPU 上的 Muse 边缘协处理器：60 FPS 可视化仪表盘、持久记忆、本地神经 TTS，"分脑异步"架构。⭐2 · 新增

## Prompts 与用例

- [everyai-com/muse-use-cases](https://github.com/everyai-com/muse-use-cases) —— 真实用例田野指南：351 个用例、257 个附完整原始 prompt，另有一份可一次性粘贴的 capability pack。⚠️ 活跃度疑似偏低。⭐2
- [freeflow-community/skill-explorer](https://github.com/freeflow-community/skill-explorer) —— 网页版个人助手 prompts 浏览器（含 Muse 板块），通过 GitHub issue 征集新 prompt。⭐3
- [styrigx/muse-playbook](https://github.com/styrigx/muse-playbook) —— 501 条中文 Muse 实用技巧与真实用例，十大分类整理。⭐0 · 新增
- [Luceternity/sifti-muse-template](https://github.com/Luceternity/sifti-muse-template) —— 可移植的 Muse 构建规格：音频优先的定时双语内容摘要（摘要+英语音频+双语字幕，支持简中/西/法副字幕）。纯 spec，无可运行代码。⭐2 · 新增
- [doforu-labs/muse-agent-guide](https://github.com/doforu-labs/muse-agent-guide) —— 30+ 可直接复制的 Muse 使用食谱与 workflow 模板。⭐1 · 作者删除后于 2026-10-11 重建恢复

## 开发工具 / CLI

- [duclm1x1/Muse-Chat-MCP](https://github.com/duclm1x1/Muse-Chat-MCP) —— 用 Playwright 驱动已登录的 Chrome，把 muse.ai 变成 MCP server + OpenAI 兼容接口 + CLI。⚠️ 可能违反 Meta ToS。⭐52
- [kevintsai1202/muse-image-mcp](https://github.com/kevintsai1202/muse-image-mcp) —— 社区 MCP server：经 Meta Model API 调用 Muse 图像模型（给开发者在 Claude Code/Cursor 里用，非 Muse 用户工具）。⭐0
- [cszach/calliope](https://github.com/cszach/calliope) —— 非官方 muse.ai GNOME 桌面客户端（WebKitGTK）。⭐0 · 新增
- [drumpat01/muse-chat](https://github.com/drumpat01/muse-chat) —— 非官方聊天客户端，带动态虚拟形象（Linux/Windows）。⭐0 · 新增
- [buzhidaosm/muse-cli-bridge](https://github.com/buzhidaosm/muse-cli-bridge) —— muse.ai 命令行桥接：Keychain 登录、MCP、双向任务桥。⭐0 · 新增
- [whxjwksjs/muse-windows](https://github.com/whxjwksjs/muse-windows) —— muse.ai 的 Windows Electron 桌面封装。⭐0 · 新增
- [bynne2602/museflow](https://github.com/bynne2602/museflow) —— 可视化节点式浏览器扩展，用已登录的 muse.ai 会话驱动图像/视频生成：画布 workflow + 时间线剪辑组装。⭐56 · 新增
- [lucaisgrowing/muse-switcher](https://github.com/lucaisgrowing/muse-switcher) —— Chrome MV3 扩展：一键切换多个 muse.ai 账号（快照/恢复登录态，免重复收验证码）。⭐0 · 新增
- [BlueSkyz-Labs/muse-auto-allow](https://github.com/BlueSkyz-Labs/muse-auto-allow) —— Chrome MV3 扩展：自动点掉 muse.ai 审批卡片的 Allow，附带轮询式追问 prompt 库。⚠️ 绕过了 Muse 的人工审批环节，请自行判断。⭐0 · 新增

## 评测与基准

- [dpawlan/ai-assistant-benchmark](https://github.com/dpawlan/ai-assistant-benchmark) —— 公开记分牌（Wirecutter 风格）：40 个助手 × 15 个维度，含 Muse 档案页。⭐2
- [ultrametricai/ultrametric](https://github.com/ultrametricai/ultrametric) —— 产品竞技场：Muse 在个人 AI 助手赛道排 #8/9（PA 7.6）。⭐6 · 已由 productarena 改名
- [mahdi-salmanzade/meta-muse-teardown](https://github.com/mahdi-salmanzade/meta-muse-teardown) —— Muse 客户端的静态隐私分析，附证据与复现脚本（独立安全研究）。⭐4
- [mikezio/muse-runtime](https://github.com/mikezio/muse-runtime) —— 非官方 Muse agent 系统架构拆解：架构图、请求流走查、组件参考、安全/隐私/调度章节，按版本归档运行时快照。⭐3 · 新增

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
