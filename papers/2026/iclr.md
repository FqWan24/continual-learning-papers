# ICLR 2026

检索窗口 2024-11-13 至 2026-11-13 内，与持续学习、终身学习或增量学习相关的 ICLR 2026 论文，共 60 篇。主会 60 篇，Findings 0 篇，Workshop 0 篇，其他 0 篇。

主会数字包含该会议的官方主会轨道；NeurIPS 的 Datasets and Benchmarks 单独成节，仍计入主会。Findings、Workshop、Industry、Student Abstract 与 Short 另行标注。

## 主会（60 篇）

### 1. A General Spatio-Temporal Backbone with Scalable Contextual Pattern Bank for Urban Continual Forecasting

- **作者**：Aoyu Liu, Yaying Zhang
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=LHSea6DI8U
- **关键词**：catastrophic forgetting, graph
- **摘要**：已有持续时空预测方法的骨干建模能力有限，也缺少平衡稳定性与适应性的有效机制；该文面向城市持续预测，讨论带可扩展上下文模式库的通用时空骨干。

### 2. Actions as Language: Fine-Tuning VLMs into VLAs Without Catastrophic Forgetting

- **作者**：Asher Hancock, Xindi Wu, Lihan Zha, Olga Russakovsky, Anirudha Majumdar
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=sFO9d6XSlf
- **关键词**：architecture / parameter isolation, catastrophic forgetting, foundation models
- **摘要**：VLM2VLA 把低层动作表示为自然语言，先在数据层面消除视觉语言模型微调为视觉语言动作模型时的不匹配，以避免灾难性遗忘。

### 3. Activation Function Design Sustains Plasticity in Continual Learning

- **作者**：Lute Lillo, Nick Cheney
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=XZf6wObHX4
- **关键词**：class-incremental, catastrophic forgetting, reinforcement learning, benchmark
- **摘要**：基于对负支形状与饱和行为的性质分析，该文提出可直接替换的 Smooth-Leaky 与 Randomized Smooth-Leaky 两种非线性，并在包括监督类增量在内的两种互补设定中评估它们维持持续学习可塑性的作用。

### 4. Adaptive Collaboration with Humans: Metacognitive Policy Optimization for Multi-Agent LLMs with Continual Learning

- **作者**：Wei Yang, Defu Cao, Jiacheng Pang, Muyan Weng, Yan Liu
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=IKVUB9Exuc
- **关键词**：foundation models, benchmark
- **摘要**：HILA 把人与智能体的协作组织为有原则的范式，用于多智能体大语言模型在持续学习中的自适应协作与元认知策略优化。

### 5. ADEPT: Continual Pretraining via Adaptive Expansion and Dynamic Decoupled Tuning

- **作者**：Jinyang Zhang, Yue Fang, Hongxin Ding, Weibin Liao, Muyang Ye, Junfeng Zhao, Yasha Wang, Xu Chu
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=vcWDDfA4Ev
- **关键词**：catastrophic forgetting, continual pretraining, foundation models, benchmark
- **摘要**：面向领域适应的常规大语言模型持续预训练常伴随灾难性遗忘，领域容量也有限；ADEPT 通过自适应扩展与动态解耦调参进行持续预训练。

### 6. All-day Multi-scenes Lifelong Vision-and-Language Navigation with Tucker Adaptation

- **作者**：XUDONG WANG, Gan Li, Zhiyu Liu, Yao Wang, Lianqing Liu, Zhi Han
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=qSak1Hjfdq
- **关键词**：architecture / parameter isolation, catastrophic forgetting
- **摘要**：TuKA 把多层导航知识表示为高阶张量，并用 Tucker 分解将其解耦为共享子空间与场景专属专家，以支持全天多场景的终身视觉语言导航。

### 7. Asymmetric Synthetic Data Update for Domain Incremental Dataset Distillation

