# Issue #8 — Let's build the GPT Tokenizer

- **GitHub issue:** https://github.com/majorgilles/karpathy_ml_course/issues/8
- **Video:** https://youtu.be/zduSFxRajkE
- **Lesson notes:** [`lessons/08-gpt-tokenizer.md`](../../lessons/08-gpt-tokenizer.md)
- **Transcript:** [`video_transcripts/08-gpt-tokenizer.md`](../../video_transcripts/08-gpt-tokenizer.md)

## Goal

Implement a GPT-style tokenizer from bytes through BPE merges, encode/decode, and special-token handling.

## Starter notebook

- [`notebooks/08-tokenizer.ipynb`](notebooks/08-tokenizer.ipynb)

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

- [ ] Byte-level tokenizer utilities and BPE merge training.
- [ ] Working `encode()` and `decode()` functions with tests/examples.
- [ ] Notes and examples of tokenizer-driven LLM quirks.
