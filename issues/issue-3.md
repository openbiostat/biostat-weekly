# 生统爱好者周刊（第 3 期）：数据共享范式下，如何用好科学数据

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251009185540.png)

## 本周话题：[数据共享范式下，如何用好科学数据](https://mp.weixin.qq.com/s/uvnQkhmKO-uldFOGoP0w5g)

> 随着科研透明化和数据驱动研究的发展，开放科学理念在全球范围内快速推广。各类科研机构和期刊纷纷要求共享数据、开放论文，以提高研究的可重复性和透明度，同时促进学术合作与创新。

@kirihsia 在推动数据共享的过程中，需要平衡开放性与合规性，制定规范的数据管理和共享协议，让科研数据真正成为创新和合作的桥梁。如此，科研人员才能在保证科研诚信和成果可靠性的前提下，高效利用数据资源，推动科学研究不断前进。

## 生统研究

1. [Nature Medicine | 冠状动脉疾病风险的元预测](https://mp.weixin.qq.com/s/4cik2fu7gPKCipzaQwGxFw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251009173139.png)

探索冠状动脉疾病（CAD）风险的精准预测一直是医学界的重大挑战。最新发表在《Nature medicine》上的研究成果带来了一线曙光——通过巧妙整合年龄、遗传等不可修正因素与临床、生物测量等可修正因素，科学家们构建了一个突破性的元预测框架。这一框架不仅在多个独立测试队列中展现了超越现有标准的预测准确性，更揭示了遗传风险在影响干预措施效果中的关键作用。

令人瞩目的是，研究还深入剖析了CAD风险的异质性，成功识别出五个具有鲜明特征的风险子组。这些子组在面对标准临床干预时，展现出了截然不同的反应模式，进一步凸显了个性化预防策略的重要性和紧迫性。这一创新不仅为CAD的精准预防开辟了新路径，更为临床决策提供了有力支持。

- 论文 DOI：10.1038/s41591-025-03648-0

2. [Nature Communication | JointPRS：一种整合遗传相关性与数据自适应的多群体遗传风险预测框架](https://mp.weixin.qq.com/s/LJCrTfCUCN4M5ZF0bYcwKA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251009190259.png)

多基因风险评分（Polygenic Risk Scores, PRS）通过整合多个遗传变异的影响来预测个体患复杂疾病的风险，在疾病监测、预防和治疗中展现出巨大潜力。然而，目前的PRS研究主要基于欧洲人群的大规模全基因组关联研究（GWAS）数据开发，导致其在非欧裔人群中的预测准确性大打折扣。

耶鲁大学公共卫生学院生物统计系的Hongyu Zhao教授和Leying Guan博士团队在《Nature Communications》发表了本研究。该研究提出了一种名为JointPRS的新型数据自适应框架，旨在解决非欧裔人群遗传风险预测准确性不足的问题。JointPRS利用GWAS摘要统计数据，通过整合跨多个人群的遗传相关性信息来提升预测效果。该方法的一大创新在于其数据自适应性：在没有个体水平调优数据时仍能提供准确预测（JointPRS-auto），而在有调优数据（即使规模较小）时，能自适应地有效利用这些数据进一步优化模型。

- 论文 DOI：10.1038/s41467-025-59243-x

3. [Lancet | 2010~2019年间全球非传染性疾病死亡率变化](https://mp.weixin.qq.com/s/esPpQaXlBQkdEvqAlY1oTA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251009174007.png)

本研究旨在量化2010年至2019年间不同国家和地区非传染性疾病（non-communicable diseases, NCDs）死亡率的变化情况，重点分析其与前十年的对比、与表现最佳国家和地区之间的差距，以及导致死亡率变化的NCD死因类别。研究发现：2010年至2019年间，全球约五分之四的国家和地区NCD死亡率有所下降，但由于多种NCD死亡率降幅减小，多数国家和地区的改善幅度较前十年有所减缓。

- 论文 DOI：10.1016/S0140-6736(25)01388-1

## 博文资讯

4. [高斯过程 Gaussian Processes 原理、可视化及代码实现](https://borgwang.github.io/ml/2019/07/28/gaussian-processes.html "高斯过程 Gaussian Processes 原理、可视化及代码实现")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251009164143.png)

该文对高斯过程进行公式推导、原理阐述、可视化以及代码实现，介绍了以高斯过程为基础的高斯过程回归 Gaussian Process Regression 基本原理、超参优化、高维输入等问题。

5. [博弈论入门教程--从基本概念到具体案例](https://gfwjumper.medium.com/%E5%8D%9A%E5%BC%88%E8%AE%BA%E5%85%A5%E9%97%A8%E6%95%99%E7%A8%8B-%E4%BB%8E%E5%9F%BA%E6%9C%AC%E6%A6%82%E5%BF%B5%E5%88%B0%E5%85%B7%E4%BD%93%E6%A1%88%E4%BE%8B-2d0e54294318 "博弈论入门教程--从基本概念到具体案例")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251009164811.png)

博弈论（game theory）专门研究多个独立个体之间的竞争行为（对抗行为），该文概述了博弈论的基本概念。

6. [从另一个视角看Transformer：注意力机制就是可微分的k-NN算法](https://mp.weixin.qq.com/s/Ty3Qh5b2DtE8dkTGi93VXA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251009165035.png)

注意力机制听起来很玄乎，但我们可以把它看作一个软k-NN算法。查询向量问："谁跟我最像？"，softmax投票，相似的邻居们返回一个加权平均值。这就是注意力头的另外一种解释： 一个可微分的软k-NN：计算相似度 → softmax转换为权重 → 对邻居值求加权平均。

## 工具

7. [SigProfilerExtractor--矩阵化的突变数据的一站式工具](https://github.com/AlexandrovLab/SigProfilerExtractor "SigProfilerExtractor")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251009165516.png)

SigProfilerExtractor 是在矩阵化的突变数据上自动完成“签名个数确定 + 签名谱提取 + 样本暴露量估计”的一站式工具，前端依赖 MatrixGenerator 造矩阵，后端用 Plotting 出图，用于解释癌症样本里“哪种致突变过程造成了哪些突变、占了多少份额”。

8. [HTML 颜色代码选择器](https://html-color-codes.info/chinese/ "HTML 颜色代码选择器")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251009170551.png)

为科研图表与论文配色的一站式工具：强大且用户友好的颜色选择器，探索和自定义 HTML 颜色代码。

9. [R 包 omixVizR 更新到 1.3.0 版本](https://leslie-lu.r-universe.dev/omixVizR "omixVizR")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251009170906.png)

R 包 omixVizR 更新到 1.3.0 版本，目前除了支持画 gwas 结果图，同时更新了对 Two-Stage Least Squares (2SLS) Mendelian Randomization analysis 的支持，以及相应结果的 forest plot 绘制。

## 资源

10. [R 语言入门教程](https://www.math.pku.edu.cn/teachers/lidf/docs/Rbook/html/_Rbook/index.html "R 语言入门教程")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251009171336.png)

该教程为《统计软件》等课程设置， 也可以用作《数据科学》的入门教材，包含从 R 语言基本语法到统计学习的深入概念。

11. [微软高分项目：一门教你从零开始构建AI代理的课程](https://github.com/microsoft/ai-agents-for-beginners "微软高分项目")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251009172337.png)

该课程包含关于构建 AI 代理基础知识的课程，每节课都包含代码示例以及继续学习的额外资源链接。

12. [生物科学“101计划”核心教材出版发行](https://mp.weixin.qq.com/s/fXn9XtfOMBC2vIMXvuSP6A)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/WeChatOfficialAccount/img_2025/20251009172617.png)

生物科学“101计划”由西湖大学校长施一公教授牵头，西湖大学作为牵头单位，联合全国32所生物科学拔尖学生培养基地所在高校共同实施。此次核心教材的发布，标志着“101计划”在生物科学领域迈出里程碑式步伐，更是我国自主培养生物科学拔尖人才的重要突破。其中，有《生物信息学》新教材。

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