- **作者**：Minyoung Oh, Jae-Young Sim
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=XcsaCHaoJh
- **关键词**：domain-incremental, distillation, catastrophic forgetting, benchmark
- **摘要**：该文提出领域增量数据集蒸馏这一设定，要求把来自不同领域的数据持续蒸馏进同一个合成数据集，并在此设定下研究非对称合成数据更新。

### 8. Avoid Catastrophic Forgetting with Rank-1 Fisher from Diffusion Models

- **作者**：Zekun Wang, Anant Gupta, Zihan Dong, Christopher MacLellan
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=zCZcbRsc4g
- **关键词**：class-incremental, regularization, catastrophic forgetting, benchmark
- **摘要**：该文提出秩 1 的 EWC 变体，其计算代价与对角近似相当，同时能捕捉主导曲率方向，并用来自扩散模型的秩 1 Fisher 避免灾难性遗忘。

### 9. Consistency-Driven Calibration and Matching for Few-Shot Class Incremental Learning

- **作者**：Qinzhe Wang, Zixuan Chen, Keke Huang, Xiu Su, Chunhua Yang, Chang Xu
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=LxO83jNZKk
- **关键词**：class-incremental, few-shot incremental, benchmark
- **摘要**：受海马联想记忆启发，该文设计记忆感知的原型校准，从基类提取可泛化语义属性并重新注入新类，以增强概念中心的一致性，用于少样本类增量学习中的一致性驱动校准与匹配。

### 10. Continual Low-Rank Adapters for LLM-based Generative Recommender Systems

- **作者**：Hyunsik Yoo, Ting-Wei Li, SeongKu Kang, Zhining Liu, Caizhi Charlie Xu, Qilin Qi, Hanghang Tong
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=DBCNTM7mot
- **关键词**：architecture / parameter isolation, foundation models
- **摘要**：PESO 以近端正则化维持单一且持续演化的 LoRA，作为推荐场景中的持续适配方法，服务于基于大语言模型的生成式推荐系统。

### 11. Detect, Decide, Unlearn: A Transfer-Aware Framework for Continual Learning

- **作者**：Yiwen Wang, Diana Benavides-Prado, Yun Sing Koh
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=Lej4WvdpFE
- **关键词**：catastrophic forgetting
- **摘要**：DEDUCE 在持续学习中动态检测负迁移，并用混合反学习机制加以缓解。

### 12. Enhanced Continual Learning of Vision-Language Models with Model Fusion

- **作者**：Haoyuan Gao, Zicong Zhang, Yuqi Wei, Linglan Zhao, Guilin Li, Yexin Li, Bo Wang, Linghe Kong, Weiran Huang
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=ptFP9yT9DK
- **关键词**：catastrophic forgetting, foundation models, benchmark
- **摘要**：ConDU 以持续的解耦与统一过程，把模型融合用于视觉语言模型的持续学习。

### 13. Fed-Duet: Dual Expert-Orchestrated Framework for Continual Federated Vision-Language Learning

- **作者**：Tao GUO, Junwei Chen, Laizhong Cui
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=Jk8g1OxyZY
- **关键词**：architecture / parameter isolation, catastrophic forgetting, foundation models
- **摘要**：Fed-Duet 以双专家编排框架，支持视觉语言模型上高效的联邦持续学习。

### 14. Fly-CL: A Fly-Inspired Framework for Enhancing Efficient Decorrelation and Reduced Training Time in Pre-trained Model-based Continual Representation Learning

- **作者**：Heming Zou, Yunliang Zang, Wutong Xu, Xiangyang Ji
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=jNbxjdc745
- **关键词**：catastrophic forgetting
- **摘要**：在近乎冻结的预训练模型上，持续表征学习把参数更新改写为相似度匹配问题以减轻灾难性遗忘；受果蝇启发的 Fly-CL 在此范式下加强高效去相关并缩短训练时间。

### 15. FlyPrompt: Brain-Inspired Random-Expanded Routing with Temporal-Ensemble Experts for General Continual Learning

