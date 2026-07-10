---
layout: page
title: Sentinel
description: Evaluation harness for coding agents with graders, monitors, traces, and artifacts.
img:
importance: 3
category: research
---

[Sentinel](https://github.com/udsea/sentinel) is a lightweight evaluation harness for coding agents. It runs task specs in isolated workspaces, records traces, applies executable graders, runs behavioral monitors, and exports JSON artifacts.

The central design choice is to track task success and suspicious behavior separately. A coding agent can pass grading while still being flagged by monitors for behavior such as protected-path writes, risky final-output language, suspicious written content, configurable write-policy violations, or test-informed shortcut edits.

What this project is for:

- making coding-agent behavior easier to inspect after a run
- separating grader success from monitor concerns
- supporting deterministic scripted agents and bounded model-backed agents
- producing artifacts another engineer can review

Status: proof-of-life harness with scripted demos, OpenRouter-backed smoke paths, task fixtures, monitor outputs, and experiment configs.
