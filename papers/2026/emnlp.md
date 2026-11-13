# EMNLP 2026

检索窗口 2024-11-13 至 2026-11-13 内，与持续学习、终身学习或增量学习相关的 EMNLP 2026 论文，共 43 篇。主会 25 篇，Findings 17 篇，Workshop 0 篇，其他 1 篇。

主会数字包含该会议的官方主会轨道；NeurIPS 的 Datasets and Benchmarks 单独成节，仍计入主会。Findings、Workshop、Industry、Student Abstract 与 Short 另行标注。

## 主会（25 篇）

### 1. ANCHORS: Adaptive Normalization for Continual High-Order Retention via Sigmoid-Guided Magnitude Control

- **作者**：Yuxuan Zhang, Jiaqi Zhu
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.1215/
- **PDF**：https://aclanthology.org/2026.emnlp-main.1215.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.1215
- **关键词**：replay / rehearsal, regularization, architecture / parameter isolation, catastrophic forgetting, foundation models, benchmark
- **摘要**：ANCHORS 以 S 形函数引导的幅度控制进行自适应归一化，在激进适配过程中保持知识持续留存，从而应对稳定性与可塑性的困境，并实现持续的高阶保留。

### 2. AWARe: Mitigating Catastrophic Forgetting via Activation-Weighted Adaptive REtention

- **作者**：Juncheng Liao, Jinfan Lv, Guoming Wang, Juepeng Zheng, Ling Xiao, Siliang Tang
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.604/
- **PDF**：https://aclanthology.org/2026.emnlp-main.604.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.604
- **关键词**：catastrophic forgetting, foundation models
- **摘要**：AWARe 依据激活模式动态控制参数更新，以激活加权的自适应保留减轻微调中的灾难性遗忘。

### 3. CoDe-LoRA: Mitigating the Orthogonality Dilemma in Continual Learning of LLMs via Knowledge Consolidation and Decoupling

- **作者**：Maoqi Liu, Quan Fang, Yufei He
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.1188/
- **PDF**：https://aclanthology.org/2026.emnlp-main.1188.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.1188
- **关键词**：architecture / parameter isolation, catastrophic forgetting, foundation models, benchmark
- **摘要**：为减轻灾难性遗忘，已有工作采用带正交投影的低秩适配（如 O-LoRA）隔离任务参数；CoDe-LoRA 针对其中的正交性困境，通过知识巩固与解耦进行大语言模型的持续学习。

### 4. CPR for LLMs: Critical-Point Routing against Catastrophic Forgetting in Domain Adaptation

- **作者**：Kwangmin Ki, Yunhun Nam, Jongheon Jeong, Jaehyung Kim
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.1247/
- **PDF**：https://aclanthology.org/2026.emnlp-main.1247.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.1247
- **关键词**：catastrophic forgetting, foundation models
- **摘要**：现有方法通常修改监督微调损失来减轻遗忘，因而仍处在领域能力与通用能力的权衡之中；CPR 以临界点路由应对大语言模型领域适配中的灾难性遗忘。

### 5. CRAM: Centroid-Routing and Adaptive MoE for Multimodal Continual Instruction Tuning

- **作者**：Jun-Tao Tang, Zhen-Hao Xie, Yu-Cheng Shi, Da-Wei Zhou
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.1175/
- **PDF**：https://aclanthology.org/2026.emnlp-main.1175.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.1175
- **关键词**：architecture / parameter isolation, catastrophic forgetting, continual fine-tuning, foundation models, benchmark
- **摘要**：CRAM 结合质心路由与自适应混合专家，用于多模态持续指令微调。

### 6. DynaTokens: Controlling Token Dynamics for Continual Video-Language Understanding

- **作者**：Toan Nguyen, Yang Liu, Celso M De Melo, Flora D. Salim
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.2425/
- **PDF**：https://aclanthology.org/2026.emnlp-main.2425.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.2425
- **关键词**：domain-incremental, architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：DynaTokens 用基于 Transformer 的词元生成器按需动态产生微调词元，并通过共享生成权重实现随任务自适应的提示更新，以控制持续视频语言理解中的词元动态。

