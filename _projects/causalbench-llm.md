---
layout: page
title: CausalBench-LLM
description: Synthetic benchmark for testing causal reasoning in language models.
img:
importance: 5
category: evaluation
---

[causalbench-llm](https://github.com/udsea/causalbench-llm) is a synthetic benchmark for testing whether language models can reason causally instead of relying on observational correlations.

The benchmark generates linear-Gaussian structural causal model instances with known graph structure and known ground-truth intervention effects. Prompts ask models to compare observational quantities such as `P(Y > 0 | X ~= 1)` against interventional quantities such as `P(Y > 0 | do(X = 1))`.

What this project is for:

- creating causal reasoning tasks with known labels
- testing traps such as confounding, mediation, colliders, instrumental variables, anti-causal structure, and backdoor adjustment
- scoring strict JSON outputs deterministically
- comparing local Hugging Face models, OpenRouter models, and non-LLM heuristic baselines

Status: working benchmark scaffold with fixed splits, SCM/task generation, evaluation runners, summaries, and initial compute-constrained results.
