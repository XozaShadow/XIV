# XIV

Dalamud plugin catalog for XozaShadow plugins. Source stays in each plugin repo. This repo is only the installer list.

## Install

In game: `/xlsettings` → **Experimental** → **Custom Plugin Repositories**, add:

```
https://raw.githubusercontent.com/XozaShadow/XIV/main/repo.json
```

Save, then `/xlplugins`. Search **XozaShadow**, or a plugin name.

Turn on **Get plugin testing versions** if you want LightsOn test builds.

Do not also add each plugin’s own `repo.json`. Same `InternalName` in two catalogs duplicates in the installer.

## Plugins

| Plugin | What | Source |
| --- | --- | --- |
| **LightsOn** | Occupancy for listed venues and short outdoor scenes | [LightsOn](https://github.com/XozaShadow/LightsOn) |
| **StatusShift** | Online status, search comment, and commands from zone, activity, and schedule | [StatusShift](https://github.com/XozaShadow/StatusShift) |

Zips come from each plugin’s GitHub Releases. This file only points at them.

A scheduled Action refreshes `repo.json` from those repos. Run **Sync plugin catalog** on Actions if a release just dropped and the list is stale.
