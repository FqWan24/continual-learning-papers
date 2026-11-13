# KDD 2026

检索窗口 2024-11-13 至 2026-11-13 内，与持续学习、终身学习或增量学习相关的 KDD 2026 论文，共 19 篇。主会 19 篇，Findings 0 篇，Workshop 0 篇，其他 0 篇。

主会数字包含该会议的官方主会轨道；NeurIPS 的 Datasets and Benchmarks 单独成节，仍计入主会。Findings、Workshop、Industry、Student Abstract 与 Short 另行标注。

## 主会（19 篇）

### 1. Cognitive Bifurcation: Dual-Progressive Causal Diffusion with Hippocampal Memory for Continual Graph Learning

- **作者**：Jiahao Liang, Carl Yang, Haoran Yang, Zhiwen Yu, Mengzhu Wang, Kaixiang Yang
- **会议**：KDD 2026 · 主会
- **官方页面**：https://doi.org/10.1145/3770855.3818129
- **关键词**：distillation, architecture / parameter isolation, catastrophic forgetting, graph
- **摘要**：DCDHippo 受人类大脑认知分叉的启发，以双渐进因果扩散与海马记忆处理持续图学习。

### 2. Collaborative Knowledge Extraction and Integration for Graph Domain Incremental Learning

- **作者**：Jialu Li, Yu Wang, Wanyu Lin, Pengfei Zhu
- **会议**：KDD 2026 · 主会
- **官方页面**：https://doi.org/10.1145/3770855.3817613
- **关键词**：domain-incremental, architecture / parameter isolation, catastrophic forgetting, graph
- **摘要**：面向图域增量学习，该工作认为需要不绑定分类特性的域无关表示，以帮助新模型捕捉更具判别性的特征，并据此讨论协同的知识抽取与整合。

### 3. Continual-GraphLLM: Dynamic Graph Large Language Model with Invariance Regularized Adaptive Multi-Scale Experts

- **作者**：Tianhang Wan, Xin Yue Wang, Haibo Chen, Longtao Huang, Wenwu Zhu
- **会议**：KDD 2026 · 主会
- **官方页面**：https://doi.org/10.1145/3770855.3817924
- **关键词**：catastrophic forgetting, foundation models, graph
- **摘要**：Continual-GraphLLM 把新到来的模式路由到专长于相似历史模式的专家，使动态图上的大语言模型持续适应，并缓解覆盖问题。这些专家带有不变性正则，并采用自适应的多尺度形式。

### 4. CREAM: Continual Retrieval on Dynamic Streaming Corpora with Adaptive Soft Memory

- **作者**：Huijeong Son, Hyeongu Kang, Sunho Kim, Subeen Ho, SeongKu Kang, Dongha Lee, Susik Yoon
- **会议**：KDD 2026 · 主会
- **官方页面**：https://doi.org/10.1145/3770854.3780281
- **关键词**：benchmark
- **摘要**：基于记忆的持续学习已被广泛用于信息检索以缓解相关问题。CREAM 讨论动态流式语料上的持续检索，并采用自适应软记忆。

### 5. DSETA: A Dual-Stage Continual Learning Framework for Travel Time Prediction in Dynamic Traffic Environments

- **作者**：Yanming Lyu, Yue Cheng, Lingkun Li, Ruipeng Gao, Xinyue Liu, Hui Gao, Qiang Ni
- **会议**：KDD 2026 · 主会
- **官方页面**：https://doi.org/10.1145/3770855.3818375
- **关键词**：catastrophic forgetting, benchmark
- **摘要**：DSETA 是可以增量更新的双阶段预计到达时间预测框架，用于动态交通环境中的行程时间预测。

### 6. Fair Class-Incremental Learning using Sample Weighting

- **作者**：Jaeyoung Park, Minsu Kim, Steven Euijong Whang
- **会议**：KDD 2026 · 主会
- **官方页面**：https://doi.org/10.1145/3770854.3780167
- **关键词**：class-incremental, catastrophic forgetting, benchmark
- **摘要**：在面向可信人工智能的类别增量学习中，模型公平性日益重要。本文讨论利用样本加权实现公平的类别增量学习。

