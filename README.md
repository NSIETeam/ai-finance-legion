# AI Finance Legion

**智能财务分析团队。一句话输入，六 Agent 协作，自动输出完整财务报告。**

> 傅盛 AI 战队青少年黑客松参赛作品 — 多 Agent AI 数字团队

---

## 🚀 在线演示

**展示网站**: [https://nsieteam.github.io/ai-finance-legion/](https://nsieteam.github.io/ai-finance-legion/)

## 🧠 六 Agent 流水线

| Agent | 角色 | 输入 → 输出 |
|-------|------|------------|
| 📊 Auditor | 财务审计师 | 原始数据 → 分类账簿 |
| 📈 Analyst | 财务分析师 | 账簿 → 报表 + 比率 |
| 💡 Advisor | 投资顾问 | 报表 → 配置 + 选股 |
| ⚖️ Tax Officer | 税务官 | 账簿 → 税务报告 |
| 🛡️ Risk Controller | 风控官 | 全流水线数据 → 风险评分 |
| 🤖 CFO | 执行董事 | 所有 Agent 输出 → 最终报告 + 行动计划 |

## 🏗️ 项目结构

`
finance-legion/
├── index.html           # 静态展示页面（备份）
├── build.py             # 独立 HTML 页面生成脚本
├── template.html        # HTML 模板块
├── SKILL.md             # OpenClaw Skill 定义
├── agent-pipeline/      # 6 Agent 详细定义 + 工作流
│   ├── finance-auditor.md
│   ├── financial-analyst.md
│   ├── investment-advisor.md
│   ├── tax-officer.md
│   ├── risk-controller.md
│   ├── cfo.md
│   └── workflow.md
└── src/
    ├── main.js          # Vite 入口
    ├── App.vue          # 主组件 (Velorah 玻璃拟态)
    └── style.css        # 设计系统
`

## 🛠️ 技术栈

- **前端**: Vue 3 + Vite
- **设计**: Velorah 玻璃拟态（Instrument Serif + Inter 字体，深色海军蓝 + 渐变边框）
- **AI 协作**: OpenClaw Subagents + neodata-financial-search
- **部署**: GitHub Pages

## 💻 本地开发

`ash
npm install
npm run dev
`

## 📄 许可证

MIT
