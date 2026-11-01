# Mukto Dot

A dot-matrix typeface made for **Mukto Keyboard** by **Mobassher Ahmed Sowrov / JS Organization**.

Version 1.100 · © 2026 Mobassher Ahmed Sowrov, JS Organization

## Font files

| File | Family | Style | Typing a–z gives |
|---|---|---|---|
| `MuktoDot-Regular.ttf` | Mukto Dot | Regular | dotted capitals |
| `MuktoDot-Bold.ttf` | Mukto Dot | Bold | dotted capitals |
| `MuktoDotLight-Regular.ttf` | Mukto Dot Light | Regular | dotted capitals |
| `MuktoDotMixed-Regular.ttf` | Mukto Dot Mixed | Regular | mixed case |
| `MuktoDotMixed-Bold.ttf` | Mukto Dot Mixed | Bold | mixed case |
| `MuktoDotMixedLight-Regular.ttf` | Mukto Dot Mixed Light | Regular | mixed case |

## What's included

Latin (with accents), digits, Bangla digits, punctuation, currency signs, math symbols, arrows, and
decorative symbols such as ☞ ◑ ♥ ♡ ❤ ❥ ✔ ✓ ✗ ✘ ✖ ☑ ✪ ☆ ★ ✰ ⇨ ⇦ ⇧ ⇩ ➤ ✆ ✉ № © ® ™ ✿ ✦ ❀.

Symbols that Android treats as emoji (❤ ✔ ☑ ✉ ☞ © ® ™ ♥ …) also render in dot style when followed by
the emoji selector `U+FE0F` or the text selector `U+FE0E`.

## Usage in Android (Kotlin / Jetpack Compose)

Put the `.ttf` files in `res/font/` (lowercase names, e.g. `mukto_dot_regular.ttf`), then:

```kotlin
val MuktoDot = FontFamily(
    Font(R.font.mukto_dot_regular, FontWeight.Normal),
    Font(R.font.mukto_dot_bold, FontWeight.Bold)
)

Text("♥ ✔ ✉ ☞ © ™", fontFamily = MuktoDot)
```

## License

Licensed under **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International
(CC BY-NC-ND 4.0)** — <https://creativecommons.org/licenses/by-nc-nd/4.0/>

- **Attribution:** you must credit Mobassher Ahmed Sowrov / JS Organization.
- **NonCommercial:** the font may not be sold or redistributed for profit.
- **NoDerivatives:** the font may not be altered, transformed or built upon.

**Special Commercial Exception by JS Organization:** any software developer or app owner is officially
permitted to embed and bundle the unmodified "Mukto Dot" font within their own applications (including
commercial/monetized apps) free of charge, provided that appropriate credit is given to Mobassher Ahmed
Sowrov / JS Organization, and the font file itself is not sold standalone.

Suggested credit line:

> Font "Mukto Dot" by Mobassher Ahmed Sowrov / JS Organization, CC BY-NC-ND 4.0.

See `LICENSE.txt` for the full text.

## Changelog

- **1.100** — Added emoji-selector (`FE0E`/`FE0F`) support so symbols stay in dot style on Android;
  license changed to CC BY-NC-ND 4.0 with a commercial app-embedding exception; full font names now
  include the style (e.g. "Mukto Dot Regular").
- **1.000** — First release.
