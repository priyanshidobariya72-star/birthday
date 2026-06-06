---
name: Ethereal Devotion
colors:
  surface: '#fff8f1'
  surface-dim: '#dfd9d1'
  surface-bright: '#fff8f1'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f9f3eb'
  surface-container: '#f4ede5'
  surface-container-high: '#eee7df'
  surface-container-highest: '#e8e1da'
  on-surface: '#1e1b17'
  on-surface-variant: '#514345'
  inverse-surface: '#33302b'
  inverse-on-surface: '#f7f0e8'
  outline: '#847375'
  outline-variant: '#d6c2c3'
  surface-tint: '#874e58'
  primary: '#874e58'
  on-primary: '#ffffff'
  primary-container: '#ffb6c1'
  on-primary-container: '#7b444e'
  inverse-primary: '#fcb3be'
  secondary: '#655687'
  on-secondary: '#ffffff'
  secondary-container: '#d8c6fe'
  on-secondary-container: '#5e5080'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#ecc54b'
  on-tertiary-container: '#675200'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9de'
  primary-fixed-dim: '#fcb3be'
  on-primary-fixed: '#360c17'
  on-primary-fixed-variant: '#6b3741'
  secondary-fixed: '#eaddff'
  secondary-fixed-dim: '#d0bef5'
  on-secondary-fixed: '#21123f'
  on-secondary-fixed-variant: '#4d3f6e'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#fff8f1'
  on-background: '#1e1b17'
  surface-variant: '#e8e1da'
typography:
  display-romantic:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.3'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-padding: 32px
  element-gap: 24px
  section-margin: 80px
---

## Brand & Style

The design system is centered on an intimate, dreamlike celebration of a personal bond. It targets a romantic partner, aiming to evoke feelings of warmth, nostalgia, and enchantment. The aesthetic is "Etheral High-End," blending soft organic forms with sophisticated digital depth.

The style is primarily **Glassmorphism** mixed with **Minimalism**. It uses translucent layers and background blurs to create a sense of light passing through delicate materials. Floating elements and subtle "magical" particle effects (small, shimmering golden dots) provide a sense of weightlessness and movement. Every interaction should feel like a soft breeze—fluid, gentle, and intentional.

## Colors

The palette is a sophisticated blend of dawn-like pastels and metallic warmth:

- **Primary (Soft Pink - #ffb6c1):** Used for key emotional moments, active states, and soft glows.
- **Secondary (Lavender - #d9c7ff):** Used for interactive elements and depth layering.
- **Tertiary (Gold - #D4AF37):** Reserved for accents, iconography, and decorative "magic" particles.
- **Neutral (Cream - #fff8f0):** The foundation of the UI, providing a warm, parchment-like alternative to stark white.
- **Surface (Cloud White - #FFFFFF):** Used for high-elevation glass cards with 60-80% opacity.

## Typography

The typography strategy pairs editorial elegance with modern legibility. 

- **Headings:** While the narrative requests a romantic feel, we utilize **Playfair Display** (as a high-end alternative available in the system) to provide that classic, high-contrast serif look for "Display" and "Headline" levels. These should be treated with generous line height.
- **Body & Labels:** **Plus Jakarta Sans** provides a soft, rounded, and contemporary feel that ensures the "clean" requirement is met without feeling corporate. 
- **Styling:** Use Gold (#D4AF37) for Labels to make them feel like delicate engravings. Large headings should often be center-aligned to evoke the feeling of a formal invitation.

## Elevation & Depth

Depth is the cornerstone of this design system, achieved through **Glassmorphism** and **Ambient Shadows**:

- **Layers:** Use multiple stacked surfaces. The base layer is the Cream background. The second layer consists of soft, blurred Pink or Lavender "auras." The top layer consists of semi-transparent Cloud White cards.
- **Shadows:** Use very large, extremely soft shadows (Blur: 40px, Opacity: 8%) tinted with the Secondary color (#d9c7ff) instead of black. This makes elements appear to float in a hazy, ethereal space.
- **Glass Effect:** Apply a `backdrop-filter: blur(12px)` to all cards, with a 1px solid white border at 20% opacity to define the edges.

## Shapes

The design system uses a **Rounded** shape language to maintain softness. Sharp corners are avoided entirely as they break the "dreamlike" illusion. 

- Standard components use a 0.5rem (8px) radius.
- Large cards and floating containers use a 1.5rem (24px) radius.
- Decorative elements, such as "story" circles or floating bubbles, should be fully circular.

## Components

- **Glass Cards:** The primary container. Must have a soft white border and background blur. They should appear to "hover" with a subtle float animation (Y-axis oscillation).
- **Romantic Buttons:** Pill-shaped with a subtle Gold-to-Pink gradient. Text should be in the Label style. On hover, the button should "glow" with a soft pink shadow.
- **Floating Chips:** Small, translucent Lavender capsules used for tags or dates, with Gold text.
- **Input Fields:** Minimalist. Only a bottom border in Gold, which expands softly when focused.
- **Photo Frames:** Images should have high roundedness (1rem) and a soft "bloom" effect (inner glow) to make them look like memories rather than flat files.
- **Particle Layer:** A global background component that generates slow-moving, tiny Gold (#D4AF37) circles of varying sizes and opacities (0.1 to 0.5) to simulate magic dust.