<div align="center">
  <!-- 项目标识位置：加入已授权的本地图片后，在此添加图标。 -->
  <h1>Julius' future</h1>
  <p>把学习中的问题，推进为有来源、有验证、有记录的研究与写作成果。</p>
  <p><strong>学习 · 研究 · 写作 · 成果管理</strong></p>
  <p>当前重点：量子核自设计与风险增强组合优化<br>当前阶段：研究设计与预立项</p>
  <p>
    <a href="#first-contribution">完成第一次贡献</a> ·
    <a href="research/quantum-research.md">阅读研究方案</a> ·
    <a href="CONTRIBUTING.md">查看贡献指南</a>
  </p>
  <!-- 状态图标位置：可添加与仓库实际进度一致的徽章。 -->
</div>

## 这个项目解决什么问题

读过一些资料后，如何找到值得追问的问题？提出一个研究想法后，如何判断依据是否充分、比较是否公平？写下笔记后，如何让其他人接着阅读、复核和推进？

Julius' future 围绕这些问题，把学习、研究、写作和成果管理放进同一条协作流程。当前以量子研究为切入点：在有限评估预算与硬件约束下选择量子特征映射，再研究它对风险预测和组合决策的作用。完整定位见[项目介绍](docs/project-introduction.md)。

现在可以从仓库获得三件具体的帮助：

- **看清一个研究问题如何展开**：沿着[研究方案](research/quantum-research.md)，查看问题、基线、预算与评价条件如何对应。
- **把阅读变成可讨论的证据**：借助[参考资料](research/references.md)和[复核记录模板](docs/roadmap.md#review-record)，定位原文，记录它支持什么、还缺什么。
- **完成一次有明确交付的小贡献**：选择下方任务，提交来源复核、比较建议或概念说明，经过审阅后进入成果记录。

## 模块、材料与下一步

| 模块 | 现在可阅读的材料 | 下一项交付 | 当前状态 |
| --- | --- | --- | --- |
| 项目与协作 | [项目介绍](docs/project-introduction.md)、[贡献指南](CONTRIBUTING.md) | 用首批任务完成一次提交、审阅、登记 | 流程已定义，待实践 |
| 量子研究 | [问题与实验设计](research/quantum-research.md) | 复核研究依据与经典基线，明确首个实验的配置和预算 | 研究设计与预立项 |
| 资料与证据 | [研究参考资料](research/references.md) | 为具体陈述补充原文位置、支持程度与修改建议 | 索引可阅读，逐项复核待开展 |
| 学习与写作 | [学习与写作指南](docs/learning-and-writing.md) | 完成一篇连接研究问题的前置概念说明 | 路径已列出，材料待编写 |
| 成果与维护 | [路线图与成果登记](docs/roadmap.md)、[维护与交接](docs/maintenance.md) | 登记首项经审阅的贡献及其版本、证据和后续事项 | 登记规则已定义 |

实验实现、对照结果和配套教程将随各里程碑交付。研究方案中的评价数值是拟定目标；实际结论以可追溯的实验与复核记录为依据。

<a id="first-contribution"></a>

## 完成第一次贡献

从核对一条陈述开始。只需能阅读 Markdown、访问原始资料，并把疑问说明白。

1. 在[研究方案](research/quantum-research.md)中选出一句涉及方法、研究依据或比较条件的陈述，记下章节和原句。
2. 从[参考资料](research/references.md)找到对应原始来源，核对具体版本、章节、页码或公式。阅读原文后再判断支持程度；暂时无法访问时记录访问情况。
3. 复制[复核记录模板](docs/roadmap.md#review-record)，写清原文位置、支持程度及理由、建议修改或下一步。一次只处理一个清楚的问题。
4. 查看已有 [Issues](https://github.com/Soros2040/julius-future/issues)，在相关任务下提交记录，或用[任务模板](https://github.com/Soros2040/julius-future/issues/new?template=task.md)发起讨论。能形成具体修改时提交 PR，并附上记录；审阅通过后更新[成果登记](docs/roadmap.md#result-register)。

## 当前研究的三个问题

1. 在相同评估预算下，量子核自设计能否比固定映射和随机搜索选出更稳定、有效的线路？
2. 在统一的数据时点、资产顺序和风险定义下，量子表示能否改善时间外风险预测，并传递到组合决策？
3. 将线路深度、双量子比特门、SWAP、shots 和噪声纳入搜索后，能否获得可执行且目标质量可接受的方案？

问题对应的实验设计、经典基线与证据要求见[量子研究方案](research/quantum-research.md)。希望先补齐背景的读者可按[学习顺序](docs/learning-and-writing.md#learning-path)阅读和提问。

## 首批可认领任务

| 任务 | 交付到哪里 | 怎样验收 | 状态 |
| --- | --- | --- | --- |
| **T01 · 引用复核** | Issue 中提交一条复核记录；如需修改，更新 [research/references.md](research/references.md) 与研究方案对应陈述 | 原始来源的版本与位置明确；判断支持程度并说明理由；建议能定位到具体文字 | 未认领 |
| **T02 · 经典基线公平性复核** | Issue 中提交比较条件清单；建议落实到 [research/quantum-research.md](research/quantum-research.md) 的首个实验或下游评价 | 指定一组比较，逐项检查数据划分、调参、预算、指标与随机性；列出每项依据、缺项及补齐方法 | 未认领 |
| **T03 · 前置概念说明** | 在 [docs/learning-and-writing.md](docs/learning-and-writing.md) 的“前置概念说明”中提交一个完整小节 | 解释量子核或时间外验证中的一个概念；包含前置知识、研究用途、最小例子、原始来源与一道自检题 | 未认领 |

认领方式、完整验收条件和任务状态见[路线图](docs/roadmap.md#starter-tasks)。

## 参与与维护

可以在线阅读文件，也可以把仓库保存到本地：

```sh
git clone https://github.com/Soros2040/julius-future.git
cd julius-future
```

文档复核可直接从浏览器开始。实验参与需要 Python、线性代数、概率统计与机器学习实验基础；各模块交付时提供相应的环境和运行说明。

项目由 Julius（[@Soros2040](https://github.com/Soros2040)）维护。贡献按“提交 → 审阅 → 合并 → 登记”推进，任务负责人和审阅者在 Issue / PR 中记录。具体要求见[贡献指南](CONTRIBUTING.md)，职责、复现与交接安排见[维护与交接](docs/maintenance.md)。欢迎学习者、研究参与者和维护者从一个可独立验收的小任务加入。

## 致谢与许可

首页的信息组织参考了 Datawhale 的 [diy-llm](https://github.com/datawhalechina/diy-llm) 和 [zero-to-sglang](https://github.com/datawhalechina/zero-to-sglang)：用项目说明、学习入口、材料状态与贡献路径帮助读者开始参与。本项目的内容围绕自身学习与研究问题编写。感谢原始资料作者及参与复核、写作和维护的贡献者。

原创文档采用 [CC BY-NC-SA 4.0](LICENSE)，原创代码采用 [MIT](LICENSE-CODE)。第三方资料遵循各自许可，详见[来源与许可说明](THIRD_PARTY_NOTICES.md)。
