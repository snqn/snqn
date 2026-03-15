#  Sine qua non v0.3.0

snqn is an opinionated high contrast dark theme. It consists of 26 colors and multiple themes/ports that I (and hopefully soon, the community) created.

## Philosophy

I'll be blunt:

- This colorscheme and it's ports are *my* preferences, and I won’t compromise on its core style. **But!** You’re absolutely welcome to contribute:
  - Found a bug or inconsistency in my ports? Open a GitHub issue or submit a pull request!
  - Want to add your own port? Go for it! I’d love to see it!

And so; in my own opinion, the core rules should be:
- **Stay high-contrast and dark.** (Though *maybe* I'll cave and add a light mode <img src="https://user-images.githubusercontent.com/49000471/258223152-6c644f95-2fd7-4db3-b266-b387a95f150c.png" height="16px" width="16px"> <sub>just maybe...</sub>)
- **Stick to the palette below.**
  - If a theme *requires* flexibility (e.g., more colors), use Alpha values (with RGBA) instead.
- Ports / Themes should contain **NO ROUNDED CORNERS!**

### Versioning

I bump the version once I change a color of the Palette below.

```
v0.3.0
 ╰─┼─┼─ Release Version / When I feel like I've perfected it (perhaps in 10+ years)
   ╰─┼─ Major Version / After the palette has changed enough (when I update all of my [ports](#ports))
     ╰─ Minor Version / Very small updates to the palette
```

## Palette

| Color                                                                 | Base     | HEX       | RGB                   | OLKCH                        |
| :---:                                                                 | :---     | :---      | :---                  | :---                         |
| ![#07060B](https://img.shields.io/badge/_-07060B?style=for-the-badge) | `base00` | `#07060B` |  `rgb(7, 6, 11)`      | `oklch(0.127 0.013 295.088)` |
| ![#1C1B28](https://img.shields.io/badge/_-1C1B28?style=for-the-badge) | `base01` | `#1C1B28` |  `rgb(28, 27, 40)`    | `oklch(0.229 0.025 287.781)` |
| ![#323246](https://img.shields.io/badge/_-323246?style=for-the-badge) | `base02` | `#323246` |  `rgb(50, 50, 70)`    | `oklch(0.326 0.035 284.274)` |
| ![#4C4B69](https://img.shields.io/badge/_-4C4B69?style=for-the-badge) | `base03` | `#4C4B69` |  `rgb(76, 75, 105)`   | `oklch(0.426 0.049 285.627)` |
| ![#72708E](https://img.shields.io/badge/_-72708E?style=for-the-badge) | `base04` | `#72708E` |  `rgb(114, 112, 142)` | `oklch(0.558 0.046 287.857)` |
| ![#BFBDCA](https://img.shields.io/badge/_-BFBDCA?style=for-the-badge) | `base05` | `#BFBDCA` |  `rgb(191, 189, 202)` | `oklch(0.804 0.018 293.054)` |
| ![#EBE9F1](https://img.shields.io/badge/_-EBE9F1?style=for-the-badge) | `base06` | `#EBE9F1` |  `rgb(235, 233, 241)` | `oklch(0.938 0.011 297.619)` |
| ![#F5F3FA](https://img.shields.io/badge/_-F5F3FA?style=for-the-badge) | `base07` | `#F5F3FA` |  `rgb(245, 243, 250)` | `oklch(0.968 0.01 299.241)`  |
| ![#FE587C](https://img.shields.io/badge/_-FE587C?style=for-the-badge) | `base08` | `#FE587C` |  `rgb(254, 88, 124)`  | `oklch(0.691 0.202 11.193)`  |
| ![#FF837C](https://img.shields.io/badge/_-FF837C?style=for-the-badge) | `base09` | `#FF837C` |  `rgb(255, 131, 124)` | `oklch(0.748 0.152 24.703)`  |
| ![#FCE66F](https://img.shields.io/badge/_-FCE66F?style=for-the-badge) | `base0A` | `#FCE66F` |  `rgb(252, 230, 111)` | `oklch(0.92 0.141 98.982)`   |
| ![#62FF90](https://img.shields.io/badge/_-62FF90?style=for-the-badge) | `base0B` | `#62FF90` |  `rgb(98, 255, 144)`  | `oklch(0.891 0.201 149.92)`  |
| ![#58E7E2](https://img.shields.io/badge/_-58E7E2?style=for-the-badge) | `base0C` | `#58E7E2` |  `rgb(88, 231, 226)`  | `oklch(0.85 0.122 191.837)`  |
| ![#7285FE](https://img.shields.io/badge/_-7285FE?style=for-the-badge) | `base0D` | `#7285FE` |  `rgb(114, 133, 254)` | `oklch(0.661 0.179 273.773)` |
| ![#8C6BFF](https://img.shields.io/badge/_-8C6BFF?style=for-the-badge) | `base0E` | `#8C6BFF` |  `rgb(140, 107, 255)` | `oklch(0.635 0.21 289.279)`  |
| ![#B967FF](https://img.shields.io/badge/_-B967FF?style=for-the-badge) | `base0F` | `#B967FF` |  `rgb(185, 103, 255)` | `oklch(0.674 0.221 306.199)` |


## Naming Convention

Use either `Sine qua non` or `snqn` where it makes sense. There's really not much more to it.

## Showcase

TODO: add example images

## Ports

Contributions welcome! Here's what exists so far:

| Application / Tool | Repository | status |
| --- | --- | --- |
| [base16](https://github.com/chriskempson/base16) | [snqn/base16](https://github.com/snqn/base16) | in progress |
<!-- | [GTK](https://www.gtk.org/) | [74k1/yueye.gtk](https://github.com/74k1/yueye.gtk) | in progress | -->
<!-- | [Kagi Search](https://kagi.com/) | [74k1/yueye.kagi.css](https://github.com/74k1/yueye.kagi.css) | in progress | -->
<!-- | [Nix](https://nixos.org/) | [74k1/yueye.nix](https://github.com/74k1/yueye.nix) | in progress | -->

## Contributing

see [contributing](CONTRIBUTING.md) guide.

<!-- #FE587C -->
<!-- #4DE7C9 -->
<!-- #FCE66F -->
<!-- #62FF90 -->
<!-- #58E7E2 -->
<!-- #7285FE -->
<!-- #8C6BFF -->
<!-- #B967FF -->
