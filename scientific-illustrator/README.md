# scientific-illustrator

科研插图执行技能。独立使用时，从论文片段或用户描述提取事实锁、故事板、视觉语法和负面约束，输出 AI 绘图 Prompt、分轮迭代方案和 SVG/Visio/Illustrator 图层计划。

适合机制图、医学示意图、技术路线图、系统架构图和空间过程图。真实数据、统计数值和显著性必须由数据绘图工具生成。

可选联合：接收 `scientific-figure` 的 `FigureSpec + LayoutSpec`，完成插图执行；完成后把渲染预览和 `rendered_unknowns` 交回版式技能检查。

入口文件：[SKILL.md](SKILL.md)
