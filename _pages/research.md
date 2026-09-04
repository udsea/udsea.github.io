---
layout: page
title: research
permalink: /research/
nav: true
nav_order: 2
---

I'm interested in a basic problem in AI safety: how can we tell what a capable AI system is doing, and whether our evidence about its behavior remains trustworthy as the system becomes more capable and autonomous?

This becomes difficult when models reason in ways we only partially observe, learn from interactions with their overseers, exploit weaknesses in evaluations, or distribute behavior across long trajectories and multiple agents. Monitoring and evaluation methods that work for passive models may fail once the systems being measured can adapt to the measurement process itself.

I study these problems empirically. My work uses behavioral experiments, causal interventions, adversarial evaluations, and controlled experimental settings to test what different signals actually tell us about model behavior—and where those signals break down.

## 2026

### Do Thoughts Cause Lies?

Causal interventions on reasoning and deceptive behavior.

_Research note._

### Watcher&rsquo;s Echo

Can agents learn about their monitors from repeated feedback, or are they merely learning to adapt to feedback in general?

_Research note._

### HackTrace

Studying how reward-hacking strategies emerge, propagate, and can be attributed in agentic systems.

_Project._

## Earlier Work

[ActionLens]({{ '/projects/actionlens/' | relative_url }}) studies pre-execution control for shell and file actions. [Format-Sensitivity Eval]({{ '/projects/format-sensitivity-eval/' | relative_url }}) examines how response format changes observed safety behavior. [Sentinel]({{ '/projects/sentinel/' | relative_url }}) is an evaluation harness for coding agents with executable graders, monitors, and traces. [CausalBench-LLM]({{ '/projects/causalbench-llm/' | relative_url }}) is a synthetic causal-reasoning benchmark with known intervention effects.

<p><a href="{{ '/projects/' | relative_url }}">View earlier projects</a></p>
