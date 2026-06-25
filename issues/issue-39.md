# 生统爱好者周刊（第 39 期）：普通人用AI来看病真的更可靠吗？

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260625232955.png)

## 本周话题：[普通人用AI来看病真的更可靠吗？](https://mp.weixin.qq.com/s/tR-yvmKE_NbiNd1y0M0-wA)

模型能回答医学问题，已经不稀奇。普通人能不能把它用成正确判断，才是公众医疗助手的关键。研究结果提醒我们，医疗 AI 的下一步不只是更大模型、更高 benchmark、更长推理链。真正要补上的是问诊流程、风险分层、用户理解和真实人群测试。

## 生统研究

1. [Nature | 跨物种“死亡时钟”揭示衰老的转录组机制](https://mp.weixin.qq.com/s/0Lx3C1CtQxOkC0y2ZRKU7Q)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260625233622.png)

衰老研究最扎心的冲突是：身份证年龄相同的人，身体离“死亡风险”可能并不一样。2026年5月27日，Nature 发表《Universal transcriptomic hallmarks of mammalian ageing and mortality》，把超过11,000份转录组、25种以上组织和小鼠、大鼠、食蟹猴、人放到同一张地图里。核心结论很硬：哺乳动物衰老和死亡风险共享一套保守的转录组指纹，并且可以被可解释的“年龄/死亡时钟”量化。真正抓人的地方在这里：它不是再报一个长寿基因，而是在追问哪些分子模块正在把身体推向更高死亡风险，哪些干预又能把这个读数往回拉。

- 论文 DOI：10.1038/s41586-026-10542-3

2. [Nature | Robin：用于自动化科学发现的多智能体系统](https://mp.weixin.qq.com/s/VwWAs9F0oDEI_NUryrSr6g)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260625234627.png)

本文提出 Robin，一个把文献检索、治疗假设生成、实验建议、实验数据分析和下一轮假设更新连接起来的多智能体系统；作者将其用于干性年龄相关性黄斑变性（dAMD）药物再利用场景，报告 Robin 提出增强 RPE 细胞吞噬作用作为治疗策略，并在体外实验中验证 ripasudil 和 KL001 可增强 RPE phagocytosis，同时用 RNA-seq 分析提示 ABCA1 上调这一可能机制线索。

- 论文 DOI：10.1038/s41586-026-10652-y

## 博文资讯

3. [大脑“顿悟”机制：先重现记忆，再更新理解](https://mp.weixin.qq.com/s/XbqMFDLzNW4Iue1-ciGj-g)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260626000216.png)

研究通过让被试观看乱序电视剧发现，“啊哈时刻”往往源于对因果相关过往事件的回忆。fMRI结果显示，顿悟发生前，大脑会先重现相关记忆，随后约2秒内皮层表征发生突变，完成情境理解更新。进一步表明，大脑倾向以因果关系而非时间顺序组织记忆，使人能够在复杂叙事中快速建立连贯理解。

4. [肿瘤试验PFS和OS的矛盾](https://mp.weixin.qq.com/s/PK3fqW6rjDhU-65uCSSE4Q)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260626000856.png)

在肿瘤试验中，常用的评价终点有ORR可观缓解率、PFS、OS等。基于肿瘤负担改善程度的ORR以及PFS往往作为早期终点，来加速包括实体瘤在内的严重威胁患者生存的疾病的相关药物的上市审批。在这类药物的临床试验中，由于ORR、PFS是在OS之前进行评估，因而可以尽可能提早上市。但是这同时带来了问题，OS被视为肿瘤药物疗效和安全性评价的金标准，ORR和PFS并没有提供足够的OS的信息，来评价药物的长期疗效和安全性。事实上，已经有很多RCT的结论显示，PFS和OS之间可能会存在相当大的矛盾。

## 工具

5. [Python多面板哑铃图复现](https://mp.weixin.qq.com/s/FvzP-sjLqlNxde7hC4xo3A)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260626003249.png)

教程基于Python实现多面板哑铃图的期刊级复现，涵盖数据结构组织、配色方案设计及多子图布局控制。通过封装绘图函数，实现均值与标准差区间、差值标注及分组对比的综合展示，适用于多维度比较分析场景。该方法强调绘图流程模块化与参数化，为复杂统计结果的标准化可视化提供技术参考。

6. [引用 endnote 本身](https://supportcenter.clarivate.com/s/article/Citing-the-EndNote-program-as-a-reference?language=en_US "Citing the EndNote program as a reference")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260626004017.png)

如何在 sci 文章中引用 endnote 本身。

## 资源

7. [R语言流程整合：多组学结果可视化与统计分析的综合绘图实践](https://mp.weixin.qq.com/s/b1_Q_tnkKtMDN3s1h25xEw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260626005642.png)

教程系统整合alteration图、多火山图、fgsea富集分析、校准曲线、TMB、PCoA及网络图等11类常用可视化方法，构建从差异分析到功能解释的完整R语言流程。内容涵盖多组学数据展示与结果解读，强调图形表达在生物统计与生信分析中的关键作用，为复杂数据的标准化呈现与方法复现提供实践参考。

8. [生物统计学教学资源汇总](https://mp.weixin.qq.com/s/45JMojs-8oIAFVvCQFMj7A)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260626005925.png)

整合生物统计学核心教学内容，涵盖试验设计原则、随机化方法（完全随机、区组、拉丁方、裂区设计）及误差控制等基础模块，构建从研究设计到数据分析的系统学习框架。内容以视频形式呈现，侧重方法学理解与应用，为初学者建立规范统计思维及提升科研设计能力提供入门参考。

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
