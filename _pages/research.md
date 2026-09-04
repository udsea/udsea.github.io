---
layout: page
title: research
permalink: /research/
description: Reliable learned trajectories, across generative models and reasoning agents.
nav: true
nav_order: 2
---

## Research Statement

I study reliable trajectory-generating systems: learned systems that move from uncertainty to structure. In generative modeling, this means trajectories that transform noise into samples. In reasoning and agency, it means trajectories that transform incomplete information into actions, decisions, or explanations.

The central problem is not whether a model can produce an answer once. It is whether the trajectory that produced it remains robust under pressure, controllable under intervention, and interpretable enough to reveal shortcuts. I treat evaluation as measurement engineering: build tasks and artifacts that make those properties observable.

## One Spine, Two Testbeds

### Flow-Based Generative Models

Diffusion and flow matching offer a direct setting for studying learned trajectories. I am interested in the geometry of learned transport, how conditioning changes a path, when a path is robust to perturbation, and what kinds of controls reliably steer generation. A longer-term application is AI4Science, where the generated object has scientific structure rather than only visual plausibility.

### Reasoning Agents

Reasoning and agentic systems expose a second kind of trajectory: a sequence of tool calls, intermediate decisions, or policy updates made under uncertainty. Current work uses coding agents, causal reasoning, and safety-tuned language models to study pre-execution oversight, format-sensitive behavior, and optimization pressure that creates brittle shortcuts.

## Current Questions

1. **How do learned trajectories change under objective and conditioning pressure?** This connects flow-based generation, RL reasoning, and controllability.
2. **When does optimization create a shortcut rather than a robust mechanism?** PressureTrace and related agent evaluations make that tradeoff visible in action traces.
3. **Can causal interventions distinguish robust behavior from a spurious rule?** CausalBench-LLM uses known structural causal models to make intervention effects scoreable.
4. **What evidence makes a trajectory controllable?** ActionLens tests whether proposed agent actions can be inspected before execution; diffusion and flow-matching work asks the analogous question for generative paths.
5. **How can interpretability support reliability rather than only post-hoc explanation?** The goal is to connect internal or external evidence to interventions that change future behavior.

## Purpose

The long-term purpose is to understand learned trajectories under optimization well enough to control them. I want tools and benchmarks that are small enough to inspect, sharp enough to reveal a specific failure, and honest enough to report their limits.

The near-term purpose is to make public work easier to follow: clear assumptions, reproducible artifacts, concrete case studies, and an explicit record of what would change a conclusion.

## Principles

- **Follow the trajectory, not only the endpoint.** A good output can conceal a brittle or unsafe path.
- **Use interventions where possible.** Causal robustness requires more than correlational evidence.
- **Keep evidence inspectable.** Logs, traces, generated objects, and task specifications should be auditable.
- **Separate capability from control.** A system can complete a task and still behave in a way that should not be approved.
- **Report limitations directly.** Small studies, heuristic monitors, and synthetic tasks are useful only when their scope is explicit.
