# NeurIPS 2026

检索窗口 2024-11-13 至 2026-11-13 内，与持续学习、终身学习或增量学习相关的 NeurIPS 2026 论文，共 97 篇。主会 97 篇，Findings 0 篇，Workshop 0 篇，其他 0 篇。

主会数字包含该会议的官方主会轨道；NeurIPS 的 Datasets and Benchmarks 单独成节，仍计入主会。Findings、Workshop、Industry、Student Abstract 与 Short 另行标注。

## 主会（92 篇）

### 1. A Mahalanobis Margin \texorpdfstring{$\gamma_{\min}$}{gamma\_min} Bound on Task Confusion in Pretrained Class-Incremental Learning: From Infeasibility to Exponential Attenuation

- **作者**：Milad Khademi Nori, Guanghui Wang
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=Yljy4oNHZD
- **关键词**：class-incremental, architecture / parameter isolation, catastrophic forgetting, foundation models, benchmark
- **摘要**：类增量学习存在结构性障碍：判别式顺序训练只优化成对损失矩阵的对角块，任务之间的任务混淆块并未被最小化。本文用马氏间隔 γ_min 界讨论预训练类增量学习中的任务混淆，涵盖从不可行性到指数衰减。

### 2. A Margin Perspective on LoRA: Robustness to Catastrophic Forgetting and Adapter Merging (MaLoRA)

- **作者**：Ziqing Xu, Hancheng Min, Lachlan MacDonald, Salma Tarmoun, Enrique Mallada, Weijie Su, Rene Vidal
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=8PbIL0Lq7v
- **关键词**：regularization, architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：LoRA 是大神经网络参数高效微调的常用方法，能以很少的可训练参数和较低优化代价完成任务适应。MaLoRA 从间隔视角讨论 LoRA 对灾难性遗忘和适配器合并的鲁棒性。

### 3. A Theoretical Bridge Between Long-Tailed Recognition and Continual Learning

- **作者**：Mahdiyar Molahasani, Michael Greenspan, Ali Etemad
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=wERJT1NgQB
- **关键词**：architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：CLTR 把长尾识别与持续学习联系起来，用现成的持续学习方法顺序学习头部类与尾部类，并缓解灾难性遗忘。

### 4. AgentOdyssey: Open-Ended Long-Horizon Text Game Generation for Test-Time Continual Learning Agents

- **作者**：Zheyuan Zhang, Zehao Wen, Bowei Zhang, Andrew Wang, Jianwen Xie, Daniel Khashabi, Tianmin Shu
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=uNezciDNHb
- **关键词**：architecture / parameter isolation
- **摘要**：AgentOdyssey 用程序化方式生成包含丰富实体、世界动态和长程任务的开放式文本游戏，用以评测测试时持续学习智能体。

### 5. ALIGN-Rec: Continual Recommendation under Heterogeneous Unlearning Requests

- **作者**：Nitin Bisht, Sumit Bisht, Tong Zhang, Yu Yang, Huan Huo, Guandong Xu
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=L8dS5AKSwG
- **关键词**：benchmark
- **摘要**：ALIGN-Rec 是与具体模型无关的在线框架，用于在交错的学习请求与遗忘请求下进行持续推荐。

### 6. Anchoring Physiological Invariance, Expanding Domain Plasticity: Prior-Stabilized Dynamic Adaptation for Continual rPPG Measurement

- **作者**：Zhongtian He, Shuyang Chu, Jingang Shi
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=t9PpANJFJe
- **关键词**：graph, benchmark
- **摘要**：ApexPhys 是持续 rPPG 测量框架，同时锚定生理不变性并扩展域可塑性，采用先验稳定的动态适应。

### 7. Autonomous Continual Learning for Environment Adaptation of Computer-Use Agents

- **作者**：Tianci Xue, Zeyi Liao, Tianneng Shi, Zilu Wang, Kai Zhang, Dawn Song, Yu Su, Huan Sun
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=FHgXFf6vU1
- **关键词**：catastrophic forgetting
- **摘要**：ACuRL 是自主课程强化学习框架，在不使用人工数据的情况下，让计算机使用智能体持续适应特定环境。

### 8. Base Items Overfit, New Items Underfit: Hidden Cost of Joint Training in Incremental Adaptation

- **作者**：Rishabh Agrawal
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=0ianGd8N9W
- **关键词**：regularization, foundation models, benchmark
- **摘要**：针对增量适应中联合训练使基础条目过拟合、新条目欠拟合的问题，该文提出按群体划分的低秩子空间，用各自的共享投影矩阵参数化基础条目与新条目，从而解耦优化，并提供与数据可得量成比例的隐式正则。

### 9. Bayes-pFCL:Bayesian Personalized Federated Continual Learning

- **作者**：Qingyang Yu, Yang Hua, Hao Wang, Yue Ning, Qizhen Zhang, Hao Wang
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=qV1obunXod
- **关键词**：catastrophic forgetting, benchmark
- **摘要**：个性化联邦持续学习用于缓解跨任务的灾难性遗忘以及客户端之间的数据异构。Bayes-pFCL 从贝叶斯角度讨论个性化联邦持续学习。

### 10. Beyond Exemplar Selection: Value-Aware Memory Allocation in Replay-Based Continual Learning

- **作者**：Yuhang Li, Guoxu Zhou, Zhenhao Huang, Yuning Qiu, Qibin Zhao
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=3bHKdbo9Qx
- **关键词**：catastrophic forgetting
- **摘要**：回放用有界记忆缓冲区保存已见类别的样本，是缓解持续学习中灾难性遗忘的标准策略。本文把讨论从样本选择推进到回放式持续学习中的价值感知记忆分配。

### 11. C-LoRA: Continual Low-Rank Adaptation for Pre-trained Visual Models

- **作者**：Xin Zhang, Liang Bai, Xian Yang
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=nf0YHUKcRr
- **关键词**：architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：C-LoRA 让单一共享的 LoRA 适配器处理预训练视觉模型上的顺序任务，推理时不需要模块选择或融合，并避免灾难性遗忘。

### 12. CHAIN: Continual Heterogeneous Cooperation with Information Bottleneck for Multi-Agent Reinforcement Learning

