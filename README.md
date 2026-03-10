# homebrew-tap

Homebrew tap for Reproq command-line tooling.

This repository currently publishes the formula for:

- `reproq-tui`: realtime terminal dashboard for Reproq Worker and Reproq Django

## Install

```bash
brew tap adpena/tap
brew install reproq-tui
```

## Upgrade

```bash
brew update
brew upgrade reproq-tui
```

## Uninstall

```bash
brew uninstall reproq-tui
brew untap adpena/tap
```

## Formula Maintenance

Formulae in this repository are generated from upstream release artifacts. The tap
is intentionally small: release automation updates the formula here, while product
documentation and issue tracking live in the main project repository.

- Upstream project: [`adpena/reproq-tui`](https://github.com/adpena/reproq-tui)
- Releases: <https://github.com/adpena/reproq-tui/releases>

## Reporting Problems

If installation fails because of a formula issue, open an issue in the upstream
project and include:

- your macOS version
- your Homebrew version
- the exact `brew install` or `brew upgrade` output
- the formula version you attempted to install

## License

Apache License 2.0. See [LICENSE](LICENSE).
