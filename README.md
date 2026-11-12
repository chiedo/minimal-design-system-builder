# Minimal Design System Builder

One HTML file. Open it in a browser. No install.

A builder for a **color palette**, **type roles** (h1–h6, body, UI, caption, mono), **button sizes**, and the rest of a small UI system, with a live app preview. Inspired by the workflow in *Refactoring UI* — not a copy of the book files.

## Open it

1. Copy `index.html` anywhere.
2. Double-click it (Chrome, Edge, or Firefox).

## Palette

Every scale (primary, neutrals, accent, danger, warning, success) is yours to set: hue, saturation, lightness, 50/500/900 edges, optional hue rotation, and per-shade HSL overrides. Optional import of a `palette-XX.json` from the Refactoring UI Color Palettes ZIP (stays on your computer).

## Type

Display, UI, and mono families, plus a **role for each heading and text style**. Click H1–H6, body, UI, caption, or mono and set font, weight, size step, line height, tracking, and ink. The type specimen shows those roles as real headings.

## Buttons

Small / medium / large. Each size has its own type step, vertical padding, horizontal padding, and icon size. Padding is meant to tighten as type shrinks. Inputs share the selected control height. Hierarchy is separate: primary (solid), secondary (outline), tertiary (link), danger.

## Space

Spacing scale through the large layout sizes, a roundness control for boxes, borders, and the nav header, a separate button radius, five shadow elevations, border widths, focus ring, icon sizes, opacity tokens, and max-widths.

## Preview

- **App preview** — sidebar, headings, stats, form, table, dropdown, alerts, empty state, all three button sizes
- **Color board** — 10-shade ramps with hex and HSL
- **Type specimen** — every role, then a nested article
- **Components** — button matrix, matching inputs, badges, avatars, icons, shadows, opacity
- Dark preview toggle (also exported as `[data-theme="dark"]`)

## Export

Download `tokens.css` (or copy CSS / JSON). Paste the CSS at the top of your stylesheet.