- **作者**：Haowen Dou, Lujuan Dang, Badong Chen
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=4avjOdnj6s
- **关键词**：reinforcement learning, benchmark
- **摘要**：CHAIN 面向多智能体强化学习中的持续异构协作，采用信息瓶颈，并配备异构策略瓶颈 HPB。

### 13. Class-Domain Incremental Learning with Extensible Multi-Center Modeling

- **作者**：Xuetong Yang, Yuxiang Yan, Zhiyuan Zhou, Xin Gao, Guanghao Li, Jian Pu
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=L7nQuDA3fX
- **关键词**：domain-incremental, catastrophic forgetting, benchmark
- **摘要**：EMCift 用可扩展多中心建模和双路径漂移协调处理类域增量学习，把跨域与跨语义空间的异构数据视为共存的多视图观测。

### 14. Class-Incremental Learning via LoRA-based Elastic Ensemble of Experts

- **作者**：Ruilong Yu, Fei Ye, Zhiyuan Ren, Qihe Liu, Adrian G. Bors, Rongyao Hu, Shijie Zhou
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=5v1mhJ0DnN
- **关键词**：class-incremental, regularization, architecture / parameter isolation, benchmark
- **摘要**：E³ 是基于 LoRA 的弹性专家集成，作为参数高效框架用于类增量学习。

### 15. Class-Mixed Diffusion Augmentation for Shortcut-Breaking in Continual Learning

- **作者**：Abhinab Acharya, Dayou Yu, Qi Yu, Xumin Liu
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=GGcrbkuKF6
- **关键词**：class-incremental, exemplar-free
- **摘要**：CMDA 不仅把扩散模型用作以往任务的数据生成器，也把它用作受控生成器来挑战对捷径的依赖，从而在持续学习中打破捷径。

### 16. Combating Catastrophic Forgetting in Continual Domain Adaptation via Knowledge Recasting

- **作者**：Zijie Liu, Zhen Tan, Charles Fleming, Tianlong Chen
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=x28eNvC5gp
- **关键词**：catastrophic forgetting
- **摘要**：SST 是一种训练后框架，把新知识运送到模型已有的技能空间，通过知识重铸应对持续域适应中的灾难性遗忘。

### 17. COMET: Decoupled Distillation, Routing, and Capacity Control for Task-Agnostic Continual Vision--Language Learning

- **作者**：Seungyoon Woo, Keonhee Park, Gunhee Kim
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=RsE3HOXbTn
- **关键词**：distillation, benchmark
- **摘要**：COMET 以协作式混合专家迁移处理任务无关的持续视觉语言学习，并分别用解耦的蒸馏、路由和容量控制应对三类问题。

### 18. Concentrated Gradients Amplify Forgetting: Dominant-direction Projection for Continual Multimodal Learning

- **作者**：Chengxiang Huang, Haopeng Zhang, Yuzhe Han, Rui Dai, Kaikui Liu, Xiangxiang Chu, Piotr Koniusz
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=EF8TL6jlfw
- **关键词**：architecture / parameter isolation, catastrophic forgetting, continual fine-tuning, foundation models, benchmark
- **摘要**：DiGPro 维护近期梯度方向的短缓冲区，并用自适应秩选择提取其主导子空间，以主方向投影应对持续多模态学习中由梯度集中放大的遗忘。

### 19. Continual Learning in Modern Hopfield Networks with an Application to Diffusion Models

- **作者**：Ken Takeda, Masafumi Oizumi, Ryo Karakida
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=UyZlLEPgiU
- **关键词**：replay / rehearsal, foundation models
- **摘要**：该文把任务切换后 Hopfield 能量的上升定义为内在遗忘，并在现代 Hopfield 网络中讨论持续学习及其在扩散模型上的应用。

### 20. COVD: Continual Open-Vocabulary Object Detection with Novel Concept Injection

- **作者**：Yupeng Zhang, Ruize Han, Yuzhong Feng, Zixin Ren, Yuntong Tian, Liang Wan
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=4of16OWJXb
- **关键词**：benchmark
- **摘要**：COVD 让模型顺序学习新到达的概念组，同时保留已有概念和原有开放词汇知识，从而把持续开放词汇目标检测表述为新概念注入。

### 21. Cross-Domain Knowledge Separation and Positive Transmission for Noisy Domain Incremental Learning

- **作者**：Kunlun Xu, Zhengyuan Cai, Jiahuan Zhou
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=QpRuEc6Iem
- **关键词**：domain-incremental, architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：ST-Prompt 面向含噪域增量学习，进行跨域知识分离与正向传递。

### 22. Cross-Foundation Complementary Learning Systems for Continual Test-Time Adaptation in Open-Vocabulary Semantic Segmentation

- **作者**：Guan-Yu Chen, Wei-Hua Li, Huei-Fang Yang, Chu-Song Chen
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=vP6mCzbls0
- **关键词**：architecture / parameter isolation, test-time adaptation
- **摘要**：XF-CLS 是无源的开放词汇语义分割持续测试时适应框架，用跨基础模型的互补学习系统使轻量在线适应在长时程上保持稳定。

### 23. CTRL: Continual Test-Time Reinforcement Learning for Large Language Models

- **作者**：Chu Zhao, Enneng Yang
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=MBS7pBUFkB
- **关键词**：catastrophic forgetting, foundation models, reinforcement learning
- **摘要**：CTRL 面向大语言模型的持续测试时强化学习，用过程奖励模型 PRM 替代结果级投票，并以细粒度过程评分筛选高置信轨迹来抑制伪标签偏差。

### 24. Data-Free Reservoir Features for Efficient Long-Horizon Cold-Start Continual Learning

- **作者**：Augustinas Jučas, Yangchen Pan
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=D9TG2PKiJD
- **关键词**：class-incremental, exemplar-free
- **摘要**：CIRCLE 由改编自 BiRC2D 的固定双向二维储备池特征以及流式线性判别分析头构成，作为类增量分类器，用于无数据条件下的长时程冷启动持续学习。

### 25. Disentangling Optimization Geometry via Hierarchical Polar Adapters for Class-Incremental Learning

- **作者**：Dat Q Mac, Thanh Hai Dang, Duc-Trong Le, Quynh-Trang Pham Thi
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=FBAriogGVS
- **关键词**：class-incremental, architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：HiPo 受大脑多时间尺度巩固和频率感知记忆动态的启发，用分层极坐标适配器重新刻画神经知识的参数化与存储，以理清类增量学习中的优化几何。