### 7. Forget What’s Sensitive, Remember What Matters: Token-Level Differential Privacy in Memory Sculpting for Continual Learning

- **作者**：Bihao Zhan, Jie Zhou, Junsong Li, Yutao Yang, Shilian Chen, Qianjun Pan, Xin Li, Wen Wu, Xingjiao Wu, Qin Chen, Hang Yan, Liang Dou, Liang He
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.39/
- **PDF**：https://aclanthology.org/2026.emnlp-main.39.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.39
- **关键词**：catastrophic forgetting
- **摘要**：PeCL 在记忆塑造中引入词元级差分隐私，使持续学习忘掉敏感内容并记住重要内容。

### 8. Generalizable Lifelong Model Editing via Preference Optimization

- **作者**：Dahyun Jung, Suhyune Son, Heuiseok Lim
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.170/
- **PDF**：https://aclanthology.org/2026.emnlp-main.170.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.170
- **关键词**：architecture / parameter isolation, lifelong / continual model editing, foundation models
- **摘要**：GLIME 把知识编辑与针对生成行为的偏好优化结合起来，以实现可泛化的终身模型编辑。

### 9. GR-SAP: Generative Replay for Safety Alignment Preservation during Fine-Tuning

- **作者**：Zhouxiang Fang, Jiawei Zhou, Hanjie Chen
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.50/
- **PDF**：https://aclanthology.org/2026.emnlp-main.50.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.50
- **关键词**：replay / rehearsal, foundation models
- **摘要**：受持续学习中生成式回放的启发，GR-SAP 从大语言模型合成领域特定的对齐数据，并在下游适配时加以整合，以在微调期间保持安全对齐。

### 10. HarmoLoRA: Commit-Stage Update Admission in Low-Rank Adaptation for Continual Speech Recognition

- **作者**：Ye-Eun Ko, Ji-Eun Choi, Dong-Hyun Kim, Joon-Hyuk Chang
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.2631/
- **PDF**：https://aclanthology.org/2026.emnlp-main.2631.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.2631
- **关键词**：architecture / parameter isolation, graph
- **摘要**：HarmoLoRA 用秩约束的提交算子，相对先前已提交方向分解当前任务的训练更新，构造秩封闭的残差提交路径，并以字典序约束规则进行选择，从而在持续语音识别的低秩适配中做提交阶段的更新准入。

### 11. How Do Large Language Models Learn Concepts During Continual Pre-Training?

- **作者**：Barry Menglong Yao, Sha Li, Yunzhi Yao, Minqian Liu, Zaishuo Xia, Qifan Wang, Lifu Huang
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.2437/
- **PDF**：https://aclanthology.org/2026.emnlp-main.2437.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.2437
- **关键词**：replay / rehearsal, continual pretraining, foundation models, graph
- **摘要**：人类主要通过概念这一抽象心理表征来组织感知、推理与学习；该文讨论大语言模型在持续预训练期间如何学习概念。

### 12. LadderEdit: Edit-Level Residual Compression for Memory-Efficient Lifelong Editing of LLMs

- **作者**：Xiaobing Yu, Peijie Qiu, Jin Yang, Xuanzhao Dong, Weiwei Ma, Zhaoqi An, Xiaoqi Zhao, Xiaofeng Liu
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.1261/
- **PDF**：https://aclanthology.org/2026.emnlp-main.1261.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.1261
- **关键词**：architecture / parameter isolation, lifelong / continual model editing, benchmark
- **摘要**：LadderEdit 在每个 LoRA 适配器获得之后将其压缩，以编辑级残差压缩实现大语言模型内存高效的终身编辑。

### 13. Lifelong Intent Discovery: A Continual Learning Protocol and Method

- **作者**：Peng Chen, Yu Xia, Bang Wang
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.705/
- **PDF**：https://aclanthology.org/2026.emnlp-main.705.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.705
- **关键词**：foundation models, benchmark
- **摘要**：发现新意图对系统适应用户不断变化的需求至关重要，因而本质上是持续过程；该文提出终身意图发现的持续学习协议与相应方法。

