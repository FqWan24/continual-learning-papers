# AAAI 2026

检索窗口 2024-11-13 至 2026-11-13 内，与持续学习、终身学习或增量学习相关的 AAAI 2026 论文，共 68 篇。主会 63 篇，Findings 0 篇，Workshop 0 篇，其他 5 篇。

主会数字包含该会议的官方主会轨道；NeurIPS 的 Datasets and Benchmarks 单独成节，仍计入主会。Findings、Workshop、Industry、Student Abstract 与 Short 另行标注。

## 主会（63 篇）

### 1. Adapt Before Continual Learning

- **作者**：Aojun Lu, Tao Feng, Hangjie Yuan, Chunhui Ding, Yanan Sun
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i29.39584
- **关键词**：catastrophic forgetting, benchmark
- **摘要**：ACL 在每次进入新任务的核心持续学习之前，为预训练模型加入一段即插即用的适应。

### 2. Adversarial Perturbation Shield: Preventing Concept Bleed-through in Continual Learning of Personalized Generative Models

- **作者**：Ziwen Lan, Keisuke Maeda, Takahiro Ogawa, Miki Haseyama
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i27.39438
- **关键词**：continual learning
- **摘要**：个性化生成模型的持续学习中，已有工作试图在模型适应层面缓解概念渗漏，却仍难以在潜空间中充分保持彼此区分的语义表示。本文讨论用对抗扰动屏蔽来防止这种概念渗漏。

### 3. Attention Retention for Continual Learning with Vision Transformers

- **作者**：Yue Lu, Xiangyu Zhou, Shizhou Zhang, Yinghui Xing, Guoqiang Liang, Wencong Zhang
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i29.39592
- **关键词**：catastrophic forgetting
- **摘要**：受人类视觉系统选择性注意的启发，该工作提出注意力保持框架，用以缓解视觉 Transformer 持续学习中的遗忘。

### 4. Better Matching, Less Forgetting: A Quality-Guided Matcher for Transformer-based Incremental Object Detection

- **作者**：Qirui Wu, Shizhou Zhang, De Cheng, Yinghui Xing, Lingyan Ran, Dahu Shi, Peng Wang
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i13.38046
- **关键词**：catastrophic forgetting, graph, benchmark
- **摘要**：面向基于 Transformer 的增量目标检测，本文提出质量引导的最小费用最大流匹配器 Q-MCMF，以期通过更好的匹配减轻遗忘。

### 5. Beyond Sharpness: A Flatness Decomposition Framework for Efficient Continual Learning

- **作者**：Yanan Chen, Tieliang Gong, Yunjiao Zhang, Wen Wen
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i24.39124
- **关键词**：regularization
- **摘要**：FLAD 面向高效持续学习，把锐度感知扰动分解为与梯度对齐的分量和随机噪声分量，并表明只保留噪声分量有助于泛化。

### 6. BOFA: Bridge-Layer Orthogonal Low-Rank Fusion for CLIP-Based Class-Incremental Learning

- **作者**：Lan Li, Tao Hu, Da-Wei Zhou, Jia-Qi Yang, Han-jia Ye, De-Chuan Zhan
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i27.39461
- **关键词**：class-incremental, benchmark
- **摘要**：BOFA 是面向基于 CLIP 的类别增量学习提出的桥接层正交低秩融合框架。

### 7. Bring Your Dreams to Life: Continual Text-to-Video Customization

- **作者**：Jiahua Dong, Xudong Wang, Wenqi Liang, Zongyan Han, Meng Cao, Duzhen Zhang, Hanbin Zhao, Zhi Han, Salman Khan, Fahad Shahbaz Khan
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i5.37361
- **关键词**：architecture / parameter isolation, catastrophic forgetting
- **摘要**：CCVD 是持续定制的视频扩散模型，能够不断学习新概念以完成多种文生视频任务，并处理遗忘与概念忽视。

### 8. Catastrophic Forgetting in Kolmogorov-Arnold Networks

- **作者**：Mohammad Marufur Rahman, Guanchu Wang, Kaixiong Zhou, Minghan Chen, Fan Yang
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i30.39697
- **关键词**：architecture / parameter isolation, catastrophic forgetting, continual fine-tuning
- **摘要**：该工作系统研究 Kolmogorov-Arnold 网络中的灾难性遗忘，并建立把遗忘与激活支撑重叠及数据内在维度联系起来的理论框架。

