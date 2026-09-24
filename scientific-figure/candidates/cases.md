# BSG 原书案例提取（scientific-figure）

> 仅记录 BSG.md 中可核验的案例/演示；图片只按文字说明取证，不声称看过外链图。每条绑定可泛化的科研视觉方法。

- id: c01
  title: 以读者视线组织复杂科学图
  type: case
  example_kind: firsthand_design_process
  source_chapter: Chapter 7, Organization and Emphasis（约 1306–1340 行）
  source_quote: |
    “Where will the reader’s gaze enter the space? What piece of information do they need first, second, and third? … How can the position of the elements reinforce the story…”
  summary: |
    作者以连续小草图先安排信息分区、阅读入口和先后顺序，再决定元素位置；构图被视为让形式服务功能、强化主旨的过程。可迁移到场景图、流程图、架构图和数据图。
  bound_to: [视觉故事逻辑, 注意力引导, 信息分层]
  outcome: 原文将其作为组织与强调章节的基础工作法，未给出量化结果。
  tags: [case, narrative, hierarchy]

- id: c02
  title: Science 太阳活动图的网格与模块化
  type: case
  example_kind: reported_case
  source_chapter: Chapter 7, Composition / Grid（约 1380–1428 行）
  source_quote: |
    “The material is chunked up and organized in a logical manner. Sub-sections are easy to distinguish… Labels are also aligned.”；Nature Reviews 示例中“Each element is defined by the empty space around it… vertical alignment… horizontal alignment…”
  summary: |
    太阳周期图将内容拆成模块，标签按主网格或次级导线对齐；Nature Reviews 病毒图用元素周围的空白定义单元，并以垂直/水平轴连接可比较信息。网格是组织关系的思维工具，不是把页面填成方格。
  bound_to: [网格布局, 对齐, 模块化, 留白]
  outcome: 原文评价为清晰、易读的流动信息结构；不推测图像之外的效果。
  tags: [case, grid, alignment, negative-space]

- id: c03
  title: 用负空间替代多余边框
  type: case
  example_kind: reported_case
  source_chapter: Chapter 7, Negative Space（约 1428–1454 行）
  source_quote: |
    “Negative space … can be used to frame objects and create groupings… try using a buffer of negative space instead [of a line/frame].”；Bloomberg 图“imagery and text is given some space to breathe… label alignments make it feel intentional.”
  summary: |
    太阳图用文字块之间的沟槽形成分组；Bloomberg 芯片短缺图保留右侧大块空白，并以强垂直导线和标签对齐维持平衡。空白承担分组、停顿和阅读节奏，减少装饰线造成的噪声。
  bound_to: [留白, 分组, 版面平衡, 信息对齐]
  outcome: 原文明确说空间被有意设计而非“尽量塞满”。
  tags: [case, whitespace, grouping]

- id: c04
  title: 连续数据的渐变与不确定性说明
  type: case
  example_kind: reported_case
  source_chapter: Color Coding / Graphics as Principal Character（约 2024–2044、2730–2736 行）
  source_quote: |
    “Rainbow color gradients have been falling out of favor… print… in grayscale.”；重设计水汽地图时“the gradient is truer to the continuous nature of the data… dotted line and label”标出关注区；Nature hockey-stick 图原说明包含 raw data、reconstruction 与 ±2σ uncertainty limits。
  summary: |
    连续变量采用能表达连续性的明度变化，而非彩虹伪序；关键区域用点线和标签引导注意。气候曲线同时区分原始数据、重建线与 ±2σ 不确定性边界，示范视觉编码必须保留数据证据层次。
  bound_to: [数据编码, 配色可验证性, 不确定性, 注释]
  outcome: 原文建议灰度打印检验；hockey-stick 图后续研究以不同方法支持其信息，原文未要求仿制其造型。
  tags: [case, color, uncertainty, data-plot]

- id: c05
  title: 误差条变化的解释性图解
  type: case
  example_kind: firsthand_design_process
  source_chapter: Chapter 15/数据故事段落（约 3416–3420 行）
  source_quote: |
    “included a chart plotting the measurements over time for each method, including error bars… an explanatory diagram on precision… acknowledge why uncertainty exists… and some ways in which uncertainty can be reduced.”
  summary: |
    时间序列保留误差条，并增加解释图拆解误差变小的两种原因：离散测量次数增加，或单次测量分辨率提升。图表与机制图协同，使不确定性成为故事的一部分。
  bound_to: [误差表达, 机制解释, 图表组合, 科研叙事]
  outcome: 原文称其帮助读者理解误差条随时间变化；不外推统计结论。
  tags: [case, error-bars, explanatory-diagram]

