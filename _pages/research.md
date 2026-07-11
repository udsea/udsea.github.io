---
layout: page
title: research
permalink: /research/
description: Research statement and current questions.
nav: true
nav_order: 2
---

## Research Statement

I study how generative and reasoning systems learn structured transformations under uncertainty, and how to make those transformations reliable, controllable, and robust under shift. I am interested in evaluation as a form of measurement engineering: building tasks, protocols, and artifacts that make model behavior legible under realistic pressure.

The systems I care about are not only chat models answering static prompts. They are models embedded in workflows: autonomous tools that interact with environments, safety-tuned models whose behavior changes with output format, and reasoning models that can sound coherent while following the wrong causal rule. In those settings, a single aggregate score is rarely enough. Good evaluation should expose where the score came from, what failure modes it hides, and what kind of evidence would change the conclusion.

My current work sits around four questions:

1. **Can oversight inspect action evidence before execution?** ActionLens explores pre-execution control for shell and file actions, using probes such as diff previews, dry runs, sensitivity scans, and network-risk checks.
2. **Can we separate success from suspicious behavior?** Sentinel treats grading and monitoring as separate outputs, so an agent can pass a task while still being flagged for behavior such as shortcut edits or protected-path access.
3. **How much do evaluation formats change measured safety?** Format-sensitivity experiments test whether refusal rates from forced-choice probes overstate behavior in free-form deployment settings.
4. **Can causal reasoning be measured with known ground truth?** CausalBench-LLM generates structural causal model instances where intervention effects are known, making it possible to score causal discrimination directly.

## Purpose

The long-term purpose is to build evaluation tools that are small enough to inspect, sharp enough to reveal specific failures, and honest enough to report their limits. I prefer benchmarks that produce useful case studies, not only tables.

The near-term purpose is simpler: keep public work organized, make assumptions clear, and turn research scaffolds into reproducible artifacts that other people can run, criticize, or extend.

## Principles

- **Measure behavior under the conditions that matter.** Deployment-like settings often differ from benchmark-shaped prompts.
- **Keep evidence inspectable.** Logs, traces, summaries, and task specs should make results easier to audit.
- **Separate capability from control.** A model can complete a task and still behave in a way that should not be approved.
- **Report limitations directly.** Small-N studies, heuristic monitors, and synthetic tasks are useful only when their scope is explicit.
- **Prefer reproducible scaffolds.** The best result is one that can be rerun, ablated, and stress-tested.
