ember-template-lint mirror
================

Mirror of ember-template-lint package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For ember-template-lint: see https://github.com/ember-template-lint/ember-template-lint


### Using ember-template-lint with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: ./ember-template-lint-pre-commit
        rev: master
        hooks:
          - id: ember-template-lint