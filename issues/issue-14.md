# 生统爱好者周刊（第 14 期）：人工智能+医学科研有没有搞头

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251225184130.png)

## 本周话题：[人工智能+医学科研有没有搞头](https://mp.weixin.qq.com/s/mU-vJlXTAmPySgghuYPIdg)

近日，国务院正式发布《关于深入实施“人工智能+”行动的意见》（国发〔2025〕11号）。这份重磅文件为AI技术与各产业的深度融合下达了“行动令”。对于关乎国计民生的医药行业而言，这不仅是发展的“加速器”，更预示着一场深刻的产业变革。

- AI将成为医生的得力副手，尤其在医学影像分析（如CT、病理切片） 和辅助诊断方面，帮助提升早期病灶的检出率与诊断效率，让“火眼金睛”成为常态。

- 新药研发耗时耗资的“双十定律”（十年、十亿美元）有望被打破。AI能通过智能筛选与模拟，快速从海量化合物中锁定潜力候选药物，大幅缩短研发周期、降低成本，让更多创新药更快惠及患者。

- 通过分析患者的基因、生活习惯与临床数据，AI能辅助医生制定高度个性化的治疗方案，实现“同病异治”，真正步入精准医疗时代。

## 生统研究

1. [Nature | 为什么精神疾病总爱“扎堆”出现？](https://mp.weixin.qq.com/s/JduRm4tjQ9kTQn6o2IX-6w)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251225173754.png)

精神疾病种类繁多，比如抑郁症、焦虑症、精神分裂症、双相情感障碍、自闭症、多动症、强迫症、成瘾等，传统上它们被当作彼此独立的疾病来诊断和治疗。但临床上常发现这些疾病容易共病，患者可能同时或先后出现多种症状，提示它们在根源上可能存在共同的生物学基础。基于此，2025年12月10日，美国科罗拉多大学Jordan W. Smoller研究团队在Nature杂志发表了“Mapping the genetic landscape across 14 psychiatric disorders”揭示了绘制14种精神障碍的遗传图谱。

为揭示精神障碍之间的遗传关联，作者整合前沿统计与功能基因组学方法，分析了14种儿童期和成人期起病的精神疾病（共1,056,201例患者）的常见遗传变异数据，识别出五个潜在的基因组因子，平均解释各障碍约66%的遗传风险，并关联238个多效性位点。其中，“精神病性因子”（涵盖精神分裂症和双相情感障碍）与“内化因子”（包括重度抑郁、创伤后应激障碍和焦虑症）表现出高度的多基因重叠和局部遗传相关性且几乎不含障碍特异性位点。全障碍共享的遗传信号富集于基础生物学过程（如转录调控），而更特异的通路则在因子层面显现：精神病性因子的风险基因显著富集于兴奋性神经元表达的基因，而内化因子则与少突胶质细胞生物学密切相关。这些发现支持以神经生物学机制为基础重构精神障碍分类体系，并为针对共病核心症状开发新疗法提供关键线索。

- 论文 DOI：10.1038/s41586-025-09820-3

2. [Nature | 注意力缺陷多动障碍（ADHD）突破：首次发现 MAP1A 等 3 个“高风险”罕见变异](https://mp.weixin.qq.com/s/u3Nc82VTP_GzSAb8fM5jag)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251225174159.png)

该研究通过大规模外显子组测序发现了三个赋予注意力缺陷多动障碍（ADHD）高患病风险的罕见变异基因（MAP1A, ANO8, ANK2），并揭示了它们主要通过影响神经元骨架、突触功能和多巴胺能神经元等生物学过程来致病。

这项工作首次为ADHD找到了具有高风险效应的罕见编码变异基因，将ADHD的遗传学研究从“普遍但效应微弱”的常见变异推进到了“罕见但效应强大”的罕见变异层面，为理解ADHD的神经生物学发病机制提供了关键的分子靶点，并为未来潜在的精准干预和治疗开辟了新方向。

- 论文 DOI：10.1038/s41586-025-09702-8

3. [Nat Revi Neuro | 心血管疾病如何重塑CNS](https://mp.weixin.qq.com/s/idkWzdWbDYwKIysaKvlRow)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251225174612.png)

心脏与大脑之间存在着精密而双向的沟通网络，即脑-心轴。它对维持心脏的节律性功能和满足机体代谢需求至关重要。当心血管系统发生病变时，这种平衡会被打破。 心血管疾病不仅损害心脏本身，还会引发中枢及外周自主神经系统的深刻改变。这些神经重塑又会反过来加速心血管疾病的进展，形成恶性循环。然而，目前针对心血管疾病的神经调控疗法主要集中于外周神经系统，针对复杂中枢的干预则相对滞后。 2025年12月11日，美国加州大学洛杉矶分校Marmar Vaseghi团队在国际期刊Nature Reviews Neuroscience上发表了题为The brain–heart axis: effects of cardiovascular disease on the CNS and opportunities for central neuromodulation的研究论文。 该综述系统性地阐述了在高血压与心力衰竭等疾病状态下，中枢神经系统内从脊髓、脑干到高阶皮层广泛存在的血管紧张素信号增强、神经炎症、氧化应激及胶质细胞活化等共性病理重塑特征。文章不仅详细解析了这些改变如何导致交感神经过度激活与副交感神经功能抑制，还全面评述了针对这些中枢靶点的多种神经调控工具与策略的最新进展及挑战。这些工作为未来开发以中枢神经系统为靶点的心血管疾病创新疗法奠定了重要的理论基础进铁死亡，并在类器官和动物模型中显著增强肺腺癌对化疗及化疗联合免疫治疗的敏感性。

- 论文 DOI：10.1016/S1474-4422(25)00402-8

## 博文资讯

4. [ggplot2 开始将其核心OOP系统从S3迁移到S7](https://tidyverse.org/blog/2025/09/ggplot2-4-0-0/ "ggplot2 开始将其核心OOP系统从S3迁移到S7")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251225174912.png)

ggplot2 4.0.0 版本发布，开始将其核心OOP系统从S3迁移到S7，这标志着标志着S7已经具备了支撑数百万级用户核心基础设施的稳定性。

5. [CRediT（Contributor Roles Taxonomy）](https://groups.niso.org/higherlogic/ws/public/download/31067/CRediT_Taxonomy_Terms_and_Definitions_list "CRediT（Contributor Roles Taxonomy）")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251225175306.png)

CRediT（Contributor Roles Taxonomy）即“贡献者角色分类法”，是一个由 ANSI/NISO 批准的国际标准，旨在更准确、透明地反映学术研究成果（如期刊论文）中每位参与者的具体贡献。它通过将研究贡献细分为 14 个不同的维度，解决了传统排名无法体现交叉学科合作中具体分工的问题。

6. [浪淘沙预印本平台接收文章方向](https://mp.weixin.qq.com/s/rApaiIEY2m8_uxno2AQKrg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251225175440.png)

“浪淘沙”平台聚焦生命科学领域，目前覆盖15个主要学科方向：生物化学与生物物理学、生物工程与生物技术、生命科学与人工智能、细胞生物学、化学生物学、计算生物学与生物信息学、发育生物学与解剖学、生态学与环境生物学、遗传学与基因组学、免疫学与微生物学、分子生物学、神经生物学、药理学与毒理学、生理学与病理学、植物学与农业科学。平台目前不接收临床试验或流行病学研究。

## 工具

7. [themis包处理数据类别不平衡问题](https://github.com/tidymodels/themis "themis包处理数据类别不平衡问题")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251225175829.png)

themis 是 R 语言中 tidymodels 生态系统里的一个扩展包，专门用于处理数据不平衡（Unbalanced Data）问题。当你的分类数据中某一类远多于另一类（例如欺诈检测、罕见病诊断）时，可以使用 themis 在 recipe 工作流中轻松集成这些采样算法，以提高模型对少数类的预测能力。

8. [AMSTAR 2-系统评价方法学质量评价工具](https://mp.weixin.qq.com/s/hknL4981KxATkPuvDdWNkg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251225180433.png)

随着系统综述在临床与政策决策中的广泛应用，越来越多的综述不仅纳入随机对照试验（RCTs），也纳入了非随机研究（NRSIs）。然而，非随机研究更易受到偏倚影响，因此评估其方法质量显得尤为关键。AMSTAR（2007年发布）是最早用于评价RCT系统综述的方法工具之一。为了更好地评估同时包含RCT与NRSI的综述，研究团队开发了AMSTAR 2，这是原始AMSTAR的重大升级，旨在帮助用户区分高质量与存在方法缺陷的系统综述。

- 论文 DOI：10.1136/bmj-2025-085718

9. [一站式科研服务平台MedPeer](https://mp.weixin.qq.com/s/SlIg9X4cO6hgJfErw2f7QQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251225181129.png)

MedPeer 科研绘图工具则提供了 10 万 + 原创矢量图标，覆盖 30 余种生物医学学科且这些图标风格统一，还支持自定义配色，可根据论文风格灵活调整~（PS：该网站需要会员 ~）

## 资源

10. [MMWR（Morbidity and Mortality Weekly Report）](https://www.cdc.gov/mmwr/index.html "MMWR（Morbidity and Mortality Weekly Report）")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251225181544.png)

MMWR 是由美国疾病控制与预防中心（CDC）出版的权威科学刊物。它通常被称为“CDC 的声音”，是该机构发布公共卫生信息、建议和科学报告的主要平台。MMWR 涵盖广泛的公共卫生主题，包括传染病、慢性病、环境健康、职业安全等。该刊物以其及时性、科学性和实用性著称，旨在为公共卫生专业人员、政策制定者和公众提供最新的研究成果和实践指南。想了解美国乃至全球最新的公共卫生趋势、疫情预警或权威医疗指导，MMWR 是最重要的参考来源之一。

11. [文献检索平台Connected Papers](https://www.connectedpapers.com/ "Connected Papers")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251225182428.png)

Connected Papers 是一个专门为科研人员和应用科学家设计的可视化文献探索工具。它能将学术论文之间的关系以“可视化图表（Graph）”的形式呈现，帮助用户快速了解某个研究领域的全貌，发现最重要的论文。它通过分析数万篇论文，利用“共同引用（Co-citation）”和“文献耦合（Bibliographic Coupling）”来计算论文间的相似性。即使两篇论文没有直接互相引用，只要它们参考文献重合度高，就会被连接在一起。

## 贡献者（GitHub ID）

「OpenBioStat 生统爱好者周刊」运维小组：

- [`@Leslie-Lu`]（陆震）
- [`@YihanChen325`]（陈奕含）
- [`@kirihsia`]（夏鑫辛）
- [`@GCRPM`]（徐林玉）

## 订阅

本周刊每周五发布，支持 [RSS 订阅](https://leslie-lu.github.io/biostat_weekly_rss.xml "生统爱好者周刊 RSS 订阅")，同步更新在微信公众号「陆震生物统计」（luzhen-biostat）上。

微信搜索“陆震生物统计”或者扫描二维码，即可订阅。

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251113212819.png)

（完）
