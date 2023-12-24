# reusable-workflows

This place collects reusable workflows

# Usage

```yml
name: PR Code Fixer

on:
    pull_request:
        branches: [master]

jobs:
    call-template-code-fixer-linter:
        uses: Mason-Lin/reusable-workflows/.github/workflows/template-code-fixer-linter.yml@master
        secrets: inherit
```