### 9. CiNuSeg: Class Incremental Nuclei Segmentation via Anchor-driven Consistency Learning with Dual Region Regularization

- **作者**：Xuexin Wu, Zhenhui Ding, Huisi Wu, Jing Qin
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i13.38055
- **关键词**：class-incremental, distillation, regularization, catastrophic forgetting, benchmark
- **摘要**：既有类别增量细胞核分割方法多通过原型蒸馏旧类知识来减轻遗忘，却难以捕捉细粒度细节，以应对组织学中尤为严重的高类间相似性。本文提出结合锚点驱动一致性学习与双区域正则的 CiNuSeg。

### 10. CIP-Net: Continual Interpretable Prototype-based Network

- **作者**：Federico Di Valerio, Michela Proietti, Alessio Ragno, Roberto Capobianco
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i25.39216
- **关键词**：class-incremental, exemplar-free, catastrophic forgetting
- **摘要**：CIP-Net 是面向持续学习的无示例、可自解释原型模型。

### 11. CKDA: Cross-modality Knowledge Disentanglement and Alignment for Visible-Infrared Lifelong Person Re-identification

- **作者**：Zhenyu Cui, Jiahuan Zhou, Yuxin Peng
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i5.37342
- **关键词**：distillation, architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：CKDA 面向可见光–红外终身行人重识别，以均衡方式显式分离并保留模态特定知识与模态共有知识。

### 12. Class Incremental Medical Image Segmentation via Prototype-Guided Calibration and Dual-Aligned Distillation

- **作者**：Shengqian Zhu, Chengrong Yu, Qiang Wang, Ying Song, Guangjun Li, Jiafei Wu, Xiaogang Xu, Zhang Yi, Junjie Hu
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i16.38406
- **关键词**：class-incremental, distillation, benchmark
- **摘要**：面向类别增量医学图像分割，本文提出原型引导校准蒸馏 PGCD 与双对齐原型蒸馏 DAPD。

### 13. Compensating Distribution Drifts in Continual Learning with Pre-trained Vision Transformers

- **作者**：Xuan Rao, Simian Xu, Zheng Li, Bo Zhao, Derong Liu, Mingming Ha, Cesare Alippi
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i30.39698
- **关键词**：class-incremental, distillation, benchmark
- **摘要**：SLDC 引入潜空间转移算子，用于补偿预训练视觉 Transformer 在持续学习中遇到的分布漂移。

### 14. Composition-Incremental Learning for Compositional Generalization

- **作者**：Zhen Li, Yuwei Wu, Chenchen Jing, Che Sun, Chuanhao Li, Yunde Jia
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i8.37605
- **关键词**：distillation, benchmark
- **摘要**：为定量评估组合增量学习 CompIL，该工作利用已有数据构建评测流程，得到 MIT-States-CompIL 与 C-GQA-CompIL。

### 15. ConSurv: Multimodal Continual Learning for Survival Analysis

- **作者**：Dianzhi Yu, Conghao Xiong, Yankai Chen, Wenqian Cui, Xinni Zhang, Yifei Zhang, Hao Chen, Joseph J. Y. Sung, Irwin King
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i33.40013
- **关键词**：architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：ConSurv 针对十亿像素级全切片图像与基因组之间的复杂跨模态交互以及灾难性遗忘，提出用于生存分析的多模态持续学习方法。

### 16. Continual Out-of-Distribution Detection with Analytic Neural Collapse

- **作者**：Saleh Momeni, Changnan Xiao, Bing Liu
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i18.38585
- **关键词**：catastrophic forgetting
- **摘要**：AnaNC 在冻结预训练模型的特征空间中以解析方式构造神经坍缩性质，无需训练即可用于持续分布外检测，并克服灾难性遗忘。

### 17. Decomposing and Composing: Towards Efficient Vision-Language Continual Learning via Rank-1 Expert Pool in a Single LoRA

