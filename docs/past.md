[English](past.md) · [简体中文](past.zh-CN.md)


# One year, three projects

The connection between these projects is a growing interest in how a research idea survives contact with data, computing resources and other people. I explored Alex-Fin, then BenjaminAgent, then Q-Fintelligence within one year. The sequence below records the questions and decisions; precise dates belong to the corresponding source and experiment records.

## Alex-Fin: choosing a model and understanding its parts

Alex-Fin started with adaptive portfolio allocation. The design combines information at different frequencies, graph relationships between assets, a mixture of experts and a reinforcement-learning policy. The manuscript reports an out-of-sample annualized return of 18.72%, annualized Sharpe ratio of 1.43 and maximum drawdown magnitude of 12.65%; its repository explains the evaluation context and manuscript provenance.

The work also exposed a practical weakness in my process. I wanted results quickly while my understanding of each model component was still uneven. Compute costs on AutoDL narrowed the time available for exploration. Research became harder to sustain when architecture, implementation, evaluation and explanation all competed for the same limited attention.

The lesson I take forward is to give each component a question I can answer: What enters it? What leaves it? What simpler comparison would test its contribution? That makes a complex architecture something I can explain and improve step by step.

## BenjaminAgent: making research a workflow

BenjaminAgent moved the question toward a financial research agent: how a task is decomposed, how candidate factors are generated, and how the outcome becomes useful memory for the next attempt. Its working source combines a DeerFlow foundation with financial and Qlib extensions. The public walkthroughs map the design to the actual modules.

Deployment decisions became part of the learning. I continued using a GPU rental environment for work that also required ordinary web-service hosting. Only later did I better understand the different roles of a compute instance and a general-purpose cloud server. Resource planning now needs to distinguish training, batch evaluation and a continuously available service.

## Q-Fintelligence: connecting research and a product

Q-Fintelligence brought together risk modeling, constrained portfolio objectives, quantum circuits and a research workbench. The available material includes product source, algorithm software, executed notebooks and registered experiments. The hardware studies make compilation and measurement conditions part of the research record.

My responsibilities were experimental design, product architecture and model architecture. During the summer competition period, I did not closely participate in frontline implementation. The contribution record therefore treats design, coding, deployment and experiment execution as distinct responsibilities. Understanding the system includes understanding how other contributors made it work.

The results are mixed, which gives the next questions substance. Encoding consistency can hold while a quantum component underperforms a classical baseline; hardware feasibility can differ sharply from an ideal circuit. The [project evidence](https://github.com/Soros2040/Q-Fintelligence) makes those distinctions visible.

## What changed across the three projects

| Earlier question | Question I now add |
| --- | --- |
| Can this architecture express the idea? | Which component has evidence of an incremental contribution? |
| Can I finish a run? | Can another person locate its configuration and interpret the result? |
| Can I rent enough compute? | Which parts need GPUs, which need ordinary hosting, and what can be checked on a CPU? |
| Can I complete the project? | Can its documents and responsibilities support continued collaboration? |

I encountered Datawhale between the second and third projects and began contributing during the third. Specific community contributions belong in a record with their public links and actual scope. The next step is to make my own work similarly legible to others.

Continue with [reflection](reflections.md), [next steps](roadmap.md), or [the portfolio](https://github.com/Soros2040).
