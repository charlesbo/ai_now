# Copilot Instructions — AI 全景速览项目

## 项目概述
本仓库维护一个 AI 全景速览海报页面（`index.html`），每日自动更新全球 AI 最新动态。

## 更新规则

### 必须保持的设计
- 深色科技风（`#0a0a1a → #1a1a3e` 渐变背景）
- 卡片式布局，配色方案不变（主色 `#00d4ff`、辅色 `#a855f7`、强调色 `#22c55e`、警告色 `#f59e0b`）
- 移动端优先 + 768px 断点响应式
- 纯 HTML + CSS，单文件，无外部依赖，无 JavaScript
- UTF-8 编码

### 页面结构（8 个板块）
1. 顶部标题区 — 更新日期为当天
2. 🧠 前沿大模型 — 模型版本、性能数据
3. 🤖 AI Agent 智能体 — 编码智能体 + 通用平台
4. 🎨 内容生成 — 视频/图像/音乐
5. ⚡ 生产力工具矩阵 — 场景×推荐工具
6. 🦾 具身 AI & 机器人
7. ⚖️ 全球 AI 监管
8. 🔮 核心趋势（8 条）
9. 底部信息栏 — 更新制作日期

### 信息来源（需通过 web search 获取最新数据）
- **模型发布**: OpenAI, Anthropic, Google DeepMind, Meta AI, DeepSeek, Moonshot AI (月之暗面), 智谱AI 官方博客和公告
- **Agent/工具**: GitHub Blog, Cursor, Vercel, LangChain, Product Hunt
- **内容生成**: OpenAI Sora, Google Veo, Runway, Kling, Midjourney, Suno, Udio
- **机器人**: Boston Dynamics, Tesla AI, Figure AI, NVIDIA Isaac
- **监管**: EU AI Act updates, US AI regulation news, 中国网信办公告
- **行业报告**: Stanford HAI AI Index, Deloitte, McKinsey, arXiv trending
- **排行榜**: Chatbot Arena (LMSYS), SWE-bench, MMLU, HumanEval

### 更新原则
1. **只更新有实质变化的内容** — 如果某板块没有新信息，保持原样
2. **数据准确性** — 版本号、日期、性能数据必须有来源佐证
3. **保持简洁** — 每条信息一句话，突出关键数据
4. **新增内容高亮** — 新加入的模型/工具用合适方式标注
5. **更新标题区日期** — `🌍 AI 全景速览 — YYYY.MM.DD`
6. **更新底部制作日期**
