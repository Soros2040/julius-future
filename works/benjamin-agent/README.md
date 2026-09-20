[English](README.md) · [简体中文](README.zh-CN.md)

# BenjaminAgent historical research manuscript

This manuscript explains the research design that evolved into BenjaminAgent: a factor-evolution DAG, Bayesian seed retrieval, formula-first candidate generation, joint factor/model scheduling and a shared record of experiments. It preserves the historical Alex-Fin name so that the original figures, equations and reported experiments remain traceable.

[Complete Chinese text](manuscript.md) · [Download PDF](manuscript.pdf) · [Figures and source map](source-map.md) · [Works index](../README.md)

## Reading route

Read the introduction for the three research challenges, the methods section for retrieval, generation and scheduling, and the experiment section and appendices for reported comparisons and parameters. Follow Figures 1–3 to connect the design. Then read the current implementation cases: the web research workflow and the quantitative factor loop are separate entry paths; a factor does not become validated merely because it was generated or stored.

## Scope and version

The historical design specifies an 8-dimensional strategy state; the current scheduler uses 9 dimensions. Figures and manuscript results describe the historical document, while source links identify current implementation. The manuscript’s performance claims are retained as reported; this publication pass only checked and organized existing material. It did not execute the underlying research workflow. Cover contact information and decorative cover images are excluded from the public edition.

| Item | Content |
| --- | --- |
| Original title | Alex-Fin：DAG拓扑驱动的贝叶斯检索-生成与双臂Bandit自进化联合调度的Multi-Agent投资策略 |
| Edition date | 2026-09-20 |
| Math nodes / tables / body images | 298 / 15 / 9 |
| Chapter and equation correspondence | [content-map.json](content-map.json) |
| Source and image checksums | [source-manifest.json](source-manifest.json) |

## Connection to the project

Read [Fintelligence](https://github.com/Soros2040/Fintelligence) for methods and results, then follow [the detailed case](https://github.com/Soros2040/Fintelligence/blob/main/docs/en/case-02-factor-lifecycle.md) to map the manuscript to the available code.

## A reading contribution

Choose one equation or table. Record the source section, symbol meanings, comparison conditions and corresponding code location. If the manuscripts differ, record both versions and their source positions, then identify the specific question that needs author confirmation. Claim the task in an Issue and submit a sourced revision.

Original manuscript text and editorial notes use CC BY-NC-SA 4.0; quoted material retains its original rights.
