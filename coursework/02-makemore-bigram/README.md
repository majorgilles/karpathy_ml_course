# Issue #2 — The spelled-out intro to language modeling: building makemore

- **GitHub issue:** https://github.com/majorgilles/karpathy_ml_course/issues/2
- **Video:** https://youtu.be/PaCmpygFfXo
- **Duration:** 1h57m
- **Transcript:** [`transcript.md`](transcript.md)

## Lesson focus

Build a bigram character-level language model and learn the basic language-modeling loop: training, sampling, and loss evaluation.

## Learning checkpoint

By the end, you should be able to describe how a simple character-level model predicts the next token and how its loss is measured.

## Goal

Implement the makemore bigram language model and the basic train/sample/evaluate loop for character-level modeling.

## Starter notebook

- [`notebooks/02-makemore-bigram.ipynb`](notebooks/02-makemore-bigram.ipynb)

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

- [ ] Bigram count and probability tables for the names dataset.
- [ ] A neural bigram version using PyTorch tensors and gradient descent.
- [ ] Generated samples and loss measurements for both approaches.
