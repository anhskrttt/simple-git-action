# simple-git-action

Trying to display this README through github pages.

## Heading 1

Random text goes here.

## Usage

This is an example of Github Action for [ShellCheck](https://github.com/marketplace/actions/shellcheck).

```yaml
on:
  push:
    branches:
      - master

name: 'Trigger: Push action'
permissions: {}

jobs:
  shellcheck:
    name: Shellcheck
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Run ShellCheck
        uses: ludeeus/action-shellcheck@master
```
