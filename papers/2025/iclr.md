# ICLR 2025

检索窗口 2024-11-13 至 2026-11-13 内，与持续学习、终身学习或增量学习相关的 ICLR 2025 论文，共 41 篇。主会 41 篇，Findings 0 篇，Workshop 0 篇，其他 0 篇。

主会数字包含该会议的官方主会轨道；NeurIPS 的 Datasets and Benchmarks 单独成节，仍计入主会。Findings、Workshop、Industry、Student Abstract 与 Short 另行标注。

## 主会（41 篇）

### 1. A Second-Order Perspective on Model Compositionality and Incremental Learning

- **作者**：Angelo Porrello, Lorenzo Bonicelli, Pietro Buzzega, Monica Millunzi, Simone Calderara, Rita Cucchiara
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=OZVTqoli2N
- **关键词**：continual learning
- **摘要**：深度预训练模型的微调呈现出组合性，多个专用模块可以任意组合成单一的多任务模型。该文从二阶视角讨论这种模型组合性与增量学习。

### 2. Active Learning for Continual Learning: Keeping the Past Alive in the Present

- **作者**：Jaehyun Park, Dongmin Park, Jae-Gil Lee
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=mnLmmtW7HO
- **关键词**：catastrophic forgetting
- **摘要**：AccuACL 把费舍尔信息矩阵用作样本选择准则，按累积信息量进行主动持续学习，使过去的信息在当前学习中仍然起作用。

### 3. Adapt-$\infty$: Scalable Continual Multimodal Instruction Tuning via Dynamic Data Selection

- **作者**：Adyasha Maharana, Jaehong Yoon, Tianlong Chen, Mohit Bansal
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=EwFJaXVePU
- **关键词**：catastrophic forgetting, continual fine-tuning, foundation models, benchmark
- **摘要**：Adapt-∞ 把终身指令微调改写成数据选择问题：模型依据当前已经获得的知识，从早期数据和新数据中自动挑选有益样本，以支持可扩展的持续多模态指令微调。

### 4. ADAPT: Attentive Self-Distillation and Dual-Decoder Prediction Fusion for Continual Panoptic Segmentation

- **作者**：Ze Yang, Shichao Dong, Ruibo Li, Nan Song, Guosheng Lin
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=HF1UmIVv6a
- **关键词**：distillation, catastrophic forgetting, benchmark
- **摘要**：现有持续全景分割方法常常在效率或可扩展性上受限。ADAPT 用注意力自蒸馏和双解码器预测融合来做持续全景分割。

### 5. Adaptive Retention & Correction: Test-Time Training for Continual Learning

- **作者**：Haoran Chen, Micah Goldblum, Zuxuan Wu, Yu-Gang Jiang
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=9bLdbp46Q1
- **关键词**：benchmark
- **摘要**：传统方法大多在训练阶段加入历史任务的数据来缓解这一问题。自适应保持与校正把持续学习放到测试时训练中处理。

### 6. Advancing Prompt-Based Methods for Replay-Independent General Continual Learning

- **作者**：Zhiqi KANG, Liyuan Wang, Xingxing Zhang, Karteek Alahari
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=V6uxd8MEqw
- **关键词**：replay / rehearsal, architecture / parameter isolation, catastrophic forgetting
- **摘要**：MISA 通过掩码与初始会话适应，推进不依赖回放的通用持续学习中的提示方法。

### 7. Boosting Multiple Views for pretrained-based Continual Learning

- **作者**：Quyen Tran, Tung Lam Tran, Khanh Doan, Toan Tran, Dinh Phung, Khoat Than, Trung Le
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=AZR4R3lw7y
- **关键词**：architecture / parameter isolation, benchmark
- **摘要**：自改进过程用来妥善选择任务特定组件，并缓解误预测可能引起的特征偏移，从而增强基于预训练模型的持续学习中的多视图。

### 8. BrainUICL: An Unsupervised Individual Continual Learning Framework for EEG Applications

