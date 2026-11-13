# ECCV 2026

检索窗口 2024-11-13 至 2026-11-13 内，与持续学习、终身学习或增量学习相关的 ECCV 2026 论文，共 30 篇。主会 30 篇，Findings 0 篇，Workshop 0 篇，其他 0 篇。

主会数字包含该会议的官方主会轨道；NeurIPS 的 Datasets and Benchmarks 单独成节，仍计入主会。Findings、Workshop、Industry、Student Abstract 与 Short 另行标注。

## 主会（30 篇）

### 1. Audio-Visual Continual Test-Time Adaptation without Forgetting

- **作者**：Sarthak Kumar Maharana, Akshay Mehra, Bhavya Ramakrishna, Yunhui Guo, Guan-Ming Su
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/4294.pdf
- **关键词**：catastrophic forgetting, test-time adaptation, benchmark
- **摘要**：基于融合层参数较强的跨任务可迁移性，AVReCAP 在无法访问任何源数据的情况下改善视听模型的测试时表现，并追求持续测试时适应中的不遗忘。

### 2. Beyond Disjoint Tasks: Towards More Natural Continual Learning for Vision-Language Models

- **作者**：Xiang Xu, Yiyang Su, Tianchen Zhao, Zheng Zhang, Zhuowen Tu, Anil Jain, Jonathan Wu
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/537.pdf
- **关键词**：architecture / parameter isolation, benchmark
- **摘要**：SOCiaL 识别并利用任务之间的共享结构，使视觉语言模型的持续学习能够超越任务互不相交的假设。

### 3. CaPCL: Caption-Preserved Continual Learning for Text-to-Image Retrieval

- **作者**：Naoya Sogi, Ren Ohkubo, Takashi Shibata, Makoto Terao, Yusuke Hosoya, Takayuki Okatani
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/9419.pdf
- **关键词**：distillation, catastrophic forgetting, benchmark
- **摘要**：为考察文到图检索持续学习中的相关现象，本文引入两项诊断指标：以主子空间相似度衡量图像域重叠，以图像条件下的查询概率量化文本查询分歧。CaPCL 关注在这一过程中保持描述文本。

### 4. CL-Anomaly: Layer-Adaptive Mixture-of-Experts with Multimodal Large Language Model for Continual Learning in Anomaly Detection

- **作者**：Wen Dong, Zhao Wang, Shuangqing Zhang, Kai Sun, Ben Li, Guosen Xie, Caifeng Shan, Fang Zhao
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/3639.pdf
- **关键词**：class-incremental, architecture / parameter isolation, foundation models
- **摘要**：CL-Anomaly 基于隔离与共享的协作，对多模态大语言模型进行参数高效微调，并以按层自适应的混合专家支持异常检测中的持续学习。

### 5. COLA: Continual Orthogonal Low-Rank Adaptation for Class-Incremental Learning

- **作者**：Monu Nagar, Debasis Das
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/10799.pdf
- **关键词**：class-incremental, replay / rehearsal, architecture / parameter isolation, catastrophic forgetting, foundation models
- **摘要**：COLA 是无重放、参数高效的类增量持续学习框架，将 LoRA 的低秩适配与受 Oja 启发、可增量逼近的学习规则结合起来。

### 6. D-VLAM: Differential Vision and Language Mixing for Rehearsal Free Continual Learning

- **作者**：Muhammad Anwar Ma'sum, Mohsen Guizani, Waseem Ullah
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/13415.pdf
- **关键词**：replay / rehearsal, architecture / parameter isolation, catastrophic forgetting, foundation models, Robustness, Privacy, Learning & Theory
- **摘要**：在无重放约束的动态环境中，语言引导的提示式持续学习被视为应对灾难性遗忘的一条途径。D-VLAM 进一步研究视觉与语言的差异化混合。

### 7. DeCoFlow: Structural Decomposition of Normalizing Flows for Continual Anomaly Detection

