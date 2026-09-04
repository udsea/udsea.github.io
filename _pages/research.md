---
layout: page
title: research
permalink: /research/
description: Public work on AI monitoring, evaluation, and model behavior.
nav: true
nav_order: 2
---

I work on empirical questions around AI monitoring, evaluation, and model behavior. I tend to build small experiments designed to distinguish between competing explanations, then stress-test the result with interventions, controls, and inspectable artifacts.

## Selected Work

### [ActionLens]({{ '/projects/actionlens/' | relative_url }})

Pre-execution control for shell and file actions. The project tests whether a monitor can gather lightweight environment evidence before approving a proposed action, instead of relying on transcript text alone.

### [Format-Sensitivity Eval]({{ '/projects/format-sensitivity-eval/' | relative_url }})

A replication study of how response format changes observed persuasion-safety behavior. It compares forced-choice and free-form generation under the same underlying prompt set.

### [Sentinel]({{ '/projects/sentinel/' | relative_url }})

An evaluation harness for coding agents with executable graders, behavioral monitors, traces, and exported artifacts. It keeps task success distinct from monitor concerns so both can be examined directly.

### [CausalBench-LLM]({{ '/projects/causalbench-llm/' | relative_url }})

A synthetic causal-reasoning benchmark with known graph structure and intervention effects. The goal is to distinguish causal reasoning from observational pattern matching using deterministic scoring.

## Ongoing Work

### [PressureTrace]({{ '/projects/pressuretrace/' | relative_url }})

An active research scaffold for studying how optimization pressure can shift reasoning and coding systems from robust task solving toward shortcut-seeking or oversight-evasive behavior.

## Other Directions

I also keep technical notes and early experiments on flow matching and diffusion. They are not a separate research claim yet; public artifacts will appear when the experiments and protocol are ready to stand on their own.

<p><a href="{{ '/projects/' | relative_url }}">View all projects</a></p>
