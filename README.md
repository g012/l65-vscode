# Visual Studio Code extension for l65

## Features

Currently support syntax highlighting.

## Classes

These classes are defined and should be set in settings.json:

 * entity.name.type.l65
 * keyword.operator.l65
 * keyword.control.l65
 * constant.numeric.l65
 * punctuation.separator.label.l65
 * entity.name.label.l65
 * punctuation.separator.label.l65.local
 * entity.name.label.l65.local
 * punctuation.separator.section.l65
 * entity.name.section.l65
 * meta.preprocessor.l65


Also added missing labels from standard Lua:

 * punctuation.separator.label.lua
 * entity.name.label.lua

## Example

Here's my tokenColorCustomizations section:
```json
    "editor.tokenColorCustomizations": {
        "textMateRules": [
            {
                "scope": [
                    "punctuation.separator.label",
                ],
                "settings": {
                    "foreground": "#3090a0",
                },
            },
            {
                "scope": [
                    "entity.name.label",
                ],
                "settings": {
                    "foreground": "#5fafd7",
                },
            },
            {
                "scope": [
                    "punctuation.separator.label.l65",
                ],
                "settings": {
                    "foreground": "#907090",
                },
            },
            {
                "scope": [
                    "entity.name.label.l65",
                ],
                "settings": {
                    "foreground": "#af87af",
                },
            },
            {
                "scope": [
                    "punctuation.separator.label.l65.local",
                ],
                "settings": {
                    "foreground": "#805080",
                },
            },
            {
                "scope": [
                    "entity.name.label.l65.local",
                ],
                "settings": {
                    "foreground": "#af74af",
                },
            },
            {
                "scope": [
                    "punctuation.separator.section.l65",
                ],
                "settings": {
                    "foreground": "#7070B0",
                },
            },
            {
                "scope": [
                    "entity.name.section.l65",
                ],
                "settings": {
                    "foreground": "#9090E0",
                },
            },
            {
                "scope": [
                    "entity.name.type.l65",
                ],
                "settings": {
                    "foreground": "#5fafaf",
                },
            },
            {
                "scope": [
                    "meta.preprocessor.l65",
                ],
                "settings": {
                    "foreground": "#5faf87",
                },
            },
            {
                "scope": [
                    "keyword.operator.l65",
                ],
                "settings": {
                    "foreground": "#3f80af",
                },
            },
            {
                "scope": [
                    "support.variable.lua",
                ],
                "settings": {
                    "foreground": "#8faf5f",
                },
            },
        ],
    },
```