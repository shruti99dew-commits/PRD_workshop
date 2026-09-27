---
name: Botanical Warmth
colors:
  surface: '#f8f9ff'
  surface-dim: '#d0dbed'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dee9fc'
  surface-container-highest: '#d9e3f6'
  on-surface: '#121c2a'
  on-surface-variant: '#404945'
  inverse-surface: '#27313f'
  inverse-on-surface: '#eaf1ff'
  outline: '#717975'
  outline-variant: '#c0c8c3'
  surface-tint: '#3b6758'
  primary: '#013428'
  on-primary: '#ffffff'
  primary-container: '#1e4b3e'
  on-primary-container: '#8cbaa9'
  inverse-primary: '#a1d0bf'
  secondary: '#2c6955'
  on-secondary: '#ffffff'
  secondary-container: '#b1f0d6'
  on-secondary-container: '#326f5b'
  tertiary: '#5c1000'
  on-tertiary: '#ffffff'
  tertiary-container: '#7e230b'
  on-tertiary-container: '#ff9378'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bdeddb'
  primary-fixed-dim: '#a1d0bf'
  on-primary-fixed: '#002018'
  on-primary-fixed-variant: '#224e41'
  secondary-fixed: '#b1f0d6'
  secondary-fixed-dim: '#95d3bb'
  on-secondary-fixed: '#002117'
  on-secondary-fixed-variant: '#0d503e'
  tertiary-fixed: '#ffdad2'
  tertiary-fixed-dim: '#ffb4a2'
  on-tertiary-fixed: '#3c0700'
  on-tertiary-fixed-variant: '#83260e'
  background: '#f8f9ff'
  on-background: '#121c2a'
  surface-variant: '#d9e3f6'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 44px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-xs:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-md: 1.5rem
  gutter-lg: 2rem
  margin: 1rem
  margin-md: 2rem
  margin-lg: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system establishes a warm, contemporary, and trustworthy consumer aesthetic designed specifically for urban pet parents aged 25–40. It rejects childish, cartoonish pet-app clichés (e.g., novelty paw prints, neon palettes, overly bubbly shapes) in favor of refined botanical sophistication, authentic community warmth, and clear signals of safety and veterinary-grade reliability.

The emotional signature balances neighborhood familiarity with premium curation:
- **Calm Assurance:** Muted organic tones reassure pet owners concerning safety, health records, and trusted meetups.
- **Urban Polish:** Crisp structure, confident spacing, and thoughtful typography reflect the expectations of modern professionals.
- **Tactile Warmth:** Gentle cream bases and layered micro-elevations produce an inviting, physical feel without slipping into skeuomorphism.

## Colors
The palette evokes botanical freshness paired with warm domestic comfort, grounded by strict contrast ratios that fulfill WCAG AAA requirements for text readability.

- **Primary (`#1E4B3E` - Forest Green):** The core anchor for primary interactions, key navigation items, prominent badges, and verification anchors. Evokes grounding, nature, and responsibility.
- **Secondary (`#2D6A56` - Botanical Spruce):** Used for hover/pressed states of the primary hue, secondary buttons, section dividers, and active filters.
- **Tertiary (`#E76F51` - Warm Coral):** Reserved strictly for high-emotion and high-conversion moments—playdate matches, real-time alerts, critical CTAs, and heart states.
- **Neutral Primary (`#1F2937` - Deep Charcoal):** Highest-contrast typography and icon glyphs.
- **Neutral Muted (`#6B7280` - Slate Grey):** Secondary metadata, timestamps, and placeholder copy.
- **Canvas Base (`#FDFBF7` - Soft Cream):** Primary viewport backdrop that eliminates stark digital glare.
- **Accent Muted Lavender (`#ECE8F6` background, `#6C5CE7` foreground):** Exclusively utilized for specialized pet credentials, medical record verification tags, and behavioral trait badges.

## Typography
The system uses an intentional pairing between **Plus Jakarta Sans** for structural, expressive headings and **Inter** for dense, readable UI content.

- **Plus Jakarta Sans:** Provides friendly geometric construction with slightly rounded terminal terminals, giving pet profiles and section headers an approachable personality without losing refinement.
- **Inter:** Ensures maximum optical clarity across compact listings, safety documentation, verification badges, chat threads, and metadata counters.
- **Hierarchy Rules:** Section headers must always retain tight negative tracking (`-0.01em` to `-0.02em`) to maintain editorial punch. Overlines and status indicators use uppercase `label-xs` with expanded tracking to signal operational metadata cleanly.

## Layout & Spacing
The layout follows a fluid-responsive column system anchored by an 8pt spatial grid:
- **Mobile (< 768px):** 4 fluid columns, `1rem` margins, `1rem` gutters. Interactive cards span full-width or side-scrolling cards with partial peek.
- **Tablet (768px – 1024px):** 8 fluid columns, `2rem` margins, `1.5rem` gutters. Two-column pet profile card layouts and split-pane message panels.
- **Desktop (> 1024px):** 12 columns constrained to a max-width container of `1200px`, centered with `3rem` margins and `2rem` gutters.

