prettier-eslint-cli mirror
================

Mirror of prettier-eslint-cli package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For prettier-eslint-cli: see https://github.com/eslint/prettier-eslint-cli


### Using prettier-eslint-cli with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/lfhbento/mirrors-prettier-eslint-cli
        sha: ''  # Use the sha you want to point at
        hooks:
        -   id: prettier-eslint-cli
