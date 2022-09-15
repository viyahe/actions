# install-dependencies

Github Action for installint dependencies

## Supports
- pipenv
- npm / yarn


## Getting Started

To run this action:

```yaml
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: viyahe/actions/install-dependencies@v1
        with:
          npm-install: true
```


## Inputs

| Name             | Required | Required  | Default | Description                   |
| ---------------- | -------- | --------- | ------- | ----------------------------- |
| `npm-install`    | -        | `boolean` | `false` | Installs npm package          |
| `pipenv-install` | -        | `boolean` | `false` | Installs package from pipfile |

## Outputs

| Name | Description |
| ---- | ----------- |
|      |             |