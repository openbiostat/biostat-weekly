# 生统爱好者周刊（第 43 期）：养老科技的最大增量市场不是80+，而是80后？

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260723224058.png)

## 本周话题：[养老科技的最大增量市场不是80+，而是80后？](https://mp.weixin.qq.com/s/gvFdr98gxXTCUt_nYolx_A)

颈椎退行性病变、焦虑失眠、代谢综合征——18到44岁群体的慢性病患病率正在加速攀升，2030年预计将超过30%。80后还没老，身体已经开始"提前养老"了。养老科技的最大增量市场，不在养老院，在80后的手机里。

## 生统研究

1. [Nature | 从348种疾病中提取21条生命轨迹，AI能否重新定义疾病分类？](https://mp.weixin.qq.com/s/ODzQp6t6PxcbTFWXfTYNJA)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260723224422.png)

两个人最后进入同一个诊断框，却未必沿着同一条生物学路径走到这里。电子健康记录本来保留了这种差异：疾病在什么年龄出现，哪些诊断先发生，哪些疾病长期共存，新诊断出现后风险如何改变。然而，常见分析方法往往把每种疾病单独拿出来建模，心梗预测心梗，乳腺癌预测乳腺癌，糖尿病预测糖尿病。一个人几十年间不断交织的多种疾病，由此被拆成了一组彼此独立的标签。

来自麻省总医院、哈佛医学院、Broad研究所、Dana-Farber癌症研究所等机构的研究团队，由 Sarah M. Urbut、Alexander Gusev、Pradeep Natarajan 和 Giovanni Parmigiani 担任通信作者，在 Nature 发表了题为 “A Bayesian framework for longitudinal EHR and genetic discovery” 的研究。团队开发了一个名为 ALADYNOULLI 的贝叶斯生成模型，把纵向电子健康记录、年龄变化和遗传风险放入同一个框架中，试图恢复隐藏在诊断代码背后的疾病组合及其随时间变化的轨迹。

研究覆盖英国生物样本库、Mass General Brigham Biobank和美国All of Us三个独立队列，总样本量超过68.3万人，最长随访达到52年，共纳入348种疾病。模型最终识别出21个潜在疾病特征，其中20个对应相对明确的疾病过程，另一个用于描述低发病状态。

- 论文 DOI：10.1038/s41586-026-10780-5

2. [Nature ｜ 大语言模型能预测社会科学实验结果，但会系统性高估效应](https://mp.weixin.qq.com/s/2UrXBTc5jok0GeSfv5qFLw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260723225254.png)

社会科学最核心的问题之一，是因果。一段公共卫生信息能不能提高疫苗接种意愿？一种政治沟通方式会不会减少党派敌意？某个社会政策框架会不会改变公众支持度？这些问题不能只靠直觉回答，通常需要随机实验：把不同人随机分到不同条件，再比较他们的态度、选择或行为有没有变化。

现在，一个新问题出现了：大语言模型能不能先替我们“预演”实验？不是简单问模型“你觉得这个实验会怎样”，而是把它当作很多虚拟参与者，让它根据不同人口学背景、不同实验材料和不同结果问题，模拟人类在每个条件下会怎么回答。随后再像分析真实实验一样，比较模拟回答中的 treatment effect。真正需要检验的是：这些由 LLM 生成的实验效应，和真实人类实验效应到底有多接近？

来自 Harvard University Department of Psychology、Stanford University Department of Sociology 和 Transluce 的 Ashwini Ashokkumar、Luke Hewitt、Isaias Ghezae 和 Robb Willer，在Nature发表了题为Large language models can predict the results of social science experiments的研究。

- 论文 DOI：10.1038/s41586-026-10742-x

## 博文资讯

3. [OpenAI新模型能碾压爱因斯坦，但不如一个会举手提问的小学生？](https://mp.weixin.qq.com/s/CT-_Kv-h43xR2eWhKcsB3Q)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260723225656.png)

以前我们总是担心AI会失控，什么天网觉醒，产生自主意识，然后消灭人类。但现实版的“失控”，比这朴素太多了，没有那么多弯弯绕绕，不过这只是开始。

AI可能不会产生自主意识，不过当它那颗能碾压爱因斯坦的大脑，只能认真干活的时候，可能就已经是最危险的事了。网上有句梗叫“不怕坏人绞尽脑汁，就怕蠢人灵机一动”。AI正好相反，它虽然没想害人，但它在“绞尽脑汁”完成任务时没有“灵机一动”，可能最后咱们得给它擦屁股。

4. [《柳叶刀》：过去十年青少年肥胖及心理健康问题持续攀升](https://mp.weixin.qq.com/s/Y3TpKxv2haHlk3N_-FzI9Q)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260723225829.png)

5月21日，《柳叶刀》发布第二版《柳叶刀》青少年健康重大报告。报告指出，过去十年，青少年健康与福祉的进展喜忧参半且不均衡，其中，肥胖及心理健康等问题持续升高。若不采取有针对性的行动，到2030年全球仍将有超过10亿的青少年生活在条件堪忧的环境中。

## 工具

5. [Python绘制带显著性标注的Spearman相关森林图](https://mp.weixin.qq.com/s/POk_9OB3jknkIDIm7p4Hyw)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260723230024.png)

教程以肺癌临床数据为例，利用Python构建相关系数森林图，结合分组配色、零值基准线、特征标签与显著性标记展示变量关联方向及强度。该模块化绘图流程适用于生物统计中相关性分析结果的规范化可视化。

6. [R语言SCI组合图：模型结果与多维数据可视化模板](https://mp.weixin.qq.com/s/vjfgliI2HNH9t9uZbky8NQ)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260723230351.png)

教程整合Sankey地图、GLMM优势比、瀑布图、特殊热图、分裂小提琴图与PCA等9类图形，覆盖分层模型、组间比较、降维及生态空间数据展示。内容强调依据数据结构选择图形，并通过模块化拼图提升复杂统计结果的可读性。

## 资源

7. [Nature Portfolio临床医学期刊：影响力指标与学科布局概览](https://mp.weixin.qq.com/s/SpYJkLMRzEzWmuJu2W8WRg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20260723230516.png)

文章汇总Nature Portfolio临床医学及综述期刊的2025年影响因子、学科排名、引用与下载数据，覆盖肿瘤、心血管、消化、肾脏及精神卫生等领域。该信息可为科研人员进行期刊定位、文献检索和投稿策略制定提供参考。

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
