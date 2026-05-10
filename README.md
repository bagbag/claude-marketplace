# tstdl Claude Code marketplace

Claude Code plugin marketplace for the `@tstdl` ecosystem.

## Plugins

| Name | Description |
| :--- | :--- |
| [`tstdl-base`](https://www.npmjs.com/package/@tstdl/base) | Scaffolding (`init`), core conventions, and per-module patterns for `@tstdl/base` consumers. Versioned with the npm package. |

## Install

In your Claude Code session, add this marketplace once:

```
/plugin marketplace add bagbag/claude-marketplace
```

Then install:

```
/plugin install tstdl-base
```

Skills become available namespaced as `tstdl-base:init`, `tstdl-base:core`, `tstdl-base:orm`, `tstdl-base:api`, `tstdl-base:injector`.

## Updates

After a new `@tstdl/base` release that matches the marketplace's semver range:

```
/plugin update tstdl-base
```

To pull marketplace changes (e.g., a new plugin added):

```
/plugin marketplace update tstdl
```
