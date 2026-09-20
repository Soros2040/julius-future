[English](README.md) · [简体中文](README.zh-CN.md)

# BenjaminAgent 历史研究稿

这份稿件记录演变为 BenjaminAgent 的研究设计：因子演化 DAG、贝叶斯种子检索、先公式后代码的候选生成、因子与模型联合调度，以及统一实验记忆。正文保留历史名称 Alex-Fin，使原图、公式与报告实验仍可对应。

[完整中文正文](manuscript.md) · [下载 PDF](manuscript.pdf) · [图表与版本索引](source-map.md) · [作品目录](../README.zh-CN.md)

## 阅读路线

从引言理解三个研究挑战，通过方法章掌握检索、生成与调度，再阅读实验章和附录的比较结果及参数。沿图 1 至图 3 建立设计关系，然后阅读当前实现案例：网页研究流程与量化因子循环具有各自入口；生成或存储一个因子，本身不能证明它已经验证有效。

## 材料范围与版本

历史设计规定 8 维策略状态，当前调度器采用 9 维。图与稿件结果对应历史文档，源码链接对应当前实现。绩效主张按稿件报告保留；本次整理核对和组织现有材料，未执行研究流程。公开版清理封面联系方式，封面装饰图保存在私人原稿中。

| 对应项 | 内容 |
| --- | --- |
| 原稿题名 | Alex-Fin：DAG拓扑驱动的贝叶斯检索-生成与双臂Bandit自进化联合调度的Multi-Agent投资策略 |
| 整理版日期 | 2026-09-20 |
| 公式 / 表格 / 正文原图 | 298 / 15 / 9 |
| 章节与逐式索引 | [content-map.json](content-map.json) |
| 原稿与原图校验值 | [source-manifest.json](source-manifest.json) |

## 与项目连接

阅读 [Fintelligence](https://github.com/Soros2040/Fintelligence) 的方法与结果，并从 [深入案例](https://github.com/Soros2040/Fintelligence/blob/main/docs/zh/case-02-factor-lifecycle.md) 将稿件内容对应到现有代码。

## 可以完成的阅读任务

选择一个公式或表格，在贡献记录中写出原章节、符号含义、比较条件和对应源码位置。若两份稿件的设置不同，分别记录版本与原文位置，再提出需要作者确认的具体问题。通过仓库 Issue 认领并提交一次有来源的修订。

原创文稿与整理说明采用 CC BY-NC-SA 4.0；引用内容按原权利处理。
