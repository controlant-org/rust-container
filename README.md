A [reusable workflow](https://docs.github.com/en/actions/using-workflows/reusing-workflows) for building Rust projects into containers.

## Usage

```yaml
name: Build and publish container

on:
  push:
  workflow_dispatch:

jobs:
  build:
    uses: controlant-org/rust-container/.github/workflows/build.yaml@master
```