- **作者**：Hun Im, Jungi Lee, Subeen Cha, Pilsung Kang
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/7227.pdf
- **关键词**：architecture / parameter isolation, catastrophic forgetting, graph
- **摘要**：DeCoFlow 将子网络分解为冻结的通用基座与任务特定的低秩适配器，从而隔离更新，用于归一化流上的持续异常检测。

### 8. Deconfounded Lifelong Learning for Autonomous Driving via Dynamic Knowledge Spaces

- **作者**：Jiayuan Du, Yuebing Song, Yiming Zhao, Xianghui Pan, Jiawei Lian, Yuchu Lu, Liuyi Wang, Chengju Liu, Qijun Chen
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/4347.pdf
- **关键词**：catastrophic forgetting
- **摘要**：DeLL 将狄利克雷过程混合模型与因果推断中的前门调整结合起来，借助动态知识空间进行自动驾驶中的去混杂终身学习。

### 9. Distill Once, Adapt Life-Long: Exploring Dataset Distillation for Continual Test-Time Adaptation

- **作者**：Hyun-Kurl Jang, Jihun Kim, Hyeokjun Kweon, KUK-JIN YOON
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/3046.pdf
- **关键词**：distillation, catastrophic forgetting, test-time adaptation, benchmark
- **摘要**：DO-ALL 在部署前进行数据集蒸馏以得到少量合成数据，并以紧凑、注重隐私的形式重新利用源信息，作为即插即用框架支持持续测试时适应。

### 10. Dual-Generalization-aware Minimization for Continual Fine-Tuning of Vision-Language Models

- **作者**：Yanan Chen, Tieliang Gong, Yanle Lyu, Yuanhong Zhang, Weizhan Zhang
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/1281.pdf
- **关键词**：continual fine-tuning, foundation models
- **摘要**：DGM 是面向视觉语言模型持续适配的即插即用优化框架，它扩展平坦性感知训练，并重新定义扰动目标以同时促进双重泛化。

### 11. Enhancing Pretrained Model-based Continual Representation Learning via Guided Random Projection

- **作者**：Ruilin Li, Heming Zou, Xiufeng Yan, Zheming Liang, Jie Yang, Chenliang Li, Xue Yang
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/7991.pdf
- **关键词**：class-incremental, exemplar-free, benchmark, Robustness, Privacy, Learning & Theory
- **摘要**：SCL-MGSM 是带有 MemoryGuard 监督机制的随机持续学习器，借助引导随机投影增强基于预训练模型的持续表示学习。

### 12. Fisher-Routed Mixture of Experts for Federated Class-Incremental Learning

- **作者**：Wenhao Yuan, Chenchen Lin, Jian Chen, Jinfeng Xu, Zewei Liu, Edith C. H. Ngai
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/6181.pdf
- **关键词**：class-incremental, regularization, architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：FedFMX 以 Fisher 路由的混合专家实现跨客户端的自适应专家专业化，用于联邦类增量学习。

### 13. Geometry-Anchored Transport Framework for Exemplar-Free Class-Incremental Learning

- **作者**：Hongye Xu, Bartosz Krawczyk
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/6505.pdf
- **关键词**：class-incremental, exemplar-free, Robustness, Privacy, Learning & Theory
- **摘要**：面向无样本类增量学习，该几何锚定传输框架首先通过马氏对齐回归导出解析几何锚点，以减轻宏观各向异性漂移。

### 14. Interference-Aware Continual Vision–Language Learning via Instance-Level Expert Routing

- **作者**：Zhang Changyuan, Tianxiang Xu, Canran Xiao, Fei Shen
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/8007.pdf
- **关键词**：architecture / parameter isolation
- **摘要**：该干扰感知的适配器路由框架为每个样本估计度量一致的投影能量以量化潜在干扰，并在容量均衡下路由到干扰最小的专家，用于实例级的持续视觉—语言学习。

### 15. LANCE: Low Rank Activation Compression for Efficient On-Device Continual Learning

