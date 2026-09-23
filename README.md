# madeye/homebrew-tap

Homebrew formulae for projects by [madeye](https://github.com/madeye).

| Formula | Description |
|---|---|
| `openzl-laya` | [OpenZL-Laya](https://github.com/madeye/openzl-laya): the OpenZL CLI with local Laya integer routing on Core ML (macOS 14+, Apple Silicon) |

```sh
brew install madeye/tap/openzl-laya
openzl-laya-worker prepare   # one-time model download (~940 MB)
```

Formulae are generated from each project's release; for `openzl-laya`, run
`scripts/laya/update_homebrew_formula.sh VERSION SHA256` in the OpenZL-Laya
repository.
