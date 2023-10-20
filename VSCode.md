# Visual Studio Code

## Extensions

Installer les extensions :

- Mardown All in One
- Markdown Preview Enhanced
- Markdown PDF
- markdownlint

## Paramètres

`Ctrl+Shift+P` pour ouvrir la palette de commandes
(Menu Affichage -> Palette de commandes)

Préférences : ouvrir les Paramètres Utilisateur (json)

```json
{
  "editor.bracketPairColorization.enabled": true,
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  "editor.formatOnType": true,
  "files.autoSave": "afterDelay",
  "files.autoSaveDelay": 2000,
  "files.encoding": "utf8",
  "files.eol": "\n",
  "files.trimFinalNewlines": true,
  "files.trimTrailingWhitespace": true,
  "[markdown]": {
    //"editor.wordWrap": "on",
    //"editor.wordWrap": "wordWrapColumn",
    //"editor.quickSuggestions": {
    //  "comments": "off",
    //  "strings": "off",
    //  "other": "off"
    //},
    "editor.trimAutoWhitespace": false,
    "files.trimTrailingWhitespace": false,
    "files.trimFinalNewlines": false,
    "markdown-pdf.highlightStyle": "github.css",
    "markdown-preview-enhanced.enableCriticMarkupSyntax": true
  }
}
```
