# AGENT.md — AI 全景速览海报生成任务

## 任务目标

在本仓库中创建一个精美的 HTML 海报页面 `ai-landscape-2026.html`，内容为截至 2026 年 3 月 7 日的全球 AI 发展全景速览。

## 设计要求

### 视觉风格
- **深色科技风**：背景使用深色渐变（#0a0a1a → #1a1a3e）
- **卡片式布局**：每个板块为一张独立卡片，半透明深色背景 + 微发光边框
- **配色方案**：主色 #00d4ff（科技蓝）、辅色 #a855f7（紫色）、强调色 #22c55e（绿色）、警告色 #f59e0b（橙色）
- **字体**：中文用 system-ui / "PingFang SC" / "Microsoft YaHei"，英文用 monospace 风格
- **图标**：使用 Emoji 作为每个板块的图标标识

### 布局要求
- **移动端优先**：必须在手机上完美显示（单列布局）
- **桌面端**：宽屏时使用两列网格
- **响应式断点**：768px
- **每张卡片**内使用小型表格或列表展示信息，表格需适配移动端（可横向滚动或转为堆叠式）

### 页面结构（共 8 个板块）

#### 顶部标题区
- 大标题：🌍 AI 全景速览 — 2026.03.07
- 副标题：从大模型到具身 AI，一页掌握全球 AI 最新动态

#### 板块一：🧠 前沿大模型
表格展示以下模型的最新版本、亮点和最佳用途：
| 模型 | 最新版本 | 亮点 | 最佳用途 |
|------|----------|------|----------|
| GPT-5 系列 (OpenAI) | GPT-5.4 (2026.3) | 400K 上下文，幻觉降低 65%，速度 3.8×，AIME 满分 | 推理、复杂问答 |
| Claude (Anthropic) | Opus 4.6 / Sonnet 4.6 (2026.2) | SWE-bench 80.9%，200K-1M 上下文，Agent Teams | 代码、企业 |
| Gemini (Google) | 3.1 Pro (2026.2) | 1M token 上下文（最大），Deep Think，MMLU 93.8% | 长文档、多模态 |
| DeepSeek V3.2 (开源) | 2026.Q1 | 1M+ 上下文，成本极低，开放权重 | 高性价比部署 |
| Kimi K2 (月之暗面) | 2026.Q1 | 万亿参数开放权重，Chatbot Arena 第一 | 中文生态 |
| GLM-5 (智谱) | 2026.Q1 | 首个华为芯片训练的前沿模型 | 国产化部署 |

趋势标注：API 价格一年暴跌 50-98%，多模型路由成为标配

#### 板块二：🤖 AI Agent 智能体
分两个子区域：

**编码智能体：**
- GitHub Copilot (Agent Mode)：深度集成 GitHub，全仓库上下文
- Claude Code：端到端自主编码，业界最强代码质量
- Cursor：IDE 级全仓库理解，自然语言→代码
- Devin：全自主软件工程师
- Amazon Q Developer：AWS 集成，遗留代码现代化

**通用/业务智能体平台：**
- LangChain / LangGraph：开发者首选 Agent 框架
- CrewAI：多 Agent 协作编排
- n8n (AI Agent 节点)：无代码 AI 自动化
- Zapier AI：连接 5000+ 应用
- Adaptive / Lindy / Relevance AI：无代码 Agent 构建器

核心变化标注：Agent 从"辅助"进化到"执行"

#### 板块三：🎨 内容生成
分三个子区域（视频 / 图像 / 音乐）：

**视频生成：**
| 工具 | 亮点 | 价格 |
|------|------|------|
| Sora 2 | 电影级叙事，物理仿真，同步音频 | $20-200/月 |
| Veo 3.1 | 4K 专业视频，原生音频口型同步 | $19.99/月 |
| Runway Gen-4.5 | Motion Brush 精确控制 | $12-78/月 |
| Kling 2.6 | 1080p 两分钟，人体运动最逼真 | 免费+付费 |

**图像生成：** Midjourney（艺术王者）、DALL-E 4、Adobe Firefly、SD XL

**音乐生成：** Suno v3（完整歌曲）、Udio（分轨编辑+Remix）、ElevenLabs

#### 板块四：⚡ 生产力工具矩阵
表格展示：
| 场景 | 推荐工具 |
|------|----------|
| AI 助手 | ChatGPT、Microsoft Copilot、Gemini |
| 会议沟通 | Fathom、Fireflies.ai、Granola |
| 写作内容 | Notion AI、Jasper、Grammarly AI |
| 研究知识 | NotebookLM、Perplexity、Elicit |
| 演示可视化 | Gamma、Canva AI、Beautiful.ai |
| 日程任务 | Motion、Reclaim.ai、ClickUp AI |
| 邮件管理 | Superhuman、Shortwave |
| 应用开发 | Lovable、Bolt、v0 |
| 自动化 | Zapier AI、n8n、Make |

#### 板块五：🦾 具身 AI & 机器人
要点列表：
- Boston Dynamics Atlas 3.0：已在工厂实际部署
- Tesla Optimus / Figure AI / AgiBot：人形机器人进入量产
- NVIDIA Cosmos & Isaac GR00T：开放物理 AI 模型
- LG CLOiD：家庭服务机器人，可端餐做家务
- 趋势：通用"机器人大脑"基础模型将硬件与智能解耦

#### 板块六：⚖️ 全球 AI 监管
表格展示：
| 地区 | 状态 |
|------|------|
| 欧盟 | EU AI Act 执行中，2026.8 主要截止日期，罚款最高营收 7% |
| 美国 | 无联邦统一法，科罗拉多 2026.6 生效，加州框架领先 |
| 中国 | 算法透明、内容标注、芯片管控 |
| 英国 | 亲创新，依托现有监管机构 + AI 安全研究所 |
| 日韩 | 灵活促进型框架，研发+安全并重 |

警告标注：2026 被称为"AI 执法元年"

#### 板块七：🔮 核心趋势
8 条一句话总结，用编号列表+高亮关键词：
1. 没有最好的模型，只有最适合任务的模型 — 多模型路由成标配
2. Agent 是主角 — 从聊天机器人到自主执行工作流
3. 成本悬崖式下降 — API 价格一年降 50-98%
4. 多模态融合 — 文本+图像+视频+音频+代码统一处理
5. 开源追赶闭源 — DeepSeek、Kimi K2、GLM-5 挑战商业模型
6. 具身 AI 元年 — 人形机器人从 demo 走向工厂和家庭
7. 监管收紧 — 全球进入实质执法阶段
8. AI 原生应用爆发 — 自然语言即编程

#### 底部信息栏
- 信息来源：OpenAI / Anthropic / Google / NVIDIA 官方，Deloitte / Stanford / IFR 报告，PCMag / TechRadar 测评，arXiv / Chatbot Arena 数据
- 制作日期：2026-03-07
- GitHub: charlesbo/ai_now

## 技术要求
- 单个 HTML 文件，所有 CSS 内联（在 `<style>` 标签中）
- 不依赖任何外部 CSS/JS 框架
- 纯 HTML + CSS，不使用 JavaScript
- 文件编码 UTF-8
- 文件名：`ai-landscape-2026.html`
- 放在仓库根目录

## 输出文件
- `ai-landscape-2026.html`
