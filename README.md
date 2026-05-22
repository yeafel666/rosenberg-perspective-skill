# rosenberg-perspective-skill

以 **Marshall B. Rosenberg**（非暴力沟通 / NVC 创始人）的思维框架作为你的个人思维顾问——分析冲突、审视沟通、提供反馈。

兼容所有支持自定义 Skill 的 AI Coding Agent，包括但不限于 **Claude Code**、**Qoder**、**Codex CLI**、**QwenCode**、**OpenClaw** 等，跨平台可用（Windows / macOS / Linux）。

## 它能做什么？

激活此 skill 后，Agent 会直接以 Rosenberg 的身份回应，用他的语气、节奏和思维逻辑来帮你：

- **分析人际冲突** — 识别语言暴力背后的未满足需求
- **审视沟通方式** — 指出评判、指责、命令等暴力语言模式
- **提供反馈建议** — 用观察 → 感受 → 需要 → 请求的 NVC 框架重构表达
- **决策咨询** — 从非暴力沟通的视角提供决策启发

## 知识来源

基于 6 个维度的深度调研构建：

| 维度 | 内容 |
|------|------|
| 核心著作 | *Nonviolent Communication*、*Speak Peace in a World of Conflict* 等 |
| 一手访谈 | Inquiring Mind 采访、San Francisco 工作坊等 5 个来源 |
| 批评声音 | NVC 的 6 类外部批评与回应 |
| 关键决策 | Rosenberg 一生的 7 个关键决策分析 |
| 完整时间线 | 从 1934 年出生到 2015 年去世的传记时间线 |
| 表达 DNA | 语法偏好、词汇频率、节奏特征、幽默风格 |

提炼出 **6 个核心心智模型**、**8 条决策启发式** 和完整的表达风格 DNA。

## 安装

将 `rosenberg-perspective` 目录放入你的 Agent 的 skills 目录。以 Claude Code 为例：

```
~/.claude/skills/rosenberg-perspective/
├── SKILL.md
├── README.md
└── references/
    ├── research/
    │   ├── 01-writings.md
    │   ├── 02-conversations.md
    │   ├── 03-expression-dna.md
    │   ├── 04-external-views.md
    │   ├── 05-decisions.md
    │   └── 06-timeline.md
    ├── sources/
    └── synthesis.md
```

## 使用方法

在 Agent 中直接用自然语言触发：

- "用 Rosenberg 的视角帮我看看这段对话"
- "卢森堡会怎么处理这个冲突？"
- "帮我用非暴力沟通的角度重新组织这段话"
- "切换到 Rosenberg 模式"

## 构建工具

本 Skill 由 [女娲 Skill 造人术](https://github.com/alchaincyf/nuwa-skill) 蒸馏生成，创建者：[花叔](https://x.com/AlchainHust)。

## License

MIT
