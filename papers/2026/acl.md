# ACL 2026

检索窗口 2024-11-13 至 2026-11-13 内，与持续学习、终身学习或增量学习相关的 ACL 2026 论文，共 41 篇。主会 28 篇，Findings 12 篇，Workshop 1 篇，其他 0 篇。

主会数字包含该会议的官方主会轨道；NeurIPS 的 Datasets and Benchmarks 单独成节，仍计入主会。Findings、Workshop、Industry、Student Abstract 与 Short 另行标注。

## 主会（28 篇）

### 1. Can Continual Pretraining Bridge the Performance Gap between General-purpose and Specialized Language Models in the Medical Domain?

- **作者**：Niclas Doll, Jasper Schulze Buschhoff, Shalaka Satheesh, Hammam Abdelwahab, Héctor Allende-Cid, Katrin Klug
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.17/
- **PDF**：https://aclanthology.org/2026.acl-long.17.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.17
- **关键词**：continual pretraining, benchmark
- **摘要**：该文通过持续预训练与模型合并进行领域适配，缩小医学领域中小型专用语言模型与规模大得多的通用模型之间的性能差距。

### 2. Can Large Language Models Keep Up? Benchmarking Online Adaptation to Continual Knowledge Streams

- **作者**：Jiyeon Kim, Hyunji Lee, Dylan Zhou, Sue Hyun Park, Seunghyun Yoon, Trung Bui, Franck Dernoncourt, Sungmin Cha, Minjoon Seo
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.1956/
- **PDF**：https://aclanthology.org/2026.acl-long.1956.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.1956
- **关键词**：foundation models, benchmark
- **摘要**：OAKS 建立面向持续更新知识流的在线适配基准，用以评估大语言模型跟上不断到来的知识的能力。

### 3. Can Spectral-Clipping Enable Better Learning While Forgetting Less for Low-Rank Adaptation?

- **作者**：Hyowon Wi, Noseong Park
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.1179/
- **PDF**：https://aclanthology.org/2026.acl-long.1179.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.1179
- **关键词**：architecture / parameter isolation, catastrophic forgetting
- **摘要**：该文建立理论联系，指出 LoRA 适配器奇异值的不受控增长会导致预训练知识遗忘，即灾难性遗忘，并由此讨论谱裁剪能否使低秩适配学得更好、忘得更少。

### 4. CL^2GEC: A Multi-Discipline Benchmark for Continual Learning in Chinese Literature Grammatical Error Correction

- **作者**：Shang Qin, Jingheng Ye, Yinghui Li, Hai-Tao Zheng, Qi Li, Jinxiao Shan, Zhixing Li, Hong-Gee Kim
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.1546/
- **PDF**：https://aclanthology.org/2026.acl-long.1546.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.1546
- **关键词**：regularization, catastrophic forgetting, foundation models, benchmark
- **摘要**：CL²GEC 是首个面向中文文学语法纠错的持续学习基准，用于在多个学科领域上评估自适应的中文语法纠错。

### 5. CTTA-T: Continual Test-Time Adaptation for Text Understanding via Teacher-Student with a Domain-aware and Generalized Teacher

- **作者**：Tianlun Liu, Zhiliang Tian, Zhen Huang, Xingzhi Zhou, Wanlong Yu, Tianle Liu, Feng Liu, Dongsheng Li
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.187/
- **PDF**：https://aclanthology.org/2026.acl-long.187.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.187
- **关键词**：test-time adaptation
- **摘要**：CTTA-T 采用师生框架进行文本理解上的持续测试时适应，使教师具备领域意识与泛化能力，以适配不断演化的目标领域。

### 6. DarwinTOD: LLM-Driven Lifelong Self-evolution for Task-oriented Dialog Systems

- **作者**：Shuyu Zhang, Yujie Liu, Xinru Wang, Cheng Zhang, Yanmin Zhu, Bin Li
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.2050/
- **PDF**：https://aclanthology.org/2026.acl-long.2050.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.2050
- **关键词**：foundation models
- **摘要**：DarwinTOD 是由大语言模型驱动的终身自演化任务型对话框架，能够从零样本基础出发持续优化策略，而无需针对具体任务做微调。

### 7. Data Mixing Agent: Learning to Re-weight Domains for Continual Pre-training

