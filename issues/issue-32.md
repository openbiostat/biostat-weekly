# 生统爱好者周刊（第 32 期）：导师如何在博士生涯中发挥重要作用

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260507133030.png)

## 本周话题：[导师如何在博士生涯中发挥重要作用](https://www.nature.com/articles/d41586-026-00853-w?utm_source=x&utm_medium=social&utm_campaign=nature&linkId=61382583 "14 things our PhD supervisors got right and why it mattered")

《自然》（Nature）杂志近日分享了一篇2025年博士生调查相关的文章，博士生们纷纷讲述自己的导师如何在博士生涯中发挥重要作用——从细微的善意举动，到塑造职业发展的关键指导。文章中，学生们提到导师给予他们项目自主权、在COVID-19隔离期间提供情感支持、鼓励他们参加国际会议以建立自信、灵活处理产假和心理健康问题，以及创造安全空间让学生敞开心扉讨论个人困境。这些故事突显了信任、灵活性和支持对缓解博士生常见的压力（如冒名顶替综合征、工作生活平衡难题）的重要性。

## 生统研究

1. [Nature Human Behaviour | 特征选择可导致机器学习模型解释偏差](https://mp.weixin.qq.com/s/qb900IUog5Zx0PaSWDAj6g)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260507134310.png)

脑影像机器学习里最常见的可解释性做法，是先用单变量特征筛选（univariate feature selection）找出与目标表型关联最强的一批连接，再把这些高排名特征解释成该表型的“神经网络”。Adkinson 等人用四个大样本发育期数据集、超过 12,000 名参与者、13 个结局变量，把全脑连接按与表型的关联强弱切成十个互不重叠的十分位组（decile），结果发现显著预测并不只属于最靠前的特征。许多在常规流程里被丢弃的低排名连接，既能在内部交叉验证和外部验证中维持显著预测，也会导向不同的网络和节点解释。

- 论文 DOI：10.1038/s41562-026-02447-y

2. [Nature Genetics | 空间多组学进行镶嵌式整合 SpaMosaic](https://mp.weixin.qq.com/s/-WXVySLCOA61aYvT2iTNIQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260507134737.png)

Nature Genetics 上的空间多组学整合工具 SpaMosaic。针对空间组学中样本模态不全、平台不一的“马赛克式”数据难题，提出了一种基于图神经网络和对比学习的整合思路：通过将不同切片、不同模态（如RNA、ATAC、蛋白、组蛋白修饰）对齐到统一低维空间，不仅能实现跨样本的空间聚类和区域注释，还能有效预测缺失的组学信息。通过模拟数据、小鼠脑及胚胎等复杂数据集验证了其在去批次和保持空间连续性上的优越性，为研究者提供了一种无需重复实验、仅靠数据整合即可补全“调控拼图”的高端科研范式。

- 论文 DOI：10.1038/s41588-026-02573-3

3. [中国肥胖流行加速：全生命周期防控刻不容缓](https://mp.weixin.qq.com/s/5vE-Ro4aaDLUh0ESj9XT8Q)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260507135719.png)

该研究系统揭示了中国超重肥胖在成人与儿童青少年中持续快速上升的流行趋势，识别出涵盖个体行为与宏观环境的多层次危险因素，并指出我国现有防控政策在协同治理与全生命周期干预方面的不足；研究进一步提出以政府主导、多部门联动为核心的综合防控策略，强调前移干预关口与构建支持性环境，以应对日益严峻的肥胖问题。

## 博文资讯

4. [主题模型: 从K-means到BERTopic](https://mp.weixin.qq.com/s/vY6GaAdg39d8Op0Fz7GnFQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260507140211.png)

传统主题模型 LDA 与现代语义主题模型 BERTopic 的优劣。无论是针对空间组学中碎片化模态的 SpaMosaic，还是取代传统 LDA 主题模型的 BERTopic，都在强调通过语义对齐和图神经网络等现代算法，将原本零散、模糊的原始信息转化为高连贯性、可解释的科学故事，为处理复杂数据提供了从“勤劳补实验”向“高效换模型”转型的进阶范式。

5. [生成式人工智能对医学信息学发展贡献与挑战](https://mp.weixin.qq.com/s/NBRnhd1ySf2zklPLpuMdNg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260507135921.png)

随着医学信息学进入以大数据与AI驱动的智能化阶段，生成式AI正推动临床决策支持从“规则提示”向“协同推演”转型，通过整合多模态数据与多智能体协作提升复杂疾病诊疗能力；同时重构医学知识发现模式，实现从文献挖掘到真实世界研究的自动化与数据驱动；并进一步延伸至智能问诊、健康管理和医学教育，促进医疗服务向全生命周期健康管理转变。然而，当前仍存在数据质量与泛化能力不足、评估体系缺失、伦理与隐私风险以及临床工作流整合困难等关键瓶颈。总体而言，生成式AI正在重塑医学信息学范式，但其价值实现仍依赖技术进步与规范治理的协同推进。

## 工具

6. [卫生经济学教程：使用R语言建立简单马尔可夫模型](https://mp.weixin.qq.com/s/S38zTc-pccj8wMBd1F3Edw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260507140406.png)

使用R语言构建马尔可夫模型，并进行成本效果分析。

7. [Agent skills for Obsidian](https://github.com/kepano/obsidian-skills "Agent skills for Obsidian")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260507140502.png)

5个Obsidian Skills：defuddle（网页抓取）、obsidian-cli（命令行操作）、obsidian-markdown（Markdown 语法）、obsidian-bases（数据库视图）、json-canvas（画布文件）。

## 资源

8. [GitHub 画图 Skill: 一句话生成流程图、架构图](https://mp.weixin.qq.com/s/V3ljnVIwnJIVO1-qd_Uy3g)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260507142457.png)

三款基于 GitHub 且集成 Claude 的绘图 Skill，旨在通过自然语言交互彻底简化技术绘图流程，三者共同实现了从 RAG 流程到云架构图的高效、专业化自动生成。

9. [NeuroClaw：属于神经科学/脑科学工作者的“小龙虾”](https://mp.weixin.qq.com/s/3FE6ulWVWL3cPG7CBvf3kA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260507142549.png)

NeuroClaw 是由港中文与哈佛联手打造的神经科学专用 AI Agent，它像一只拥有“数字外骨骼”的小龙虾，凭借三层智能体架构，能自主从原始数据抓取元数据、自动配置复杂的 Docker/Python 环境，并精准调度 FreeSurfer、FSL 等主流工具链，旨在将科研人员从繁琐的工程报错与复现危机中解放出来，让大脑研究真正实现“科研的归科学家，工程的归智能体”。

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
