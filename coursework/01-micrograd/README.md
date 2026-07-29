# Issue #1 — The spelled-out intro to neural networks and backpropagation: building micrograd

- **GitHub issue:** https://github.com/majorgilles/karpathy_ml_course/issues/1
- **Video:** https://youtu.be/VMj-3S1tku0
- **Duration:** 2h25m
- **Transcript:** [`transcript.md`](transcript.md)

## Lesson focus

A ground-up introduction to neural networks and backpropagation, using Micrograd to make the mechanics explicit.

## Learning checkpoint

By the end, you should be able to explain how a computation graph supports gradient-based optimization.

## Goal

Rebuild the core scalar autograd engine and a tiny MLP so backpropagation is concrete rather than magical.

## Starter notebook

- [`notebooks/01-micrograd.ipynb`](notebooks/01-micrograd.ipynb)

## Folder contract

- `notebooks/` — exploratory notebooks while following the lecture.
- `src/` — cleaned-up Python modules or scripts worth keeping.
- `tests/` — lightweight checks, gradient checks, shape checks, or reproducibility checks.
- `artifacts/` — small generated plots, samples, metrics, or screenshots that document progress.

## Suggested workflow

1. Skim the issue and transcript before starting.
2. Follow the video in `notebooks/` or a scratch script.
3. Move reusable code into `src/` once it stabilizes.
4. Add small checks in `tests/` for the important lesson-specific behavior.
5. Save representative outputs in `artifacts/` and summarize findings back in the issue.

## Deliverables

- [ ] A working scalar `Value` object with forward and backward passes.
- [ ] Small neuron/layer/MLP code that trains on a toy dataset.
- [ ] Gradient checks or tiny examples showing backprop works as expected.
