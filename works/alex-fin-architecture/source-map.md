# 图表与版本索引 / Source map

原稿：`alexfin架构（markdown）.docx`。SHA-256：`9314ca5b7f719199f5ad15078116cfb298228b6b1bc5e2e8908a93959e7b9fbd`。

[中文导读](README.zh-CN.md) · [English guide](README.md) · [正文](manuscript.md) · [PDF](manuscript.pdf)

本表按原章节与出现次序对应整理正文。PDF 为内容重排版，段落、公式与表格按源顺序保留；页码与 Word 原稿不同。正文公式的 TeX、章节和原出现序号全部记录在 [content-map.json](content-map.json)。出现序号包含行内公式，并非原稿公式编号。

The correspondence follows source sections and occurrence order. PDF pagination changes with reflow. The content map stores every converted mathematical expression and its section; occurrence IDs also count inline math and do not replace source equation numbers.

## 章节 / Sections

| 原章节 / Source section | 整理正文 / Text |
| --- | --- |
| Alex-Fin 模型架构详解 | [对应章节](manuscript.md#alex-fin-模型架构详解) |
| Alex-Fin | [对应章节](manuscript.md#alex-fin) |
| 第一章 问题定义与研究范式 | [对应章节](manuscript.md#第一章-问题定义与研究范式) |
| 第二章 多频率金融时空关联网络构建 | [对应章节](manuscript.md#第二章-多频率金融时空关联网络构建) |
| 第三章 多频率并行时空分离注意力图神经网络特征提取模块 | [对应章节](manuscript.md#第三章-多频率并行时空分离注意力图神经网络特征提取模块) |
| 第四章 市场状态自适应的自专业化MoE混合专家模块 | [对应章节](manuscript.md#第四章-市场状态自适应的自专业化moe混合专家模块) |
| 第五章 基于GRPO的深度强化学习自适应投资组合优化模块 | [对应章节](manuscript.md#第五章-基于grpo的深度强化学习自适应投资组合优化模块) |

## 表格 / Tables

| 原出现次序 | 原图题或前置标题 | 所在章节 | 行数（含表头） |
| --- | --- | --- | --- |
| 1 | 表1-1 模型投资绩效评价指标体系 | [1.3 投资绩效评价指标体系](manuscript.md#13-投资绩效评价指标体系) | 8 |
| 2 | 表2-1 全局频率索引与对应金融属性 | [2.2.1 全局固定频率索引映射](manuscript.md#221-全局固定频率索引映射) | 8 |

## 原图与引用图 / Figure provenance

图像 SHA-256 为原稿内对应图片字节的校验值。公开的原图未修改坐标、数值或标签。

| 原稿成员 | 图题或来源 | 公开位置 / 处理 | SHA-256 |
| --- | --- | --- | --- |

## 版本与待核事项 / Version notes

这份材料记录模型设计，尚不能用它唯一确定产生实验结果的可执行提交。架构稿与插图研究稿在频率、专家等设定上存在差异，项目案例逐项说明。整理修复明确的分隔符和下标转码问题并保留公式编号；原稿截断的卡尔玛比率公式在来源索引中登记待核。

This document records a model design. It is not an experiment log tied to an executable commit. The architecture and illustrated manuscript contain different settings, including input frequency and expert details; the project cases preserve those distinctions. Clear delimiter/subscript damage has been repaired while keeping equation numbers. One Calmar-ratio expression is truncated in the source and remains unresolved in the source map.

原稿卡尔玛比率所在行（保留截断位置）：

```text
|<br/>|卡尔玛比率|$\text{Calmar Ratio} = \frac{\text{Annual Return}}{|
```

明确的排版修复共 57 处；涉及分隔符、下标转码、冗余外括号、表格竖线和公式编号显示。修复未补写卡尔玛比率分母。

原稿公式编号 (4.7) 在正文重复出现；整理版保留两处出现位置，逐式对应记录通过出现序号区分。

Equation number (4.7) occurs twice in the source. Both occurrences are retained and distinguished by occurrence order in the formula map.
