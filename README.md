# psion-opl

Syntax highlighting for the Open Psion Language (OPL) used by Psion portable computers.

## Features

Provides keyword syntax highlighting, including distinguishing between control keywords (e.g. `PROC`/`ENDP`, `IF`/`ELSE`/`ENDIF` etc.) and other keywords (e.g. `PRINT`, `INPUT` etc.), as well as recognising `REM` comments and legitimate variable names.

\!\[Example\]\(img/psion-opl-sample.png\)

## Requirements

This has been written for use with VS Code.

## Installation

You can add this extension to VS Code manually by using the vsix file. From the command line:

`code --install-extension psion-opl-0.0.1.vsix`

## Known Issues

Please get in touch if you notice anything strange and/or highlighting that doesn't look right. This is a stepping stone towards a fully fledged LSP for OPL, so all constructive feedback gratefully received.

## Release Notes

### 0.0.1

Initial release.