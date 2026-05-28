# 生统爱好者周刊（第 35 期）：高校集体号召过紧日子

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260528210732.png)

## 本周话题：[高校集体号召过紧日子](https://mp.weixin.qq.com/s/Lw6yqiBfVV0TO6Z9x87mTw?scene=1)

近几年，经济压力持续传导至教育领域，全国多所高校陆续发文提倡「习惯过紧日子」，从压缩行政开支、严控差旅培训，到收紧人才引进待遇、下调科研与教学奖励，一系列政策密集落地。

## 生统研究

1. [Nature丨全球首个人类胚胎早期器官发生阶段时空动态转录全景图问世](https://mp.weixin.qq.com/s/gd1G0qqQORkyA0gL103KFA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260528204511.png)

长期以来，受精后第4周至第8周的人类胚胎发育阶段被视为“认知盲区”——既难以在体外培养获得该时期的胚胎，也无法通过影像学手段获取类似胎儿发育的精准数据。然而，这一阶段的分子调控与人类对自身发育的认知密切相关，同时该阶段的发育异常与先天性心脏病、神经发育障碍及多种疾病的易感性密切相关。尽管近年来测序技术不断进步，针对该阶段胚胎转录特征的系统性、连续性时空解析数据仍极为稀缺。

2026年5月27日，复旦大学、浙江大学与华大生命科学研究院基因组多维解析技术全国重点实验室科研团队在Nature上发表了题为Spatiotemporal transcriptome atlas of human embryos after gastrulation的研究论文。研究团队通过整合高分辨空间转录组技术Stereo-seq与单核RNA测序 (snRNA-seq)，首次系统绘制了覆盖原肠运动后、器官形成关键期 (Carnegie stage 12–23，受精后约4至8周) 的人类全胚胎时空转录组图谱。这是全球首个人类胚胎早期器官发生阶段时空转录全景图，标志着人类对早期器官发生的认知，从零散的切片观察迈入整体、动态、分子化的全景解析新阶段。同期，Nature杂志配发评论文章高度评价这项工作，评价认为“With this resource, they provide a powerful framework for connecting genetic variation to human disease”.

- 论文 DOI：10.1038/s41586-026-10545-0

2. [Nature BME | 利用类关联流形学习弥合医学人工智能模型的可解释性差距](https://mp.weixin.qq.com/s/P5g1PGfaccZaopZZNOos6w)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260528205134.png)

深圳理工大学及中国科学院深圳先进技术研究院团队提出了一种称为“类关联流形学习”的数学方法，成功将黑盒AI模型决策规律转化为低维空间可视化流形，可识别AI模型决策的关键因素，并且以生成式方法生成使得模型输出改变的一系列特征变化样本，从而让医生直观理解模型行为，弥合了医疗AI的“可解释鸿沟”，有助于发现AI背后隐藏的医学知识规律。

- 论文 DOI：10.1038/s41551-026-01676-w

3. [Nature | Co-Scientist：多智能体 AI 加速科学发现](https://mp.weixin.qq.com/s/LVNZk-Lv-6i0u4ieNPH4Gg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260528205357.png)

本文提出 Co-Scientist，一个基于 Gemini 的多智能体科学推理系统，用生成、反思、排序、演化和专家反馈来产生可检验假说，并在 AML 药物再利用、肝纤维化靶点发现和抗菌耐药机制解释三个生物医学场景中做了初步真实验证。

- 论文 DOI：10.1038/s41586-026-10644-y

## 博文资讯

4. [基金委重磅发布：青年科学基金项目（C类）资助规模将大幅增长](https://mp.weixin.qq.com/s/BxoWZDHzlZBEnFxjxAuMNA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260528205851.png)

5月13日，国家自然科学基金委员会网站发布重磅消息：为深入贯彻落实习近平总书记在加强基础研究座谈会上重要讲话精神，进一步加大对青年科技人才支持力度，国家自然科学基金委员会将于2026年大幅增加青年科学基金项目（C类）资助规模，预计增加12000项，增幅超过50%。此举将为基础研究提供源源不断的优秀后备人才。

5. [真实世界研究里，先看两组有没有足够重叠](https://mp.weixin.qq.com/s/IE0vYANB9wted68WrRoT4w)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/43faf651802366b70bfef5bbc1f7eeee.jpg)

做真实世界研究时，我们经常会遇到一个看起来很技术、但其实很基础的问题：两组患者到底是不是同一类人？比如一组患者用了某个治疗，另一组患者没有用；或者一组用 A 药，另一组用 B 药。后面当然可以做倾向评分匹配、加权、分层，也可以上 Cox 模型、Logistic 回归或更复杂的模型。但在这些动作之前，有一个问题要先回答：这两组人有没有足够的重叠区间？

## 工具

6. [我用 Codex 做研究后，总结出 6 条有用经验](https://mp.weixin.qq.com/s/gyLbhAIIe67KhfrCqtWXmw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260528205949.png)

最近用 Codex 做了一些研究导向的代码工作，包括论文复现、读高质量 repo、整理实验逻辑、改课程项目里的功能。 我现在更愿意把它当成一个项目协作者。本文是总结出的一些使用经验。

## 资源

7. [DeepSeek陈德里与两个AI，合写了一篇论文](https://mp.weixin.qq.com/s/Z8IOHlufZrZvgF4be5X-lA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260528210313.png)

DeepSeek 研究员陈德里（Deli Chen）在 X 上分享了一篇由 AI Agent 深度参与完成的文章「From Copilots to Colleagues: A Survey of Autonomous Research Agents」。完成这篇文章后，陈德里也由此抛出了一个颇有意思的判断，他形容为个人暴论：Code Agent 正在让计算机科学论文发生疯狂通胀 —— 过去同样的工作，至少要花一个月。

论文的最后写道：「L5 自主研究 —— 能够自主制定长期研究议程的智能体 —— 是一个『何时』而非『是否』的问题。研究社区的任务是确保这一转变伴随着充分的理解、适当的保障，以及公平的收益分配。」

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
