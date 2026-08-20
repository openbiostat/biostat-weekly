# 生统爱好者周刊（第 47 期）：mRNA个性化癌症疫苗的突破意味着什么？

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub:
[openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交
issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260820231449.png)

## 本周话题：[mRNA个性化癌症疫苗的突破意味着什么？](https://mp.weixin.qq.com/s/2wtOHHedHCko6fdQx9TJZQ)

Moderna与默沙东联合研发的个性化mRNA癌症疫苗在大型三期临床试验中取得成功，这标志着肿瘤免疫治疗领域迎来里程碑式突破，并验证了mRNA技术在呼吸道疾病之外的巨大商业潜力。目前，Moderna与默沙东的INTerpath系列项目已包含9项二期和三期临床试验，覆盖非小细胞肺癌、膀胱癌和肾细胞癌等多个瘤种。市场正密切关注即将公布的详细数据，以及预计在2026至2027年间出炉的其他癌种临床结果，这将最终决定mRNA癌症疫苗能否从科学"圣杯"全面走向临床现实。

## 生统研究

1. [npj Digital Medicine \|
   利用语言模型实现专家级医学文本验证](https://mp.weixin.qq.com/s/g5gf7KJ7d8hMZmfMeoGrUQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/s41746-026-03084-5_reference.png)

来自斯坦福大学的团队，在 npj Digital Medicine 发表了题为 Toward expert-level
medical text validation with language models 的研究。他们提出
MedVAL：不让模型直接替医生下结论，而是让它在另一段医疗文本即将进入工作流前，先判断其中有没有会影响使用安全的事实偏差，并给出是否应升级给医生复核的风险等级。作者想回答的问题：当医疗大模型已经能写摘要、改写报告、回答用药问题时，如何以可扩展的方式判断它这一次写得能不能用？

- 论文 DOI：10.1038/s41746-026-03084-5

2. [Nature Reviews Genetics \|
   AI驱动的基因组与电子健康记录多模态整合：从数据基础到临床实施](https://mp.weixin.qq.com/s/JdloLYjmws-TTFOasbb9rg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260820232626.png)

面对基因组、多组学与电子健康记录（electronic health
record，EHR）长期各自为阵的问题，本文梳理人工智能（artificial
intelligence，AI）和机器学习（machine
learning，ML）如何从数据标准化、表型构建走向多模态整合与临床决策，并归纳疾病异质性、标志物与治疗靶点、风险预测等用途。

- 论文 DOI：10.1038/s41576-026-00992-w

## 博文资讯

3. [当精准营养遇上AI，它离'数字孪生'还有多远？](https://mp.weixin.qq.com/s/k1GHH7GPZ8ud4b5heB6S1g)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260820232851.png)

精准营养的核心矛盾是：每个人对同一膳食的代谢反应差异巨大，而要把这种个体差异转化为可执行的建议，需要整合基因组、微生物组、代谢组、生活方式等多源数据。这篇
Perspective 提出的问题是------AI/ML
能否成为打通'多组学数据'到'个体化营养干预'的关键方法层？它还差哪些拼图？

4. [为什么"健康饮食"仍可能不可持续？](https://mp.weixin.qq.com/s/DItO7EeSW2C4JpdRhGt1Qw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260820233238.png)

一个更加关键的问题始终缺少系统回答：如果把人体健康和地球生态承载能力同时作为约束条件，一个普通人的饮食究竟应该如何设计？这正是本文试图解决的问题。相比于已有研究关注"哪种饮食更环保"，作者进一步提出：真正的可持续饮食，不应只是相对减少环境影响，而应真正控制在地球能够承受的生态边界以内。

## 工具

5. [Claude for Healthcare](https://mp.weixin.qq.com/s/1XGMSJwV970fkMPfMg5kHw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260820233406.png)

Claude for
Healthcare是Anthropic推出的面向医疗机构的AI平台，旨在为医疗服务提供者、保险公司和消费者提供符合HIPAA标准的人工智能服务
。将Claude的推理能力与安全、合规的临床和行政工作流深度整合，是包含原生数据连接器、HIPAA就绪基础设施和预置工作流技能的解决方案。

6. [biomcp，给 Claude Code
   装上医生工具包](https://mp.weixin.qq.com/s/cfmYW22pmZTqklN1FUzTzg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260820233550.png)

biomcp把PubMed、ClinVar、ClinicalTrials.gov、OncoKB、Reactome 等 30
个生物医学数据源整合成MCP（Model Context Protocol）服务器，可以直接在 Claude
Code、Codex、Claude Desktop 中当工具使用，搜索生物医学数据源中的信息。

## 资源

7. [用 AI for Medicine 入门医学
   AI](https://mp.weixin.qq.com/s/by1Y4GNZjtu4DBlKuVqa-g)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/AIforMedicine.png)

AI for Medicine 由 Stanford 团队（DeepLearning AI
出品）制作，是面向有基础者的医学 AI
专项，分三个方向：医学影像、电子病历、基因组学。它把临床问题与机器学习方法对应起来，带你理解每种任务用什么模型、数据从哪里来、结果怎么解读。对生物与医学背景的同学，它是连接本专业与
AI 的桥梁，比通用课更贴近真实应用场景。

8. [Aging Biobank数据库](https://mp.weixin.qq.com/s/UACQsjVPVI0Jdah7vTU90g)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260820234032.png)

国家生物信息中心联合中国科学院动物研究所共同打造的Aging
Biobank数据库系统正式上线运行。Aging
Biobank是面向人类衰老研究的公共数据资源平台，旨在系统整合、规范管理和开放共享衰老相关的多维数据资源，为衰老标志物发现、衰老时钟构建、器官衰老评估、生活方式与衰老关联分析，以及衰老干预研究提供数据支撑。

## 贡献者（GitHub ID）

「OpenBioStat 生统爱好者周刊」运维小组：

- [`@Leslie-Lu`]（陆震）
- [`@YihanChen325`]（陈奕含）
- [`@kirihsia`]（夏鑫辛）
- [`@GCRPM`]（徐林玉）
- [`@Jinyu-Luo`]（罗瑾瑜）

## 订阅

本周刊每周五发布，更新在微信公众号「陆震生物统计」（luzhen-biostat）上，微信搜索`陆震生物统计`或者扫描二维码，即可订阅。

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251113212819.png)

同时，本周刊同步支持 [RSS
订阅](https://leslie-lu.github.io/biostat_weekly_rss.xml "生统爱好者周刊 RSS 订阅")；本周刊同名中文播客现已正式在[苹果播客（Apple
Podcasts）](https://podcasts.apple.com/cn/podcast/%E7%94%9F%E7%BB%9F%E7%88%B1%E5%A5%BD%E8%80%85%E5%91%A8%E5%88%8A/id1868591486?l=en-GB "Apple Podcasts 订阅")和[小宇宙](https://www.xiaoyuzhoufm.com/podcast/69650caa93e769238063a05e "小宇宙订阅")平台上线，搜索`生统爱好者周刊`即可订阅收听。该播客内容基于本周刊公开内容制作，相关学术论文链接及原始资讯请查阅本周刊文字版。

（完）
