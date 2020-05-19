# sort-problem-matcher

This problem matcher lets you show errors from GNU `sort` as annotation in GitHub Actions.

Based on korelstar's xmllint-problem-matcher.

## Usage

Add the step to your workflow, before `sort -c` is called.

```yaml
    - uses: codespell-project/sort-problem-matcher@v1
```
