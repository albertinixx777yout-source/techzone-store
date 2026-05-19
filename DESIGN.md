---
name: TechZone Store
colors:
  surface: '#121317'
  surface-dim: '#121317'
  surface-bright: '#38393d'
  surface-container-lowest: '#0d0e12'
  surface-container-low: '#1a1b1f'
  surface-container: '#1e1f23'
  surface-container-high: '#292a2e'
  surface-container-highest: '#343539'
  on-surface: '#e3e2e7'
  on-surface-variant: '#c1c6d7'
  inverse-surface: '#e3e2e7'
  inverse-on-surface: '#2f3034'
  outline: '#8b90a0'
  outline-variant: '#414755'
  surface-tint: '#adc6ff'
  primary: '#adc6ff'
  on-primary: '#002e69'
  primary-container: '#4b8eff'
  on-primary-container: '#00285c'
  inverse-primary: '#005bc1'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#4a4949'
  on-secondary-container: '#bab8b7'
  tertiary: '#c6c6c8'
  on-tertiary: '#2f3132'
  tertiary-container: '#909193'
  on-tertiary-container: '#282a2c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a41'
  on-primary-fixed-variant: '#004493'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#e2e2e4'
  tertiary-fixed-dim: '#c6c6c8'
  on-tertiary-fixed: '#1a1c1d'
  on-tertiary-fixed-variant: '#454749'
  background: '#121317'
  on-background: '#e3e2e7'
  surface-variant: '#343539'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Metropolis
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Metropolis
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1440px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

The design system is engineered to evoke a sense of precision, innovation, and premium craftsmanship. It targets tech enthusiasts and professional creators who value high-performance hardware and refined aesthetics. 

The visual style is **Modern Minimalism** infused with a **Futuristic** edge. It utilizes expansive whitespace to allow product photography to breathe, paired with sharp, intentional accents of color that mimic high-end LED indicators. The interface should feel like a high-performance instrument: quiet, efficient, and sophisticated.

## Colors

The palette is anchored in a sophisticated Dark Mode to highlight the textures of hardware products.

*   **Primary (Electric Blue):** Used exclusively for interactive focal points, progress indicators, and active states. It represents the "pulse" of the technology.
*   **Secondary (Deep Charcoal):** The foundational surface color. It provides a rich, low-glare backdrop that enhances the luminosity of screen displays in product shots.
*   **Tertiary (Crisp White):** Reserved for primary high-contrast text and critical UI elements to ensure peak legibility.
*   **Neutral (Slate Gray):** Used for secondary information, borders, and disabled states to maintain a clean visual hierarchy without clutter.

## Typography

This design system employs a tiered typographic strategy to balance technical precision with marketing impact.

*   **Hanken Grotesk** is used for headlines. Its contemporary geometry and sharp terminals feel engineered and modern.
*   **Metropolis** serves as the workhorse for body copy. Its high x-height and geometric structure ensure readability across long product descriptions and technical specs.
*   **JetBrains Mono** is utilized for small labels, SKU numbers, and technical specifications, providing a "system-code" aesthetic that resonates with tech-savvy users.

All headers use tighter letter spacing to maintain a "locked-in" architectural feel.

## Layout & Spacing

The layout follows a **12-column fluid grid** for desktop and a **4-column grid** for mobile. 

*   **Whitespace:** Use generous vertical padding (80px - 120px) between major sections to emphasize a premium, gallery-like experience.
*   **Alignment:** Content should predominantly be left-aligned to mimic technical documentation, with the exception of hero display sections which can be centered for dramatic impact.
*   **Density:** Keep information density low. Utilize "progressive disclosure" (e.g., expandable spec sheets) to prevent cognitive overload.

## Elevation & Depth

Hierarchy is established through **Tonal Layers** and **Subtle Shadows**.

*   **Planes:** The base surface is `#121212`. Elevated cards use a slightly lighter `#1E1E1E`.
*   **Shadows:** Use extremely diffused "Ambient Shadows" with a 0% offset and large blur radii (20px - 40px). Shadow color should be a deep indigo-black to prevent a "dirty" look on the dark background.
*   **Glassmorphism:** Apply a 20px backdrop blur with 10% opacity white fill on navigation bars to maintain context as users scroll through content.

## Shapes

The shape language is disciplined and industrial. **Soft (0.25rem)** corners are the standard for most UI components (buttons, input fields) to maintain a precise, hardware-milled aesthetic. 

Product cards may use **rounded-lg (0.5rem)** to slightly soften the visual impact of large images. Avoid fully rounded pill shapes as they appear too playful for this professional brand narrative.

## Components

*   **Buttons:** Primary buttons are solid Electric Blue with White text. Secondary buttons use a ghost style (Transparent background, White border, White text).
*   **Input Fields:** Dark backgrounds (`#1E1E1E`) with a subtle 1px border. On focus, the border transitions to Electric Blue with a faint outer glow.
*   **Cards:** Use a "Flat-Elevated" look. No borders; depth is defined solely by a slight change in background tone and the ambient shadow.
*   **Chips/Tags:** Monospaced text (JetBrains Mono) inside a dark gray container with high letter spacing.
*   **Status Indicators:** Use small, glowing circular pips for "In Stock" (Cyan) or "Limited Edition" (Electric Blue) status.
*   **Additional Components:** Include a "Spec-Grid"—a high-contrast, data-heavy table component designed specifically for comparing technical hardware specifications.