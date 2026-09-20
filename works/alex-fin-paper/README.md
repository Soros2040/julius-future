[English](README.md) · [简体中文](README.zh-CN.md)

# Alex-Fin portfolio research manuscript

This manuscript connects a portfolio-allocation question to multifrequency graph modeling, mixture-of-experts routing and reinforcement learning. It contains the complete Chinese argument, method equations, evaluation setup and original result tables, including the baseline, mechanism, market-regime, volatility, sector and component comparisons.

[Complete Chinese text](manuscript.md) · [Download PDF](manuscript.pdf) · [Figures and source map](source-map.md) · [Works index](../README.md)

## Reading route

Start with Chapter 3 to define the decision problem and metrics; use Chapter 4 to follow the model; read Chapter 5 before reading any result. Chapter 6 contains Tables 6-1 through 6-7, and Chapter 7 contains Table 7-1. The manuscript reports 18.72% annualized return, 1.43 annualized Sharpe and 12.65% maximum-drawdown magnitude for the stated out-of-sample period 2017-01 to 2026-02. These are manuscript-reported results. The case guide checks their interpretation against the tables and the available code.

## Scope and version

The source text is retained as a historical work. Where its prose conflicts with its own table, the current case guide uses the table: the bear-market table also gives PPO a positive Sharpe of 0.24; the DSR removal has Sharpe 0.68, lower than the MoE-removal row. Several embedded reference illustrations originate in other papers. Their positions, captions and identified sources are retained in the map; bitmap copies with unconfirmed redistribution rights are represented by source notices. DeepSeek-V3 training and ablation figures are reference material, not Alex-Fin experiments.

| Item | Content |
| --- | --- |
| Original title | Alex-Fin：多频率时空图网络与深度强化学习的自适应动态投资组合优化框架 |
| Edition date | 2026-09-20 |
| Math nodes / tables / body images | 243 / 10 / 2 |
| Chapter and equation correspondence | [content-map.json](content-map.json) |
| Source and image checksums | [source-manifest.json](source-manifest.json) |

## Connection to the project

Read [Alex-Fin](https://github.com/Soros2040/Alex-Fin) for methods and results, then follow [the detailed case](https://github.com/Soros2040/Alex-Fin/blob/main/cases/02-risk-rewards-and-evaluation.md) to map the manuscript to the available code.

## A reading contribution

Choose one equation or table. Record the source section, symbol meanings, comparison conditions and corresponding code location. If the manuscripts differ, record both versions and their source positions, then identify the specific question that needs author confirmation. Claim the task in an Issue and submit a sourced revision.

Original manuscript text and editorial notes use CC BY-NC-SA 4.0; quoted material retains its original rights.
