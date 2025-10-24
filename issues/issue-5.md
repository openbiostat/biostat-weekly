# 生统爱好者周刊（第 5 期）：无偿审稿，是学术看门人还是免费苦力？

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251023161829.png)

## 本周话题：[无偿审稿，是学术看门人还是免费苦力？](https://mp.weixin.qq.com/s/YwMcDczeITY6MwEnYGGjoQ)

> 在出版链条中，编辑、期刊、出版商都有钱赚，唯独审稿人“两袖清风”，不拿一分钱报酬。有人提议给审稿人付费，却被出版商嗤之以鼻：一来支付报酬会推高成本；二来担心收费评审会产生“利益冲突”。然而，作者掏腰包付论文处理费（APC），机构砸钱买期刊访问权，编辑拿着薪水做最终裁决，这些“金钱交易”怎么就不算利益冲突？唯独审稿人，被塑造成无需报酬的“学术超人”，靠徽章、证书或“免费读论文”打发。

@Leslie-Lu 在同行评审之前，或许应该拥抱 AI 审稿，只是不给这一轮太大的权重。否则越来越海量的文章，无论是否灌水，漫长的巨量审稿，对审稿人、作者、期刊三方都是巨大的负担。

## 生统研究

1. [Lancet | 双抗 ADC 药物 iza-bren 首个注册III期临床研究结果发表](https://mp.weixin.qq.com/s/06fCWD0KEYhzkj9ZydDKAA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251023162359.png)

百利天恒公布了其全球首创、新概念EGFR×HER3双抗ADC药物——iza-bren的首个注册III期临床研究结果，结果显示与标准化疗（吉西他滨、卡培他滨或多西他赛）相比，iza-bren后线治疗鼻咽癌疗效翻倍（cORR 54.6% vs. 27.0%，mPFS 8.38m vs. 4.34m），标志该药物完成了从概念验证到疗效验证的关键里程碑。在鼻咽癌领域，该研究是全球首个针对鼻咽癌后线治疗的确证性随机对照III期研究，成果成功入选ESMO大会最高荣誉环节——Late-breaking Abstract (LBA)，并经快审通道在柳叶刀正刊获同步发表。鼻咽癌领域的关键贡献者、香港中文大学Anthony TC Chan教授在同期述评中高度评价：“与标准化疗相比，iza-bren疗效翻倍，ADC药物将成为未来鼻咽癌治疗的基石。”

- 论文 DOI：10.1016/S0140-6736(25)01954-3

2. [Cell | UKB 53026名成年人健康和疾病血浆蛋白质组图谱](https://mp.weixin.qq.com/s/8RaNKWLliBvUCvbmbbf1PA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251023162123.png)

这项研究不仅提供了全球首个大规模血浆蛋白质图谱，还首次系统地揭示了2,920种血浆蛋白与健康和疾病之间的深层联系，包含了超过700种疾病和986种健康相关特质。

- 论文 DOI：10.1016/j.cell.2024.10.045

## 博文资讯

3. [ICH M14指导原则中文版征求意见：真实世界数据用于药品安全评估迎来国际标准](https://mp.weixin.qq.com/s/O9Z8qnKh1tYmsHy4dRAGIQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251023162732.png)

10月17日，国家药监局药品审评中心（CDE）正式发布通知，公开征求ICH《M14：使用真实世界数据进行药品安全性评估的非干预性研究：规划、设计、分析和报告的一般原则》指导原则实施建议和中文翻译稿的意见。这标志着真实世界数据（RWD）用于药品安全性评估正式有了国际通行的技术标准。

4. [Transformer自回归关键技术：掩码注意力](https://mp.weixin.qq.com/s/4GpSmsqq8ZafFxwD7lViXw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251023162856.png)

掩码机制让GPT等模型能够逐词生成文本，每次预测都只基于已经生成的内容，这正是自回归语言模型的精髓所在。通过一个上三角掩码矩阵，就能让模型在训练时学会"单向思考"，这种设计的巧妙之处在于它完美平衡了计算效率和生成质量。掌握了掩码注意力，你就理解了GPT、LLaMA等主流生成模型的核心工作原理。

5. [倾向性评分动画介绍](https://mp.weixin.qq.com/s/yJl-jAhli2I_sXtCGDoN7g)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251023163050.png)

本期《NEJM循证》（NEJM Evidence）STATS, STAT! 动画以为华夫饼选择最优质枫糖浆为例，介绍了如何应用倾向性评分校正观察到的混杂因素，使观察性研究更接近随机试验的效果，从而比较接受不同治疗患者的结局。

## 工具

6. [ASReview](https://github.com/asreview/asreview "ASReview")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251023163259.png)

ASReview是一款专为系统综述设计的开源主动学习软件,可以显著提高大规模文献筛选的效率，其算法原理为人工智能中的主动学习（active learning）。它基于的 ASReview Python 软件包构建，利用最先进的主动学习算法，使使用者能够轻松筛选大型数据集、模拟评价过程和管理项目。ASReview LAB v.2 已通过使用共享的 AI 模型，实现了 AI 辅助系统评价的进步，支持多位专家协作筛选。

7. [合并两张ggplot图](https://mp.weixin.qq.com/s/d34d-Ub2BAX85n5Fw0aOFw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251023163439.png)

Y叔推文介绍了多种合并两张 ggplot 图的实现方式，适合作为图形语法的学习材料。

## 资源

8. [UK Biobank Community](https://community.ukbiobank.ac.uk/hc/en-gb "UK Biobank Community")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251023163644.png)

UKB 官方指南，指导如何开始注册账号、理解 UKB 数据格式、使用 UKB-RAP 进行数据分析等。

9. [R Shiny 制作网页](https://www.analyticsvidhya.com/blog/2021/05/build-interactive-models-with-r-shiny/ "R Shiny 制作网页")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251023163810.png)

推文详细介绍了如何利用 R Shiny 制作可与用户进行互动的网页版的模型工具平台。

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