- **作者**：Zhan Fa, Yue Duan, Jian Zhang, Lei Qi, Wanqi Yang, Yinghuan Shi
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i25.39240
- **关键词**：architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：直接使用 LoRA 来缓解灾难性遗忘并不容易，该框架因此把单个 LoRA 模块重构为可分解的秩一专家池，用于视觉语言持续学习。

### 18. Decomposing Prompts, Composing Actions: A Multi-Granularity Prompting Approach for Incremental Action Learning

- **作者**：Xinyi Cheng, Chenghao Xu, Xi Wang, Jiexi Yan, Yanhua Yang
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i5.37326
- **关键词**：replay / rehearsal, architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：DPCA 面向增量动作学习，提出采用多粒度自适应提示的时空持续学习框架。

### 19. Decomposing the Neurons: Activation Sparsity via Mixture of Experts for Continual Test Time Adaptation

- **作者**：Rongyu Zhang, Aosong Cheng, Yulin Luo, Gaole Dai, Huanrui Yang, Jiaming Liu, Ran Xu, Li Du, Dan Wang, Yuan Du
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i42.40922
- **关键词**：architecture / parameter isolation, catastrophic forgetting, test-time adaptation
- **摘要**：受神经网络中神经元激活编码特性的启发，MoASE 以激活稀疏性构成混合专家，用于持续测试时适应。

### 20. Decoupling Continual Semantic Segmentation

- **作者**：Yifu Guo, Yuquan Lu, Wentao Zhang, Zishan Xu, Dexia Chen, Siyu Zhang, Yizhe Zhang, Ruixuan Wang
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i6.42446
- **关键词**：architecture / parameter isolation, catastrophic forgetting
- **摘要**：DecoupleCSS 是面向持续语义分割的两阶段解耦框架。

### 21. DiAPR: Dimensionally-Allocated Prototype Refinement for Non-Exemplar Class Incremental Learning

- **作者**：Ruixuan Gao, Qijun Zhao, Keren Fu
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i25.39263
- **关键词**：class-incremental, exemplar-free, catastrophic forgetting
- **摘要**：DiAPR 面向无示例类别增量学习，通过三个模块逐步精炼原型，使其在新的特征空间中呈现类别可分性。

### 22. Diffusion-calibrated Continual Test-time Adaptation

- **作者**：Xu Yang, Moqi Li, Kun Wei
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i33.39989
- **关键词**：test-time adaptation, benchmark
- **摘要**：面向扩散校准的持续测试时适应，该框架把外部辅助生成模型与测试时适应方法结合起来，并利用交叉验证识别可靠的监督信号，以增强推理模型的判别能力。

### 23. Distillation-Guided Structural Transfer for Continual Learning Beyond Sparse Distributed Memory

- **作者**：Huiyan Xue, Xuming Ran, Yaxin Li, Qi Xu, Enhui Li, Yi Xu, Qiang Zhang
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i32.39960
- **关键词**：distillation, architecture / parameter isolation, catastrophic forgetting
- **摘要**：稀疏子网络的隔离会严重限制跨任务知识复用，而提高稀疏度在减少干扰的同时，又往往因特征受限而降低性能。本文讨论以蒸馏引导的结构迁移超越这种稀疏分布式记忆。

### 24. E-Logic Prompt: Unified Energy-Logic Framework for Continual Visual Question Answering

- **作者**：Jiayao Tan, Tianle Liu, Fuyuan Hu, Wei Feng, Liang Wan
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i30.39775
- **关键词**：architecture / parameter isolation
- **摘要**：E-Logic Prompt 面向持续视觉问答，用基于能量的模型刻画提示与查询之间的语义兼容性，形成统一的能量逻辑框架。

### 25. Expandable and Differentiable Dual Memories with Orthogonal Regularization for Exemplar-free Continual Learning

- **作者**：Hyung-Jun Moon, Sung-Bae Cho
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i29.39626
- **关键词**：class-incremental, exemplar-free, regularization, architecture / parameter isolation
- **摘要**：面向无示例持续学习，该工作提出带正交正则、完全可微且可扩展的双记忆方法：一块记忆学习可供所有任务使用的共同特征，另一块结合这些共享特征继续学习。

### 26. FedRNC: Addressing Spatio-Temporal Label Misalignment in Federated Noisy Class-Incremental Learning