### 26. Distance-Dependent Connectivity Shapes Continual Learning by Synaptic-Resource-Delimited Separation of Neural Dynamics

- **作者**：CHIU-CHANG CHENG, Ching-Lung Hsu, Ya-Ning Chang, Chao-Hung Wang
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=gyvtSJyA7P
- **关键词**：class-incremental, catastrophic forgetting, graph
- **摘要**：生物回路能够学习而不发生灾难性遗忘，但这种能力的结构基础仍不清楚。本文讨论距离依赖的连接如何通过突触资源所限定的神经动态分离来塑造持续学习。

### 27. Dual-Pronged LoRA: Achieving Near-Zero Forgetting and High-Performance Adaptation for MLLMs

- **作者**：Jingqi Ye, Haonan He, Minglei Li, Fujun Han, Tao Chen, Peng Ye
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=5NC3OefOsg
- **关键词**：architecture / parameter isolation, catastrophic forgetting, foundation models
- **摘要**：Dual-Pronged LoRA 是面向多模态大语言模型的微调框架，包含两个组件，目标是在保持高性能适应的同时把遗忘压到接近于零。

### 28. DyJR: Preserving Local Policy Plasticity in Reinforcement Learning with Verifiable Rewards via Dynamic Jensen-Shannon Replay

- **作者**：Long Li, Zhijian Zhou, Tianyi Wang, Weidi Xu, Zuming Huang, Wei Chu, Zhe Wang, Shirui Pan, Chao Qu, Yuan Qi
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=0Go4KDhkDw
- **关键词**：replay / rehearsal, regularization, foundation models, reinforcement learning
- **摘要**：DyJR 用来自近期轨迹的动态参考分布做 Jensen-Shannon 回放，作为一种正则框架，在带可验证奖励的强化学习中保持局部策略可塑性。

### 29. Dynamic Cross-Modal Prompt Generation for Multimodal Continual Instruction Tuning

- **作者**：Tao Hu, Da-Wei Zhou
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=aOCvDH4aTc
- **关键词**：architecture / parameter isolation, catastrophic forgetting, continual fine-tuning, foundation models, benchmark
- **摘要**：DRAPE 为多模态持续指令微调合成连续的、随实例变化的跨模态软提示。

### 30. Dynamical Adapter Fusion: Constructing A Global Adapter for Pre-Trained Model-based Class-Incremental Learning

- **作者**：RuiQi Liu, Boyu Diao, Zijia An, Runjie Shao, Feixiang Ge, Zhulin An, Fei Wang, Yongjun Xu
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=cs7cFJRYLj
- **关键词**：class-incremental, architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：DAF 通过动态适配器融合，为基于预训练模型的类增量学习构建单一且稳健的全局适配器。

### 31. Ergodic Risk Measures: Towards a Risk-Aware Foundation for Continual Reinforcement Learning

- **作者**：Juan Rojas, Chi-Guhn Lee
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=P7WboKVZGN
- **关键词**：reinforcement learning
- **摘要**：该文首次从风险感知决策的角度形式化处理持续强化学习，使智能体优化超越均值的长期表现度量，即遍历风险度量。

### 32. Estimating and Orthogonalizing Unknown Pre-training Gradients for Continual Fine-tuning of Large Language Models

- **作者**：Bing Wang, Changchun Li, Xin-Qiang Cai, Lin Y Wu, Ximing Li, Gang Niu, Masashi Sugiyama
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=RvsI4JyU2Q
- **关键词**：architecture / parameter isolation, catastrophic forgetting, continual fine-tuning, foundation models
- **摘要**：EoupCT 估计并正交化未知的预训练梯度，用于大语言模型的持续微调。

### 33. FedVaccine: Knowledge Recall after Spatial-Temporal Catastrophic Forgetting in Federated Continual Learning via Gradient-Based Vaccine

- **作者**：Hao Yu, Xin Yang, Boyang Fan, Xuemei Cao, Lingfei Ren, Hanlin Gu, Yang Liu, Qiang Yang
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=U1jzG8noWv
- **关键词**：catastrophic forgetting, benchmark
- **摘要**：FedVaccine 在联邦持续学习中允许遗忘，以便为新任务保持高可塑性，同时通过重学一个基于梯度的紧凑疫苗集合，召回经历时空灾难性遗忘后的旧知识。

### 34. FLAME: Adaptive Mixture-of-Experts for Continual Multimodal Multi-Task Learning

- **作者**：Xing Han, Shravan Chaudhari, Tanvi Ranade, Rama Chellappa, Suchi Saria
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=5NwsnKcAvg
- **关键词**：architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：FLAME 提出可扩展的自适应混合专家框架，支持在灵活的模态组合上进行多任务预训练和持续多模态多任务学习。

### 35. FOGO: Forgetting-aware Orthogonalization Optimizer

- **作者**：Toan Nguyen, Yang Liu, Trung Le, Celso De Melo, Flora Salim
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=QBkoiaQrV0
- **关键词**：continual fine-tuning
- **摘要**：FOGO 是可扩展的遗忘感知正交化优化器，在两种情形下持续检测并消除梯度干扰。

### 36. From Anti-Forgetting to Fast Adaptation: Continual Reinforcement Learning with World Models

- **作者**：Qiyang Zhou, Yuliang Cai, Peng Wang, Senquan Yi, Yanming Li, Haobo Fu, Li Shen
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=hoG3Hx7DHo
- **关键词**：replay / rehearsal, regularization, architecture / parameter isolation, catastrophic forgetting, reinforcement learning
- **摘要**：HERD 即视界自适应的精英回放与奖励分歧，用于带世界模型的持续强化学习。在如何学习这一侧，不确定性感知的奖励规划借助集成分歧来加快适应。

### 37. From Generic to Dedicated: A Novel Optimizer for Online Continual Learning

- **作者**：Yongyi Wu, Zheng Wang, Sen Lin
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=oReUobH6m9
- **关键词**：online continual learning, replay / rehearsal, regularization, catastrophic forgetting
- **摘要**：在线持续学习要求模型在严格的单次遍历约束下从非平稳数据流中学习，因此很容易发生灾难性遗忘。本文讨论如何从通用优化器转向面向该设定的专用优化器。

