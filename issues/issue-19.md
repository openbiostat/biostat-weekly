# 生统爱好者周刊（第 19 期）：ChatGPT眼里的中国统计与公共卫生统计

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/640.jpg)

## 本周话题：[ChatGPT眼里的中国统计与公共卫生统计](https://mp.weixin.qq.com/s/tlLUztVAeAubGxByo62bFw)

中国统计学界与公共卫生、临床试验统计之间联系非常有限：学术谱系分化、评价与激励机制不一致，以及教育体系和机构设置的长期分割，使两边逐渐形成各自封闭的专业世界，彼此缺乏共同语言。随着真实世界证据、AI 与医疗融合以及国际多中心研究不断推进，统计方法正被迫直面更复杂、更真实的问题，这也在客观上为生物统计这样的中间领域创造了空间。统计作为应用学科，不能把发表顶刊顶会当作终点，而应以解决药物研发、疾病防控等现实问题为起点，在实践中孕育方法和理论，否则过度抽象只会让学科看似繁荣、实则逐步边缘化。

## 生统研究

1. [Nature Genetics | 你选什么专业，基因说了算？](https://mp.weixin.qq.com/s/l3Qa4EMaB-rQT2Xvmuqn_Q)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260129153111.png)

在人生的诸多十字路口中，专业选择无疑是最关键的一个。它像一个无形的筛选器，不仅塑造了我们的知识结构和职业生涯，更深刻地影响着我们的思维方式、社交圈层，乃至未来的家庭与生活。每当填报志愿或回首往事时，我们总会用家庭背景、个人兴趣、社会趋势或经济回报来解释自己的选择。但你是否曾想过，在这场关乎未来的重大抉择背后，是否还存在着一种更古老、更深邃的力量，来自我们基因的“轻语”？

为探讨基因与专业选择间的关联，研究团队利用芬兰和挪威的教育注册数据及其对应基因型信息，涵盖10类专业领域（如社会科学、人文艺术、商科、信息与通信技术、自然科学等），总样本规模超过46万，每类从约4万至31万不等。作者首先在控制教育水平（如最高学历）后，考察基因是否仍与专业类别显著相关。其次，采用兄弟姐妹或家庭内分析设计（within-family design），以排除家庭背景和群体分层等混杂因素。结果显示，这些基因关联在家庭内也部分存在，表明至少部分效应源于“直接遗传作用”，而非完全受社会或地理结构影响。

- 论文 DOI：10.1038/s41588-025-02391-z

2. [JAMA Network Open | 有向无环图的构建及其在顶尖医学期刊中的应用](https://mp.weixin.qq.com/s/Hye52QbaBPweGxbYVfQUdQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260129153521.png)

该研究基于对四大医学顶刊的系统评价发现，当前临床研究中有向无环图（DAG）的构建透明度和应用一致性普遍不足，许多研究未在设计阶段使用DAG，也缺乏对因果关系假设的明确证据说明，且理论设定与实际分析常不一致。结果表明，尽管DAG在因果推断中的价值已被广泛认可，其规范化应用仍有较大提升空间，未来需将其更系统地纳入证据评估框架并加强报告与决策依据的清晰性，以提升研究可信度。

- 论文 DOI：10.1001/jamanetworkopen.2025.53803

3. [Fundamental Research | 健康生活方式可缩小由社会经济差异导致的老年健康不平等，显著提升晚年生活质量](https://mp.weixin.qq.com/s/frfBBk5BAs97nkSWMVKkhw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260129154313.png)

该研究基于长达20年的全国前瞻性队列研究，系统剖析了社会经济地位与健康生活方式对老年人死亡和健康老龄化的影响。研究发现，低社会经济地位群体在预期寿命和健康老龄化上均存在显著劣势，但无论个体处于何种社会经济地位，维持健康生活方式都是延长总预期寿命、提升健康预期寿命的重要途径，能够有效缓解社会经济差异带来的健康不平等。该研究为破解“健康鸿沟”提供了可落地的个体干预突破口，为我国应对人口老龄化和促进健康老龄化实践提供了重要的科学证据。

- 论文 DOI：10.1016/j.fmre.2025.10.004

## 博文资讯

4. [印度尼帕病毒疫情](https://mp.weixin.qq.com/s/WthX0fI3LZcFgKqWzY60Mw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/640.webp)

近期，多家媒体报道印度东部的西孟加拉邦出现尼帕病毒感染病例，目前已有5例确诊病例，其中包括医护人员，已有近百人被要求居家隔离，地方风险持续存在，已引起了全球卫生界的广泛关注。目前，国内尚无尼帕病毒感染病例报告，注意防范潜在风险，不必恐慌。

5. [腾讯开发者 | Transformer架构原理解析](https://mp.weixin.qq.com/s/8m7HlMBDIC1ekMDnb5F8ww)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/642.webp)

这篇深入浅出的文章旨在解析大型语言模型（LLM）的智能来源，核心聚焦于其基础架构——Transformer的原理与构造。文章详细阐述了模型如何通过分词、词嵌入和位置编码将离散文本转化为可计算的连续向量，并强调了注意力机制在捕捉序列中复杂依赖关系中的关键作用。此外，它深入剖析了由自注意力层和前馈网络组成的解码器结构，并介绍了当前旗舰模型中采用的 MoE 混合架构等前沿设计，以提高效率和性能。

6. [PageRank 算法](https://en.wikipedia.org/wiki/PageRank "PageRank - Wikipedia")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260129155849.png)

PageRank 是一种用于衡量网页（或网络节点）重要性/影响力的链接分析算法，最早由 Larry Page 与 Sergey Brin 在斯坦福大学读博期间提出，后来成为 Google 早期搜索引擎排名的核心技术之一。虽然起源于网页搜索，PageRank 很快被推广到各种网络分析中：学术网络：论文/作者影响力；生物网络：基因、蛋白相互作用重要性；社交网络：节点中心性；医学信息学：文献证据权重、知识图谱推理。本质上，PageRank 是一种基于图结构的全局中心性指标。

## 工具

7. [Clawdbot快速入门部署教程](https://mp.weixin.qq.com/s/todjN0Vw_9e5nlcO8moG7g)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260129160415.png)

最近Clawdbot这个项目在技术圈彻底火了，GitHub上两周狂揽49k+ stars，甚至还带火了Mac Mini的销量。这篇文章带大家快速上手Clawdbot，搭建一个真正7x24小时运行的个人AI助手。

8. [Bioinfokit | python开源工具](https://github.com/reneshbedre/bioinfokit "Bioinfokit")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260129160117.png)

Bioinfokit是一款开源的生物信息学数据分析和可视化工具包，旨在为基因组学实验产生的生物数据提供一系列易于使用的功能。

9. [lets-plot | python开源工具](https://github.com/JetBrains/lets-plot "lets-plot")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260129160222.png)

## 资源

10. [神经影像数据分析的统计学习方法及其应用](https://www.youtube.com/watch?v=kSuP5_x8B4g "神经影像数据分析的统计学习方法及其应用 - YouTube")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260129160618.png)

从常见神经影像技术出发，梳理影像数据在个体层面与人群层面的分析框架，系统回顾大型影像研究与影像基因组学联盟，总结当前主流统计方法及其面临的核心挑战与最新方法进展。

11. [Modern Statistics for Modern Biology](https://web.stanford.edu/class/bios221/book/ "Modern Statistics for Modern Biology")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260129160746.png)

该书旨在帮助从事生物研究的科学家快速掌握许多重要的概念和方法，从而最大限度地利用实验和其他可用数据。采用实践性强的教学方法，叙述围绕各类问题或特定数据类型展开。方法和理论的介绍也遵循“需要掌握”的原则，而非从基本原理出发进行系统推导。

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