### 14. LifeMem: Enabling Lifelong Experience Reuse for LLM Agents

- **作者**：Yuli Qiu, Yutong Li, Wei Su, Zeming Liu, Wanxiang Che, Heyan Huang, Haifeng Wang, Yuhang Guo
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.1024/
- **PDF**：https://aclanthology.org/2026.emnlp-main.1024.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.1024
- **关键词**：catastrophic forgetting, foundation models
- **摘要**：LifeMem 让智能体在多个环境之间迁移知识，从而使大语言模型智能体能够终身复用经验。

### 15. Mitigating Forgetting Between Supervised and Reinforcement Learning Yields Stronger Reasoners

- **作者**：Xiangchi Yuan, Xiang Chen, Tong Yu, Dachuan Shi, Can Jin, Wenke Lee, Saayan Mitra
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.730/
- **PDF**：https://aclanthology.org/2026.emnlp-main.730.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.730
- **关键词**：architecture / parameter isolation, catastrophic forgetting, reinforcement learning
- **摘要**：MIFO 以即插即用的方式把监督微调并入强化学习，并显式约束监督微调所引起的更新，从而减轻两类学习之间的遗忘，以得到更强的推理模型。

### 16. Mitigating Memory Interference in Lifelong Model Editing through Multi-Head Hopfield Retrieval

- **作者**：Yue Che, Chen Guoyi, Xijian Deng, Yujie Wu, Jiang Cai, Xuming Ran, Mingkun Xu
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.1699/
- **PDF**：https://aclanthology.org/2026.emnlp-main.1699.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.1699
- **关键词**：lifelong / continual model editing, foundation models, benchmark
- **摘要**：MH-HoReN 在互补子空间上进行多头 Hopfield 检索，并组合各头的匹配信号，使终身模型编辑中的记忆选择更可靠，从而减轻记忆干扰。

### 17. OptiMer: Optimal Distribution Vector Merging Is Better than Data Mixing for Continual Pre-Training

- **作者**：Haiyue Song, Huy Hien Vu, Masao Utiyama
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.1090/
- **PDF**：https://aclanthology.org/2026.emnlp-main.1090.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.1090
- **关键词**：continual pretraining, benchmark
- **摘要**：OptiMer 把配比选择与训练解耦：为每个数据集单独训练一个持续预训练模型，提取表示该数据集所引起参数偏移的分布向量，再搜索最优组合，从而以分布向量合并进行持续预训练。

### 18. Plasticity without Collapse: Plasticity-Inducing Control Optimizer for Cross-Lingual Continual Pre-Training

- **作者**：Sumin Kim, Minjun Song, Surin Lee, S M Wahidur Rahman, Yongtae Lee, Haeung Choi, Heung-No Lee
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.528/
- **PDF**：https://aclanthology.org/2026.emnlp-main.528.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.528
- **关键词**：continual pretraining
- **摘要**：PICO 在更新层面处理可塑性与坍缩之间的困境，作为面向跨语言持续预训练的可塑性诱导控制优化器。

### 19. PRISM: Private Rank-Invariant Subspace Memory for Federated Continual Fine-Tuning under Local Differential Privacy

- **作者**：Ziyi Wang, Liang Liu, Zhu Meng, Zhicheng Zhao
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.313/
- **PDF**：https://aclanthology.org/2026.emnlp-main.313.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.313
- **关键词**：architecture / parameter isolation, continual fine-tuning
- **摘要**：PRISM 以固定秩 LoRA 沿数据流调度当前可塑秩，并对受差分隐私保护的聚合更新做收缩门控的记忆写入，从而在本地差分隐私下为联邦持续微调提供私有且秩不变的子空间记忆。

### 20. RECAP: Regression Evaluation for Continual Adaptation of Prompts