- **作者**：Kailai Yang, Xiao Liu, Lei Ji, Hao Li, Xiao Liang, Zhiwei Liu, Yeyun Gong, Peng Cheng, Mao Yang
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.427/
- **PDF**：https://aclanthology.org/2026.acl-long.427.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.427
- **关键词**：catastrophic forgetting, continual pretraining, foundation models, reinforcement learning, benchmark
- **摘要**：在小规模任务数据上做持续预训练可以提升大语言模型在新目标领域的表现，同时也有遗忘原有能力的风险；数据混合智能体学习为各个领域重新加权，以支持持续预训练。

### 8. Evolutionary Strategies at Scale lead to Catastrophic Forgetting

- **作者**：Immanuel Abdi, Akshat Gupta, Micah Mok, Alex Lu, Nicholas Lee, Gopala Anumanchipalli
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-short.18/
- **PDF**：https://aclanthology.org/2026.acl-short.18.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-short.18
- **关键词**：catastrophic forgetting
- **摘要**：该文指出进化策略这类无梯度算法在规模化时会出现灾难性遗忘，并希望促使后续工作缓解这一问题。

### 9. FOREVER: Forgetting Curve-Inspired Memory Replay for Language Model Continual Learning

- **作者**：Yujie Feng, Hao Wang, Jian Li, Xu Chu, Zhaolu Kang, Yiran Liu, Yasha Wang, Philip S. Yu, Xiao-Ming Wu
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.1144/
- **PDF**：https://aclanthology.org/2026.acl-long.1144.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.1144
- **关键词**：replay / rehearsal, regularization, catastrophic forgetting, foundation models, benchmark
- **摘要**：受大语言模型遗忘类似于艾宾浩斯人类遗忘曲线这一发现推动，FOREVER 使回放日程与以模型为中心的时间概念对齐，用于语言模型的持续学习。

### 10. From Curated Data to Scalable Models: Continual Pre-training of Dense and MoE Large Language Models for Tibetan

- **作者**：Lei Yang, Leiyu Pan, Bojian Xiong, Renren Jin, Shaowei Zhang, Yue Chen, Ling Shi, Jiang Zhou, Junru Wu, Zhen Wang, Jianxiang Peng, Juesi Xiao, Tianyu Dong, Zhuowen Han, Zhuo Chen, Yuqi Ren, Deyi Xiong
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.1866/
- **PDF**：https://aclanthology.org/2026.acl-long.1866.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.1866
- **关键词**：architecture / parameter isolation, continual pretraining, continual fine-tuning, foundation models, benchmark
- **摘要**：该文给出综合流程，通过大规模数据整理与持续预训练推进藏文语言建模，对象包括稠密模型与混合专家大语言模型。

### 11. From Experts to Bases: Orthogonal Subspace Mixture for Continual Multimodal Instruction Tuning

- **作者**：Pei Chen, Xilai Wang, Shiqixu, Zejian Li, Lingyun Sun
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.481/
- **PDF**：https://aclanthology.org/2026.acl-long.481.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.481
- **关键词**：architecture / parameter isolation, catastrophic forgetting, continual fine-tuning, foundation models, benchmark
- **摘要**：MoBLoRA 以基混合 LoRA 作为持续多模态指令微调框架，把专家组织为正交子空间上的基混合。

### 12. Harmonizing the Past, Present, and Future: A Null-Space Constrained Region-Specific Method for Continual Learning in LLMs

- **作者**：Jinhui Chen, Shizhu He, Xingchang Yang, Huanxuan Liao, Yequan Wang, Xiangwen Liao, Wenhao Teng, Kang Liu, Jun Zhao
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.1244/
- **PDF**：https://aclanthology.org/2026.acl-long.1244.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.1244
- **关键词**：catastrophic forgetting, foundation models, benchmark
- **摘要**：大语言模型的可持续演化需要同时保留已获得的知识、学会新的任务技能，并为后续学习预留足够的参数容量；该文用零空间约束的区域特定方法来协调过去、现在与未来。

### 13. HiEdit: Lifelong Model Editing with Hierarchical Reinforcement Learning

- **作者**：Yangfan Wang, Tianyang Sun, Chen Tang, Jie Liu, Wei Cai, Jingchi Jiang
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.1855/
- **PDF**：https://aclanthology.org/2026.acl-long.1855.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.1855
- **关键词**：catastrophic forgetting, lifelong / continual model editing, foundation models, reinforcement learning
- **摘要**：HiEdit 用层次强化学习为每个编辑实例自适应地确定与知识最相关的层，以支持终身模型编辑。

