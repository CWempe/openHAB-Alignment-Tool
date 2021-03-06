# openHAB Alignment Tool

[![Build Status](https://maxbec.visualstudio.com/openHAB%20Alignment%20Tool/_apis/build/status/MaxBec.openHAB-Alignment-Tool?branchName=master)](https://maxbec.visualstudio.com/openHAB%20Alignment%20Tool/_build/latest?definitionId=1&branchName=master)
[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/max-beckenbauer.oh-alignment-tool?color=blue&label=Installs&logo=visual-studio-code)](https://img.shields.io/visual-studio-marketplace/i/max-beckenbauer.oh-alignment-tool?color=blue&label=Installs&logo=visual-studio-code)
[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/max-beckenbauer.oh-alignment-tool?color=orange&label=Version)](https://img.shields.io/visual-studio-marketplace/v/max-beckenbauer.oh-alignment-tool?color=orange)
[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/stars/max-beckenbauer.oh-alignment-tool?label=Rating&logo=visual-studio-code)](https://img.shields.io/visual-studio-marketplace/stars/max-beckenbauer.oh-alignment-tool?label=Rating&logo=visual-studio-code)

This extension adds support for formatting and indenting [openHAB](http://www.openhab.org) files like `*.items`, `*.things`, etc. At the moment only `*.items` and `*.sitemap` files are supported. They can be formatted in a column or multiline style. In the future the other file types and other
format-types will be added. Feel free to enter feature-requests.

## Features

The tool is available via the Command-Palette. Just type `cmnd+shift+p` and enter `openHAB Alignment Tool`. Then you get the option to format the whole file.

### Item-Formatting:

![formatting item gif](images/item-formatting.gif)

### Sitemap-Formatting:

![formatting sitemap gif](images/sitemap-formatting.gif)

## Limitations

The formatting is available for the following openhab file types:

-    `.items`
-    `.sitemap`

## Extension Settings

### New Line After Item

With this option you can choose if you want to have a new line after each item.

`"oh-alignment-tool.newLineAfterItem": true`

### Preserve Whitespace

Whitespaces in front of items get preserved and won't be deleted.

`"oh-alignment-tool.preserveWhitespace": true`

### Multiline Indent Amount

With this option you can control the amount of indent when using the Multiline format.

`"oh-alignment-tool.multilineIndentAmount": 28`

### Format Style

The format style option gives you two styles between you can choose.

-    Column
-    ChannelColumn
-    Multiline

The Column style formats the files in a column-way. Each item will be on one line and the item parts are separated in columns. The Multiline format prints every part of an item in a new line and indents the different parts.

## Known Issues

See [Github Issues](https://github.com/MaxBec/openHAB-Alignment-Tool/issues) file for the details.

## Release Notes

See [CHANGELOG.md](https://github.com/MaxBec/openHAB-Alignment-Tool/blob/master/CHANGELOG.md) file for the details.

---

### For More Information

-    [openHAB Documentation](https://www.openhab.org/docs/)
-    [openHAB Community](https://community.openhab.org)

**Enjoy!**
