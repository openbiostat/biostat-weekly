# 生统爱好者周刊（第 7 期）：减少行政性学术评价，缓解年轻教师职业压力

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251106204821.png)

## 本周话题：[减少行政性学术评价，缓解年轻教师职业压力](https://mp.weixin.qq.com/s/aFBGd6uYy3vvhauegPZYcA)

> 当前高校中行政性学术评价的泛滥，确实让年轻教师陷入无形的竞争与焦虑之中。这种以行政权威为导向的评价机制，削弱了学术研究的自主性与创造性，使教师不得不将精力从教学科研转向应付指标与申报。

`@kirihsia` 行政性学术评价的泛滥反映了评价体系与教育初心之间的错位，也暴露出学术生态的功利化倾向。唯有让评价回归学术本身，才能真正减轻教师负担，恢复高校应有的学术活力。

## 生统研究

1. [Nature Medicine | AI生命时钟准确预测从婴儿到老年的生物学年龄及疾病风险](https://mp.weixin.qq.com/s/eq5vXqI99N_mq99F8euWrA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251106205348.png)

衰老是一个涉及分子、细胞和器官多层次变化的复杂过程，生物学年龄比实际年龄更能反映个体衰老速度与健康状况。随着多组学、影像学和电子健康记录的发展，衰老时钟（Aging Clock）可通过多维生物标志物精准预测个体的生物学年龄及疾病风险。该研究基于近千万人的EHR数据，利用Transformer架构的AI模型EHRFormer开发出全生命周期时钟LifeClock，首次将婴儿期到老年期的发育与衰老过程整合在同一框架中，揭示了18岁前以发育为主、18岁后以衰退为主的两种时钟模式。该模型区分了儿童和成人时钟，能准确预测不同阶段的主要疾病风险，为实现覆盖全生命周期的精准健康管理和延长健康寿命提供了新途径。

- 论文 DOI：10.1038/s41591-025-04006-w

2. [Nature Medicine | 潜伏的“幽灵”：带状疱疹病毒与老年痴呆的惊人联系](https://mp.weixin.qq.com/s/z14V_KQYroFI03qScg1JGA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251106205553.png)

水痘-带状疱疹病毒（VZV）在童年以水痘形式感染后潜伏于神经节中，免疫功能减弱时可重新激活，引发带状疱疹。过去人们认为其影响局限于皮肤和神经，最新发表于《Nature Medicine》的研究利用超过一亿人的健康记录发现，VZV的再激活与痴呆，尤其是阿尔茨海默病的发生风险显著相关。这项大规模流行病学研究首次系统揭示了神经病毒感染与认知退化之间可能存在的因果联系，提示带状疱疹不仅是皮肤病，更可能成为神经退行性疾病的潜在诱因，并为预防痴呆提供了可干预的新思路。

- 论文 DOI：10.1038/s41591-025-03972-5

3. [Nature | Array programming with NumPy](https://mp.weixin.qq.com/s/Cg0J0DeTQsqmllUXbZd1WA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251106210505.png)

这是一篇Nature上的综述论文，罕见的对一门编程语言库进行了专门综述，足可见其重要性。这篇文章中NumPy开发者全面地回顾了Numpy的历史，介绍了NumPy的基本设计理念与用法、以及围绕NumPy建立的庞大的Python科学计算生态系统。

- 论文 DOI：10.1038/s41586-020-2649-2

## 博文资讯

4. [中介分析的实现与多个 R 包横向测评](https://mp.weixin.qq.com/s/xBuy5XSu5YE3oueOEj3CCg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251106210732.png)

推文对比了五个R包：mediation、lavaan、psych、piecewiseSEM 和 brms。通过每个包的具体操作和结果展示，分析了其各自的优缺点：mediation 包简单易用，lavaan 支持潜变量，psych 操作便捷，piecewiseSEM 提供可视化和结构方程模型支持，brms 适合复杂模型。总结了不同R包在中介分析中的适用性，为研究者提供了实用的选择指南。

5. [因果推断 Causal Inference: What If](https://miguelhernan.org/whatifbook "因果推断 Causal Inference: What If")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251106210904.png)

本书旨在为所有对因果推断感兴趣的读者提供系统而实用的指导，共分为三个难度递增的部分：首先介绍无模型因果推断的基本概念和方法；随后探讨在特定模型框架下进行因果分析的思路与应用；最后深入讨论如何从复杂的纵向数据中进行因果推断，帮助读者全面理解并掌握因果推断的理论与实践。

6. [什么是订阅源 RSS](https://aboutfeeds.com/ "什么是订阅源 RSS")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251106211235.png)

推文详细介绍了什么是订阅源 RSS，对于想集中管理自己关注的信息流的同学，推荐阅读。

## 工具

7. [Covidence网站：高效的综述写作工具](https://mp.weixin.qq.com/s/58vB7LjZro_LYtMa2ytqsA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251106211429.png)

Covidence是一个在线平台，旨在帮助研究人员和团队简化文献综述和系统评价的整个过程，使研究变得更加高效。该平台包含引文筛选、全文审阅、偏倚风险评估、研究特征和结果提取以及数据和参考文献导出等多种功能，可高效地管理文献筛选、数据提取和质量评估。

8. [gtsummary包: 快速生成关联分析中的多个回归模型表格](https://mp.weixin.qq.com/s/noUyfHDKic4_O15afZn4Fw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251106211547.png)

gtsummary包是一个非常好用的R包，既可以绘制基线特征表，快速进行统计描述，也可以整理众多模型结果，快速输出高质量、发表级的统计表格。关联分析是临床研究中常用的统计学分析方法，此类论文中常用的统计表格包括基线特征表、分层分析、多个回归方程模型等。

## 资源

9. [又一个重症数据库，Northwestern ICU (NWICU) ](https://blog.csdn.net/idata01/article/details/143968881 "NWICU数据库介绍")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251106212253.png)

回顾性医疗数据收集对于推进患者护理、提供洞见并支持医疗技术发展至关重要。重症监护医疗信息集市 (MIMIC)-III 数据库在提供全面的重症监护数据以促进研究工作方面发挥了重要作用。该文介绍西北大学 ICU 数据库，一个从芝加哥医院网络收集并与 MIMIC 数据结构协调一致的重症监护数据集。

10. [All of US: Research Project Directory](https://www.researchallofus.org/research-project-directory/ "All of US: Research Project Directory")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251106212729.png)

All of US 研究项目为注册研究人员提供其 Researcher Workbench 项目的描述，以便其他研究人员、参与者和公众了解数据集的使用方式。

## 贡献者（GitHub ID）

「OpenBioStat 生统爱好者周刊」运维小组：

- [`@Leslie-Lu`]（陆震）
- [`@YihanChen325`]（陈奕含）
- [`@kirihsia`]（夏鑫辛）
- [`@GCRPM`]（徐林玉）

## 订阅

本周刊每周五发布，支持 [RSS 订阅](https://leslie-lu.github.io/biostat_weekly_rss.xml "生统爱好者周刊 RSS 订阅")，同步更新在微信公众号「陆震生物统计」（luzhen-biostat）上。

微信搜索“陆震生物统计”或者扫描二维码，即可订阅。

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/qrcode_for_gh_395f59db8b4c_258.jpg)

（完）