- **作者**：Xingwei Huang, Zhaobin Sun, Junjie Shi, Xin Yang, Zengqiang Yan
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i26.39359
- **关键词**：class-incremental, benchmark
- **摘要**：该工作提出联邦噪声类别增量学习，并首次指出时空标签错位这一新型标签噪声，即未见类别的样本被整体误标为已知类别。

### 27. First Learn, Then Review: Human-Like Continual Learning for Cross-View Geo-Localization with Limited Field of View

- **作者**：Lei Cheng, Daikun Liu, Zhikun Chen, Teng Wang
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i5.37321
- **关键词**：benchmark
- **摘要**：HCL-Geo 面向视场有限的跨视图地理定位，遵循先学习、再复习的类人持续学习方式，并在学习阶段按由易到难的顺序呈现任务。

### 28. Forgetting Knowledge Localization and Isolation for Continual Forgetting of Pre-trained Vision Models

- **作者**：Zhiwen Yang, Jiehua Zhang, Chenggang Yan, Yuhan Gao, Zongpeng Li, Xichun Sheng, Liang Li
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i33.39995
- **关键词**：architecture / parameter isolation, benchmark
- **摘要**：该方法定位并隔离预训练视觉模型中的待遗忘知识，以便在持续遗忘中精确去除目标知识，同时减轻对其余知识的过度遗忘。

### 29. Gene Incremental Learning for Single-Cell Transcriptomics

- **作者**：Jiaxin Qi, Yan Cui, Jianqiang Huang, Gaogang Xie
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i2.37062
- **关键词**：class-incremental, benchmark
- **摘要**：该工作把基因作为词元，在单细胞转录组这一大规模生物数据上构建基因增量学习流程，并建立相应评测。

### 30. Grow-on-Demand: Sparse and Adaptive Expert Expansion for Continual Instruction Tuning

- **作者**：Ying Zhang, Xingyue Guo, Yu Zhao, Xuhui Sui, Baohang Zhou, Xinying Qian, Xiaojie Yuan
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i34.40077
- **关键词**：architecture / parameter isolation, catastrophic forgetting, continual fine-tuning, foundation models, benchmark
- **摘要**：Grow-on-Demand 采用结构共享策略，使相似任务可以复用参数，只在必要时做稀疏且自适应的专家扩展，并避免任何数据回放，用于持续指令微调。

### 31. Harnessing Textual Semantic Priors for Knowledge Transfer and Refinement in CLIP-Driven Continual Learning

- **作者**：Lingfeng He, De Cheng, Di Xu, Huaijie Wang, Nannan Wang
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i26.39314
- **关键词**：distillation, benchmark
- **摘要**：SECA 面向 CLIP 驱动的持续学习，利用文本先验抗遗忘且有结构的特点，引导骨干网络中语义感知的知识迁移与精炼。

### 32. HiCL: Hippocampal-Inspired Continual Learning

- **作者**：Kushal Kapoor, Wyatt Mackey, Yiannis Aloimonos, Xiaomin Lin
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i27.39411
- **关键词**：regularization, catastrophic forgetting, benchmark
- **摘要**：HiCL 是受海马回路启发的双记忆持续学习架构，用于缓解灾难性遗忘。

### 33. HLML-SNN：Fast Continual Learning in Spiking Neural Networks Achieved via Hebbian Learning-Driven Meta-Learning

- **作者**：Jiangshuai Xu, Peiyun Xue, Jiacheng Song, Xuhui Huang, Qingshan Hou
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i32.39942
- **关键词**：catastrophic forgetting
- **摘要**：HLML-SNN 受皮层与海马记忆机制启发，把赫布可塑性与元学习结合起来，用于脉冲神经网络中的快速持续学习。

### 34. Improving Sustainability of Adversarial Examples in Class-Incremental Learning

- **作者**：Taifeng Liu, Xinjing Liu, Liangqiu Dong, Yang Liu, Yilong Yang, Zhuo Ma
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i9.37664
- **关键词**：class-incremental
- **摘要**：SAE 用于提升对抗样本在类别增量学习中的可持续性。

### 35. KSS-MoE: Knowledge Space Synergy Framework in Mixture of Experts for Continual Visual Instruction Tuning

