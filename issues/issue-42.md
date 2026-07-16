# 生统爱好者周刊（第 42 期）：如何应对中国的肥胖问题

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260716220556.png)

## 本周话题：[如何应对中国的肥胖问题](https://mp.weixin.qq.com/s/try5quB45L6VJLICDfEFig)

柳叶刀-区域健康（西太平洋）》3月刊中多项中国相关研究核心聚焦肥胖流行趋势及其多层次风险因素，并延伸至感染治疗、抗菌耐药、HIV治疗策略及环境健康影响等议题。研究指出，中国肥胖问题将在未来持续加重，其成因涉及个体行为、环境与政策多重因素，当前防控体系仍存在明显缺口；同时，多项临床研究揭示了治疗策略优化、耐药性挑战及环境因素对健康的重要影响，强调循证决策与系统性干预的必要性。

## 生统研究

1. [Science | 人工智能代理的自主生物医学研究 Biomni](https://mp.weixin.qq.com/s/wcdwE_pfzH_TNk_lYGN2Yg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260716215944.png)

Kexin Huang 等人在 Science 发表《Autonomous biomedical research with an artificial intelligence agent》，介绍了通用生物医学 AI 智能体 Biomni。这项研究释放了一个清晰的信号：我们正在从医疗 AI 问答时代，进入医疗 AI 智能体时代。医疗 AI 的下一次跃迁，不只是“更会回答问题”，而是能够理解研究目标、调用专业工具、执行分析流程，并与临床医生共同完成一项研究。

- 论文 DOI: 10.1126/science.adz4351

2. [npj Digital Medicine | CancerLLM：癌症领域的大型语言模型](https://mp.weixin.qq.com/s/gFgsFLa0jsFTmqEIIbjmNg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260716220301.png)

通用生物医学大语言模型（如 BioMistral、ClinicalCamel、PMC-LLaMA）主要在 PubMed 摘要或 MIMIC-III 等通用生物医学文本上训练，对肿瘤领域的特殊表述模式覆盖不足。肿瘤学有自己独特的术语体系、复杂的分期分级系统（TNM 分期、Gleason 评分等）以及高度结构化的临床记录格式。Li 等人在npj Digital Medicine上发表了 CancerLLM（DOI: 10.1038/s41746-026-02441-8），一个基于 Mistral 7B 构建的肿瘤领域专用大语言模型。该模型在癌症表型提取和诊断生成两个核心任务上的平均 F1 分别达到 91.78% 和 86.81%，比现有最优基线平均高出 9.23 个百分点——而它的推理显存仅需 5,550 MB，不到 70B 参数模型的七分之一。

- 论文 DOI: 10.1038/s41746-026-02441-8

## 博文资讯

3. [Anthropic：AI做生物研究，卡在数据库](https://mp.weixin.qq.com/s/Y-jguaIV4dRDc2nRXbBOxg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260716220412.png)

AI写代码已经很强了，但做生物研究却明显落后。Anthropic最新发的一篇科学博客揭示了一个反直觉的原因：瓶颈不只是模型推理能力，而是生物数据基础设施还没为agent准备好。

4. [Ozempic等GLP-1类药物是否能预防癌症](https://theconversation.com/can-ozempic-prevent-cancer-a-doctor-explains-why-the-headlines-are-easy-to-misread-285206 "Ozempic等GLP-1类药物是否能预防癌症")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260716220556.png)

最近"Ozempic等GLP-1类药物能预防癌症"的说法有点跑在证据前面了。而这类研究有三个特别容易被误读的地方：一是"健康使用者偏倚"——能用上这类药、还坚持用下去的人，往往本身就比同等体重但没有这些条件的人更健康、经济状况更好，观察性研究很难剔除这种偏倚，真正压低癌症风险的可能是促成用药的那些背景优势，而非药物本身；二是对照组选择会直接影响结果，比如把GLP-1药物使用者和胰岛素使用者做比较，但胰岛素通常留给病情更重的糖尿病患者，这类人群癌症风险本就偏高，跟这样一个高风险对照组比，几乎什么药都会显得"有保护作用"；三是起效时间不太合理——癌症往往要几十年才发展出来，但多数相关研究随访时间只有几年，部分研究里"保护效果"几乎在用药后立刻出现，这在生物学上讲不通，更像是偏倚而非真实药效。

## 工具

5. [Anthropic推出Claude Science](https://mp.weixin.qq.com/s/MYkNSBieg9W5_-Olopk3Tg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260716220717.png)

Anthropic推出AI工作平台Claude Science，可用于自动化完成一系列生物学和化学研究任务，例如预测蛋白质结构。这款软件整合了科学家常用的多种工具，包括60多个科学数据库，其目标是让科学家能够更轻松地自动化执行多步骤任务，使用自然语言提问，并在无需逐一查询多个信息来源的情况下获得答案。

6. [17 条规则去除 AI 味](https://mp.weixin.qq.com/s/dz5Fdv3RZi-x-jV7ZtNmiA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260716220920.png)

Nature 报道了一款名为 Academic Humanizer 的开源项目。与常见的 AI 写作工具不同，它并不负责生成论文，而是专门处理已经完成的 AI 草稿，对语言风格、论断强度和学术表达进行二次优化。这一工具反映出一个新的趋势：AI 学术写作正在从“生成内容”进入“后处理（Post-processing）”阶段。

## 资源

7. [李飞飞: 对于世界模型的深入浅出讲解](https://mp.weixin.qq.com/s/9sTsSma2DLocKBZmXuCR1A)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260716221037.png)

世界模型目前被视为是智能体走向自主感知、推理、规划与生成的重要基础。作为一个未来趋势的重要概念，世界模型正被频繁提及。关于如何理解世界模型的概念和内涵，李飞飞本人在社媒上发布了文章《A Functional Taxonomy of World Models》，深入浅出地讲解了世界模型的内涵和功能。

8. [OpenAI Academy](https://academy.openai.com/ "OpenAI Academy")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260716221142.png)

由 OpenAI 推出的人工智能学习与交流平台，旨在帮助个人、开发者、教育工作者、研究人员和组织系统学习并应用人工智能技术。平台提供涵盖 ChatGPT、生成式 AI、提示工程、AI 应用开发、安全与负责任使用等方向的课程、教程、实践案例和社区资源，帮助用户从基础认知逐步提升至实际应用能力。OpenAI Academy 不仅关注工具使用，更强调培养 AI 素养、问题拆解能力和人机协作思维，推动 AI 在教育、科研、企业和社会领域的创新应用。对于希望系统学习 AI 工作流、智能体应用和未来技术趋势的学习者而言，该平台是官方权威的入门与进阶资源中心。

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