- **作者**：Marco Apolinario, Kaushik Roy
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/14194.pdf
- **关键词**：catastrophic forgetting, benchmark
- **摘要**：LANCE 通过一次性高阶奇异值分解得到可复用的低秩子空间，用于激活投影，从而以低秩激活压缩支持端侧持续学习。

### 16. Learning Probabilistic Prompt for Continual Learning

- **作者**：Hyekang Park, Sanghoon Lee, Geon Lee, Jongyoun Noh, BUMSUB HAM
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/5331.pdf
- **关键词**：regularization, architecture / parameter isolation, benchmark, Robustness, Privacy, Learning & Theory
- **摘要**：本文提出基于概率提示的持续学习框架，用以捕捉任务序列中图像的多样模式。

### 17. Mitigate Modality-Asymmetric Forgetting via Stabilizing Visual Representations in CLIP-Based Class-Incremental Learning

- **作者**：Yuanhong Zhang, Yanan Chen, Xin Zhang, Zhaoyang Wang, Weizhan Zhang, Muyao Yuan, Hongjin Niu, LAN MA, Yuan Gao, Joey Tianyi Zhou
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/5550.pdf
- **关键词**：class-incremental, distillation, catastrophic forgetting, benchmark
- **摘要**：VAST 通过基于视觉锚点的结构迁移，在持续学习中稳定视觉表示，以缓解基于 CLIP 的类增量学习中模态不对称的遗忘。

### 18. Multi-Anchor Distillation with Text-Guided Analytic Classifier for Continual Learning

- **作者**：Qier Meng, De Cheng, Jiahao Li, Cheng Deng
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/337.pdf
- **关键词**：exemplar-free, distillation, regularization, catastrophic forgetting, Robustness, Privacy, Learning & Theory
- **摘要**：该无样本统一框架在编码器与分类器两个层面处理持续学习中的两类效应，并结合多锚点蒸馏与文本引导的解析分类器。

### 19. Online Versatile Incremental Learning: Towards Class and Domain-Agnostic Adaptation at Any Time

- **作者**：Jaeho Lee, Jun-Yeong Moon, Min-Yeong Park, Jung Uk Kim, Gyeong-Moon Park
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/3188.pdf
- **关键词**：continual learning
- **摘要**：TopFlow 以拓扑保持与流匹配表示构成两个互补机制，使在线多能增量学习能够适应更接近真实条件的动态环境，并随时进行与类别和领域无关的适应。

### 20. Orthogonal Knowledge Refreshing for Domain-Incremental Object Detection

- **作者**：Aoting Zhang, Dongbao Yang, Chang Liu, Xiaopeng Hong, Can Ma, Yu ZHOU
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/1365.pdf
- **关键词**：domain-incremental, exemplar-free
- **摘要**：OKR 以正交知识刷新应对域增量目标检测。

### 21. REAL-OW: Rehearsal-free Open World Object Detection with Low-Rank Adaptation and Dual-Stage Objectness Modeling

- **作者**：Huazhong Zhang, Xiaowen Fu, Yang Zhang, Linlin Shen, Jinbao Wang
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/9391.pdf
- **关键词**：replay / rehearsal, architecture / parameter isolation, catastrophic forgetting
- **摘要**：现有开放世界目标检测框架高度依赖样本回放来缓解灾难性遗忘，但保存原始数据会与访问限制冲突，并带来暴露风险和显著内存开销。REAL-OW 在无重放条件下结合低秩适配与双阶段目标性建模。

### 22. Rethinking Continual Anomaly Detection on the Edge: Benchmarking Under Realistic Industrial Conditions

- **作者**：Chad Weatherly, Sen Lin
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/1778.pdf
- **关键词**：replay / rehearsal, benchmark
- **摘要**：本文提出统一基准，涵盖结构异常与逻辑异常上的离散任务评估、连续漂移协议、对已发表持续异常检测方法的对照比较，以及边缘端的计算效率分析。

### 23. Safe Generalization: Mitigating Catastrophic Forgetting in Single-Source Multi-Organ Segmentation via Collaborative Causal Learning

