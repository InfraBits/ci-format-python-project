# Format a Python project

Re-formats a Python code base

## Example Usage

```
  format-project:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - uses: infrabits/ci-format-python-project@main
```
