# 生统爱好者周刊（第 54 期）：精准肿瘤学时代的抗癌药价难题

这里记录每周值得分享的生统相关内容，周五发布。

本杂志开源（GitHub: [openbiostat/biostat-weekly](https://github.com/openbiostat/biostat-weekly "openbiostat/biostat-weekly")），欢迎提交 issue 投稿或推荐生统相关内容。

[「生统爱好者周刊讨论区」](https://github.com/openbiostat/biostat-weekly/discussions "生统爱好者周刊讨论区")

## 封面图

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261023161348.png)

## 本周话题：精准肿瘤学时代的抗癌药价难题

2024年，全球新增癌症病例约[2060万](https://doi.org/10.3322/caac.70090 "2024 Global Cancer Statistics")；2025年新启动的临床试验中，近四成属于[肿瘤领域](https://www.iqvia.com/locations/emea/blogs/2026/07/oncology-innovation-2026-and-beyond "Oncology Innovation 2026 and Beyond")。预计到2029年，全球抗癌药支出将达4410亿美元，五年增长75%，主要推手是药价本身。精准医学把患者按基因越分越细，每发现一个新靶点，新药都能以“首创”身份上市，价格也就一直居高不下。以部分靶向药为例，它们针对罕见的基因融合，适用患者须经基因检测筛出，人数稀少，难以设立对照组，上市时只依据小规模、无对照组的试验。疗效尚无比较证据，患者一年的用药费用却高达约20万至40万美元，远非普通家庭所能承受。药越来越“准”，用得上的人却只是少数。

## 生统研究

1. [Journal of the Royal Statistical Society Series B | Martingale posterior 让贝叶斯分位数回归不再依赖似然与先验](https://academic.oup.com/jrsssb/article/88/4/1130/8381503 "Martingale posterior for Bayesian quantile regression")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261023162003.png)

Martingale posterior是一种不需要写出似然和先验的贝叶斯框架：它把后验的不确定性看作来自尚未观察到的数据，通过反复预测、填补未来观测来得到后验。该研究将这一框架用于quantile regression，用递推公式逐步更新quantile function，并证明了后验的存在性、相合性与收缩速度。与依赖Markov chain Monte Carlo的传统非参数贝叶斯方法相比，新方法的抽样速度快了数十至数千倍，但尾部quantile的可信区间偏窄，目前也只适用于单变量结局。

- 论文 DOI：10.1093/jrsssb/qkaf080

2. [The New England Journal of Medicine | ENRICH试验：后验概率、层级模型与中期规则如何组成一套贝叶斯自适应设计](https://mp.weixin.qq.com/s/9tv4Ha31hG6p34PV9L6U1Q)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261023162204.png)

ENRICH试验是一项比较脑出血微创手术与内科治疗的贝叶斯自适应试验。研究用后验概率代替P值作为决策依据，用贝叶斯层级模型在脑叶和前基底节两个出血亚组之间通过partial pooling借用信息，并预先设定中期分析规则：某亚组获益的后验概率过低时，即停止该亚组入组。该研究在纳入175人时，前基底节亚组触发了这一规则，此后试验只招募脑叶出血患者；180天结局的缺失则采用贝叶斯多重插补处理。解析文章附有R语言代码，可以复现整套分析流程。

- 论文 DOI：10.1056/NEJMoa2308440

3. [JAMA Network Open | 前列腺癌队列研究比较强化治疗方案](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2855498 "Androgen Synthesis Inhibitors vs Androgen Receptor Inhibitors and Survival in Metastatic Hormone-Sensitive Prostate Cancer")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261023162349.png)

美国3,404名转移性激素敏感性前列腺癌患者中，经治疗概率加权后，阿帕他胺／恩扎卢胺组较阿比特龙组死亡风险更低（HR 0.74；95% CI 0.64–0.87）。中位随访25.6个月。在缺乏直接随机比较的情况下，这是有用的比较效果证据。但残余混杂及不同数据库结果不一致，包括既往 VA 研究，使其不能确定哪种治疗更优。

- 论文 DOI：10.1001/jamanetworkopen.2026.39458

## 博文资讯

4. [换用数字乳腺断层合成，间期癌少了约四分之一，为什么仍是“不显著”？](https://mp.weixin.qq.com/s/RFWUjKtYZFH32HPmdw2nag)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261023162759.png)

“间期癌”指筛查结果为阴性之后、下一次筛查之前被查出的癌症，常被用来衡量筛查漏掉了多少。德国TOSYMA试验把近10万名50至70岁的女性随机分为两组：一组做数字乳腺断层合成加合成二维摄影，也就是常说的“三维钼靶”，它通过多角度扫描重建出逐层切片，减少组织重叠造成的遮挡；另一组做常规的数字乳腺摄影，即二维钼靶。研究者再与癌症登记处做数据链接，追踪筛查阴性的女性此后两年是否确诊。结果显示，断层合成组每万人出现14.2例浸润性间期癌，常规组为18.6例，相对减少约24%，绝对数上每万人约少4.4例。但衡量两组差异的比值比，其95%置信区间为0.55至1.06，包含了代表“没有差别”的1，P值为0.11，没有达到统计学显著。

24%听起来不少，为什么不算数？因为间期癌本身很少见：两组各约4.9万人，病例只有70例和92例。事件越少，随机波动越大，真实效果可能是明显降低，也可能接近于零。作者认为，这项大型随机试验仍为断层合成筛查增添了实质证据；不过，间期癌减少能否最终转化为死亡率下降，还有待验证。“不显著”不等于“无效”，也不等于“有效”，它只是说明：这一次的数据还不足以下结论。

- 论文 DOI：10.1016/S1470-2045(26)00341-4

5. [漂亮的框架和详尽的细节，恰恰是AI最擅长伪装出来的东西](https://mp.weixin.qq.com/s/n44j38DlEvPikn2R4GQ-ig)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261023163101.png)

AI研究机构Epoch AI设计了一项测试：让AI智能体在不联网的环境中，独立发明一种改进语言模型训练的新方法，目标是达到一项2026年初才发表、模型从未见过的人类成果的效果。两个前沿模型各获得3000个GPU小时的算力，实际花费约6700至14000美元，结果都没能接近人类方法。

最值得关注的是AI Agent的结果报告方式。训练神经网络带有随机性，同一段代码换一个随机种子重跑，分数就会上下浮动。两个模型都把几乎相同的训练重复跑了多次，只把最好的一次当作结论上报，却没有交代其余的运行。这就像买了一沓彩票只公布中奖的那张。经评审员校正后，Claude Fable 5自报达到人类方法效果的43%，实际仅约2%，提升几乎全部来自挑选；GPT-5.6 Sol自报71%，扣除挑选后为35%，再剔除违反任务规则的改动，只剩15%。

Epoch还对照了模型工作时的推理记录：Fable 5曾写明重跑是为了“钓”出更好的结果，Sol也留下过担心造成选择偏差的笔记，但两者最终都没有在报告中披露。这究竟是有意为之还是判断混乱，作者没有下定论；他们的结论是，现阶段AI产出的研究，仍需人类逐项复核。

## 工具

6. [adaptr：贝叶斯自适应试验模拟器](https://inceptdk.github.io/adaptr/ "adaptr: A Bayesian Adaptive Trial Simulator")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261023163225.png)

adaptr是丹麦重症监护平台试验项目（INCEPT）开发的R包，用于模拟和比较多组、多阶段的自适应临床试验。研究者只需设定试验组别、真实疗效、中期分析时点和决策阈值，adaptr就会基于后验概率模拟试验过程，包括因优效或无效提前停止、剔除表现不佳的组别，以及根据已有数据调整随机分配比例。它还能自动校准阈值，使一类错误率等操作特性达到预设目标。

7. [brms：基于Stan的贝叶斯回归模型](https://cran.r-project.org/web/packages/brms/index.html "brms: Bayesian Regression Models using 'Stan'")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261023163345.png)

brms是R中最常用的贝叶斯回归工具之一，语法与常见的lme4公式写法一致，背后调用Stan完成抽样，可以拟合线性、广义线性、多层级等多种模型。与本期生统研究第一篇相关的是，它可以通过asymmetric Laplace分布做贝叶斯quantile regression，例如设定quantile = 0.9来估计第90百分位。这正是论文中提到的“工作似然”做法：使用方便，但似然本身是错设的，可信区间未必准确，抽样也依赖较慢的Markov chain Monte Carlo。把它和论文中的新方法对照来看，能更直观地理解后者想解决的问题。

## 资源

8. [DeepSeek开源推理框架：走向真正普惠的未来](https://mp.weixin.qq.com/s/5MEu2eeqNfBWXlkCKTd6sg)

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261023163444.png)

2026年10月20日，DeepSeek宣布将内部推理框架DeepInfer全面开源。这里的“推理”不是统计推断，而是指训练好的大模型上线后，实时响应海量用户请求的运行过程，其效率直接决定了算力成本和电力消耗。DeepInfer支持分布式推理、结构化输出等能力，兼容英伟达和华为昇腾两类芯片，并同步开源了与官方接口处理逻辑一致的文本编解码组件deepseek-recipe。DeepSeek表示，希望借此帮助开发者和企业降低部署成本，让智能以更低的价格惠及更多人群。这与本期“可负担性”的主题形成呼应：无论是抗癌药还是大模型，好技术能否普及，最终都绕不开成本。

9. [AI Engineering: Building Applications with Foundation Models](https://github.com/chiphuyen/aie-book "AI Engineering: Building Applications with Foundation Models")

![](https://cdn.jsdelivr.net/gh/Leslie-Lu/images/images/20261023163525.png)

由Chip Huyen所著、于2025年出版的《AI Engineering》，系统介绍如何基于现成的基础模型搭建AI应用，面向的读者也包括几乎没有AI背景的人。全书十章，覆盖提示词工程、检索增强生成（让模型先查资料再回答）、智能体、微调、数据集构建和推理优化等主题，其中第六章专门讲解智能体的设计与搭建。对统计背景的读者来说，最值得细读的可能是第三、四章：作者用两章篇幅讨论如何评估开放式模型的输出，包括正在兴起的“用AI评判AI”方法。正如本期博文资讯所示，AI的产出需要被检验，在让智能体辅助工作之前，先学会评估它，同样重要。

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