- **作者**：Hongwei Yan, Guanglong Sun, Kanglei Zhou, Qian Li, Liyuan Wang, Yi Zhong
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=8pi1rP71qv
- **关键词**：architecture / parameter isolation
- **摘要**：持续参数高效微调仍缺少针对性设计，尚未解决如何把专家参数分配给不断变化的数据分布，以及如何在受限条件下提高其表示能力；FlyPrompt 以脑启发的随机扩展路由与时间集成专家讨论通用持续学习。

### 16. Forget Forgetting: Continual Learning in a World of Abundant Memory

- **作者**：Dongkyu Cho, Taesup Moon, Rumi Chunara, Kyunghyun Cho, Sungmin Cha
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=fvL8IIEPxG
- **关键词**：class-incremental, catastrophic forgetting, continual fine-tuning, foundation models
- **摘要**：该文考察记忆已经足以缓解遗忘、但从头完整重训仍然过于昂贵的情形，并据此挑战持续学习中的既有范式。

### 17. Heads collapse, features stay: Why Replay needs big buffers

- **作者**：Giulia Lanzillotta, Damiano Meier, Thomas Hofmann
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=IdW0d0mRnG
- **关键词**：replay / rehearsal
- **摘要**：持续学习中长期存在一个矛盾：神经网络对过去任务的输出预测已经失效，这些任务的线性可分表征却往往仍然保留；该文由此讨论头部坍缩而特征仍在，以及回放为何需要较大缓冲区。

### 18. HippoTune: A Hippocampal Associative Loop–Inspired Fine-Tuning Method for Continual Learning

- **作者**：Yanxi Chen, Xiuxing Li, Yuyang Han, Zhuo Wang, Qing Li, Ziyu Li, Xiang Li, Chen Wei, Xia Wu
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=MtDiLnnYgm
- **关键词**：catastrophic forgetting, benchmark
- **摘要**：HippoTune 在每个 Transformer 层中嵌入查询、检索与反馈回路，以潜空间迭代检索进行持续学习微调，其设计受海马联想环路启发。

### 19. HSIC Bottleneck for Cross-Generator and Domain-Incremental Synthetic Image Detection

- **作者**：CHIN-CHIA YANG, Yung-Yu Chuang, Hwann-Tzong Chen, Tyng-Luh Liu
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=msLnKDvhBx
- **关键词**：domain-incremental, catastrophic forgetting
- **摘要**：该文在 CLIP ViT 的中间特征上施加希尔伯特–施密特独立性准则（HSIC）瓶颈损失，使表示能够区分真实与合成图像，同时独立于生成器身份和图文对齐，以支持跨生成器与领域增量的合成图像检测。

### 20. IDER: IDempotent Experience Replay for Reliable Continual Learning

- **作者**：Zhanwang Liu, Yuting Li, Haoyuan Gao, Yexin Li, Linghe Kong, Lichao Sun, Weiran Huang
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=Vr5f3kRvLD
- **关键词**：replay / rehearsal, distillation, catastrophic forgetting, benchmark
- **摘要**：已有持续学习方法被用来减轻遗忘；IDER 以幂等经验回放讨论如何获得更可靠的持续学习。

### 21. Interference-Isolated Elastic Weight Consolidation and Knowledge Calibration for Incremental Object Detection

- **作者**：De Cheng, Mingyue Zeng, Zhipeng Xu, Di Xu, Nannan Wang, Xinbo Gao
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=VrXdmCjni4
- **关键词**：regularization, catastrophic forgetting, benchmark
- **摘要**：该文以弹性权重巩固（EWC）为基础，缓解增量目标检测中任务干扰所导致的冲突性知识保留，并讨论干扰隔离与知识校准。

### 22. KeepLoRA: Continual Learning with Residual Gradient Adaptation

- **作者**：Mao-Lin Luo, Zi-Hao Zhou, Yi-Lin Zhang, Yuanyu Wan, Min-Ling Zhang, Tong Wei
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=T3Vc5fkTzV
- **关键词**：architecture / parameter isolation
- **摘要**：KeepLoRA 通过残差梯度适配进行持续学习，以简洁的方式平衡其所针对的学习目标。

