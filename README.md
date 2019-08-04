# pyre-check pre-commit hook

[pre-commit]() hook for [pyre-check]().

## Using pyre-check with pre-commit

Add this to your `.pre-commit-config.yaml`

```yaml
-   repo: https://github.com/fsouza/pre-commit-pyre-check
    rev: ''  # Use the sha / tag you want to point at
    hooks:
    -   id: pyre-check
```

