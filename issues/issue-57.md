# 生统爱好者周刊（第 57 期）：科研越来越像一门生意：科研人员拼命做实验，有人却靠卖科研焦虑发财

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261113000217.png)

## 本周话题：[科研越来越像一门生意：科研人员拼命做实验，有人却靠卖科研焦虑发财](https://mp.weixin.qq.com/s/n1MqA3QKIHLh1WR-YkC1ng)

随着科研评价与论文、项目、专利等指标深度绑定，科研人员面临的竞争压力催生了商业化的科研服务市场。从高被引服务、基金标书代写到专利代理和论文引用操纵，一些机构利用科研人员的焦虑牟利，甚至将未中标的申请书包装成“成功案例”进行宣传。文章强调，正规的科研培训和专业服务具有一定价值，但代写标书、购买成果和操纵引用等行为已经触及科研诚信底线。科研服务本身并非问题，真正值得反思的是科研评价体系如何催生了对“捷径”的需求，以及科研人员为何逐渐成为科研焦虑产业链的消费者。

## 生统研究

1. [bioRxiv | 并行 AI 智能体从脑细胞数据中生成可检验假设](https://www.biorxiv.org/content/10.64898/2026.10.15.759436v1 "bioRxiv | 并行 AI 智能体从脑细胞数据中生成可检验假设")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261113000611.png)

团队报告用数千个 GPT-Rosalind 智能体，在32分钟内解读小鼠脑基因扰动图谱。盲评中，专家有75%的比较更偏好分布式智能体报告。可为实验优先级排序及数据与文献整合提供思路。但生成的假设不等于已验证治疗，人工耗时估算也不等于前瞻性对照试验。

- 论文 DOI：10.64898/2026.10.15.759436

2. [Nature Medicine | MedGemma：面向多种医疗任务的开放视觉-语言模型](https://www.nature.com/articles/s41591-026-04626-w "Nature Medicine | MedGemma：面向多种医疗任务的开放视觉-语言模型")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261113001352.png)

Nature Medicine 10 月 6 日发表 MedGemma，一组基于 Gemma 3、针对医学场景专门优化的视觉-语言基础模型。在分布外测试中，相比基础模型，MedGemma 在医学图像问答、胸片分类以及 agentic evaluation 等任务上均取得明显提升，同时配套推出医学视觉编码器 **MedSigLIP。这项工作正好位于“医学研究 × 基础模型 AI”的交叉点。真正值得关注的不只是 benchmark，而是这种规模相对可控、可微调的医学模型能否成为影像、文本以及临床工作流 AI 的通用底座。

- 论文 DOI：10.1038/s41591-026-04626-w

## 博文资讯

3. [FLOW试验如何重塑糖尿病肾病治疗格局](https://mp.weixin.qq.com/s/d_W9SOUOi1SKhFEwTQKEbQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261113005358.png)

慢性肾脏病（CKD）是2型糖尿病最常见的并发症之一，也是全球终末期肾病的主要病因。在FLOW试验结果公布之前，糖尿病肾病的治疗主要依赖肾素-血管紧张素系统抑制剂（RASi）延缓疾病进展，SGLT2抑制剂（SGLT2i）则自2019年起被证实可进一步降低心肾事件风险。然而，即便在RASi和SGLT2i的双重保护下，仍有大量患者面临肾功能持续下降的风险。GLP-1受体激动剂（GLP-1 RA）能否提供额外的肾脏保护？FLOW试验给出了明确的答案。

4. [人群归因分数概念、简单计算案例](https://mp.weixin.qq.com/s/0wAhGL0fhnFEs5LwOBF5Nw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261113005514.png)

人群归因分数（Population Attributable Fraction, PAF）是疾病负担研究中常用的指标，其大致含义是，假设人群的风险暴露降低至理想水平，预计可减少的患病人口数占实际患病人口数的比例。

## 工具

5. [AI智能体寻找新抗菌肽](https://mp.weixin.qq.com/s/m77tHmceILUp_102RERWPA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261113005627.png)

Google DeepMind 展示了一种利用AI智能体发现新型抗菌肽（AMPs）的工作流程。研究团队借助 ProtNLM，从 UniProt 数百万条蛋白质序列中筛选潜在候选物，并结合 BLAST 序列比对、AlphaFold 结构分析及基因组邻域分析进行多层验证，最终发现一条97个氨基酸的细菌素候选序列。目前，该候选物已进入湿实验验证阶段。该工作展示了AI智能体整合蛋白质数据库检索、生物信息学分析、结构预测和实验设计的能力，为加速新型抗菌分子的发现提供了新的思路。

6. [肿瘤数字孪生python框架](https://mp.weixin.qq.com/s/AuzFAQ4UK838C_HFco_RzQ)

UT Austin 团队开发了开源 Python 框架 TumorTwin，旨在解决肿瘤数字孪生研究中代码定制化程度高、跨病种可移植性差的问题。该框架基于 PyTorch 构建，整合反应扩散方程、化疗药物衰减模型和放疗线性二次模型，利用纵向 MRI 中的 ADC 数据估计肿瘤细胞密度，并通过优化算法完成患者特异性模型标定。研究展示了其在高级别胶质瘤和三阴性乳腺癌中的应用潜力，并实现了约195万个自由度的三维肿瘤模拟，支持肿瘤生长预测及不同治疗方案的反事实推演。不过，目前模型仍存在参数空间均一化、不确定性量化不足及缺乏大规模临床验证等局限，距离实际临床应用仍有一定距离。

## 资源

7. [《Lancet Global Health》统计方法及应用趋势](https://mp.weixin.qq.com/s/w4mOxpQxqJj0AAXw5Hk_-g)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261113005843.png)

《Lancet Global Health》2026年发表的研究展现了公共卫生统计方法的多元化应用。1. 贝叶斯分层模型与序数回归：多国调查中的合并估计。2. 双重差分与双向固定效应：政策评估中的准实验设计。3. 个体参与者数据汇总、不平等指数与风险预测。4. 诊断准确性研究与外部验证。整体趋势显示，顶刊研究正从单纯的疾病负担描述，逐步转向不确定性量化、因果效应评估、健康不平等分析和模型外部验证，强调统计方法与实际公共卫生决策问题的结合。

8. [斯坦福最新课程发布：200行写Claude Code，批量培养「AI 原生开发者」](https://mp.weixin.qq.com/s/7vd3Wjy8ES9E9aqGy8HDtQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261113010029.png)

这门课是 CS146S《The Modern Software Developer》，于 2026 年秋季学期再次更新！课程不沿用过去的教学路径，而是推翻了去年秋季 85% 的旧教案。原因在于：随着 Claude 等前沿大模型在推理与长程规划上的能力阶跃，代码智能体（Coding Agent）已不再是简单的辅助插件，而是彻底重构了软件工程的协作链路。

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