### 23. LCA: Local Classifier Alignment for Continual Learning

- **作者**：Tung Tran, Danilo Vasconcellos Vargas, Khoat Than
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=3uINmRldVW
- **关键词**：catastrophic forgetting, benchmark
- **摘要**：LCA 通过局部分类器对齐损失，使分类器与骨干网络更好地对齐，用于持续学习。

### 24. Lifelong Embodied Navigation Learning

- **作者**：XUDONG WANG, Jiahua Dong, Baichen Liu, Qi Lyu, Lianqing Liu, Zhi Han
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=PaYo96rjij
- **关键词**：architecture / parameter isolation, catastrophic forgetting, foundation models
- **摘要**：Uni-Walker 用解码器扩展 LoRA（DE-LoRA）把导航知识解耦为任务共享与任务专属两部分，构成终身具身导航学习框架。

### 25. Lifelong Learning with Behavior Consolidation for Vehicle Routing

- **作者**：Jiyuan Pei, Yi Mei, Jialin Liu, Mengjie Zhang, Xin Yao
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=sEdGLzgf6s
- **关键词**：catastrophic forgetting
- **摘要**：神经求解器在学习求解路径问题方面已有进展，该文进一步讨论面向车辆路径问题、带行为巩固的终身学习。

### 26. M$^3$E: Continual Vision-and-Language Navigation via Mixture of Macro and Micro Experts

- **作者**：Yongliang Jiang, Huaidong Zhang, Xuandi Luo, Shengfeng He
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=pFh5ygjN3V
- **关键词**：domain-incremental, architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：M³E 把宏观专家与微观专家组织成环境感知的层次化混合专家框架，用于持续视觉语言导航。

### 27. Mapping Post-Training Forgetting in Language Models at Scale

- **作者**：Jackson Harmon, Andreas Hochlehnert, Matthias Bethge, Ameya Prabhu
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=qCIg2WGudx
- **关键词**：catastrophic forgetting, continual pretraining, continual fine-tuning, reinforcement learning, benchmark
- **摘要**：该文提出按样本度量的范式，用以刻画语言模型在大规模后训练中遗忘了什么，以及反向迁移何时发生。

### 28. Memory-Free Continual Learning with Null Space Adaptation for Zero-Shot Vision-Language Models

- **作者**：Yujin Jo, Taesup Kim
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=tucuU4sQ3s
- **关键词**：replay / rehearsal, distillation, catastrophic forgetting, benchmark
- **摘要**：NuSA-CL 是面向零样本视觉语言模型的轻量无记忆持续学习框架，采用零空间适配。

### 29. Memory-Statistics Tradeoff in Continual Learning with Structural Regularization

- **作者**：Haoran Li, Jingfeng Wu, Vladimir Braverman
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=qfEqXJnlB4
- **关键词**：regularization, catastrophic forgetting
- **摘要**：该文在设定良好的随机设计下，研究由两个线性回归任务构成的持续学习问题的统计表现，并讨论结构正则化下记忆与统计量之间的权衡。

### 30. Merge before Forget: A Single LoRA Continual Learning via Continual Merging

- **作者**：Fuli Qiao, Mehrdad Mahdavi
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=i1Rj7yU6eF
- **关键词**：architecture / parameter isolation, catastrophic forgetting, foundation models, benchmark
- **摘要**：参数高效持续学习使大语言模型能够在适配新任务的同时减轻灾难性遗忘；该文讨论在遗忘发生之前进行持续合并，并以单一 LoRA 完成持续学习。

### 31. Meta-UCF: Unified Task-Conditioned LoRA Generation for Continual Learning in Large Language Models

