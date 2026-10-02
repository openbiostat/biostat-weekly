# 生统爱好者周刊（第 52 期）：复杂世界里的不平等与公平

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261001225959.png)

## 本周话题：[复杂世界里的不平等与公平](https://mp.weixin.qq.com/s/wq31NV6xMSnGOwponqMIvg)

《自然-人类行为》“复杂世界里的不平等与公平”专题，指出不平等并非单一问题，而是由个人差异、社会结构、文化观念、技术变革与环境因素交织形成的复杂系统；其表现既包括“随时间累积”的机会差距，也包括在出生前后由遗传、环境与教育资源不均带来的代际传递。与此同时，不同人对“平等/公平”的理解并不一致，而这种价值观与归因方式（例如对个人努力与社会结构的不同权重）会直接影响对再分配、干预和政策的接受程度。文章还强调：教育、健康、就业与环境不平等相互强化，技术与AI既可能缩小差距也可能通过数据偏见与数字鸿沟放大不平等，因此需要跨学科、面向真实世界的研究框架来指导政策与组织实践。

## 生统研究

1. [npj Digital Medicine | RDMA：一种基于Agent、从电子健康记录中挖掘罕见病的高性价比方法](https://mp.weixin.qq.com/s/DtbMUqI1Z0gBt1NwZR6uxQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/Screenshot2026-10-01at23.03.26.png)

RDMA（Rare Disease Mining Agents），一个面向罕见病的多 Agent 框架，通过提取、验证、隐含表型推理和 HPO/Orphanet 编码，将病历中的自由文本和实验室异常转化为结构化的罕见病表型信息。研究发现，24B 的本地量化模型结合合理的 Agent workflow，可以在多个 benchmark 上取得较好的表现，说明医学 AI 的提升不一定依赖更大的模型，而可以通过更合理的工作流、医学知识库和本地部署来提高表型挖掘的准确性与可用性。

- 论文 DOI：10.1038/s41746-026-03070-x

2. [Lancet Diabetes & Endocrinology | 每周一次司美格鲁肽2.4 mg为中国超重/肥胖人群提供本土高效减重新循证](https://mp.weixin.qq.com/s/N-vN-b8DzkM-Akrg882HZA)

司美格鲁肽（Semaglutide）2.4 mg 是一种每周皮下注射一次的胰高血糖素样肽-1（GLP-1）受体激动剂，在降低体重的同时兼具多重心血管代谢获益。为了评估其在中国本地 BMI 标准定义的超重或肥胖成人中的有效性与安全性，由北京医院郭立新教授领衔的团队联合多家中心开展了 STEP 12 临床试验。该成果近日发表于国际学术期刊 The Lancet Diabetes & Endocrinology。研究显示，在中国按本地 BMI 标准定义的超重或肥胖成人（伴或不伴 2 型糖尿病）中，每周一次皮下注射司美格鲁肽 2.4 mg 联合生活方式干预治疗 44 周，可实现大幅且有临床意义的体重降低，且耐受性良好。该研究成果为我国超重及肥胖症的规范化临床诊疗提供了高质量的本土循证依据。

- 论文 DOI：10.1016/S2213-8587(26)00133-6

## 博文资讯

3. [海归当了院长，“明星效应”如何影响学科产出？](https://mp.weixin.qq.com/s/8WjvX8HFKN9YsEjUdNqrsA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261001232030.png)

当一位海归学者出任高校院长，他会如何影响院系发展？会拉动学科科研实力提升还是仅仅成就个人的“明星效应”？学术界对此讨论已久，却大多依赖经验判断，缺少实证证据。

4. [AI时代科研诚信的挑战与应对](https://mp.weixin.qq.com/s/3u3jzYd_hslPwff9HrqHrg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261001232310.png)

全球撤稿论文数量十年增长近10倍，AI技术加剧了虚假或错误论文的风险；《柳叶刀》通过贯穿投稿至发表全流程的审查机制（如自动检测抄袭、虚构参考文献及同行评议）来维护科研诚信，并要求作者披露AI使用情况；同时，期刊联合世界科研诚信大会基金会成立国际委员会，强调科研诚信问题需从源头预防，依赖整个科研生态系统的集体努力，而非相互指责。

## 工具

5. [CCSR for ICD-10-CM diagnoses](https://hcup-us.ahrq.gov/toolssoftware/ccsr/ccs_refined.jsp "CCSR for ICD-10-CM diagnoses")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/Screenshot2026-10-01at23.25.17.png)

CCSR 全称是 Clinical Classifications Software Refined。它属于 HCUP（Healthcare Cost and Utilization Project）的一套研究工具，由 AHRQ 支持。目前官网介绍的 CCSR for ICD-10-CM diagnoses，把超过 70,000 个 ICD-10-CM diagnosis codes 聚合成 530 多个 clinical categories，再分布在 22 个 body systems 中。它的核心目的不是重新编码病历，而是把非常细碎的 ICD-10-CM/PCS code 聚合成更有临床意义、也更适合科研分析的 categories。

6. [Simpletex 公式输入神器](https://mp.weixin.qq.com/s/tQe1XzihOJfkFUQ8xJkkiw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261001232705.png)

介绍一款用于学术写作的公式输入工具 SimpleTex：用户可以通过“截图/拍照”把文献或纸上复杂公式导入，工具自动识别并生成可编辑结果；随后还能将识别后的内容以 LaTeX 形式导出，便于在 Word 等软件中再次编辑与插入，从而显著减少手动敲公式的繁琐。文末还顺带推广艾笔论平台，称其可根据论文题目快速生成论文内容并配套公式、代码、图片与表格，帮助赶进度的学生降低写作成本。

## 资源

7. [炎症性抑郁症（ISMDD）的临床识别与评估：国际德尔菲专家共识](https://mp.weixin.qq.com/s/JiidadVIb4s5b8UhLNuOcA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261001232826.png)

2026年发表于《Brain, Behavior, and Immunity》的ASPIRE国际德尔菲专家共识，旨在建立炎症性抑郁症（ISMDD）的临床识别与评估框架。研究从症状域、评估量表及患者体验三个方面形成共识，指出疲劳、嗜睡、动机缺乏、体重/食欲增加和认知困难是较具一致性的特征，并发现IDS-SR/QIDS-SR对相关症状覆盖最全面。文章强调，识别炎症性抑郁症有助于理解部分患者常规治疗反应不佳，并推动抑郁症精准分型与个体化治疗研究。

8. [AVMoments-EEG：一个面向自然动态视听事件加工的大规模开放EEG数据集](https://mp.weixin.qq.com/s/T6s5hnn_XPCxibDZz2D7zg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/Screenshot2026-10-01at23.30.05.png)

AVMoments-EEG，一个包含10名被试、每人超过1万个EEG trials的大规模自然视听事件数据集，通过自然短视频以及视觉、听觉信息的系统性操纵，研究大脑如何处理动态、多模态事件。数据集同时开放了从原始EEG到预处理、epoch-level和stimulus-level的数据及代码，可用于EEG编码/解码、人脑与AI模型对齐、多模态神经表征以及NeuroAI benchmark等研究。

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

同时，本周刊同步支持 [RSS 订阅](https://leslie-lu.github.io/biostat_weekly_rss.xml "生统爱好者周刊 RSS 订阅")；本周刊同名中文播客现已正式在[苹果播客（Apple Podcasts）](https://podcasts.apple.com/cn/podcast/%E7%94%9F%E7%BB%9F%E7%88%B1%E5%A5%BD%E8%80%85%E5%91%A8%E5%88%8A/id1868591486?l=en-GB "Apple Podcasts 订阅")和[小宇宙](https://www.xiaoyuzhoufm.com/podcast/69650caa93e769238063a05e "小宇宙订阅")平台上线，搜索`生统爱好者周刊`即可订阅收听。该播客内容基于本周刊公开内容制作，相关学术论文链接及原始资讯请查阅本周刊文字版。

（完）