- **作者**：Yangxuan Zhou, Sha Zhao, Jiquan Wang, Haiteng Jiang, Shijian Li, Tao Li, Gang Pan
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=6jjAYmppGQ
- **关键词**：graph, benchmark
- **摘要**：受持续学习启发，BrainUICL 提出无监督的个体持续学习范式，用来在实践中处理脑电应用里的相应问题。

### 9. Budgeted Online Continual Learning by Adaptive Layer Freezing and Frequency-based Sampling

- **作者**：Minhyuk Seo, Hyunseo Koh, Jonghyun Choi
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=dOAkHmsjRX
- **关键词**：online continual learning, foundation models, benchmark
- **摘要**：不同的计算预算和存储预算会妨碍持续学习算法在实践中的公平比较。该文分别用浮点运算量和以字节计的总内存度量这两类预算，并在预算化的在线持续学习中采用自适应层冻结与基于频率的采样。

### 10. C-CLIP: Multimodal Continual Learning for Vision-Language Model

- **作者**：Wenzhuo Liu, Fei Zhu, Longhui Wei, Qi Tian
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=sb7qHFYwBc
- **关键词**：benchmark
- **摘要**：C-CLIP 引入来自多个领域的图像—描述数据，并建立面向视觉语言模型的多模态持续学习基准。

### 11. CLDyB: Towards Dynamic Benchmarking for Continual Learning with Pre-trained Models

- **作者**：Shengzhuang Chen, Yikai Liao, Xiaoxiao Sun, Kede Ma, Ying Wei
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=RnxwxGXxex
- **关键词**：foundation models, benchmark
- **摘要**：CLDyB 提出在动态基准上评估预训练模型持续学习方法的通用框架。

### 12. Closed-Form Merging of Parameter-Efficient Modules for Federated Continual Learning

- **作者**：Riccardo Salami, Pietro Buzzega, Matteo Mosconi, Jacopo Bonato, Luigi Sabetta, Simone Calderara
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=ROpY0qRUXL
- **关键词**：class-incremental, architecture / parameter isolation
- **摘要**：面向联邦持续学习中参数高效模块的闭式合并，LoRM 采用交替优化，每次只训练一个 LoRA 矩阵。

### 13. Continual Slow-and-Fast Adaptation of Latent Neural Dynamics (CoSFan): Meta-Learning What-How & When to Adapt

- **作者**：Ryan Missel, Linwei Wang
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=Dl3MsjaIdp
- **关键词**：replay / rehearsal, catastrophic forgetting
- **摘要**：CoSFan 是一个持续元学习框架，对潜在神经动力学进行持续的慢适应与快适应，并元学习应当适应什么、如何适应以及何时适应。

### 14. Convergence and Implicit Bias of Gradient Descent on Continual Linear Classification

- **作者**：Hyunji Jung, Hanseul Cho, Chulhee Yun
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=DTqx3iqjkz
- **关键词**：catastrophic forgetting
- **摘要**：关于持续线性分类上梯度下降的收敛性与隐式偏差，该文在任务按循环顺序给出时，对周期平均遗忘作出非渐近分析。分析表明，任务之间的对齐与灾难性遗忘及反向知识迁移密切相关。

### 15. Coreset Selection via Reducible Loss in Continual Learning

- **作者**：Ruilin Tong, Yuhang Liu, Javen Qinfeng Shi, Dong Gong
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=mAztx8QO3B
- **关键词**：replay / rehearsal, distillation, catastrophic forgetting, benchmark
- **摘要**：基于排练的持续学习通过保留并回放历史任务中的样本子集来缓解灾难性遗忘。该文讨论借助可约损失选择核心集。

### 16. Expand and Compress: Exploring Tuning Principles for Continual Spatio-Temporal Graph Forecasting

- **作者**：Wei Chen, Yuxuan Liang
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=FRzCIlkM7I
- **关键词**：architecture / parameter isolation, catastrophic forgetting, graph, benchmark
- **摘要**：EAC 是基于提示调优的持续时空图预测方法，遵循扩展与压缩这两条调优原则。

