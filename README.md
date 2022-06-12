# Material Theme Oceanic custom for VS Code

<div align="center">
    <img src="logo.png" width="250" height="250" alt="logo"></img>
</div>

## It looks like this

![laptop-full](IDE_view.png)

## Description

This is a port of the famous [Material Theme](https://github.com/equinusocio/vsc-material-theme) Android studio for Vs Code, allowing a total customization.
This theme is made for Flutter and dart.

## Install

[How to install Visual Studio Code extensions](https://code.visualstudio.com/docs/editor/extension-marketplace)

[Direct link to Visual Studio Code Marketplace](https://marketplace.visualstudio.com/items?itemName=berthomejulien.material-theme-oceanic-custom)

## Recommended settings

For the theme to be most effective with Flutter, I recommend these settings in the settings file:

Open the settings.json file in your IDE => `Ctrl` + `Shift` + `P` and tap `settings.json`

```
{
    "debug.openDebug": "openOnDebugBreak",
    
    // [Editor] personalization
    "editor.minimap.enabled": false,
    "editor.renderWhitespace": "none",
    "editor.fontSize": 16,
    "editor.autoClosingBrackets": "always",
    "editor.lineHeight": 30,
    "editor.bracketPairColorization.enabled": true,
    "editor.showUnused": true,
    "editor.tokenColorCustomizations": {
      "textMateRules": [
        {
          "scope": "punctuation",
          "settings": {
            "foreground": "#89ddffbd"
          }
        },
      ],
    },
    "editor.semanticHighlighting.enabled": true,
    "editor.semanticTokenColorCustomizations": {
      "rules": {
        "parameter.label": "#f78c6c",
      },
    },
    
    // [Workbench] personalization
    "workbench.tree.indent": 15,
    "workbench.iconTheme": "material-icon-theme",
    "workbench.colorTheme": "Material theme oceanic custom",
    "workbench.colorCustomizations": {
      "editorBracketHighlight.foreground1": "#89ddffbd",
      "editorBracketHighlight.foreground2": "#89ddffbd",
      "editorBracketHighlight.foreground3": "#89ddffbd",
      "editorBracketHighlight.foreground4": "#89ddffbd",
      "editorBracketHighlight.foreground5": "#89ddffbd",
      "editorBracketHighlight.foreground6": "#89ddffbd",
      "editorBracketHighlight.unexpectedBracket.foreground": "#89ddffbd"
    },
    
    // [Flutter] recommended settings
    "dart.openDevTools": "flutter",
    "dart.devToolsTheme": "dark",
    "dart.previewFlutterUiGuides": false,
    "dart.previewFlutterUiGuidesCustomTracking": false,
    "[dart]": {
      "editor.formatOnSave": true,
      "editor.formatOnType": true,
      "editor.rulers": [80],
      "editor.selectionHighlight": false,
      "editor.suggest.snippetsPreventQuickSuggestions": false,
      "editor.suggestSelection": "first",
      "editor.tabCompletion": "onlySnippets",
      "editor.wordBasedSuggestions": false,
    },
    "files.autoSave": "afterDelay"
}
```

## License

Licensed under MIT