# 生统爱好者周刊（第 15 期）：榜单套路大赏：从大学排名到高被引学者排名

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260101231749.png)

## 本周话题：[榜单套路大赏：从大学排名到高被引学者排名](https://mp.weixin.qq.com/s/pCBReuD0Zgk_fD-MGuyJCQ)

`@kirihsia` 大学排名表面上是衡量学术水平的客观工具，实质却是一套放大高校与学者焦虑、将声誉转化为流量与利益的注意力生意。它通过看似中立的指标体系，悄然重塑高校的行为逻辑，甚至侵蚀学术共同体的价值取向。真正值得被严肃对待的不是排名高低，而是大学是否守住学术诚信，并持续为社会创造长期而真实的公共价值。

## 生统研究

1. [Nature Medicine | 个人健康大语言模型：睡眠与健身指导的新突破](https://mp.weixin.qq.com/s/mV3YVV4YhGv9YVO9h4Po2Q)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260101231919.png)

随着可穿戴设备的普及，海量健康数据正在被持续记录，但如何将这些数据转化为真正有用、可执行的个性化建议一直是难题。近日，Google Research / Google DeepMind 联合睡眠医学、运动科学与多模态人工智能等领域的研究人员，提出了个人健康大语言模型 PH-LLM。该模型基于 Google Gemini Ultra 1.0，通过两阶段训练同时理解文本与可穿戴传感器数据，可为用户提供个性化的睡眠与健身指导。研究结果显示，PH-LLM 在睡眠医学和健身专业测试中的表现已接近甚至超过人类专家，在 857 个真实世界案例评估中，其生成的睡眠和健身建议与专家水平几乎无差异；在预测自我报告睡眠质量方面，模型性能也与专业判别模型相当。

- 论文 DOI：10.1038/s41591-025-03888-0

2. [Nature Machine Intelligence | 多模态扩散模型实现心血管信号实时全面监测](https://mp.weixin.qq.com/s/zNvVzYisKB5SEcPiNPioXw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260101232122.png)

针对可穿戴心血管信号“易获取但质量不稳、高质量却难长期采集”的现实困境，清华大学朱军团队提出了统一多模态生成框架 UniCardio，并于 2025 年 12 月发表于 Nature Machine Intelligence。该方法将 PPG、ECG 和血压等不同心血管信号视为同一生理系统的多重观测，首次在单一扩散 Transformer 模型中同时实现信号去噪、缺失插补和跨模态生成。通过任务特定注意力机制与持续学习训练范式，UniCardio 能稳定覆盖多模态、多任务和多条件组合，并充分利用不同信号之间的互补信息。结果表明该模型在多项生成任务上优于或媲美任务特定方法，且生成信号在异常检测、心率与血压估计等下游任务中具备接近真实信号的实用价值与临床可解释性。

- 论文 DOI：10.1038/s42256-025-01147-y

3. [Nature Cardiovascular Research | 多模态AI精准预测“心脏杀手”](https://mp.weixin.qq.com/s/U2-CLDo4sDh5kVzREfGxsA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260101232249.png)

这项发表于 Nature Cardiovascular Research 的研究聚焦于肥厚型心肌病（HCM）患者最棘手的临床难题，如何更精准地预测心源性猝死风险、避免ICD“该装的不装、不该装的白装”。约翰霍普金斯大学团队提出了多模态AI模型 MAARS，首次将电子健康记录、心脏影像报告以及原始LGE-CMR磁共振图像在Transformer框架下进行中期融合，从“综合题”而非“单选题”的角度理解患者风险。结果显示，MAARS在内外部独立队列中的AUROC显著优于现行三大临床指南，且在不同年龄和性别亚组中表现稳定可靠。更重要的是，模型通过注意力热图揭示了与心律失常高度相关的心肌纤维化等关键病理特征，使AI不再只是“黑盒预测器”，而是成为医生可理解、可信赖的风险评估助手。

- 论文 DOI：10.1038/s44161-025-00679-1

## 博文资讯

4. [国自然基金项目申请书改版](https://mp.weixin.qq.com/s/GGNmWOSgbyjA1iW4EjAObA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260101232542.png)

自然科学基金委积极响应学术界的关切和诉求，在2026年启动申请书“瘦身提质”行动。我们将对申请量最大、覆盖面最广的两类项目——面上项目和青年科学基金项目（C类）的申请书提纲进行优化调整。调整后的申请书正文包括立项依据、研究内容及研究基础三部分。在立项依据部分，只需要说清楚“为什么要开展此项研究，研究的价值何在”；研究内容部分不再预设提纲限制，申请人可以根据自己的研究思路和研究工作的自身逻辑自主撰写；研究基础部分主要展示前期的工作积累。两类项目的申请书正文篇幅原则上不超过30页，鼓励简洁表达。

5. [2025数字医疗年度创新白皮书：AI落地应用成主旋律，脑机接口进入临床试验高峰](https://mp.weixin.qq.com/s/CxYkt-iuPyQjI5vdmU6lkQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260101232642.png)

2025数字医疗年度创新白皮书发布。白皮书基于对十余家数字医疗创新企业、头部投资机构及资深行业专家的深度调研与访谈，从行业动态与企业实践双维度切入，系统梳理我国医疗人工智能、脑机接口等数字医疗各细分领域的发展现状，全面剖析2025年行业核心特征与关键突破，前瞻性展望2026年行业发展趋势，旨在为行业参与者提供有价值的参考与启示。

6. [The BMJ | CONSORT 2025声明：随机试验报告指南更新](https://mp.weixin.qq.com/s/RhAH2iZDsvNBJuL53rs8Lw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260101232910.png)

CONSORT 2025 声明：随机试验报告指南，旨在提升临床研究透明度、完整性和可重复性。该指南由国际方法学专家共同修订，强化了对试验设计、实施、分析与结果报告的关键要求，为研究人员、期刊编辑和同行评审提供权威参考，推动循证医学高质量发展。

- 论文 DOI：10.1136/bmj-2024-081123

## 工具

7. [Nano-Banana Pro 论文绘图最全教程发布](https://mp.weixin.qq.com/s/IG8cITKAESi-vomyQiobZg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260101233033.png)

该教程采用一套标准化的工作流，将复杂的绘图任务拆解为 “逻辑构建（The Architect）” 与 “视觉渲染（The Renderer）” 两个独立且互补的环节。通过利用 LLM 强大的逻辑推理能力来指导绘图模型的像素生成能力，能够产出符合 CVPR/NeurIPS 等顶刊标准的学术插图。

8. [生物信息学中常用的开源R包及其GitHub地址](https://mp.weixin.qq.com/s/A_eoEl3101bqVOeDtWb75g)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260102153307.png)

生物信息学中R包，包括差异表达分析，序列和基因组分析，数据操作和可视化，单细胞分析，通路和富集分析，数据结构与IO，统计和机器学习，网络分析，变异分析，质谱和蛋白质组学。

9. [UCSC LiftOver工具对不同版本的基因组坐标进行转换](https://mp.weixin.qq.com/s/kCLfC6Mp50c3uWuthQrMJg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260101233259.png)

UCSC 分别提供了网页版和Linux命令行两个版本的LiftOver工具。网页版工具的输入文件大小限制为500M，当遇到比较大的文件时，需要使用Linux命令行版本进行转换。

## 资源

10. [使用常规收集卫生数据开展观察性研究的报告规范-RECORD 规范](https://mp.weixin.qq.com/s/7rv3KYnk9w4nUXyZbyOZBw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260101233446.png)

RECORD 规范是 STROBE 规范扩展版，其可用来提出针对使用常规收集卫生数据开展观察性研究有关报告的条件要求。RECORD 清单扩展了包括题目、摘要、前言、方法、结果、讨论和其他内容等需要在此类研究报告中包含的 13 个条目内容。

11. [抛弃碎片化，系统生信入门之python：在线电子书籍推荐](https://mp.weixin.qq.com/s/rKwTs1ZMigLfr9mWIxgMeA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260101233625.png)

抛弃碎片化，系统生信入门之python版本的推荐。这本中文 Python 在线电子书不仅支持 PDF 下载打印，还配套提供可直接运行的 ipynb 代码，非常适合用 VS Code 或 Jupyter Notebook 上手学习。

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