### 17. Federated Class-Incremental Learning: A Hybrid Approach Using Latent Exemplars and Data-Free Techniques to Address Local and Global Forgetting

- **作者**：Milad Khademi Nori, IL-MIN KIM, Guanghui Wang
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=ydREOIttdC
- **关键词**：class-incremental, replay / rehearsal, benchmark
- **摘要**：该文为联邦类增量学习建立数学框架，用来表述局部遗忘和全局遗忘。其混合途径使用潜在示例与无数据技术来处理这两类遗忘。

### 18. Federated Continual Learning Goes Online: Uncertainty-Aware Memory Management for Vision Tasks and Beyond

- **作者**：Giuseppe Serra, Florian Buettner
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=f65RuQgVlp
- **关键词**：catastrophic forgetting, benchmark
- **摘要**：该文面向在线联邦持续学习，处理以小批量流到达且只能处理一次的新数据，并覆盖不同模态。其记忆管理是不确定性感知的，对象包括视觉任务以及其他任务。

### 19. Federated Few-Shot Class-Incremental Learning

- **作者**：Muhammad Anwar Masum, Mahardhika Pratama, Lin Liu, H Habibullah, Ryszard Kowalczyk
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=ZiPoAlKf9Y
- **关键词**：class-incremental, few-shot incremental, architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：UOPP 是统一优化的原型提示模型，用来同时处理联邦少样本类增量学习中的灾难性遗忘、过拟合和原型偏差。

### 20. High-dimension Prototype is a Better Incremental Object Detection Learner

- **作者**：Yanjie Wang, Liqun Chen, Tianming Zhao, Tao Zhang, Guodong Wang, Luxin Yan, Sheng Zhong, Jiahuan Zhou, Xu Zou
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=6T8czSBWce
- **关键词**：distillation, catastrophic forgetting
- **摘要**：围绕增量目标检测中的高维原型，GMDP 基于高斯混合分布构造原型，通过直接度量新旧模型嵌入落入各类的似然，显式建模不同类别之间的分布关系。

### 21. LeanAgent: Lifelong Learning for Formal Theorem Proving

- **作者**：Adarsh Kumarappan, Mohit Tiwari, Peiyang Song, Robert Joseph George, Chaowei Xiao, Anima Anandkumar
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=Uo4EHT4ZZ8
- **关键词**：foundation models, benchmark
- **摘要**：LeanAgent 是面向形式定理证明的终身学习框架，能够在不断扩展的数学知识上持续泛化并改进，同时不遗忘先前已经学到的知识。

### 22. LiNeS: Post-training Layer Scaling Prevents Forgetting and Enhances Model Merging

- **作者**：Ke Wang, Nikos Dimitriadis, Alessandro Favero, Guillermo Ortiz-Jimenez, François Fleuret, Pascal Frossard
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=J5sUOvlLbQ
- **关键词**：catastrophic forgetting, foundation models
- **摘要**：LiNeS 在训练之后按层递增地缩放网络，旨在保留预训练模型的泛化并增强微调任务上的表现，从而防止遗忘并改善模型合并。

### 23. LOIRE: LifelOng learning on Incremental data via pre-trained language model gRowth Efficiently

- **作者**：Xue Han, Yitong Wang, Junlan Feng, wenchun.gao, Qian Hu, Chao Deng
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=F5PlYMC5ik
- **关键词**：distillation, catastrophic forgetting
- **摘要**：LOIRE 使预训练语言模型能够利用增量数据有效扩展自身容量，从而进行终身学习。

### 24. Meta-Continual Learning of Neural Fields

- **作者**：Seungyoon Woo, Junhyeog Yun, Gunhee Kim
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=OCpxDSn0G4
- **关键词**：catastrophic forgetting, benchmark
- **摘要**：神经场已成为表示复杂数据的通用框架。该文讨论神经场上的元持续学习。

### 25. Mining your own secrets: Diffusion Classifier Scores for Continual Personalization of Text-to-Image Diffusion Models

