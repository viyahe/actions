# setup-ssh-key

Github Action for setting up ssh key

## Getting Started

To run this action:

```yaml
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: viyahe/actions/setup-ssh-key@v1
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