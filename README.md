# pyre-check pre-commit hook

[pre-commit](https://pre-commit.com) hook for
[pyre-check](https://pyre-check.org/).

## Using pyre-check with pre-commit

Add this to your `.pre-commit-config.yaml`

```yaml
-   repo: https://github.com/fsouza/pre-commit-pyre-check
    rev: ''  # Use the sha / tag you want to point at
    hooks:
    -   id: pyre-check
```