- **作者**：Harsh Deshpande, Kushal Chawla, Sangwoo Cho, William M. Campbell, Sambit Sahu
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.1684/
- **PDF**：https://aclanthology.org/2026.emnlp-main.1684.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.1684
- **关键词**：architecture / parameter isolation, benchmark
- **摘要**：RECAP 在严格的先适配后测试协议下，于约束层面度量遗忘、回退与前向迁移，并且提示优化方法只能获得约束信息，用以评测提示的持续适配。

### 21. ReProF: Residual Prototype Fusion for Continual LLM Attribution

- **作者**：Yujie Wang, Zhendong Mao, Quan Wang
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.2051/
- **PDF**：https://aclanthology.org/2026.emnlp-main.2051.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.2051
- **关键词**：replay / rehearsal, catastrophic forgetting, foundation models
- **摘要**：ReProF 无需训练，把特征提取器的层次划分为层块，并通过由浅到深的残差拟合得到深度感知的解析原型，用于持续的大语言模型归因。

### 22. Retrievable Gradients: Continual Post-Training Without Cumulative Weight Drift

- **作者**：Weihang Su, Jiacheng Kang, Jingyan Xu, Qingyao Ai, Jianming Long, Hanwen Zhang, Bangde Du, Xinyuan Cao, Min Zhang, Yiqun Liu
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.1197/
- **PDF**：https://aclanthology.org/2026.emnlp-main.1197.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.1197
- **关键词**：catastrophic forgetting, continual pretraining
- **摘要**：ReGrad 将梯度视为可检索的知识单元，用于避免累积权重漂移的持续后训练。

### 23. Small Models, Fewer Heads, More Forgetting: Sparse Attention Fine-Tuning for SLM Continual Learning

- **作者**：Hao Xu, Shezheng Song, Long Peng, Xiaodong Liu, Xiaopeng Li, Ma Jun, Shasha Li, Jie Yu
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.1099/
- **PDF**：https://aclanthology.org/2026.emnlp-main.1099.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.1099
- **关键词**：architecture / parameter isolation, benchmark
- **摘要**：LightLoRA 是专为小语言模型设计的稀疏微调方法，针对小模型注意力头更少、遗忘更严重的持续学习问题。

### 24. SPRInG: Continual LLM Personalization via Selective Parametric Adaptation and Retrieval-Interpolated Generation

- **作者**：Seoyeon Kim, Jaehyung Kim
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.1551/
- **PDF**：https://aclanthology.org/2026.emnlp-main.1551.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.1551
- **关键词**：replay / rehearsal, architecture / parameter isolation, catastrophic forgetting, foundation models, benchmark
- **摘要**：SPRInG 是面向大语言模型持续个性化的半参数框架，结合选择性参数适配与检索插值生成。

### 25. TORe: Rehearsal-Free Continual Learning for Table QA via Operation Recipe Reconstruction

- **作者**：Jinyu Zhang, Ruiheng Liu, Yu Zhang
- **会议**：EMNLP 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.emnlp-main.1320/
- **PDF**：https://aclanthology.org/2026.emnlp-main.1320.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-main.1320
- **关键词**：replay / rehearsal, foundation models, benchmark
- **摘要**：TORe 是面向表格问答的无重放框架，通过表模式感知的推理模式重建历史知识。

## Findings（17 篇）

### 1. A Benchmark for Self-Evolving Agents via Experience-Driven Lifelong Learning

- **作者**：Yuxuan Cai, Yipeng Hao, Jie Zhou, Hang Yan, Zhikai Lei, Rui Zheng, Zhenhua Han, Yutao Yang, Junsong Li, Qianjun Pan, Tianyu Huai, Qin Chen, Xin Li, Kai Chen, Bo Zhang, Xipeng Qiu, Liang He
- **会议**：EMNLP 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-emnlp.770/
- **PDF**：https://aclanthology.org/2026.findings-emnlp.770.pdf
- **DOI**：https://doi.org/10.18653/2026.findings-emnlp.770
- **关键词**：distillation, architecture / parameter isolation, benchmark
- **摘要**：StuLife 是面向自演化智能体的合成基准，用于评估与经验驱动终身学习相关的若干操作能力。

