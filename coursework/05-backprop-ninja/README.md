# Issue #5 — Building makemore Part 4: Becoming a Backprop Ninja

- **GitHub issue:** https://github.com/majorgilles/karpathy_ml_course/issues/5
- **Video:** https://youtu.be/q8SA3rM6ckI
- **Lesson notes:** [`lessons/05-makemore-backprop-ninja.md`](../../lessons/05-makemore-backprop-ninja.md)
- **Transcript:** [`video_transcripts/05-makemore-backprop-ninja.md`](../../video_transcripts/05-makemore-backprop-ninja.md)

## Goal

Manually derive and verify the gradients for the makemore MLP end-to-end.

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

- [ ] Manual gradients through cross entropy, linear layers, tanh, BatchNorm, and embeddings.
- [ ] Comparisons against PyTorch autograd for every derived gradient.
- [ ] Shape notes documenting the tensor-level backward pass.
