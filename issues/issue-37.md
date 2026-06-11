# 生统爱好者周刊（第 37 期）：当 AI Agent 成为新的软件范式

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260611234359.png)

## 本周话题：[当 AI Agent 成为新的软件范式](https://mp.weixin.qq.com/s/JZQHliFgnx_ZobU7XL4UWw)

Agent 的价值不仅是提高编码效率，而是将软件从“静态代码系统”转变为“动态推理系统”，使用户直接表达目标，由 Agent 自主规划、执行和交付结果。未来工程师的核心能力将从编写代码转向意图表达、Agent编排、质量治理和系统监督。

## 生统研究

1. [Nature Medicine | 一项关于迷幻药对大脑回路功能影响的国际大型分析](https://mp.weixin.qq.com/s/msHxYt86Dqjk0X2igv2bGg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260611231716.png)

在该项国际多中心Mega-analysis研究中，整合11个静息态fMRI数据库、267名受试者和5种经典迷幻药（Psilocybin、LSD、DMT、Ayahuasca及Mescaline）数据，采用统一预处理流程和贝叶斯层级模型分析迷幻药对脑功能连接的影响。结果发现，迷幻药最稳定的神经特征是增强默认网络、额顶网络与视觉及感觉运动网络之间的连接，并增强纹状体与皮层间耦合，提示其通过削弱大脑层级结构、促进跨网络信息整合改变意识状态。该研究为迷幻药辅助精神疾病治疗提供了重要神经生物学依据。

- 论文 DOI：10.1038/s41591-026-04287-9

2. [Nat Rev Neuro | 基于人工智能对大脑和行为动力学进行联合建模](https://mp.weixin.qq.com/s/6x5WrR1jheax9sb9ZM1-og)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260611232503.png)

Mathis等于2026年在《Nature Reviews Neuroscience》发表综述，系统总结人工智能驱动的脑-行为联合建模（Joint Brain–Behaviour Modelling）研究进展。作者提出，神经科学正从单纯研究脑活动转向同时整合神经数据与行为数据，通过判别模型、生成模型和对比学习模型挖掘两者共享的潜在动态结构。文章重点介绍了姿态估计、行为分割、多模态大模型等技术在行为量化中的应用，并展望神经科学基础模型（Foundation Models）和数字孪生脑的发展前景。该框架有望推动脑机接口、精神疾病研究及精准医学的发展。

- 论文 DOI：10.1038/s41583-025-00996-1

## 博文资讯

3. [Codex 接入 Zotero：让 AI 从你的文献库里找参考文献](https://mp.weixin.qq.com/s/x-Kc6tH2DpqeQXpPHURxxQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260611233013.png)

介绍了 Codex 与 Zotero 插件的集成应用，帮助研究人员直接从个人 Zotero 文献库中检索和管理参考文献。与传统AI依赖网络搜索不同，Zotero 插件将检索范围限定在用户已收藏和整理的文献条目中，从而降低引用错误和虚构文献的风险。文章演示了插件安装、账号授权、文献列表读取、利用 Zotero 条目 Key 精准定位文献以及自动生成参考文献格式并写入 Word 文档的流程。

4. [大脑智能的本质，是一个不断校正的内部世界](https://mp.weixin.qq.com/s/8r_ZsMtHjBdUKjnz2-2Jtw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260611233225.png)

围绕神经科学中的内部模型（Internal Model）理论展开，系统阐述了大脑如何通过预测、误差校正和持续更新来构建对身体与环境的内部表征。文章介绍了前向模型（Forward Model）和逆向模型（Inverse Model）的经典框架，以及小脑、基底节、海马和前额叶在不同层级内部模型中的作用。进一步将 Internal Model 与认知地图（Cognitive Map）、生成模型（Generative Model）和世界模型（World Model）联系起来，分析其在预测编码、主动推断和具身智能中的意义。作者认为，未来类脑AI的发展方向应从静态模式识别转向具备预测、规划、学习和内部模拟能力的世界模型智能体，从而实现更接近生物智能的认知与决策能力。

## 工具

5. [使用 rstanarm 估计纵向数据和生存时间数据的联合模型](https://cran.r-project.org/web/packages/rstanarm/vignettes/jm.html "rstanarm 联合模型教程")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260611233624.png)

rstanarm 包中 stan_jm 函数的官方应用文档，介绍如何在贝叶斯框架下构建联合模型（Joint Model），同时分析纵向重复测量数据和生存结局数据。文档详细说明了纵向子模型、事件子模型及关联结构的设定，并展示动态风险预测、个体生存概率预测及多结局联合建模等功能。该方法适用于生物标志物轨迹与死亡、疾病进展等时间结局之间关联的研究。

6. [Claude Cowork 使用说明](https://mp.weixin.qq.com/s/u02DHk2Lasi45JHAlOha5g)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260611233831.png)

Claude Cowork 是 Anthropic 于 2026 年推出的桌面端 AI 智能体工作模式，面向非程序员知识工作者。与传统聊天机器人不同，Cowork 不仅提供建议，还能直接访问授权文件夹，自主拆解任务、调用工具、处理文档，并生成 Excel、Word、PPT 等可交付成果。它支持本地文件管理、网络研究、定时任务、项目记忆及多工具连接，强调“描述目标，委派任务，验收结果”的工作方式。其核心价值在于将用户从重复性操作中解放出来，转向监督、决策与成果评估。

## 资源

7.[Obsidian Sketch Your Mind社区](https://community.sketch-your-mind.com/t/welcome-to-the-sketch-your-mind-community/353 "Obsidian Sketch Your Mind社区")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260611234037.png)

Sketch Your Mind（SYM）是由 Obsidian Excalidraw 插件开发者 Zsolt Viczián 创建的视觉知识管理（Visual PKM）学习社区，致力于帮助用户通过可视化思维提升学习、研究、写作与决策能力。平台围绕 Obsidian 与 Excalidraw 构建完整生态，提供 Excalidraw Essentials 入门课程、Excalidraw Mastery 深度课程、Visual PKM 工作坊以及 Sketch Your Life 思维工具体系。社区还汇集了大量视频教程、课程讲义、案例展示和成员交流内容，涵盖视觉笔记、思维导图、PDF批注、知识管理与AI工作流等主题。对于希望将 Obsidian 从“笔记工具”升级为“可视化第二大脑”的学习者而言，SYM 是当前国际上最具影响力的 Visual PKM 资源平台之一。

8. [PKMer知识管理开源社区](https://github.com/PKM-er "PKMer知识管理开源社区")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260611234217.png)

PKMer（PKM-er）是国内具有影响力的知识管理（Personal Knowledge Management, PKM）开源社区，致力于推广知识管理理念、数字笔记方法和效率工具应用。社区以 Obsidian 生态为核心，长期维护 Blue Topaz 主题、Obsidian Surfing、Editing Toolbar 等多个知名插件和项目，同时建设中文知识库、数学知识库及插件导航资源。PKMer倡导开放分享、协作共建和持续学习的社区文化，鼓励用户围绕知识组织、科研学习、写作创作和个人成长开展实践与交流。其网站（pkmer.cn）已成为中文 Obsidian 用户获取教程、插件评测和知识管理经验的重要平台之一。

## 贡献者（GitHub ID）

「OpenBioStat 生统爱好者周刊」运维小组：

- [`@Leslie-Lu`]（陆震）
- [`@YihanChen325`]（陈奕含）
- [`@kirihsia`]（夏鑫辛）
- [`@GCRPM`]（徐林玉）

## 订阅

本周刊每周五发布，更新在微信公众号「陆震生物统计」（luzhen-biostat）上，微信搜索`陆震生物统计`或者扫描二维码，即可订阅。

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251113212819.png)

同时，本周刊同步支持 [RSS 订阅](https://leslie-lu.github.io/biostat_weekly_rss.xml "生统爱好者周刊 RSS 订阅")；本周刊同名中文播客现已正式在[苹果播客（Apple Podcasts）](https://podcasts.apple.com/cn/podcast/%E7%94%9F%E7%BB%9F%E7%88%B1%E5%A5%BD%E8%80%85%E5%91%A8%E5%88%8A/id1868591486?l=en-GB "Apple Podcasts 订阅")和[小宇宙](https://www.xiaoyuzhoufm.com/podcast/69650caa93e769238063a05e "小宇宙订阅")平台上线，搜索`生统爱好者周刊`即可订阅收听。该播客内容基于本周刊公开内容制作，相关学术论文链接及原始资讯请查阅本周刊文字版。

（完）
