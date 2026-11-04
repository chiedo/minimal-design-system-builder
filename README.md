# Design System Studio

One HTML file. Open it in a browser. No install.

It is a small studio for building a **color palette** and a **type system**, with a live preview of an app screen, components, and a type specimen. Inspired by the workflow in *Refactoring UI* (fixed shade ramps, tinted neutrals, a short type scale) — not a copy of the book files.

## Open it

1. Copy `index.html` anywhere.
2. Double-click it (Chrome, Edge, or Firefox).

## Palette

Every scale (primary, neutrals, accent, danger, warning, success) is **yours to set**:

- Hue (0–360), not a preset personality
- Base saturation and lightness for shade **500** (the button color)
- Lightest (**50**) and darkest (**900**)
- Hue rotation and end-saturation so light/dark shades stay vivid
- Click any swatch to override that shade’s HSL
- Optional: tint neutrals with the primary hue
- Optional: import a `palette-XX.json` from the Refactoring UI Color Palettes ZIP (stays on your computer)

The generator fills the eight shades between 50, 500, and 900. Moving hue / sat / lightness rebuilds the ramp.

## Type

Pick a display face, a UI/body face, and a mono face (Google Fonts, loaded in the browser). Choose a short size scale, base size, weights, and headline tracking.

## Preview

- **App preview** — nav, stats, form card, semantic alerts
- **Color board** — all 10-shade ramps with hex and HSL
- **Type specimen** — the scale in the chosen faces
- **Components** — buttons, form, alerts
- Dark preview toggle

## Export

Download `tokens.css` (or copy CSS / JSON from the Export tab) and paste it at the top of your stylesheet.
