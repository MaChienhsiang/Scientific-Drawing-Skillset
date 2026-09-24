# BSG 反例与边界提取（scientific-figure）

- id: ce01
  title: 把学科视觉术语当成通用语言
  type: counter-example
  source_chapter: Symbols / Arrows（约 1200–1251 行）
  source_quote: |
    “Symbols and colors can carry highly specific information within a specific context…”；若受众不懂箭头术语，“the arrow won’t be meaningful. Come up with another solution, or label things carefully.”
  failure_mode: 在跨学科科研图中未经解释地复用领域符号、颜色或箭头，读者无法解码关系。
  mechanism: 视觉变量的意义依赖共享约定；方向箭头还会暗示状态变化或因果，滥用会制造错误叙事。
  warning_signs: [标签与对象靠箭头相连但没有方向含义, 使用只在单一领域成立的符号, 未给图例或文字解释]
  bound_to: [视觉故事逻辑, 跨学科泛化, 箭头使用]
  tags: [counter-example, jargon, ambiguity]

- id: ce02
  title: 用默认彩虹渐变制造伪结构
  type: counter-example
  source_chapter: Color Coding（约 2024–2030 行）
  source_quote: “Rainbow color gradients have been falling out of favor… try printing things out on a black and white printer, or simply converting your digital file to grayscale.”
  failure_mode: 用彩虹色表达连续数据，导致亮度跳变、顺序关系失真，读者把色差当成真实边界。
  mechanism: 颜色感知与灰度顺序不稳定；连续变量应有单调、可解释的明度/色相变化，并通过灰度和印刷测试。
  warning_signs: [灰度打印后梯度顺序不保留, 图例颜色很难按数值排序, 颜色变化比数据变化更抢眼]
  bound_to: [配色规范, 数据图, 可访问性]
  tags: [counter-example, rainbow, misleading-encoding]

- id: ce03
  title: 为填满版面而添加“snazzy visual”
  type: counter-example
  source_chapter: Practical design guidance（约 3726–3770 行）
  source_quote: |
    “I’m not a fan of deciding to build a graphic because there’s room or money to spare and folks like the idea of filling it with a snazzy visual… If that’s your sole goal… a representative illustration, an editorial illustration, or a photograph might be more fitting.”
  failure_mode: 以吸睛或填空为目的堆叠图形，图表没有需要解释的科学关系。
  mechanism: 当内容目标缺席时，视觉装饰取代证据与结构；图形类型应由要传达的关系和受众决定。
  warning_signs: [先定风格后找数据, 删除装饰不影响任何解释, 图形只为“engagement”而无信息任务]
  bound_to: [内容优先, 克制设计, 图表类型选择]
  tags: [counter-example, decoration, purpose]

- id: ce04
  title: 把商业/新闻表达的装饰迁入学术图
  type: counter-example
  source_chapter: Practicalities / Nature content levels（约 2774–2790 行；约 418–439 行）
  source_quote: |
    Nature 区分“Original research articles with peer-reviewed visuals”“reviews… non-peer-reviewed visuals”“news items… non-peer-reviewed visuals”；另有案例称星系细节和大理石球体是面向休闲翻阅读者的“welcoming gesture”。
  failure_mode: 将新闻或大众传播场景允许的叙事性插画、卡通化细节、装饰性效果无条件用于同行评审科研图。
  mechanism: 目标受众、创作所有权和审稿层级决定设计介入程度；新闻视觉的吸引力策略不等于研究图的证据表达标准。
  warning_signs: [以“welcoming”或流量为唯一理由加入装饰, 用卡通/渐变替代变量编码, 未区分原始研究与新闻图的出版语境]
  bound_to: [学术边界, 专业克制, 视觉故事逻辑]
  tags: [counter-example, boundary, commercialization]
  note: 用户任务进一步规定科研绘图严禁 Emoji、过度装饰卡通 Icon、花哨渐变；BSG 原文仅说明新闻/大众语境中的允许范围，不能据此为学术图装饰辩护。

- id: ce05
  title: 只展示确定曲线而隐去不确定性
  type: counter-example
  source_chapter: Graphics as Principal Character / precision（约 2730–2736、3416–3420 行）
  source_quote: 原始 Nature 曲线说明同时列出 raw data、reconstruction 与“positive and negative 2σ uncertainty limits”；误差条解释图用于说明不确定性来源。
  failure_mode: 为追求干净或戏剧性，只画单一趋势线，省略原始数据、误差条或置信范围。
  mechanism: 读者会把估计当作精确事实，无法判断模型与观测、样本量和分辨率对结果的贡献。
  warning_signs: [没有误差/置信区间说明, 图注未区分原始与重建数据, 趋势线比不确定性带更突出且无解释]
  bound_to: [严谨数据图, 不确定性表达, 学术出版可靠性]
  tags: [counter-example, uncertainty, omission]