### 38. Geometry Conflict: Explaining and Controlling Forgetting in LLM Continual Post-Training

- **作者**：Yuanyi Wang, Yifan Yang, Su Lu, Yanggan Gu, Pengkai Wang, Wenjun Wang, Zhaoyi Yan, Congkai Xie, Jianmin Wu, Jialun Cao, Shing-Chi Cheung, Hongxia Yang
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=8EOfA3Wh07
- **关键词**：regularization, catastrophic forgetting, continual pretraining, foundation models
- **摘要**：GCWM 是无数据的更新整合方法，通过高斯 Wasserstein 重心构造共享的 Wasserstein 度量，并用几何冲突来门控几何感知的合并，以解释和控制大语言模型持续后训练中的遗忘。

### 39. Gram-Calibrated Anchoring for Class-Incremental Learning

- **作者**：Qi Zhu, Ziang Gan, Libao Zhang
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=wGCFSJasYK
- **关键词**：class-incremental, architecture / parameter isolation, benchmark
- **摘要**：GCA 把 Gram 校准锚定用于带预训练 Vision Transformer 的类增量学习。

### 40. Heterogeneity-aware Distillation for Federated Continual Learning

- **作者**：Gaozhuo Liu, Yichen Li, Xiuying Wang, Yulong Li, Chuang Zhao, Yankai Jiang, Imran Razzak
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=6F5SkPuDh3
- **关键词**：distillation, regularization
- **摘要**：Ha-FCL 用针对性的蒸馏策略处理联邦持续学习中的空间异构与时间异构。

### 41. Hidden Forgetting in Continual Multimodal Learning: When Accuracy Survives but Grounding Fails

- **作者**：Qianyu Chen, Canran Xiao, Runxuan Tang
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=MDf0kUD4oe
- **关键词**：foundation models
- **摘要**：多模态大语言模型需要持续适应不断变化的任务和领域，但标准持续学习指标主要检查旧答案是否仍然正确，很少考察多模态接地是否稳定。本文讨论准确率尚存而接地失败时的隐蔽遗忘。

### 42. HIDRA: Hierarchical Dual-Routing Attention for Replay-Free Lifelong Imitation Learning

- **作者**：Fanqi Yu, Matteo Tiezzi, Cigdem Beyan, Tommaso Apicella, Vittorio Murino
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=FIXDBNuA60
- **关键词**：regularization, architecture / parameter isolation, benchmark
- **摘要**：HIDRA 用分层双注意力把指令级专家检索与依赖上下文的细化解耦，作为无回放终身模仿学习中的结构化路由框架。

### 43. Hierarchical Semantic Tree Anchoring for CLIP-Based Class-Incremental Learning

- **作者**：Tao Hu, Lan Li, Zhenhao Wen, Da-Wei Zhou
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=sCUuF8mN4k
- **关键词**：class-incremental, catastrophic forgetting, benchmark
- **摘要**：HASTEN 利用语义结构锚定层次语义树，以稳定基于 CLIP 的类增量学习。

### 44. Hyperbolic Displacement-Constrained Adaptation for CLIP-Based Class-Incremental Learning

- **作者**：Quan Cheng, Zhenhao Wen, Lan Li, Da-Wei Zhou, Lijun Zhang
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=CHvh1192IA
- **关键词**：class-incremental, architecture / parameter isolation, catastrophic forgetting, foundation models, benchmark
- **摘要**：HDCA 把遗忘视为顺序适配器更新所引起的、不受控制的残差位移，并对基于 CLIP 的类增量学习施加双曲位移约束适应。

### 45. Improving Continual Video Instance Segmentation via Spatial-Temporal Balanced Mixture-of-Experts Adapters

- **作者**：Hao Fu, Sihao Liu, Hanbin Zhao, Jiahua Dong, Zhang Chao, Hui Qian
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=zpJp5PjRLP
- **关键词**：architecture / parameter isolation, catastrophic forgetting
- **摘要**：STEAM 用时空均衡的混合专家适配器改进持续视频实例分割。

### 46. InduceKV: Fixed-Footprint Continual Adaptation of Multimodal LLMs via Inducing KV Memories

- **作者**：Qianyu Chen, Ziteng Feng, Canran Xiao, Runxuan Tang
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=Jb8bv8eTGB
- **关键词**：task-incremental, domain-incremental, architecture / parameter isolation, continual fine-tuning, foundation models
- **摘要**：InduceKV 基于检索把选中的训练前缀存为可直接参与注意力的记忆项，其中包含冻结的检索键和可附加到模型上的紧凑逐层 KV 载荷，从而以固定足迹持续适应多模态大语言模型。

### 47. InTAct: Interval-based Task Activation Consolidation for Continual Learning

- **作者**：Patryk Krukowski, Jan Miksa, Piotr Helm, Jacek Tabor, Paweł Wawrzyński, Przemysław Spurek
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=1YkQOLXLUU
- **关键词**：domain-incremental, architecture / parameter isolation, benchmark
- **摘要**：InTAct 通过基于区间的任务激活巩固，在不冻结参数、也不保留历史数据的情况下，维持共享表示中的功能行为。

### 48. Learning Robust Representations for Defending White-Box Adversarial Attacks in Continual Learning

- **作者**：Yusen Chen, Fei Ye, Qihe Liu, Adrian G. Bors, Shijie Zhou
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=3KoSZdy13A
- **关键词**：regularization
- **摘要**：动态表示匹配 DRM 在每个任务内对齐干净特征分布与对抗特征分布，以缩小干净性能与鲁棒性之间的折中，从而学习能抵御持续学习中白盒对抗攻击的表示。

### 49. Lost or Hidden? A Concept-Level Forgetting in Supervised Continual Learning

- **作者**：Katarzyna Filus, Kamil Faber, Roberto Corizzo, Christopher Kanan
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=d06ZssFH8b
- **关键词**：catastrophic forgetting
- **摘要**：尽管已有大量方法缓解灾难性遗忘，该领域仍以性能为主，对遗忘在视觉模型表示空间中究竟对应什么了解有限。本文在监督持续学习中讨论概念层面的遗忘是丢失还是被隐藏。