### 7. FAT-TAG: Mitigating Forgetting in Task-Free Temporal Graph Class Incremental Learning

- **作者**：Jiyuan Feng, Zhao Liu, Dongyi Zheng, Weihong Han, Binxing Fang, Qing Liao
- **会议**：KDD 2026 · 主会
- **官方页面**：https://doi.org/10.1145/3770855.3818117
- **关键词**：class-incremental, architecture / parameter isolation, catastrophic forgetting, graph, benchmark
- **摘要**：FAT-TAG 是无任务边界的时序图类别增量学习框架，用于减轻遗忘。

### 8. FedFST: Mitigating Spectral Catastrophic Forgetting in Federated Graph Continual Learning

- **作者**：Hanyao Guo, Zihan Tan, Wenke Huang, Bin Yang, Mang Ye
- **会议**：KDD 2026 · 主会
- **官方页面**：https://doi.org/10.1145/3770855.3817730
- **关键词**：distillation, catastrophic forgetting, graph
- **摘要**：FedFST 是面向联邦图持续学习的谱感知框架，用于减轻双重谱灾难性遗忘。

### 9. G$^2$LoRA: Gradient Orthogonal Low-Rank Adaptation Framework for Graph Continual Learning on Text-Attributed Graphs

- **作者**：Yuhan Wang, Yibo Ding, Yutong Ye, Mufan Zhao, Wenbo Zhang, Ruijie Wang, Jianxin Li
- **会议**：KDD 2026 · 主会
- **官方页面**：https://doi.org/10.1145/3770855.3817966
- **关键词**：architecture / parameter isolation, graph
- **摘要**：文本属性图上的 LLM-as-Aligner 以 CLIP 式对比学习对齐图与文本，但在流式任务上顺序微调时会出现严重灾难性遗忘，参数高效微调虽能部分减轻遗忘，仍不足以消除任务干扰并实现有效的知识迁移。G2LoRA 针对异构下游任务引起的优化目标变化，以及图编码器与文本编码器适应敏感度不同所导致的失配，在减轻干扰的同时促进跨任务正向迁移。

### 10. GradMix: Gradient-based Selective Mixup for Robust Data Augmentation in Class-Incremental Learning

- **作者**：Minsu Kim, Seong-Hyeon Hwang, Steven Euijong Whang
- **会议**：KDD 2026 · 主会
- **官方页面**：https://doi.org/10.1145/3770854.3780300
- **关键词**：class-incremental
- **摘要**：GradMix 研究类别增量学习中的梯度选择性 Mixup，将其用作稳健的数据增强。

### 11. Lethe: Plasticity-aware Active Forgetting for Resource-Efficient On-Device Continual Learning

- **作者**：Haibo Liu, Chenxin Mao, Zhenzhe Zheng, Fan Wu, Guihai Chen, He Huang
- **会议**：KDD 2026 · 主会
- **官方页面**：https://doi.org/10.1145/3770855.3817621
- **关键词**：continual learning
- **摘要**：Lethe 把遗忘重新视为一种可能的解决途径，提出面向资源高效端侧持续学习的可塑性感知主动遗忘方案。

### 12. PrePrompt: Predictive Prompting for Class Incremental Learning

- **作者**：Libo Huang, Xiangqi Li, Jiarui Zhao, Zhulin An, Chuanguang Yang, Boyu Diao, Fei Wang, Yan Zeng, Zhifeng Hao, Yongjun Xu
- **会议**：KDD 2026 · 主会
- **官方页面**：https://doi.org/10.1145/3770855.3817682
- **关键词**：class-incremental, architecture / parameter isolation
- **摘要**：PrePrompt 研究类别增量学习中的预测式提示。

### 13. ReCATS: Replay-Free Continual Anomaly Detection for Non-Stationary Multivariate Time Series