### 2. Ask Only When Needed: Proactive Retrieval from Memory and Skills for Experience-Driven Lifelong Agents

- **作者**：Yuxuan Cai, Wei Li, Jie Zhou, Qin Chen, Xin Li, Bo Zhang, Liang He
- **会议**：EMNLP 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-emnlp.775/
- **PDF**：https://aclanthology.org/2026.findings-emnlp.775.pdf
- **DOI**：https://doi.org/10.18653/2026.findings-emnlp.775
- **关键词**：continual learning
- **摘要**：ProactAgent 是经验驱动的终身学习框架，在结构化经验库上进行主动检索，使智能体只在需要时询问记忆与技能。

### 3. Beyond One-Hot Replay: Self-Distillation Reduces Target Variance in Continual Pre-Training

- **作者**：Peng Lu, Sijie Dong, Xiaoyun Feng, Xuanwei Hu, Xin Zhang
- **会议**：EMNLP 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-emnlp.1299/
- **PDF**：https://aclanthology.org/2026.findings-emnlp.1299.pdf
- **DOI**：https://doi.org/10.18653/2026.findings-emnlp.1299
- **关键词**：distillation, catastrophic forgetting, continual pretraining
- **摘要**：持续预训练把预训练语言模型适配到目标领域时，即便使用通用数据回放来缓解遗忘，通用能力仍常下降。本文关注超越 one-hot 回放、以自蒸馏降低目标方差。

### 4. Continual Fine-Tuning of Large Language Models via Program Memory

- **作者**：Hung Le, Svetha Venkatesh
- **会议**：EMNLP 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-emnlp.1048/
- **PDF**：https://aclanthology.org/2026.findings-emnlp.1048.pdf
- **DOI**：https://doi.org/10.18653/2026.findings-emnlp.1048
- **关键词**：architecture / parameter isolation, catastrophic forgetting, continual fine-tuning, foundation models, benchmark
- **摘要**：受互补学习系统启发，该工作提出带有程序记忆的持续 LoRA 框架，用于大语言模型的持续微调。

### 5. Continual Graph Memory for Adaptive Recommendation under Intent Drift

- **作者**：Hao Nguyen Ngoc, Tung Nguyen, Nguyen Thi Hanh, Dinh Thai Hoang, Nguyen Xuan Tung
- **会议**：EMNLP 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-emnlp.402/
- **PDF**：https://aclanthology.org/2026.findings-emnlp.402.pdf
- **DOI**：https://doi.org/10.18653/2026.findings-emnlp.402
- **关键词**：architecture / parameter isolation, foundation models, graph
- **摘要**：CGM-Rec 是持续图记忆框架，用于意图漂移下的自适应推荐。

### 6. EBS: Efficient Block-Sparse Framework for Continual Learning of Large Language Models

- **作者**：Zhixin Han, Hang Gao, Yinhao Bai, Yuhua Zhao, Bitong Luo, Zhiyu Li, Mengting Hu, Minlie Huang
- **会议**：EMNLP 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-emnlp.2462/
- **PDF**：https://aclanthology.org/2026.findings-emnlp.2462.pdf
- **DOI**：https://doi.org/10.18653/2026.findings-emnlp.2462
- **关键词**：architecture / parameter isolation, foundation models, benchmark
- **摘要**：为限制计算开销的持续增长，EBS 以块稀疏框架支持大语言模型的持续学习。

### 7. Entropy-Adaptive Fine-Tuning: Resolving Confident Conflicts to Mitigate Forgetting

- **作者**：Muxi Diao, Lele Yang, Wuxuan Gong, Yutong Zhang, Zhonghao Yan, Yufei Han, Kongming Liang, Weiran Xu, Zhanyu Ma
- **会议**：EMNLP 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-emnlp.703/
- **PDF**：https://aclanthology.org/2026.findings-emnlp.703.pdf
- **DOI**：https://doi.org/10.18653/2026.findings-emnlp.703
- **关键词**：catastrophic forgetting, reinforcement learning
- **摘要**：EAFT 以熵自适应微调消解高置信冲突，从而缓解遗忘。

