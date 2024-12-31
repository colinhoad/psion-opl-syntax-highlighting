# Change Log

All notable changes to the "psion-opl-syntax-highlighting" extension will be documented in this file.

## 0.0.3
- Fixes for:
    - Boolean operators (`AND`, `OR`, `NOT`) now recognised
    - Equivalence operators (`<>`,`<`,`>`,`<=`,`>=`) now recognised
    - Suffix operators (`#`, `$`) now recognised
    - All `PEEK` and `POKE` variant keywords now recognised
    - No longer treating `\` as an escape character inside a quoted string
    - Colon line separator no longer spoils syntax highlighting

## 0.0.2

- Fixes for:
    - Scientific notation floats now recognised as constants
    - Variables only identified if 8 characters or less
    - De-indentation after `ENDP`, `ENDIF`, `ENDWH` and `UNTIL`

## 0.0.1

- Initial release