- **作者**：Saurav Jha, Shiqi Yang, Masato Ishii, Mengjie Zhao, Christian Simon, Muhammad Jehanzeb Mirza, Dong Gong, Lina Yao, Shusuke Takahashi, Yuki Mitsufuji
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=hUdLs6TqZL
- **关键词**：regularization, architecture / parameter isolation, benchmark
- **摘要**：该文用扩散分类器分数正则化文生图扩散模型的参数空间和函数空间，以支持持续个性化。

### 26. MIRACLE 3D: Memory-efficient Integrated Robust Approach for Continual Learning on 3D Point Clouds via Shape Model Construction

- **作者**：Hossein Resani, Behrooz Nasihatkon
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=ANBuEJesgx
- **关键词**：regularization, benchmark
- **摘要**：MIRACLE 3D 提出面向三维物体分类、内存高效且保护隐私的持续学习框架，途径是为三维点云构建形状模型。

### 27. Optimal Protocols for Continual Learning via Statistical Physics and Control Theory

- **作者**：Francesco Mori, Stefano Sarao Mannelli, Francesca Mignacco
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=rhhQjGj09A
- **关键词**：catastrophic forgetting
- **摘要**：神经网络顺序学习多个任务时经常出现灾难性遗忘，因为新任务上的训练会损害已经学过的任务。该文借助统计物理和控制论讨论持续学习的最优协议。

### 28. Privacy-Aware Lifelong Learning

- **作者**：Ozan Özdenizci, Elmar Rueckert, Robert Legenstein
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=UstOpZCESc
- **关键词**：task-incremental, replay / rehearsal, architecture / parameter isolation, catastrophic forgetting
- **摘要**：终身学习算法使模型能够逐步获得新知识，同时不遗忘已经学会的信息。该文研究这一过程中的隐私问题。

### 29. Prototype antithesis for biological few-shot class-incremental learning

- **作者**：Binghao Liu, Han Yang, Fang Wan, Fei Gu
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=bRqaHn3J5I
- **关键词**：class-incremental, few-shot incremental, catastrophic forgetting, benchmark
- **摘要**：原型对偶方法利用生物分类群的层次结构，减轻生物学少样本类增量学习中新旧物种之间的混淆。

### 30. PseDet: Revisiting the Power of Pseudo Label in Incremental Object Detection

- **作者**：Qiuchen Wang, Zehui Chen, Chenhongyi Yang, Jiaming Liu, Zhenyu Li, Feng Zhao
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=Iu8FVcUmVp
- **关键词**：replay / rehearsal, distillation, catastrophic forgetting, benchmark
- **摘要**：现有增量目标检测大多采用响应级知识蒸馏，让教师模型在新的训练数据上做隐式记忆回放，以克服遗忘。PseDet 重新审视伪标签在这一设定中的作用。

### 31. RECAST: Reparameterized, Compact weight Adaptation for Sequential Tasks

- **作者**：Nazia Tasnim, Bryan Plummer
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=J3H8Az3YlB
- **关键词**：architecture / parameter isolation, benchmark
- **摘要**：RECAST 用重参数化的紧凑权值适应处理顺序任务，从而大幅减少任务特定的可训练参数。

### 32. SD-LoRA: Scalable Decoupled Low-Rank Adaptation for Class Incremental Learning

- **作者**：Yichen Wu, Hongming Piao, Long-Kai Huang, Renzhen Wang, Wanhua Li, Hanspeter Pfister, Deyu Meng, Kede Ma, Ying Wei
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=5U1rlpX68A
- **关键词**：class-incremental, replay / rehearsal, architecture / parameter isolation, foundation models, benchmark
- **摘要**：SD-LoRA 面向类增量学习，在不使用排练的情况下，持续把 LoRA 分量的幅度学习与方向学习分开。

### 33. Self-Normalized Resets for Plasticity in Continual Learning

- **作者**：Vivek Farias, Adam Jozefiak
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=G82uQztzxl
- **关键词**：regularization
- **摘要**：自归一化重置会在有证据表明某个神经元的发放率实际上已经降到零时重置其权重，以缓解持续学习中的可塑性损失。