### 8. Knowledge is Still There: Why RL Beats SFT for Sustainable Continual Machine Translation

- **作者**：Junhong Wu, Yang Zhao, Yangyifan Xu, Chengqing Zong
- **会议**：EMNLP 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-emnlp.2340/
- **PDF**：https://aclanthology.org/2026.findings-emnlp.2340.pdf
- **DOI**：https://doi.org/10.18653/2026.findings-emnlp.2340
- **关键词**：catastrophic forgetting, foundation models, reinforcement learning
- **摘要**：持续机器翻译的传统研究长期假定灾难性遗忘源于底层语言知识被不可逆擦除。本文讨论在知识仍然存在的前提下，为何强化学习比监督微调更有利于可持续的持续翻译。

### 9. Latent-LoRA: Compact Latent-Space Adapters with Gradient-Free Routing for Continual Learning

- **作者**：Reza Rahimi Azghan, Gautham Krishna Gudur, Pavan K. Turaga, Giulia Pedrielli, Hassan Ghasemzadeh
- **会议**：EMNLP 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-emnlp.1390/
- **PDF**：https://aclanthology.org/2026.findings-emnlp.1390.pdf
- **DOI**：https://doi.org/10.18653/2026.findings-emnlp.1390
- **关键词**：regularization, architecture / parameter isolation, catastrophic forgetting, foundation models, benchmark
- **摘要**：基于 LoRA 的持续学习通常为每个任务分配独立的低秩适配器，但现有方法要么在推理时依赖任务身份，要么无差别地累加全部适配器，使无关分支扭曲输出。Latent-LoRA 研究带免梯度路由的紧凑潜空间适配器。

### 10. MASkills: Continual Skills Optimization for Multi-Agent LLM Systems

- **作者**：Huaiyuan Yao, Xiaoou Liu, Charles Fleming, Tianlong Chen, Hua Wei
- **会议**：EMNLP 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-emnlp.1453/
- **PDF**：https://aclanthology.org/2026.findings-emnlp.1453.pdf
- **DOI**：https://doi.org/10.18653/2026.findings-emnlp.1453
- **关键词**：foundation models
- **摘要**：MASkills 通过智能体技能优化多智能体大语言模型系统，形成持续学习框架。

### 11. Mitigating New-Tail Collapse in Long-Tailed Class-Incremental Learning with CLIP

- **作者**：HyeokJun Lee, Sungmin Cha, YoungJoon Yoo
- **会议**：EMNLP 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-emnlp.1962/
- **PDF**：https://aclanthology.org/2026.findings-emnlp.1962.pdf
- **DOI**：https://doi.org/10.18653/2026.findings-emnlp.1962
- **关键词**：class-incremental, architecture / parameter isolation
- **摘要**：SBRL 依据 CLIP 的视觉—语言几何估计有效的旧类竞争者，并抑制它们对新类尾部样本施加的平滑旧侧压力，以缓解长尾类增量学习中的新尾部坍塌。

### 12. Not All Components Forget Alike: Component-Level Intervention Profiles in Continual Pretraining

- **作者**：Sangyeol Baek, Suan Lee
- **会议**：EMNLP 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-emnlp.1583/
- **PDF**：https://aclanthology.org/2026.findings-emnlp.1583.pdf
- **DOI**：https://doi.org/10.18653/2026.findings-emnlp.1583
- **关键词**：continual pretraining
- **摘要**：本文将相关结果呈现为稳健的组件级干预剖面，而不是证明 V/O 是遗忘的唯一因果存储位置，并指出持续预训练中并非所有组件都以同样方式遗忘。

### 13. P-Space: Puncturing the Null-Space to Resolve Cognitive Dissonance in Continual Knowledge Editing

- **作者**：Shiqiang Tian, Cheng Ding, Qin Chen, Jie Zhou, Xin Li, Liang He
- **会议**：EMNLP 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-emnlp.757/
- **PDF**：https://aclanthology.org/2026.findings-emnlp.757.pdf
- **DOI**：https://doi.org/10.18653/2026.findings-emnlp.757
- **关键词**：architecture / parameter isolation, lifelong / continual model editing, benchmark
- **摘要**：为化解持续知识编辑中的认知失调，P-Space 在每个编辑步骤刺破受保护的协方差，从而解除对过时表示的保护。

