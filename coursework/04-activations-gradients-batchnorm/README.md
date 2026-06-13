# Issue #4 — Building makemore Part 3: Activations & Gradients, BatchNorm

- **GitHub issue:** https://github.com/majorgilles/karpathy_ml_course/issues/4
- **Video:** https://youtu.be/P6sfmUTpUmc
- **Lesson notes:** [`lessons/04-makemore-activations-gradients-batchnorm.md`](../../lessons/04-makemore-activations-gradients-batchnorm.md)
- **Transcript:** [`video_transcripts/04-makemore-activations-gradients-batchnorm.md`](../../video_transcripts/04-makemore-activations-gradients-batchnorm.md)

## Goal

Diagnose training health by inspecting activations, gradients, initialization, and BatchNorm behavior.

## Starter notebook

- [`notebooks/04-activations-gradients-batchnorm.ipynb`](notebooks/04-activations-gradients-batchnorm.ipynb)

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

- [ ] Activation and gradient histograms/diagnostics for the MLP.
- [ ] Improved initialization and BatchNorm implementation.
- [ ] Notes comparing training-time and inference-time BatchNorm behavior.
