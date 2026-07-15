---
name: Heritage Institutional
colors:
  surface: '#fff8f6'
  surface-dim: '#e7d6d1'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff1ec'
  surface-container: '#fceae5'
  surface-container-high: '#f6e5df'
  surface-container-highest: '#f0dfda'
  on-surface: '#221a17'
  on-surface-variant: '#554242'
  inverse-surface: '#382e2b'
  inverse-on-surface: '#ffede8'
  outline: '#887271'
  outline-variant: '#dbc0bf'
  surface-tint: '#9c4144'
  primary: '#510711'
  on-primary: '#ffffff'
  primary-container: '#6f1f24'
  on-primary-container: '#f58687'
  inverse-primary: '#ffb3b2'
  secondary: '#7f5600'
  on-secondary: '#ffffff'
  secondary-container: '#fec568'
  on-secondary-container: '#775000'
  tertiary: '#282620'
  on-tertiary: '#ffffff'
  tertiary-container: '#3e3c35'
  on-tertiary-container: '#aba69d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad9'
  primary-fixed-dim: '#ffb3b2'
  on-primary-fixed: '#410008'
  on-primary-fixed-variant: '#7d2a2e'
  secondary-fixed: '#ffdeae'
  secondary-fixed-dim: '#f5bd61'
  on-secondary-fixed: '#281900'
  on-secondary-fixed-variant: '#604100'
  tertiary-fixed: '#e7e2d8'
  tertiary-fixed-dim: '#cbc6bc'
  on-tertiary-fixed: '#1d1b16'
  on-tertiary-fixed-variant: '#49473f'
  background: '#fff8f6'
  on-background: '#221a17'
  surface-variant: '#f0dfda'
  cream-bg: '#f8f2e8'
  paper-surface: '#fffdf9'
  ink-text: '#271e1b'
  heritage-maroon: '#6f1f24'
  saffron-gold: '#ce9a42'
  muted-earth: '#765f54'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 82px
    fontWeight: '700'
    lineHeight: 96px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 52px
    fontWeight: '700'
    lineHeight: 60px
  headline-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 34px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  eyebrow:
    fontFamily: DM Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.18em
  button-label:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  section-gap-desktop: 100px
  section-gap-mobile: 70px
  grid-gutter: 24px
  content-max-width: 1160px
  readable-text-width: 720px
---

## Brand & Style

This design system is built upon the pillars of **longevity, purity, and local heritage**. It serves as a visual "stamp of quality" for a brand that has been a staple in the community for decades. The aesthetic is anchored in a **Corporate/Modern** framework but heavily infused with **Heritage** elements—utilizing generous whitespace, editorial typography, and a palette that evokes traditional Indian dairy craftsmanship.

The target audience seeks reliability and a connection to the past. The UI should feel like a digital extension of a physical boutique storefront: warm, authentic, and timeless. We avoid fleeting trends like neon or heavy glassmorphism, favoring instead the permanence of a well-printed broadsheet or a vintage product label.

## Colors

The palette is a direct reflection of the brand's heritage materials: **Maroon** (the color of traditional seals and richness), **Saffron** (representing purity and local flavor), and **Cream** (the essence of dairy).

- **Primary (Maroon):** Used for key identity moments, primary calls to action, and as a sophisticated background for high-contrast sections.
- **Secondary (Saffron):** Reserved for highlights, celebratory accents, and "premium" category markers.
- **Tertiary (Cream):** The primary canvas. It replaces stark white to provide a softer, more organic "paper" feel that reduces digital eye strain.
- **Neutral (Ink):** A deep, warm black used for body text to maintain maximum legibility while staying within the warm tonal family.

## Typography

The typographic strategy relies on a classic **Serif/Sans-Serif pairing**. 

**Playfair Display** provides the "voice" of the brand. It is used for all headlines and emotional copy. Its high contrast and elegant serifs evoke the feel of a heritage institution.

**DM Sans** provides the "utility." It is a modern, low-contrast sans-serif that ensures clear communication for menus, product descriptions, and metadata. 

The "Eyebrow" style is a critical design element—it should always be uppercase with increased letter spacing to act as a clear section signifier without overwhelming the main headline.

## Layout & Spacing

This design system employs a **Fluid Grid** with a strong emphasis on vertical rhythm. 

- **Sectioning:** Large vertical gaps (100px) are used to separate major content areas, allowing the high-quality imagery and typography to "breathe."
- **Widths:** While the main container stretches to 1160px for grid layouts (like product cards), long-form text is restricted to a "readable width" of 720px to ensure an optimal reading experience.
- **Breakpoints:** Transitions occur at 720px, where multi-column grids (3 or 4 columns) collapse into a single-column stack. Margins should reduce from 40px to 20px on mobile devices.

## Elevation & Depth

To maintain the "Heritage" feel, the system avoids heavy drop shadows and synthetic glows. Depth is instead communicated through **Tonal Layering** and **Structural Outlines**.

- **Surfaces:** We use subtle shifts in background color (e.g., Cream to a slightly darker 'Efe4d3' or a lighter 'Paper' white) to define sections.
- **Overlays:** For text over photography, a soft Maroon-tinted gradient (`rgba(35, 19, 14, 0.6)`) is used rather than a pure black overlay, maintaining the warmth of the palette.
- **Interaction:** Hover states should be indicated by color shifts or subtle scale transforms (1.02x) rather than increased shadow depth.

## Shapes

The shape language is **Soft and Structural**. We use a conservative corner radius (0.25rem / 4px) for interactive elements like buttons and cards. This provides a hint of modernity and friendliness without losing the "institutional" sturdiness that 0px corners provide.

**Specific Shape Elements:**
- **Product Cards:** Feature a prominent 3px top-border in Saffron-Gold to provide a signature brand mark.
- **Logo Containers:** The circular seal of the logo should be mirrored in avatar or featured-category thumbnails where appropriate.

## Components

### Buttons
- **Primary:** Solid Saffron-Gold background with Maroon or Ink text. 4px border radius. Bold DM Sans labels.
- **Secondary (Ghost):** 1px border in the current text color (Maroon or White). No fill.
- **Action Links:** DM Sans (Bold) followed by a thin arrow icon (→).

### Cards
- Background: Paper-Surface (#fffdf9).
- Accent: 3px top-border in Saffron-Gold.
- Content: Eyebrow label in Maroon, Headline in Playfair Display, Body in Muted Earth.

### Input Fields
- Understated style: 1px bottom-border only, or a very light 1px stroke on all sides using `#d5c5b1`.
- Focus State: Border color shifts to Maroon.

### WhatsApp Integration
As a primary ordering channel, the WhatsApp CTA should be treated with its own dedicated style: a Maroon background with white text and the brand monogram, often fixed or pinned for easy access.

### Lists & Dividers
- Use thin (1px) horizontal lines in `#efe4d3` for subtle separation.
- List items should have generous vertical padding (16px+) to maintain the system's spacious, premium feel.