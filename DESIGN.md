---
name: Enigma Systems
colors:
  surface: '#0a1513'
  surface-dim: '#0a1513'
  surface-bright: '#303c38'
  surface-container-lowest: '#06100d'
  surface-container-low: '#131e1b'
  surface-container: '#17221f'
  surface-container-high: '#212c29'
  surface-container-highest: '#2c3734'
  on-surface: '#d9e5e0'
  on-surface-variant: '#c5c9ad'
  inverse-surface: '#d9e5e0'
  inverse-on-surface: '#27332f'
  outline: '#8f937a'
  outline-variant: '#454934'
  surface-tint: '#b1d400'
  primary: '#ffffff'
  on-primary: '#2a3400'
  primary-container: '#ccf229'
  on-primary-container: '#596c00'
  inverse-primary: '#546500'
  secondary: '#4edea3'
  on-secondary: '#003824'
  secondary-container: '#00b47d'
  on-secondary-container: '#003e28'
  tertiary: '#ffffff'
  on-tertiary: '#103441'
  tertiary-container: '#c5e8f9'
  on-tertiary-container: '#486977'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ccf229'
  primary-fixed-dim: '#b1d400'
  on-primary-fixed: '#171e00'
  on-primary-fixed-variant: '#3e4c00'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002114'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#c5e8f9'
  tertiary-fixed-dim: '#a9ccdc'
  on-tertiary-fixed: '#001f29'
  on-tertiary-fixed-variant: '#2a4b59'
  background: '#0a1513'
  on-background: '#d9e5e0'
  surface-variant: '#2c3734'
  canvas-base: '#040807'
  surface-raised: '#0F1A17'
  surface-border: '#1B2B27'
  electric-lime: '#D2F831'
  matrix-emerald: '#4EDEA3'
  light-canvas: '#F7FDF9'
typography:
  headline-xl:
    fontFamily: Epilogue
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Epilogue
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Epilogue
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Epilogue
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Epilogue
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Epilogue
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: 0em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  code-lg:
    fontFamily: Space Mono
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.01em
  code-md:
    fontFamily: Space Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-md:
    fontFamily: Space Mono
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-sm:
    fontFamily: Space Mono
    fontSize: 10px
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
  gutter-sm: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system embodies a high-conviction, technical aesthetic rooted in modern developer tools, cryptography, and decentralized protocol architecture. It fuses the rigorous clarity of technical engineering with an electric, forward-leaning vitality.

### Brand Personality & Audience
- **Target Audience:** Systems engineers, protocol developers, cryptographers, and high-velocity technical teams building resilient digital infrastructure.
- **Personality:** Decisive, mathematically precise, utilitarian yet high-energy.
- **Emotional Response:** Inspires absolute confidence in speed, security, and cryptographic integrity. The experience feels fast, terminal-adjacent, and devoid of corporate fluff.

### Design Movement: Hyper-Modern Technical Brutalism
This design system pairs dark canvas aesthetics with ultra-sharp accents. Deep obsidian blacks and structural bio-luminescent greens construct a high-contrast matrix. Interface elements employ disciplined geometry, crisp hairline architectural lines, monospaced data density, and purposeful typography contrasts to create immediate visual clarity and raw utility.

## Colors

The color architecture relies on a luminous-on-void foundation, maximizing legibility in code-heavy and data-dense interfaces.

### Role Assignments
- **Canvas Base (`#040807`):** The foundational infinite canvas. An ultra-deep, slightly forest-tinted obsidian tone that mitigates eye fatigue and offers infinite depth.
- **Primary / Electric Lime (`#D2F831`):** High-velocity kinetic accent. Used sparingly for critical calls to action, active terminal signals, and primary interactions.
- **Secondary / Matrix Emerald (`#4EDEA3`):** Technical clarity and telemetry accent. Dedicated to cryptographic status indicators, success notifications, metric badges, and secondary interactive states.
- **Neutral / Surface Raised (`#0F1A17`):** The primary container surface. Lifts panels, tables, code blocks, and cards off the root canvas.
- **Light Canvas / Text On Dark (`#F7FDF9`):** Pristine, high-contrast foreground color used for body copy and headlines against the dark backdrop.

### Application Rules
1. Never flood surfaces with `#D2F831`—its high chroma is reserved strictly for focal points, active cursors, primary triggers, and high-impact key performance indicators.
2. Structure surfaces using hairline borders with `#1B2B27` rather than high-contrast dividing lines.
3. For disabled or lower-tier elements, employ alpha-blended variants of `#F7FDF9` (60% for secondary, 38% for tertiary, 12% for stroke dividers).

## Typography

The typographic hierarchy orchestrates three distinct typefaces to demarcate editorial structure, readable body communication, and precision data visualization:

