# 生统爱好者周刊（第 49 期）：AI 从解谜到创造

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub:
[openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交
issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260903160136.png)

## 本周话题：[AI 从解谜到创造](https://doi.org/10.1126/science.aeg6829 "De novo design of RNA pseudoknots with deep learning")

本期封面选自Science第393卷6814期封面（发布于2026年8月27日），图片来源是由斯坦福大学
Rhiju Das 教授带领团队发表的论文 De novo design of RNA pseudoknots with deep
learning。该论文展示了现有的深度学习工具已经能够基于给定的二级结构，自主从头生成RNA假结(pseudoknot)。

假结是一种交叉缠绕的折叠方式，环上的碱基跑去和环外的序列配对，结构比常见的发夹要复杂得多，封面上的这些结构便是运用AI设计出的RNA假结。这里的关键工具是该团队此前训练的[RNet模型](https://www.biorxiv.org/content/10.1101/2024.02.24.581671v1 "Ribonanza: deep learning of RNA structure through dual crowdsourcing")，它学的是上百万条RNA的化学探针实验数据，判断的是二级结构而非三维坐标。有了RNet做筛选和引导，各种深度学习方法就能在不依赖三维结构预测的前提下生成序列。团队在RNA设计平台Eterna上发起了为期一年的OpenKnot挑战，先后给出57个假结目标，让六种来自不同机构的AI方法和资深的Eterna人类玩家同台盲测，双方最终都解决了其中95%以上的目标。团队随后用化学探针、补偿性突变和冷冻电镜三种手段逐一验证，确认这些序列确实折成了预想的形状。

过去研究RNA结构，通常是拿到一条已有的序列，去猜它会折成什么样子，这是"预测"。这篇论文做的是反过来的事：先定好想要的形状，让AI去设计出一条能折成这个形状的全新序列，这是"设计"。预测是看懂，设计是造出来。这一步突破意味着RNA药物、诊断探针、催化元件的开发，有望从"靠试错和经验摸索"，变成"根据需求说明书直接造出来"，从而大幅缩短早期设计的研发周期，节省大量时间和金钱成本。

## 生统研究

1. [Nature Reviews Drug Discovery \|
   设计、模拟、改进：让临床试验先在计算机里跑一遍](https://mp.weixin.qq.com/s/o39mg2mF7eBA6gE86_rJaw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260903161907.png)

现代临床试验越来越多地采用适应性设计、生物标志物指导入组、主方案等策略，效率提升的同时，试验本身也变得越来越难以理解和评估，有变成黑箱的风险。这篇发表在《Nature
Reviews Drug
Discovery》的文章主张，把计算机模拟从"公式算不出来时的备选方案"提升为设计阶段的正式实验：在招募第一位患者之前，先把试验在虚拟环境里跑上几千遍，观察这个设计在各种可能的真实情况下会如何表现。作者把模拟的输入拆成两类，一类是设计者能控制的设计选项（样本量、期中分析的次数和时点、随机化比例），另一类是控制不了的假设（真实疗效、入组速度、脱落率），两者组合成场景，反复模拟后汇总出功效、一类错误率、预期样本量、试验时长等运行特征。文章提出五条原则：有效性、透明与可复现、周密性、效率、可比性，其中几点很有提醒意味，比如必须纳入一个简单的基准设计，既衡量复杂设计究竟加了多少价值，也反过来检验模拟器本身有没有写错；比较不同设计时应固定数据生成、只变决策逻辑；如果一个设计在所有场景下都完胜基准，这本身就该引起怀疑，通常说明评估不够对称。文章还给出ASTIN、VICTAS等四个公开案例，以及ICH
E20、FDA和EMA相关指导文件的对照表。

- 论文 DOI：10.1038/s41573-026-01481-9

2. [Statistics in Medicine \|
   非概率样本的参与偏差：一个参考调查不够用怎么办？](https://doi.org/10.1002/sim.70403 "Statistics in Medicine | 非概率样本的参与偏差：一个参考调查不够用怎么办？")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260903160939.png)

近年来越来越多的健康研究通过手机app、社交媒体、志愿者面板招募参与者。这类非概率样本（也叫便利样本）省钱省时，但参与者是"方便找到的人"，样本在人口学、生活方式、职业和健康特征上可能系统性地偏离目标总体，由此估计出的患病率和暴露与结局的关联都可能有偏。已有的校正思路是借助一个具有代表性的概率抽样调查作为参考，反推每个人进入便利样本的概率，取倒数得到伪权重（pseudo-weight），[代表方法](https://www.tandfonline.com/doi/full/10.1080/01621459.2019.1677241 "Doubly robust inference with nonprobability survey samples")有adjusted
logistic
propensity和CLW方法。问题在于，与"是否愿意参与"相关的辅助变量往往分散在不同的调查里，一个参考调查通常覆盖不全，而现有方法只能用一个。这篇文章提出了一个统一的估计方程框架，可以同时纳入多个参考调查，ALP和CLW都是它的特例。作者重点讨论了其中的校准估计量（calibration
estimator），因为它对微观数据的依赖更低，在只能拿到边际汇总信息时仍然可用，实践者更容易上手。方差估计方面给出了基于泰勒线性化的解析公式和留一法刀切估计量，并通过模拟研究和一个实际数据例子比较了各种伪权重估计量的表现。团队还开发了配套的R包
nonprobsampling。

- 论文 DOI：10.1002/sim.70403

3. [Nature Communications \|
   时变网络分析揭示青年大脑任务状态与认知表现、症状的关联](https://mp.weixin.qq.com/s/iPO_Si09WwdLc2jZ60xJqA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260903161249.png)

研究介绍了基于时间变化功能网络连接（time-varying functional network
connectivity,
tvFNC）的脑网络动态分析方法，探索大脑功能网络如何随认知任务变化，并揭示其与行为表现及精神疾病症状之间的关系。研究基于
IMAGEN 大型青少年队列和 STRATIFY
临床验证队列，利用滑动窗口分析、独立成分分析（ICA）和聚类方法识别动态脑网络状态。研究发现，相比传统静态功能连接分析，时间变化网络连接能够解释更多行为差异，并在抑郁症、酒精使用障碍等精神疾病识别中表现出更高敏感性。该研究强调，将脑网络视为动态系统而非静态结构，有助于更准确理解认知过程和精神病理机制，为计算精神病学和精准神经科学提供新的分析框架。

- 论文 DOI：10.1038/s41467-025-67398-w

## 博文资讯

4. [一群"业余玩家"如何设计出能救命的RNA分子？](https://stanmed.stanford.edu/molecule-design-rna-test-tuberculosis/ "一群“业余玩家”如何设计出能救命的RNA分子？")

本期封面研究背后的Eterna平台，是斯坦福 Rhiju Das
团队在2010年创立的开放科学游戏平台，口号是"解开谜题，发明药物"，注册玩家约十万人。这篇报道讲的是Eterna此前的一项成果：用众包设计出一款低成本的结核病检测试剂。全球约四分之一人口感染结核杆菌，但细菌可以潜伏多年不发病，真正危险的是它转为活动性的时刻。判断这个转变要测血液里几种基因转录本的比值，比值远比单个基因准确，问题是算起来麻烦，现有手段依赖昂贵设备。Das团队把这道题挂上Eterna：设计一条RNA分子，让它自己去"算"三种RNA的浓度比是否达到活动性结核的特征。之所以能这样做，是因为RNA本身就有开关性质，折成一种形状代表真，另一种代表假，等于计算机里的0和1。最终的原型和新冠抗原试剂条一样，在试纸上显出一条粉线。值得一提的是Das对人机分工的判断：这类问题没有现成解可以拿来训练AI，而人类擅长找捷径，能看出算法看不出的东西。封面论文其实是同一个判断的延伸。如果一直等着深度学习把RNA三维结构预测做准，这件事不知要拖到哪一年；Das团队换了条路，用只判断二级结构的RNet当裁判，绕开三维预测直接生成序列。真正找到捷径的，仍然是人。

## 工具

5. [Eterna /
   OpenKnotAI：跟着封面研究自己动手折RNA](https://eternagame.org/ "Eterna / OpenKnotAI：跟着封面研究自己动手折RNA")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260903162239.png)

Eterna 是本期封面研究所依托的RNA设计平台，Rhiju Das
团队2010年创立，面向公众开放，把RNA折叠变成一关关的解谜游戏，注册玩家约十万人。你不需要生物化学背景就能上手，游戏会告诉你目标结构，剩下的是试出一条能折成那个形状的序列。玩家提交的设计有机会被真正合成并做实验验证，本期封面论文里"人类设计者"那一栏的成绩，就来自这批人。

配套的 OpenKnotAI 是这项研究公开的全部代码，托管在
Zenodo，内容包括RNA文库设计、SHAPE化学探针数据处理、OpenKnot评分的实现，以及论文里各种AI设计方法本身。实验数据则在斯坦福的
RNA Mapping Database（rmdb.stanford.edu）可以查到，冷冻电镜结构和图谱分别存放在
PDB 和 EMDB。想复现或者在此基础上改进方法的，材料是齐的。

- DOI：10.5281/zenodo.20649966

6. [rpact：把自适应临床试验设计跑起来的R包](https://www.rpact.org/ "rpact：把自适应临床试验设计跑起来的R包")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260903162442.png)

由 Gernot Wassmer 与 Friedrich Pahlke
开发的开源R包（LGPL-3），用于确认性自适应临床试验的设计、模拟与分析，实现的是
Wassmer 与 Brannath
2016年[专著](https://www.indigo.ca/products/group-sequential-and-confirmatory-adaptive-designs-in-clinical-trials "Group Sequential and Confirmatory Adaptive Designs in Clinical Trials")中的方法。功能覆盖固定样本设计及带期中分析的设计，支持连续、二分类、生存和计数四类终点的样本量与功效计算，并提供对应的模拟工具，可评估基于条件功效的样本量重估、多臂试验中的治疗选择策略以及富集设计。

## 资源

7. [Rosalind:
   靠解谜学生物信息学](https://rosalind.info/problems/locations/ "Rosalind: 靠解谜学生物信息学")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260903162947.png)

Rosalind
是加州大学圣地亚哥分校与圣彼得堡学术大学等机构合作的免费学习平台，2012年上线，名字取自
Rosalind Franklin，设计思路借鉴了 Project Euler
这类编程解题网站。每道题先讲清楚背后的生物学问题，再把它转成一个计算问题，你提交答案后系统自动判定对错。题目按难度排成一棵树，可以顺着走，也可以按主题挑，涵盖序列比对、动态规划、基因组组装、基因组重排、系统发育、概率、字符串算法、计算质谱等方向。平台分几个板块：Python
Village 面向零基础，从语法练起；Bioinformatics Stronghold
要求自己实现算法；Bioinformatics Armory
则是同类问题改用现成工具解决；另有一条配合 Compeau 与 Pevzner
教材《Bioinformatics
Algorithms》的路线。答错时平台不给详细反馈，这是有意为之，因为真实研究里也没有标准答案可对。语言不限，用
R、Python 还是别的都行。

8. [Statistical Rethinking:
   把贝叶斯建模从头捋一遍](https://github.com/rmcelreath/stat_rethinking_2026 "Statistical Rethinking: 把贝叶斯建模从头捋一遍")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260903163050.png)

这是由德国马普演化人类学研究所 Richard McElreath
开设的贝叶斯统计课程，2026年的全套讲座已陆续上线
YouTube，课件、习题、代码和参考解答都在 GitHub
公开。课程的特点在于先把因果假设画成图、再把模型写成一条条明确的分布假设，从而帮助读者把每个先验和似然都想清楚，配套的
rethinking R包也是照这个思路设计的。需说明的是同名教材由 CRC Press
出版，属于付费书籍，但讲座与全部课程材料免费开放，第三版目前在起草中。

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
