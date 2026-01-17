# vndredev Marketplace

Custom Claude Code plugins for development workflows.

## Available Plugins

| Plugin                                                     | Description                       | Prod Version | Dev Source            |
| ---------------------------------------------------------- | --------------------------------- | ------------ | --------------------- |
| [devkit-plugin](https://github.com/vndredev/devkit-plugin) | Clean Architecture + Dev Workflow | v0.23.2      | `~/dev/devkit-plugin` |

## Installation

**Production** (stable release):

```bash
claude-plugin add vndredev/devkit-plugin
```

**Development** (local source):

```bash
claude-plugin add --local ~/dev/devkit-plugin
```

## Manifest

Plugin metadata in `.claude-plugin/marketplace.json`:

```json
{
  "plugins": [
    {
      "name": "devkit-plugin",
      "versions": {
        "prod": { "version": "0.23.2", "source": "github:..." },
        "dev": { "version": "local", "source": "~/dev/..." }
      }
    }
  ]
}
```
