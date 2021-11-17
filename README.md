# pre-commit-lizard

This is a pre-comit hook for lizard.

For pre-commit: see `https://github.com/pre-commit/pre-commit`

For lizard: see `https://github.com/terryyin/lizard`

## Using lizard with pre-commit

Add this to your `.pre-commit-config.yaml`:
```yaml
- repo: https://github.com/johnor/pre-commit-lizard
  rev: '' # Use the tag you want to point at
  hooks:
    - id: lizard-cpp
```

## Available Hooks

### `lizard-cpp`
Run lizard on c++ files. Uses default settings in lizard and prints warnings.
