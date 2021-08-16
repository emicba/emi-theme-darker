<h1 align="center">✨ Emi theme (darker) ✨</h1>

## Installation

You can get this theme from the [VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=Emi.emi-theme-darker).

## Recomended settings ✨

- [Cascadia Code Font](https://github.com/microsoft/cascadia-code)

- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

- VSCode Settings:
  ```json
  "editor.fontFamily": "Cascadia Code",
  "editor.fontWeight": "350",
  "editor.fontLigatures": true,
  ```

## Override color scheme

Tokens can be overridden by adding theme-specific settings to your config.
More info at [VSCode Themes Docs](https://code.visualstudio.com/docs/getstarted/themes#_workbench-colors).

_Example_

```json
"editor.tokenColorCustomizations": {
  "[Emi Theme Darker]": {
    "textMateRules": [
      {
        "name": "Storage",
        "scope": "storage.type.js",
        "settings": {
          "fontStyle": "underline"
        }
      }
    ]
  }
}
```
