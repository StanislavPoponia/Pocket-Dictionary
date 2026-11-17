# Design tokens — Pocket Dictionary

Source: Figma file `8gBHrnqIou1gzSUY6Ib3HC`, frame **UI Kit** (node `11727:98`).
https://www.figma.com/design/8gBHrnqIou1gzSUY6Ib3HC/Pocket-Dictionary?node-id=11727-98
Extracted: 2026-11-17. Re-read the frame if the design changes.

The Figma file has no local styles and only a few variables; the rest of the values below were read directly from the UI Kit layers.

## Colors

| Token | Hex | Where it is used |
|---|---|---|
| `primary` | `#E9672B` | Primary button fill, secondary button border |
| `accent-pink` | `#F6CFCA` | Language chip (EN / UA / CZ), soft accent |
| `background` | `#FEF9F9` | Page background (Figma variable «Фоновый») |
| `white` | `#FCFBFB` | Figma variable `white` |
| `white-pure` | `#FFFFFF` | Cards, search field, secondary button fill |
| `surface-1` | `#FBF8F5` | Neutral surface tone from the palette |
| `surface-2` | `#F3F0EC` | Neutral surface tone from the palette |
| `gray` | `#888888` | Secondary text (Figma variable «Cерый») |
| `black` | `#000000` | Text, outline swatch |
| `red` | `#F43F5E` | Error / destructive (Figma variable `red`) |
| `green` | `#00C3AD` | Success / check icon (Figma variable `green`) |

The UI Kit canvas itself is `#F0E5DA`. It is the presentation background of the kit, not a site color.

Palette swatches in the kit (left to right): `#E9672B`, `#FBF8F5`, `#000000`, white with black border, `#F6CFCA`, `#F3F0EC`.

## Shadows

| Token | Value |
|---|---|
| `shadow-default` | `3px 8px 14px 0 rgba(136, 198, 253, 0.19)` — Figma `#88C6FD30` |
| `shadow-hover` | `7px 13px 14px 0 rgba(116, 177, 232, 0.24)` — Figma `#74B1E83D` |

## Fonts

| Font | Weight | Role |
|---|---|---|
| Livvic | Bold | Logo |
| Convergence | Regular | Titles |
| Imprima | Regular | Body text, buttons |
| Marck Script | Regular | Stickers |

Manrope SemiBold (60px, letter-spacing 2.4px) is used only for the section labels inside the UI Kit frame, not for the site.

Text sizes seen in the kit: button label Imprima 18px / line-height 28px; language chip Imprima 16px / line-height 20px.

## Components

**Primary button** — 154×60, radius 30, fill `#E9672B`, label Imprima 18/28, black.
**Secondary button** — 154×60, radius 30, fill white, border 3px `#E9672B`, same label.
**Language chip** — 40×40 circle, fill `#F6CFCA`, label Imprima 16/20 (EN, UA, CZ).
**Search field** — 608×44, radius 20, fill white, `shadow-default`; icons `search` and `cross-small` (28×28) on the right.
**Input rows** — 458×48, text 24px high; trailing icons `cross-small`, `check`, `eye-closed` (24×24). Colors and radius not yet read.

## Assets

```
Photo/
  svg/
    icons/      UI icons (monochrome, black unless noted)
    social/     brand icons
    stickers/   vector stickers (empty)
  images/
    photos/       raster photos (empty)
    stickers/     raster stickers (empty)
    backgrounds/  background images (empty)
```

Icons available in `Photo/svg/icons/`: `check` (24px, `#00C3AD`), `cross-small`, `eye-closed`, `eye-open`, `menu-hamburger`, `search`, `trash-2` (all 28px).
Social: `Photo/svg/social/google.svg` (30px, full color).

### Still to export from the UI Kit

- Icons: `plus` (`11727:249`), `user-1` (`11727:261`), `edit-2` (`11727:263`), `linkedin` (`11747:385`).
- Stickers / illustrations: the `image NN` layers and the `Frame` groups in the lower part of the kit (including `reshot-icon-*` and `19-Winner`).