- **作者**：Lingyun Song, Ziyao Chen, Kang Pan, Xiaolin Han, Xinbiao Gan, Yudai Pan, Xiaofan Sun, Xiaoqi Wang, Xuequn Shang
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i30.39749
- **关键词**：architecture / parameter isolation, catastrophic forgetting, continual fine-tuning, foundation models
- **摘要**：KSS-MoE 把知识空间协同框架用于混合专家，服务于持续视觉指令微调。

### 36. Learning Adaptive and Expandable Mixture Model for Continual Learning

- **作者**：Fei Ye, YongCheng Zhong, Qihe Liu, Adrian G. Bors, JingLing Sun, Jinyu Guo, ShiJie Zhou
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i33.39999
- **关键词**：architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：现有持续学习方法通常依赖单一预训练骨干，并冻结全部预训练参数以减轻网络遗忘，从而限制了对新任务的适应能力。本文讨论自适应且可扩展的混合模型。

### 37. Learning from Imperfect Data: Incremental Learning and Few-shot Learning

- **作者**：Yaoyao Liu
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i47.41349
- **关键词**：benchmark
- **摘要**：人工智能近年来已在许多领域取得成功。在此背景下，本文讨论如何从不完美数据中进行增量学习与少样本学习。

### 38. Learning with Preserving for Continual Multitask Learning

- **作者**：Hanchen David Wang, Siwoo Bae, Zirong Chen, Meiyi Ma
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i31.39821
- **关键词**：replay / rehearsal, catastrophic forgetting, benchmark
- **摘要**：LwP 面向持续多任务学习，把需要保持的重点从任务输出转向共享表示空间的几何结构。

### 39. LifeAlign: Lifelong Alignment for Large Language Models with Memory-Augmented Focalized Preference Optimization

- **作者**：Junsong Li, Jie Zhou, Bihao Zhan, Yutao Yang, Qianjun Pan, Shilian Chen, Tianyu Huai, Xin Li, Qin Chen, Liang He
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i37.40428
- **关键词**：catastrophic forgetting, foundation models
- **摘要**：LifeAlign 面向大语言模型的终身对齐，借助记忆增强的聚焦偏好优化，使模型在顺序任务中保持一致的人类偏好，同时保留已经学到的价值。

### 40. Lifelong Domain Adaptive 3D Human Pose Estimation

- **作者**：Qucheng Peng, Hongfei Xue, Pu Wang, Chen Chen
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i10.37785
- **关键词**：catastrophic forgetting, benchmark
- **摘要**：该工作提出终身域自适应三维人体姿态估计这一新任务。

### 41. Lifelong Language-Conditioned Robotic Manipulation Learning

- **作者**：Xudong Wang, Zebin Han, Zhiyu Liu, Gan Li, Jiahua Dong, Baichen Liu, Lianqing Liu, Zhi Han
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i22.38930
- **关键词**：catastrophic forgetting
- **摘要**：SkillsCrafter 是语言条件下的机器人操作框架，可以持续学习多项技能，并减轻对旧技能的灾难性遗忘。

### 42. LoRA in LoRA: Towards Parameter-Efficient Architecture Expansion for Continual Visual Instruction Tuning

- **作者**：Chang Che, Ziqi Wang, Pengwan Yang, Cheems Wang, Hui Ma, Zenglin Shi
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i24.39082
- **关键词**：architecture / parameter isolation, catastrophic forgetting, continual fine-tuning, foundation models, benchmark
- **摘要**：在持续视觉指令微调中，架构扩展常通过引入任务专用模块来避免干扰、减轻遗忘。本文讨论以 LoRA in LoRA 实现参数高效的架构扩展。

### 43. MacVQA: Adaptive Memory Allocation and Global Noise Filtering for Continual Visual Question Answering

- **作者**：Zhifei Li, Yiran Wang, Chenyi Xiong, Yujing Xia, Xiaoju Hou, Yue Zhao, Miao Zhang, Kui Xiao, Bing Yang
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i38.40458
- **关键词**：continual learning
- **摘要**：MacVQA 面向持续视觉问答，采用自适应记忆分配与全局噪声过滤。

### 44. MetaGDPO: Alleviating Catastrophic Forgetting with Metacognitive Knowledge Through Group Direct Preference Optimization

