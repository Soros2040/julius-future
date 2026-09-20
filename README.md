[English](README.md) · [简体中文](README.zh-CN.md)

# Julius' future

**Collected research works, project experience and questions for what comes next.**

I am Julius. My current research interests are **quantum computing and quantum machine learning**. Work on portfolio models, financial research agents and quantum representations has shaped how I think about a useful research contribution: a clear problem, an inspectable method, a fair comparison and an explanation another person can follow.

[Read the complete works](works/README.md) · [Explore the projects](docs/past.md) · [Future direction](docs/roadmap.md) · [Contribute](CONTRIBUTING.md)

## Three complete works

Each work has its complete Chinese text, a downloadable PDF, an English/Chinese guide, original figures and a chapter/formula/table correspondence map. The guides connect historical design and reported results to current project source.

| Work | What it contains | Continue into the project |
| --- | --- | --- |
| [Alex-Fin architecture](works/alex-fin-architecture/README.md) | Five chapters following market frequencies through graph attention, experts and a policy | [Model and implementation](https://github.com/Soros2040/Alex-Fin) |
| [Alex-Fin research manuscript](works/alex-fin-paper/README.md) | Full research narrative, evaluation conditions, Tables 6-1–6-7 and 7-1 | [Methods and result interpretation](https://github.com/Soros2040/Alex-Fin) |
| [BenjaminAgent historical manuscript](works/benjamin-agent/README.md) | Factor-evolution DAG, retrieval/generation, joint scheduling and historical experiments | [Current agent workflow](https://github.com/Soros2040/Fintelligence) |

![Original Alex-Fin multifrequency input and graph architecture](works/alex-fin-paper/figures/image3.png)

*Original figure from the Alex-Fin research manuscript: multifrequency observations → GLASSO-DY graphs → MB-PSTSA-GNN. Chinese labels are retained. The [work guide](works/alex-fin-paper/README.md) explains the design and the [source map](works/alex-fin-paper/source-map.md) records provenance.*

## Past, reflection and future

| Path | Available now | A useful next step |
| --- | --- | --- |
| Past | [Three projects and their decisions](docs/past.md), complete works and source-linked cases | Follow one design choice from manuscript to implementation |
| Reflection | [Resources, confidence and sustainable work](docs/reflections.md), with [reading sources](docs/reading-sources.md) | Write from a specific experience and distinguish interpretation from quotation |
| Future | [Research direction and review conditions](docs/roadmap.md) | Discuss one bounded quantum-computing or QML question |
| Research | [Existing quantum evidence](https://github.com/Soros2040/Q-Fintelligence), [earlier kernel-design proposal](research/quantum-research.en.md) | Compare representations, classical references and resource costs before fixing a new topic |
| Collaboration | [Learning/writing guide](docs/learning-and-writing.md), contribution template and example | Claim an evidence review and submit a focused bilingual improvement |

## Seven cases to read closely

| Project | Questions you can follow | My contribution and the evidence |
| --- | --- | --- |
| [Q-Fintelligence · 量融智枢](https://github.com/Soros2040/Q-Fintelligence) | [Objective → QUBO → Ising](https://github.com/Soros2040/Q-Fintelligence/blob/main/docs/cases/01-objective.md); [quantum representations](https://github.com/Soros2040/Q-Fintelligence/blob/main/docs/cases/02-representations.md); [hardware transfer](https://github.com/Soros2040/Q-Fintelligence/blob/main/docs/cases/03-hardware.md) | Experimental design, product architecture and model architecture; implementation/execution credited separately. E01–E07 and hardware records include favorable and unfavorable comparisons. |
| [BenjaminAgent](https://github.com/Soros2040/Fintelligence) | [A task reaches evaluation](https://github.com/Soros2040/Fintelligence/blob/main/docs/en/case-01-task-to-backtest.md); [factor lineage and feedback](https://github.com/Soros2040/Fintelligence/blob/main/docs/en/case-02-factor-lifecycle.md) | Financial research and factor-workflow exploration on DeerFlow/Qlib; historical design is mapped to the current engineering snapshot. |
| [Alex-Fin](https://github.com/Soros2040/Alex-Fin) | [Multifrequency graphs and policy inputs](https://github.com/Soros2040/Alex-Fin/blob/main/cases/01-causal-multifrequency-graphs.md); [evaluation and ablation](https://github.com/Soros2040/Alex-Fin/blob/main/cases/02-risk-rewards-and-evaluation.md) | Portfolio-model design and reported experimental exploration; full source manuscripts and version differences remain visible. |

Each case joins prerequisites, equations, an existing example, source locations, results/limitations and a reading contribution. English and Chinese editions carry the same technical substance.

## Research and collaboration status

Q-Fintelligence already includes **fidelity kernels over a frozen catalogue of 12 maps** and a separate study using local observable features. Systematic task-aware kernel self-design is a future direction. The earlier proposal in this repository records a design trajectory; the next concrete research question remains open for discussion.

The [Datawhale preparation](https://github.com/Soros2040/Q-Fintelligence/blob/main/docs/datawhale-preinitiation.md) describes an intended educational collaboration. Roles, readiness and external collaboration progress are updated when evidence exists. The current collection provides existing writing, source explanations and archived results.

## Your first contribution

Choose one equation, result table or source-linked claim. Read the original section, record its comparison conditions and locate the corresponding code. Explain what is supported and which question remains. Claim the task in an Issue, submit a focused PR, and register the review using the [contribution guide](CONTRIBUTING.md). The [completed example](contributions/example-review.md) shows the expected level of evidence.

[Maintenance and handoff](docs/maintenance.md) · [Figure provenance](works/figure-provenance.md) · [Project introduction](docs/project-introduction.md)

## License and acknowledgments

Original documents: [CC BY-NC-SA 4.0](LICENSE). Original code: [MIT](LICENSE-CODE). Third-party work retains its rights; see [notices](THIRD_PARTY_NOTICES.md). Figures with unconfirmed redistribution rights are represented by source-position notices and links in the collected works.

The reading and collaboration structure draws inspiration from Datawhale's [diy-llm](https://github.com/datawhalechina/diy-llm) and [zero-to-sglang](https://github.com/datawhalechina/zero-to-sglang). The project explanations are written for the actual materials collected here.
