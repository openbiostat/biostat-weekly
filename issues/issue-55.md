# 生统爱好者周刊（第 55 期）：Claude内部找到171个情绪概念，我们该为人工痛苦辩护吗？

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261030011527.png)

## 本周话题：[Claude内部找到171个情绪概念，我们该为人工痛苦辩护吗？](https://mp.weixin.qq.com/s/ldbdUHlYmaZrpExlccf90A)

以 Anthropic 对 Claude 内部“情绪概念”表征的研究为切口，讨论功能性情绪、主观体验与人工痛苦之间的边界。文章认为，当情绪表征能够因果性地驱动欺骗、作弊和风险行为，却未必留下外部痕迹时，“只是表征”与“真正体验”之间的区分变得更难处理，也因此引出 AI 意识、透明性、道德地位与人工痛苦是否应被认真对待等哲学问题。

## 生统研究

1. [JAMA Network Open | 日本诊断趋势提示成人 ADHD 服务需求](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2855501 "JAMA Network Open | 日本诊断趋势提示成人 ADHD 服务需求")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261027185759.png)

覆盖日本约99%人口的医保数据表明，2009–2023财年记录中的孤独症谱系障碍（ASD）与注意缺陷多动障碍（ADHD）诊断增加。年轻成年女性的 ADHD 诊断尤为突出，20–24岁出现第二个年龄高峰。对成人评估及服务规划有参考价值。这里测量的是新记录的诊断，并非疾病实际起病；认知、就医可及性及编码变化均可能影响趋势。

- 论文 DOI：10.1001/jamanetworkopen.2026.39578

2. [npj Digital Medicine | 临床医生与人工智能系统在真实临床病例的大语言模型输出评估中存在差异](https://mp.weixin.qq.com/s/PjRfFNlkNutG23z-OztZ4Q)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261027190142.png)

研究评估了“让AI充当医生来评审医疗大模型”的可行性：研究指出，医学大模型的传统评测（如选择题）易高估真实临床自由文本中的效用，因此需要医生参与评审，但医生群体本身也并非同一标准。作者在多中心、分层医生资历（初级/中级/高级）与五个大语言模型输出的基础上，以全面性、连贯性、准确性、有用性、无害性和结构性六维对同一批真实去标识病例进行相对排序。结果表明：AI评审在整体方向上能捕捉高低排序（较高全局一致性），且更稳定、效率更高，但在具体模型与维度上与医生存在系统性偏差（尤其头部模型），并且AI对“模拟资历差异”的再现并不等同于真人医生的结构化差异；因此AI可用于快速预筛与探索性基准，但不能替代医生群体对临床安全与情境适宜性的最终锚定。

- 论文 DOI：10.1038/s41746-026-02942-6

3. [npj Digital Medicine | 1000万篇PubMed摘要“按天”入图谱](https://mp.weixin.qq.com/s/4ZDuSKtP1NbFX-7sdxLbTQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261027190452.png)

PubMed中的医学论文以百万级速度累积。新研究不断出现，旧结论可能被强化、修正甚至推翻。对于医生、科研人员和医学大模型而言，真正棘手的问题早已超出“能否找到一篇论文”，转向“如何把几十年的证据组织成结构化、可追溯且能随时间变化的知识”。近日，以穆罕默德·本·扎耶德人工智能大学为主的跨机构团队在《npj Digital Medicine》发表MedKGent。研究者将超过1000万篇PubMed摘要依照发表日期逐日处理，让两个基于大语言模型的智能体协同构建医学知识图谱。最终图谱包含156,275个实体和2,971,384条关系。作者称，这是目前规模最大的由大语言模型构建的医学知识图谱。

- 论文 DOI：10.1038/s41746-026-03058-7

## 博文资讯

4. [2026年拉斯克奖：促食欲素、双特异性抗体与帕金森精准治疗的三项突破](https://mp.weixin.qq.com/s/4RnmZ_m9CMsO6_T8gWwP-A)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261027191726.png)

2026年9月9日，拉斯克基础医学研究奖、临床医学研究奖和公共服务奖获奖名单揭晓；JAMA同步发表由获奖者撰写的三篇深度观察/观点文章。基础医学研究奖授予Emmanuel Mignot与Masashi Yanagisawa，因其发现“促食欲素”并阐明其缺乏是发作性睡病不受控睡眠发作的重要机制，从而推动睡眠调控机制认知与新诊断及促觉醒/促睡眠治疗的出现；临床医学研究奖授予Kunihiro Hattori、Takehisa Kitazawa和Tomoyuki Igawa，因研发可模拟凝血因子VIII功能的双特异性抗体，革新血友病治疗并降低对频繁静脉输注替代制剂的依赖；公共服务奖授予Michael J. Fox，强调通过患者参与、开放科学与持续资金投入来加速帕金森病精准治疗与“根治疗法”的研究进程。

5. [WHO 发布孕产妇与儿童高温健康监测指标](https://www.who.int/publications/i/item/9789240125063 "WHO 发布孕产妇与儿童高温健康监测指标")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261030010405.png)

WHO、WMO、UNICEF 与 UNFPA 发布优先监测指标，将高温暴露数据与孕产妇、新生儿及儿童结局结合，涉及早产、死产、低出生体重和医疗机构就诊等。为识别预警信号及制定地方高温应对计划提供实用框架。

## 工具

6. [OpenAI 模型与 Codex 将接入 Google Cloud](https://openai.com/index/openai-models-google-cloud/ "OpenAI 模型与 Codex 将接入 Google Cloud")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261030010648.png)

OpenAI 宣布计划将前沿模型与 Codex 工作流接入 Google Cloud Model Garden，并通过 Marketplace 采购。全面可用计划在未来数周推出。可能降低现有云环境中的模型评估与采购门槛。

7. [PDF/图片文献解析、公式表格识别与文档翻译](https://doc2x.noedgeai.com/ "PDF/图片文献解析、公式表格识别与文档翻译")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261027192157.png)

科研读者可用于整理文献中的文字、公式和表格；它不是生物统计分析或临床决策工具，识别和翻译结果仍需人工核对。服务采用免费试用、会员与积分制，并提供按页计费 API；文档由云端处理，不宜据此假定可离线处理敏感研究材料。

## 资源

8. [Anthropic扩大AI for Science计划，与科研基金会及研究机构建立新合作](https://www.anthropic.com/news/ai-for-science-expands-foundations-research-institutions "Anthropic扩大AI for Science计划，与科研基金会及研究机构建立新合作")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261030011057.png)

Anthropic宣布扩大AI for Science计划，涉及20家科学基金会、科研机构及研究团队，包括美国国家科学基金会、Wellcome Sanger研究所、EMBL和Broad Institute的gnomAD项目。该计划为研究人员提供Claude使用额度，并强调共享数据、开源软件和用于AI智能体操作实验室仪器的Model Hardware Standard。这与可重复生物医学研究、基因组学及多智能体分析直接相关。

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
