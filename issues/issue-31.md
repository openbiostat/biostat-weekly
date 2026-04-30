# 生统爱好者周刊（第 31 期）：UK Biobank史上最大数据安全事件

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260430234819.png)

## 本周话题：[UK Biobank史上最大数据安全事件](https://mp.weixin.qq.com/s/6RGmy-jXaonCwzOoq9G-jA)

4月23日，英国科技部长Ian Murray在下议院紧急发表声明：UK Biobank约50万志愿者的去标识化健康数据，被发现在阿里巴巴电商平台上公开挂牌出售。数据来源于三家中国研究机构。这些机构此前合法申请并获得了UK Biobank的数据访问权限，通过正规渠道下载了去标识化的参与者数据。然后，这些数据被挂到了电商平台上出售。

`@Leslie-Lu` 对于公开数据库的使用，数据安全是重中之重，否则可能会断送掉职业生涯。

## 生统研究

1. [Nature | 人的大脑一生都在重排层级](https://mp.weixin.qq.com/s/jVrOQ-KMRIj5ophECs65_Q)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260430235114.png)

作者希望回答一个神经科学中非常基础、却长期缺少完整图谱的问题：人类大脑皮层的大尺度功能层级，究竟如何从婴儿期逐步建立，在成年期达到相对成熟，又在老年阶段发生怎样的变化。 这项研究进一步追问，这种层级结构是否与认知能力、脑结构耦合以及分子层面的生物学特征相互对应。

文章的核心结论可以概括为一句话：人脑的功能组织不是固定不变的，而是在一生中沿着几条主要轴线不断重塑。 婴幼儿时期，这种组织主要由初级感觉系统奠基；儿童和青春期阶段，高级联想与控制相关系统逐渐拉开层级；进入老年之后，原本清晰的分化又会出现一定程度的减弱，也就是所谓的“去分化”。更重要的是，这种变化并不只是图谱上的现象，它与认知表现、结构—功能关系以及转录组特征都存在对应关系。

- 论文 DOI：10.1038/s41586-026-10219-x

2. [Nature Neuroscience | 解锁新生儿大脑发育新维度](https://mp.weixin.qq.com/s/jEKmvN1cxBfLHWQYVnWxcg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260430235338.png)

在人类生命的最早期阶段，大脑经历着翻天覆地的解剖学重组，其中最直观的特征是体积的爆发式增长。然而，长期以来，发育神经科学面临一个核心难题：仅仅通过脑体积或简单的线性尺度测量，是否足以描述大脑发育的全貌？如果两个新生儿具有相似的大脑体积，他们的大脑在组织复杂性、神经成熟度以及遗传特征上是否依然存在显著差异？目前，临床和科研领域缺乏一种能够量化大脑形态复杂性、且对遗传和发育成熟度具有高度特异性的生物标志物，这限制了我们对早产或遗传代谢疾病引起的微细大脑形态异变的识别能力。

本研究通过大规模的对比分析，在结论中明确了分形维数在计算神经影像学指标体系中的统治地位。相比于皮层厚度、曲率等传统局部指标，FD凭借其对大脑空间填充效率和多尺度拓扑特征的全局整合能力，展现出了更强的表征效用。这在方法论上为未来的神经发育AI模型指明了方向，即应当优先集成非线性几何特征。总而言之，本研究不仅在科学上发现了一套调控大脑形状形成的数学律动，更在技术上提供了一套鲁棒的计算工具，为未来精准评估、预测及干预新生儿神经发育奠定了深厚的科学基石。

- 论文 DOI：10.1038/s41593-025-02107-w

## 博文资讯

3. [从Alpha波到Gamma波，揭秘大脑如何用节拍器协调860亿神经元](https://mp.weixin.qq.com/s/w7Xe_zA_VpxdyXfmtgsqyw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260430235609.png)

大脑神经元通过不同频段的节律性活动（如Delta、Theta、Alpha、Beta、Gamma波）实现协同工作，这些“节拍”不仅对应睡眠、记忆、注意与认知等功能，还通过同步与相位锁定机制提升脑区间的信息传递效率。其中，神经振荡并非附属现象，而是类似“操作系统”的协调机制，其失调与帕金森病、阿尔茨海默病及精神分裂症等密切相关。同时，基于振荡的神经调控、神经反馈和脑机接口技术正展现出重要应用潜力。

4. [CMS的BALANCE模型](10.1001/jama.2026.2894 "CMS的BALANCE模型")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260501000238.png)

CMS推出的BALANCE模型（2027年示范项目）旨在通过标准化覆盖和激励措施，降低新型肥胖症药物（GLP-1类药物）的使用障碍。该模型将协商降低药物价格，并在Medicare Part D和Medicaid中标准化覆盖，同时将药物治疗与生活方式干预相结合。标准化条款和激励有望减少事前授权（prior authorization）的繁琐流程和经济负担，从而帮助更多肥胖患者获得治疗。然而，该模型仍存在不确定性，包括制药企业、医保计划和各州的自愿参与度，以及患者长期坚持用药的情况。

## 工具

5. [利用ggplot2+circlize绘制环图棒棒糖图+堆叠柱状图+箱线图+色块图](https://mp.weixin.qq.com/s/Pah9B9rgFEiYSJuf-sOVPg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260501000455.png)

分享发表在Nature Aging题为“Nonlinear dynamics of multi-omics profiles during human aging”中环状圆形棒棒糖图+堆叠柱状图+色块图+箱线图。

6. [TRIBE v2 计算机神经科学的视觉、听觉和语言基础模型](https://github.com/facebookresearch/tribev2 "TRIBE v2 计算机神经科学的视觉、听觉和语言基础模型")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260501000857.png)

TRIBE v2 是 Meta 开源的一个神经AI工具，用于预测人脑对外界刺激的 fMRI 活动反应。它通过三阶段架构工作：首先利用音频、视频和文本的预训练模型提取多模态特征；其次通过 Transformer 学习跨任务、跨个体的通用表征；最后将这些表征映射到具体个体的脑体素上，实现全脑活动预测。

相较于早期版本，TRIBE v2 能预测约7万个体素的全脑信号，并支持零样本泛化（无需再训练即可适用于新刺激和新个体）。其预测结果在一定程度上比单次fMRI扫描更稳定，接近群体平均脑反应。该工具可用于脑功能建模、虚拟神经实验（in-silico neuroscience）以及AI与人脑表征对齐研究。

## 资源

7. [GIN-IMN神经影像工具资源平台](https://www.gin.cnrs.fr/en/tools/ "GIN-IMN神经影像工具资源平台")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260501001033.png)

法国波尔多大学神经退行性疾病研究所（GIN-IMN）团队提供的一个神经影像工具资源平台，主要汇总了该团队开发的一系列脑影像分析工具与脑区图谱（atlas）。内容涵盖常用脑区分区模板（如AAL系列、AICHA）、白质通路与语言网络图谱，以及配套的软件工具（如影像分割、成分分析算法）和问卷工具（如静息态评估）。整体而言，这是一个面向神经影像与脑科学研究者的专业资源库，可用于脑区标注、功能连接分析及群体影像研究。

8. [临床医学领域最受欢迎的90+机器学习数据集](https://mp.weixin.qq.com/s/GIh33OWDTdNlRBJWAyAPRQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260501001203.png)

汇总了“临床医学领域最受欢迎的90+机器学习数据集”，系统整理了来自 Kaggle、GitHub 等平台的高质量公开资源。核心内容以数据集清单为主，为每个数据集提供名称、热度（⭐）、简要用途、主题标签、使用协议、提供者及访问链接，便于快速检索与使用。所涵盖领域广泛，包括疾病预测（如糖尿病、癌症、心血管疾病）、健康指标分析、临床记录与试验数据、医学影像与声音数据，以及心理健康、医疗资源管理等多个方向。此外，文章还补充了相关数据集合集与工具资源（如 MIMIC-III），构成一个结构化的数据资源导航。

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
