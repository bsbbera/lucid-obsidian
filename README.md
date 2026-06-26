<div align="center">

# ◇ Lucid

### A webpage for every note.

*An Apple-style frosted-glass Obsidian theme — translucent cards with real backdrop blur, a calm **blue** accent with **teal** italics, an **Apple-style gradient text**, and crisp **Segoe UI** throughout. Dark-first, with a bright light variant.*

![version](https://img.shields.io/badge/version-2.0.0-3d8fe6?style=flat-square)
![obsidian](https://img.shields.io/badge/Obsidian-1.5.0%2B-4ecdc4?style=flat-square)
![style settings](https://img.shields.io/badge/Style_Settings-ready-6aa9ef?style=flat-square)
![license](https://img.shields.io/badge/license-MIT-9bb4cf?style=flat-square)

![Lucid theme screenshot](screenshot.png)

</div>

---

> **What it is.** Lucid turns plain Markdown into something that reads like a product page — hero banners, frosted cards, gradient text, infoboxes, multi-column layouts and 47 semantic callout casts — all from ordinary Obsidian callouts. One blue accent, two glass modes, zero plugins required for the look.

## ✦ Two modes

| | |
|---|---|
| **Light** | Bright off-white, deep ink text, blue rules. Daylight reading. |
| **Dark** *(default)* | Calm `#0d0f14` glass with violet/teal glow, frosted translucent cards. The signature mode. |

Switch with Obsidian's normal light/dark toggle — the whole palette pivots on one set of `--mwg-*` tokens, so a single accent picker recolours everything.

## ✦ New in 2.0 — the `dark` switch & `grid` banner

- **`dark` now inverts the page.** Add `dark` to *any* card or callout and its panel flips against the current mode — a deep slab in light mode, a bright one in dark mode. No `dark` = it simply follows the theme. One keyword, every element.
- **`grid` is its own keyword.** A blueprint-grid banner overlay that honours the light/dark switch. `[!card|hero grid]` paints the grid on the page-mode panel; add `dark` to drop it on the inverted one.

```md
> [!card|hero grid spanfull]
> ###### FOUR STEPS · ANY SKILL LEVEL
> # From zero to *merged*, in an afternoon.
> Blueprint grid that tracks your light/dark mode.

> [!card|profile dark]
> ###### INVERTED
> ### Opposes the theme
```

## ✦ What you get

- **A card system** — `hero · skill · section · step · profile · honor · channels`, composed in `> [!grid|colsN]`, reflowing on resize, distributable by `w1…w10` ratio.
- **The `dark` / `grid` modifiers** — invert any panel against the page, or drop a blueprint-grid banner that follows the mode.
- **47 semantic casts** — stamps, flags, tablets and tags for every callout type, each honouring the dark switch.
- **Editorial elements** — frosted infoboxes that float and wrap text, multi-column notes, code blocks, illuminated quotes, ornamented dividers.
- **Inline typography** — `at-kicker · at-lead · at-display · at-stat · at-mark · at-badge`, plus **`at-gradient`** Apple-style gradient text with a per-use ramp.
- **Style Settings** — accent & colours, italic/emphasis colour, font dropdowns, width, roundness, per-element default styles, the gradient ramp, glass blur, and animations.

> **Companion theme:** [Atelier](https://github.com/bsbbera/atelier-obsidian) shares the *same* card / column / cast / utility syntax — including the `dark` switch and `grid` banner. A note authored for one renders with identical layout in the other; only the skin (warm paper + copper + serif) changes.

## ✦ Install

**From Obsidian** *(once published)* — Settings → Appearance → Themes → **Manage** → search **Lucid**.

**Manually** — copy `manifest.json` + `theme.css` into `<vault>/.obsidian/themes/Lucid/`, then select **Lucid** under Settings → Appearance.

> Requires Obsidian **1.5.0+**. Install the **Style Settings** plugin to customise everything. Lucid's defaults use **system fonts (Segoe UI)**, so it works offline out of the box.

## ✦ Sixty-second start

```md
> [!grid|cols3]
>
> > [!card] First
> > A frosted-glass card. Add as many as you like; the grid wraps them into rows.
>
> > [!card] Second
> > Resize the pane — columns reflow like a web page.
>
> > [!card|dark] Third
> > Add `dark` and this one inverts against the page.

> [!note] Note
> A standard callout, themed with a mono small-caps title.
```

That's three of Lucid's elements. There are dozens more.

## ✦ The demo note

Paste **[EXAMPLES.md](EXAMPLES.md)** into a note (reading view, Lucid selected) to exercise every feature — cards, `wN` ratios, named step icons, the `dark`/`grid` modifiers, infobox, multi-column, code blocks, casts.

## ✦ Customising

**Settings → Style Settings → Lucid** — accent & colours, italic/emphasis colour, font dropdowns, note width, roundness, default card style, card glass blur, gradient ramp (4 stops + angle), body size, and animations.

## ✦ Credits

- Aesthetic: Apple-style frosted glass & product-page editorial.
- Fonts: **Segoe UI** (system); **JetBrains Mono** for code.
- License: **[MIT](LICENSE)**.

<div align="center"><sub>Built for Obsidian · <code>--mwg-*</code> token system · made by <a href="https://github.com/bsbbera">Subhadip</a></sub></div>
