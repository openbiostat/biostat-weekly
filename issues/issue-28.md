# 生统爱好者周刊（第 28 期）：Nature | 我和我的博士生导师的关系变得很糟糕——我该怎么办？

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260409192358.png)

## 本周话题：[Nature | 我和我的博士生导师的关系变得很糟糕——我该怎么办？](https://mp.weixin.qq.com/s/Zx7w-u2mYIUHs-bNLjkm6w)

`@kirihsia` 面对导师“怪物式”的压迫，Nature 的回复揭示了一个扎心的现实：博士生的幸福感往往并不取决于实验结果，而取决于导师的底线。面对导师的毒性压迫，首要任务是实现心理切割，坚信人格尊严远重于一纸文凭。建议在通过详细计划书进行“防御性沟通”的同时，务必留存所有交流证据，并积极寻求校方调解或更换导师的退路。

## 生统研究

1. [Nature Biomedical Engineering | 用于乳腺超声图像分析的基础生成模型](https://mp.weixin.qq.com/s/XQybKRkkOcIBsF5jjt9zeA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260409192643.png)

北京大学与医科院肿瘤医院团队开发出首个乳腺超声基础生成模型 BUSGen，通过 350 万张大规模影像预训练，有效解决了医疗AI研发中高质量标注数据稀缺的难题。该模型生成的合成数据不仅能显著提升癌症筛查、早期诊断及预后预测的准确性，在导管原位癌等疑难诊断上的表现甚至超越了资深放射科医生。研究证实，这种合成数据具备极强的可扩展性与泛化能力，能有效规避数据采集偏差并保护患者隐私，为医疗影像AI的研究与临床转化开辟了高效率、安全的新路径。

- 论文 DOI：10.1038/s41551-026-01639-1

2. [Nature Machine Intelligence | 基于对170万个体数据训练，实现跨场景、跨设备的心脏健康评估的多模态基础模型](https://mp.weixin.qq.com/s/j5y0F6WyTFtuJqBsHTTjWA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260409192855.png)

牛津大学等机构的研究团队开发了首个心脏感知基础模型 CSFM，通过对 170 万人规模的异构心电图（ECG）、脉搏波（PPG）及临床文本进行生成式预训练，成功打破了心脏健康监测中不同设备、信号和场景之间的数据问题。该模型展现了极强的“通用性”与“设备无关性”，不仅在心血管疾病诊断和生命体征测量等五大类任务中超越了传统专用模型，还能在仅有单导联输入的情况下推断缺失的空间信息，甚至实现从脉搏波到心电图的跨模态波形重建。CSFM 的诞生标志着心脏监测领域进入了“通用智能时代”，其强大的特征提取能力和即插即用的灵活性，将极大地降低医疗AI的开发门槛，为全球范围内普及公平、精准的心血管健康管理提供了可能。

- 论文 DOI：10.1038/s42256-026-01180-5

## 博文资讯

3. [英伟达发布《2026年医疗健康与生命科学领域AI应用现状报告》](https://mp.weixin.qq.com/s/Jgw_H8iNGOw84JmOS6Bk0w)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260409193234.png)

NVIDIA发布《State of AI in Healthcare and Life Sciences: 2026 Trends》（2026年医疗健康与生命科学领域AI应用现状报告），报告通过对全球600余位行业专业人士的调研，全面呈现了医疗健康与生命科学行业的AI应用全景，解读了行业核心技术趋势、商业落地成果与未来发展方向。

4. [因果推断：背景与潜在结果框架](https://mp.weixin.qq.com/s/pmHzMrPR51kQ7embgZAJeA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260409193526.png)

因果推断中的潜在结果框架（Potential Outcomes Framework），又称 Neyman–Rubin 因果模型，是现代因果推断的重要理论基础。该框架以反事实思维为核心，通过为每个研究单位定义在不同处理条件下可能出现的潜在结果，将因果效应形式化为这些潜在结果之间的差异。在这一框架下，不同目标人群对应不同的因果估计量，如总体平均处理效应（ATE）、处理组平均处理效应（ATT）等，同时需要依赖若干关键假设来识别因果效应，包括稳定单位处理值假设（SUTVA）、无混杂性（可忽略性）以及重叠性条件等。潜在结果框架为理解随机对照试验和观察性研究中的因果效应估计提供了统一的理论基础，也是倾向得分、匹配、工具变量等多种因果推断方法的理论出发点。

## 工具

5. [从AutoFigure到AutoFigure-Edit：AI论文绘图可以编辑](https://mp.weixin.qq.com/s/6CzFVWr9ariTCM_p9pWi_g)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260409194339.png)

西湖大学团队开源的 AutoFigure-Edit 是一款首创的 AI 论文矢量绘图工具，它打破了传统 AI 生图“不可编辑”的局限，能够将长篇学术文本直接转化为可直接拖拽、改字、换色的 SVG 矢量图。该系统利用 SAM3 技术智能分割图像组件，并支持通过上传参考图实现一键风格迁移（如适配 Nature 风格），其核心代码与环境已在 GitHub（[ResearAI/AutoFigure-Edit](https://github.com/ResearAI/AutoFigure-Edit "ResearAI/AutoFigure-Edit")）完全开源，并提供在线体验网站（[deepscientist.cc](https://deepscientist.cc/ "deepscientist.cc")）。

6. [Zread CLI | 快速理解代码架构](https://mp.weixin.qq.com/s/4UWurhgVGWvNrji-nT5vpw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260409194433.png)

Zread CLI 是由智谱 AI 推出的一款强大的本地代码仓库深度解读工具，专为解决开发者面对庞大陌生源码（如数十万行代码的 Claude Code）时“看不懂、理不顺”的痛点。只需在项目目录下执行简单的 zread 命令，该工具便能自动分析代码结构、逻辑依赖与系统架构，并生成一份图文并茂、可交互的结构化 Wiki 说明书。相比网页版工具，它支持完全本地化运行，能够无缝处理公司私有项目或个人非开源代码，能为 Cursor 等 AI 编程工具提供精准的项目上下文，极大提升了研发效率与代码理解深度。

## 资源

7. [全球遴选150名本科生，2026西湖大学生科“大师课”报名开启](https://mp.weixin.qq.com/s/jvUALEdZuS3UBZ2dUY6PYQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260409194554.png)

近日，2026西湖大学生命科学国际暑期学校已开放申请，将从全球申请者中遴选150名优秀本科生，与国际顶尖学者共同探索生命科学的前沿奥秘。一年一期的“大师课”，也是研究型大学里的研究型夏校，今年已到第四期。

8. [UKBAnalytica1.0 | 告别重复造轮子](https://mp.weixin.qq.com/s/jhjR4d4W2b08ajNPJcf6Bw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260409194733.png)

UKBAnalytica 1.0 是一款专为UK Biobank设计的 R 语言全流程分析工具包，它针对 RAP 平台数据处理中的字段晦涩、疾病定义复杂及生存时间计算繁琐等痛点，提供了一套从数据下载、标准化预处理、自动提取 20 余种预定义疾病表型，到批量 Cox/Logistic 回归及机器学习（支持 SHAP 解释）的一站式解决方案。

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
