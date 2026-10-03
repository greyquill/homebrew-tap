# Greyquill Homebrew tap

Homebrew packages published by [Greyquill Software](https://www.greyquill.io).

## MCPsight

[MCPsight](https://www.greyquill.io/mcpsight/) inspects an MCP server before you
trust it: what it costs in tokens, what it can reach, and whether it changed.

```console
brew install --cask greyquill/tap/mcpsight
```

To upgrade:

```console
brew upgrade --cask mcpsight
```

The cask in `Casks/` is written by the MCPsight release workflow on every release.
Please do not edit it by hand. Report problems in the
[MCPsight repo](https://github.com/greyquill/mcpsight/issues).
