# Material Hush for Alacritty

Dark and light themes for [Alacritty](https://github.com/alacritty/alacritty). Part of [Material Hush](../../README.md).

## Install

Copy `material-hush.toml` (or `material-hush-light.toml`) to `~/.config/alacritty/`, then add this to `alacritty.toml`:

```toml
[general]
import = ["~/.config/alacritty/material-hush.toml"]
```

This needs Alacritty 0.14 or later. On 0.13, put `import` at the top level instead of under `[general]`.
