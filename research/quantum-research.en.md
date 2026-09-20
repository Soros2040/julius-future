[English](quantum-research.en.md) · [简体中文](quantum-research.md)

# Quantum feature-map design and risk-enhanced portfolio optimization

Status: research design and preproposal. This document defines the questions, experimental constraints and evidence to be delivered.

## 1. Research question

Quantum-kernel design searches over feature maps, circuit structures and continuous parameters. Evaluating a candidate may require kernel-matrix estimation, simulation or physical measurements. Finite shots, noise and compilation overhead can change the choice made under ideal conditions.

**Under an accountable evaluation budget, how can we select a quantum feature map with a better balance of predictive quality, stability and hardware cost?** Financial risk tasks provide a downstream evaluation of the selection.

## 2. Method chain

```text
Point-in-time data and a dynamic asset universe
  → feature selection and quantum-kernel candidates
  → candidate scoring, ranking and continuous-parameter optimization
  → shared local quantum message circuits and risk-graph aggregation
  → return and risk parameters μ, B, d
  → QUBO / Ising objective and portfolio constraints
  → QAOA portfolio candidates
  → hardware-aware selection and execution evidence
```

QuKerNet is a starting point for feature-map search. The risk graph, portfolio interface and hardware execution chain each need separate incremental evaluation.

The initial application design uses a dynamic CSI 300 asset graph, daily decisions, next-trading-day execution, selection of five assets and equal weights. The number 300 refers to graph nodes. Local circuit size depends on simulation and hardware budgets.

## 3. First reproducible experiment

Begin with redistributable synthetic data and small tasks, then use appropriately licensed financial data for out-of-time evaluation.

1. Freeze generation or preprocessing, train/validation/test splits, seeds, search space and budget.
2. Compare classical linear/RBF kernels, fixed quantum maps, random circuit search and QuKerNet-style candidate selection.
3. Under the same total evaluation budget, record candidate evaluations, kernel-estimation work, predictive metrics and across-seed variation.
4. Report ideal simulation, finite-shot sampling and noise simulation separately; add physical-backend evidence when resources permit.
5. Ablate feature selection, ranking and continuous-parameter optimization to locate the source of improvement.

The first deliverables are reproducible configurations and a complete comparison table. They determine the next stage.

## 4. Downstream evaluation and interface constraints

| Stage | Conditions held consistent | Evaluation |
| --- | --- | --- |
| Data | Decision time, asset axis, label horizon, availability | Missingness, leakage checks and temporal splits |
| Risk prediction | Return units, risk definition and horizon | Out-of-time RMSE/MAE and stability |
| Risk parameters | Meaning of μ, low-rank factors B and residual d | Dimensions, finite values, nonnegative residuals and axis consistency |
| Portfolio optimization | Objective, hard constraints, turnover and costs | Feasibility, CVaR, drawdown and net return |
| Hardware | Compiler version, topology, calibration and shots | Two-qubit gates, depth, SWAPs and objective quality |

Compare risk prediction with at least Ridge/FEVD, classical graph methods and the quantum-component ablation. Check portfolio objectives and constraints using enumeration or exact solving on small problems before comparing relevant classical optimizers.

Build data using information available at each decision time. Separate training, validation and testing chronologically; set purge/embargo according to the label horizon. Freeze transaction-cost, suspension, price-limit and liquidity treatment before the formal experiment.

## 5. Planned evaluation targets

These numbers plan the formal experiments. Freeze them after agreeing data access, resources and the experimental contract, then report both attained and missed targets.

| Dimension | Target |
| --- | --- |
| Out-of-time risk prediction | At least 5% lower RMSE/MAE than the strongest classical baseline, with confidence intervals |
| Risk-enhanced portfolio | At least 5% improvement in CVaR or maximum drawdown, no worse net return, 100% hard-constraint satisfaction |
| Hardware executability | At least 10% reduction in compiled two-qubit gates, depth or SWAPs, with at most 1% loss of objective quality |
| Stability | Review across seeds, out-of-time windows and at least three independent calibration blocks |
| Evidence completeness | Link and reproduce data, circuits, compilation, measurement, evaluation and decisions |

Every comparison states baseline selection, sample size, budget and uncertainty. Quantum advantage requires independent, resource-fair evidence; one improvement is insufficient.

## 6. Milestones and evidence

- **Kernel-search baseline:** implementation and environment, frozen configuration, comparisons, budget and review record.
- **Risk-to-portfolio bridge:** availability checks, axes and units, objective consistency and constraint tests.
- **Hardware evaluation:** backend, circuit and compilation records, sampled outcomes, failures and resource report.
- **Educational output:** conceptual explanations, minimal examples, exercises and common questions around validated modules.

If targets are missed, record the applicable boundary and cause, then use an Issue to decide whether to revise the method or end that experimental direction. Data, implementation and measurements are identified by their artifact versions.

See the [research bibliography](references.en.md).
