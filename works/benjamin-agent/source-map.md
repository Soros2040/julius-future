# 图表与版本索引 / Source map

原稿：`Alex-FIN1（Benjaminagent）.docx`。SHA-256：`92e17be4508ecbbd9ab03dc388d859706d714954532ba46bd8764ac1aa8003fd`。

[中文导读](README.zh-CN.md) · [English guide](README.md) · [正文](manuscript.md) · [PDF](manuscript.pdf)

本表按原章节与出现次序对应整理正文。PDF 为内容重排版，段落、公式与表格按源顺序保留；页码与 Word 原稿不同。正文公式的 TeX、章节和原出现序号全部记录在 [content-map.json](content-map.json)。出现序号包含行内公式，并非原稿公式编号。

The correspondence follows source sections and occurrence order. PDF pagination changes with reflow. The content map stores every converted mathematical expression and its section; occurrence IDs also count inline math and do not replace source equation numbers.

## 章节 / Sections

| 原章节 / Source section | 整理正文 / Text |
| --- | --- |
| 引言 | [对应章节](manuscript.md#引言) |
| 相关工作 | [对应章节](manuscript.md#相关工作) |
| 因子挖掘 | [对应章节](manuscript.md#因子挖掘) |
| 预测模型与因子-模型协同优化 | [对应章节](manuscript.md#预测模型与因子-模型协同优化) |
| 大语言模型驱动的金融智能体 | [对应章节](manuscript.md#大语言模型驱动的金融智能体) |
| 研究方法：DAG拓扑驱动的贝叶斯检索-生成与Bandit调度 | [对应章节](manuscript.md#研究方法dag拓扑驱动的贝叶斯检索-生成与bandit调度) |
| 系统总体架构：胖节点DAG与8步闭环 | [对应章节](manuscript.md#系统总体架构胖节点dag与8步闭环) |
| DAG拓扑感知因子挖掘：贝叶斯检索与定向生成 | [对应章节](manuscript.md#dag拓扑感知因子挖掘贝叶斯检索与定向生成) |
| 双臂Bandit因子-模型联合调度与跨类型知识共享 | [对应章节](manuscript.md#双臂bandit因子-模型联合调度与跨类型知识共享) |
| 闭环整合：双条件准入、三维度过滤与统一知识更新 | [对应章节](manuscript.md#闭环整合双条件准入三维度过滤与统一知识更新) |
| 实证实验 | [对应章节](manuscript.md#实证实验) |
| 实验设置 | [对应章节](manuscript.md#实验设置) |
| 主要实验 | [对应章节](manuscript.md#主要实验) |
| 讨论 | [对应章节](manuscript.md#讨论) |
| 诊断性洞察 | [对应章节](manuscript.md#诊断性洞察) |
| 系统设计反思 | [对应章节](manuscript.md#系统设计反思) |
| 更广泛的影响 | [对应章节](manuscript.md#更广泛的影响) |
| 结论 | [对应章节](manuscript.md#结论) |
| 局限性与伦理考量 | [对应章节](manuscript.md#局限性与伦理考量) |
| 局限性 | [对应章节](manuscript.md#局限性) |
| 伦理考量 | [对应章节](manuscript.md#伦理考量) |

## 表格 / Tables

| 原出现次序 | 原图题或前置标题 | 所在章节 | 行数（含表头） |
| --- | --- | --- | --- |
| 1 | 表1 因子节点三态生命周期 | [基于DAG的因子演化拓扑建模](manuscript.md#基于dag的因子演化拓扑建模) | 4 |
| 2 | 表2 五节点定义 | [DAG感知因子生成器](manuscript.md#dag感知因子生成器) | 6 |
| 3 | 表3 Alex-Fin及所有模型在沪深 300 成分股数据集上的实验结果 | [主要结果分析](manuscript.md#主要结果分析) | 1 |
| 4 | 表3 Alex-Fin及所有模型在沪深 300 成分股数据集上的实验结果 | [主要结果分析](manuscript.md#主要结果分析) | 29 |
| 5 | Predictive power(%) | [贝叶斯DAG因子组件分析](manuscript.md#贝叶斯dag因子组件分析) | 11 |
| 6 | Portfolio construction | [贝叶斯DAG因子组件分析](manuscript.md#贝叶斯dag因子组件分析) | 11 |
| 7 | 表5 Alex-Fin(DeepSeek-V4)动作选择策略的消融实验 | [联合调度消融实验](manuscript.md#联合调度消融实验) | 5 |
| 8 | 表6 实验参数 | [伦理考量](manuscript.md#伦理考量) | 18 |
| 9 | 表7 中证500指数数据集的样本外实验结果 | [交易策略](manuscript.md#交易策略) | 23 |
| 10 | 表8 中证1000指数数据集的样本外实验结果 | [交易策略](manuscript.md#交易策略) | 1 |
| 11 | 表8 中证1000指数数据集的样本外实验结果 | [交易策略](manuscript.md#交易策略) | 22 |
| 12 | 表9 检索器（retriever）和生成器（generator）消融实验 | [交易策略](manuscript.md#交易策略) | 13 |
| 13 | 我们列出了各因素的ID、表达式、描述及其在测试期间的表现ICIR。 | [交易策略](manuscript.md#交易策略) | 29 |
| 14 | 表11 Alpha20基准因子公式 | [交易策略](manuscript.md#交易策略) | 21 |
| 15 | 以下是当优化目标为因子（Factor）时所使用的提示词： | [交易策略](manuscript.md#交易策略) | 2 |

## 原图与引用图 / Figure provenance

图像 SHA-256 为原稿内对应图片字节的校验值。公开的原图未修改坐标、数值或标签。

| 原稿成员 | 图题或来源 | 公开位置 / 处理 | SHA-256 |
| --- | --- | --- | --- |
| `word/media/image1.jpeg` | 封面装饰 / Cover decoration | 封面装饰，原稿档案保留 | `e6d6a3d504b56034938604226cc7cfba8e96bde4d73de1b2e1348ac5588d67ec` |
| `word/media/image2.webp` | 封面装饰 / Cover decoration | 封面装饰，原稿档案保留 | `98ae7b618960ad2b7b1e4993dd5b7b8a85446b4e7373c69a3bd8c5ddf94d5895` |
| `word/media/image3.png` | 封面装饰 / Cover decoration | 封面装饰，原稿档案保留 | `ad6d678f70417f5883cceeb3d7c6829adcce1545cc57dd69f9ccd2cf6f325e64` |
| `word/media/image4.jpeg` | 封面装饰 / Cover decoration | 封面装饰，原稿档案保留 | `31efba1d1ef56d5d103f515d4c84bbe828862103ce08e1026c305accbab3e054` |
| `word/media/image5.jpeg` | 图1 Alex-Fin技术路线图 | [原图](figures/image5.jpeg) | `84da99e948278a41a11c250d201388090ebe85e423bc383fdd4780d8fa866e08` |
| `word/media/image6.jpeg` | 图2 Alex-Fin架构图 | [原图](figures/image6.jpeg) | `bf8f1d566237c64b05c72c500ef560cde1d089e25bd6287d0f7a72016fdbd221` |
| `word/media/image7.png` | 图3 全局感知因子挖掘架构图 | [原图](figures/image7.png) | `ec3c6e9ead8ff88bc252772a9f49b63bd24a5031b41f1ad2239db212efdde001` |
| `word/media/image8.png` | 图4 Alex-Factor因子假设余弦相似度热力图 | [原图](figures/image8.png) | `ee06f69ef5f5f1ec45f41b8210505eebcce62a5977383a10338e24d5169c2aec` |
| `word/media/image9.png` | 图5 沪深300指数回测曲线 | [原图](figures/image9.png) | `d389c384fcea93afde937ab0998dadf3fb163e4dee640f73a1a29cf5d763b2cf` |
| `word/media/image10.png` | 图6 Alex-Fin敏感性分析 | [原图](figures/image10.png) | `fa3ba189e7c4c2b7c06c0e6eb193934898130c09e518adfed9778ddaf935f5bc` |
| `word/media/image11.png` | 图7 Alex-FinIC动态变化对比 | [原图](figures/image11.png) | `c4701ae757aa155913b7b69cf15543c183332c9c207eca7eba7b4ae10a48c67a` |
| `word/media/image12.png` | 图8 因子效应评估实验的完整结果 | [原图](figures/image12.png) | `bacb6c4aa86200b2dca6248de0f2a17cd7215ab457b952a6d4ca565e208b81f5` |
| `word/media/image13.png` | 图9 基于日频价格变动提取的沪深CSI300因子挖掘拓扑结构 | [原图](figures/image13.png) | `f7202c4428c7dab3b7dc2669a209479a72cf4c562353ef57d1481f797c6f7612` |

## 版本与待核事项 / Version notes

历史设计规定 8 维策略状态，当前调度器采用 9 维。图与稿件结果对应历史文档，源码链接对应当前实现。绩效主张按稿件报告保留；本次整理核对和组织现有材料，未执行研究流程。公开版清理封面联系方式，封面装饰图保存在私人原稿中。

The historical design specifies an 8-dimensional strategy state; the current scheduler uses 9 dimensions. Figures and manuscript results describe the historical document, while source links identify current implementation. The manuscript’s performance claims are retained as reported; this publication pass only checked and organized existing material. It did not execute the underlying research workflow. Cover contact information and decorative cover images are excluded from the public edition.

IR(SHR*) 指标说明中的成对加粗标记被误存入公式，整理版清理外侧两颗星号，保留括号内的原始星号。逐式索引同时保存该处原表达式与整理表达式。

Paired bold-markup asterisks in the IR(SHR*) explanation had been stored as formula characters. The public edition removes the outside markup pair and retains the source asterisk inside parentheses; the formula map records both expressions.
