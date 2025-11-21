# 生统爱好者周刊（第 9 期）：SAS 退出中国：时代变化超出想象

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251120234936.png)

## 本周话题：[SAS 退出中国：时代变化超出想象](https://mp.weixin.qq.com/s/E7JkROM-loihGPn6-0YMeg)

> 1976 年诞生于美国北卡州的 SAS，是全球最大的私营软件公司，连续 45 年保持盈利。在《财富》500 强前 100 强中，97 家把数据命脉交给了它；149 个国家、金融、医药、零售、制造、公共卫生等关键行业，几乎把“数据分析”写成了 SAS 的同义词。然而，2025 年 10 月最后一天，这家在华深耕 30 年的“隐形冠军”突然注销，社交媒体甚至没有来得及预热。

`@Leslie-Lu` 在 R 语言没被 FDA、EMA、国家卫健委等监管机构纳为成熟的申报递交工具方案之前，国内药企 CRO 出海还是要严重依赖 SAS。

## 生统研究

1. [Nature | 空间解析技术绘制与人类复杂性状相关细胞图谱](https://mp.weixin.qq.com/s/sJNfywlxVV4asu1pyBDruw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251120232841.png)

这篇文章提出了一种创新的生物信息学方法—gsMap，通过结合空间转录组学和GWAS数据，在空间层面上揭示了疾病相关细胞的分布及其基因表达特征 。这一方法不仅为理解复杂疾病的病理机制提供了新的工具和视角，还为精准医疗和个体化治疗strategy的开发奠定了基础 。

- 论文 DOI：10.1038/s41586-025-08757-x

2. [Nature | 超13万人大规模循环代谢标志物与全基因组关联研究](https://mp.weixin.qq.com/s/yD2deGmHK5eJebM8p9rBGQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251120233047.png)

来自芬兰奥卢大学的Minna K. Karjalainen课题组在Nature上发表了研究论文Genome-wide characterization of circulating metabolic biomarkers，该课题组极大的拓展了之前的研究队列，在该研究中通过对超过13万人的循环代谢特征与全基因组关联研究，发现了400多个独立的基因位点并确定了其中可能的因果基因，样本和参与者特征会影响遗传关联。该文章的发现对于全面表型分子数据的转化具有重要意义，同时也揭示了多种代谢途径的大量遗传多效性，为孟德尔随机化分析提供了理论指导价值。

- 论文 DOI：10.1038/s41586-024-07148-y

3. [NEJM | 药食同源，食物营养中的“暗物质”](https://mp.weixin.qq.com/s/9eEWxasrV_SQWRrINCOvbw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251120233233.png)

越来越多的证据进一步强调了饮食质量在疾病预防中的重要性，尤其是在全球早发性癌症激增的情况下，这是美国国立癌症研究所（National Cancer institute）确定的一个新兴重点研究。事实上，自20世纪90年代以来，尽管遗传性癌症发病率没有变化，但全球50岁以下成年人的癌症发病率有所上升，这一发现强调了环境和生活方式因素的影响。在过去几十年中，生命早期的饮食暴露发生了显著变化，这反映了超重、肥胖和西式饮食的趋势，甚至在儿童和青少年中也是如此。

2025年5月7日，NEJM 发表题为“Chemical Complexity of Food and Implications for Therapeutics”的文章。人类日常饮食中蕴藏着一个庞大的“营养分子库”（曾称“营养暗物质”，NDM），包含超过13.9万种生物活性分子。这些分子不仅是食物的化学组成部分，更可能是维系健康的关键“密码”，让“食药同源”从经验认知升华为科学探索的新方向。

- 论文 DOI：10.1056/NEJMra2413243

## 博文资讯

4. [为什么GPU能够加速AI学习](https://www.civo.com/blog/why-gpus-accelerate-ai-learning?utm_id=FAUN_Kala501_Link_title "为什么GPU能够加速AI学习")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251120233419.png)

推文简要介绍了对于模型训练与推理来说，gpu 相比 cpu 的优势。

5. [中山大学校内部署 Overleaf](https://mp.weixin.qq.com/s/f5pRQi1n5TJxNoK4A28ddw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251120233557.png)

中山大学校内基于 Overleaf 社区版本二次开发的在线协同 latex 编辑器，便利校内师生使用。平台支持无限数量合作者、无编译时间限制、历史记录、中文支持等功能。

## 工具

6. [GitHub CLI 手册](https://cli.github.com/manual/ "GitHub CLI 手册")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251120233712.png)

GitHub CLI 可以让开发者通过命令行与 GitHub 进行无缝的协同工作，无需离开终端就能操作 GitHub。

7. [SoS Notebook 文档](https://vatlab.github.io/sos-docs/notebook.html "SoS Notebook 文档")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251120233827.png)

SoS Notebook 是一个基于 Jupyter 的多语言工作环境，允许你在同一个笔记本中无缝使用多种编程语言。网页具体介绍了入门指南、用户手册、教程、FAQ 等内容。

8. [英飞思想家：无限白板的绘图工具](https://infi.cn/app/dashboard/ "英飞思想家：无限白板的绘图工具")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251120234133.png)

基于无线画布的在线协作空间，能够在多人协同环境中实时记录与分享灵感与想法。在无线画布中，用户可以通过多种形式进行记录与表达，包括文字、便签、图形等，还能绘制流程图、科研设计图等专业图示。

## 资源

9. [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html "Google Python Style Guide")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251120234246.png)

编程风格是指代码在命名、缩进与排版、注释与文档、错误处理、模块组织、测试与提交信息等方面的统一约定。好的风格让团队读起来“像同一人写的”，从而降低沟通成本、减少 Bug、提升维护性与可测试性。这里详细给出了 Google Python Style，值得学习。

10. [Python 统计入门](https://github.com/thomas-haslwanter/statsintro_python "Python 统计入门")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20251120234345.png)

这是 Thomas Haslwanter 教授撰写的《An Introduction to Statistics with Python》一书的配套代码库。该项目是学习如何使用 Python 进行统计学分析和数据科学的不错入门资源。

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
