# lowlysre.github.io

Brand assets for the [lowlysre](https://github.com/lowlysre) org — home of the lowly inchworm. 🐛

**Live gallery:** <https://lowlysre.github.io>

## Assets

| Variant | SVG | PNG sizes |
|---|---|---|
| Logo · light (wordmark) | [`logo-light.svg`](assets/svg/logo-light.svg) | 16–1024 |
| Logo · dark (wordmark) | [`logo-dark.svg`](assets/svg/logo-dark.svg) | 16–1024 |
| Icon · light | [`icon-light.svg`](assets/svg/icon-light.svg) | 16–1024 |
| Icon · dark | [`icon-dark.svg`](assets/svg/icon-dark.svg) | 16–1024 |
| Mark · transparent | [`mark-green.svg`](assets/svg/mark-green.svg) | 16–1024 |

PNGs live in [`assets/png/`](assets/png/) as `{variant}-{size}.png` for sizes 16, 32, 64, 128, 256, 512, 1024. A multi-resolution [`favicon.ico`](favicon.ico) is also included.

## Theme-aware usage in Markdown

```html
<picture>
  <source srcset="https://lowlysre.github.io/assets/svg/logo-dark.svg" media="(prefers-color-scheme: dark)">
  <img src="https://lowlysre.github.io/assets/svg/logo-light.svg" alt="lowlysre" width="160">
</picture>
```

## Colors

| | Light | Dark |
|---|---|---|
| Worm | `#2da44e` | `#3fb950` |
| Background | `#fdf6e3` | `#0d1117` |
| Text | `#57606a` | `#8b949e` |