### 34. Semantic Aware Representation Learning for Lifelong Learning

- **作者**：Fahad Sarfraz, Elahe Arani, Bahram Zonooz
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=WwwJfkGq0G
- **关键词**：continual learning
- **摘要**：SARL 采用稀疏激活，并以有原则的方式评估不同任务中物体之间的相似度，再用这些相似度引导终身学习中的表示学习。

### 35. Spurious Forgetting in Continual Learning of Language Models

- **作者**：Junhao Zheng, Xidi Cai, Shengjie Qiu, Qianli Ma
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=ScI7IlKGdI
- **关键词**：foundation models, benchmark
- **摘要**：该文引入冻结策略，固定语言模型的底层，以处理持续学习中的虚假遗忘，并在四种持续学习情形中改善表现。

### 36. STAR: Stability-Inducing Weight Perturbation for Continual Learning

- **作者**：Masih Eskandar, Tooba Imtiaz, Davin Hill, Zifeng Wang, Jennifer Dy
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=6N5OM5Duuj
- **关键词**：replay / rehearsal, catastrophic forgetting
- **摘要**：持续学习中缓解遗忘的一种常见做法，是保留少量已见样本并在训练时回放。STAR 研究能够诱导稳定性的权值扰动。

### 37. Theory on Mixture-of-Experts in Continual Learning

- **作者**：Hongbo Li, Sen Lin, Lingjie Duan, Yingbin Liang, Ness Shroff
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=7XgKAabsPp
- **关键词**：architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：持续学习因为能够适应随时间到来的新任务而受到关注。该文给出持续学习中混合专家模型的理论。

### 38. TSVD: Bridging Theory and Practice in Continual Learning with Pre-trained Models

- **作者**：Liangzu Peng, Juan Elenter, Joshua Agterberg, Alejandro Ribeiro, Rene Vidal
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=bqv7M0wc4x
- **关键词**：benchmark
- **摘要**：持续学习的目标是训练出能够顺序解决多个任务的模型。TSVD 用来衔接预训练模型持续学习中的理论与实践。

### 39. Unlocking Efficient, Scalable, and Continual Knowledge Editing with Basis-Level Representation Fine-Tuning

- **作者**：Tianci Liu, Ruirui Li, Yunzhe Qi, Hui Liu, Xianfeng Tang, Tianqi Zheng, Qingyu Yin, Monica Cheng, Jun Huan, Haoyu Wang, Jing Gao
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=PITFO1ddeh
- **关键词**：lifelong / continual model editing, foundation models, benchmark
- **摘要**：大语言模型已经在多种自然语言任务上取得突出表现。该文讨论用基级表示微调实现高效、可扩展且可持续的知识编辑。

### 40. Unlocking the Power of Function Vectors for Characterizing and Mitigating Catastrophic Forgetting in Continual Instruction Tuning

- **作者**：Gangwei Jiang, Caigao Jiang, Zhaoyi Li, Siqiao Xue, JUN ZHOU, Linqi Song, Defu Lian, Ying Wei
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=gc8QAQfXv6
- **关键词**：regularization, catastrophic forgetting, continual fine-tuning, foundation models, benchmark
- **摘要**：理论与实证分析表明，大语言模型中的灾难性遗忘主要来自功能激活的偏差，而不是任务处理功能被覆盖。该文据此用功能向量刻画并缓解持续指令微调中的遗忘。

### 41. Vision and Language Synergy for Rehearsal Free Continual Learning

- **作者**：Muhammad Anwar Masum, Mahardhika Pratama, Savitha Ramasamy, Lin Liu, H Habibullah, Ryszard Kowalczyk
- **会议**：ICLR 2025 · 主会
- **官方页面**：https://openreview.net/forum?id=9aZ2ixiYGd
- **关键词**：replay / rehearsal, architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：该文提出基于提示的结构与算法，用于无排练持续学习中的视觉与语言协同。其要点包括以语言作为提示生成的输入、按任务设置生成器，以及借助软任务标识预测限制匹配描述符的搜索范围。
