# Makefile Highlighting for IntelliJ products

This JAR will provide very basic Makefile syntax highlighting.

## Installation
Go to `File` > `Import Settings` and import `Makefile.jar`.

## Indenting with Tabs

Use the EditorConfig plugin and add this to your `.editorconfig` settings:

```ini
[{Makefile, makefile, GNUmakefile, *.mk, gmsl, __gmsl}]
indent_style = tab
indent_size = 4
```

-James Deucker 2017
