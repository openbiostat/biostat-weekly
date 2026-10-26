# 生统爱好者周刊（第 53 期）：美国科研经费动态

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261015192951.png)

## 本周话题：[美国科研经费动态](https://www.aip.org/fyi/the-week-of-october-5-2026 "美国科研经费动态")

AIP 最新科研政策简报显示，NSF 在 2026 财年结束时仍有超过 10 亿美元科研经费未完成义务化支出。NSF 今年科研支出约 64 亿美元、涉及 6,218 项资助，较 2025 财年下降约 23%。相比之下，尽管 NIH 年初 grantmaking 进展缓慢，但最终仍完成了约 340 亿美元院外科研预算的支出。对在美国科研体系里工作的人，这个差异非常重要。名义预算并不等于实际可获得的科研经费；grant 发放速度、资金义务化比例以及机构执行方式，都会直接影响实验室、博士后岗位和新项目机会。

## 生统研究

1. [Nature Communications | 用WGS-代谢组-多组学整合锁定因果变异与药物靶点](https://mp.weixin.qq.com/s/pProCcQ3c3tYaaT05e4Wrg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261015194112.png)

复旦大学郁金泰团队在 Nature Communications 用 UK Biobank 的199,138人WGS 联合 313项血浆代谢物，识别出 36,105个遗传信号（其中 22.20% 为新信号），并精细定位 12,361个因果变异关联。相比芯片插补，WGS更好捕获低频/罕见与非编码变异，使代谢性状遗传力中位数达 0.31。进一步通过 MR与共定位 找到 245个潜在因果“代谢物-疾病”关系，再结合 1,856种血浆蛋白的cis-MR、MR-BMA及方向一致性 优先出 410个潜在药物靶点；其中 81个已有获批药物或处于临床试验阶段，并纳入安全性评估筛选出更多可推进候选。研究提出可复用的 “WGS-代谢组-多组学” 整合框架，用于机制解析与靶点优先化。

- 论文 DOI：10.1038/s41467-026-74781-8

2. [BMJ | 糖尿病患者心血管病风险预测模型跨国应用的再校准方法评价](https://mp.weixin.qq.com/s/tz4CreSQSq3Pk-6G1xXsZw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261015191551.png)

研究基于中国CHERRY队列与新西兰PREDICT队列，比较糖尿病患者心血管风险预测模型在跨国应用中的危险因素效应差异，并评估PREDICT-T2D模型对中国人群的适用性。结果显示血压、血糖等多数因素效应相近，但年龄效应显著异质：若直接应用或仅常规再校准，可能高估年轻人、低估高龄人，导致过度或不足治疗。研究提出在常规再校准基础上联合更新年龄回归系数可显著提升校准；同时给出面向资源受限人群的简化再校准方法，无需获取全部个体预测变量数据。

- 论文 DOI：10.1136/bmj-2026-100535

## 博文资讯

3. [2026 诺贝尔生理学或医学奖授予光遗传学奠基者](https://www.reuters.com/business/healthcare-pharmaceuticals/deisseroth-hegemann-nagelwin-2026-nobel-medicine-prize-2026-10-05/ "2026 诺贝尔生理学或医学奖授予光遗传学奠基者")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261015191806.png)

Karl Deisseroth、Peter Hegemann 和 Georg Nagel 因发现光门控离子通道并推动光遗传学发展而获得 2026 年诺贝尔生理学或医学奖。光遗传学让研究者能够利用光精确控制特定神经元，已经深刻改变神经环路研究。除了是这几天最重要的生物医学新闻之一，它也很好地说明了基础机制研究如何逐渐发展为平台型技术，并进一步进入神经科学、疾病模型甚至潜在治疗领域。

4. [40年前的航空规范，救了爱说废话的AI](https://mp.weixin.qq.com/s/5YPKctLVxVKXVwa1KDiH4A)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261015191934.png)

AI 真的太爱说废话了。为此，Karpathy 专门分享了一组技巧，针对的就是怎么让大模型越来越多的输出变得更容易理解。Karpathy 拿出的是一套 40 年前的航空写作规范。而40 年前的航空规范，让大模型输出清晰易读。

## 工具

5. [用 ggplot2 的语法，画出六种网络与层级图](https://mp.weixin.qq.com/s/v7s3V71fbTqeyQGTNNtyCA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261015192022.png)

本文介绍 R 包 ggraph 如何用类似 ggplot2 的图层语法绘制网络与层级图。用两套内置数据（层级的 flare 与关系调查的 highschool）展示六种常见可视化：四种层级树图（圆形树状图、圆形打包图、矩形树图、自由布局树图）以及两种关系网络图（基于入度大小的关系网络图、按编号排列的弧线图），布局会改变观察角度但不自动消除复杂关系。文章最后给出可直接运行的完整 R 代码，并说明替换数据时需要的 from/to 边表与带唯一 name 的节点表，以及在层级结构与一般网络中应如何选择合适的布局。

## 资源

6. [科研软件合集](https://mp.weixin.qq.com/s/RQf8xoueJBBf1dF9n2GUDg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261015192233.png)

本文是一份“科研软件合集”类文章，围绕科研与工程工作中常见的软件需求进行系统梳理，覆盖办公与文献管理、图像/媒体处理、3D与设计等多个方向；作者按功能类别罗列了大量具体软件及其典型用途，旨在帮助读者快速定位适合自身任务的工具。整体核心思想是以“按任务领域分门别类”的方式，提供覆盖面广的科研与工程软件参考清单。

7. [率的标准化与分解](https://www2.census.gov/library/publications/1993/demographics/p23-186.pdf#page=2.18 "率的标准化与分解")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261015192505.png)

《率的标准化与分解：用户手册》（Standardization and Decomposition of Rates: A User's Manual），作者是 Prithwis Das Gupta。这是一本方法论手册，目的是让读者掌握"标准化与分解"技术的实际应用和结果解读，而不必陷入繁琐的数学推导。报告给出了处理"标准化与分解"这一双重问题的方法，可适用于任意数量的因素和任意数量的人群，也涵盖了多种因素与总体率之间的关系（例如，率等于若干因素的乘积，或来自交叉分类数据的率）。书中的分解方法把两个率之间的差异拆分为可加的主效应，不涉及交互效应。适合谁读： 人口学、公共卫生、社会统计等领域，需要比较不同人群的死亡率、出生率、就业率等指标，并想弄清差异究竟由哪些因素造成的研究者和学生。

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
