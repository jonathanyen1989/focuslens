# Prompt Examples for handdrawnyl

## 1. Visual Planning Only

```text
Use $handdrawnyl 先不要生成图片。

请分析下面这段内容，提炼适合视觉化的认知锚点，并输出 handdrawnyl 风格的 Shot List。

要求：
- 只输出 Shot List
- 不生成图片
- 优先选择认知洞察图
- 其次考虑结构解释图
- 每张图只表达一个核心认知点
- 默认使用手绘笔记感 50% + 企业级结构 30% + 科技/AI/数据元素 20%

<粘贴内容>
```

## 2. Meeting Insight Shot List

```text
Use $handdrawnyl 先不要生成图片。

请从下面的会议内容中提取值得视觉化的管理洞察，输出 Shot List。

每张图需要写清楚：
- 图名
- 图形类型
- 认知锚点
- 核心表达
- 构图方式
- 人物动作
- 关键元素
- 建议文字标签
- 推荐 Color Mode

优先级：
认知洞察图 > 结构解释图 > Presentation 配图 > 项目管理图

<粘贴会议内容>
```

## 3. Single Cognitive Insight

```text
Use $handdrawnyl 为下面这个观点设计 1-2 张认知洞察图方案。

先不要生成图片，只输出 Shot List。

观点：
“不要只解决表面问题，要找到问题背后的系统。”

要求：
- 图形类型优先选择认知洞察图
- 使用结构隐喻 + 工作现场隐喻
- 可以使用白板、问题树、放大镜、隐藏系统、关键杠杆点等元素
- 人物使用 handdrawnyl 中性线条人物
- 文字标签尽量少
```

## 4. AI Agent / Skill Structure Explanation

```text
Use $handdrawnyl 先不要生成图片。

请把下面这段 AI Agent / Skill 文档转成 handdrawnyl 风格的结构解释图 Shot List。

要求：
- 识别系统结构、输入输出、反馈闭环、工具链、Agent 协作关系
- 推荐使用 Tech Accent Mode
- 使用干净手绘线稿
- 允许使用 agent node、data flow、dashboard、pipeline、tool chain 等元素
- 不要画成复杂正式架构图
- 每张图只讲一个结构

<粘贴文档>
```

## 5. Presentation Visual

```text
Use $handdrawnyl 先不要生成图片。

请为下面这页 Presentation 内容设计 handdrawnyl 风格视觉配图方案。

要求：
- 默认 16:9
- 图形类型选择 Presentation 配图
- 画面要完整、稳定、可展示
- 可以使用一个中心模型 + 少量标签
- 推荐使用 Soft Color Sketch Mode
- 保持手绘感，但不要太草稿
- 不要生成传统 PPT 信息图

<粘贴页面内容>
```

## 6. Project Management Visual

```text
Use $handdrawnyl 先不要生成图片。

请把下面的项目管理内容转成 handdrawnyl 风格的项目管理图 Shot List。

要求：
- 可以使用 timeline、milestone、risk radar、kanban、owner card、checklist、review loop
- 推荐使用 Thinking Note Mode
- 文字可以比认知洞察图略多，但必须保持短标签化
- 画面像项目白板规划，不要像复杂 PPT 信息图

<粘贴项目内容>
```

## 7. Generate Images After Approval

```text
Use $handdrawnyl 根据上一步确认的 Shot List 生成图片。

请生成第 01、02、03 张。

要求：
- 每张单独生成
- 不要拼成一张大图
- 默认 16:9 横版
- 使用 handdrawnyl 手绘风格
- 遵守对应图形类型的颜色、线条、背景和文字规则
- 不要使用小黑风格
- 不要使用黑色实心小人
- 不要使用可爱卡通风
```

## 8. Specific Color Mode

```text
Use $handdrawnyl 根据已确认的 Shot List 生成第 01 张图片。

Color Mode 使用：Thinking Note Mode。

要求：
- 白底或极浅暖灰底
- 黑色 / 深灰手绘线条
- 蓝色用于结构
- 黄色用于重点
- 橙色用于风险或阻塞点
- 不要过度上色
```

## 9. Specific Canvas Ratio

```text
Use $handdrawnyl 根据已确认的 Shot List 生成第 02 张图片。

画面比例：1:1 方图。

用途：
社媒知识卡片。

要求：
- 保持 handdrawnyl 手绘风格
- 减少元素数量
- 文字标签更短
- 保留核心认知锚点
```

## 10. Revise Existing Image

```text
Use $handdrawnyl 帮我迭代这张图。

问题：
- 画面太像 PPT 信息图
- 文字太多
- 人物太像卡通 IP
- 科技元素过重

请保持核心意思不变，重新生成一版。

调整要求：
- 更像手绘笔记
- 人物改成中性线条人物
- 减少文字标签
- 保留结构清晰度
- 使用 Thinking Note Mode
```
