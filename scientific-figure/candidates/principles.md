# scientific-figure：原则候选（BSG 全文扫描）

> 来源：Jen Christiansen, *Building Science Graphics*（BSG.md）。行号为 Markdown 源文件行号；引文是原文短摘，后面的“扩展/边界”是本技能蒸馏层，不能当作原书原话。BSG 讨论的是科学图形设计，不等同于任何期刊的强制规范；本技能将其原则与用户要求的科研出版边界合并。

- id: p01
  title: 先定义视觉故事，再画细节
  type: principle
  source_chapter: CHAPTER 7 Organization and Emphasis；CHAPTER 15 The Process of Building Graphics
  source_quote: |
    “Where will the reader’s gaze enter the space? What piece of information do they need first, second, and third? How can I direct their attention…?”（约 1290–1295）
  summary: |
    先写图的目标、入口和阅读顺序，再决定元素位置；让版面位置、大小、对比和箭头共同强化论证顺序。流程图用顺序/循环，比较图保持对应方向，架构图按关系布置，数据图选择能突出目标关系的图形。
  tags: [principle, visual-story, attention, cross-disciplinary]

- id: p02
  title: 让信息流与读者视线同向
  type: rule
  source_chapter: CHAPTER 7 Composition
  source_quote: |
    “Think about taking a reader by the hand…What information do they need to encounter first…second? How can you help the reader follow the correct path effortlessly…”（约 1310–1320）
  summary: |
    为每张图设计明确入口、路径和终点；用箭头、位置、尺度、色彩层级和重复结构降低寻找成本。不要假设读者有作者口头讲解，图应可独立解释。
  tags: [rule, flow, sequence, usability]

- id: p03
  title: 用网格和对齐建立可读结构
  type: principle
  source_chapter: CHAPTER 7 Grids and Alignments
  source_quote: |
    “Those gutters of negative space prevent images or text from colliding…The overall effect is logical and modular. Alignment lines are built into the structure.”（约 1365–1375）
  summary: |
    在绘制前建立隐性网格、列宽、基线和对齐轴；模块、标签、图例和面板沿共同轴线组织。网格是规划工具，不应成为成品中的装饰线；小图也至少保持主要水平/垂直对齐。
  tags: [principle, grid, alignment, layout]

- id: p04
  title: 留白用于分组、呼吸和导航
  type: rule
  source_chapter: CHAPTER 7 Negative Space
  source_quote: |
    “Negative space…can be used to frame objects and create groupings…try using a buffer of negative space instead [of a frame].”（约 1441–1450）
  summary: |
    用有意的空白区分模块、包围重点、隔开标签和给视线休息；不要为填满画布而添加内容。优先用间距和邻近关系表达分组，只有确需裁切/框定时才用边框。
  tags: [rule, whitespace, grouping, restraint]

- id: p05
  title: 层级必须可见且可预测
  type: principle
  source_chapter: CHAPTER 7 Visual Hierarchy
  source_quote: |
    “Hierarchy [is] conveyed visually, through variations in scale, value, color, spacing, placement…Without hierarchy, graphic communication is…difficult to navigate.”（约 1461–1475）
  summary: |
    以位置、尺度、明度、色彩、间距、线宽和字级建立主次；每一层只承担清晰的注意力职责。标题/总览先于细节，背景和上下文降低视觉权重，避免所有元素同等抢眼。
  tags: [principle, hierarchy, emphasis, navigation]

- id: p06
  title: 颜色是编码和引导工具，不是装饰
  type: rule
  source_chapter: CHAPTER 8 Color
  source_quote: |
    “Color…can be used…to selectively isolate and highlight objects and information.”（约 1978–1982）；“double-encode that information, unless your colors pass the grayscale test.”（约 2049）
  summary: |
    先明确颜色代表的变量（类别、连续值、状态或焦点），建立有限且语义稳定的调色板；连续数据用感知上均匀的明度变化，重点用有限对比。关键信息应以形状、纹理、线型或直接标签双重编码，并进行灰度、色觉缺陷和打印检查。
  tags: [rule, color, encoding, accessibility]

