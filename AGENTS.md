# Agent Instructions

## Learning-notebook documentation

When adding or changing learning code in a notebook:

- Add concise inline comments to new or changed code and a nearby Markdown cell that explains the purpose, inputs, outputs, and next concept.
- Keep comments and Markdown synchronized with the executable code, including loop scope, sample counts, smoothing choices, and whether a value is a total or an average.
- For probabilistic or loss code, explicitly distinguish training examples, vocabulary candidates, and the expected target. State which indexed probability contributes directly to the loss.
- Include LaTeX formulas in notebook Markdown for central mathematical relationships. Define every symbol in surrounding prose and prefer a readable progression from one-example loss to dataset-average loss.
- State whether an evaluation loop scores the full dataset or a deliberately supplied test sequence.
- When the request is documentation-only, do not change executable behavior.
- Validate notebook JSON after documentation edits.

## Git scope

- Stage and commit only files within the approved request scope. Do not include generated files, dependency directories, or duplicate datasets unless explicitly requested.
