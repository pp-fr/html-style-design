---
name: html-style-design
description: 生成或改版独立 HTML 文档时，按文档用途选择并沿用实际样稿的展示样式。适用于演讲稿、课件、报告、案例申报、操作手册、方案、计划和纪要。
---

# HTML 样式设计

## 按文档类型选版式

- 默认交付本地单文件 HTML。用户指定格式、交付位置或样式时，按当次要求执行。
- 先判断谁使用这份文档、在什么场合使用、打开后要做什么，据此确定整份文档的阅读顺序、主版式和导航。遇到混合用途，按主要用途选版式，次要用途用附录或独立章节承载。未列出的文档按最接近的用途匹配。
- 用户指定的样稿或主题优先。其他情况按下表找对应的 Skill 和可打开的实际样稿。对应 Skill 未安装时，查看表中引用的上游样稿或项目里同用途的成品。只取得结构说明时，说明样稿缺失，按最接近的可用样稿定位展示方向。

| 文档类型 | 整份 HTML 的版式与顺序 | 样式参考 |
| --- | --- | --- |
| 演讲稿、主持稿 | 提词稿式。单栏大字、短段，按现场顺序排。用时、停顿、转场和上台动作与口播正文用不同样式呈现。 | [presentation-script-coach](https://github.com/archlizheng/presentation-script-coach/blob/main/SKILL.md) 的提词器与提示卡 |
| 现场授课、宣讲课件 | 横向翻页式。一页讲一个重点，按讲解、演示、练习安排节奏。 | [guizang-ppt-skill](https://github.com/op7418/guizang-ppt-skill) 的电子杂志或瑞士国际主义模板。延续 B 版课堂动效时，用已安装的 `training-html-motion` 及其互动模板，并读[现场课件设计](references/training-slides.md)。 |
| 工作汇报、项目复盘 | 纵向报告式。首屏放结论和需拍板事项，往下看依据、问题、改进建议与后续安排，长文用固定目录。 | [agent-html](https://github.com/QingYunA/agent-html/blob/main/skills/agent-html/SKILL.md) 的报告母版 |
| 流程讲解、操作手册 | 逐步操作式。先给流程总览，再按实际顺序展开。每步标出操作入口、动作和完成标志，按需配截图；跨岗位流程标明交接。 | [overment/explainer](https://github.com/overment/skills/blob/main/skills/explainer/SKILL.md) 的逐步走读和泳道 |
| 培训方案、项目提案 | 决策简报式。先给目标和推荐方案，再列实施安排、所需资源、风险和待定事项。 | [html-artifacts](https://github.com/joshuadavidthomas/agent-skills/blob/main/html-artifacts/SKILL.md) 的文档模式可改造 |
| 课程大纲、执行计划 | 进程安排式。先给全程总览，按天或阶段列目标、内容、负责人和交付物，以现有信息为准。 | [agent-html](https://github.com/QingYunA/agent-html/blob/main/skills/agent-html/SKILL.md) 的报告母版可改造 |
| 会议纪要、任务交接 | 决议与行动清单式。先看决定、负责人、期限和未决事项，讨论细节或交接背景在后。 | [html-artifacts](https://github.com/joshuadavidthomas/agent-skills/blob/main/html-artifacts/SKILL.md) 的文档模式可改造 |
| 调研报告、案例分析、案例申报 | 长文阅读式。按问题、发现、证据和启示展开，保留出处和不确定项。案例申报首屏呈现阶段、本人贡献和证据入口。 | [interactive-report](https://github.com/yanyuliu01/interactive-report/blob/main/.claude/skills/interactive-report/SKILL.md) 的长文报告样式 |
| 常见问题、培训速查 | 查阅式。按使用场景分组，短答案先给，详细操作按需展开，内容多时加目录。 | [agent-html](https://github.com/QingYunA/agent-html/blob/main/skills/agent-html/SKILL.md) 的目录和折叠章节可改造 |

- 同一套培训材料可以生成不同版式。领导审阅用纵向报告，讲师上台用提词稿，投屏授课用横向课件，学员课后跟做用操作手册。
- 频繁更新的系列课件可参考 [Slidev 官方主题](https://github.com/slidevjs/themes)。图文路演、作品展示可参考 [WebSlides](https://github.com/WebSlides/WebSlides)。

## 沿用样稿的展示样式

- 打开所选样稿的首屏和代表内页，核对页面比例、标题与正文层级、网格、留白、色彩、导航和典型组件。用本次内容做首屏和代表内页，再展开全篇。说明沿用了哪些具体样式。纵向报告或横向翻页是阅读方式，样稿的构图和组件决定页面实际长什么样。
- 找准每类页的阅读焦点，按样稿的视觉体系安排构图。时间顺序用步骤或时段，前后变化用对照，演示用实际输入、操作和结果。交互用于逐步走读、切换比较或回放，保留能直接查看的关键内容。
- 样稿太密或不适合当前内容时，优先调整页间拆分、比例和组件用法。样式方向仍有歧义时，可以用同一段真实内容做两种构图供比较。按源码核对外部依赖、许可和归属。离线单文件内嵌必要资源。
- 样式改版默认保留事实、数字、来源和未核实说明。需要压缩时，将参考资料放在末页或折叠区。涉及重大视觉调整，先用封面和代表性内页做高保真样稿供确认。用户已授权直接产出时，可以另存一份完整样稿供比较。
- 翻页课件提供可见的上一页、下一页和选页入口。移动端内容放不下时允许正文滚动，避免滚轮误翻页。正文、导航和页脚在浅深两种背景上都要可读。

## 交付前验收

- 在浏览器打开实际交付文件，对照样稿看首屏、典型正文和内容最密的一页。按使用场景检查桌面、约 390 像素宽的窄屏或投屏，确认视觉焦点、层级、对比、字号、换行、留白和截图可读性。
- 翻页课件实测按钮、方向键、目录跳转。阅读页实测锚点和折叠。要求离线时断网或屏蔽外部请求验证。
- 与来源稿核对日期、课时、链接和缺项说明。按用户指定位置保存，只汇报实际检查过的功能。
