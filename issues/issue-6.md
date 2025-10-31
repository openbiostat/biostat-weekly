# 生统爱好者周刊（第 6 期）：Meta 分析，为什么顶刊一边依赖它，一边骂它？

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251030152914.png)

## 本周话题：[为什么顶刊一边依赖它，一边骂它？](https://mp.weixin.qq.com/s/u9El6GBFSkOGbjFFcXesJw?scene=1&click_id=2)

> Meta分析是一种对多项研究结果进行定量综合的方法，自20世纪70年代引入以来，已在医学、社会科学、生态学等众多领域产生深远影响。它通过系统评价和严格统计建模，提高了科学研究的透明度、可重复性和证据整合能力，为循证决策提供了坚实基础。然而，随着Meta分析数量的爆发式增长，低质量研究、方法滥用、统计偏差和发表偏倚等问题也日益凸显，引发了学界对其可靠性和学术伦理的广泛争议。

meta分析方法和概念的培训，应成为基础科学和应用科学领域中攻读更高学位的学生（包括研究生、医学博士以及其他专业科学从业者）基础培训的一部分。这将使他们的工作正式立足于现有证据的背景之下，并有助于他们学习统计技能和批判性评估技能。从事原始研究的人员也需要更好地理解meta分析，以便充分利用开放数据带来的变革。最重要的是，新一代的科学家、同行评审人员、编辑以及科学政策制定者，都将从对证据综合的方法学及其解读有更深入的理解中受益。

## 生统研究

