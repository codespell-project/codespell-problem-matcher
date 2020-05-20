# sort-problem-matcher

This problem matcher lets you show errors from GNU `sort -c` as annotation in
GitHub Actions.

Based on korelstar's xmllint-problem-matcher.

## Inputs

No inputs are required.

## Outputs

No outputs are generated apart from a configured problem matcher.

## Usage

Add the step to your workflow, before `sort -c` is called.

```yaml
    - uses: codespell-project/sort-problem-matcher@v1
```
