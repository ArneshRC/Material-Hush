# Material Hush for foot

Dark and light themes for [foot](https://codeberg.org/dnkl/foot). Part of [Material Hush](../../README.md).

## Install

Requires foot 1.26 or later. Copy `material-hush.ini` to `~/.config/foot/`, then add this line at the top of `foot.ini`, before any `[section]` header:

```ini
include=~/.config/foot/material-hush.ini
```

To switch between modes, include both files. The theme in the last `include` loads at startup, and foot's `color-theme-toggle` key binding switches to the other.
