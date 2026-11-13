# 持续 / 终身 / 增量学习论文清单

本仓库整理近 24 个月顶会中与持续学习、终身学习和增量学习相关的论文，便于按年份和会议查阅。每条记录保留已核验的题名、作者、会议与年份、官方页面，以及来源中给出的 PDF；中文摘要依据公开摘要改写为一至两句，不补充摘要里没有的实验数字。

## 检索窗口

- **检索日期**：2026-11-13
- **时间窗口**：会议或正式出版日期位于 **2024-11-13 至 2026-11-13**（含边界）。EMNLP 2024 的会期为 2024-11-12 至 2024-11-16，按边界收入。
- **主题**：continual / lifelong / incremental learning，以及与之紧密相关的回放、正则、结构或参数隔离、灾难性遗忘；涵盖类增量、任务增量、域增量，以及以持续学习为核心的基础模型持续预训练或持续微调。
- **会议**：NeurIPS、ICML、ICLR、ACL、EMNLP、NAACL、EACL、COLM、CVPR、ICCV、ECCV、AAAI、IJCAI、KDD、WWW、SIGIR。以主会为主；Findings、Workshop、Industry、Student Abstract、Short 仅在主题明确相关时保留，并单独标注。

## 收录规模

共 **1025** 篇。

- **主会**（含 NeurIPS Datasets and Benchmarks 等主会轨道）：**953**
- **Findings**：**55**
- **Workshop**：**1**
- **其他**（Industry / Student Abstract / Short）：**16**

来源核验清单共 1058 篇。本仓库排除 33 篇明显离题或截断重复的条目后保留上表篇数。排除项主要是：普通强化学习经验回放（并非持续学习）、训练动力学里被称作 incremental learning 的优化过程、增量因果图发现、社交用户地理定位，以及三维高斯局部修补。黑盒单次知识编辑、以及两条被目录页截断的重复记录一并移除。没有新增来源之外的论文。

个别条目的题名或作者曾被会议目录页粘连。WWW 2025 的 RISC 与 SIGIR 2025 的终身知识图谱嵌入论文，已按该条目官方页面或 Crossref 上的同一篇 DOI 校正作者与题名，没有改动其余书目字段。

## 按会议年统计

主会列包含 Datasets and Benchmarks 等官方主会轨道。Findings、Workshop 与其他轨道分开计数。

| 会议年 | 主会 | Findings | Workshop | 其他 | 合计 |
|---|---:|---:|---:|---:|---:|
| NeurIPS 2024 | 44 | 0 | 0 | 0 | 44 |
| EMNLP 2024 | 13 | 8 | 0 | 0 | 21 |
| NeurIPS 2025 | 60 | 0 | 0 | 0 | 60 |
| ICML 2025 | 56 | 0 | 0 | 0 | 56 |
| ICLR 2025 | 41 | 0 | 0 | 0 | 41 |
| ACL 2025 | 16 | 9 | 0 | 0 | 25 |
| EMNLP 2025 | 10 | 5 | 0 | 4 | 19 |
| NAACL 2025 | 6 | 3 | 0 | 2 | 11 |
| COLM 2025 | 1 | 0 | 0 | 0 | 1 |
| CVPR 2025 | 54 | 0 | 0 | 0 | 54 |
| ICCV 2025 | 44 | 0 | 0 | 0 | 44 |
| AAAI 2025 | 51 | 0 | 0 | 1 | 52 |
| IJCAI 2025 | 10 | 0 | 0 | 0 | 10 |
| KDD 2025 | 5 | 0 | 0 | 0 | 5 |
| WWW 2025 | 9 | 0 | 0 | 0 | 9 |
| SIGIR 2025 | 6 | 0 | 0 | 0 | 6 |
| NeurIPS 2026 | 97 | 0 | 0 | 0 | 97 |
| ICML 2026 | 97 | 0 | 0 | 0 | 97 |
| ICLR 2026 | 60 | 0 | 0 | 0 | 60 |
| ACL 2026 | 28 | 12 | 1 | 0 | 41 |
| EMNLP 2026 | 25 | 17 | 0 | 1 | 43 |
| NAACL 2026（缺口） | 0 | 0 | 0 | 0 | 0 |
| EACL 2026 | 4 | 1 | 0 | 2 | 7 |
| COLM 2026 | 3 | 0 | 0 | 0 | 3 |
| CVPR 2026 | 72 | 0 | 0 | 0 | 72 |
| ECCV 2026 | 30 | 0 | 0 | 0 | 30 |
| AAAI 2026 | 63 | 0 | 0 | 5 | 68 |
| IJCAI 2026 | 9 | 0 | 0 | 0 | 9 |
| KDD 2026 | 19 | 0 | 0 | 0 | 19 |
| WWW 2026 | 15 | 0 | 0 | 0 | 15 |
| SIGIR 2026 | 5 | 0 | 0 | 1 | 6 |
| **合计** | **953** | **55** | **1** | **16** | **1025** |

## 分册

### 2024

