# 生统爱好者周刊（第 4 期）：一辈子动手做实验的科学家

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251016154817.png)

## 本周话题：[一辈子动手做实验的科学家](https://mp.weixin.qq.com/s/QvMFFEHBwCveO_RI4vWkPQ)

> John Gurdon (1933-2025) 是做出过重要工作的发育生物学家，特别是在体细胞核移植、发育的分子生物学研究。Gurdon的特点之一是一直自己动手做实验，得诺奖不影响、86岁也照样做。

驱动科研的核心还是要真地感兴趣好奇，渴望产出有价值的知识。这样的人和氛围，还是少有的。

## 生统研究

1. [Nature | Delphi-2M：重新定义疾病预测与健康管理](https://mp.weixin.qq.com/s/EnRT1wpgwfd0HinFY5PukA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251016155107.png)

近几年来，在智慧医疗领域中出现了一种新的技术：利用大型语言模型（LLM）跟踪和预测个人一生中的疾病轨迹，这一技术在改善个性化医疗方面具有巨大的潜力。该研究的意义在于，Delphi-2M能够全面预测多种疾病并理解疾病之间的相互关系，推动精准医疗的发展，实现个性化健康管理。通过捕捉疾病的时间性进展，模型为长期健康评估提供了新视角，并展示了在不同地区的广泛适用性，能够为全球公共卫生决策提供支持。

- 论文 DOI：10.1038/s41586-025-09529-3

2. [AJHG | 基因-环境相互作用的模型阐释](https://mp.weixin.qq.com/s/NC8BZe1l1gznB9GFVdadug)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251016155240.png)

在以往的基因组研究中，常采用的统计模型包括单位点模型（例如全基因组关联研究GWAS）和全基因组模型（例如多基因风险评分PRS）。然而，在基因-环境交互作用(GxE)研究中该采用怎么样的统计模型来构建疾病模型呢？本文提出了三种统计方法，用于区分GxE交互作用的三种机制，并应用于UK Biobank中33个性状与10种环境变量的分析，为未来的GxE研究提供了可遵循的研究框架。

- 论文 DOI：10.1016/j.ajhg.2025.01.014

## 博文资讯

3. [FDA 更新审评 TFL 指导文件](https://mp.weixin.qq.com/s/gIaNocHcH3lcQBhnyggI3w)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251016155519.png)

FDA 更新两份内部工作指南，一份是定制医学查询（OCMQs），另一本是标准安全性表与图（ST&Fs）2.0版。它们其实是帮审评员（以及想顺利过关的药企）更聪明、更一致地审查药品安全性的“神器”。

4. [GBD2023 数据开放下载](https://mp.weixin.qq.com/s/KMVZvvY_6HnKEJJeRT_IzQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251016160042.png)

2025年10月12日，《柳叶刀》（IF 88.5）全球疾病负担研究（GBD）2023齐发三篇重磅文章，同步开放了GBD2023数据的下载。推文介绍了三篇文章的主要发现。

5. [透视2025年诺贝尔生理学或医学奖](https://mp.weixin.qq.com/s/rn3cUnrzdl8Ao1jA7yd02A)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251016160106.png)

三位科学家因为发现了一种新的外周组织免疫耐受调节机制，即调节性T细胞及其工作机制，获得了本年度诺贝尔生理学或医学奖。

## 工具

6. [R 包 pheatmap 绘图](https://mp.weixin.qq.com/s/wVTH_3_xbsH_5x0X-BByYA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251016160226.png)

热图是一种非常有用的数据可视化工具，被广泛应用于生物信息学领域。推文详细介绍R 包 pheatmap 绘图基础与进阶。

7. [15 个Web 开发者需要知道的杀手级网站](https://mp.weixin.qq.com/s/vZFTHYeyoPbhhTWh8nSiqw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251016161030.png)

推文介绍了一些提高工作效率的网站工具，如免版税插图、调色板等。

8. [Codex 支持本地运行+多端协同](https://mp.weixin.qq.com/s/Zfw9WIVrPeVLIcHxmkHgJQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251016161139.png)

Codex是一款可在本地终端、IDE、云端运行的AI编程助手，能够生成、读取、修改并执行机器上指定目录中的代码。该工具基于Rust语言构建以确保速度与效率，目前正在持续快速迭代。推文介绍了三种使用Codex的方式。

## 资源

9. [Think Bayes: Bayesian Statistics in Python](https://github.com/AllenDowney/ThinkBayes "Think Bayes: Bayesian Statistics in Python")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251016161332.png)

ThinkBayes 是由 Allen B. Downey 教授编写的一套关于贝叶斯统计（Bayesian Statistics）的开源教材与示例代码。该项目旨在通过直观、编程驱动的方式，帮助读者理解并掌握贝叶斯思维与推断方法。本项目配合作者的著作 《Think Bayes: Bayesian Statistics in Python》 使用（O’Reilly 出版），书中通过一系列实际问题（如赌博、疾病检测、信号识别、MCMC抽样等）逐步展示如何利用 Python 进行贝叶斯建模与推断。

10. [Hugging Face 提供的 5 门免费 AI 课程](https://www.kdnuggets.com/5-free-ai-courses-from-hugging-face?utm_id=FAUN_Kala497_Link_title "5 门免费 AI 课程")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251016161451.png)

推文回顾了 Hugging Face 上提供的一些最受欢迎且必不可少的免费课程。这些课程涵盖 AI 代理、模型上下文协议 (MCP)、大型语言模型 (LLM)、扩散模型和强化学习等主题，所有这些都是当今快速发展的 AI 领域的核心。

11. [精选 LLM 应用集](https://www.zdoc.app/zh/Shubhamsaboo/awesome-llm-apps "精选 LLM 应用集")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251016161601.png)

精选整理的使用 RAG、AI 智能体、多智能体团队、MCP、语音智能体等技术构建的 Awesome LLM 应用集合。该仓库收录的 LLM 应用使用了来自 openai logoOpenAI、anthropic logoAnthropic、google logoGoogle、X logoxAI 的模型，以及如 alibaba logoQwen 或 meta logoLlama 等可在本地计算机上运行的开源模型。

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