- **作者**：ShiLin Xiao, Tianxiang Xu, Canran Xiao, Weihao Luo, Liwei Hou, Chuangxin Zhao
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=iNg5KL7eTC
- **关键词**：architecture / parameter isolation, catastrophic forgetting, foundation models, benchmark
- **摘要**：Meta-UCF 把每个任务编码为轻量的层归一化均值嵌入，再送入单一超网络，为每个 Transformer 层即时生成秩为 r 的 LoRA 更新，从而实现大语言模型持续学习中统一的任务条件 LoRA 生成。

### 32. Multi-Synaptic Cooperation: A Bio-Inspired Framework for Robust and Scalable Continual Learning

- **作者**：Penghui Li, Zhuang Ma, Yunliang Zang, Qiang YU
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=KjxS4AgFol
- **关键词**：catastrophic forgetting, benchmark
- **摘要**：受生物神经系统中突触连接的丰富性与可塑性启发，多突触协同网络 MSCN 建模多个突触之间的协同相互作用，作为稳健且可扩展的持续学习框架。

### 33. Naming to Learn: Class Incremental Learning for Vision-Language Model with Unlabeled Data

- **作者**：Qiwei Li, Xiaochen Yang, Jiahuan Zhou
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=Hc71kKCEFG
- **关键词**：class-incremental, catastrophic forgetting, benchmark
- **摘要**：N2L 采用可以递归求解的均方误差回归目标，支持视觉语言模型在无标注数据下的类增量学习。

### 34. Null-Space Filtering for Data-Free Continual Model Merging: Preserving Stability, Promoting Plasticity

- **作者**：Zihuan Qiu, Lei Wang, Yang Cao, Runtong ZHANG, Bing Su, Yi Xu, Fanman Meng, Linfeng Xu, Qingbo Wu, Hongliang Li
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=HDIf3fYqPP
- **关键词**：architecture / parameter isolation, benchmark
- **摘要**：在缺少任务数据时，如何把数据层面的要求与参数空间优化衔接起来并同时保证稳定性与可塑性，现有方法尚未解决；该文以零空间滤波讨论无数据条件下的持续模型合并。

### 35. One-Prompt Strikes Back: Sparse Mixture of Experts for Prompt-based Continual Learning

- **作者**：Minh Le, Bao-Ngoc Dao, Huy Nguyen, Quyen Tran, Anh Nguyen, Nhat Ho
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=B8eIc9783S
- **关键词**：architecture / parameter isolation, benchmark
- **摘要**：SMoPE 以稀疏混合专家整合任务专属提示与共享提示两类策略的长处，用于基于提示的持续学习。

### 36. PAC-Bayes bounds for cumulative loss in Continual Learning

- **作者**：Lior Friedman, Ron Meir
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=hWw269fPov
- **关键词**：continual learning
- **摘要**：实用的持续学习算法已经不少，如何为其提供可靠的风险证书成为相应的问题；该文讨论持续学习累积损失的 PAC-Bayes 界。

### 37. PACE: Pretrained Audio Continual Learning

- **作者**：Chang Li, Kanglei Zhou, Liyuan Wang
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=k5PgSlNc4E
- **关键词**：benchmark
- **摘要**：PACE 给出首个面向预训练模型的音频持续学习系统化基准，并分析该设定特有的挑战。

### 38. PCLR: Progressively Compressed LoRA for Multimodal Continual Instruction Tuning

- **作者**：Weicheng Meng, Jingyang Qiao, Zhizhong Zhang, Shaohui Liu, Yuan Xie
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=WdP1NVSzsz
- **关键词**：class-incremental, architecture / parameter isolation, catastrophic forgetting, continual fine-tuning
- **摘要**：为同时应对遗忘与内存膨胀，该文提出借鉴人类睡眠中记忆巩固过程的压缩、整合与学习流程，以渐进压缩的 LoRA 支持多模态持续指令微调。

### 39. Pi-CCA: Prompt-Invariant CCA Certificates for Replay-Free Continual Multimodal Learning

