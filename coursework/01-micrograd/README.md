# Issue #1 — The spelled-out intro to neural networks and backpropagation: building micrograd

- **GitHub issue:** https://github.com/majorgilles/karpathy_ml_course/issues/1
- **Video:** https://youtu.be/VMj-3S1tku0
- **Lesson notes:** [`lessons/01-micrograd-backpropagation.md`](../../lessons/01-micrograd-backpropagation.md)
- **Transcript:** [`video_transcripts/01-micrograd-backpropagation.md`](../../video_transcripts/01-micrograd-backpropagation.md)

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