- **Headlines (Epilogue):** Imparts weight, structural architectural tension, and editorial authority to prominent section heads and landing statements.
- **Body & Prose (Plus Jakarta Sans):** High legibility and soft geometry that balances the technical edge, ensuring comfortable scanning over long documents.
- **Labels, Telemetry, and Code (Space Mono):** Used for navigation anchors, tags, protocol readouts, data metrics, hash IDs, and interactive buttons. Labels default to uppercase formatting with widened letter spacing to invoke terminal instrument panels.

## Layout & Spacing

The layout philosophy leverages an adaptive fluid grid with rigid structural containment:
- **Desktop (1024px+):** 12-column layout with 24px (`1.5rem`) gutters and a max canvas width of 1440px centered within standard 32px (`2rem`) margins.
- **Tablet (768px - 1023px):** 8-column layout with 16px (`1rem`) gutters and 24px margins.
- **Mobile (< 768px):** 4-column layout with 16px gutters and 16px (`1rem`) margins.

Spacing follows an exponential 4px/8px modular scale. Spacers (`space-xs` through `space-xl`) define padding within elements and structural offsets between siblings. Cards and data grids maintain square rhythm, favoring compact padding (`space-md` or `space-lg`) to preserve information density without clutter.

## Elevation & Depth

Visual hierarchy is constructed through structural surface stacking and crisp hairline borders rather than traditional diffused drop shadows.

- **Surface Tiers:**
  - *Tier 0 (Root Canvas):* `#040807` — absolute background.
  - *Tier 1 (Panels & Cards):* `#0F1A17` with a 1px border of `#1B2B27`.
  - *Tier 2 (Modals, Flyouts, Tooltips):* `#13221E` overlaid with a 1px border of `#4EDEA3` (at 40% alpha) and subtle ambient glow (`0 8px 32px rgba(4, 8, 7, 0.8)`).
- **Hairline Framing:** Borders remain 1px wide. Selected or hovered elements illuminate by shifting border color from neutral `#1B2B27` to active `#4EDEA3` or `#D2F831`.
- **Neon Bloom:** For interactive anchors and active terminal triggers, an electric bloom effect can be applied on hover: `box-shadow: 0 0 16px rgba(210, 248, 49, 0.35)`.

## Shapes

The design system utilizes subtle corner rounding (`roundedness: 1` — Soft / 4px base radius) to retain an architectural, instrument-like feel while smoothing harsh pixel corners.

- **Containers & Panels:** `0.25rem` (4px).
- **Cards & Modals (`rounded-lg`):** `0.5rem` (8px).
- **Badges, Tags & Input Fields:** `0.25rem` (4px).
- **Full Pill Exceptions:** Badges indicating active real-time status pulses or system connectivity may adopt fully rounded pill styling (`9999px`) where appropriate.

## Components

### Buttons
- **Primary:** Background in `#D2F831`, foreground in `#040807`, styled with `label-md` uppercase typography in `Space Mono`. On hover: `box-shadow: 0 0 16px rgba(210, 248, 49, 0.45)`, scale transition: none (instant, mechanical response).
- **Secondary / Ghost:** Transparent background with 1px border in `#4EDEA3`, text in `#4EDEA3`. On hover: background `#4EDEA3` at 10% opacity, border `#4EDEA3`.
- **Tertiary / Subdued:** Background `#0F1A17`, border 1px `#1B2B27`, text `#F7FDF9`. On hover: border `#F7FDF9` at 40%.

### Chips & Badges
- Constructed with `label-sm` font settings. Height fixed at 24px with horizontal padding of `space-sm`.
- **Status Chip:** Surface `#0F1A17` with 1px border in `#1B2B27`. Employs a 6px glowing green dot (`#4EDEA3`) on the left to signify active node connection.

### Cards & Grid Modules
- Background `#0F1A17` with a 1px border in `#1B2B27`.
- Padding set to `space-lg` (24px).
- Card headers utilize `headline-sm` with subheadings set in `code-md` (`Space Mono`) to reinforce data integrity.

### Input Fields & Controls
- **Inputs:** Surface `#040807`, border 1px `#1B2B27`, text `#F7FDF9` in `Space Mono`. Focus state transitions the border to `#D2F831` with an interior glow `inset 0 0 0 1px #D2F831`.
- **Checkboxes & Radios:** Sharp 4px boxes with `#0F1A17` fill and `#1B2B27` stroke. Checked state fills with `#D2F831` featuring an obsidian `#040807` glyph.

### Code Terminals & Telemetry Logs
- Specialized component embedded directly into operational panels.
- Dark canvas `#040807` with a top header bar containing window controls and node cluster identifiers.
- Body formatted strictly in `code-md` (`Space Mono`) with syntax highlights utilizing `#D2F831` (variables/keywords) and `#4EDEA3` (strings/values).