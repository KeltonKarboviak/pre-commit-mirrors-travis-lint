# travis cli pre-commit mirror

Mirror of travis cli package for pre-commit. Runs the `travis lint` command.

For pre-commit: see <https://github.com/pre-commit/pre-commit>

For travis: see <https://github.com/travis-ci/travis.rb>

## Using travis with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
repos:
  - repo: https://github.com/KeltonKarboviak/pre-commit-mirrors-travis-lint
    rev: ''  # Use the sha / tag you want to point at
    hooks:
      - id: travis
```