- **作者**：Lanxue Zhang, Yuqiang Xie, Fang Fang, Fanglong Dong, Rui Liu, Yanan Cao
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i41.40777
- **关键词**：distillation, catastrophic forgetting, foundation models
- **摘要**：MetaGDPO 借助元认知知识，通过群体直接偏好优化，从数据与微调方式两方面缓解灾难性遗忘。

### 45. Multi-Task Test-time Adaptation via Gradient Consensus and Plasticity Constraint

- **作者**：Zhong Ye, Yu Hu, Zhenguo Yang
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i33.40006
- **关键词**：catastrophic forgetting, test-time adaptation
- **摘要**：CoCo-MT-TTA 面向多任务测试时适应，通过对齐跨任务梯度方向来寻求共识梯度，并施加多任务可塑性约束。

### 46. OPLoRA: Orthogonal Projection LoRA Prevents Catastrophic Forgetting During Parameter-Efficient Fine-Tuning

- **作者**：Yifeng Xiong, Xiaohui Xie
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i40.40703
- **关键词**：architecture / parameter isolation, catastrophic forgetting, foundation models
- **摘要**：OPLoRA 在参数高效微调中通过双侧正交投影抑制干扰，从而防止灾难性遗忘。

### 47. Palimpsest: Reconciling the CISS Trilemma for Incremental Nuclei Segmentation

- **作者**：Jiajia Li, Huisi Wu
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i27.39458
- **关键词**：class-incremental, exemplar-free, architecture / parameter isolation, benchmark
- **摘要**：Palimpsest 面向增量细胞核分割，通过系统解耦相互冲突的需求来调和 CISS 三难困境。

### 48. PANDA – Patch and Distribution-Aware Augmentation for Long-Tailed Exemplar-Free Continual Learning

- **作者**：Siddeshwar Raghavan, Jiangpeng He, Fengqing Zhu
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i30.39694
- **关键词**：exemplar-free, catastrophic forgetting, benchmark
- **摘要**：PANDA 是面向长尾无示例持续学习的图像块与分布感知增强框架，可以与现有基于预训练模型的无示例持续学习方法衔接。

### 49. Parameter Merging with Gradient-Guided Supermasks in Online Continual Learning

- **作者**：Benliu Qiu, Heqian Qiu, Lanxiao Wang, Taijin Zhao, Yu Dai, Lili Pan, Hongliang Li
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i30.39687
- **关键词**：online continual learning, distillation, catastrophic forgetting, benchmark
- **摘要**：在线持续学习要求以每个样本只读取一次的方式学习非平稳数据流，因而面临灾难性遗忘与学习不足之间的权衡。本文讨论用梯度引导超掩码进行参数合并。

### 50. Persistent Backdoor Attacks Under Continual Fine-Tuning of LLMs

- **作者**：Jing Cui, Yufei Han, Jianbin Jiao, Junge Zhang
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i36.40295
- **关键词**：continual fine-tuning, foundation models
- **摘要**：P-Trojan 是基于触发器的攻击算法，在大语言模型持续微调的反复更新中显式优化后门的持久性。

### 51. Perturbing to Preserve: Defending Fragile Knowledge in Online Continual Learning

- **作者**：Dulan Zhou, Zijian Gao, Kele Xu
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i34.40129
- **关键词**：online continual learning
- **摘要**：在线持续学习要求模型从非平稳数据流中学习并保留已有知识。本文讨论通过扰动来保护其中的脆弱知识。

### 52. R-Tuning: Wavelet-Decomposed Replay and Semantic Alignment for Continual Adaptation of Pretrained Time-Series Models

- **作者**：Tianyi Yin, Jingwei Wang, Chenze Wang, Han Wang, Jiexuan Cai, Min Liu, Yunlong Ma, Kun Gao, Yuting Song, Weiming Shen
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i33.40010
- **关键词**：catastrophic forgetting, benchmark
- **摘要**：R-Tuning 面向预训练时间序列模型的持续适应，采用小波分解回放与语义对齐。

### 53. Random Amalgamation of Adapters for Flatter Loss Landscapes: Towards Class-Incremental Learning with Better Stability