- [NeurIPS 2024](papers/2024/neurips.md)：44 篇（主会 44）
- [EMNLP 2024](papers/2024/emnlp.md)：21 篇（主会 13，Findings 8）

### 2025

- [NeurIPS 2025](papers/2025/neurips.md)：60 篇（主会 60）
- [ICML 2025](papers/2025/icml.md)：56 篇（主会 56）
- [ICLR 2025](papers/2025/iclr.md)：41 篇（主会 41）
- [ACL 2025](papers/2025/acl.md)：25 篇（主会 16，Findings 9）
- [EMNLP 2025](papers/2025/emnlp.md)：19 篇（主会 10，Findings 5，其他 4）
- [NAACL 2025](papers/2025/naacl.md)：11 篇（主会 6，Findings 3，其他 2）
- [COLM 2025](papers/2025/colm.md)：1 篇（主会 1）
- [CVPR 2025](papers/2025/cvpr.md)：54 篇（主会 54）
- [ICCV 2025](papers/2025/iccv.md)：44 篇（主会 44）
- [AAAI 2025](papers/2025/aaai.md)：52 篇（主会 51，其他 1）
- [IJCAI 2025](papers/2025/ijcai.md)：10 篇（主会 10）
- [KDD 2025](papers/2025/kdd.md)：5 篇（主会 5）
- [WWW 2025](papers/2025/www.md)：9 篇（主会 9）
- [SIGIR 2025](papers/2025/sigir.md)：6 篇（主会 6）

### 2026

- [NeurIPS 2026](papers/2026/neurips.md)：97 篇（主会 97）
- [ICML 2026](papers/2026/icml.md)：97 篇（主会 97）
- [ICLR 2026](papers/2026/iclr.md)：60 篇（主会 60）
- [ACL 2026](papers/2026/acl.md)：41 篇（主会 28，Findings 12，Workshop 1）
- [EMNLP 2026](papers/2026/emnlp.md)：43 篇（主会 25，Findings 17，其他 1）
- [EACL 2026](papers/2026/eacl.md)：7 篇（主会 4，Findings 1，其他 2）
- [COLM 2026](papers/2026/colm.md)：3 篇（主会 3）
- [CVPR 2026](papers/2026/cvpr.md)：72 篇（主会 72）
- [ECCV 2026](papers/2026/eccv.md)：30 篇（主会 30）
- [AAAI 2026](papers/2026/aaai.md)：68 篇（主会 63，其他 5）
- [IJCAI 2026](papers/2026/ijcai.md)：9 篇（主会 9）
- [KDD 2026](papers/2026/kdd.md)：19 篇（主会 19）
- [WWW 2026](papers/2026/www.md)：15 篇（主会 15）
- [SIGIR 2026](papers/2026/sigir.md)：6 篇（主会 5，其他 1）
- NAACL 2026：未收录（见下方缺口）

## 已知缺口

- **NAACL 2026**：未检索到官方论文列表。`aclanthology.org/events/naacl-2026/` 为 404，Anthology 中也没有 `2026.naacl.xml`，因此本窗口内 NAACL 2026 的篇数为 0。
- **WWW 2025**：可能不完整。SIGWEB 官方目录当时只见到 `www25a.html` 与 `www25b.html`（约 200 篇），少于 OpenAlex 中该来源 2025 年的作品量；`www2025.thewebconf.org` 无法访问。已有条目尽量用 DOI 或官方目录交叉核对。
- **NeurIPS 2026**：官方 virtual 录用名单已公开并已扫描，但 `papers.nips.cc` 会议论文集在 2026-11-13 仍返回 404，部分论文可能还没有 PDF。journal track 与 Bridging the Future 等非主会展示未计入。
- **AAAI**：OJS 站点有反爬验证，作者与摘要主要来自 Crossref 的 DOI 记录，页面链接使用 DOI。
- **研讨会**：除 ACL Anthology 中随主会卷出现的 Student Research Workshop 外，没有系统扫描各大会的独立 workshop 论文集。ICLR 与 NeurIPS 的 Blog、TMLR / JMLR journal track 展示未计入主会。
- **摘要缺失**：少数 KDD 2026、WWW 2026 与 SIGIR 2026 条目在来源中没有可用的公开摘要。这些条目的中文说明只复述题名中的主题，不补充方法或实验。

## 条目字段

每个分册先按轨道分节，再按题名排序。单篇包含：

- 题名
- 作者
- 会议与年份，并标明主会、Findings、Workshop、Industry、Student Abstract 或 Short
- 官方论文页面；来源给出 PDF 时附上 PDF
- 一至两句中文摘要
- 关键词

中文摘要是对公开摘要的改写，不是来源清单里的模板句（「本文是一篇持续学习研究，旨在……据官方摘要」）。摘要不引入原文没有的准确率、数据集分数或其他实验数字。

## 许可

题名、作者与链接是来自官方录用名单或论文集的书目事实。中文摘要为本仓库根据公开摘要所作的简短改写。仓库内容以 [CC BY 4.0](LICENSE) 授权。