- **作者**：Jiayu Zhang, Chuangxin Zhao, Canran Xiao, Ruibo Duan, Wenyi Mo, Haoyu Gao, Wenshuo Wang
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=pn2H6YeOv2
- **关键词**：architecture / parameter isolation
- **摘要**：Pi-CCA 以几何优先的方式，用捕捉前 k 个典范谱与子空间的紧凑证书概括图文对齐，为无回放的持续多模态学习提供对提示不变的 CCA 证书。

### 40. Plug-and-Play Compositionality for Boosting Continual Learning with Foundation Models

- **作者**：Weiduo Liao, Fei Han, Hisao Ishibuchi, Qingfu Zhang, Ying Wei
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=22hBwIf7OC
- **关键词**：distillation, catastrophic forgetting, foundation models
- **摘要**：受概念级理解有助于减轻遗忘的启发，CompSLOT 作为通用框架引导不同持续学习器进行概念学习，从而以即插即用的组合性增强基础模型上的持续学习。

### 41. Point-UQ: An Uncertainty-Quantification Paradigm for Point Cloud Few-Shot Class Incremental Learning

- **作者**：Xiangqi Li, Libo Huang, Jiarui Zhao, Weilun Feng, Chuanguang Yang, Zhulin An, Yongjun Xu
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=fhVfyiiAqt
- **关键词**：class-incremental, few-shot incremental, catastrophic forgetting
- **摘要**：Point-UQ 是面向三维点云少样本类增量学习的增量式、无需训练的范式，基于不确定性量化把重点从特征调优转向动态决策优化。

### 42. PolySkill: Learning Generalizable Skills Through Polymorphic Abstraction For Continual Learning

- **作者**：Simon Yu, Gang Li, Weiyan Shi, Peng Qi
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=KdEsujyiSV
- **关键词**：architecture / parameter isolation, foundation models
- **摘要**：PolySkill 通过多态抽象让智能体学习可泛化且可组合的技能，以支持持续学习。

### 43. Principled Fast and Meta Knowledge Learners for Continual Reinforcement Learning

- **作者**：Ke Sun, Hongming Zhang, Jun Jin, Chao Gao, Xi Chen, Wulong Liu, Linglong Kong
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=loNTDX3wTn
- **关键词**：catastrophic forgetting, reinforcement learning, benchmark
- **摘要**：受人类学习与记忆系统、尤其是海马体与大脑皮层相互作用的启发，该文提出由快速学习器与元学习器组成的双学习器框架，用于持续强化学习。

### 44. Quantized Gradient Projection for Memory-Efficient Continual Learning

- **作者**：Dongjun Kim, Seohyeon Cha, Huancheng Chen, Chaining Wang, Haris Vikalo
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=xJtxpJ6QdD
- **关键词**：benchmark
- **摘要**：QGPM 压缩并保留以往的梯度子空间，以量化梯度投影记忆实现内存高效的持续学习。

### 45. Random Anchors with Low-rank Decorrelated Learning: A Minimalist Pipeline for Class-Incremental Medical Image Classification

- **作者**：Xinyao Wu, Zhe Xu, Raymond Kai-yu Tong
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=mduCc7XKXH
- **关键词**：class-incremental, architecture / parameter isolation, benchmark
- **摘要**：RA-LDL 是面向类增量医学图像分类的极简表征框架，结合基于预训练模型的特征提取与可选的 ViT-Adapter 调优，并通过冻结的随机锚点做特征校准，同时采用低秩去相关学习。

### 46. Rethinking Continual Learning with Progressive Neural Collapse

- **作者**：Zheng Wang, Wanhao Yu, Li Yang, Sen Lin
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=E3bBZ02Qcc
- **关键词**：distillation, catastrophic forgetting
- **摘要**：最大且彼此等间隔的类原型使 ETF 成为持续学习中减轻知识干扰的理想学习目标，该文据此以渐进神经坍缩重新思考持续学习。

### 47. Reversible Primitive–Composition Alignment for Continual Vision–Language Learning

