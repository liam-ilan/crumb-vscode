# Crumb Syntax Highlighter for Visual Studio Code
The Visual Studio Code syntax highlighter extension for [Crumb](https://github.com/liam-ilan/crumb). Install the extension [here](https://marketplace.visualstudio.com/items?itemName=liamilan.crumb).

## Examples
| ![example 1](./assets/example-1.png) | ![example 2](./assets/example-2.png) |
|---|---|

# Size of the Highlighter
The TextMate grammar for this highlighter is tiny ([less than 50 lines of very whitespaced json](./syntaxes/crumb.tmLanguage.json)). Since Crumb's whole syntax can be described in 6 lines of EBNF, simplicity carries through! Crumb has no keywords, so all that needs to be highlighted are closures, comments, strings, numbers, and some minor special symbols (`->`, `<-`, and `=`).

## Author
Built by [Liam Ilan](https://www.liamilan.com/).