### 50. Making LoRA Identifiable: Orthogonal Alignment for Continual Learning

- **作者**：Pratik Rakesh Singh, Mohammadi Zaki, Akash Saha, Aneesh Mukkamala, Pankaj Wasnik
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=6IGj3mpXfp
- **关键词**：architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：SOAR 分两阶段进行 Stiefel 优化与对齐旋转，使持续学习中的 LoRA 具有可辨识性。

### 51. MIST: Reliable Streaming Decision Trees for Online Class-Incremental Learning via McDiarmid Bound

- **作者**：Phu-Hoa Pham, Chi-Nguyen Tran, Phu-Quy Nguyen-Lam, Dao S Minh, Trung-Kiet Huynh, Long Tran-Thanh
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=YsDOcP6Vpb
- **关键词**：class-incremental, benchmark
- **摘要**：MIST 即 McDiarmid 增量流式树，用三个集成组件处理在线类增量学习中流式决策树的两类失效，其中之一是作为结构正则、且与 K 无关的紧 McDiarmid 置信半径，用于 Gini 划分。

### 52. Mitigating Asymmetric Boundary Encroachment in Continual Learning of Vision-Language Models

- **作者**：Mingfeng Li, Xinyang Chen, Xiucheng Li, Weili Guan, Liqiang Nie
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=luUDOdK0bX
- **关键词**：foundation models
- **摘要**：该文提出统一框架，以系统抑制视觉语言模型持续学习中的非对称边界侵入。

### 53. Modulating Merging Strengths via Joint Loss Estimation for LoRA-based Continual Learning

- **作者**：Kun Gu, De Cheng, Zhipeng Xu, Lingfeng He, Di Xu, Nannan Wang
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=zRXaWRbyGH
- **关键词**：architecture / parameter isolation, benchmark
- **摘要**：M²LE 通过联合损失估计调节基于 LoRA 的持续学习中的合并强度，由 Hessian 信息引导的自适应合并 HIM 与面向合并的任务模拟扰动 TSP 组成。

### 54. MoRe: Modular Representations for Principled Continual Representation Learning on Sequential Data

- **作者**：Jiaqi Sun, Boyang Sun, Rasmy M. H., Xiangchen Song, Kun Zhang
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=mXmO7UBPWK
- **关键词**：foundation models, benchmark
- **摘要**：MoRe 受人类大脑模块化组织的启发，在表示本身中识别模块性，而不是在架构层面分配模块，用于序列数据上的持续表示学习。

### 55. MT-CC: Multi-Group Temperature Scaling for Asymmetric Calibration Behavior in Class-Incremental Learning

- **作者**：Sungjun Yun, Yonghee Choi, Dong-Jun Han
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=vCft9tPVmL
- **关键词**：class-incremental, regularization
- **摘要**：MT-CC 用多组温度缩放做事后校准，处理类增量学习中置信度变化速率与另一变化速率不一致的非对称校准行为。

### 56. NADS: Navigator-Guided Data Selection for Mitigating Catastrophic Forgetting in Fine-Tuning

- **作者**：JIANHAO ZHANG, Ou Wu, Yi Du
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=uZIL1Rr7jG
- **关键词**：distillation, regularization, catastrophic forgetting, foundation models
- **摘要**：NADS 用导航器引导的数据选择来缓解大语言模型微调中的灾难性遗忘。

### 57. NeSyKC: Neurosymbolic Knowledge Compilation For Lifelong Learning Embodied Agents

- **作者**：Wonje Choi, Jooyoung Kim, Sera Choi, Younguk Song, Honguk Woo
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=0KyH3bbBjN
- **关键词**：architecture / parameter isolation, benchmark
- **摘要**：NeSyKC 通过共享符号表示，把陈述性知识的形成与向程序性知识的增量编译耦合起来，用于具身智能体的终身学习。

### 58. Not All Routing Drift Is Harmful: Trust-Region Projection for Class-Incremental Learning

- **作者**：Tae-Hwan Kim, Sung-Bae Cho
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=WklS219u5L
- **关键词**：class-incremental, architecture / parameter isolation, benchmark
- **摘要**：基于预训练模型的类增量学习越来越多地采用混合专家适配器，冻结主干并把输入选择性地路由到稀疏适配器子集。本文指出并非所有路由漂移都有害，并以信任域投影讨论这一类增量学习问题。

### 59. Not Every Image Teaches Vision: Visual-Necessity-Gated Continual Learning for Multimodal Large Language Models

- **作者**：Jiamu Xue, Haidong Kang, Wen Luo, Jubo Chen, Xuhao Guo
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=odMdim806d
- **关键词**：foundation models
- **摘要**：视觉必要性门控持续调优（VNG-CT）比较原图与反事实空图下的目标似然，估计每个样本对视觉证据的依赖，并据此对多模态大语言模型做路径感知的持续调优。

### 60. NoTA: Normalized Tensor Adaptation for Parameter-Efficient Continual Learning

- **作者**：Yunsong Deng, Yuning Qiu, Qibin Zhao, Guoxu Zhou
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=Rzivs8kzM2
- **关键词**：class-incremental, replay / rehearsal, architecture / parameter isolation, catastrophic forgetting
- **摘要**：归一化张量适配（NoTA）面向参数高效持续学习，并联合处理文中所指的两个方面。

### 61. On Neural Scaling Laws for Weather Emulation through Continual Training

- **作者**：Shashank Subramanian, Alexander Kiefer, Arnur Nigmetov, Amir Gholami, Dmitriy Morozov, Michael Mahoney
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=u9jpPYohUA
- **关键词**：foundation models, benchmark
- **摘要**：神经缩放律在一些领域能按模型、数据与算力规模预测大型神经网络的表现，是自然语言处理与计算机视觉里构建基础模型的基石。本文在通过持续训练做天气模拟的设定下讨论这类缩放律。

### 62. Out-of-Distribution Detection in Continual Learning

- **作者**：Nimeshika Udayangani Hewa Dehigahawattage, Sarah Erfani, Flora Salim, Christopher Leckie
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=tUbhxJCUrN
- **关键词**：replay / rehearsal, catastrophic forgetting
- **摘要**：本文为无回放持续学习提出一种分布外检测框架，思路来自 Kolmogorov–Arnold Networks（KAN）。KAN 依靠固有的局部神经可塑性缓解灾难性遗忘。

