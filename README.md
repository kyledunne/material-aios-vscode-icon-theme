<!-- markdownlint-disable -->

# AIOS Icon Theme

File and folder icons for an **AIOS** (a personal AI operating system). Built on
the excellent [Material Icon Theme](https://github.com/material-extensions/vscode-material-icon-theme),
with extra folder icons for the conventionally-named files and tools an AIOS uses
every day (`.claude`, `.codex`, and more).

> **This is a separate project.** AIOS Icon Theme is an independent derivative of
> Material Icon Theme, distributed under the MIT license. It is **not** affiliated
> with, endorsed by, or supported by the Material Icon Theme authors. If you want
> the original, install
> [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme).

## Why this exists

An AIOS keeps its configuration and tooling in conventionally-named folders
(`.claude`, `.codex`, and similar). This theme adds first-class icons for those on
top of Material's full icon set, so an AIOS workspace stays readable at a glance.
Everything Material Icon Theme already does, this still does.

## Getting started

1. **Install the extension.**
2. **Activate it** — open the command palette (`Ctrl+Shift+P` / `Cmd+Shift+P`),
   run **AIOS Icons: Activate Icon Theme**, or pick it via
   *Preferences: File Icon Theme → AIOS Icon Theme*.

## Customization

All of Material Icon Theme's customization works here, under the
`aios-icon-theme.*` settings namespace. A few common settings:

```json
"aios-icon-theme.folders.color": "#ef5350",
"aios-icon-theme.files.color": "#42a5f5",
"aios-icon-theme.folders.theme": "specific",
"aios-icon-theme.opacity": 0.9,
"aios-icon-theme.saturation": 0.8
```

Custom file/folder associations, icon clones, icon packs, and per-folder colors
are all supported. For the full reference, see the
[Material Icon Theme customization docs](https://github.com/material-extensions/vscode-material-icon-theme#customization)
— the settings are identical, just with the `aios-icon-theme.` prefix in place of
`material-icon-theme.`.

## Commands

Open the command palette and type **AIOS Icons**:

| Command | Description |
| --- | --- |
| **AIOS Icons: Activate Icon Theme** | Activate the icon theme. |
| **AIOS Icons: Change File Color** | Change the color of the file icons. |
| **AIOS Icons: Change Folder Color** | Change the color of the folder icons. |
| **AIOS Icons: Change Folder Theme** | Change the design of the folder icons. |
| **AIOS Icons: Change Opacity** | Change the opacity of the icons. |
| **AIOS Icons: Change Root Folder Color** | Change the color of the root folder icons. |
| **AIOS Icons: Change Saturation** | Change the saturation value of the icons. |
| **AIOS Icons: Configure Icon Packs** | Enable an icon pack (e.g. Angular, React, Vue). |
| **AIOS Icons: Restore Default Configuration** | Reset to the default configuration. |
| **AIOS Icons: Toggle Explorer Arrows** | Show or hide the arrows next to folder icons. |
| **AIOS Icons: Toggle Grayscale** | Set icon saturation to grayscale, or back to color. |

## Credits & license

Built on [Material Icon Theme](https://github.com/material-extensions/vscode-material-icon-theme)
by Philipp Kief and the material-extensions team — thank you for the icons and the
build tooling this project depends on. Underlying artwork comes from
[Material Design Icons](https://pictogrammers.com/library/mdi/) and
[Material Symbols](https://fonts.google.com/icons).

Released under the MIT License. This project bundles and extends MIT-licensed work
from Material Icon Theme; see [LICENSE](LICENSE).
