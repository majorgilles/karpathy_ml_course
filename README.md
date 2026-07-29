# Neural Networks: Zero to Hero — Lesson Links

Unofficial index of Andrej Karpathy's **Neural Networks: Zero to Hero** course.

- Course page: <https://karpathy.ai/zero-to-hero.html>
- Format: one self-contained lesson workspace under [`coursework/`](coursework/), with its video guide, transcript, and follow-along code together.

## Python environment

This repository is also a [`uv`](https://docs.astral.sh/uv/) project for course exercises and experiments.

```bash
uv sync --dev
uv run ruff check .
uv run ruff format .
```

Runtime dependencies: `numpy`, `pandas`, `seaborn`, and `torch` (PyTorch). Dev dependency: `ruff`.

## Repository layout

- `coursework/` — one self-contained workspace per GitHub issue/lesson, including its guide, transcript, notebooks, code, tests, and artifacts.
- `data/` — shared raw, processed, and external data.
- `artifacts/` — shared small figures, samples, and metrics.

## Lessons

The [official course page](https://karpathy.ai/zero-to-hero.html) currently lists these eight videos and labels the course ongoing.

| # | Duration | Lesson | Video | Summary | Workspace | Transcript |
|---:|:---:|---|---|---|---|---|
| 01 | 2h25m | The spelled-out intro to neural networks and backpropagation: building micrograd | [Watch](https://youtu.be/VMj-3S1tku0) | Build a scalar autograd engine and use backpropagation to train a small neural network. | [workspace](coursework/01-micrograd/README.md) | [transcript](coursework/01-micrograd/transcript.md) |
| 02 | 1h57m | The spelled-out intro to language modeling: building makemore | [Watch](https://youtu.be/PaCmpygFfXo) | Build a bigram character language model; introduce tensors, sampling, and negative log likelihood. | [workspace](coursework/02-makemore-bigram/README.md) | [transcript](coursework/02-makemore-bigram/transcript.md) |
| 03 | 1h15m | Building makemore Part 2: MLP | [Watch](https://youtu.be/TCH_1BHY58I) | Train an MLP language model and cover splits, tuning, hyperparameters, and overfitting. | [workspace](coursework/03-makemore-mlp/README.md) | [transcript](coursework/03-makemore-mlp/transcript.md) |
| 04 | 1h55m | Building makemore Part 3: Activations & Gradients, BatchNorm | [Watch](https://youtu.be/P6sfmUTpUmc) | Diagnose activation and gradient scaling, then use BatchNorm for more stable deep-network training. | [workspace](coursework/04-activations-gradients-batchnorm/README.md) | [transcript](coursework/04-activations-gradients-batchnorm/transcript.md) |
| 05 | 1h55m | Building makemore Part 4: Becoming a Backprop Ninja | [Watch](https://youtu.be/q8SA3rM6ckI) | Manually backpropagate through the MLP at tensor level, including BatchNorm and embeddings. | [workspace](coursework/05-backprop-ninja/README.md) | [transcript](coursework/05-backprop-ninja/transcript.md) |
| 06 | 56m | Building makemore Part 5: Building a WaveNet | [Watch](https://youtu.be/t3YJ5hKiMQ0) | Build a deeper hierarchical, WaveNet-like model while tracking tensor shapes and using `torch.nn`. | [workspace](coursework/06-wavenet/README.md) | [transcript](coursework/06-wavenet/transcript.md) |
| 07 | 1h56m | Let's build GPT: from scratch, in code, spelled out. | [Watch](https://www.youtube.com/watch?v=kCc8FmEb1nY) | Implement a GPT-style Transformer and connect it to autoregressive modeling and ChatGPT. | [workspace](coursework/07-gpt/README.md) | [transcript](coursework/07-gpt/transcript.md) |
| 08 | 2h13m | Let's build the GPT Tokenizer | [Watch](https://youtu.be/zduSFxRajkE) | Build a BPE tokenizer; examine encode/decode and tokenization's effects on LLM behavior. | [workspace](coursework/08-tokenizer/README.md) | [transcript](coursework/08-tokenizer/transcript.md) |

## Attribution

This repository is an unofficial lesson-link index. Lesson titles, durations, links, and summary scope are based on Karpathy's public course page.