1. [Lancet | 30种抗抑郁药对心脏代谢及其他生理指标的影响](https://mp.weixin.qq.com/s/HoH3dTv3FAb-RdSbI_qzLA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/6cd97004831b48b50b8b996fe6d82790.png)

抗抑郁药可以有效治疗多种精神障碍，总体安全性和耐受性良好，但也会引起多种生理变化，包括体重增加、血压异常、低钠血症及 QTc 间期延长等，有时会导致过早停药。权威机构建议，临床处方抗抑郁药时，有关副作用的讨论应作为医患沟通的核心内容。然而，用于支持抗抑郁药副作用讨论的综合性证据相当缺乏，不同抗抑郁药在急性期治疗中引发生理指标变化的相对程度及其影响因素尚不清楚。另外在精神分裂症患者中，精神病性症状的改善与抗精神病药诱发的代谢紊乱存在关联；抑郁症状的改善与抗抑郁药导致的代谢变化之间是否存在类似的关系，目前也有待澄清。

一项 10 月 21 日在线发表于《柳叶刀》的系统综述和网状 meta 分析中，研究者系统检索了 MEDLINE、EMBASE、PsycINFO、ClinicalTrials.gov 及 FDA 网站 2025 年 4 月 21 日前收录的、比较抗抑郁药单药和安慰剂用于各种精神障碍急性期治疗的单盲或双盲随机对照试验，采用频率学派随机效应网状荟萃分析对治疗引起的 15 项生理指标的变化进行了探讨；在研究层面采用 meta 回归分析评估了这些生理变化与参与者年龄、性别、基线体重之间的关联；分析了抑郁症患者症状严重程度变化与代谢指标变化之间的相关性。

- 论文 DOI：10.1016/S0140-6736(25)01293-0

2. [Lancet Infectious Diseases | 人工智能重塑传染病防治：从预测、诊断到新药研发的全景解析](https://mp.weixin.qq.com/s/nn7S3MhWcZU2cPdkkRofEQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251030155047.png)

人工智能（AI）正以前所未有的深度和广度，重塑我们对抗传染病的战役。它已经深入到疾病预防、诊断、治疗和研究的各个角落，成为推动全球健康安全的关键力量。早在20世纪70年代，MYCIN专家系统就已尝试利用AI辅助抗生素治疗方案的制定，这标志着一个新时代的开端。如今，AI通过实时处理来自病原体、人类宿主和环境的海量数据，为我们应对新发传染病、气候变化和抗生素耐药性（AMR）等严峻挑战提供了前所未有的机遇。为此，Lancet Infectious Diseases 设立了“Artificial Intelligence and Infectious Diseases”专栏，讨论AI在感染性疾病中的角色定位和作用。

- 论文 DOI：10.1016/S1473-3099(25)00412-8

3. [Nature Mental Health | 网络温度作为衡量青春期抑郁症状稳定性的指标](https://mp.weixin.qq.com/s/Y2PBRqtOTY_OnqtOxckrwg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251030155649.png)

网络温度类似于统计力学中描述固体->液体->气体能态转变的物理温度，可通过伊辛（Ising）模型建模。在伊辛模型里，温度代表节点可能状态的随机性水平，放到抑郁网络中，这种随机性就是症状波动。我们还可以用熵值来衡量系统的紊乱或不确定性：抑郁网络中高熵意味着症状变化范围广、更难预测，低熵则表示症状更一致、可预测。而温度会影响全局熵，当把网络看作相互依赖的能量系统时，低网络温度会让抑郁网络呈现低熵、稳定且可预测的症状模式；高网络温度则会导致更随机的激活模式、更高的熵以及更不稳定的症状特征。

研究团队首次将心理症状网络中“网络温度” 的概念形式化，并运用多组伊辛模型这一创新方法，评估其在网络比较中的效用。他们在三个大型独立队列（ABCD、ALSPAC、MCS）中，研究了网络温度在青少年抑郁症发展过程中的变化，同时还探究了性别分层下温度的变化。

- 论文 DOI：10.1038/s44220-025-00415-5

## 博文资讯

4. [柳叶刀系列期刊开放获取相关问题](https://mp.weixin.qq.com/s/5FdOJMypwQmIBN3URqHtaw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251030155848.png)

《柳叶刀》系列期刊提供多种开放获取发表方案。在开放获取周，柳叶刀整理了关于开放获取的主要问题，可以查看备用。

5. [UK Biobank常见病患者携带罕见病基因突变，数据挖掘凉了吗？| NEJM](https://mp.weixin.qq.com/s/7W8XqNZQa4U5KH7jz0d5bQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251030161039.png)

科学家利用英国生物样本库（U.K. Biobank）及多项临床试验中18,000余名参与者的大规模基因组与临床数据，揭示出在多发性硬化症、炎症性肠病和特应性皮炎患者中有1%~3%的人携带罕见单基因病致病变异。这些变异不仅可能导致误诊或漏诊，还影响患者对常规治疗的应答。众所周知，在被诊断为常见病的患者中，有一部分患的是孟德尔遗传病。此类疾病常存在有别于常见病的特征，例如在癌症易感、阿尔茨海默病及炎症性肠病患者中，有一部分属于单基因遗传，这些患者普遍发病年龄更早、多病灶可能性更大、临床严重程度更高。

然而，在临床实践中，常见病患者中的罕见病往往难以识别。本研究的核心发现是，罕见病被误诊为常见病的现象并不罕见。误诊可能通过多种途径发生：罕见病的临床表现可能与常见病非常相似，因此不经过基因检测难以区分；另一种情况是，罕见病患者可能出现相似但更严重的临床表现；或者罕见病与常见病共存，且部分临床表现重叠。如果本研究结果具有普遍适用性，则相当比例的特应性皮炎、多发性硬化症或炎症性肠病患者有望通过基因检测发现罕见病病因，从而实现个体化临床治疗。

- 论文 DOI：10.1056/NEJMoa2405459

- 论文 DOI：10.1056/NEJMe2510168

## 工具

6. [medicaldata](https://higgi13425.github.io/medicaldata/ "medicaldata")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251030161714.png)

这是一个包含19个医学数据集的数据包，用于教授使用R语言进行医学研究。

7. [ggstatsplot](https://indrajeetpatil.github.io/ggstatsplot/ "ggstatsplot")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251030162137.png)

ggstatsplot是 ggplot2 的一个扩展包，用于创建包含统计检验细节的图形，并将这些细节融入到信息丰富的图表中。

## 资源

8. [Mathematics of Machine Learning](https://github.com/cosmic-cortex/mathematics-of-machine-learning-book "Mathematics of Machine Learning")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251030172835.png)

《Mathematics of Machine Learning》一书的官方 GitHub 代码库，通过大量的Python实例，学习如何在实际场景中应用这些机器学习概念，例如使用梯度下降法训练机器学习模型，或处理向量、矩阵和张量等数据。

9. [Cochrane系统综述学习指南](https://www.cochrane.org/authors/handbooks-and-manuals/handbook/current "Cochrane系统综述学习指南")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251030172040.png)

Cochrane系统评价是国际公认的循证卫生保健最高标准证据，其在线图书馆提供了各个版本的Cochrane review实施指导手册。

## 贡献者（GitHub ID）

「OpenBioStat 生统爱好者周刊」运维小组：

- [`@Leslie-Lu`]（陆震）
- [`@YihanChen325`]（陈奕含）
- [`@kirihsia`]（夏鑫辛）
- [`@GCRPM`]（徐林玉）

## 订阅

本周刊每周五发布，同步更新在微信公众号「陆震生物统计」（luzhen-biostat）上。

微信搜索“陆震生物统计”或者扫描二维码，即可订阅。

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/qrcode_for_gh_395f59db8b4c_258.jpg)

（完）
