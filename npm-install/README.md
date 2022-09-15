# npm-install 

Github Action for installing npm dependencies

## Getting Started

To run this action:

```yaml
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: viyahe/actions/npm-install@v1
        with:
          npm-install: true
```


## Inputs

| Name | Required | Required | Default | Description |
| ---- | -------- | -------- | ------- | ----------- |
|      |          |          |         |             |

## Outputs

| Name | Description |
| ---- | ----------- |
|      |             |