### 63. Overcoming Catastrophic Forgetting in Visual Continual Learning with Reinforcement Fine-Tuning

- **作者**：Meng Lou, Hanzhong Guo, Linwei Chen, Yizhou Yu
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=XQ0Bir2SLj
- **关键词**：class-incremental, domain-incremental, replay / rehearsal, architecture / parameter isolation, catastrophic forgetting, foundation models
- **摘要**：顾及保留的策略优化（RaPO）是一种强化微调框架，通过轨迹级奖励塑形显式缓解视觉持续学习中的遗忘。

### 64. PaLoRA: Paced Low-Rank Adaptation for Continual Learning

- **作者**：Yuxuan Li, Fanhu Zeng, Hao Tang
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=fU1XY23snF
- **关键词**：architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：PaLoRA 用自适应 SVD 截断压缩历史知识，把梯度投影到先前任务的零空间，并按秩感知地调节更新节奏。

### 65. Past, Future, All at Once: Breaking Stability-Plasticity Dilemma via Post-hoc JANUS Rectification

- **作者**：Zhilong Zheng, Letian Tao, Yang Guan, Yujie Yang, Wei Xiong, Kehua Sheng, Bo Zhang, Jingliang Duan, Keqiang Li, Shengbo Eben Li
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=amfBq5fDzv
- **关键词**：catastrophic forgetting, foundation models
- **摘要**：已有工作试图在参数高效微调的基础上缓解稳定性与可塑性的困境，但采用了过严的子空间正交条件。本文讨论用事后 JANUS 校正来打破这一困境。

### 66. PM-LoRA: Scalable Continual Learning via Progressive Merging of Low Rank Adapters

- **作者**：Xiaobing Yu, Peijie Qiu, Jin Yang, Xiaoqi Zhao, XUANZHAO DONG, Wenhui Zhu, Xiwen Chen, Weiwei Ma, Xiaofeng Liu, Jiangpeng He
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=HL68qRLWDM
- **关键词**：architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：渐进合并低秩适配器（PM-LoRA）是一个可扩展框架，用来同时处理文中所指的两方面问题。

### 67. Predicting Plasticity in Deep Continual Learning: A Theoretical Perspective

- **作者**：Jiuqi Wang, Jayanth Srinivasa, Claire Chen, Shuze Daniel Liu, Ali Payani, Shangtong Zhang
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=Z8JDztVnTJ
- **关键词**：continual learning
- **摘要**：深度持续学习要求模型适应新任务，而无需从头重新训练。本文从理论角度讨论如何预测这种可塑性。

### 68. Prototype Topology Consistency for Visible-Infrared Lifelong Person Re-Identification

- **作者**：Tan Shang, Zhijie Lu, Wuxuan Shi, He Li, Mang Ye
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=4fE0YqAObx
- **关键词**：benchmark
- **摘要**：可见光与红外两种模态会形成不一致的类间相似结构，常规跨模态监督无法消除，并在共享骨干的持续学习下表现为高度不对称的跨模态遗忘。本文围绕原型拓扑一致性讨论可见光–红外终身行人重识别。

### 69. Query as a Resource: Activity-Cost Guided Remote Sensing Domain-Incremental Object Detection

- **作者**：Xi Yang, Zhengyu Yuan, De Cheng, Nannan Wang
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=v4SMwpRLeM
- **关键词**：domain-incremental, regularization, architecture / parameter isolation, benchmark
- **摘要**：在把查询视为资源的视角下，本文提出由活动代价引导的 Q-cost，用于遥感领域增量目标检测。

### 70. Rehearsal-Free Statistical Prototype Regularization for Federated Incremental Learning

- **作者**：Xiuying Wang, Yichen Li, Jiahua Cheng, Xiwei Liu, Chuang Zhao, Bo Liu, Imran Razzak
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=v2AOJ4JiUk
- **关键词**：replay / rehearsal, distillation, regularization, catastrophic forgetting
- **摘要**：SPR-FIL 是面向联邦增量学习的无回放轻量框架，通过对统计原型施加正则来应对文中所指的挑战。

### 71. Revisiting Incremental Learning: A Three-Interface Diagnosis of Stability and Plasticity

- **作者**：Keuntae Kim, Beomseok Lee, Hyunwoo Kim, Yong Suk Choi
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=kX9Kbog4s6
- **关键词**：class-incremental, task-incremental, catastrophic forgetting
- **摘要**：增量学习通常只通过最终分类器或语言模型头来评估，但这一接口并不能表明遗忘发生在何处。本文从三个接口诊断稳定性与可塑性。

### 72. RIZZ: Routing Interactions to Near Zero-Interference Zones for Continual Adaptation of Black-Box Agents

- **作者**：Sonali Goel, Pranav Vaidhyanathan, Lucas Schorling, Natalia Ares, Michael A Osborne
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=laAYDZ8VQG
- **关键词**：architecture / parameter isolation, foundation models, graph, benchmark
- **摘要**：RIZZ 面向复合语言模型系统的持续适配，完全通过验证器门控的记忆、路由和提示编译来学习，把交互引导到近零干扰区域。

### 73. Robust and Efficient Continual Model Merging via Global Singular Subspace Separation and Restoration

- **作者**：Juncheol Shin, Byeongho Yu, Semin Kim, Eunhyeok Park
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=wdIBHsopRB
- **关键词**：continual learning
- **摘要**：全局奇异子空间分离与恢复（GS3R）是无数据、且能与优化过程兼容的持续模型合并框架。

### 74. Robust Policy Optimization to Prevent Catastrophic Forgetting

- **作者**：Mahdi Sabbaghi, George J. Pappas, Adel Javanmard, Hamed Hassani
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=fg8I6pwObp
- **关键词**：catastrophic forgetting, reinforcement learning
- **摘要**：为防止灾难性遗忘，多数已有工作在下游阶段设计方法，用来保留先前学到的行为。本文讨论强化学习设定下的稳健策略优化。

### 75. ROSE: Risk-Aware Orthogonal Subspace Navigation for Lifelong Knowledge Editing in Multimodal Large Language Models

