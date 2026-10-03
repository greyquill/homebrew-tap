<p>
  <a href="https://mcpsight.dev">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://mcpsight.dev/brand/lockup-dark.svg">
      <img src="https://mcpsight.dev/brand/lockup.svg" alt="mcpsight" width="182" height="40">
    </picture>
  </a>
</p>

# Greyquill Homebrew tap

Homebrew packages published by [Greyquill Software](https://www.greyquill.io).

## MCPsight

[MCPsight](https://mcpsight.dev/) inspects an MCP server before you
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
