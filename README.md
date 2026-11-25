# 🍺 iamludal/homebrew-tap

[Homebrew](https://brew.sh) formulae and casks for my tools.

## 📦 Install

```bash
brew install iamludal/tap/<name>
```

Or add the tap once, then install by name:

```bash
brew tap iamludal/tap
brew install <name>
```

## 🧰 Available

| Name | Description |
|---|---|
| [`kvx`](https://github.com/iamludal/kvx) | 🔐 Power tools for Vault and OpenBao KV secrets |

## 🔄 Update

```bash
brew update && brew upgrade
```

## 🤖 How it works

The files in [`Casks/`](Casks) are generated and pushed by
[GoReleaser](https://goreleaser.com) on every release of each tool, so
**don't edit them by hand**: changes would be overwritten at the next
release.

## 🐛 Issues

For a bug in a tool, open an issue in that tool's repository. Open one here
only for a problem with the installation itself.

## 📄 License

[MIT](LICENSE)
