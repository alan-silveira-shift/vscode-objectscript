[![Known Vulnerabilities](https://snyk.io/test/github/daimor/vscode-objectscript/badge.svg)](https://snyk.io/test/github/daimor/vscode-objectscript)

# vscode-objectscript

[InterSystems](http://www.intersystems.com/our-products/) ObjectScript language support for Visual Studio Code

## Features

- Initial InterSystems ObjectScript code highlighting support.
  ![example](images/screenshot.png)
- Export existing sources to the working directory: press Ctrl+Shift+P, type 'ObjectScript', press Enter.
- Save and compile a class: press Ctrl+F7 (⌘+F7) or select "ObjectScript: Save and compile" from Ctrl+Shift+P menu.
- Server Explorer with possibility to export items![ServerExplorer](images/explorer.png)

## Installation

Install [Visual Studio Code](https://code.visualstudio.com/) first.
Open VSCode. Go to extensions and search for "ObjectScript" like it is shown on the attached screenshot and install it.
Or install from ObjectScript extension page on [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=daimor.vscode-objectscript)

## Configure connection

To be able to use many plugin features, you need to configure the connection to Caché server first.

- Find a 'objectscript.conn' section in workspace settings (File - Preferences - Settings)
- Change settings according to your Caché instance and reload VSCode ( as temporary solution )
- You will see Caché-related output in "Output" while switched to "ObjectScript" channel (right drop-down menu on top of the output window)

## Notes

For Caché/IRIS instance with maximum security level, add '%Development' role for '/api/atelier/' web-application ( [More](https://community.intersystems.com/post/using-atelier-rest-api) )