### 14. If an LLM Were a Character, Would It Know Its Own Story? Evaluating Lifelong Learning in LLMs

- **作者**：Siqi Fan, Xiusheng Huang, Yiqun Yao, Xuezhi Fang, Kang Liu, Peng Han, Shuo Shang, Aixin Sun, Yequan Wang
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.1659/
- **PDF**：https://aclanthology.org/2026.acl-long.1659.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.1659
- **关键词**：catastrophic forgetting, foundation models, benchmark
- **摘要**：LifeState-BENCH 用于评估大语言模型的终身学习，考察把模型当作一个角色时，它是否了解自己的故事。

### 15. Knowledge is Not Enough: Injecting RL Skills for Continual Adaptation

- **作者**：Pingzhi Tang, Yiding Wang, Muhan Zhang
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.550/
- **PDF**：https://aclanthology.org/2026.acl-long.550.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.550
- **关键词**：foundation models, reinforcement learning, benchmark
- **摘要**：PaST 以参数化技能迁移支持模块化的技能传递，把强化学习技能注入知识适配过程，从而实现持续适配。

### 16. Mitigating Catastrophic Forgetting in Target Language Adaptation of LLMs via Source-Shielded Updates

- **作者**：Atsuki Yamaguchi, Terufumi Morishita, Aline Villavicencio, Nikolaos Aletras
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.865/
- **PDF**：https://aclanthology.org/2026.acl-long.865.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.865
- **关键词**：catastrophic forgetting, foundation models
- **摘要**：源屏蔽更新（SSU）以选择性参数更新主动保护源语言知识，从而减轻大语言模型在目标语言适配中的灾难性遗忘。

### 17. MoCa: Modality-aware Continual Pre-training Makes Better Bidirectional Multimodal Embeddings

- **作者**：Haonan Chen, Hong Liu, Yuping Luo, Liang Wang, Nan Yang, Furu Wei, Zhicheng Dou
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.34/
- **PDF**：https://aclanthology.org/2026.acl-long.34.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.34
- **关键词**：continual pretraining, foundation models, benchmark
- **摘要**：MoCa 以模态感知的两阶段持续预训练，把预训练视觉语言模型转化为双向多模态嵌入模型。

### 18. MPBoCo: Multimodal Prompt-based Boundary-enhanced Continual Framework for Joint Entity and Relation Extraction

- **作者**：Guanglu Sun, Xinyu Liu, Lili Liang, Yang Yu, Fei Lang, Suxia Zhu, Ming Liu
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.1220/
- **PDF**：https://aclanthology.org/2026.acl-long.1220.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.1220
- **关键词**：architecture / parameter isolation, graph
- **摘要**：该文提出持续多模态实体与关系联合抽取任务 CMERJE，并给出多模态提示式、边界增强的持续框架 MPBoCo。

### 19. OASIS: Online Sample Selection for Continual Instruction Tuning

- **作者**：Minjae Lee, Minhyuk Seo, Tingyu Qu, Tinne Tuytelaars, Jonghyun Choi
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.158/
- **PDF**：https://aclanthology.org/2026.acl-long.158.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.158
- **关键词**：continual fine-tuning, foundation models
- **摘要**：OASIS 为持续指令微调做自适应的在线样本选择，通过估计每个样本相对全部已见数据的信息量来挑选样本，从而超出仅在批次内比较的限制。

### 20. PASs-MoE: Mitigating Misaligned Co-drift among Router and Experts via Pathway Activation Subspaces for Continual Learning

- **作者**：ZhiYan Hou, Haiyun Guo, Haokai Ma, Yandu Sun, Yonghui Yang, Jinqiao Wang
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.1474/
- **PDF**：https://aclanthology.org/2026.acl-long.1474.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.1474
- **关键词**：architecture / parameter isolation, continual fine-tuning, foundation models, benchmark
- **摘要**：通路激活子空间由 LoRA 诱导，反映输入在每个专家中激活了哪些低秩通路方向，并为路由与知识保持提供与能力对齐的坐标系，用以缓解持续学习中路由器与专家之间错位的共同漂移。

### 21. Perplexity-Aware Data Scaling Law: Perplexity Landscapes Predict Performance for Continual Pre-training

- **作者**：Lei Liu, Hao Zhu, Xiaoyan Yang, Yue Shen, Zhixuan Chu, Jian Wang, Jinjie Gu, Kui Ren
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.999/
- **PDF**：https://aclanthology.org/2026.acl-long.999.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.999
- **关键词**：continual pretraining, foundation models, benchmark
- **摘要**：该文提出困惑度感知的数据缩放律，在领域数据的困惑度景观与测试损失之间建立可预测关系，用于持续预训练。

