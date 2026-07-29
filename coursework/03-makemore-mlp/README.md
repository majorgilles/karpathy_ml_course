# Issue #3 — Building makemore Part 2: MLP

- **GitHub issue:** https://github.com/majorgilles/karpathy_ml_course/issues/3
- **Video:** https://youtu.be/TCH_1BHY58I
- **Duration:** 1h15m
- **Transcript:** [`transcript.md`](transcript.md)

## Lesson focus

Extend makemore into a multilayer perceptron character-level language model while introducing practical ML workflow concepts.

## Learning checkpoint

By the end, you should understand train/dev/test splits, learning-rate tuning, hyperparameters, and overfitting at a basic level.

## Goal

Move from bigram tables to a learned embedding plus MLP language model for next-character prediction.

## Starter notebook

- [`notebooks/03-makemore-mlp.ipynb`](notebooks/03-makemore-mlp.ipynb)

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

- [ ] Context-window dataset construction for makemore.
- [ ] Embedding lookup, hidden layer, logits, and cross-entropy loss in PyTorch.
- [ ] Train/dev/test split, learning-rate sweep, loss curves, and generated names.
