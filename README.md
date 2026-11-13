# Mavio plugins

The official plugin catalog of [Mavio](https://github.com/mavioai/mavio). Each release holds the packages of Mavio's first-party plugins, built from the source of a Mavio release by `tools/plugindist`, and their `catalog.json`. A server installs from the catalog of the latest release, the default of its `plugin-catalog` setting:

```
https://github.com/mavioai/plugins/releases/latest/download/catalog.json
```

Releases are published by the Release workflow, run by hand with the tag of a Mavio release (empty for the latest). The plugins' sources live in [`plugins/`](https://github.com/mavioai/mavio/tree/main/plugins) of the Mavio repository.

Licensed under GPL-3.0.