- **作者**：Yao Deng, Xiang Xiang, Jiaqi Gui
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i25.39213
- **关键词**：class-incremental, architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：面向类别增量学习的稳定性，该工作首先独立优化多条适配器分支，为预训练模型配备多样化的可学习参数，以改善参数更新时的稳定性，并讨论以适配器随机融合追求更平坦的损失景观。

### 54. Rep Deep & Machine Learning: Exemplar-Free Continual Video Action Recognition via Slow-Fast Collaborative Learning

- **作者**：Xueyi Zhang, Chengwei Zhang, Zheng Li, Xiyu Wang, Siqi Cai, Mingrui Lao, Yanming Guo, Huiping Zhuang
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i42.40924
- **关键词**：exemplar-free, distillation, catastrophic forgetting
- **摘要**：该工作研究无示例的持续视频动作识别，并提出慢快协同学习框架 SFCL。

### 55. Shared & Domain Self-Adaptive Experts with Frequency-Aware Discrimination for Continual Test-Time Adaptation

- **作者**：Jianchao Zhao, Chenhao Ding, SongLin Dong, Jiangyang Li, Qiang Wang, Yuhang He, Yihong Gong
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i34.40102
- **关键词**：test-time adaptation, benchmark
- **摘要**：面向持续测试时适应，该频率感知框架采用共享专家与域自适专家，其双分支结构提取通用特征并动态建模域特定表示。

### 56. Sparse Tuning Enhances Plasticity in PTM-based Continual Learning

- **作者**：Huan Zhang, Shenghua Fan, Shuyu Dong, Yujin Zheng, Dingwen Wang, Fan Lyu
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i33.40050
- **关键词**：regularization, architecture / parameter isolation, benchmark
- **摘要**：MIST 是即插即用的互信息引导稀疏调参方法，按照对互信息目标的敏感度，选择性更新预训练模型中的一小部分参数，以增强基于预训练模型的持续学习可塑性。

### 57. Structural Entropy Guided Incremental Learning for Open-World Multimodal Social Event Detection

- **作者**：Zhiwei Yang, Haimei Qin, Xiaoyan Yu, Hao Peng, Lei Jiang, Li Sun, Zhiqin Yang
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i19.38647
- **关键词**：distillation, benchmark
- **摘要**：SeInEvent 以结构熵引导增量学习，用于开放世界多模态社会事件检测。

### 58. Topology-aware Knowledge Preservation for Class-Incremental Learning

- **作者**：Han Zang, Yongfeng Dong, Linhao Li, Liang Yang, Yu Wang
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i33.40031
- **关键词**：class-incremental, distillation, catastrophic forgetting, benchmark
- **摘要**：为捕捉特征空间中的多尺度结构模式，该工作提出利用持久同调的拓扑感知蒸馏框架，用于类别增量学习中的知识保持。

### 59. Towards Multimodal Continual Knowledge Embedding with Modality Forgetting Modulation

- **作者**：Xiaowen Jiang, Jing Yang, ShunDong Yang, Yuan Gao, Xinfa Jiang, Laurence Tianruo Yang, Jieming Yang
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i17.38516
- **关键词**：catastrophic forgetting, graph
- **摘要**：MoFot 面向不断增长的多模态知识图谱，提出带有模态遗忘调制的多模态持续表示学习框架。

### 60. Unified Representation Causal Prompt Distillation for Re-Inference-Free Lifelong Person Re-Identification

- **作者**：Jiaqi Zhao, Jie Luo, Yong Zhou, Wen-Liang Du, Xixi Li, Rui Yao
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i15.38315
- **关键词**：distillation, architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：URCPD 面向无需重新推理的终身行人重识别，提出统一表示因果提示蒸馏。

### 61. Unifying Locality of KANs and Feature Drift Compensation Projection for Data-Free Replay Based Continual Face Forgery Detection

- **作者**：Tianshuo Zhang, Siran Peng, Li Gao, Haoyuan Zhang, Xiangyu Zhu, Zhen Lei
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i15.38274
- **关键词**：catastrophic forgetting
- **摘要**：KAN-CFD 面向无真实数据回放的持续人脸伪造检测，包含域组 KAN 检测器 DG-KD，以及通过 KAN 漂移补偿投影进行特征分离的 FS-KDCP，并统一 KAN 的局部性与特征漂移补偿。

