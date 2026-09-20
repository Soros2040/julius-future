[English](README.md) · [简体中文](README.zh-CN.md)

# Julius' future

**完整研究作品、项目经历，以及接下来值得追问的问题。**

我是 Julius。目前优先关注**量子计算与量子机器学习**。投资组合模型、金融研究智能体和量子表征的探索，逐渐改变了我对研究贡献的理解：问题要清楚，方法可以检查，比较条件公平，解释能够被另一个人沿着读下去。

[阅读完整作品](works/README.zh-CN.md) · [回顾项目](docs/past.zh-CN.md) · [未来方向](docs/roadmap.zh-CN.md) · [参与贡献](CONTRIBUTING.zh-CN.md)

## 三份完整作品

每份作品均提供完整中文正文、可下载 PDF、中英文导读、原图和章节／公式／表格对应索引。导读把历史设计、稿件报告的结果与当前项目源码连接起来。

| 作品 | 主要内容 | 继续阅读项目 |
| --- | --- | --- |
| [Alex-Fin 架构详解](works/alex-fin-architecture/README.zh-CN.md) | 五章内容，从市场频率走向图注意力、专家与策略 | [模型与实现](https://github.com/Soros2040/Alex-Fin) |
| [Alex-Fin 研究稿](works/alex-fin-paper/README.zh-CN.md) | 完整研究论述、评价条件、表 6-1 至表 6-7 和表 7-1 | [方法与结果解释](https://github.com/Soros2040/Alex-Fin) |
| [BenjaminAgent 历史稿](works/benjamin-agent/README.zh-CN.md) | 因子演化 DAG、检索生成、联合调度与历史实验 | [当前智能体工作流](https://github.com/Soros2040/Fintelligence) |

![Alex-Fin 原稿中的多频率输入与图网络架构](works/alex-fin-paper/figures/image3.png)

*Alex-Fin 研究稿原图：多频率观测 → GLASSO-DY 图 → MB-PSTSA-GNN。保留原有中文标签。[作品导读](works/alex-fin-paper/README.zh-CN.md)解释设计，[来源索引](works/alex-fin-paper/source-map.md)记录出处。*

## 过去、思考与未来

| 路径 | 现有材料 | 下一项有用行动 |
| --- | --- | --- |
| 过去 | [三个项目及其选择](docs/past.zh-CN.md)、完整作品与源码案例 | 沿着一个设计选择，从原稿追踪到实现 |
| 思考 | [资源、自信与能够持续的工作](docs/reflections.zh-CN.md)，以及[阅读来源](docs/reading-sources.zh-CN.md) | 从一段具体经历写起，区分个人解释与引用 |
| 未来 | [研究方向与复核条件](docs/roadmap.zh-CN.md) | 讨论一个有边界的量子计算或 QML 问题 |
| 研究 | [已有量子证据](https://github.com/Soros2040/Q-Fintelligence)、[早期量子核设计方案](research/quantum-research.md) | 先比较表征、经典参考和资源成本，再确定新选题 |
| 协作 | [学习写作指南](docs/learning-and-writing.zh-CN.md)、贡献模板与示例 | 认领证据复核，提交一次集中的双语改进 |

## 七个可以深入阅读的案例

| 项目 | 可以追踪的问题 | 我的贡献与证据 |
| --- | --- | --- |
| [Q-Fintelligence · 量融智枢](https://github.com/Soros2040/Q-Fintelligence) | [目标 → QUBO → Ising](https://github.com/Soros2040/Q-Fintelligence/blob/main/docs/cases/01-objective_zh.md)；[量子表征](https://github.com/Soros2040/Q-Fintelligence/blob/main/docs/cases/02-representations_zh.md)；[硬件迁移](https://github.com/Soros2040/Q-Fintelligence/blob/main/docs/cases/03-hardware_zh.md) | 实验设计、产品架构与模型架构；实现和执行单独署名。E01–E07 与硬件记录同时保留有利与不利比较。 |
| [BenjaminAgent](https://github.com/Soros2040/Fintelligence) | [任务如何到达评价](https://github.com/Soros2040/Fintelligence/blob/main/docs/zh/case-01-task-to-backtest.md)；[因子谱系与反馈](https://github.com/Soros2040/Fintelligence/blob/main/docs/zh/case-02-factor-lifecycle.md) | 基于 DeerFlow/Qlib 的金融研究与因子工作流探索；历史设计与当前工程快照逐项对应。 |
| [Alex-Fin](https://github.com/Soros2040/Alex-Fin) | [多频率图与策略输入](https://github.com/Soros2040/Alex-Fin/blob/main/cases/01-causal-multifrequency-graphs.zh-CN.md)；[评价与消融](https://github.com/Soros2040/Alex-Fin/blob/main/cases/02-risk-rewards-and-evaluation.zh-CN.md) | 投资组合模型设计与稿件报告的实验探索；完整原稿与版本差异可以继续查阅。 |

每个案例贯通前置知识、公式、已有实例、源码位置、结果与局限，以及一个可完成的阅读贡献。中英文版本保留相同的技术深度。

## 研究与协作状态

量融智枢已经包含**12 个冻结候选映射上的保真度量子核**，以及独立的局部可观测量特征研究。系统性的任务驱动量子核自设计属于未来方向。本仓库的早期方案记录研究设计的演变，下一项具体研究问题仍待讨论。

[Datawhale 预立项准备](https://github.com/Soros2040/Q-Fintelligence/blob/main/docs/datawhale-preinitiation_zh.md)描述拟议的教育协作。职责、成熟度与外部合作进展在有实际依据时更新。当前作品集提供已有写作、源码解释和历史结果。

## 第一次参与

选一个公式、结果表或有源码链接的表述，阅读原章节，记录比较条件并定位对应代码。说明证据支持什么、还留下什么问题。在 Issue 中认领，通过集中的 PR 提交，再按[贡献指南](CONTRIBUTING.zh-CN.md)登记审阅。[完整示例](contributions/example-review.zh-CN.md)展示需要的证据深度。

[维护与交接](docs/maintenance.zh-CN.md) · [原图来源](works/figure-provenance.md) · [项目介绍](docs/project-introduction.zh-CN.md)

## 许可与致谢

原创文档采用 [CC BY-NC-SA 4.0](LICENSE)，原创代码采用 [MIT](LICENSE-CODE)。第三方材料保留原权利，详见[说明](THIRD_PARTY_NOTICES.zh-CN.md)。再分发权利待核的图片，在作品区保留原位置提示和来源链接。

阅读与协作的组织方式参考 Datawhale 的 [diy-llm](https://github.com/datawhalechina/diy-llm) 与 [zero-to-sglang](https://github.com/datawhalechina/zero-to-sglang)。项目讲解围绕这里实际收录的材料撰写。
