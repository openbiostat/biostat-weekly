# 生统爱好者周刊（第 48 期）：2026年国家自然科学基金评审结果公布

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub:
[openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交
issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260827211019.png)

## 本周话题：[2026年国家自然科学基金评审结果公布](https://mp.weixin.qq.com/s/_3Fb3AEQJXPwomNinL7LTA)

2026年国家自然科学基金集中接收申请项目评审结果于8月26日正式公布，共受理申请469429项，批准资助10类项目共计69563项。在中央财政大力支持下，青年科学基金项目（C类）和面上项目资助规模显著增加，增幅分别达50.1%和14.8%，体现了对原创性研究和青年人才培养的倾斜。文章同时分析了2021-2025年各地区面上项目和青年项目的资助经费分布，并介绍了基金委持续深化改革、构建"青年学生项目---青年科学基金项目---团队类项目"资助体系、破除人才项目"帽子化"倾向等系列举措，强调基础研究在建设科技强国中的根本性作用。

## 生统研究

1. [Nature Medicine \|
   面向睡眠与健身教练的个人健康大语言模型](https://mp.weixin.qq.com/s/cP3vzvRvqV4JMVn9BB30zQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260827211224.png)

研究介绍了个人健康大语言模型PH-LLM，该模型基于Gemini Ultra
1.0微调，旨在处理长达30天的Fitbit可穿戴设备汇总数据，以生成睡眠与健身训练建议。研究采用三层评价体系：专业知识题库（99道体能题）、专家评分的真实/合成案例（350个健身案例）以及大规模主观状态预测（4163名参与者）。三项关键发现是：健身领域微调未在知识题上产生增量（与基础模型同为88%准确率）；在案例评分中，PH-LLM与人类专家整体无显著差异，但在"训练负荷"环节出现可追溯的性能退步；用于预测16项主观睡眠状态的"四个软令牌"适配器虽优于文本提示，但其预测准确性并未超越基于相同汇总特征的传统逻辑回归。

- 论文 DOI：10.1038/s41591-025-03888-0

2. [BMJ \|
   真实世界研究能复刻RCT吗？](https://mp.weixin.qq.com/s/nLqm2IjdL4Yfj265aKdeJA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260827211455.png)

这项BMJ系统综述与Meta分析纳入50项研究、107组目标试验模拟（TTE）与随机对照试验（RCT）的正面对照，发现总体Pearson相关系数仅为0.59（中等相关），标准化差异一致率79%，总体ROR为0.96，平均无明显系统偏差。当模拟设计更贴近RCT（63组满足近似模拟条件）时，一致性显著提升至r=0.83、一致率87%。研究强调TTE的可靠性并不来自观察性数据的"自动随机化"，而是取决于能否真正复刻目标试验的基线人群、时间零点、对照策略、结局和数据结构，因此设计良好的TTE可接近RCT并作为补充证据，但不能替代RCT。

- 论文 DOI：10.1136/bmj-2025-086810

## 博文资讯

3. [女性初级保健医生的薪酬悖论](https://mp.weixin.qq.com/s/BWSZqfMTZ026CTVIn-hb4w)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260827211754.png)

研究利用全国性的全支付方索赔数据和电子健康档案数据，系统性地调查了初级保健领域中的性别薪酬差距。研究发现，尽管女性初级保健医生的工作天数更少、接诊量更少、收入更低，但她们花在每位患者身上的直接照护时间反而更多，且单次就诊记录更多诊断和医嘱。这表明薪酬差距并非由工作时间或接诊量减少所致，而是源于女性医生在相同时间内提供了更细致的照护，却未能获得相应的收入回报，揭示了基于按服务收费的支付体系下性别平等面临的结构性挑战。

4. [AI陪伴正在如何重塑儿童青少年的关系学习](https://mp.weixin.qq.com/s/Qs8GN1krJnDP4ZQLEDWY5A)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260827211857.png)

随着交互式AI（如ChatGPT、豆包等）在青少年群体中的普及，其角色已从纯粹的"工具"演变为情感倾诉对象甚至"朋友"，对儿童青少年的关系学习能力产生深远影响。最新发表在《Lancet
Child & Adolescent
Health》的研究指出，AI陪伴产品因复刻了安全依恋的"可及性"与"回应性"而令青少年依赖，其影响具有双重性：一方面可作为"社交脚手架"缓解孤独感并促进社交技巧迁移，另一方面则通过"关系替代"和"适应不良的关系学习"两条路径增加社交退缩与抑郁风险。文章强调，问题的核心并非禁止使用AI，而是引导其成为真实人际关系的"辅助"而非"替代"，并针对不同年龄段为家长提供了从开放对话、共同使用到培养AI素养的五条实操建议。

## 工具

5. [Claude 官方：将 Session
   用到极致](https://mp.weixin.qq.com/s/6uIvqA-osZJC7ED33UjG_g)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260827212006.png)

基于 Claude 官方发布的技术文章，系统阐述了如何优化 Claude Code 中 Session
的使用效率以最大化 token
价值。token成本由模型、输入输出类型及缓存命中决定。用/clear分隔任务、@-mention附加文件、以quiet参数控噪、用Subagent隔离高噪声任务，避开四个高成本陷阱。

6. [archify：让 AI
   画图不再翻车，输出还能验证](https://mp.weixin.qq.com/s/StkRTjPYxHtV6KKBTymB-A)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260827212133.png)

本文介绍了开源项目 archify，这是一个面向 AI 编程代理（如 Cursor、Claude Code）的
Agent skill，旨在解决 AI
生成架构图时"杂乱无章、连接错误"的痛点。其核心创新在于：将 AI
生成的图转换为类型化 JSON
中间表示，并在交付前通过确定性验证逻辑（检查组件重叠、标签超宽、元素越界等）确保输出正确，最终生成自包含、可交互、带动效的
HTML
文件。该工具覆盖架构图、工作流、时序图、数据流和生命周期图五种类型，支持暗/亮主题切换、节点路径追踪、故事模式演示及架构改动对比，并提供机器可读的
JSON 修复回执，实现"生成可验证、交付可回溯"的闭环流程。

## 资源

7. [柳叶刀临床资源中心------一站式获取前沿研究与教育资源](https://mp.weixin.qq.com/s/phJcwzBGRtYKh_IwlHCFyw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260827212238.png)

柳叶刀临床资源中心作为一站式平台，汇集《柳叶刀》系列期刊的前沿临床研究，帮助临床工作者深入掌握诊断、治疗及照护领域的最新进展。该中心通过临床医学专题、临床知识库等多种资源类型，提供研讨会、综述、临床病例和信息图等深度学习内容，持续支持专业成长与临床实践。同时，专辑、委员会重大报告及会议同步文章进一步挖掘前沿理念，推动临床决策优化和卫生政策发展。

8. [《柳叶刀》系列期刊影响因子全览](https://mp.weixin.qq.com/s/1omTGtyWKEDgMkzrkBLl_w)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260827212437.png)

2026年是《柳叶刀》系列期刊历史表现最佳的一年，其旗舰刊《柳叶刀》（The
Lancet）以109.0的影响因子和92.4的CiteScore稳居全球综合医学期刊榜首。旗下29本系列期刊中，24本拥有影响因子，其中5本在JCR学科领域排名第一，18本影响因子实现增长。

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

同时，本周刊同步支持 [RSS
订阅](https://leslie-lu.github.io/biostat_weekly_rss.xml "生统爱好者周刊 RSS 订阅")；本周刊同名中文播客现已正式在[苹果播客（Apple
Podcasts）](https://podcasts.apple.com/cn/podcast/%E7%94%9F%E7%BB%9F%E7%88%B1%E5%A5%BD%E8%80%85%E5%91%A8%E5%88%8A/id1868591486?l=en-GB "Apple Podcasts 订阅")和[小宇宙](https://www.xiaoyuzhoufm.com/podcast/69650caa93e769238063a05e "小宇宙订阅")平台上线，搜索`生统爱好者周刊`即可订阅收听。该播客内容基于本周刊公开内容制作，相关学术论文链接及原始资讯请查阅本周刊文字版。

（完）
