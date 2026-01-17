# vndredev Marketplace

Custom Claude Code plugins for development workflows.

## Available Plugins

| Plugin                                                     | Description                       | Version |
| ---------------------------------------------------------- | --------------------------------- | ------- |
| [devkit-plugin](https://github.com/vndredev/devkit-plugin) | Clean Architecture + Dev Workflow | 0.23.2  |

## Installation

```bash
claude-plugin add vndredev/devkit-plugin
```

## For Developers

Local dev overrides via `.claude-plugin/local.json` (gitignored):

```json
{
  "devkit-plugin": {
    "source": "~/dev/devkit-plugin"
  }
}
```
