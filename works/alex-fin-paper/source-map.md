# 图表与版本索引 / Source map

原稿：`（有插图）Alex-Fin：多频率时空图网络与深度强化学习的自适应动态投资组合优化框架.docx`。SHA-256：`a99bcfb09d1a007361a75b681eb4eb574f4956ba3aef7abfc387255c4269a7f4`。

[中文导读](README.zh-CN.md) · [English guide](README.md) · [正文](manuscript.md) · [PDF](manuscript.pdf)

本表按原章节与出现次序对应整理正文。PDF 为内容重排版，段落、公式与表格按源顺序保留；页码与 Word 原稿不同。正文公式的 TeX、章节和原出现序号全部记录在 [content-map.json](content-map.json)。出现序号包含行内公式，并非原稿公式编号。

The correspondence follows source sections and occurrence order. PDF pagination changes with reflow. The content map stores every converted mathematical expression and its section; occurrence IDs also count inline math and do not replace source equation numbers.

## 章节 / Sections

| 原章节 / Source section | 整理正文 / Text |
| --- | --- |
| 引言 | [对应章节](manuscript.md#引言) |
| 研究背景与问题提出 | [对应章节](manuscript.md#研究背景与问题提出) |
| 研究内容与边际贡献 | [对应章节](manuscript.md#研究内容与边际贡献) |
| 论文结构安排 | [对应章节](manuscript.md#论文结构安排) |
| 相关研究综述 | [对应章节](manuscript.md#相关研究综述) |
| 动态投资组合优化研究进展 | [对应章节](manuscript.md#动态投资组合优化研究进展) |
| 多频率金融时间序列建模研究 | [对应章节](manuscript.md#多频率金融时间序列建模研究) |
| 深度强化学习在资产配置中的应用研究 | [对应章节](manuscript.md#深度强化学习在资产配置中的应用研究) |
| 现有研究评述 | [对应章节](manuscript.md#现有研究评述) |
| 理论框架与问题形式化 | [对应章节](manuscript.md#理论框架与问题形式化) |
| 动态投资组合优化的理论基础 | [对应章节](manuscript.md#动态投资组合优化的理论基础) |
| 序列决策问题的MDP形式化定义 | [对应章节](manuscript.md#序列决策问题的mdp形式化定义) |
| 核心术语规范界定 | [对应章节](manuscript.md#核心术语规范界定) |
| 投资绩效评价指标体系构建 | [对应章节](manuscript.md#投资绩效评价指标体系构建) |
| Alex-Fin模型设计 | [对应章节](manuscript.md#alex-fin模型设计) |
| 模型整体架构 | [对应章节](manuscript.md#模型整体架构) |
| 多频率金融时空关联网络构建 | [对应章节](manuscript.md#多频率金融时空关联网络构建) |
| 多频率并行时空分离注意力图神经网络特征提取 | [对应章节](manuscript.md#多频率并行时空分离注意力图神经网络特征提取) |
| 市场状态自适应的自专业化MoE混合专家模块 | [对应章节](manuscript.md#市场状态自适应的自专业化moe混合专家模块) |
| 基于GRPO的深度强化学习投资组合优化框架 | [对应章节](manuscript.md#基于grpo的深度强化学习投资组合优化框架) |
| 实证研究设计 | [对应章节](manuscript.md#实证研究设计) |
| 数据来源与样本选择 | [对应章节](manuscript.md#数据来源与样本选择) |
| 变量定义 | [对应章节](manuscript.md#变量定义) |
| 基准模型设置 | [对应章节](manuscript.md#基准模型设置) |
| 实证回测框架 | [对应章节](manuscript.md#实证回测框架) |
| 实证结果与分析 | [对应章节](manuscript.md#实证结果与分析) |
| 基准实证结果 | [对应章节](manuscript.md#基准实证结果) |
| 作用机制分析 | [对应章节](manuscript.md#作用机制分析) |
| 异质性分析 | [对应章节](manuscript.md#异质性分析) |
| 稳健性检验与研究展望 | [对应章节](manuscript.md#稳健性检验与研究展望) |
| 核心模块消融实验 | [对应章节](manuscript.md#核心模块消融实验) |
| 安慰剂检验 | [对应章节](manuscript.md#安慰剂检验) |
| 其他稳健性检验 | [对应章节](manuscript.md#其他稳健性检验) |
| 研究局限与未来展望 | [对应章节](manuscript.md#研究局限与未来展望) |

## 表格 / Tables

| 原出现次序 | 原图题或前置标题 | 所在章节 | 行数（含表头） |
| --- | --- | --- | --- |
| 1 | 表3-1 模型投资绩效评价指标体系 | [投资绩效评价指标体系构建](manuscript.md#投资绩效评价指标体系构建) | 8 |
| 2 | 表4-1 全局频率索引与对应金融属性 | [异频特征维度对齐与标准化处理](manuscript.md#异频特征维度对齐与标准化处理) | 8 |
| 3 | 表6-1 全样本外测试区间核心投资绩效对比 | [基准实证结果](manuscript.md#基准实证结果) | 11 |
| 4 | 表6-2 不同频率输入下的模型绩效对比 | [多频率时空网络的信息增量机制](manuscript.md#多频率时空网络的信息增量机制) | 6 |
| 5 | 表6-3 有无MoE模块的分市场绩效对比 | [MoE模块的市场自适应机制](manuscript.md#moe模块的市场自适应机制) | 3 |
| 6 | 表6-4 GRPO与PPO算法的训练与泛化能力对比 | [GRPO算法的策略优化机制](manuscript.md#grpo算法的策略优化机制) | 3 |
| 7 | 表6-5 不同市场行情下的年化夏普比率对比 | [不同市场行情的异质性分析](manuscript.md#不同市场行情的异质性分析) | 5 |
| 8 | 表6-6 不同市场波动水平下的年化夏普比率对比 | [不同市场波动水平的异质性分析](manuscript.md#不同市场波动水平的异质性分析) | 4 |
| 9 | 表6-7 不同行业板块的年化夏普比率对比 | [不同行业板块的异质性分析](manuscript.md#不同行业板块的异质性分析) | 6 |
| 10 | 图 7-1 核心创新模块增量贡献瀑布图 | [核心模块消融实验](manuscript.md#核心模块消融实验) | 7 |

## 原图与引用图 / Figure provenance

图像 SHA-256 为原稿内对应图片字节的校验值。公开的原图未修改坐标、数值或标签。

| 原稿成员 | 图题或来源 | 公开位置 / 处理 | SHA-256 |
| --- | --- | --- | --- |
| `word/media/image1.png` | DeepSeek-V3 technical report, Figure 2 | [引用来源](https://arxiv.org/abs/2412.19437) | `9e3e37771855d870d14724ad47a349cff3f90f450f476c919bd22d27b06c2708` |
| `word/media/image2.png` | FinCast, joint conditional training component | [引用来源](https://arxiv.org/abs/2508.19609) | `acc4b382448fc2c2b15d5914420296fa27dd0535f355a63c795c833acc4e2c17` |
| `word/media/image3.png` | 多频率输入、GLASSO-DY 与 MB-PSTSA-GNN 总体架构 / Model architecture | [原图](figures/image3.png) | `50fbde8cba59880ccec27c6f1b08b90ea06dcb18f358ae390724458e93fa8af8` |
| `word/media/image4.png` | 基于风险溢出网络的 MTGNN 预测模型图；原稿未给出逐图出处 | 出处待核；保留原位置说明 | `7e4ef15fe747aca07ecb2ddbf559f94acc2fa10066ca138967e32ec2beabf945` |
| `word/media/image5.png` | GLASSO-DY 股票网络示意 / Stock-network illustration | [原图](figures/image5.png) | `564ce302a42e8de82c9f28f55d1407662f1fa26d83d08024e5e3c583a7b33a73` |
| `word/media/image6.png` | 2007—2014 年行业间风险溢出网络图；原稿未给出逐图出处 | 出处待核；保留原位置说明 | `923e8b3367513f1b6342db7e3688bd6f482a8ba8632c330644fb7818bde26b00` |
| `word/media/image7.png` | 图卷积模块和混合跳跃传播层图；原稿未给出逐图出处 | 出处待核；保留原位置说明 | `84a4d75d8cb38de7e568a16958ce14b2c88b44a4e24d64d335b7992893959a75` |
| `word/media/image8.png` | DeepSeek-V3 technical report, Figure 3 | [引用来源](https://arxiv.org/abs/2412.19437) | `744842a59a1f756d1548b0848aaa43516ca7748d3da21fd444b262f171028abc` |
| `word/media/image9.png` | DeepSeek-V3 technical report, Figure 9 | [引用来源](https://arxiv.org/abs/2412.19437) | `6cde84697c45a0104b9a0117e2462cf563b2c9abbb5130d55dbed2fb43e19d75` |
| `word/media/image10.png` | Deep Reinforcement Learning for Optimal Portfolio Allocation, Figure 2 | [引用来源](https://arxiv.org/abs/2602.17098) | `38dcc917f5e36dbacde0cdd155202e359ea8625d7405f7d40f295e273f2fed76` |
| `word/media/image11.png` | MIDAS-TGCN 总关联性图；原稿未给出逐图出处 | 出处待核；保留原位置说明 | `1645fb34cf601a8f64b69b15cf4ac9366f3f0385b2c09ec1d24dacb7a0be5a76` |
| `word/media/image12.png` | VAR、TVP-VAR 与 BK 关联性图；原稿未给出逐图出处 | 出处待核；保留原位置说明 | `2af5696a09d2fce3f5b75fb26409d29a315e14332f8297bbbb1e61d3e5b0bdb7` |
| `word/media/image13.png` | DeepSeek-V3 technical report, Figure 10 | [引用来源](https://arxiv.org/abs/2412.19437) | `0aac23ad28e3e38c7360c3d025fe34e7c2eff961ecaee4985f4dba33a5e04dd4` |
| `word/media/image14.png` | DeepSeek-V3 technical report, Table 4 | [引用来源](https://arxiv.org/abs/2412.19437) | `27f4a7d52ad18c021d46b936e1a57d03cdbad3d51cdf0259877b4577f7d5d4b4` |

## 版本与待核事项 / Version notes

正文作为历史作品保留。原文与自身表格冲突时，当前案例以表格为依据：熊市表中 PPO 的夏普也为正，数值为 0.24；删除 DSR 的夏普为 0.68，低于删除 MoE 的对应行。部分插图来自其他论文，索引保留位置、原图题及已识别出处，再分发权利待核的图片用来源提示替代。DeepSeek-V3 的训练与消融插图属于参考材料，不构成 Alex-Fin 实验结果。

The source text is retained as a historical work. Where its prose conflicts with its own table, the current case guide uses the table: the bear-market table also gives PPO a positive Sharpe of 0.24; the DSR removal has Sharpe 0.68, lower than the MoE-removal row. Several embedded reference illustrations originate in other papers. Their positions, captions and identified sources are retained in the map; bitmap copies with unconfirmed redistribution rights are represented by source notices. DeepSeek-V3 training and ablation figures are reference material, not Alex-Fin experiments.

部分公式在 Word 中被保存为字面的 TeX 命令，整理时恢复其分式、上下标、矩阵和公式编号的显示结构；[逐式排版对应记录](formula-formatting-map.json)保存修复前后的表达式。表 3-1 的卡尔玛比率与组合换手率两处公式在原稿中截断，保留以下原始片段，含义待作者确认：

Some Word equations store literal TeX commands. The formatting map preserves the before/after expressions for display restoration. Two expressions in Table 3-1 are truncated in the source; their fragments are retained below and require author confirmation.

```text
$\text{Calmar Ratio} = \frac{\text{Annual Return}}{
```

```text
$\text{Turnover} = \frac{1}{T} \sum_{t=1}^T
```

原稿 image5 的标题中已有缺失中文字形，公开图保持原始字节，节点、连边与英文标记可正常辨认。

The source image5 already contains missing Chinese glyphs in its title. The public image retains the original bytes; its nodes, edges and English labels remain visible.