- **作者**：Canran Xiao, Tianxiang Xu, SiYuan Ma, Yiyang Jiang, Haoyu Gao, Yuhan Wu
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=eiTy6AYeQi
- **关键词**：domain-incremental, replay / rehearsal
- **摘要**：Compo-ReAlign 以结构优先的配方服务于持续视觉语言学习，其中包括按设计把基元嵌入映射为组合的可逆组合器，以及同时对齐同一目标的文本视图与组合视图的多正样本 InfoNCE。

### 48. Revisiting Weight Regularization for Low-Rank Continual Learning

- **作者**：Yaoyue Zheng, Yin Zhang, Joost Van De Weijer, Gido Van De Ven, Shaoyi Du, Xuetao Zhang, Zhiqiang Tian
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=pZj2DhfaVD
- **关键词**：regularization, architecture / parameter isolation, benchmark
- **摘要**：基于大规模预训练模型的持续学习已把重点从从头训练转向对这些模型的持续适配，该文重新审视低秩持续学习中的权重正则化。

### 49. RLAP-CLIP: Continual Multimodal Learning with Prototype Adaptation and Difficulty-Aware Routing

- **作者**：Ruikun Luo, Jiarui Wang, Yuan Gao, Jing Yang, Jieming Yang, Song Wu, Hai Jin, Xiaoyu Xia
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=rMHZfCznhZ
- **关键词**：class-incremental, architecture / parameter isolation, reinforcement learning, benchmark
- **摘要**：RLAP-CLIP 通过三个组成部分应对持续多模态学习中的相应局限，其中包括原型适配与难度感知路由。

### 50. Robust Selective Activation with Randomized Temporal K-Winner-Take-All in Spiking Neural Networks for Continual Learning

- **作者**：Jiangrong Shen, Liang Zhao, Qi Xu, Yuqi Yang, Liangjun Chen, Gang Pan, Badong Chen
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=uAkexWJ7dW
- **关键词**：regularization, catastrophic forgetting
- **摘要**：脉冲神经网络上的持续学习需要平衡任务专属选择性与自适应资源分配，并增强对扰动的稳健性以减轻灾难性遗忘；该文采用随机化的时间 K 赢家通吃来实现稳健的选择性激活。

### 51. SAFA-SNN: Sparsity-Aware On-Device Few-Shot Class-Incremental Learning with Fast-Adaptive Structure of Spiking Neural Network

- **作者**：Huijing Zhang, Muyang Cao, Linshan Jiang, Xin Du, Di Yu, Changze Lv, Shuiguang Deng
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=9jcB40wjk3
- **关键词**：class-incremental, few-shot incremental, catastrophic forgetting, benchmark
- **摘要**：SAFA-SNN 在脉冲神经网络中结合稀疏感知的神经元动力学与快速自适应结构，用于设备端少样本类增量学习。

### 52. Scaling Agents via Continual Pre-training

- **作者**：Liangcai Su, Zhen Zhang, Guangyu Li, Zhuo Chen, Chenxi Wang, Maojia Song, Xinyu Wang, Kuan Li, Jialong Wu, Xuanzhong Chen, Zile Qiao, Zhongwang Zhang, Huifeng Yin, Shihao Cai, Runnan Fang, Zhengwei Tao, Wenbiao Yin, Rui Ye, Yong Jiang, Ningyu Zhang, Et al. （共 26 人）
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=Dru5mm9anE
- **关键词**：continual pretraining, foundation models, benchmark
- **摘要**：该文通过持续预训练扩展智能体，并据此开发名为 AgentFounder 的深度研究智能体模型。

### 53. Sculpting Subspaces: Constrained Full Fine-Tuning in LLMs for Continual Learning

- **作者**：Nikhil Shivakumar Nayak, Krishnateja Killamsetty, Ligong Han, Abhishek Bhandwaldar, Prateek Chanda, Kai Xu, Oleg Silkin, Mustafa Eyceoz, Hao Wang, Aldo Pareja, Akash Srivastava
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=vQcyqsGJDw
- **关键词**：architecture / parameter isolation, catastrophic forgetting, foundation models, benchmark
- **摘要**：该文提出正交子空间微调（OSFT），作为一种参数高效的持续学习方法，并讨论大语言模型中受约束的全量微调与子空间刻画。

