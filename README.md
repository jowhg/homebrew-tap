# jowhg/homebrew-tap

Homebrew casks for [SimView](https://github.com/jowhg/simview): all your iOS simulators in one window, plus an
MCP server for AI agents.

```sh
brew tap jowhg/tap
brew trust jowhg/tap   # Homebrew asks you to trust a tap before installing from it
brew install --cask jowhg/tap/simview
```

| Cask | Installs |
| --- | --- |
| `simview` | `SimView.app` in `/Applications`, and `simview-mcp` on your `PATH` |

SimView is not notarized: the first time you open it, allow it in System Settings › Privacy & Security
(**Open Anyway**).
