# Taplo pre-commit

For Taplo: see https://github.com/tamasfe/taplo

For pre-commit: see https://github.com/pre-commit/pre-commit

## Using Taplo with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/hoxbro/taplo-pre-commit
  rev: v0
  hooks:
    - id: taplo
```
