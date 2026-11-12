# Material Hush for Xresources

Dark and light colors for the [X resource database](https://gitlab.freedesktop.org/xorg/app/xrdb), read by xterm, URxvt and other X apps. Part of [Material Hush](../../README.md).

## Install

Copy `material-hush.Xresources` (or `material-hush-light.Xresources`) somewhere, add this line to `~/.Xresources`, then run `xrdb -merge ~/.Xresources`:

```c
#include "/path/to/material-hush.Xresources"
```