Spacing tokens are strictly reserved for visual distance:
- `space-xs` (4px) and `space-sm` (8px) govern tight pairings (e.g., between an avatar and a verified badge, or icon and label).
- `space-md` (16px) establishes standard card interior padding and form input gaps.
- `space-lg` (24px) establishes structural section gaps within cards and list items.
- `space-xl` (40px) controls macro-separation between content blocks and feed segments.

## Elevation & Depth
Depth avoids artificial, pitch-black drop shadows in favor of ambient, multi-layered warm-toned diffusions. Shadows are tinted with the forest-primary or warm-neutral pigments to retain natural harmony with `#FDFBF7`.

- **Level 0 (Flat):** Surface container `#FFFFFF` nested on `#FDFBF7` base, framed by a soft hairline border: `1px solid rgba(31, 41, 55, 0.06)`. Used for list items and static panels.
- **Level 1 (Subtle Lift):** Cards, pet cards, and search inputs: `box-shadow: 0 2px 8px -2px rgba(30, 75, 62, 0.05), 0 1px 4px -1px rgba(31, 41, 55, 0.04)`.
- **Level 2 (Active / Floating):** Sticky navigation pills, active playdate invitations, filter drawers: `box-shadow: 0 12px 24px -6px rgba(30, 75, 62, 0.08), 0 4px 8px -2px rgba(31, 41, 55, 0.04)`.
- **Level 3 (Modals / Overlays):** Safety checklists, adoption/meetup verification dialogs: `box-shadow: 0 24px 48px -12px rgba(30, 75, 62, 0.16)`. Accompanied by a botanical-tinted backdrop blur: `backdrop-filter: blur(8px); background-color: rgba(30, 75, 62, 0.25)`.

## Shapes
The shape system employs Level 2 (Rounded) curvature across the entire component library:
- **Cards and Containers:** `rounded-lg` (16px / 1rem) creates an approachable yet orderly structure suitable for photo-heavy profiles and neighborhood event cards.
- **Dialogs & Sheet Modals:** `rounded-xl` (24px / 1.5rem) frames critical verification workflows and action hubs.
- **Buttons & Inputs:** `0.5rem` (8px) for inputs and tertiary buttons to maintain crisp tap targets, with selective pill-shapes reserved exclusively for tags, micro-badges, and filter chips.
- **Avatars:** Fully circular (`rounded-full`) for human owners, and rounded squares (`rounded-lg` with 16px radius) for pets to visually distinguish owner from animal at a glance.

## Components

### Buttons
- **Primary:** Forest green (`#1E4B3E`) background, white text (`#FFFFFF`), `0.5rem` radius, bold text (`label-md`). Hover elevates to `#2D6A56`.
- **Accent / Match:** Coral (`#E76F51`) background, white text, reserved for "Connect", "Schedule Playdate", and high-intent match requests.
- **Secondary / Ghost:** Soft cream background with a 1px border of `rgba(30, 75, 62, 0.2)` and text in `#1E4B3E`.

### Cards
- Constructed with `#FFFFFF` background against the `#FDFBF7` canvas, `1rem` border radius, subtle Level 1 elevation, and a delicate border (`rgba(31, 41, 55, 0.05)`).
- Pet Profile cards feature full-bleed imagery at top (aspect ratio 4:3 or 1:1), followed by `space-md` internal padding containing pet name, breed, age tag, and neighborhood location indicator.

### Badges & Chips
- **Filter Chips:** Pill-shaped, `0.75rem` vertical by `1rem` horizontal padding. Selected: `#1E4B3E` with white text. Unselected: `#FFFFFF` with `1px solid rgba(31, 41, 55, 0.12)` and `#1F2937` text.
- **Verification Badges:** Soft Lavender (`#ECE8F6`) background, `#6C5CE7` text and micro-shield icon for vet-checked, vaccination status, and identity-verified pet parents.
- **Trait Tags:** Muted sage background (`rgba(45, 106, 86, 0.08)`) with `#1E4B3E` text (e.g., "Leash Trained", "Friendly with Small Dogs").

### Form Inputs & Checkboxes
- **Inputs:** Crisp `#FFFFFF` surface with `1px solid rgba(31, 41, 55, 0.15)`, transitioning to `2px solid #1E4B3E` on focus without glowing neon rings. Muted placeholders in `#6B7280`.
- **Checkboxes & Radios:** Curved corner square for checkboxes (`4px`), circle for radios. Active state filled with `#1E4B3E` with crisp white inner tick.

### Trust & Safety Indicator
- A dedicated micro-component for local verification: an inline pill badge containing a safety icon, verified status copy, and a tap target leading to the Bangalore pet-parent verification ledger.