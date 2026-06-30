# handdrawnyl

把文章、会议洞察、管理判断、系统逻辑和 AI 工作流，转化为统一手绘笔记风格的认知洞察图。

**16:9 横版优先 | 手绘笔记感 | 企业级结构 | AI / 数据 / 系统元素 | 两阶段 Shot List 工作流**

---

## What is handdrawnyl?

`handdrawnyl` 是一个用于生成手绘风格认知洞察图的 Skill。

它不是小黑风格插画 Skill，不是通用商业插画 prompt，也不是传统 PPT 信息图模板。

它的核心目标是：

> 先理解内容中的认知锚点，再把其中一个判断、结构、流程、系统关系或管理洞察，转化为一张清晰、有结构、有手绘笔记感的解释图。

---

## Visual Style

默认视觉比例：

- 50% 手绘笔记感
- 30% 企业级结构
- 20% 科技 / AI / 数据元素

核心特征：

- 白底、极浅灰底或极浅暖白底
- 黑色 / 深灰手绘线条
- 轻微手绘抖动，但保持清晰
- 少量颜色强调
- 稳定的中性线条人物符号
- 短标签、少文字
- 结构清楚，有思考痕迹

---

## Illustration Type Priority

handdrawnyl 优先支持：

1. 认知洞察图
2. 结构解释图
3. Presentation 配图
4. 项目管理图

---

## Two-stage Workflow

handdrawnyl 默认使用两阶段工作流。

### Stage 1: Visual Planning

先分析内容，提取认知锚点，输出 Shot List。  
即使用户说“生成图片”，默认也先规划，不直接生图。

### Stage 2: Image Generation

用户确认、选择或修改 Shot List 后，再生成图片。  
每张图单独生成，不默认拼成一张大图。

---

## Color Modes

### Tech Accent Mode

黑白线稿 + 蓝 / 青 / 紫科技点缀。  
适合 AI、Agent、Automation、Power BI、数据系统和结构解释图。

### Thinking Note Mode

黑白线稿 + 蓝 / 黄 / 橙手写强调。  
适合会议洞察、问题树、决策树、管理原则和复盘图。

### Soft Color Sketch Mode

黑色线稿 + 柔和浅色填充。  
适合 presentation、知识型文章插图和视频视觉页。

### Custom Mode

用户可以指定品牌色、项目色或特殊场景颜色。

---

## Recurring Figure

handdrawnyl 使用稳定的中性线条人物符号。

它不是小黑，不是卡通 IP，也不是吉祥物。  
人物只是认知动作的执行者，用来表达观察、拆解、推进、判断、协作和复盘。

人物可以根据场景变成：

- 白板思考者
- 项目经理 / Operator
- AI Agent 协作者
- 系统观察者

---

## Install

```bash
git clone <your-repo-url>
cd handdrawnyl

mkdir -p "${CODEX_HOME:-$HOME/.codex}/skills"
cp -R ./handdrawnyl "${CODEX_HOME:-$HOME/.codex}/skills/"
```

Use:

```text
Use $handdrawnyl ...
```

---

## Directory Structure

```text
.
├── README.md
├── LICENSE
├── NOTICE.md
├── examples/
│   ├── prompts.md
│   └── images/
└── handdrawnyl/
    ├── SKILL.md
    ├── agents/
    │   └── openai.yaml
    ├── assets/
    │   └── examples/
    └── references/
        ├── style-dna.md
        ├── visual-figure.md
        ├── visual-elements.md
        ├── composition-patterns.md
        ├── prompt-template.md
        └── qa-checklist.md
```

---

## Notes

- 先选认知锚点，再设计画面。
- 每张图只表达一个核心认知点。
- 不要平均配图。
- 不要把文章塞成说明书。
- 中文标签越短越稳定。
- 示例图只用于风格校准，不作为构图模板。
- 不保留小黑样图，避免风格污染。