- **作者**：Qiuyang Li, Qian Ma, Zhongming Yao, Shikai Guo, Yu Gu, Ge Yu, Tianyi Li
- **会议**：KDD 2026 · 主会
- **官方页面**：https://doi.org/10.1145/3770855.3817985
- **关键词**：continual learning
- **摘要**：ReCATS 研究非平稳多元时间序列上、不依赖回放的持续异常检测。

### 14. Regime-Adaptive Continual Learning for Portfolio Management

- **作者**：C. Liqiang Pan, Lingfei Ren, Linbo Xiong, Yonghao Li, Wei Wei, Xin Yang
- **会议**：KDD 2026 · 主会
- **官方页面**：https://doi.org/10.1145/3770855.3817620
- **关键词**：benchmark
- **摘要**：ReCAP 把持续学习引入投资组合管理，以状态感知的方式应对动态金融环境。

### 15. SCOPE: Streaming Covariance-Orthogonal Post-Hoc Editing for Continual LLM Safety Governance

- **作者**：Yizhe Yang, Xuanming Jiang, Jisheng Dang, Aoying Wang, Baoyi An, Hao Wu, Bimei Wang, Hong Peng, Guoshuai Zhao, Bin Hu, Zhongyu Yang
- **会议**：KDD 2026 · 主会
- **官方页面**：https://doi.org/10.1145/3770855.3817993
- **关键词**：foundation models
- **摘要**：SCOPE 研究持续的大语言模型安全治理，采用流式协方差正交的事后编辑。

### 16. Self-Regulating Prompt Expansion for Continual Learning

- **作者**：Yiwen Wang, Diana Benavides-Prado, Yun Sing Koh
- **会议**：KDD 2026 · 主会
- **官方页面**：https://doi.org/10.1145/3770855.3817717
- **关键词**：architecture / parameter isolation
- **摘要**：该文研究持续学习中的自调节提示扩展。

### 17. Slowing Down Forgetting in Continual Learning: Evidence from Manufacturing

- **作者**：Pascal Janetzky, Tobias Schlagenhauf, Michael Klar, Stefan Feuerriegel
- **会议**：KDD 2026 · 主会
- **官方页面**：https://doi.org/10.1145/3770855.3818481
- **关键词**：class-incremental, domain-incremental, catastrophic forgetting, benchmark
- **摘要**：ReCL 用于减缓持续学习中的遗忘，并给出制造业场景中的证据。

### 18. TRACE: Discovering Task-Specific Parameter via Adaptation-Aware Probing for Continual Fine-Tuning

- **作者**：Xiaosong Han, Ke Chen, Xindi Dai, Di Liang, Minlong Peng, Wei Pang, Fausto Giunchiglia, Xiaoyue Feng, Yonghao Liu, Renchu Guan
- **会议**：KDD 2026 · 主会
- **官方页面**：https://doi.org/10.1145/3770855.3817801
- **关键词**：architecture / parameter isolation, catastrophic forgetting, continual fine-tuning, foundation models, benchmark
- **摘要**：鉴于大语言模型参数对任一单一任务存在冗余，TRACE 把持续任务适应重新表述为通过适应感知探测来发现任务特定参数。短时热启动探测会暴露该任务的适应痕迹，并据此识别相关参数。

### 19. TTMC: Brain-Inspired Test-Time Memory Calibration with Orthogonal Projection for Online Continual Learning

- **作者**：Yuyang Han, Ziyu Li, Diwei Su, Shihao Zhang, Qing Li, Zhiying Long, Xia Wu
- **会议**：KDD 2026 · 主会
- **官方页面**：https://doi.org/10.1145/3770855.3818072
- **关键词**：online continual learning, benchmark
- **摘要**：受测试时学会记忆这一机制以及海马模式分离过程的启发，TTMC 提出无需梯度的解析式测试时记忆校准框架，并采用正交投影，用于在线持续学习。