### 22. Representation Interventions Enable Lifelong Knowledge Memory Control in LLMs

- **作者**：Xuyuan Liu, Shengyu Chen, Xinshuai Dong, Yanchi Liu, Xujiang Zhao, Haoyu Wang, Yujun Yan, Haifeng Chen, Zhengzhang Chen
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.246/
- **PDF**：https://aclanthology.org/2026.acl-long.246.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.246
- **关键词**：foundation models, benchmark
- **摘要**：RILKE 把知识控制视为模型表示空间中的干预，以稳健且可扩展的方式实现大语言模型的终身知识记忆控制。

### 23. SLoRA: Balancing Plasticity and Forgetting in Large Language Models for Continual Learning

- **作者**：Lina Yang, Yusheng Liao, Yanfeng Wang, Yu Wang
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.247/
- **PDF**：https://aclanthology.org/2026.acl-long.247.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.247
- **关键词**：regularization, architecture / parameter isolation, catastrophic forgetting, foundation models
- **摘要**：SLoRA 借助与基座模型的子空间相似度滤除 LoRA 更新中的噪声成分，从而在大语言模型持续学习中平衡可塑性与遗忘。

### 24. Soft Orthogonal Low-Rank Adaptation for Knowledge Sharing in Large Language Model Continual Learning

- **作者**：Yitong Wang, Xue Han, WenChun Gao, Qian Hu, Jiahui Wang, Ziqing Wang, Lijun Mei, Junlan Feng
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.842/
- **PDF**：https://aclanthology.org/2026.acl-long.842.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.842
- **关键词**：architecture / parameter isolation, catastrophic forgetting, foundation models
- **摘要**：现代大语言模型的持续学习既面临巨大参数规模带来的计算代价，现有方法又多以减轻灾难性遗忘为主要目标；该文以软正交低秩适配讨论其中的知识共享。

### 25. Spectral Disentanglement: Rank-Aware Task Adaptation for Rehearsal-free Continual Learning in LLMs

- **作者**：Huanxuan Liao, Shizhu He, Yupu Hao, Yequan Wang, Wenhao Teng, Xiangwen Liao, Jun Zhao, Kang Liu
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.334/
- **PDF**：https://aclanthology.org/2026.acl-long.334.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.334
- **关键词**：replay / rehearsal, architecture / parameter isolation, catastrophic forgetting, foundation models
- **摘要**：SpaRTA 是无需排练的框架，从秩谱视角把知识显式解耦到两个正交子空间，并据此做对秩敏感的任务适配，用于大语言模型的持续学习。

### 26. TamEdit: Trajectory-Aware Meta-Learning for Specificity-Preserving Continual Knowledge Editing

- **作者**：Shiqiang Tian, Cheng Ding, Qin Chen, Jie Zhou, Liang He
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.979/
- **PDF**：https://aclanthology.org/2026.acl-long.979.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.979
- **关键词**：distillation, lifelong / continual model editing, foundation models
- **摘要**：TamEdit 以轨迹感知的元学习在持续知识编辑中保持特异性。

### 27. Ted-Tok: Maintaining an Evolving Vocabulary for Lifelong Learning

- **作者**：Jiameng Huang, Zhi Zhang, Zhenyu He, Jiacheng Sun, Di He
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.394/
- **PDF**：https://aclanthology.org/2026.acl-long.394.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.394
- **关键词**：continual learning
- **摘要**：时间漂移分词器 Ted-Tok 维护随时间适应新出现语言模式的演化词表，以支持终身学习。

### 28. Towards Scalable Lifelong Knowledge Editing with Selective Knowledge Suppression

- **作者**：Dahyun Jung, Jaewook Lee, Heuiseok Lim
- **会议**：ACL 2026 · 主会
- **官方页面**：https://aclanthology.org/2026.acl-long.145/
- **PDF**：https://aclanthology.org/2026.acl-long.145.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-long.145
- **关键词**：catastrophic forgetting, lifelong / continual model editing, foundation models, benchmark
- **摘要**：为克服既有局限并提高终身设定下的可扩展性，该文提出 LightEdit，以选择性知识抑制支持可扩展的终身知识编辑。

## Findings（12 篇）

