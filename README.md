# tstdl Claude Code marketplace

Claude Code plugin marketplace for the `@tstdl` ecosystem.

## Plugins

| Name | Description |
| :--- | :--- |
| [`tstdl-base`](https://www.npmjs.com/package/@tstdl/base) | Skills for application developers building on `@tstdl/base` — core conventions, DI, ORM, contract-first APIs. |

## Install

In your Claude Code session, add this marketplace once:

```
/plugin marketplace add bagbag/claude-marketplace
```

Then install a plugin:

```
/plugin install tstdl-base
```

Skills become available namespaced as `tstdl-base:core`, `tstdl-base:orm`, `tstdl-base:api`, `tstdl-base:injector`.

## Updates

After a new `@tstdl/base` release that matches the marketplace's semver range:

```
/plugin update tstdl-base
```

To pull marketplace changes (e.g., a new plugin added):

```
/plugin marketplace update tstdl
```
