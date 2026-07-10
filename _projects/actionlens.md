---
layout: page
title: ActionLens
description: Pre-execution control for shell and file actions.
img:
importance: 1
category: research
---

[ActionLens](https://github.com/udsea/actionlens) is a pre-execution control protocol for shell and file actions. Instead of approving a proposed action from transcript text alone, a trusted monitor can gather lightweight environment evidence before execution.

The current benchmark compares transcript-only monitoring against active probes such as target inspection, sensitivity scans, dry runs, diff previews, network-risk checks, and history context.

The core result from the public README is that transcript-only monitoring approves every attack in the deterministic benchmark, while ActionLens blocks the attack set and preserves benign completion. The strongest ablation signal is `preview_diff`, which contributes the largest share of attack coverage.

What this project is for:

- testing whether oversight can become more useful before an action executes
- measuring safety/usefulness tradeoffs for agent-control protocols
- studying where passive transcript review fails
- producing inspectable case studies and ablations

Status: active research prototype with deterministic benchmark tasks, BashArena-style transfer slices, hosted-model proposer loops, and multi-model sweeps.