### 1. Agent-Dice: Disentangling Knowledge Updates via Geometric Consensus for Agent Continual Learning

- **作者**：Zheng Wu, Xingyu Lou, Xinbei Ma, Yansi Li, Weiwen Liu, Weinan Zhang, Jun Wang, Zhuosheng Zhang
- **会议**：ACL 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-acl.908/
- **PDF**：https://aclanthology.org/2026.findings-acl.908.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.findings-acl.908
- **关键词**：catastrophic forgetting, foundation models
- **摘要**：Agent-Dice 基于方向一致性评估进行参数融合，分两阶段解耦知识更新，其中几何一致性过滤用于剪除冲突梯度，服务于智能体的持续学习。

### 2. AURORA: Neuro-Symbolic Continual Indexing for Evolving RAG Systems

- **作者**：Manoj Saravanan, Rohit Kumar Salla, Ramya Manasa Amancherla
- **会议**：ACL 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-acl.495/
- **PDF**：https://aclanthology.org/2026.findings-acl.495.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.findings-acl.495
- **关键词**：continual learning
- **摘要**：AURORA 把检索索引维护视为少样本持续学习问题，以神经符号框架在分布偏移下适配不断演化的 RAG 系统的索引。

### 3. Beyond Reasoning Gains: Mitigating General-Capability Forgetting in Large Reasoning Models

- **作者**：Hoang Phan, Xianjun Yang, Yuanshun Yao, Jingyu Zhang, Shengjie Bi, Xiaocheng Tang, Madian Khabsa, Lijuan Liu, Deren Lei
- **会议**：ACL 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-acl.1717/
- **PDF**：https://aclanthology.org/2026.findings-acl.1717.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.findings-acl.1717
- **关键词**：replay / rehearsal, regularization, reinforcement learning
- **摘要**：该文提出的 RECAP 是带动态目标重加权的回放策略，用于保留一般知识，从而在大型推理模型的推理增益之外减轻一般能力遗忘。

### 4. CaPEdit: Capability-Preserving Lifelong Knowledge Editing For Language Models

- **作者**：Song-Li Wu, Zhaocheng Du, Xianquan Wang, Jingyi Wang
- **会议**：ACL 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-acl.770/
- **PDF**：https://aclanthology.org/2026.findings-acl.770.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.findings-acl.770
- **关键词**：regularization, lifelong / continual model editing, foundation models
- **摘要**：CaPEdit 在终身知识编辑中保持语言模型的既有能力。

### 5. CobwebTM: Probabilistic Concept Formation for Lifelong and Hierarchical Topic Modeling

- **作者**：Karthik Singaravadivelan, Anant Gupta, Zekun Wang, Christopher J. MacLellan
- **会议**：ACL 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-acl.1753/
- **PDF**：https://aclanthology.org/2026.findings-acl.1753.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.findings-acl.1753
- **关键词**：catastrophic forgetting, benchmark
- **摘要**：CobwebTM 基于增量式概率概念形成，以较低参数量实现终身且层次化的主题建模。

### 6. Data-Centric Continual Pre-training for 500+ Languages: A New Bilingual Translation Corpus and Multilingual Models

- **作者**：Shaoxiong Ji, Zihao Li, Jaakko Paavola, Hengyu Luo, Jörg Tiedemann
- **会议**：ACL 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-acl.937/
- **PDF**：https://aclanthology.org/2026.findings-acl.937.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.findings-acl.937
- **关键词**：continual pretraining, benchmark
- **摘要**：该文以数据为中心，面向五百余种语言开展持续预训练，提出新的双语翻译语料，并由 Llama 3 基座持续预训练构建 EMMA-500 Llama 3 大规模多语言模型，进而考察持续预训练的作用。

### 7. DKME: Rethinking Coupled Knowledge Memory for Lifelong Model Editing of Large Language Models

- **作者**：Guanyu Zheng, Wang Zhenyu, He Tingting, Xv Wang, Haochang Wang, Yaokai Huang, Tiejun Zhao
- **会议**：ACL 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-acl.792/
- **PDF**：https://aclanthology.org/2026.findings-acl.792.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.findings-acl.792
- **关键词**：catastrophic forgetting, lifelong / continual model editing, foundation models, benchmark
- **摘要**：DKME 把寻址与存储解耦：解耦的语义寻址学习事实感知流形以支持范围感知路由，分区记忆存储则把编辑定位到由无监督方式识别出的记忆分区，从而重新审视大语言模型终身编辑中耦合的知识记忆。

