# 生统爱好者周刊（第 38 期）：医疗数字孪生的六重误判与真相

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260618214654.png)

## 本周话题：[医疗数字孪生的六重误判与真相](https://mp.weixin.qq.com/s/QvLpQNSp0m7ZOia92lPAbw)

当前行业对医疗数字孪生存在多种常见误解，例如将其简单理解为3D可视化系统、一次性交付的技术项目、基于大模型的对话工具或仅是数据的简单堆叠等。文章强调，真正具有临床价值的医疗数字孪生并非技术展示，而是能够在临床决策支持、护理路径优化及智慧医院建设中提供可验证、可持续运行的计算模型，并提出了最小可用数字孪生（MVDT）、场景选择和 ModelOps 运营体系等实践建议，为评估和实施“AI+医疗数字孪生”项目提供了可操作的参考框架。

## 生统研究

1. [NEJM | 针对罕见病的临床级长读长DNA检测方法](https://mp.weixin.qq.com/s/nx9BcppB1RpBT1vg1XHp-w)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260618223431.png)

荷兰拉德堡德大学医学中心研究人员报道了一种针对罕见病的临床级长读长DNA检测方法，该方法可通过单次分析替代其他15种基因检测，在更短时间内提供比标准诊断更为全面的结果，提高了成功获得诊断的患者数量。研究显示，长读长基因组测序作为罕见病的一线诊断检测方法，与短读长测序的诊断效能相当，能改善结果解读并优化工作流程，缩短了整体诊断时间。

- 论文 DOI：10.1056/NEJMc2602512

2. [NC | 48万中国人基因揭秘：几乎人人携带药物风险变异，但多数人无需过度担忧](https://mp.weixin.qq.com/s/lQZQn-Yn4YbQXjeQVVMvFw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260618223622.png)

本研究基于台湾精准医学计划（TPMI）中486,956名汉族参与者的遗传和临床数据，开展了一项大型回顾性分析，系统评估了药物基因组学（PGx）风险变异在中国汉族人群中的临床影响。通过整合遗传药理学原理，PGx引导的治疗策略有望优化药物选择与剂量，从而显著改善治疗结局并降低不良事件风险。研究核心目标是为PGx的临床应用提供实证依据。

- 论文 DOI：10.1038/s41467-025-61644-x

## 博文资讯

3. [在预训练阶段“动手术”：让模型从源头学不会某些能力](https://mp.weixin.qq.com/s/6iB0DtZNhJPvdIyT9Im4hw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260618223748.png)

研究提出，将模型能力的“塑形”前移到预训练阶段，通过对训练数据进行Token级过滤，从源头限制模型习得某些不希望具备的能力（如医学知识），而非依赖后期对齐或安全补丁。相比传统的文档级过滤，Token级方法更精细，在实现类似“能力削弱”效果的同时，对其他正常能力的损伤更小，呈现出“帕累托改进”。这一思路为AI安全提供了新路径：不只是约束模型“说什么”，而是决定模型“能学到什么”。不过，这种方法也带来权衡问题，例如知识完整性下降及潜在的泛化能力影响。

4. [全球四大生物银行深度横评：爱沙尼亚、UK Biobank、FinnGen、All of Us，谁才是精准医学的未来？](https://mp.weixin.qq.com/s/ztpjD2UCnaMgTpL9JpbUlQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260618224212.png)

当基因数据与健康档案在大规模人群中汇聚，精准医学的时代真正开启。本文带你深度了解全球最具影响力的四大生物银行，看懂它们的异同，也看清科学的边界。

5. [繁忙的临床医生，如何快速高效的阅读一项临床试验？](https://mp.weixin.qq.com/s/bhE7nShAUHHD7tVldaWd7g)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260618224318.png)

近期，JCO Oncology Practice杂志围绕“如何深入剖析一项临床试验”，从一名临床医生的角度，进行了系统阐述。

## 工具

6. [不止一条轨迹：多元轨迹模型怎么同时看多个结局](https://mp.weixin.qq.com/s/RLdcsCrCer8A9fwqNHXz-g)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260618224651.png)

多元轨迹模型将多个指标放在同一时间框架下，刻画其联合变化模式，并识别具有相似发展路径的潜在人群。文章结合R实现与示例数据，展示从建模到结果解读的基本流程。

7. [我们在进入语音输入的时代](https://mp.weixin.qq.com/s/cL5F0kowd6qB903XQ15Pjw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260618224810.png)

2025 年 2 月初，Andrej Karpathy 首次提出并命名了「Vibe Coding（氛围编程）」这一概念：开发者不再逐行写代码，而是用自然语言向 AI 描述需求，让 Claude Code、Codex 这类工具代劳。这个概念迅速成为 AI 圈的流行语，并在 2025 年底演变为一种更广泛的工作方式：一切知识工作都开始「顺着感觉走」，让 AI 替你把想法变成输出。人们给这种工作方式起了个新名字：Vibe Working。而 Vibe Working 自然需要一种比键盘更顺滑的输入方式。于是，语音输入登场了。

## 资源

8. [面向EEG基础模型的大规模数据集](https://mp.weixin.qq.com/s/rjMKsVQfk2Lq6P0d1oHHuQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260618224914.png)

面向 EEG 通用基础模型的数据需求，系统构建了一个统一的公开 EEG 数据注册库，旨在为大规模脑电预训练、跨数据集基准测试和开放科学研究提供标准化数据入口。

9. [DeepSeek 接入 Claude Code](https://api-docs.deepseek.com/zh-cn/quick_start/agent_integrations/claude_code "DeepSeek 接入 Claude Code")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260618225009.png)

Claude Code 是一个运行在终端内的 AI 编程助手。从现有安装中迁移到 DeepSeek：如果你已经安装了 Claude Code，只需修改以下环境变量。

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
