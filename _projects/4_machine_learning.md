---
layout: page
title: Machine Learning for Process Optimization
description: Supervised models that predict mechanical performance from process parameters and thermal features, cutting trial-and-error in parameter selection.
importance: 4
category: research
related_publications: true
---

Choosing print parameters is normally an expensive search: change a setting, print a batch, test it,
repeat. With enough characterized batches, that search can be shortcut.

This project trains **supervised models that predict mechanical performance directly from process
parameters and thermal features**, so promising parameter sets can be identified before printing
{% cite ahmed2025machine shanto2025mlstrength %}.

## What the models use

- Process parameters (printhead configuration, speed, spacing, temperature)
- Thermal features extracted from MWIR thermography of the bond line
- Measured mechanical response as the training target

## Related directions

The same dataset supported work on **deep learning architectures for defect detection** in FFF
{% cite dola2026evaluation %}, and on using **large language models** for process parameter optimization
{% cite shanto2025llmparams %} — evaluating whether general-purpose models can propose viable parameter
sets against a physically characterized baseline.

## Why it matters

The value is not the model accuracy in isolation but the reduction in physical experiments needed to
reach a qualified parameter set — the dominant cost in developing any new material or geometry.
