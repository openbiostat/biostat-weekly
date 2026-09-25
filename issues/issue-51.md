# 生统爱好者周刊（第 51 期）：今天你也Burnout了吗？

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![20260924195420](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260924195420.png)

## 本周话题：[今天你也Burnout了吗？](https://mp.weixin.qq.com/s/s93OJIh-Jr2n4SoL0P3cdQ)

倦怠不仅仅是个人问题，它是工作在压力环境中的结果。没有人能够在长时间的高压下持续工作，而不付出情感代价。要真正解决倦怠问题，必须在组织和文化层面进行改变。

## 生统研究

1. [JAMA Psychiatry | 相同揭盲条件下，迷幻疗法与抗抑郁药治疗抑郁症的比较](https://mp.weixin.qq.com/s/w3Z4gyJbh0OQKlpoY6yAMw?scene=1&click_id=1210476017)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/Screenshot2026-09-24.png)

致幻剂辅助心理治疗（Psychedelic‑Assisted Therapy，PAT，如裸盖菇素、DMT / 死藤水等）近年在抑郁症领域热度极高。现有临床试验中，致幻剂相比安慰剂能产生非常大的症状改善效应（HAMD‑17 量表约 7.3 分差值），而传统抗抑郁药对比安慰剂仅约 2.4 分差值，这让很多人认为致幻剂是抑郁症革命性新疗法。

但学界一直存在重大方法学质疑：致幻剂会带来强烈主观精神体验，临床试验中即便设计双盲，90‑95% 受试者可以猜出自己分到了活性药物组，发生 “功能性破盲”；反观传统抗抑郁药盲法试验，受试者猜中分组概率仅约 60%。在等同破盲的试验条件下，致幻剂辅助治疗的抑郁改善效果并不优于开放标签传统抗抑郁药。致幻剂试验的功能性破盲，极大影响了我们对其疗效大小的判断。

- 论文 DOI：10.1001/jamapsychiatry.2025.4809

2. [Lancet Planetary Health | 清洁空气政策干预与人群心血管疾病风险之间的关联](https://mp.weixin.qq.com/s/vLNfOjGD7Wc1dAj2xsA-Mw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260924200237.png)

2013年中国《清洁空气法》正式落地实施，国内整体空气质量得到显著改善。但学界始终缺乏个体层面的精准证据，清洁空气政策干预与人群心血管疾病风险之间的关联，一直没有明确结论。2026年9月1日，北大学者联合多机构，在顶刊 The Lancet Planetary Health 在线发表最新研究。依托国内大型队列中国慢性病前瞻性研究项目（China Kadoorie Biobank, CKB），采用准实验研究设计，搭配双重差分模型开展因果推断，为无RCT场景下的公共政策健康效应评估，提供了高质量的研究范式。

- 论文 DOI：10.1016/j.lanplh.2026.101513

## 博文资讯

3. [抑郁症最新国内外指南及专家共识总结综述和最新进展](https://mp.weixin.qq.com/s/a2iZTddJpbzAuPXnuT-rhA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/Screenshot2026-09-2420.05.00.png)

系统汇总了2022–2026年国内外抑郁症临床指南与专家共识，涵盖筛查诊断、药物治疗、心理治疗、特殊人群及共病管理，并梳理rTMS、氯胺酮、数字疗法、AI和精准精神病学等最新进展，适合作为抑郁症循证诊疗与研究的指南索引。

4. [人工智能何以理解语言意义](https://mp.weixin.qq.com/s/6AP_y5XieYhdwwDDU_9ZFA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260924200935.png)

对于医学尤其是精神医学AI而言，患者的症状描述、情绪状态和社会行为高度依赖个体经验与临床情境，因此单纯识别文本模式并不等同于理解疾病。

## 工具

5. [ZotFlow 插件](https://github.com/duanxianpi/ZotFlow "ZotFlow 插件")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260924201104.png)

ZotFlow 是一款用于 Obsidian 的 Zotero 集成插件，将文献管理、PDF/EPUB 阅读批注、文献笔记与引用功能整合到同一工作区。支持 Zotero 与 Obsidian 双向同步、模板化生成文献笔记、批注回传、多格式引用及库内文献检索，也可直接批注未纳入 Zotero 的文件。插件采用离线优先设计，无遥测和追踪，适合构建一体化、可复现的科研文献阅读与知识管理工作流。

6. [dynamicLM R包](https://github.com/thehanlab/dynamicLM "dynamicLM R包")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260924201246.png)

基于 landmark supermodel 方法，可利用随时间更新的协变量进行个体化风险预测。支持删失数据、竞争风险及时间依赖效应，并提供 LASSO、Ridge 等正则化方法，涵盖模型拟合、风险预测、校准、AUC/Brier 评分、Bootstrap、外部验证及个体风险轨迹可视化。

## 资源

7. [官网书单里，生物医学研究者最该读的那些免费书](https://mp.weixin.qq.com/s/w294M9kZwDU4CPVq17ce4A)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/Screenshot2026-09-24at20.16.07.png)

系统梳理适合生物医学研究者的免费R学习资源，涵盖R语言入门、统计建模、生物信息学、临床预测、Meta分析、缺失值、贝叶斯与时空分析，以及数据可视化和可重复研究。文章还根据不同科研场景给出选书建议，帮助研究者从“会用R”逐步建立完整、可复现的科研分析工具箱。

8. [从降糖到全身代谢革命：GLP-1类药物全景科普](https://mp.weixin.qq.com/s/Rm18idkBP1czeJqHH4AiPg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260924201903.png)

从2005年第一个GLP-1类药物（艾塞那肽）上市，到如今成为"代谢全能选手"，GLP-1类药物用20年时间完成了从降糖药到全身代谢调节器的蜕变。

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
