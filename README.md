# franck-plugins

A self-hosted [Claude Code](https://code.claude.com) plugin marketplace.

## Install a plugin from this marketplace

Add the marketplace, then install:

```bash
claude plugin marketplace add Franck1120/franck-plugins
claude plugin install pluginforge@franck-plugins
```

Or install a plugin straight from its repo without the marketplace:

```bash
claude plugin install Franck1120/pluginforge
```

## Plugins

| Plugin | Description |
|--------|-------------|
| [pluginforge](https://github.com/Franck1120/pluginforge) | The plugin that builds plugins. Scaffold a publishable Claude Code plugin from a one-line idea in under 60 seconds. |

## Add your own

The marketplace manifest lives at [`.claude-plugin/marketplace.json`](.claude-plugin/marketplace.json).
Each entry points at a GitHub repo containing a valid `.claude-plugin/plugin.json`.

## License

MIT.
