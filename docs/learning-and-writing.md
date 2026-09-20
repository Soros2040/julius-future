[English](learning-and-writing.md) · [简体中文](learning-and-writing.zh-CN.md)


# Turning reading into work

Start with a question small enough to answer from one source. The aim is to leave a note that helps the next reader make a decision. Reading requires the concepts used in the selected text; source review requires careful comparison; executing an experiment additionally requires its software and data environment.

## A four-step route

1. Read the project question and identify the decision a claim supports.
2. Read the original section, equation or result table. Record its assumptions and version.
3. Work through one concrete example, then explain where the example stops applying.
4. Submit a short change with the source, reasoning and verification performed.

For a technical chapter, include prerequisites, symbols, derivation, a worked example, source locations, limitations and an exercise with an answer. For a reflection, begin with an event, develop an interpretation, identify the reading that informed it and leave the uncertainty visible.

## Completed review example

**Claim reviewed:** The quantum-kernel proposal targets a reduction of at least 10% in compiled two-qubit gates, depth or SWAPs, with no more than 1% deterioration in objective quality.

**Source:** [Quantum research proposal, planned evaluation targets](../research/quantum-research.en.md#5-planned-evaluation-targets), version available in this repository.

**Finding:** The source states a planned criterion. A reader can verify the threshold and its scope, but cannot infer an achieved hardware result. The wording in the roadmap therefore describes a target to freeze in the experimental contract.

**Verification performed:** Compared the target table with the roadmap. No simulation or hardware task was executed for this editorial review.

**Result:** The public note preserves the threshold and its planning status. This example is a worked editorial exercise, not a record of a merged community PR.

## Exercise

Imagine a study evaluates 20 candidate circuits with 100 measurements per candidate, while a baseline evaluates 5 candidates with 400 measurements each. Are the budgets equal?

**Answer:** Both use 2,000 measurements under those assumptions, but that alone does not establish equal cost. Circuit depth, preparation, compilation, classical fitting and selection overhead can differ. Record the common budget definition and other costs before comparing performance.

[Contribute](../CONTRIBUTING.md) · [Roadmap](roadmap.md)
