# 生统爱好者周刊（第 24 期）：OpenClaw会是科学家的“超级助手”吗？

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260313000034.png)

## 本周话题：[OpenClaw会是科学家的“超级助手”吗？](https://mp.weixin.qq.com/s/nBclwC2dPU_at5t7f5FEkQ)

OpenClaw 的出现，标志着 AI 正从“对话时代”跨入“代理时代”。它像是一个刚刚学会走路的孩子，拥有无穷的好奇心和破坏力。它带给我们的不仅仅是生产力的跃迁，更是对人类与 AI 关系的一次重塑。OpenClaw 对科研人员来说，它能大幅提升自动化处理的效率，但目前仍需警惕其带来的底层安全风险。

## 生统研究

1. [Nat Biomedical Engineering | spEMO: 首个整合病理图像与文本嵌入的空间多组学 AI 系统](https://mp.weixin.qq.com/s/SuK5VBXunI2t3x_yr0-4ZQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260313000222.png)

该论文提出一个用于空间多模态数据分析的新型框架spEMO，可将病理学基础模型与大语言模型的嵌入表示统一，用于空间多组学分析。通过整合来自多模态的生物学先验知识（包括 LLMs 与 PFMs，尤其是全切片图像（Whole Slide Images, WSIs）嵌入）实现数据统一。通过将这些嵌入与空间解析的转录组和多组学数据结合，spEMO 构建了一个训练灵活的框架，并通过任务专用专家模块增强下游分析能力。

- 论文 DOI：10.1038/s41551-025-01602-6

2. [Science | Drugclip: AI驱动的超高通量药物虚拟筛选平台](https://mp.weixin.qq.com/s/Ug6zd3Yv2QQMIrccz6ERUQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260313000519.png)

目前，人类对靶向药物的探索约覆盖人体全部可成药靶点的10%。面对数以万计的潜在靶点，如何在广阔的化学空间中，快速筛选苗头化合物，已成为该领域里的瓶颈。清华大学智能产业研究院（AIR）兰艳艳教授联合生命学院、化学系团队创新研发AI驱动的超高通量药物虚拟筛选平台DrugCLIP。DrugCLIP筛选速度对比传统方法实现了百万倍提升，同时在预测准确率上也取得显著突破。依托该平台，团队首次完成了覆盖人类基因组规模的药物虚拟筛选，为创新药物发现带来了新的可能性。

- 论文 DOI：10.1126/science.ads9530

## 博文资讯

3. [深入解析OpenClaw上下文窗口压缩方案](https://mp.weixin.qq.com/s/CwnJ9jK4_g9Sd8jxaOddQA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260313000605.png)

最近很火的 OpenClaw 的出镜率是越来越高了，内外网的技术文章，新产品的问世，Mac Mini 的涨价，自媒体的宣传层出不穷。作者是国外一个叫 Peter Steinberger（现已经被奥特曼高薪挖到 OpenAI ），说是花了一个周末就烹饪完成的“小龙虾”。这篇文章具体展示它内部详细是如何进行上下文窗口管理的。

4. [艾伦·图灵](https://en.wikipedia.org/wiki/Alan_Turing "艾伦·图灵")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260313000800.png)

Alan Turing（艾伦·图灵，1912–1954） 是英国数学家、逻辑学家、密码学家与计算机科学先驱，被广泛誉为计算机科学之父和人工智能思想的奠基者之一。他提出的理论模型深刻定义了“什么是计算”，并直接塑造了现代计算机与 AI 的思想边界。

## 工具

5. [AlphaGenome API](https://deepmind.google.com/science/alphagenome/ "AlphaGenome API")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260313000857.png)

AlphaGenome API是 Google DeepMind 推出的基因组分析工具，能够解析长达 100 万个碱基对的 DNA 序列，并提供精确到单碱基的多模态预测（如基因表达、染色质特征等），预测性能处于业界领先水平。API 对非商业用途免费。受限于动态的服务器压力，它非常适合需要几千次预测的中小型分析，但不适合超过 100 万次预测的大规模任务。

6. [德尔菲法质量评价工具 Delphi Critical Appraisal Tool (DCAT)](https://mp.weixin.qq.com/s/FlhYLO6pYe-KybHMAjxwGQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260313001100.png)

德尔菲法 (Delphi method) 在医学研究中广泛用于临床指南制定、医疗质量指标开发、临床试验终点指标确定。它由4个核心条目和12个附加条目组成，涵盖了从研究设计到结果报告的全过程。DCAT 可帮助审稿人、读者、系统评价团队和研究设计者全面评估德尔菲研究的质量并指导高质量的研究设计。

## 资源

7. [The Health and Retirement Study](https://hrs.isr.umich.edu/ "The Health and Retirement Study")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260313001203.png)

密歇根大学 Health and Retirement Study (HRS) 是一项由美国国家衰老研究所和社会保障局资助的大型纵向追踪调查，调查对象为美国约 20,000 名具有代表性的人群。HRS 通过其独特而深入的访谈，提供了大量宝贵且不断增长的多学科数据，研究人员可以利用这些数据来探讨有关老龄化挑战和机遇的重要问题。

8. [eBioMedicine｜2025年度精选 8 篇重磅研究全景盘点](https://mp.weixin.qq.com/s/aUlmAGUgEXNYb5uOab5VGw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260313001315.png)

eBioMedicine 盘点 2025 年度精选论文：涵盖MAFLD肝再生的肠道菌群与代谢机制、阿尔茨海默高危人群衰老细胞清除试验、大语言模型赋能精准肿瘤学、GLP‑1R/GCGR 双激动剂改善糖尿病相关认知障碍、塑化剂心血管风险评估、炎症调节纳米颗粒、卵巢癌CAR‑T新策略及人肺单细胞图谱等前沿进展。

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