- **作者**：Yucheng Song, Ruoxi Yu, Feng Shu, Cheng Huang, HaoKang Ding, Zhifang Liao
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/3142.pdf
- **关键词**：regularization, catastrophic forgetting
- **摘要**：CCL-Net 通过协同因果学习，在单源多器官分割中同时追求稳健泛化与源知识保持，以缓解灾难性遗忘。

### 24. SCORE: SubDistribution-aware Collaborative Knowledge Reinforcing for Cloth-Hybrid Lifelong Person Re-Identification

- **作者**：Kunlun Xu, Liangyu Ma, Jiangmeng Li, Xin Tong, Xiaode Liu, Yufei Guo, Jiahuan Zhou
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/4318.pdf
- **关键词**：catastrophic forgetting
- **摘要**：SCORE 显式建模同一身份内部的多样性，以持续巩固彼此区分的衣着一致信息与换装信息，用于衣着混合的终身行人重识别。

### 25. SCoT: Similarity-guided Conflict-aware Task Consolidation for Continual VQA

- **作者**：Anand Patel, Moloud Abdar, Biplab Banerjee
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/6213.pdf
- **关键词**：catastrophic forgetting
- **摘要**：SCoT 将每个任务表示为相对于预训练锚点模型的参数更新，并按层整合各任务，以相似性引导且感知冲突的方式进行持续视觉问答中的任务巩固。

### 26. Shared LoRA Subspaces for almost Strict Continual Learning

- **作者**：Prakhar Kaushik, Ankit Vaidya, Shravan Sunil Chaudhari, Rama Chellappa, Alan Yuille
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/1734.pdf
- **关键词**：architecture / parameter isolation, catastrophic forgetting, continual fine-tuning
- **摘要**：Share 面向近乎严格的持续学习，在参数高效持续微调中学习并动态更新单一共享低秩子空间，从而跨多个任务与模态进行适应。

### 27. SiGMA: Sign-Guided Merging and Adaptation framework for Multimodal Continual Instruction Tuning

- **作者**：Keonhee Park, Gunhee Kim
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/9629.pdf
- **关键词**：catastrophic forgetting, continual fine-tuning, foundation models, benchmark
- **摘要**：SiGMA 面向多模态持续指令微调，以训练阶段的符号引导自适应调参和推理阶段的符号引导合并来减轻负向干扰。

### 28. Spectral-Aware Analytic Class-Incremental Learning for Long-Tailed Distributions

- **作者**：Quyen Tran, Ngoc-Hai Nguyen, Minh Quan Dao, Zhuowei Li, Nam Hai, Trung Le, Dimitris N. Metaxas
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/4103.pdf
- **关键词**：class-incremental, regularization, Robustness, Privacy, Learning & Theory
- **摘要**：在长尾分布的解析式类别增量学习中，标准岭回归采用各向同性正则，这种均匀惩罚难以在稳定尾部类别的同时避免过度收缩头部类别。本文围绕谱感知的解析式类别增量学习讨论这一限制。

### 29. SUM: Unified Geometric Surgery on Spatio-Temporal Adaptation Vectors for Federated Class Incremental Learning

- **作者**：Jaeik Kim, Jaeyoung Do
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/5643.pdf
- **关键词**：class-incremental, catastrophic forgetting, benchmark
- **摘要**：SUM 是面向联邦类别增量学习的纯服务器端框架，在聚合阶段对时空适应向量做几何手术并加以合并。

### 30. VD-LoRA: Adaptive Reuse of Low-Rank Directions for Continual Learning

- **作者**：Luqiong Ding, Jiayao Tan, Chenggong Ni, Fuyuan Hu, Fan Lyu
- **会议**：ECCV 2026 · 主会
- **PDF**：https://media.eventhosts.cc/Conferences/ECCV2026/pdfs/10036.pdf
- **关键词**：class-incremental, replay / rehearsal, architecture / parameter isolation, benchmark
- **摘要**：VD-LoRA 是变分方向感知的贝叶斯框架，在低秩更新空间内进行自适应巩固，以便在持续学习中复用低秩方向。
