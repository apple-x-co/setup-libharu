# setup-libharu

## Usage

```
jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - uses: apple-x-co/setup-libharu@v1
```

OR

```
jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - uses: apple-x-co/setup-libharu@v1
        with:
          libharu-version: 2.4.3
```
