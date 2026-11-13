# NAACL 2025

检索窗口 2024-11-13 至 2026-11-13 内，与持续学习、终身学习或增量学习相关的 NAACL 2025 论文，共 11 篇。主会 6 篇，Findings 3 篇，Workshop 0 篇，其他 2 篇。

主会数字包含该会议的官方主会轨道；NeurIPS 的 Datasets and Benchmarks 单独成节，仍计入主会。Findings、Workshop、Industry、Student Abstract 与 Short 另行标注。

## 主会（6 篇）

### 1. Continual Learning in Multilingual Sign Language Translation

- **作者**：Shakib Yazdani, Josef Van Genabith, Cristina España-Bonet
- **会议**：NAACL 2025 · 主会
- **官方页面**：https://aclanthology.org/2025.naacl-long.546/
- **PDF**：https://aclanthology.org/2025.naacl-long.546.pdf
- **DOI**：https://doi.org/10.18653/v1/2025.naacl-long.546
- **关键词**：continual learning
- **摘要**：手语翻译领域仍处于早期阶段，即便采用深度学习，翻译质量也仍然不高。该文讨论多语言手语翻译中的持续学习。

### 2. Efficient Prompting for Continual Adaptation to Missing Modalities

- **作者**：Zirun Guo, Shulei Wang, Wang Lin, Weicai Yan, Yangyang Wu, Tao Jin
- **会议**：NAACL 2025 · 主会
- **官方页面**：https://aclanthology.org/2025.naacl-long.219/
- **PDF**：https://aclanthology.org/2025.naacl-long.219.pdf
- **DOI**：https://doi.org/10.18653/v1/2025.naacl-long.219
- **关键词**：architecture / parameter isolation, catastrophic forgetting, benchmark
- **摘要**：为高效适应持续出现的模态缺失，该文引入模态特定提示、任务感知提示和任务特定提示。

### 3. Enhancing Discriminative Representation in Similar Relation Clusters for Few-Shot Continual Relation Extraction

- **作者**：Anh Duc Le, Nam Le Hai, Thanh Xuan Nguyen, Linh Ngo Van, Nguyen Thi Ngoc Diep, Sang Dinh, Thien Huu Nguyen
- **会议**：NAACL 2025 · 主会
- **官方页面**：https://aclanthology.org/2025.naacl-long.123/
- **PDF**：https://aclanthology.org/2025.naacl-long.123.pdf
- **DOI**：https://doi.org/10.18653/v1/2025.naacl-long.123
- **关键词**：catastrophic forgetting, foundation models
- **摘要**：Sirus 利用关系描述，并对这些描述进行动态聚类来识别相似关系，从而增强少样本持续关系抽取中相似关系簇的判别表示。

### 4. Hephaestus: Improving Fundamental Agent Capabilities of Large Language Models through Continual Pre-Training

- **作者**：Yuchen Zhuang, Jingfeng Yang, Haoming Jiang, Xin Liu, Kewei Cheng, Sanket Lokegaonkar, Yifan Gao, Qing Ping, Tianyi Liu, Binxuan Huang, Zheng Li, Zhengyang Wang, Pei Chen, Ruijie Wang, Rongzhi Zhang, Nasser Zalmout, Priyanka Nigam, Bing Yin, Chao Zhang
- **会议**：NAACL 2025 · 主会
- **官方页面**：https://aclanthology.org/2025.naacl-long.308/
- **PDF**：https://aclanthology.org/2025.naacl-long.308.pdf
- **DOI**：https://doi.org/10.18653/v1/2025.naacl-long.308
- **关键词**：architecture / parameter isolation, continual pretraining, foundation models, benchmark
- **摘要**：该文介绍大规模预训练语料 Hephaestus-Forge，用于加强 LLM 智能体在 API 函数调用、内在推理与规划以及适应环境反馈方面的基础能力，并服务于持续预训练。

### 5. Mutual-pairing Data Augmentation for Fewshot Continual Relation Extraction

- **作者**：Nguyen Hoang Anh, Quyen Tran, Thanh Xuan Nguyen, Nguyen Thi Ngoc Diep, Linh Ngo Van, Thien Huu Nguyen, Trung Le
- **会议**：NAACL 2025 · 主会
- **官方页面**：https://aclanthology.org/2025.naacl-long.205/
- **PDF**：https://aclanthology.org/2025.naacl-long.205.pdf
- **DOI**：https://doi.org/10.18653/v1/2025.naacl-long.205
- **关键词**：catastrophic forgetting
- **摘要**：该文提出一种数据增强策略，把单句输入与旧数据和新数据结合起来，改写成更复杂的文本，用于少样本持续关系抽取。

