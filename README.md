pre-commit-hooks
================

Some secret-hunting hooks for pre-commit.

See also: https://github.com/pre-commit/pre-commit


### Using pre-commit-hooks with pre-commit

Add this to your `.pre-commit-config.yaml`

    -   repo: https://github.com/ryanbreed-tp/pre-commit-hooks
        rev: master
        hooks:
        - id: secrets-crypto
        - id: secrets-cookies
        - id: secrets-api


### Hooks available

- `secrets-crypto`
- `secrets-cookies`
- `secrets-api`
