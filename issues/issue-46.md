# 生统爱好者周刊（第 46 期）：同济大学取消"长聘制"：激发活力还是制造焦虑？

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub:
[openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交
issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260814002631.png)

## 本周话题：[同济大学取消“长聘制”：激发活力还是制造焦虑？](https://mp.weixin.qq.com/s/-4LmkhhrhG5j3iV93-C4Mg)

同济大学此次人事制度调整，却与淡化"非升即走"相反。学校一方面保留青年教师预聘期"非升即走"的严格考核；另一方面加强长聘教师考核，推行3年中期评估、6年聘期总考核，考核不合格将面临薪酬调整、岗位调整。随着学校不再新增长聘岗位，传统"预聘+长聘"制度框架实质上被弱化，甚至可能无疾而终。

## 生统研究

1. [Lancet \| 全球抑郁症综述](https://mp.weixin.qq.com/s/XO28Hj0DoHNg8NI9w2LwPA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260813235909.png)

2026年抑郁症专题综述系统梳理了抑郁症的全球疾病负担、流行病学特征、发病机制、诊断与分层治疗路径。文章强调抑郁症是由生物、心理与社会因素共同作用的复杂疾病，需结合临床评估而非单靠量表确诊，并依据严重程度整合心理教育、生活方式干预、心理治疗、药物及必要的物理治疗。综述同时关注数字心理干预、氯胺酮、神经类固醇及致幻剂等新兴疗法，体现了抑郁症管理从单一治疗向长期、个体化和多模式干预的发展趋势。

- 论文 DOI：10.1016/S0140-6736(26)00201-1

2. [Nature Protocols \|
   医学AI使用指南](https://mp.weixin.qq.com/s/Ov-OI2ge7FNVRdDevSXHDw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260814000331.png)

Nature
Protocols发表了医学大语言模型应用教程，为医学研究者构建了从任务定义、模型选择、提示工程、模型微调到临床部署的完整研究框架。文章强调，医学AI研究不应停留于比较模型答题准确率，而应围绕具体临床场景系统评价其可复现性、安全性、公平性与实际效益。同时介绍RAG、工具调用和微调等策略，并指出模型进入临床后仍需持续监测与再验证，推动医学AI研究从"模型性能"真正转向"临床价值"。

- 论文 DOI：10.1038/s41596-026-01408-z

## 博文资讯

3. [脑网络也有'省力区'吗？结构如何塑造计算成本](https://mp.weixin.qq.com/s/2b1GjhxGEaKtRzmwUEd0Zg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260814000533.png)

Kulkarni 等在2026年提出了计算可供性地图（computational affordance
landscape）框架。研究借助网络控制理论，将脑网络完成不同活动状态转换所需的最小输入成本进行量化，从而解释网络结构如何塑造其"更容易完成哪些计算"。作者在果蝇神经环路、人类结构连接组和人工
RNN
中进行验证，发现连接结构、输入位置及目标状态共同决定计算成本，并提示学习可能进一步重塑网络的低成本活动方向。

4. [AI for Science
   真正稀缺的，是"可信反馈"](https://mp.weixin.qq.com/s/kE8F9ZgH8eg5CyJ6OgIJFg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/a.png)

AI for Science
的核心瓶颈正从"生成候选"转向"生产可信反馈"。文章强调，真正有价值的科研自动化不是跑更多实验，而是建立可复现、可解释、能改变下一步决策的闭环反馈系统。随着
AI
进入材料、药物等实体科学，竞争焦点将转向谁能更低成本地完成执行、测量、解释与证据复核。

## 工具

5. [动态潜在类别结构方程模型DLCSEM](https://github.com/PsychometricsMZ/dsem_tutorial "DLCSEM")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/b.png)

DLCSEM（动态潜在类别结构方程模型）是一种面向密集纵向数据的动态建模方法，将 DSEM
与潜在状态切换结合，可同时刻画个体内时间变化、个体间异质性及潜在状态随时间的转换。该教程提供从
CFA、时间序列、MLM、DSEM 到 DLCSEM 的渐进式学习路径，并配套 R、JAGS/Stan
可复现代码，适合学习复杂心理与健康纵向数据分析。

6. [伞状综述metaumbrella包](https://cran.r-project.org/web/packages/metaumbrella/index.html "metaumbrella")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/c.png)

metaumbrella 是专为伞状综述（umbrella review）设计的 R 包，可自动完成多组 Meta
分析、异质性与发表偏倚等检验，并依据预设或自定义标准进行证据分级，同时生成森林图。支持
OR、RR、HR、SMD 等多种效应量，适合伞状综述的标准化统计分析与证据整合。

## 资源

7. [Anatomy
   Atelier交互式3D人体解剖学习平台](https://anatomyatelier.vercel.app/en "Anatomy Atelier")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/d.png)

Anatomy Atelier 是一个以艺术化视觉学习与交互式 3D
解剖为核心的人体解剖学习平台。用户可旋转、缩放、分层和剖切器官模型，并结合结构标注、功能动画、组织学、临床疾病及器官比较学习，适合医学学习者进行直观的解剖结构理解与复习。

8. [Think系列图书在线阅读平台](https://greenteapress.com/wp/ "Think系列图书在线阅读平台")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/e.png)

Green Tea Press 是由 Allen B. Downey
创建的开放学习资源平台，提供可免费阅读和再利用的编程、统计与数据科学教材。内容涵盖
Python、贝叶斯统计、探索性数据分析、复杂系统、模拟建模及信号处理等，并配套
Jupyter Notebook、代码与练习，适合自学数据科学和计算方法。

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
