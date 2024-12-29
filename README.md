# psion-opl

Syntax highlighting for the Open Psion Language (OPL) used by Psion portable computers.

## Features

Provides keyword syntax highlighting, including distinguishing between control keywords (e.g. `PROC`/`ENDP`, `IF`/`ELSE`/`ENDIF` etc.) and other keywords (e.g. `PRINT`, `INPUT` etc.), as well as recognising `REM` comments and legitimate variable names.

![Screenshot](https://github.com/colinhoad/psion-opl-syntax-highlighting/blob/main/img/psion-opl-sample.png?raw=true)

## Requirements

This has been written for use with VS Code. If, after working on OPL source code files in VS Code, you wish to transfer said files to your Psion device (physically or via emulation), ensure that the files are saved using DOS CP437 encoding and that line breaks are set to CRLF. This can be controlled within VS Code at the bottom right of the screen: 

![File encoding](https://github.com/colinhoad/psion-opl-syntax-highlighting/blob/main/img/vscode-encoding.png?raw=true)

Or, via `Preferences` > `Settings` > `Text Editor` > `Files`

![File encoding](https://github.com/colinhoad/psion-opl-syntax-highlighting/blob/main/img/vscode-file-settings.png?raw=true)

If you need to change encoding or line breaks for files you have already created, ensure you use the Save As option after changing the encoding and/or line break settings so that VS Code overwrites the existing file with the correct encoding.

## Installation

You can add this extension to VS Code manually by creating a package and then using the generated vsix file to install. 

From the command line:

`vsce package`

This creates the `psion-opl-0.0.1.vsix` file. You can then install it into VS Code as follows:

`code --install-extension psion-opl-0.0.1.vsix`

## Known Issues

Please get in touch if you notice anything strange and/or highlighting that doesn't look right. This is a stepping stone towards a fully fledged LSP for OPL, so all constructive feedback gratefully received.

## Release Notes

### 0.0.1

Initial release.