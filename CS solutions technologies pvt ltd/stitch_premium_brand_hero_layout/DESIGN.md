---
name: Luminous Corporate
colors:
  surface: '#f8f9ff'
  surface-dim: '#d8dadf'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3f9'
  surface-container: '#eceef3'
  surface-container-high: '#e6e8ed'
  surface-container-highest: '#e1e2e8'
  on-surface: '#191c20'
  on-surface-variant: '#414750'
  inverse-surface: '#2e3135'
  inverse-on-surface: '#eff1f6'
  outline: '#717881'
  outline-variant: '#c0c7d1'
  surface-tint: '#01629d'
  primary: '#004a78'
  on-primary: '#ffffff'
  primary-container: '#00629d'
  on-primary-container: '#bcdbff'
  inverse-primary: '#99cbff'
  secondary: '#b02f00'
  on-secondary: '#ffffff'
  secondary-container: '#ff5722'
  on-secondary-container: '#541100'
  tertiary: '#3234ad'
  on-tertiary: '#ffffff'
  tertiary-container: '#4b4fc6'
  on-tertiary-container: '#d4d4ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cfe5ff'
  primary-fixed-dim: '#99cbff'
  on-primary-fixed: '#001d34'
  on-primary-fixed-variant: '#004a78'
  secondary-fixed: '#ffdbd1'
  secondary-fixed-dim: '#ffb5a0'
  on-secondary-fixed: '#3b0900'
  on-secondary-fixed-variant: '#862200'
  tertiary-fixed: '#e1e0ff'
  tertiary-fixed-dim: '#c0c1ff'
  on-tertiary-fixed: '#04006d'
  on-tertiary-fixed-variant: '#3235ad'
  background: '#f8f9ff'
  on-background: '#191c20'
  surface-variant: '#e1e2e8'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 24px
  section-padding: 120px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 24px
---

## Brand & Style
The brand identity is rooted in "Luminous Professionalism"—a blend of high-end corporate reliability and modern, optimistic energy. The aesthetic targets growth-oriented B2B sectors, evoking feelings of transparency, scale, and elite performance.

The design style is **Glassmorphism-Infused Corporate**. It utilizes a sophisticated "light-wash" approach where deep background imagery is softened by high-opacity white overlays and backdrop blurs. This creates immense visual depth without sacrificing legibility or professional rigor. The interface feels airy and expansive, reflecting the "Smart Solutions" promise of limitless scaling.

## Colors
The palette is centered around "Success Blue" and "Growth Orange," now augmented by "Deep Integrity Indigo" for sophisticated layering.

- **Primary Blue (#00629d):** Used for core branding and high-action items. It represents stability and professional depth.
- **Secondary Orange (#ff5722):** Reserved for semantic highlights, active navigation states, and icons that signify momentum and client satisfaction.
- **Tertiary Indigo (#090191):** A deep, high-contrast navy used for specialized accents, heavy-weight typography, or distinct section backgrounds where the primary blue requires a more serious companion.
- **Surface & Background:** The UI utilizes a very light off-white (#F9FBF9) to maintain a clean, crisp environment.
- **Overlays:** A signature linear gradient (95% to 10% white) is used over hero imagery to ensure text remains the focal point while maintaining a cinematic background feel.

## Typography
The system pairs **Plus Jakarta Sans** for expressive, high-impact headlines with **Inter** for functional, highly legible body and UI text. 

Headlines utilize aggressive weights (ExtraBold 800) and tight letter spacing to project confidence. Body text maintains a generous line height (1.5-1.6) to ensure effortless readability in dense information environments. Labels use increased letter spacing and semi-bold weights to distinguish interactive triggers from static content.

## Layout & Spacing
The layout follows a **Fixed-Width Centered Grid** for desktop, capped at 1280px to maintain optimal line lengths. 

- **Vertical Rhythm:** Large vertical gaps (120px section padding) create a rhythmic "breath" between content blocks.
- **Internal Spacing:** A 3-tier stacking system (8px, 16px, 24px) handles component-level proximity.
- **Adaptation:** Mobile layouts transition to a single-column flow with 24px side margins, while primary headlines scale down approximately 35% to maintain visual balance.

## Elevation & Depth
Elevation is primarily conveyed through **Ambient Shadows** and **Tonal Layering**.

- **Level 1 (Subtle):** Used for static cards, featuring a very soft, low-opacity shadow (`rgba(0,0,0,0.03)`) to separate content from the background without creating harsh edges.
- **Level 2 (Interactive):** Used for hover states and primary action triggers, utilizing a blue-tinted shadow (`rgba(0, 98, 157, 0.08)`) to suggest "glow" and active potential.
- **Glass Effect:** The navigation bar uses a `backdrop-blur-xl` (24px+) combined with a semi-transparent white background (80% opacity) to provide a persistent sense of place without obscuring the background imagery.

## Shapes
The shape language is defined by **Large Radii (24px)** for containers and **Pill-shapes** for buttons. This softens the corporate aesthetic, making the brand feel more approachable and modern. 

Standard components (inputs, small cards) follow a 16px (rounded-xl) or 8px (rounded-lg) logic, but the signature "Floating Card" and "Action Button" use the 24px radius to create a distinct visual signature.

## Components
- **Primary Buttons:** High-contrast, pill-shaped (full rounded), utilizing the Primary Blue. Includes a subtle "active" scale-down effect (95%) and icon translation on hover.
- **Secondary Buttons:** Outlined with a 2px stroke matching the Primary color. Transitions to Secondary Orange on hover to signal a "hot" interaction area.
- **Tertiary Elements:** Specialized components such as tag labels or "Internal Use" badges utilize the Tertiary Indigo to distinguish them from standard primary/secondary flows.
- **Feature Cards:** White base (`surface-container-lowest`), 24px padding, 1px border (`outline-variant/50`), and Level 1 shadow. Icons within cards are housed in tinted circular containers (10% opacity of the icon color).
- **Navigation:** Fixed-top with a subtle bottom border (`10% opacity outline`). Active links are denoted by a 2px bottom border in the secondary color.
- **Icons:** Material Symbols (Outlined style), utilizing a Weight of 400. In feature cards, "FILL" is set to 1 to emphasize brand iconography.