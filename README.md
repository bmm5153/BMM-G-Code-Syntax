FOR THIS TO WORK PROPERLY, YOU MUST ADD THE CONTENTS OF THE SETTINGS.JSON FILE INTO YOUR LOCAL SETTINGS FILE. USUALLY FOUND:

C:\Users\{username}\AppData\Roaming\Code\User

# bmm-g-code-syntax README

This is working draft of custom syntax for G-Code, for use on Visual Studion Code. Suggestions/improvements/criticisms are welcome and encrouraged as this is my first attempt at several things throughout this process.

## Features

This package is intended to highlight and color specific portions of your G-Code and specific ways. Generally speaking, it is intended to make important or often-searched parts of your G-Code very easy to find, and stand out amongst generic X/Y/Z moves. 

You may further customize or change the coloring of the scopes defined by this extension by altering your local settings.json file.

       "scope": "keyword.control.gcode",    ------> Scope defined by regex in syntaxes\gcode.tmLanguage.json file
       "settings": {      
            "foreground": "#ff0000",        ------> Coloring for all code that falls in this scope
            "fontStyle": "underline",       ------> Any stylising for all code that falls in this scope


## Requirements

You must of VS code installed, and be working with files with extensions: .nc, .eia, or .txt.

## Extension Settings


## Known Issues

1. An extra step needed to set colors to defined scopes in local settings.json file. 

## Release Notes

Users appreciate release notes as you update your extension.

-----------------------------------------------------------------------------------------------------------

## Working with Markdown

### For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**
