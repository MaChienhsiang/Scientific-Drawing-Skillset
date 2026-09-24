# Scientific Figure Skills

三个科研绘图技能可以单独使用，也可以按需串联。默认先让最匹配的技能独立完成任务；只有任务跨越多个专精范围时才交接。

## 选择技能

| 技能 | 首要问题 | 典型输出 |
|---|---|---|
| `scientific-plot` | 数据和读者任务应该用什么图形与编码表达？ | 图型判断、编码表、DataEncodingSpec |
| `scientific-figure` | 读者如何阅读整张 Figure，版面如何组织？ | 故事板、网格、面板、字体、LayoutSpec |
| `scientific-illustrator` | 如何生成和编辑科研示意图？ | PromptPack、负面约束、迭代方案、可编辑图层 |

## 可选联合流程

```text
scientific-plot → DataEncodingSpec
                 ↓
scientific-figure → LayoutSpec
                 ↓
scientific-illustrator → PromptPack / editable plan
                 ↓
scientific-figure → publication review
```

三个技能共享 `FigureSpec v1` 字段：`task`、`claim`、`audience`、`figure_type`、`data_facts`、`encodings`、`relations`、`reading_path`、`unknowns` 和 `publication`。下游必须保留上游事实，不得补造数据、机制、结构或统计结论。

## 安装

将需要的技能目录复制到宿主的 skills 目录。单独使用时只安装对应目录即可；联合使用时安装三个目录。每个目录的 `SKILL.md` 是运行入口，`README.md` 说明专精范围，`evals/evals.json` 提供触发与边界测试。

## 学术边界

三个技能都禁止把 Emoji、过度装饰的卡通 Icon、营销元素、花哨渐变和无语义特效引入论文图；都禁止臆造数据、显著性、坐标、机制或引用。Nature Reviews 等期刊要求必须根据目标期刊当期指南单独核对。
