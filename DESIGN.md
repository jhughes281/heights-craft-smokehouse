---
name: Heights Craft Smokehouse
colors:
  surface: '#161311'
  surface-dim: '#161311'
  surface-bright: '#3c3836'
  surface-container-lowest: '#100e0c'
  surface-container-low: '#1e1b19'
  surface-container: '#221f1d'
  surface-container-high: '#2d2927'
  surface-container-highest: '#383432'
  on-surface: '#e9e1dd'
  on-surface-variant: '#d5c4af'
  inverse-surface: '#e9e1dd'
  inverse-on-surface: '#33302d'
  outline: '#9d8f7b'
  outline-variant: '#504535'
  surface-tint: '#fdba45'
  primary: '#fdba45'
  on-primary: '#432c00'
  primary-container: '#d99b26'
  on-primary-container: '#523700'
  inverse-primary: '#7f5700'
  secondary: '#ffb694'
  on-secondary: '#571f00'
  secondary-container: '#b14700'
  on-secondary-container: '#ffe2d6'
  tertiary: '#cdc5c0'
  on-tertiary: '#34302c'
  tertiary-container: '#ada5a0'
  on-tertiary-container: '#403b38'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdeae'
  primary-fixed-dim: '#fdba45'
  on-primary-fixed: '#281900'
  on-primary-fixed-variant: '#604100'
  secondary-fixed: '#ffdbcc'
  secondary-fixed-dim: '#ffb694'
  on-secondary-fixed: '#351000'
  on-secondary-fixed-variant: '#7b2f00'
  tertiary-fixed: '#eae1dc'
  tertiary-fixed-dim: '#cdc5c0'
  on-tertiary-fixed: '#1f1b18'
  on-tertiary-fixed-variant: '#4b4642'
  background: '#161311'
  on-background: '#e9e1dd'
  surface-variant: '#383432'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-xl:
    fontFamily: EB Garamond
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 48px
    letterSpacing: -0.015em
  headline-xl-mobile:
    fontFamily: EB Garamond
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-md:
    fontFamily: EB Garamond
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: EB Garamond
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Manrope
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.06em
  label-md:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-sm:
    fontFamily: Manrope
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system captures the sensory environment of an artisanal Texas smokehouse: glowing embers, slow-cured wood smoke, cast iron, and parchment-wrapped prime briskets. It balances the heritage of traditional live-fire cooking with the restrained refinement of a Michelin-starred tasting room.

The aesthetic blends rustic-tactile hospitality with high-end editorial minimalism. Deep charred-wood tones ground the canvas, layered with luminous molasses gold accents and subtle warm amber undertones. Surfaces do not feel synthetic or sterile; they convey atmospheric depth, quiet craftsmanship, and deliberate restraint. Typography pairs an authoritative, literary classical serif with a modern, calibrated geometric sans to deliver clear legibility alongside culinary distinction.

## Colors

The palette draws directly from the fire pit and the barrel room:
- **Primary (`#D99B26` - Molasses Gold):** Used for focal brand statements, active state outlines, elevated badge surfaces, and primary interactive moments. Refined, warm, and distinctly culinary.
- **Secondary (`#E06927` - Glowing Ember Smoke):** A vivid flame accent reserved for alert highlights, live availability indicators, and subtle temperature gradients.
- **Tertiary (`#231F1C` - Charred Oak Surface):** Elevated container surfaces, card layers, and contextual navigation panels that rest above the main canvas.
- **Neutral (`#191614` - Pit Charcoal Base):** The primary canvas background, creating an intimate, dimly lit dining room atmosphere.

### Functional Roles
- **Canvas Base:** `#191614`
- **Surface Elevation 1:** `#231F1C`
- **Surface Elevation 2:** `#2D2824`
- **Border / Divider:** `rgba(217, 155, 38, 0.18)` on neutral dark surfaces; `rgba(255, 255, 255, 0.08)` for structural splits.
- **Text High-Contrast:** `#FBF8F4` (Parchment Cream)
- **Text Muted / Secondary:** `#BDB2A7` (Ash Ochre)
- **Interactive Accents:** Molasses gold `#D99B26` with hover states stepping down into `#C4871B`.

## Typography

The editorial identity pairs the classical stature of EB Garamond with the calculated structural precision of Manrope.

- **EB Garamond** anchors all editorial headlining, dish titles, section prologues, and quote blocks. Its historic, literary cadence echoes bespoke leather-bound reserve lists and handcrafted woodcut signage.
- **Manrope** powers digital utility: pricing specs, reservation flows, table configurations, ingredients, and form controls. Its open counters and clean geometry ensure clarity across dark, dense backgrounds.
- All labels, badges, and status counters enforce uppercase tracking (`0.06em` to `0.1em`) to create an authoritative, curated appearance reminiscent of print menus.

## Layout & Spacing

The layout adopts an editorial column architecture with generous breathing room. Negative space is treated as a luxury asset, mirroring the deliberate pacing of a seated multi-course smokehouse tasting.