### 54. SplitLoRA: Balancing Stability and Plasticity in Continual Learning Through Gradient Space Splitting

- **作者**：Haomiao Qiu, Miao Zhang, Ziyue Qiao, Weili Guan, Min Zhang, Liqiang Nie
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=Zm1hjXxRQV
- **关键词**：architecture / parameter isolation, benchmark
- **摘要**：持续学习要求模型顺序学习多个任务，既以稳定性保留已学知识，又以可塑性学习新任务；SplitLoRA 通过划分梯度空间来平衡这两者。

### 55. StPR: Spatiotemporal Preservation and Routing for Exemplar-Free Video Class-Incremental Learning

- **作者**：Huaijie Wang, De Cheng, Guozhang Li, Zhipeng Xu, Lingfeng He, Jie Li, Nannan Wang, Xinbo Gao
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=VAn2YVMuZC
- **关键词**：class-incremental, exemplar-free, replay / rehearsal, distillation, architecture / parameter isolation, catastrophic forgetting
- **摘要**：视频类增量学习在传统类增量之外还涉及时空结构，需要在减轻灾难性遗忘的同时捕捉帧间共享语义与时间信息；StPR 在无示例设定下讨论时空保持与路由。

### 56. The Lie of the Average: How Class Incremental Learning Evaluation Deceives You?

- **作者**：Guannan Lai, Da-Wei Zhou, Xin Yang, Han-Jia Ye
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=19LHXi9uLw
- **关键词**：class-incremental
- **摘要**：该文提出极端序列这一概念，并从理论上说明它在类增量学习可靠评测中的关键作用，用以审视平均结果对评测的误导。

### 57. The Rank and Gradient Lost in Non-stationarity: Sample Weight Decay for Mitigating Plasticity Loss in Reinforcement Learning

- **作者**：Zihao Wu, Hongyao Tang, Yi Ma, Jiashun Liu, YAN ZHENG, Jianye Hao
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=5DpzzTPnJZ
- **关键词**：replay / rehearsal, reinforcement learning
- **摘要**：该文从网络优化的理论视角研究可塑性损失，关注非平稳性下流失的秩与梯度，并讨论用样本权重衰减缓解强化学习中的可塑性损失。

### 58. Two-Way Is Better Than One: Bidirectional Alignment with Cycle Consistency for Exemplar-Free Class-Incremental Learning

- **作者**：Hongye Xu, Bartosz Krawczyk
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=7UfZAxKo5K
- **关键词**：class-incremental, exemplar-free, catastrophic forgetting, benchmark
- **摘要**：该文在无示例的类增量学习中于训练时引入双向投影对齐：每个新任务学习从旧到新与从新到旧两个映射，并以停止梯度门控和循环一致性目标让传输与表示协同演化。

### 59. Understanding the Dynamics of Forgetting and Generalization in Continual Learning via the Neural Tangent Kernel

- **作者**：Guodong Zheng, Peng Wang, Shengchao Hu, Quan Zheng, Li Shen
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=NE2yIxdo1w
- **关键词**：benchmark
- **摘要**：该文在神经切线核（NTK）机制下分析标准持续学习训练过程中遗忘与泛化的动态，分析涉及降低损失的 Lipschitz 常数以及最小化跨任务核。

### 60. XIL: Cross-Expanding Incremental Learning

- **作者**：Heayoun Choi, Hyundong Jin, Eunwoo Kim
- **会议**：ICLR 2026 · 主会
- **官方页面**：https://openreview.net/forum?id=eaAGI1lIb4
- **关键词**：class-incremental, architecture / parameter isolation, benchmark
- **摘要**：交叉扩展增量学习（XIL）扩展类增量学习，要求模型处理不同领域上的类增量数据，并双向扩展类别与领域之间的关联。
