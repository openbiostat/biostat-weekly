# 生统爱好者周刊（第 58 期）：泛美卫生组织确认美国、墨西哥和玻利维亚失去麻疹消除认证

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261119194745.png)

## 本周话题：[泛美卫生组织确认美国、墨西哥和玻利维亚失去麻疹消除认证](https://www.paho.org/en/news/17-11-2026-paho-urges-countries-step-efforts-stop-measles-outbreaks-and-move-towards "泛美卫生组织确认美国、墨西哥和玻利维亚失去麻疹消除认证")

泛美卫生组织在11月10—13日独立地区审查后确认，美国、墨西哥和玻利维亚均因重新出现持续本土传播而失去国家级麻疹消除认证。其判定标准为同一麻疹病毒基因型及谱系在一国连续传播至少12个月；美国相关传播自2025年1月开始。美国CDC于11月17日发表联合声明，承诺加强MMR疫苗接种、疫情识别、数据共享和联动应对，并称自8月以来为全国预防与应对额外提供约1亿美元资金。这是美国传染病监测和疫苗政策的重大事件，体现了“消除”与“根除”的差别，以及基因组监测、流行病学调查和薄弱接种地区防控工作的必要性。

## 生统研究

1. [JAMA | SURMOUNT-ADOLESCENTS随机试验评估替尔泊肽治疗青少年肥胖](https://jamanetwork.com/journals/jama/fullarticle/2856796#251340028 "JAMA | SURMOUNT-ADOLESCENTS随机试验评估替尔泊肽治疗青少年肥胖")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261119192725.png)

这项72周双盲安慰剂对照随机试验将160名12至未满18岁的青少年分配至每周使用替尔泊肽（109人）或安慰剂（51人），两组均接受生活方式干预。两组BMI平均变化分别为−18.5%和+0.5%，组间估计差异为−19.0个百分点（95% CI −23.9至−14.1；P < .001）。至少降低5% BMI的比例分别为79.6%和28.5%；接受治疗者胃肠道不良事件发生率为81.5%和54.9%，因不良事件停药比例为9.3%和0%。样本量与人群多样性有限，72周观察也不足以确认处于生长发育期青少年的长期安全性。这为青少年肥胖治疗提供了直接随机试验证据，但显著疗效需要与耐受性、长期安全性一同评估。

- 论文 DOI：10.1001/jama.2026.23420

2. [Nature Medicine | 司美格鲁肽对2型糖尿病肾病的多层面保护机制](https://mp.weixin.qq.com/s/eqKJIecVA3X3h4-SO40bbw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261119193003.png)

2026年，华盛顿大学Katherine R. Tuttle团队联合Petter Bjornstad团队在Nature Medicine（IF=58.7）在线发表题为"Effects of semaglutide on kidney disease in type 2 diabetes: a randomized placebo-controlled trial"的研究论文。研究团队开展了一项为期52周的随机对照试验（REMODEL），纳入106例T2D合并CKD受试者（女性25例、男性81例），比较每周一次皮下注射司美格鲁肽1 mg与安慰剂的治疗效果。在此基础上，研究进一步整合肾脏多参数磁共振成像、肾活检组织学、单核RNA测序及空间转录组学等多维度技术，以系统解析司美格鲁肽的肾脏特异性作用及其潜在机制。

- 论文 DOI：10.1038/s41591-026-04674-2

## 博文资讯

3. [健康世界模型 A world model simulates the latent dynamics of human health](https://mp.weixin.qq.com/s/FPTnan_rq1jTNk-JHdp1Dw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261119193105.png)

斯坦福大学等机构研究团队提出HealthFlux，一种基于多模态数据的健康世界模型。研究整合UK Biobank中502,166名参与者的11类数据、5,647项特征，构建可随时间动态演化并持续更新的潜在健康状态，实现对1,010种疾病及死亡风险的预测。模型在长期疾病预测、未见疾病迁移及外部队列验证中均展现出良好表现，为利用多模态纵向数据理解健康变化、实现疾病早期风险预测提供了新的思路。

4. [长期健康智能体，不只是“会记住”](https://mp.weixin.qq.com/s/OEJzDl9Z27y6jrvHijKT8Q)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261119194314.png)

这篇论文从更像“随访队列”的视角出发，提出健康智能体不仅要记忆数据，还要在时间维度上保持连贯、追踪变化、动态更新判断，并在干预与放手之间拿捏分寸——关键问题不在记多少，而在怎么管。

## 工具

5. [Quantile g-computation分析暴露混合物的健康影响](https://mp.weixin.qq.com/s/Ohdw1jlZ9k8ReLjdELmICw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261119193651.png)

在如今的研究中，我们常常需要评估多种暴露因素（如多种污染物、营养素等）对健康结局的综合影响。然而，传统的分析方法往往存在局限性。介绍一种新的方法，quantile g-computation。

6. [生存分析、Cox模型、时变 (Time-varing) Cox模型、tmerge()函数](https://mp.weixin.qq.com/s/unvymvhtsYCXCMDeb7PxDQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261119193803.png)

生存分析是一大类广泛用于数据分析的统计方法，其中我们感兴趣的结果变量是事件发生之前的时间。

## 资源

7. [分类变量的纵向数据分析](https://mp.weixin.qq.com/s/RJ_p4OYGVnAq_Z5_SqrMjg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261119193436.png)

应用心理学中，纵向数据分析为研究者提供了对连续多时间点心理数据的深入分析手段。当处理分类变量如性别（男/女）、满意度（满意/不满意）时，以下是几种核心的方法学技术。

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