- **作者**：Lingyun Song, Ziyao Chen, Kang Pan, Xiaolin Han, Yifei Zhang, Xiaoqi Wang, Yudai Pan, Xuequn Shang
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=7UwsQGxwFQ
- **关键词**：catastrophic forgetting, lifelong / continual model editing, foundation models, benchmark
- **摘要**：ROSE 是面向多模态大语言模型终身知识编辑的风险感知正交子空间导航框架。

### 76. Semantic Concept Steering Breaks the Explanation Drift Loop in Continual Learning

- **作者**：Yehonatan Elisha, Oren Barkan, Noam Koenigstein
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=i3RRjUpRUG
- **关键词**：regularization, catastrophic forgetting, benchmark
- **摘要**：概念一致持续学习（C³L）把正则锚定到离线发现、与模型状态无关且在类别上一致的语义概念，例如“弯曲的喙”和“条纹图案”，从而打断持续学习中的解释漂移循环。

### 77. Spectral Rank Calibration for Continual LoRA Merging in Multimodal Large Language Models

- **作者**：Chenrui Wu, Haishuai Wang, Jiajun Bu, Jiangchuan Liu
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=mZ9hN3hGTn
- **关键词**：architecture / parameter isolation, catastrophic forgetting, foundation models
- **摘要**：谱秩校准合并（SRC-Merging）是面向多模态大语言模型的持续 LoRA 合并方法，既不需要数据，也不需要训练。

### 78. STABLE: A Continual Learning Optimizer with Adaptive Drift Control

- **作者**：Xiaoyan Li, Lanpei Li, Massimo Coppola, Vincenzo Lomonaco, Antonio Carta
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=Br2ANAj8hi
- **关键词**：replay / rehearsal, regularization, catastrophic forgetting
- **摘要**：STABLE 是带自适应漂移控制的原对偶优化器，用于持续学习。

### 79. Subspace-Guided Continual Learning: Hessian Based Stable–Plastic Decomposition for Exemplar-Free Class-Incremental Learning

- **作者**：Qi Zhu, Ziang Gan, Wanting Zhang, Libao Zhang
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=gp622AVLX9
- **关键词**：class-incremental, exemplar-free, regularization, catastrophic forgetting, benchmark
- **摘要**：子空间引导持续学习（SGCL）从几何角度处理无示例类增量学习中的稳定性–可塑性困境，对应基于 Hessian 的稳定–可塑分解。

### 80. Surprise, Episodic Context, and Catastrophic Forgetting in LLM Fine-Tuning: An Empirical Study

- **作者**：Zied Ben Houidi, Alexis Huet, Alberto Eusebio, Francesco Mantovani, Dario Rossi
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=gsvP7j7bLZ
- **关键词**：architecture / parameter isolation, catastrophic forgetting, foundation models
- **摘要**：惊奇和情景上下文被认为支配动物更新记忆的方式，并影响先前知识如何被保留。本文对大语言模型微调中的惊奇、情景上下文与灾难性遗忘做实证研究。

### 81. SynGS: Synergistic Continual Learning and Change Detection with Gaussian Splatting

- **作者**：Rui Huang, Haojie Tao, Sen Gao, Qing Guo
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=Ls29PxSARF
- **关键词**：benchmark
- **摘要**：SynGS 用统一的三维高斯框架，同时进行持续场景更新与多视角变化检测。

### 82. TailAdapt: Heavy-Tailed Sparse Variational Adaptation for Long-Tailed Class Incremental Learning

- **作者**：Abhishek Kumar Sinha, Nitant Dube, Soma Biswas
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=3V8BlU6B4a
- **关键词**：class-incremental, regularization, architecture / parameter isolation, benchmark
- **摘要**：除数据不平衡外，每个会话内部还存在不对称的似然信号：尾部类提供的证据不足以克服先验正则，即便在变分推断下参数仍靠近先验均值。TailAdapt 针对这一现象，讨论长尾类增量学习中的重尾稀疏变分适配。

### 83. The Structural Bias of $\ell_2$-Regularized Cross-Entropy Heads in Class-Incremental Learning: Characterization, Limits, and a Gauge-Anchoring Fix

- **作者**：Milad Khademi Nori, Guanghui Wang
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=xULFTd3ead
- **关键词**：class-incremental, regularization
- **摘要**：事后去中心化是评估阶段的校正，为每个权重加入按任务计算的偏移，并为每个阈值加入对应标量，从而恢复贝叶斯最优的跨任务判别器。它针对类增量学习中 ℓ₂ 正则交叉熵头的结构偏差。

### 84. Towards Better Generalization in Lifelong Person Re-Identification with Flatness-Aware Learning

- **作者**：Seungbin Hong, Sung Whan Yoon, Jae-Young Sim
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=7TZx0YOrdx
- **关键词**：exemplar-free, distillation, architecture / parameter isolation, catastrophic forgetting
- **摘要**：为解决文中所指的冲突，该框架在终身行人重识别中统一选择性的平坦性感知优化、双模型训练与权重空间插值。

### 85. Trust Region Continual Learning as an Implicit Meta-Learner

- **作者**：Zekun Wang, Anant Gupta, Chris MacLellan
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=wrirlNfjM9
- **关键词**：task-incremental, replay / rehearsal, regularization, catastrophic forgetting
- **摘要**：持续学习要顺序习得任务并避免灾难性遗忘，但标准策略存在核心权衡：当任务最优解重叠较弱时，EWC 等正则方法会过度约束更新，基于回放的方法则构成权衡的另一侧。本文把信赖域持续学习视为隐式元学习器。

### 86. Two Drifts, One Principle: Conflict-Aware Spectral Consolidation for Multimodal Continual Learning

- **作者**：Haiyi Zhang, Qianyi Cai, Hanqing Wang, Zilin Wang, Xinyue Di, Yijie Xu, Yili Wang, Tianfu Wang, Yifan Han, Hui Xiong
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=bdROoNCzjt
- **关键词**：architecture / parameter isolation, foundation models
- **摘要**：冲突感知谱整合（CASC）在多模态持续学习中联合巩固 LoRA 与投影器的更新。

### 87. UFO: A Unified Flow-Oriented Framework for Robust Continual Graph Learning