- **Desktop (1024px+):** 12-column grid, `margin: 3rem`, `gutter: 1.5rem`. Max container bound of `1320px` to maintain comfortable line-lengths for long-form tasting notes.
- **Tablet (768px - 1023px):** 8-column grid, `margin: 2rem`, `gutter: 1.25rem`. Two-column tasting cards reflow gracefully into full-width menu blocks.
- **Mobile (<768px):** 4-column grid, `margin: 1.25rem`, `gutter: 1rem`. Multi-column metadata (cuts, wood type, resting time) collapses into horizontal scroll ribbons or stacked key-value rows.
- Component internal padding strictly follows the 4px base modular scale, prioritizing `space-md` (`1rem`) and `space-lg` (`1.5rem`) to maintain an airy, unhurried density.

## Elevation & Depth

Depth is established through physical tonal stacking and ember-tinted ambient glows, rather than artificial drop shadows:

- **Tier 0 (Canvas):** Pure charred-pit tone (`#191614`).
- **Tier 1 (Cards, Menus, Modals):** Charred oak container tone (`#231F1C`) framed with a subtle 1px border of `rgba(217, 155, 38, 0.12)`.
- **Tier 2 (Floating Pickers, Context Menus):** Warm cast-iron tone (`#2D2824`) with an ambient shadow: `0 12px 32px -4px rgba(10, 8, 7, 0.75), 0 0 1px 1px rgba(217, 155, 38, 0.2)`.
- **Luminosity and Glows:** High-priority items (such as exclusive cut drops or sold-out warnings) use soft inner halos: `0 0 24px -6px rgba(224, 105, 39, 0.25)`.
- **Divider Treatment:** Fine hairline rules (`1px`) in muted bronze (`rgba(217, 155, 38, 0.15)`) separate courses and spec sheets without breaking vertical flow.

## Shapes

The geometric framework favors architectural discipline over overt softness. A base roundedness value of `1` (0.25rem / 4px) is applied across cards, inputs, and buttons. 

- This micro-radius removes harsh digital sharpness while maintaining the tailored lines of architectural ironwork and hand-cut butcher paper.
- Container elements (`rounded-lg`, 0.5rem / 8px) provide gentle separation for nested trays, modals, and sticky drawer components.
- Pill or circular forms are strictly avoided, reserved exclusively for circular imagery crops (portraits of pitmasters) and numeric item count badges.

## Components

### Buttons
- **Primary Action (Reserve Cut / Table Booking):** Solid Molasses Gold background (`#D99B26`), Neutral Dark text (`#191614`), font `Manrope`, weight 600, letter spacing `0.05em`, text transform uppercase. Height `48px`, padding `0 24px`, radius `4px`. Hover state: deepens to `#C4871B`.
- **Secondary Action (View Pit Schedule):** Transparent background, 1px border in `rgba(217, 155, 38, 0.35)`, text Parchment Cream (`#FBF8F4`). Hover: background shifts to `rgba(217, 155, 38, 0.08)` with border brightening to `#D99B26`.
- **Ghost Action:** Text only in Molasses Gold with a trailing gold hairline underline that expands on hover.

### Chips & Badges
- **Tasting / Cut Tags:** Container `#2D2824`, 1px border in `rgba(255, 255, 255, 0.08)`, text Ash Ochre (`#BDB2A7`), `label-sm` uppercase.
- **Limited Availability Badge:** Background `rgba(224, 105, 39, 0.15)`, text `#E06927`, 1px border in `rgba(224, 105, 39, 0.35)`. Displays a `6px` pulsing amber disc indicator.

### Menu Lists & Spec Tables
- Dish items feature the title in `headline-md` (EB Garamond), followed by an inline dotted or hairline rule extending across the row to the right-aligned price in `label-lg` (Manrope, Molasses Gold).
- Accompaniments, cut profiles, and wood-smoke species sit beneath in `body-sm` (Ash Ochre) with `0.25rem` top margin.

### Checkboxes & Radio Buttons
- Base container: `18px x 18px`, radius `3px`, background `#191614`, border `1px solid rgba(217, 155, 38, 0.3)`.
- Selected state: Background `#D99B26`, border `#D99B26`, with a high-contrast dark iron checkmark `#191614`.

### Input Fields
- Background `#1D1A17`, 1px border in `rgba(255, 255, 255, 0.12)`, radius `4px`, height `48px`, text `#FBF8F4`, font `Manrope` 14px.
- Focus state: Border transitions to `#D99B26` with an ember glow shadow `0 0 0 3px rgba(217, 155, 38, 0.15)`. Labels sit atop the field in `label-md` tracked Ash Ochre.

### Food & Reserve Cards
- Background `#231F1C`, 1px perimeter border `rgba(217, 155, 38, 0.14)`, radius `8px`, overflow hidden.
- Images occupy a 4:3 or 16:9 ratio with a warm, desaturated dark vignette overlay gradient fading toward the base to ensure legible overlaid typography.
- Card footer houses technical smoke specs (e.g., "Post Oak • 14 Hours • Prime Grade") formatted as inline uppercase metadata divided by subtle gold bullet points.