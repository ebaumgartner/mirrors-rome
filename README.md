rome mirror
===============

Mirror of rome package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For rome: see https://rome.tools/


### Using rome with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
-   repo: https://github.com/ebaumgartner/mirrors-rome
    rev: ''  # Use the sha / tag you want to point at
    hooks:
    -   id: rome
```

Please note that while rome supports both formatting and linting, this hook
only reformats.