### 14. PEAM: Parametric Embodied Agent Memory for Continual Skill Learning via Internalization of Experience in Minecraft

- **作者**：Yuchen Guo, Junli Gong, Weicheng Wang, Hongmin Cai, Yiu-ming Cheung, Weifeng Su
- **会议**：EMNLP 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-emnlp.1326/
- **PDF**：https://aclanthology.org/2026.findings-emnlp.1326.pdf
- **DOI**：https://doi.org/10.18653/2026.findings-emnlp.1326
- **关键词**：architecture / parameter isolation, catastrophic forgetting, foundation models
- **摘要**：PEAM 在 Minecraft 中把智能体记忆从推理时检索转变为经经验内化、驻留于参数中的技能，用于持续技能学习。

### 15. Take Only What You Need: Rank Minimization as an Implicit Forgetting Regularizer in Continual Learning

- **作者**：Haodong Lu, Chongyang Zhao, Jason Xue, Lina Yao, Kristen Moore, Dong Gong
- **会议**：EMNLP 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-emnlp.806/
- **PDF**：https://aclanthology.org/2026.findings-emnlp.806.pdf
- **DOI**：https://doi.org/10.18653/2026.findings-emnlp.806
- **关键词**：regularization, architecture / parameter isolation
- **摘要**：CoDyRA 对每次 LoRA 更新联合进行秩最小化，通过对各分量重要性权重施加促进稀疏的正则，把秩最小化用作持续学习中的隐式遗忘正则。

### 16. TSRL: Trigger-based Supervised Reinforcement Learning for Continual Agent Training

- **作者**：Yuqian Fu, Kaiwen Jiang, Zijun Song, Jiawei Wang, Yuanheng Zhu, Dongbin Zhao
- **会议**：EMNLP 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-emnlp.19/
- **PDF**：https://aclanthology.org/2026.findings-emnlp.19.pdf
- **DOI**：https://doi.org/10.18653/2026.findings-emnlp.19
- **关键词**：catastrophic forgetting, foundation models, reinforcement learning, benchmark
- **摘要**：TSRL 是面向持续智能体训练的触发式监督强化学习框架，通过自适应且随状态变化的专家监督机制结合两种范式的长处。

### 17. Unifying Detection and Adaptation in Task-Free Continual Learning

- **作者**：Dezheng Han, Anbang Zhang, Zhihao Zhu, Shuaishuai Guo
- **会议**：EMNLP 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-emnlp.721/
- **PDF**：https://aclanthology.org/2026.findings-emnlp.721.pdf
- **DOI**：https://doi.org/10.18653/2026.findings-emnlp.721
- **关键词**：architecture / parameter isolation, catastrophic forgetting, foundation models
- **摘要**：为缓解大语言模型下游持续学习中的灾难性遗忘，现有方法通常约束参数更新或引入任务特定的适配模块。本文进一步研究无任务边界条件下检测与适配的统一。

## Industry（1 篇）

### 1. When Synthetic Data Hurts: On Catastrophic Forgetting in Skill Retrieval for LLM Agents

- **作者**：Syed Shariyar Murtaza, Yifan Nie, Utkarsh Soni, Eugene Wen, Arvid Frydenlund
- **会议**：EMNLP 2026 · Industry
- **官方页面**：https://aclanthology.org/2026.emnlp-industry.172/
- **PDF**：https://aclanthology.org/2026.emnlp-industry.172.pdf
- **DOI**：https://doi.org/10.18653/2026.emnlp-industry.172
- **关键词**：regularization, catastrophic forgetting, foundation models, benchmark
- **摘要**：本文展示一个生产级技能路由器，并在真实监督有限且使用合成数据的条件下，大规模考察大语言模型智能体技能检索中的灾难性遗忘。