### 62. Vision-language Incremental Learning with Dual Class-individual Memory

- **作者**：Fuhai Chen, Feng Zhang, XiaoGuang Ma, Yiyi Zhou, Jiarong Liu, Xuri Ge
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i4.37273
- **关键词**：continual learning
- **摘要**：现有视觉语言增量学习方法大多沿用单模态范式，未能应对视觉模态与语言模态之间的根本差别。本文讨论类别与个体双记忆。

### 63. YOLO-IOD: Towards Real Time Incremental Object Detection

- **作者**：Shizhou Zhang, Xueqiang Lv, Yinghui Xing, Qirui Wu, Di Xu, Chen Zhao, Yanning Zhang
- **会议**：AAAI 2026 · 主会
- **官方页面**：https://doi.org/10.1609/aaai.v40i15.38271
- **关键词**：distillation, catastrophic forgetting, benchmark
- **摘要**：YOLO-IOD 基于预训练的 YOLO-World 构建实时增量目标检测框架，并通过分阶段的参数高效微调实现增量学习。

## Student Abstract（5 篇）

### 1. Branch, or Layer? Zeroth-Order Optimization for Continual Learning of Vision-Language Models

- **作者**：Ziwei Liu, Borui Kang, Wei Li, Hangjie Yuan, Yanbing Yang, Wenbin Li, Yifan Zhu, Tao Feng, Jun Luo
- **会议**：AAAI 2026 · Student Abstract
- **官方页面**：https://doi.org/10.1609/aaai.v40i28.39580
- **关键词**：architecture / parameter isolation, benchmark
- **摘要**：该工作系统探索把零阶优化用于基于参数高效微调的视觉语言持续学习，并考察优化应作用在分支上还是网络层上。

### 2. DeLo: Dual Decomposed Low-Rank Experts Collaboration for Continual Missing Modality Learning

- **作者**：Xiwei Liu, Yulong Li, Feilong Tang, Imran Razzak
- **会议**：AAAI 2026 · Student Abstract
- **官方页面**：https://doi.org/10.1609/aaai.v40i28.39561
- **关键词**：architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：DeLo 面向持续缺失模态学习，采用双重分解的低秩专家架构，并让这些专家相互协同。

### 3. New Metrics for Disambiguating Feature Overlap and Catastrophic Forgetting in Incremental Learning Contexts (Student Abstract)

- **作者**：Niklas M. Melton, Leonardo Enzo Brito Da Silva, Donald C. Wunsch
- **会议**：AAAI 2026 · Student Abstract
- **官方页面**：https://doi.org/10.1609/aaai.v40i48.42255
- **关键词**：replay / rehearsal, regularization, catastrophic forgetting
- **摘要**：Overlap Index 由 iCONN 指数的簇间分量改写而来，是一种增量聚类有效性指标，用于量化输入空间或潜空间中特征表示的重叠，从而在增量学习中区分特征重叠与灾难性遗忘。

### 4. ORTCL: Towards Continual Learning of Time Series Foundation Models on Streaming Data via Orthogonal Rotation

- **作者**：Li Lin, Xinrui Zhang, Qi Zhang, Shuai Wang, Kaiwen Xia
- **会议**：AAAI 2026 · Student Abstract
- **官方页面**：https://doi.org/10.1609/aaai.v40i28.39526
- **关键词**：catastrophic forgetting, lifelong / continual model editing, foundation models
- **摘要**：ORTCL 基于正交旋转变换，支持时间序列基础模型在流式数据上的持续学习。

### 5. Time Series Class-Incremental Learning via Confidence-guided Mask Distillation and Prototype-guided Contrastive Learning

- **作者**：Yu Liu, Haoqin Yang, Jinping Sui, Hui Wang, Haipeng Li, Weimin Wang, Qi Jia
- **会议**：AAAI 2026 · Student Abstract
- **官方页面**：https://doi.org/10.1609/aaai.v40i28.39568
- **关键词**：class-incremental, distillation, catastrophic forgetting, benchmark
- **摘要**：面向时间序列类别增量学习，置信度引导掩码蒸馏 CMD 用于防止蒸馏过程中继承噪声。该方法同时包括原型引导的对比学习。
