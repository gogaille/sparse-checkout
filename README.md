# Sparse checkout composite action

This action allows to sparse checkout a git repository, aims to speedup cloning time on mono repositories.

## Inputs

### `patterns`

**Required** The patterns to sparse checkout into the repository. Default `"*"`.

## Example usage

```yaml
- uses: gogaille/sparse-checkout
  with:
    patterns: 'some_directory some_other_directory'
```
