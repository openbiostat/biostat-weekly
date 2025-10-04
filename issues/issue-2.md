# 生统爱好者周刊（第 2 期）：非升即走，是人才培养更重要还是科研绩效更重要

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251002161737.png)

## 本周话题：[非升即走，是人才培养更重要还是科研绩效更重要](https://mp.weixin.qq.com/s/fwizpM-ZDeZ9Qy81fa2Lmg)

> “培养”与“不培养”的区别，就是将预聘的青年教师看作“自己人”还是“过客”。如果是前者，就会竭其所能，在科研和教学方面提供方便。如果是后者，则“公事公办”，以硬性的量化指标予以考核和约束。现在看来，后一种情况占绝大多数。对比 Tenure Track，两者形似而神不似。

有关此事，相关的评论和论文也发表了不少。但国内的情形就是这样，思考者与管理者经常是二分的，纵使思考者一再呼吁、理性分析，管理者仍常凭感觉行事。

## 生统研究

1. [Nature Medicine | 跨多种器官和影像模态生成高质量合成医学影像](https://mp.weixin.qq.com/s/wzU7BnqkWe9o1wN6vXSp9g)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251002162047.png)

MINIM（Medical Image-Text Generative Intelligent Model），这是首个能够跨多种器官和影像模态生成高质量合成医学影像的统一基础模型。该研究团队在北京大学王金卓教授和温州医科大学张康教授的联合领导下，首次验证了基于文本条件的多模态医学影像生成技术在临床应用中的实际价值，不仅在图像质量上达到了临床可用标准，更重要的是在肺癌EGFR突变检测和乳腺癌HER2状态预测等关键临床任务中展现出显著的预后改善效果。

- 论文 DOI：10.1038/s41591-024-03359-y

2. [Nature Machine Intelligence | 基于贝叶斯网络的 GWAS 因果推断框架](https://mp.weixin.qq.com/s/N9HF7a9mu2hbuBLrXNtjAw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251002162317.png)

本文提出了一种新的分析框架 Bayesian Network GWAS (BN-GWAS)，结合了贝叶斯网络建模和因果效应估计方法（如 MR、IDA/jointIDA），旨在系统性构建基因–基因–疾病因果网络，进而量化基因的直接效应、间接效应以及联合效应。

- 论文 DOI：10.1038/s42256-024-00906-7

3. JAMA Psychiatry | 心理健康研究中的跨诊断临床分期模型

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/![](httpscdn.jsdelivr.netghLeslie-LuWeChatOfficialAccountimg_202520250925155951.png).png)

当前心理健康研究中，跨诊断（transdiagnostic）临床分期模型受到越来越多关注。即不局限于某一类障碍（如抑郁、焦虑、精神病），而是试图把早期症状和风险因素建立一个分期 / 进展模型。该研究为跨诊断临床分期模型提供了强有力的纵向实证支持：从儿童到青年期，早期家族风险 -> 轻微症状 -> 中度 / 功能受损症状之间存在一种阶段性、渐进式的转变路径。中介分析表明，性格特质（如神经质倾向）等可能是干预目标：如果能够调节或缓冲神经质倾向（例如通过心理干预、情绪调节训练等），或许可以减缓或阻止从轻症到中重症的转化。该研究也强调：在心理健康的早期干预设计中，除了考虑固定的风险因素（如家族史、早期逆境等），还应将阶段身份（即当前症状状态）本身纳入风险评估和干预决策。

- 论文 DOI：10.1001/jamapsychiatry.2025.2648

## 博文资讯

4. [解析面向对象在软件工程中的应用](https://mp.weixin.qq.com/s/EkMK_xuLoAHuI--65trynw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251002163346.png)

本文系统解析了面向对象思想在软件工程中的核心价值与应用体系。作者从发展史切入，厘清面向对象与UML、软件工程、DDD等概念的关系，重点阐述用例建模方法、面向对象分析（OOA）的建模过程（含静态/动态建模及深层模型）、面向对象设计（OOD）的职责驱动模式（GRASP），最终构建出从理论到实践的完整知识框架。

5. [LLM 是如何工作的](https://www.lesswrong.com/posts/XGHf7EY3CK4KorBpw/understanding-llms-insights-from-mechanistic?utm_id=FAUN_VarBear495_Link_title "LLM 是如何工作的")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251002163741.png)

该文概述了 Transformer LLM 工作的基本原理，适合初学者阅读。

## 工具

6. [Git 实用技巧](https://mp.weixin.qq.com/s/u4lt3ucIeMZT-c1zAj7YAg)

![](https://img.devrant.com/devrant/rant/r_292990_JmRu7.gif)

推文文章列举 Git 实际应用的技巧，可以更直观的了解 Git 命令的使用方法。

7. [monkeSearch，Mac 上的语义文件搜索](https://github.com/monkesearch/monkeSearch "monkeSearch GitHub")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251002164205.png)

在 Mac 上进行完全本地化、时间感知的自然语言文件搜索，在不到 1 秒的时间内使用自然语言查找相关文件。

8. [开放科学计量学学习平台](https://www.metametrix.cn/ "开放科学计量学学习平台")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251002164322.png)

该平台提供了科学计量学的相关阅读材料与教程指南，帮助研究者掌握科研趋势分析、合作网络可视化与知识图谱构建的方法，支持跨学科交流与科研影响力评估。

## 资源

9. [GWAS 教程](https://cloufield.github.io/GWASTutorial/ "GWAS 教程")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251002164457.png)

该教程由东京大学镰谷研究室提供，主要面向生物信息学/统计遗传学的初学者。

10. [Scoop 国内软件仓库](https://github.com/scoopcn/scoopcn "Scoop 国内软件仓库")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251002164557.png)

支持安装管理常用的国内应用程序。

11. [The Python Language Reference](https://docs.python.org/3/reference/index.html "The Python Language Reference")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251002164759.png)

《The Python Language Reference》是Python官方提供的一份核心文档，它系统地阐述了Python语言本身的语法和核心语义。当你对某个语言机制的底层原理感到困惑时（例如，描述符如何工作、生成器的执行流程、元类的实例化过程），这份文档是最终的答案来源。它也是Python解释器实现者必须遵循的准则。

## 贡献者（GitHub ID）

「OpenBioStat 生统爱好者周刊」运维小组：

- [`@Leslie-Lu`]（陆震）
- [`@YihanChen325`]（陈奕含）
- [`@kirihsia`]（夏鑫辛）
- [`@GCRPM`]（徐林玉）

## 订阅

本周刊每周五发布，同步更新在微信公众号「陆震生物统计」（luzhen-biostat）上。

微信搜索“陆震生物统计”或者扫描二维码，即可订阅。

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/qrcode_for_gh_395f59db8b4c_258.jpg)

（完）