- id: p07
  title: 质疑默认彩虹渐变
  type: counter-constraint
  source_chapter: CHAPTER 8 Approaching Color Critically
  source_quote: |
    “Rainbow color gradients…[have] perceived irregularities…try printing…or converting…to grayscale…change your color palette.”（约 2015–2024）
  summary: |
    不因学科惯例而自动使用彩虹色带；检查渐变是否造成伪边界、误导排序或打印失真。选择与数据性质一致、感知顺序清楚的方案。
  tags: [constraint, color, rainbow, data-visualization]

- id: p08
  title: 排版同时负责可读性和导航
  type: principle
  source_chapter: CHAPTER 9 Typography
  source_quote: |
    “Typography…includes size, placement, alignment, spacing, color…[and] readability…and cues for how to navigate through a space.”（约 2269–2277）
  summary: |
    字体、字级、字重、行距、对齐和标签位置须成体系；标题、注释、坐标、图例和正文建立少量稳定层级。直接标注应靠近对象，避免标签与图形重叠；确保缩放、投影、印刷后仍可读。可参考学术出版物的最小字级要求，但按最终尺寸验证，不硬套单一数值。
  tags: [principle, typography, legibility, annotation]

- id: p09
  title: 上下文、复杂性和不确定性要诚实呈现
  type: rule
  source_chapter: PART 2 Special Considerations for Science Graphics
  source_quote: |
    “Honoring Complexity”；“Providing Context”；“Communicating Uncertainty and Unknowns”（约 3077–3260）
  summary: |
    不为简洁而删掉会改变结论的条件、尺度、基线、误差或未知；用图例、primer、注释和分层结构提供所需背景。明确数据范围、单位、来源与不确定性，避免视觉确定性超过证据确定性。
  tags: [rule, rigor, uncertainty, context]

- id: p10
  title: 先概念草图、再细化渲染
  type: workflow-rule
  source_chapter: CHAPTER 15 The Process of Building Graphics
  source_quote: |
    “thinking through the content before getting distracted by drawing details”; “If the organization…is solid, then the illustrative details can develop organically”（约 3706–3715）
  summary: |
    先做多种低成本构图，锁定故事、路径、尺度与分组，再投入精细绘制。概念阶段请内容专家和潜在读者检查准确性、信息路径和范围；后续反馈只改细节，重大问题应回到构图阶段。
  tags: [workflow, sketch, iteration, review]

- id: p11
  title: 用受众和输出场景校准设计
  type: principle
  source_chapter: Preface/My Point of View；CHAPTER 15 Step-by-Step Guide
  source_quote: |
    “I always define my audience as a step in the design process.”（约 353）；“Where will your image live? …inform decisions related to both content and style…dimensions”（约 4653–4670）
  summary: |
    在设计开端明确读者、媒介、尺寸、分辨率、色彩模式和阅读距离；同一数据在论文、海报、幻灯片或屏幕上的构图和字级需重新验证。跨文化/跨语言场景重新检查阅读方向、符号含义和可访问性。
  tags: [principle, audience, medium, production]

- id: p12
  title: 科研图与商业/自媒体装饰严格分界
  type: user-hard-constraint
  source_chapter: 用户任务约束（非 BSG 原文）
  source_quote: |
    用户要求：严禁在科研绘图中引入商业化元素，例如 Emoji、过度装饰的卡通 Icon、花哨渐变特效。
  summary: |
    成品应以证据、关系和可复核性为中心；禁止 Emoji、营销徽章、卡通贴纸、无语义 3D 光效、花哨渐变、拟人化装饰和“吸睛”特效。允许抽象符号、示意图和有限风格化，但每个视觉元素必须有可解释的科学语义或阅读功能。
  tags: [hard-constraint, academic, anti-commercial, restraint]

- id: p13
  title: 以顶级学术出版标准做验收目标
  type: user-extension
  source_chapter: 用户任务约束（外部目标）
  source_quote: |
    用户要求：规则需符合《Nature Reviews》等顶级学术期刊的出版标准。
  summary: |
    将 Nature Reviews 等期刊的清晰、克制、可复核审美作为验收目标：逻辑优先、信息对齐、字体可读、颜色可访问、来源和单位完整、输出规格正确。此条是本技能的质量目标，不宣称 BSG 本身等同于期刊规范；最终仍以目标期刊最新 author guidelines 为准。
  tags: [extension, publication, quality-control]

