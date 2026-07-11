---
layout: about
title: about
permalink: /
subtitle: Evaluation, agent oversight, causal reasoning, and research tools.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular
  more_info: >
    <p><a href="mailto:udbhavchitransh@gmail.com">udbhavchitransh@gmail.com</a></p>
    <p><a href="https://github.com/udsea">github.com/udsea</a></p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am Udbhav. I study how generative and reasoning systems learn structured transformations under uncertainty, and how to make those transformations reliable, controllable, and robust under shift. I build evaluation systems with a focus on failure modes that ordinary benchmark scores can miss: format-sensitive safety behavior, shortcut-seeking under pressure, causal reasoning errors, and oversight for autonomous tools.

My work is mostly practical and empirical. I like small benchmarks with clear threat models, reproducible runners, explicit limitations, and artifacts that another engineer can inspect. The common thread is control: how to tell whether a model is doing the task for the right reason, whether an evaluation protocol is measuring deployment behavior, and whether an agent's proposed action is safe before it touches the environment.

This website collects research scaffolds, experiments, and notes as they mature from prototypes into sharper benchmarks or writeups.

## Purpose

The purpose of this site is to make my work easier to audit. Each project should eventually answer four questions:

- What behavior is being measured?
- What can the current evidence support?
- What are the main limitations?
- What would make the result stronger?

## Current Direction

I am especially interested in:

- agent control protocols that inspect proposed actions before execution
- monitors that separate task success from suspicious behavior
- LLM safety evaluations where prompt format changes measured behavior
- causal reasoning benchmarks with known ground truth intervention effects
- pressure tests for shortcut-seeking, specification gaming, and oversight gaps

For now, the best public links are email and GitHub.
