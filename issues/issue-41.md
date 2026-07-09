# 生统爱好者周刊（第 41 期）：AI时代，你和导师的知识差距消失了！真的吗？然后呢？

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

## 本周话题：[AI时代，你和导师的知识差距消失了！真的吗？然后呢？](https://mp.weixin.qq.com/s/y4v-4P9rZprWfwUGUwOy7w)

现在任何人都可以在十分钟内，借助大模型拿到一个领域的知识骨架、方法论谱系和关键争议。知识获取的成本趋近于零，意味着以知识储量为壁垒的竞争模式失效了。学生在知识竞争这一块，几乎与老师平权了。当所有人面对的信息都一样多，那差异从哪来？导师拿什么继续领先学生？学生又拿什么超越同龄人？

## 生统研究

1. [Nature | 11种自闭症小鼠模型同时比较，早期皮层发育出现共同偏移](https://mp.weixin.qq.com/s/gSBjfNb6D37iFi6fngLoFQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260709221001.png)

研究团队把 11 种单基因自闭症小鼠模型放在同一个发育坐标系里，覆盖胚胎期 E14.5、出生后 P4 和 P14 三个时间点，同时纳入雌雄个体、前脑和小脑，并用单核多组学同时读取基因表达和染色质开放状态。最后，他们得到的是 251 个样本、超过 20 万个细胞核的发育图谱。

不同自闭症风险突变并不会简单造成同一种永久性损伤，它们更像是在早期皮层发育中共同拖慢了放射状胶质细胞谱系的推进，并在出生后神经元成熟阶段反复影响突触和离子通道相关程序。

- 论文 DOI：10.1038/s41586-026-10679-1

2. [BMJ | COVID-19 诊断和预后模型的质量评价](https://www.bmj.com/content/369/bmj.m1328 "COVID-19: a review of diagnostic and prognostic models")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260709221530.png)

2020 年初，具有健康研究中预测和预后建模经验的研究者发表了一篇关于 COVID-19 诊断和预后模型的综述。这篇综述不仅因其覆盖范围广而有意思，也因为被评为质量较差的模型数量惊人：“[232] 个模型被评为偏倚风险高或不明确，主要原因包括对照患者选择不具代表性、排除了在研究结束时尚未经历感兴趣事件的患者、模型过拟合风险高以及报告不清楚。”这项研究也是一项动态综述。

- 论文 DOI：10.1136/bmj.m1328

## 博文资讯

3. [OpenAI给语音AI补上“眼力见”](https://mp.weixin.qq.com/s/-M_2IBJN_Cl297bAeYsgZQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260709220112.png)

GPT-Live 是 OpenAI 面向实时语音交互推出的新一代 AI 语音模型，旨在提升人机交流的自然性与连续性。GPT-Live 通过全双工能力实现边听边说，可根据对话状态判断继续倾听、回应或调用工具，同时将自然交流与复杂任务执行分离，使语音模型负责互动体验，而推理模型负责搜索、分析和多步骤任务。该技术代表 AI 助手从简单问答工具向实时感知、主动协作型智能体的发展方向。

4. [流行病学视角: 2025年美国麻疹的死灰复燃](https://mp.weixin.qq.com/s/lkYt8_P2UqkIdqXXDQOIzg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260709220313.png)

从流行病学和系统视角分析2025年美国麻疹疫情复燃机制。该观点认为，麻疹病例快速增加与疫苗接种覆盖率下降、群体免疫屏障削弱及人口流动网络密切相关。由于麻疹具有较高基本再生数（R₀），维持95%左右免疫覆盖率是阻断传播的关键。文章强调，局部疫苗缺口在高度互联社会中可能引发区域甚至全国性传播，为公共卫生政策制定和传染病防控提供重要启示。

## 工具

5. [随机截距交叉滞后模型（RI-CLPM）](https://jeroendmulder.github.io/RI-CLPM/ "Random Intercept Cross-Lagged Panel Model (RI-CLPM)")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260709222043.png)

由乌得勒支大学 Jeroen D. Mulder 和 Ellen L. Hamaker 创建的随机截距交叉滞后面板模型（Random Intercept Cross-Lagged Panel Model, RI-CLPM）学习资源平台，用于辅助论文《Three Extensions of the Random Intercept Cross-Lagged Panel Model》的方法应用。该平台提供 Mplus 语法和 R（lavaan）代码，帮助研究者构建基础 RI-CLPM 及其扩展模型，包括时间不变预测因素、多组分析和多指标测量模型。网站同时提供模拟数据、模型比较方法及 GORICA 因果优势评价方法，适用于纵向数据中探索变量动态关系及个体内变化机制的研究。

## 资源

6. [AI-Assisted Statistics for Data Scientists](https://github.com/gedeck/ai-assisted-statistics-for-data-scientists)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260709222308.png)

于2026年出版3rd的数据科学统计学习指南。以 R 和 Python 为实践基础，系统介绍探索性数据分析、抽样与实验设计、回归分析、预测建模、机器学习、深度学习及生成式AI等核心内容。新版进一步融合 ChatGPT、Claude、Gemini 等大语言模型在统计工作流中的应用，帮助数据科学家理解AI原理、提升统计素养，并在真实数据分析和AI项目中实现更高效、可靠的建模实践。

7. [国家超算互联网核心节点正式上线](https://mp.weixin.qq.com/s/zVaNRBgwsJLDV95T6_OQWA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260709222613.png)

作为全国首个十万卡级超智融合算力资源池，核心节点的投运让郑州本地算力资源实现量级跃升，也让中原地区乃至全国用户获得面向大模型研发、科学智能体、AI4S、工业仿真、生物医药、网络安全等场景的先进算力支撑。而对于众多普通AI研发用户而言，过去需要复杂申请、专业部署和较高成本才能获得的超算、智算资源，正变得更容易获取与应用。

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
