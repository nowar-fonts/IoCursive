# IoCursive: the “upright italic” variant of [Iosevka](https://github.com/be5invis/Iosevka)

This project is part of [Nowar DIN and Nowar DIN Cursive](https://github.com/nowar-fonts/Nowar-DIN), DIN-inspired font packs for World of Warcraft.

## Pre-built packages

This project comes with several pre-built packages:
* IoCursive Sans Type/Term/Fixed
* IoCursive Slab (Proportional)/Type/Term/Fixed

| IoCursive spacing | Iosevka spacing |
| ----------------- | --------------- |
| (Proportional)    | Etoile          |
| Type              | (Default)       |
| Term              | Term            |
| Fixed             | Fixed           |

## Customized build

Almost same as [Iosevka](https://github.com/be5invis/Iosevka#customized-build).

As a apart of Nowar DIN and Nowar DIN Cursive, IoCursive is expected to produce both “upright roman” and “upright italic” in one build process. Thus it does not override the `upright` slope variant. Instead, an extra slope variant, `cursive`, is introduced, with `isItalic = true` and `slopeAngle = 0`.

Note that `cursive` shares the same slope subfamily name with `upright`. You can not install both.
