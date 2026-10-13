<p>
  <img src="svg/gnimu-icon-default-rounded.svg" alt="Gnimu icon" height="72">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="wordmark/gnimu-wordmark-transparent-white.svg">
    <img src="wordmark/gnimu-wordmark-transparent-navy.svg" alt="gnimu" height="72">
  </picture>
</p>

# Gnimu branding

The icon, wordmark and social card for the [Gnimu](https://github.com/c20d-us/Gnimu) projects. This repository is the single source for these files. The other Gnimu repositories and [gnimu.us](https://gnimu.us) reference or copy them from here.

## Layout

```
svg/         The icon as SVG: default, dark, light and tinted, each square and rounded,
             plus the mark on a transparent background
png/         The icon as 1024px PNG: default, dark, light and tinted
wordmark/    The "gnimu" wordmark as SVG and PNG, in navy and white
social/      The 1200x630 social card
```

## Which file to use

| Use | File |
|---|---|
| README header icon | `svg/gnimu-icon-default-rounded.svg` |
| Wordmark on a light background | `wordmark/gnimu-wordmark-transparent-navy.svg` |
| Wordmark on a dark background | `wordmark/gnimu-wordmark-transparent-white.svg` |
| Mark on a dark background, no tile | `svg/gnimu-mark-dark-transparent.svg` |
| App icon source | `png/gnimu-icon-default-1024.png` |
| Link previews | `social/gnimu-social-card.png` |

## Colours

| Name | Hex |
|---|---|
| Navy | `#0B1E38` |
| Blue | `#4DA3FF` |
| Yellow | `#FFD23F` |
| Red | `#FF3B30` |
| Grey | `#C3CEDD` |
| Off-white | `#F4F6F8` |
| Cream | `#FAF7F0` |

## Using the files in another README

Reference them by absolute URL, since relative paths cannot cross repositories:

```html
<p>
  <img src="https://raw.githubusercontent.com/c20d-us/Gnimu-branding/main/svg/gnimu-icon-default-rounded.svg" alt="Gnimu icon" height="72">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/c20d-us/Gnimu-branding/main/wordmark/gnimu-wordmark-transparent-white.svg">
    <img src="https://raw.githubusercontent.com/c20d-us/Gnimu-branding/main/wordmark/gnimu-wordmark-transparent-navy.svg" alt="gnimu" height="72">
  </picture>
</p>
```

Renaming or moving a file here breaks every README that links to it, so keep the paths stable.

## Licence

These files are not open source. You may use them unmodified to refer to the Gnimu projects; see the [usage policy](LICENSE.md) for what is and is not allowed.

## Silkscreen logos

The silkscreen versions of the logo live with the board designs in [Gnimu-PCB](https://github.com/c20d-us/Gnimu-PCB/tree/main/silkscreen-logos).
