# banglejs-2-widgets-on-background #

draws all loaded widgets of a Bangle.js 2 without clearing the background

By default, the Bangle.js 2 runtime clears the whole widget stripes on the top (or bottom) of its display, as soon as any widget has been loaded into that area. On displays with a structured background (such as a bitmap) this behaviour hides anything underneath these stripes.

For that reason, this module modifies the widget drawing method such that the background is not cleared - leaving it up to the widget to take care of that itself (which most widgets do).

## Usage ##

Just "require" this module before any widgets are drawn - that's all:

```
require('https://raw.githubusercontent.com/rozek/banglejs-2-widgets-on-background/main/drawWidgets.js');
```

## License ##

[MIT License](LICENSE.md)
