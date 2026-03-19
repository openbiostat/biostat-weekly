# 生统爱好者周刊（第 25 期）：arXiv变天：将脱离康奈尔大学独立

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260319214700.png)

## 本周话题：[arXiv变天：将脱离康奈尔大学独立](https://mp.weixin.qq.com/s/62QUkMnZlJOlj19ym92QlA)

最近，arXiv 发布了一个官方信息，称「经过与康奈尔大学数十年富有成效的合作，并在西蒙斯基金会的支持下，arXiv 正转型为独立的非营利组织，这也标志着这个开创开放获取科学先河的平台，迈入了其 35 年发展历程的全新阶段。」。作为整个 AI、物理、数学等硬核科技圈赖以生存的「基础设施」，arXiv 的这次转身无疑将深远地影响未来学术交流的走向。

## 生统研究

1. [BMJ | GLP-1受体激动剂：降糖神药竟成"戒瘾利器"？](https://mp.weixin.qq.com/s/xbcSffrDYQlao-9oYLdCuw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260319215016.png)

前几天，国际权威医学期刊《英国医学杂志》（BMJ）新上线发表了一项规模空前的真实世界研究——来自美国退伍军人健康系统的60余万例2型糖尿病患者数据显示，这类原本用于降糖减肥的药物，可能与降低酒精、尼古丁及阿片类药物成瘾风险存在显著关联。这一发现不仅挑战了我们对代谢性疾病治疗药物的认知边界，更为全球范围内日益严峻的物质成瘾公共卫生危机提供了全新的干预思路。

- 论文 DOI：10.1136/bmj-2025-086886

2. [Lancet | 与正常体重人群相比，肥胖人群面临的严重感染风险高出70%](https://mp.weixin.qq.com/s/fC76mvQX1zBfoiXv4vNdCw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260319215312.png)

《柳叶刀》（The Lancet）发表一项研究，探索肥胖与严重感染性疾病之间的关联。与BMI处于18.5至24.9的健康人群相比，肥胖人群因各类感染性疾病住院或死亡的风险增加70%，重度肥胖人群所面临的风险是健康群体的三倍。肥胖会显著增加因流感、肺炎、肠胃炎、尿路感染以及呼吸道感染等多种感染性疾病住院或死亡的风险。2023年全球估计每十例感染相关死亡中就有一例或与肥胖相关。作者提示，随着全球肥胖率持续上升，未来数十年间与肥胖相关的严重感染病例数将日益严峻。

- 论文 DOI：10.1016/S0140-6736(25)02474-2

## 博文资讯

3. [中南大学湘雅医院一失联研究生坠江离世，联合调查组发布情况通报](https://mp.weixin.qq.com/s/MuoStxVfbnbhVazyr38mdg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260319215452.png)

3月16日，湖南省卫健委网站发布联合调查组情况通报：2026年3月14日21时57分，中南大学湘雅医院2023级研究生孙同学离开宿舍后失联。学校立即组织力量寻找并请求警方帮助，同时与学生家属保持联系。23时26分，医院接警方通告，在橘子洲大桥发现有人坠江并正组织专业力量全力搜救。15日16时许，坠江者被打捞上岸，已无生命体征，经确认，为失联的孙同学。对该同学的不幸离世，我们深感哀痛和惋惜,将协助家属做好善后工作。目前，中南大学和湖南省卫生健康委已成立联合调查组，对网传相关情况依规依纪依法开展调查。

4. [唐纳德·O·赫布](https://en.wikipedia.org/wiki/Donald_O._Hebb "Donald O. Hebb")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260319215614.png)

Donald O. Hebb（唐纳德·O·赫布，1904–1985） 是加拿大心理学家与神经科学家，被誉为神经科学与学习理论的奠基人之一。他最著名的贡献是提出了后来被称为 “赫布学习法则（Hebbian learning）” 的思想，对神经科学、心理学以及现代人工智能产生了深远影响。20 世纪上半叶，心理学与神经科学面临一个核心困惑：学习和记忆究竟如何在大脑中实现？赫布首次尝试用神经元层面的机制，解释行为变化与学习现象之间的联系。今天看到的很多 AI 学习规则，本质上都是：“赫布法则 + 数学化 + 工程化”。

## 工具

5. [conflicted 包](https://conflicted.r-lib.org/ "conflicted 包")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260319215740.png)

conflicted 是一个旨在解决 R 语言中函数命名冲突（naming conflicts）问题的 R 包。它的作用是让函数名冲突变得显式且可控。当检测到函数名冲突时，conflicted 不会根据加载顺序自动选择，而是直接报错，迫使用户做出明确选择。它提供了 conflict_prefer() 等函数，让你在代码中显式指定在出现冲突时优先使用哪个包的函数（例如：conflict_prefer("filter", "dplyr")）。通过强制显式声明，它大大提高了 R 代码的健壮性、可读性和可重复性。

6. [bcftools](https://samtools.github.io/bcftools/bcftools.html "bcftools")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260319220111.png)

bcftools 是一个用于处理 VCF / BCF 变异数据的高性能命令行工具集，由 Wellcome Sanger Institute 开发与维护，是 HTSlib / samtools / bcftools 这一基因组学工具链中的核心成员。bcftools 是“变异数据层面”的瑞士军刀，是 WGS / WES / GWAS 流水线中不可或缺的底层工具。bcftools 专门处理已经完成比对和变异检测之后的数据，它不负责比对、不负责变异检测，而是负责：“如何高效、准确地管理和操控变异结果”。

## 资源

7. [OpenClaw中文教程项目](https://mp.weixin.qq.com/s/Tr5CyZSDutnqKFWRRxTkgg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260319220231.png)

Datawhale首个系统性的龙虾开源教程，设计了四条路径，从零开始，领养、成长你的 AI 龙虾🦞。

8. [西湖AI公开课《自然语言处理》](https://mp.weixin.qq.com/s/0z_cz2GzTr6kmwWmMDL8Bw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260319220334.png)

张岳教授于 2003 年获得清华大学计算机科学本科学位， 2009 年获得牛津大学计算机科学博士学位，随后在剑桥大学从事博士后研究工作。在加入西湖大学后，专注于自然语言处理、文本挖掘、机器学习和人工智能方向。由张岳主讲，全新版本《自然语言处理》公开课正式上新。作为 NLP 领域的入门课，在学习完后， 你能够掌握这个领域的数学和算法原理，可以去阅读最前沿的论文理解，可以去设计最前沿的创新算法。

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