### 8. Exploring Two-Phase Continual Instruction Fine-tuning for Multilingual Adaptation in Large Language Models

- **作者**：Divyanshu Aggarwal, Sankarshan Damle, Navin Goyal, Satya Lokam, Sunayana Sitaram
- **会议**：ACL 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-acl.1595/
- **PDF**：https://aclanthology.org/2026.findings-acl.1595.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.findings-acl.1595
- **关键词**：replay / rehearsal, continual fine-tuning, foundation models, benchmark
- **摘要**：大语言模型需要随时间提升多语言指令遵循能力，同时保持其已经擅长的语言、通常是英语上的能力；该文探索用两阶段持续指令微调进行多语言适配。

### 9. GROLE: Instance-Level Group Relative Optimization for LoRA Experts in Incremental Learning

- **作者**：Yongyi Liao, Wencan Lai, Jun Fang, Jinjin Guo, Xiaohui Zhang, Zhiyuan Liu, Chao Liu, Pengzhang Liu, Qixia Jiang
- **会议**：ACL 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-acl.1952/
- **PDF**：https://aclanthology.org/2026.findings-acl.1952.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.findings-acl.1952
- **关键词**：architecture / parameter isolation, catastrophic forgetting, continual fine-tuning, foundation models, reinforcement learning, benchmark
- **摘要**：GROLE 以组相对优化增量构建由冻结的任务专属 LoRA 专家组成的专家池，并在实例层面进行这一优化，用于增量学习。

### 10. Relaxing the Constraints: A Dual-Importance Projection Mechanism for Lifelong Model Editing

- **作者**：Zhenghai Chen, Senbin Xu, Jiaxi Tan, Xinhua Wu, Yan Zhang, Xiawu Zheng, Shengchuan Zhang, Ke Li, Sicheng Zhao, Liujuan Cao, Rongrong Ji
- **会议**：ACL 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-acl.1910/
- **PDF**：https://aclanthology.org/2026.findings-acl.1910.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.findings-acl.1910
- **关键词**：lifelong / continual model editing, foundation models, benchmark
- **摘要**：DipEdit 以双重重要性投影编辑放宽终身模型编辑中的约束。

### 11. Robust Uncertainty Quantification for Self-Evolving Large Language Models via Continual Domain Pretraining

- **作者**：Xiaofan Zhou, Lu Cheng
- **会议**：ACL 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-acl.388/
- **PDF**：https://aclanthology.org/2026.findings-acl.388.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.findings-acl.388
- **关键词**：foundation models
- **摘要**：该文引入自适应拒绝与不可交换 CP 框架，通过持续领域预训练为自演化大语言模型提供稳健的不确定性量化。

### 12. SCALE: Upscaled Continual Learning of Large Language Models

- **作者**：Jin-woo Lee, Junhwa Choi, Bongkyu Hwang, Jinho Choo, Bogun Kim, Jeongseon Yi, Joonseok Lee, DongYoung Jung, Jaeseon Park, Kyoungwon Park, Suk-hoon Jung
- **会议**：ACL 2026 · Findings
- **官方页面**：https://aclanthology.org/2026.findings-acl.2037/
- **PDF**：https://aclanthology.org/2026.findings-acl.2037.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.findings-acl.2037
- **关键词**：continual pretraining, foundation models, graph, benchmark
- **摘要**：SCALE 采用宽度扩展架构，在冻结全部预训练参数的同时向线性模块插入轻量扩展，保留残差与注意力拓扑，并在不扰动基座模型的前提下增加容量，用于大语言模型的持续学习。

## Workshop（Student Research Workshop）（1 篇）

### 1. Thesis Proposal: LLMs post-training for multilingual medical tasks. Instruction-Tuning, Continual-Pretraining or Reasoning?

- **作者**：Pietro Ferrazzi, Alberto Lavelli, Bernardo Magnini
- **会议**：ACL 2026 · Workshop（Student Research Workshop）
- **官方页面**：https://aclanthology.org/2026.acl-srw.9/
- **PDF**：https://aclanthology.org/2026.acl-srw.9.pdf
- **DOI**：https://doi.org/10.18653/v1/2026.acl-srw.9
- **关键词**：continual pretraining, continual fine-tuning, foundation models, benchmark
- **摘要**：该文提出论文提纲，比较指令微调、持续预训练与面向推理的训练这三种常见适配途径，讨论大语言模型在多语言医学任务上的后训练。