- **作者**：Danhui Zhang, Zhe Wang, Qing Qing, Jiarui Liu, Wentao Gao, Ziqi Xu, Mingliang Hou, Xikun Zhang, Renqiang Luo
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=38kpqzHh0B
- **关键词**：catastrophic forgetting, graph, benchmark
- **摘要**：本文提出统一流导向框架 UFO，用于稳健的持续图学习。

### 88. Unlocking Compositional Generalization in Continual Few-Shot Learning

- **作者**：Phu-Quy Nguyen-Lam, Phu-Hoa Pham, Dao S Minh, Chi-Nguyen Tran, Trung-Kiet Huynh, Long Tran-Thanh
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=JiDX823MQW
- **关键词**：benchmark
- **摘要**：以物体为中心的表示可以把场景分解为物体级部分，并在不同概念之间匹配和比较，因而有望支撑少样本学习。本文讨论如何在持续少样本学习中释放组合泛化。

### 89. VAMIRec: Value-Aware Memory Intervention for Continual Recommendation

- **作者**：Xudong Zhao, Xiaolong Xu, Haolong Xiang, Xiaoyu Xia, Jiaqiang Zhang, Xuyun Zhang, Lianyong Qi, Wanchun Dou, Amin Beheshti
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=lxpE4SEnvz
- **关键词**：distillation, regularization, catastrophic forgetting, benchmark
- **摘要**：现有持续推荐方法主要通过回放、蒸馏或正则来保存或复用历史知识，以减轻增量更新中的遗忘。VAMIRec 针对这一问题提出价值感知的记忆干预。

### 90. What Is Worth Representing? Representational Empowerment for Continual Model Construction

- **作者**：Fei Dai, Hanqi Zhou, Alison Gopnik, Charley M Wu
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=m9oKQZGDlw
- **关键词**：architecture / parameter isolation, foundation models
- **摘要**：表征赋能（RepEmp）按候选元素能在多大程度上扩展智能体未来建模与规划的能力来打分，把经典的环境赋能从对外界的控制转向持续的模型构建。

### 91. When Catastrophic Inheritance Meets Forgetting in Continual Adaptation of Foundation Models

- **作者**：Quanyu Zhang, Zhongyi Han, Zhenxue Chen, Xiao-Long Yin, Henggui Zhang, Shuo Li
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=htPvCPtGAl
- **关键词**：foundation models
- **摘要**：模糊边界校正（ABC）通过锚点引导的邻域重加权，修正由继承而来的输出收缩所引起的模糊区域，以缓解基础模型持续适配中灾难性继承与遗忘交织的问题。

### 92. When the Merge Coefficient Stops Mattering: Proximity Regularized Merging for Continual LoRA Adaptation

- **作者**：Yixuan Liu, Yuhao Sun, Sen Song, Li Jin
- **会议**：NeurIPS 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=XA9pSXrybR
- **关键词**：class-incremental, replay / rehearsal, architecture / parameter isolation
- **摘要**：邻近正则合并（PRM）对顺序 LoRA 合并只做最小改动，在任务向量训练时加入近端惩罚，而不改变随后的写入规则。

## 主会 · Datasets and Benchmarks（5 篇）

### 1. Continual Learning Bench: Evaluating Frontier AI Systems in Real-World Stateful Environments

- **作者**：Parth Asawa, Christopher M Glaze, Gabriel Orlanski, Ramya Ramakrishnan, Benji Xu, Asim Biswal, Vincent Chen, Frederic Sala, Matei A Zaharia, Joseph Gonzalez
- **会议**：NeurIPS 2026 · 主会 · Datasets and Benchmarks
- **官方页面**：https://openreview.net/forum?id=ajW4TqUrCd
- **关键词**：foundation models, benchmark
- **摘要**：CL-Bench 是首个高难度、经专家验证的基准，用来衡量基于 LLM 的系统在真实有状态环境中是否真能随经验改进。

### 2. HERO: A Heterogeneity-Aware Benchmark Library for Federated Continual Learning

- **作者**：Thinh Nguyen, Le-Tuan Nguyen, Minh-Duong Nguyen, Nhi Trinh, Anh T Nguyet, Dung Le, Kok-Seng Wong
- **会议**：NeurIPS 2026 · 主会 · Datasets and Benchmarks
- **官方页面**：https://openreview.net/forum?id=UgjTgBmVgZ
- **关键词**：class-incremental, graph, benchmark
- **摘要**：HERO 是面向联邦持续学习、能够刻画异构性的基准库。

### 3. InCLAD: A Continual Learning Benchmark for Industrial Visual Anomaly Detection

- **作者**：Łukasz Marcjan, Dorota Wilk-Kołodziejczyk, Roberto Corizzo
- **会议**：NeurIPS 2026 · 主会 · Datasets and Benchmarks
- **官方页面**：https://openreview.net/forum?id=KLoy8Knatm
- **关键词**：task-incremental, benchmark
- **摘要**：InCLAD 是面向工业视觉异常检测的持续学习基准。除单数据集上的持续场景外，它还提出跨越多个数据集的困难场景。

### 4. KuaiRecV2: Benchmarking Large-Scale Continual Learning for Diversified and Multi-task Recommendation

- **作者**：Chenxu Li, Shuchang Liu, Hantao Shu, Wei Yuan, Zhe Xu, Guoqing Hu, Yan Wang, Biao Yang, Xiang Li, Cheng Ling, Fan Yang, Yongqi Liu, Lantao Hu, Han Li, Kaiqiao Zhan, Kun Gai, An Zhang, Xiang Wang
- **会议**：NeurIPS 2026 · 主会 · Datasets and Benchmarks
- **官方页面**：https://openreview.net/forum?id=95TcP79S4L
- **关键词**：benchmark
- **摘要**：针对文中所述挑战，KuaiRecV2 用来自快手的工业级数据特意构建基准，服务多样化、多任务推荐中的大规模持续学习。

### 5. Re-evaluating Continual Learning with Few-Shot Adaptation

- **作者**：Amogh Inamdar, Matthew So, Vici I Milenia, Richard Zemel
- **会议**：NeurIPS 2026 · 主会 · Datasets and Benchmarks
- **官方页面**：https://openreview.net/forum?id=xycCkL63TF
- **关键词**：continual learning
- **摘要**：本文提出少样本评估，用来更全面地考察持续学习系统的稳定性与可塑性。
