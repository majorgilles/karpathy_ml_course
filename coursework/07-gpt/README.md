# Issue #7 — Let's build GPT: from scratch, in code, spelled out.

- **GitHub issue:** https://github.com/majorgilles/karpathy_ml_course/issues/7
- **Video:** https://www.youtube.com/watch?v=kCc8FmEb1nY
- **Lesson notes:** [`lessons/07-gpt-from-scratch.md`](../../lessons/07-gpt-from-scratch.md)
- **Transcript:** [`video_transcripts/07-gpt-from-scratch.md`](../../video_transcripts/07-gpt-from-scratch.md)

## Goal

Build a compact GPT-style autoregressive Transformer from data loading through text generation.

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

- [ ] Character-level data pipeline, batching, and train/validation loss evaluation.
- [ ] Self-attention, causal masking, multi-head attention, feed-forward layers, residuals, layer norm, and dropout.
- [ ] A trained tiny GPT model with generated samples and notes on scaling.