### 6. Prototype Conditioned Generative Replay for Continual Learning in NLP

- **作者**：Xi Chen, Min Zeng
- **会议**：NAACL 2025 · 主会
- **官方页面**：https://aclanthology.org/2025.naacl-long.636/
- **PDF**：https://aclanthology.org/2025.naacl-long.636.pdf
- **DOI**：https://doi.org/10.18653/v1/2025.naacl-long.636
- **关键词**：replay / rehearsal, architecture / parameter isolation, catastrophic forgetting
- **摘要**：语义不一致和尺度不一致是需要处理的问题。PCGR 通过原型引入任务级统计量来增强生成式回放，用于自然语言中的持续学习。

## Findings（3 篇）

### 1. An Efficient Rehearsal Scheme for Catastrophic Forgetting Mitigation during Multi-stage Fine-tuning

- **作者**：Andrew Bai, Chih-Kuan Yeh, Cho-Jui Hsieh, Ankur Taly
- **会议**：NAACL 2025 · Findings
- **官方页面**：https://aclanthology.org/2025.findings-naacl.138/
- **PDF**：https://aclanthology.org/2025.findings-naacl.138.pdf
- **DOI**：https://doi.org/10.18653/v1/2025.findings-naacl.138
- **关键词**：replay / rehearsal, catastrophic forgetting
- **摘要**：mix-cd 优先回放“附带损伤”样本，即先前模型能够正确预测、但被增量微调后的模型遗忘的样本，以缓解多阶段微调中的灾难性遗忘。

### 2. Multi-Stage LLM Fine-Tuning with a Continual Learning Setting

- **作者**：Changhao Guan, Chao Huang, Hongliang Li, You Li, Ning Cheng, Zihe Liu, Jinan Xu, Yufeng Chen, Jian Liu
- **会议**：NAACL 2025 · Findings
- **官方页面**：https://aclanthology.org/2025.findings-naacl.303/
- **PDF**：https://aclanthology.org/2025.findings-naacl.303.pdf
- **DOI**：https://doi.org/10.18653/v1/2025.findings-naacl.303
- **关键词**：distillation, foundation models, benchmark
- **摘要**：将大语言模型适配到特定领域时，可能面临领域知识快速演化的多阶段持续学习情形，这严重限制了传统微调方法。

### 3. Task-wrapped Continual Learning in Task-Oriented Dialogue Systems

- **作者**：Min Zeng, Haiqin Yang, Xi Chen, Yike Guo
- **会议**：NAACL 2025 · Findings
- **官方页面**：https://aclanthology.org/2025.findings-naacl.174/
- **PDF**：https://aclanthology.org/2025.findings-naacl.174.pdf
- **DOI**：https://doi.org/10.18653/v1/2025.findings-naacl.174
- **关键词**：architecture / parameter isolation
- **摘要**：TCL 在任务型对话系统中使用任务包裹适配器，通过参数共享同时学习全局信息和任务特定信息。

## Industry（2 篇）

### 1. CPRM: A LLM-based Continual Pre-training Framework for Relevance Modeling in Commercial Search

- **作者**：Kaixin Wu, Yixin Ji, Zeyuan Chen, Qiang Wang, Cunxiang Wang, Hong Liu, Baijun Ji, Xu Jia, Zhongyi Liu, Jinjie Gu, Yuan Zhou, Linjian Mo
- **会议**：NAACL 2025 · Industry
- **官方页面**：https://aclanthology.org/2025.naacl-industry.75/
- **PDF**：https://aclanthology.org/2025.naacl-industry.75.pdf
- **DOI**：https://doi.org/10.18653/v1/2025.naacl-industry.75
- **关键词**：continual pretraining, foundation models
- **摘要**：CPRM 是面向商业搜索相关性建模的框架，用于对大语言模型进行持续预训练。

### 2. Efficient Continual Pre-training of LLMs for Low-resource Languages

- **作者**：Arijit Nag, Soumen Chakrabarti, Animesh Mukherjee, Niloy Ganguly
- **会议**：NAACL 2025 · Industry
- **官方页面**：https://aclanthology.org/2025.naacl-industry.25/
- **PDF**：https://aclanthology.org/2025.naacl-industry.25.pdf
- **DOI**：https://doi.org/10.18653/v1/2025.naacl-industry.25
- **关键词**：continual pretraining, foundation models, benchmark
- **摘要**：该文设计了选择哪些词元进入 LLM 词表的新算法，并在 Llama-3 上针对书写系统与资源程度各异的九种印度语言，研究低资源语言的高效持续预训练。
