# Material Hush for the web

CSS custom properties, a Tailwind CSS v4 theme and design tokens. Part of [Material Hush](../../README.md).

## CSS

`material-hush.css` defines CSS custom properties such as `--hush-bg`, `--hush-fg`, `--hush-blue` and `--hush-muted`. It's light by default and switches to dark with `prefers-color-scheme` or `data-theme="dark"`.

```css
@import "material-hush.css";
body { background: var(--hush-bg); color: var(--hush-fg); }
```

## Tailwind CSS v4

Copy `tailwind.css` and `material-hush.css` to the same folder, then import `tailwind.css` after Tailwind to get utilities like `bg-hush-bg`, `text-hush-blue` and `border-hush-border`:

```css
@import "tailwindcss";
@import "./tailwind.css";
```

## Design tokens

`material-hush.tokens.json` uses the [W3C DTCG](https://www.designtokens.org/) format.
