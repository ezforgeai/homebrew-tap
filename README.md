# ezforgeai/homebrew-tap

Official Homebrew tap for [ezForge AI](https://ezforge.ai) CLI tools.

## Install

```bash
brew install ezforgeai/tap/ezforge
```

Or, equivalently:

```bash
brew tap ezforgeai/tap
brew install ezforge
```

## Formulas

| Formula | Description | Upstream |
|---------|-------------|----------|
| [`ezforge`](./ezforge.rb) | The `ezforge` CLI for the ezForge platform | [`ezforgeai/ezforge-cli`](https://github.com/ezforgeai/ezforge-cli) |

## About this tap

This tap is **automatically maintained** by [GoReleaser](https://goreleaser.com) from releases published in [`ezforgeai/ezforge-cli`](https://github.com/ezforgeai/ezforge-cli). Every new CLI release updates the corresponding formula here with new version numbers, archive URLs, and SHA-256 checksums.

**Do not file issues or pull requests against this repository.** Formula content is overwritten on every upstream release, so manual edits will be lost.

- For CLI bugs or feature requests: see [docs.ezforge.ai](https://docs.ezforge.ai)
- For installation help: see the [Quickstart](https://docs.ezforge.ai/getting-started/quickstart)
- If a formula appears broken: verify the corresponding [`ezforge-cli` release](https://github.com/ezforgeai/ezforge-cli/releases) published successfully

## License

See [`LICENSE`](./LICENSE).
