# 生统爱好者周刊（第 44 期）：AI到底是什么？在临床试验里怎么落地？

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub:
[openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交
issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260730104206.png)

## 本周话题：[AI到底是什么？在临床试验里怎么落地？](https://mp.weixin.qq.com/s/JD1OZ_s9DCqb1EMxR_JCdQ)

封面故事里，插画师们在追问AI临摹的边界在哪里。[GenAI](https://mp.weixin.qq.com/s/8X1WYlssAO28RtRmfrwfkQ)
就像是一位手法娴熟的临摹专家，它见得多，模仿得像，但不会对结果负责。在临床医药研发领域，哪些工作能放心交给它打草稿？哪些必须留给人来终裁？这篇文章给出了一套简单好用的判断框架。

## 生统研究

1. [Statistics in Medicine \|
   纵向数据里的【信息性脱落】，如何用加权GEE进行修正？](https://doi.org/10.1002/sim.70674 "Statistics in Medicine")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260730105030.png)

临床试验里的数据缺失有多种类型，脱落（dropout）和失访（lost to
follow-up）是其中最容易混淆的两种，二者的区别可参考这篇[科普](https://mp.weixin.qq.com/s/3WQt1iUAbOVuFY2T2zCqDw)。当脱落原因本身与受试者健康结局相关时，称为信息性脱落（informative
dropout）。该论文以一项抗抑郁症临床试验数据为例：试验方案规定，若受试者在当前治疗阶段持续未达到疗效、或无法耐受不良反应，可以提前终止该阶段、转入下一治疗方案，这类脱落的发生本身就和疾病变化直接挂钩。现有的IIW-GEE（逆强度加权广义估计方程）虽然能够校正随访时间不规律的问题，但是权重估计没有考量脱落与结局之间的这层关联，一旦脱落是信息性的，估计结果便会产生偏倚。*本文提出的方法*，是将逆强度权重与逆脱落概率权重相乘，构建出扩展后的
IIW×IPW-GEE，并通过模拟研究证实这一方法能显著降低偏倚；应用于该试验数据后发现，若沿用原有方法、不校正信息性脱落，患者的病情改善程度会被系统性高估。

- 论文 DOI：10.1002/sim.70674

2. [Biometrics \|
   双相情感障碍移动健康研究中，如何在潜在疾病状态下估计个体因果效应？](https://doi.org/10.1093/biomtc/ujag131 "Biometrics")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260730105211.png)

双相情感障碍患者会在抑郁、轻躁狂、躁狂等不同情绪状态之间循环，同一种干预（比如运动、社交）对健康结局（比如睡眠）的影响，往往因患者当下所处的疾病状态不同而不同。本文使用一项移动健康研究的数据：受试者的通话与短信记录、GPS
位置、加速度计运动数据、每日情绪与症状问卷等，通过智能手机被动或主动地持续收集，用来连续追踪患者的日常状态。但这类数据里并不包含"患者现在处于哪种疾病状态"这一标签，它是需要被推断出来的潜变量，而非直接测量到的变量。本文提出一种改进的自回归隐马尔可夫模型（ARHMM），把疾病状态当作潜在变量来推断，同时处理数据缺失问题，并在个体层面（N-of-1）估计某项干预对结局的因果效应。模拟研究显示：忽略潜在疾病状态的传统方法会产生明显偏倚、置信区间覆盖率接近
0%；而本文方法基本无偏，覆盖率能达到理想水平。作者进一步将方法应用于一项长达五年的双相/精神分裂症患者智能手机追踪研究，成功从真实数据中识别出患者的抑郁/情绪稳定状态切换轨迹。

- 论文 DOI：10.1093/biomtc/ujag131

## 博文资讯

3. [Agent如何重塑医疗？AI已走进临床诊断、药物研发、管理健康全流程](https://mp.weixin.qq.com/s/xdL1Z2xXXvKJMwlbSjrU1Q)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260730105355.png)

2026世界人工智能大会上，机器人问诊、智能分拣送药这些消费端场景赚足了眼球，但这只是AI进医疗的"浅层形态"。真正的深水区，是AI智能体已经悄悄嵌进了诊断、新药研发和健康管理的全流程。

复旦中山医院的"观心大模型"是个例子：从最初只能看心脏病，到现在能整合心电图、超声影像、化验单等多模态数据，自动生成结构化病历。新药研发这边更卷，水木分子把研发链路拆成了好几个专属智能体（挖文献的、生成分子的、跑临床试验的），彼此之间还能"吵架"式地互相修正，形成一条自动化的智能管线。

不过医疗行业的容错率几乎是零，"沙发做歪了能改，人不行"。所以行业的共识很一致：智能体目前的定位是医生助手，不是拍板的人，真正难的不是把模型做大，而是让它在临床上足够准。

4. [Anthropic杀入AI制药的100天，药王礼来都开始慌了！](https://mp.weixin.qq.com/s/nDqIBtk5k9CQNfX4H57UOg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260730105443.png)

今年4月，Anthropic 以四亿美元收购了成立仅八个月的 AI 制药初创 Coefficient
Bio，随后挖来 AlphaFold 核心主创、诺贝尔化学奖得主 John
Jumper，并于6月30日发布面向科研的新产品 Claude
Science，宣布将自主推进临床前阶段的药物管线，聚焦传统药企不愿碰的罕见病靶点，近期又追加了一项罕见遗传病专项征集。这一系列动作让礼来等传统药企感到压力，其首席AI官
Thomas Fuchs 公开表示公司已自研开放权重模型，以掌控自身研发命运。

## 工具

5. [Cluster-Weighted Generalized Estimating Equations,
   CWGEE](https://doi.org/10.1111/biom.13050 "Cluster-Weighted Generalized Estimating Equations, CWGEE")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260730105550.png)

由多伦多大学Aya Mitani
教授创建的聚类加权广义估计方程R包，用于分析具有信息性聚类大小（informative
cluster size,
ICS）的聚类纵向数据，即每个聚类内观测数量本身与结局相关、可能导致普通 GEE
估计产生偏倚的场景。包中 ordCWGEE 函数适用于有序结局的聚类纵向数据，mvoCWGEE
函数适用于横断面下多个相关二分类结局的分析，二分类结局的加权版本仍在开发中。该方法最初发表于论文
Marginal analysis of ordinal clustered longitudinal data with informative
cluster size（Mitani, Kaye, Nelson, 2019, Biometrics）。

R 包安装：`remotes::install_github("AyaMitani/CWGEE")`

- 论文 DOI：10.1111/biom.13050

6. [Mole: 通过终端清理、卸载、分析、优化和监控您的
   Mac](https://github.com/tw93/Mole "Mole")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260730110023.png)

一体化工具包，深度清理，智能卸载程序，磁盘洞察，实时监控 mac。

## 资源

7. [Pharmaverse: 临床试验数据流程的开源 R
   包生态](https://pharmaverse.org/ "Pharmaverse")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260730110137.png)

由 GSK 的 Michael Rimler、Roche 的 Ross Farrugia、Atorus 的 Mike Stackhouse 和
Janssen 的 Sumesh Kalappurakal 于2021年前后共同发起，最初的愿景是打造一套"从 CRF
到电子提交"全流程的开源 R
包工具栈，避免各大药企在标准化临床工作流上重复造轮子。目前已汇聚
admiral（SDTM→ADaM 映射）、sdtm.oak（SDTM
数据集生成）、tidyCDISC、rtables、Tplyr、xportr（XPT
文件生成与合规校验）等数十个包，覆盖数据收集、验证、分析到监管提交的完整链路，并与
Tidyverse 无缝集成。项目隶属于 PHUSE，社区与 FDA、EMA、R Consortium、CDISC
保持合作对接，Slack
频道已有千余名成员。各包相对独立，团队可以按需选用，不必整体采纳。

8. [Telling Stories with Data: With Applications in
   R](https://tellingstorieswithdata.com/ "Telling Stories with Data: With Applications in R")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260730110248.png)

作者 Rohan Alexander 是多伦多大学统计科学系助理教授，也是 RStudio 官方认证的
Tidyverse Trainer。这是一本用 R 语言（尤其是 tidyverse
生态）贯穿始终的数据科学入门教材，全书分为基础、沟通表达、数据获取、数据准备、建模、应用六大部分，共17章，把数据获取、清洗、可视化、建模到复现性工作流串成一条完整链路来讲，强调"讲故事"而非单纯罗列统计方法。同类教材内容大同小异，这本书的亮点在于大量采用较新的
R 方法，内容更新及时，剑桥大学 David Spiegelhalter
教授评价它"充满了给数据科学初学者的智慧建议"

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
