# 生统爱好者周刊（第 16 期）：AI 看病，误诊了谁负责？

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260108225235.png)

## 本周话题：[AI 看病，误诊了谁负责？](https://mp.weixin.qq.com/s/XLtF7rSeyZ4tn7qyu8jMLw)

`@GCRPM` AI在医疗领域快速应用，既被寄望缓解“看病难”，又引发隐私、安全和伦理担忧。当前共识是“人机共担”：医生负最终复核责任，AI厂商在产品缺陷致害时依法担责。破解“技术黑箱”需技术与法律协同，通过医工结合提升算法可解释性、通过算法治理框架明确权责，让制度与法律为AI医疗保驾护航。

## 生统研究

1. [Nature Reviews Cancer | 重塑儿童及青少年癌症的遗传易感性认知](https://mp.weixin.qq.com/s/zzB_4DXirJ5BaC1_teqY7A)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260108220832.png)

尽管癌症在儿童和青少年中很少见，但它仍然是该年龄段死亡的主要原因，而遗传易感性是主要的已知风险因素。自1985年发现视网膜母细胞瘤易感性RB1病原种系变体以来，又发现了几种额外的高渗透率癌症易感基因（CPG）。尽管很少有临床上可识别的遗传疾病表现出中度的癌症表型，但负荷测试显示出低至中度的跨导率CPG。除了 CPG 中的种系致病变异，合子后体细胞嵌合体胚胎发育过程中获得的CPG致病变异越来越被认为是导致儿童和青少年患恶性肿瘤的重要因素。各种儿童和青少年癌症类型的全基因组关联研究已经确定了一些常见的低风险癌症易感性基因。尽管多基因风险评分目前在儿童和青少年中的临床应用有限，但为成人开发的多基因风险评分可以预测儿童和青少年癌症幸存者后续的癌症风险。在这篇综述中，描述了目前对儿童和青少年癌症遗传易感性的了解。患有癌症和CPG的儿童和青少年的生存率通常很低，因此需要将基因组检测更好地融入临床护理，以改善癌症预防、监测和治疗。

- 论文 DOI：10.1038/s41568-024-00775-7

2. [Nature Medicine | 睡一晚就能预测130种疾病](https://mp.weixin.qq.com/s/WnwUv6DEP1cfZUjfv1uQhg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260108221807.png)

26年1月6日，《自然·医学》发表了来自斯坦福大学科研团队的论文，研究者们依据超过65000名参与者的多导睡眠图（PSG）数据，建立了一个多模态睡眠模型SleepFM，仅凭一晚的睡眠数据，SleepFM就能以至少0.75的C指数预测多达130种健康问题的风险，包括全因死亡（0.84）、痴呆（0.85）、心肌梗死（0.81）、心力衰竭（0.80）、慢性肾病（0.79）、中风（0.78）和心房颤动（0.78）。值得注意的是，SleepFM训练时采用了留一模态对比学习（Leave‑One‑Out Contrastive Learning），不要求所有模态同时存在，可在数据缺失时让模型保持鲁棒性，从而适应不同的PSG设备、采样方式和单位带来的数据变化，给模型提供更好的泛用性。本研究再次强调了睡眠在整体健康中的重要地位。

- 论文 DOI：10.1038/s41591-025-04133-4

3. [NC | 生成式AI在超低数据范围内实现医学图像分割](https://mp.weixin.qq.com/s/66F1cjjGaE_i6MfU6r93Ew)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260108222134.png)

医学图像分割在临床诊断和治疗中具有重要价值，但现有深度学习分割方法高度依赖大量高质量标注数据。在实际应用中，由于医学图像标注成本高、专业性强，许多任务只能获得极少量标注样本，导致模型在超低数据条件下难以有效训练，分割性能明显受限。如何在标注数据极其有限的情况下仍然实现可靠的医学图像分割，是该领域亟待解决的问题。本研究提出了一种面向超低标注数据条件的医学图像分割框架，其核心思想是将生成式模型与分割模型进行联合优化，而不是将数据生成作为独立的预处理步骤。通过在训练过程中引入生成模型，并利用分割模型的性能反馈不断调整生成策略，使生成的数据更加符合分割任务的实际需求，从而在极少真实标注样本的情况下提升模型整体分割性能。

- 论文 DOI：10.1038/s41467-025-61754-6

## 博文资讯

4. [CHEST | 利用目标试验仿真估计异质性治疗效应](https://mp.weixin.qq.com/s/u9__mA9CZ951cayesLW_9w)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260108221446.png)

本文介绍在目标试验仿真框架下，利用因果机器学习在真实世界数据中估计CATE/HTE的方法，强调交叉验证与交叉拟合、Qini与校准等评估及敏感性分析，并给出分步检查清单，提醒注意混杂与时变混杂等局限。

- 论文 DOI：10.1016/j.chest.2025.05.028

5. [身体：我想动！大脑：不，你不想！](https://mp.weixin.qq.com/s/Kfn-oL5rOYgEihvsG2pT4Q)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260108222340.png)

研究人员和临床医生一直困于如何定义、衡量和治疗认知疲劳——这些主要依赖人们自述他们感受到的疲劳程度。而如今，不同领域的科学家正在运用创新性实验方法和生物标志物，探究认知疲劳的代谢根源和后果。

## 工具

6. [Python | 主图+边缘图 (蓝粉系配色方案)](https://mp.weixin.qq.com/s/HPBYwg8nBpKh79W4dHellw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260108222807.png)

汇总了一些主图+边缘图绘制的 python 代码。

7. [10种好看的特色热图绘制方法](https://mp.weixin.qq.com/s/YtXPMQLUaxzhaDT-hKP-_Q)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260108223022.png)

热图是通过颜色梯度变化直观呈现数据高低的图表，本文整理了很多漂亮的特色热图绘制方法。

8. [GNU Awk 用户指南](https://www.gnu.org/software/gawk/manual/gawk.html#Options "GNU Awk 用户指南")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260108223258.png)

这是GAWK 的第 5.3 版：《有效的 AWK 编程：GNU Awk 用户指南》，适用于 GNU AWK 的 5.3.1（或更高版本）实现。文档详细介绍了 awk 的具体使用。

## 资源

9. [医学电子资源概览与利用](https://mp.weixin.qq.com/s/LDAO45I_JijwyeUKvzZhXw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260108223856.png)

深圳大学城图书馆为医务工作者与医学生提供多元医学信息服务，在Springer Nature、Science、EBSCO、ProQuest、知网、万方等平台基础上，引入多种重要医学数据库，帮助及时获取全球医学前沿与研究热点，支持临床与科研实践。

10. [Springer生物医学与生命科学期刊推荐](https://mp.weixin.qq.com/s/v4_JQhJYok2Q-HohPQjaWQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260108224044.png)

Springer生物医学与生命科学电子期刊在相关领域内具有较高的科研影响力，始终坚持发现并发表高质量、前沿性的研究成果，涵盖从基础理论到应用技术的广泛主题。该合集收录的期刊获得了广泛的认可和使用，致力于为科研人员、高校、研究机构及企业研发团队提供有价值的参考资源。

11. [R for Data Science (2e)](https://r4ds.hadley.nz/ "R for Data Science (2e)")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260108224502.png)

R4DS 在第一版的基础上增加了更多最新的内容，适合对 R 进行查漏补缺使用。目前是英文网站上持续更新。

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
