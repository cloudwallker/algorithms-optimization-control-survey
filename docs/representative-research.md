# 代表与前沿研究

核验截止2026-10-02。共10项代表材料；前五项建立概念，后五项对应2024–2026研究。近似理论与学习控制分开阅读，不将经验性能、近似比、遗憾界和收敛速度合并排名。这里的正式发表依据为会议/作者或出版页，预印本只标预印本状态。

|材料|时间与状态|方法入口|可核验来源与阅读边界|
|---|---|---|---|
|Submodular Function Maximization，Krause/Golovin|2014，Tractability教材章节|次模、单调、不同约束与预言机；先理解例子|[出版章节](https://www.cambridge.org/core/books/abs/tractability/submodular-function-maximization/C1925D301CBF7D7BBC55E44644A1ABA1)，经典概念资料|
|Online Convex Programming，Zinkevich|2003，ICML/技术报告|投影梯度和静态遗憾；读定义与基础定理|[作者机构全文](https://www.cs.cmu.edu/~maz/publications/techconvex.pdf)，无需把定理套到非凸深网|
|Introduction to Online Convex Optimization，Hazan|arXiv版本2019-09-11；书籍后续版2022|系统补凸性、遗憾、强凸与反馈|[原稿](https://arxiv.org/abs/1909.05207)，与[出版社书版](https://mitpress.mit.edu/9780262046985/introduction-to-online-convex-optimization/)分版本|
|Playing Atari with Deep Reinforcement Learning，Mnih等|2013-12-19，预印本/研讨会研究|像素输入、价值学习与经验回放|[原文](https://arxiv.org/abs/1312.5602)，不是2015 Nature正式DQN论文的同一版本|
|Digital-Twin-Enabled 6G，Khan等|2021-02-24预印本，架构研究|把在线决策放入系统上下文，辅助理解控制约束|[原文](https://arxiv.org/abs/2102.12169)，跨领域背景而非算法证明教材|
|Constant Approximation for Weighted Nash Social Welfare，R100，张瑞龙等|首投2024-11-05；STOC2025；v3修订2025-11-04|配置LP、大小物品与负相关舍入|[arXiv](https://arxiv.org/abs/2411.02942)，已读公开作者稿第1–3页，完整常数分析还需继续|
|Fair Submodular Maximization over a Knapsack Constraint，R098|IJCAI2025正式论文|严格预算与公平约束，常数颜色和期望约束分开|[正式会议页](https://www.ijcai.org/proceedings/2025/438)，已读所读作者稿第1–3页，短版部分证明另见长版|
|Logarithmic Approximations for Fair k-Set Selection，R097|IJCAI2025正式论文；预印本2025-05-20|二部图、最大负担、LP舍入与结构可解性|[正式会议页](https://www.ijcai.org/proceedings/2025/439)，所读作者稿第1–3页，定义与扩展以具体版本为准|
|Nash Social Welfare with Submodular Valuations: Approximation Algorithms and Integrality Gaps，R102|2025-04-13首投；v3为2025-11-05预印本版本|改进分离与多重图舍入、整数间隙|[v3](https://arxiv.org/abs/2504.09669v3)，注明重大更新及修复早期错误；未另核验正式会议刊载|
|Stackelberg Coupling of Online Representation Learning and Reinforcement Learning，R151，李韬等|arXiv首投2025-08-10；ICLR2026正式PDF可检索|表示与价值学习的双时间尺度博弈耦合|[arXiv v3全文](https://arxiv.org/pdf/2508.07452v3)；[ICLR论文入口](https://openreview.net/pdf/bec23c33a750a5296200730bbf12e372cc786c35.pdf)，方法阅读采用2026-01-28 v3|

## 不宜遗漏的核验事项

R100的常数近似和R102 v3的3.56+ε是不同研究与版本；不能将较新比率归入较早论文。R102同时研究整数间隙；某个LP的整数间隙是该松弛的限制，不能直接改写成所有算法都达不到的复杂度下界。

SCORER初版与正式版对领导方的表述不同。正式版检索页与初版的对照已经提示风险；本篇没有把两版公式拼接。继续精读应以正式版为主，记录策略、表示更新谁快谁慢、目标函数和最佳响应定义。

[R103作者稿](https://scholars.cityu.edu.hk/ws/portalfiles/portal/305976370/288416487.pdf)封面明确INFORMS Journal on Computing 38(2):377–396、2026-03-01；2025-04-03为资料记录的较早日期，正式引用应进一步核对在线发表记录，正式引用可核对[CityU出版记录](https://scholars.cityu.edu.hk/en/publications/scheduling-with-calibrations-for-multi-interval-jobs/)。它是组合调度的后续入口，本篇未将其完整算法视为已精读。

李韬2026 O-RAN延迟反馈、非可分分布式在线凸优化及2025 LQR元优化在[作者出版页](https://taoli-nyu.github.io/publications/)有记录，已核验直接来源与部分公开全文。具体版本和阅读范围见补充卡，本篇不把作者简介当作证明细节。2026记录存在年份但无日级日期时，不人为补具体月份。

## 可以提出的研究假设

预测辅助公平选择：同时要求误差大时资源可行、误差小时质量提高，需要明确定义误差量和基线。反馈延迟下的表示控制耦合：需要把延迟带来的梯度陈旧性与原有双时间尺度区分。以上均为待研究假设，可用于研究讨论，不能写成已发现定理。

## 相关研究补充（2026-10-02）

本表列出直接论文来源与版本状态；首次预印本、在线发表和正式卷期分别记录。

| 论文 | 已核验来源 | 发表与版本状态 | 阅读依据 |
|---|---|---|---|
| [Region-Level Policy Optimization for Fine-grained MLLM Perception](../papers/P051.md) | [直接来源](<https://arxiv.org/abs/2609.19745v1>) | 已核 arXiv 预印本；官方摘要页未见会议/期刊发表声明，本次未确认正式发表。 | fulltext |
| [Q-Zoom: Query-Aware Adaptive Perception for Efficient Multimodal Large Language Models](../papers/P059.md) | [直接来源](<https://arxiv.org/abs/2604.06912v1>) | 已核 arXiv 预印本；官方摘要页未见会议/期刊发表声明，本次未确认正式发表。 | fulltext |
| [VSSD: Vision Mamba with Non-Causal State Space Duality](../papers/P078.md) | [直接来源](<https://arxiv.org/abs/2407.18559v2>) | CVF 官方 proceedings：ICCV 2025，10819–10829，2025-10；另保存 arXiv v2（2024-08-04）。 | fulltext |
| [Distributed Online Convex Optimization With Nonseparable Costs and Constraints](../papers/P145.md) | [直接来源](<https://arxiv.org/abs/2602.10452>) | IEEE Control Systems Letters正式期刊，2026-05-25在线，卷10页391–396；arxiv首发2026-02-11。 | fulltext |
| [Stackelberg Coupling of Online Representation Learning and Reinforcement Learning](../papers/P146.md) | [直接来源](<https://arxiv.org/abs/2508.07452>) | ICLR2026会议论文；arxiv首发2025-08-10，所读v3更新2026-01-28。 | fulltext |
| [Multi-level traffic-responsive tilt camera surveillance through predictive correlated online learning](../papers/P153.md) | [直接来源](<https://arxiv.org/abs/2408.02208>) | Transportation Research Part C正式2024-10卷167文章104804；arxiv首发2024-08-05。 | fulltext |
