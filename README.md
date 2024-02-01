# bandit pre-commit hook

pre-commit hook of bandit with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For bandit: see [here](https://github.com/PyCQA/bandit)

## Using bandit with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-bandit
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: bandit-conda
```
