# Issue #6 — Building makemore Part 5: Building a WaveNet

- **GitHub issue:** https://github.com/majorgilles/karpathy_ml_course/issues/6
- **Video:** https://youtu.be/t3YJ5hKiMQ0
- **Duration:** 56m
- **Transcript:** [`transcript.md`](transcript.md)

## Lesson focus

Make the makemore model deeper with a tree-like structure that approaches the WaveNet architecture style.

## Learning checkpoint

By the end, you should be more comfortable tracking tensor shapes and using `torch.nn` as part of an iterative deep-learning workflow.

## Goal

Refactor makemore into deeper module-style code and build a WaveNet-like hierarchical context model.

## Starter notebook

- [`notebooks/06-wavenet.ipynb`](notebooks/06-wavenet.ipynb)

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

- [ ] PyTorch-style module classes for the makemore components.
- [ ] A `FlattenConsecutive`/hierarchical model that groups context tokens.
- [ ] Generated samples and loss comparisons against earlier makemore models.
