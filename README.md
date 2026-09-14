# Syntopica brand kit

The Syntopica mark pairs converging lines in two separated halves, black on the left and terracotta on the right, with a lowercase serif name. This repository contains ready-to-use assets; no build step is needed.

Open [preview.html](preview.html) locally to browse the kit, or see [preview.png](preview.png) for an overview. [LEEME.md](LEEME.md) is the original Spanish version of the kit documentation.

## Choose an asset

| Use | File or folder |
| --- | --- |
| Header on a light background | [Horizontal color SVG](logos/svg/syntopica-horizontal-color.svg) |
| Header on a dark background | [Horizontal inverse SVG](logos/svg/syntopica-horizontal-inverse.svg): white left half and name, terracotta right half |
| Scalable artwork or a different layout | [logos/svg/](logos/svg/): horizontal, stacked, wordmark and symbol; `-black`, `-white` and `-terracotta` for one color |
| Raster artwork with transparency | [logos/png/transparent/](logos/png/transparent/) |
| Logo with a built-in background | [logos/backgrounds/](logos/backgrounds/) |
| App icon | [icons/square/](icons/square/) for platforms that apply a mask; [rounded](icons/rounded/) or [transparent](icons/transparent/) variants otherwise |
| Browser tab | [favicons/favicon.svg](favicons/favicon.svg) adapts to the browser theme; [favicon.ico](favicons/favicon.ico) has an ivory background |
| Desktop app | [desktop/macos/](desktop/macos/) for ICNS; [desktop/windows/](desktop/windows/) for ICO |
| Web integration | [web-ready/README.md](web-ready/README.md): logos, favicons, touch icons and a sample manifest |

The color and inverse logos are transparent. Preserve proportions and leave space around the mark. SVG lettering is outlined and needs no font installation. Use the supplied small favicons rather than shrinking the full symbol. Assets are RGB for screens; print separations are not included.

## Palette

| Color | Hex |
| --- | --- |
| Ink (logo black) | `#252525` |
| Terracotta | `#AB6647` |
| White | `#FFFFFF` |
| Ivory | `#FAF8F4` |
| Fog | `#E8E5E0` |
| Sand | `#DDD4C8` |
| Charcoal | `#292929` |
| Black (background) | `#0C0C0C` |

Use [palette.css](palette.css) for CSS variables or [palette.json](palette.json) for color values. [assets.json](assets.json) lists graphic files, dimensions and SHA-256 hashes.
