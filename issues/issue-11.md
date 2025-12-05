# 生统爱好者周刊（第 11 期）：开放数据集滥用危机

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![儿童成长过程中有利、有害因素分布；论文 DOI：10.1016/S0140-6736(19)32540-1](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251203205245.png)

## 本周话题：[开放数据集滥用危机](https://mp.weixin.qq.com/s/7WZV_Mp8UiwaunKOS_4bMQ)

大量依赖 NHANES、UK Biobank 等开放数据库的公式化论文在期刊中涌现，引发对“论文工厂”和 AI 辅助写作滥用的担忧，低质研究的激增正在侵蚀学术出版的可靠性。面对数据集被滥用的趋势，Journal of Global Health 已率先收紧审核标准，要求作者披露使用开放数据集的记录与 AI 写作情况。更多期刊或将跟进，以重建基于公共数据库研究的可信度。

## 生统研究

1. [Nature Medicine | 每天走上几千步，推迟阿尔茨海默病数年](https://mp.weixin.qq.com/s/tta46qW5sX1rHhFJhFRiOQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251203193508.png)

这项基于哈佛衰老大脑研究（Harvard Aging Brain Study）项目，长达 14 年的随访发现：在 β-淀粉样蛋白水平较高、阿尔茨海默病风险较高的老年人中，每天适量步行（约 3000–7500 步）能显著减缓认知能力下降。每天 3000–5000 步可延缓约 3 年，5000–7500 步可延缓约 7 年，但超过 7500 步并无额外好处。而对 β-淀粉样蛋白水平较低的人群，步行量对认知能力并无明显影响。

- 论文 DOI：10.1038/s41591-025-03955-6

2. [Nature Communications | 深度学习模型赋能临床恶化预测提前17小时](https://mp.weixin.qq.com/s/yzRN6GO78T573DqxBbqcPg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251203194008.png)

这项发表在 Nature Communications 的研究开发并验证了一种基于可穿戴设备和深度学习的院内恶化预测模型。研究利用 888 名住院患者的连续生命体征数据训练 RNN，可提前最多 17 小时预测临床警报和不良事件，AUC 高达 0.89，显著优于传统 EHR 间歇性监测。该模型为早期识别非 ICU 患者恶化提供了更及时、精准的工具，具有重要的临床和应用价值。

- 论文 DOI：10.1038/s41467-025-65219-8

3. [Nature Cardiovascular Research | 运动对女性心脏健康的帮助更大](https://mp.weixin.qq.com/s/fK24a9yT2_yxU6NIqgROiA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251203194152.png)

这项发表于 Nature Cardiovascular Research 的研究显示，尽管当前运动指南对男女采用相同标准，但女性实际上从运动中获得的冠心病防护作用更强。研究发现，相比男性，女性在增加身体活动后，其冠心病发病风险和全因死亡风险下降得更显著。这提示未来应根据性别差异制定更精准的运动建议，以改善冠心病的预防和管理。

- 论文 DOI：10.1038/s44161-025-00732-z

## 博文资讯

4. [最全可视化韦恩图和集合图工具EVenn使用手册](https://mp.weixin.qq.com/s/JpYKYWtP159F71oWHo06yw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251203195633.png)

[EVenn](http://www.ehbio.com/test/venn "EVenn") 是一个集成多种韦恩图与数据交互工具的平台，支持标准化数据格式、提供高效的数据探索流程，并以友好的界面简化韦恩图、欧拉图和 UpSet 图的生成，是多组学数据分析与可视化的实用工具。相关论文发表在 iMeta 上。

- 论文 DOI：10.1002/imt2.184

5. [性能优化到极致的Python库](https://mp.weixin.qq.com/s/TkMQVQ9iZSPHRmMjDYFMeg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251203200229.png)

该推文介绍几个经过深度底层优化的高性能 Python 库，它们在保持 Python 风格与易用性的同时，带来接近毫秒级的性能提升，避免多线程、多进程等问题，也能轻松应对大规模数据与高性能计算。

## 工具

6. [Positron: the data science IDE](https://positron.posit.co/ "Positron: the data science IDE")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251203200436.png)

Positron 将探索与生产工作整合在一个免费的 AI 辅助环境中，为使用 Python 和 R 的数据科学全过程提供支持。

7. [Data Science Agent](https://labs.google.com/code/dsa?view=readme "Data Science Agent")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251203200918.png)

Google Colab推出基于Gemini的数据分析工具 Data Science Agent，该产品旨在简化和自动化常见的数据科学任务，例如预测建模、数据预处理和可视化。目标是帮助数据科学家专注于更复杂的任务和战略性问题。

## 资源

8. [可视化 | The R Graph Gallery](https://r-graph-gallery.com/ "可视化 | The R Graph Gallery")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251203201057.png)

R Graph Gallery提供了最全面的 R 语言可视化示例集，涵盖 400 多个示例，按近 50 种图表类型分类，并配有可复现代码与功能说明。平台为每种图表提供基础教程和进阶自定义指南，帮助用户在掌握核心结构的基础上，灵活定制满足自身需求的高质量可视化图形。

9. [REDCap | 高效可靠的研究管理工具](https://redcap.vumc.org/ "REDCap | 高效可靠的研究管理工具")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251203202351.png)

Research Electronic Data Capture (RED Cap) 是范德堡大学（Vanderbilt University）Paul Harris教授团队自2004年开发的一个电子数据采集（Electronic DataCapture,EDC）系统，这是一个成熟免费、安全可靠、网络化的在线临床研究和试验数据库管理程序，适用于中小型项目的电子化数据收集、储存及交换。

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
