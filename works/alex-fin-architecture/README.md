[English](README.md) · [简体中文](README.zh-CN.md)

# Alex-Fin model architecture

How do multiple market frequencies become a portfolio decision? This five-chapter architecture manuscript follows the whole representation chain: aligned observations, dynamic asset graphs, temporal and spatial attention, a market-conditioned mixture of experts, and a GRPO policy. It is the detailed design companion to the illustrated research manuscript.

[Complete Chinese text](manuscript.md) · [Download PDF](manuscript.pdf) · [Figures and source map](source-map.md) · [Works index](../README.md)

## Reading route

Read Chapter 1 for the decision problem and notation, Chapter 2 for GLASSO-DY graph construction, Chapter 3 for MB-PSTSA-GNN, Chapter 4 for expert routing, and Chapter 5 for the policy and reward. Follow one asset through the pipeline and record the shape, time boundary and source of each input. Compare those assumptions with the current source before interpreting a manuscript result.

## Scope and version

This document records a model design. It is not an experiment log tied to an executable commit. The architecture and illustrated manuscript contain different settings, including input frequency and expert details; the project cases preserve those distinctions. Clear delimiter/subscript damage has been repaired while keeping equation numbers. One Calmar-ratio expression is truncated in the source and remains unresolved in the source map.

| Item | Content |
| --- | --- |
| Original title | Alex-Fin |
| Edition date | 2026-09-20 |
| Math nodes / tables / body images | 247 / 2 / 0 |
| Chapter and equation correspondence | [content-map.json](content-map.json) |
| Source and image checksums | [source-manifest.json](source-manifest.json) |

## Connection to the project

Read [Alex-Fin](https://github.com/Soros2040/Alex-Fin) for methods and results, then follow [the detailed case](https://github.com/Soros2040/Alex-Fin/blob/main/cases/01-causal-multifrequency-graphs.md) to map the manuscript to the available code.

## A reading contribution

Choose one equation or table. Record the source section, symbol meanings, comparison conditions and corresponding code location. If the manuscripts differ, record both versions and their source positions, then identify the specific question that needs author confirmation. Claim the task in an Issue and submit a sourced revision.

Original manuscript text and editorial notes use CC BY-NC-SA 4.0; quoted material retains its original rights.
