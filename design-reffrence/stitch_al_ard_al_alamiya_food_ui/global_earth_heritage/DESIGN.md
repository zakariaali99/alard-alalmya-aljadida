---
name: Global Earth Heritage
colors:
  surface: '#f7f9ff'
  surface-dim: '#d7dadf'
  surface-bright: '#f7f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f9'
  surface-container: '#ebeef3'
  surface-container-high: '#e5e8ee'
  surface-container-highest: '#e0e3e8'
  on-surface: '#181c20'
  on-surface-variant: '#444651'
  inverse-surface: '#2d3135'
  inverse-on-surface: '#eef1f6'
  outline: '#757682'
  outline-variant: '#c5c5d3'
  surface-tint: '#4059aa'
  primary: '#00236f'
  on-primary: '#ffffff'
  primary-container: '#1e3a8a'
  on-primary-container: '#90a8ff'
  inverse-primary: '#b6c4ff'
  secondary: '#805533'
  on-secondary: '#ffffff'
  secondary-container: '#fdc39a'
  on-secondary-container: '#794e2e'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cca730'
  on-tertiary-container: '#4e3d00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#264191'
  secondary-fixed: '#ffdcc5'
  secondary-fixed-dim: '#f4bb92'
  on-secondary-fixed: '#301400'
  on-secondary-fixed-variant: '#653d1e'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#f7f9ff'
  on-background: '#181c20'
  surface-variant: '#e0e3e8'
  earth-brown: '#5D4037'
  pulse-cream: '#FDFBF7'
  sky-blue-tint: '#EBF1FF'
  gold-leaf: '#C5A028'
typography:
  display-lg:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 60px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
  headline-lg:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: IBM Plex Sans Arabic
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 0.5rem
  sm: 1rem
  md: 1.5rem
  lg: 2.5rem
  xl: 4rem
  container-max: 1280px
  gutter: 24px
---

## Brand & Style

This design system is built for a global leader in the food import/export sector, balancing the precision of international logistics with the organic warmth of agricultural trade. The brand personality is **authoritative, dependable, and grounded**. It bridges the gap between high-scale corporate operations and the tactile nature of earth-grown products like legumes and nuts.

The chosen design style is **Corporate / Modern with Tonal Warmth**. It emphasizes clarity and trust through structured layouts, while utilizing a sophisticated palette of earthy accents to humanize the digital experience. High-quality photography of raw products and global shipping routes should be used with generous whitespace to ensure a premium, uncluttered feel. The system is designed with a **Right-to-Left (RTL) first** mindset to prioritize the primary Arabic-speaking market.

## Colors

The palette is anchored by a **Deep Maritime Blue**, representing global trade, stability, and professional integrity. This is contrasted by a range of **Earthy Tones**—specifically a toasted brown and a refined gold—which directly reference the company's core commodities: pulses and nuts.

- **Primary (Maritime Blue):** Used for headers, primary actions, and navigational anchors.
- **Secondary (Earth Brown):** Used for supportive accents, category tags, and icons related to the product origin.
- **Tertiary (Refined Gold):** Reserved for high-importance highlights, premium product lines, and quality certifications.
- **Neutral:** A deep charcoal is used for body text to ensure maximum readability against the **Pulse Cream** background, which is a warmer, more organic alternative to pure white for large surface areas.

## Typography

The typography utilizes **IBM Plex Sans Arabic** for its exceptional clarity and technical precision. It provides a contemporary "Grotesque" feel that remains highly legible in both Arabic and English, which is essential for international trade documentation and product labeling.

- **Scale:** A strict typographic hierarchy is maintained to guide the user through complex product specifications and company information.
- **Weight:** Headlines utilize SemiBold (600) and Bold (700) to project strength. Body text is kept at Regular (400) for comfortable long-form reading.
- **RTL Optimization:** Special attention is paid to line heights to accommodate the ascending and descending strokes characteristic of Arabic script, preventing clipping and maintaining a balanced vertical rhythm.

## Layout & Spacing

This design system employs a **12-column fixed grid** for desktop, transitioning to a **4-column fluid grid** for mobile devices. The layout philosophy centers on **generous margins** to evoke a sense of premium quality and "breathability."

- **Grid:** On desktop, the container is centered with a max-width of 1280px. 
- **RTL Flow:** All layouts are mirrored. Sidebars appear on the right, and "Next" actions point to the left.
- **Vertical Rhythm:** Spacing between sections should be significant (using the `xl` token) to maintain the clean, corporate aesthetic.
- **Breakpoints:**
  - Mobile: < 768px (Side margins: 16px)
  - Tablet: 768px - 1024px (Side margins: 32px)
  - Desktop: > 1024px (Side margins: Auto)

## Elevation & Depth

Visual hierarchy is established through **Tonal Layers** and **Soft Ambient Shadows**. This approach avoids the harshness of pure flat design while remaining more modern than traditional skeuomorphism.

- **Surface Strategy:** The primary background is `pulse-cream`. Elevated elements like product cards use a pure white surface (`#FFFFFF`).
- **Shadows:** Use extremely soft, low-opacity shadows with a slight blue tint (`rgba(30, 58, 138, 0.08)`) to connect the elements to the primary brand color. 
- **Interactive Depth:** Buttons and interactive cards should use a subtle lift on hover (moving from a 4px blur to an 8px blur) to provide tactile feedback without being distracting.
- **Outlines:** Use 1px borders in a very light grey or a tinted version of the primary blue for secondary containers where shadows might clutter the interface.

## Shapes

The shape language is **Rounded**, reflecting the organic nature of the food products (seeds, pulses, nuts) while maintaining a professional structure.

- **Components:** Standard buttons, input fields, and cards use the `0.5rem` (8px) base radius.
- **Imagery:** Product photography within grids should feature slightly rounded corners to soften the corporate layout.
- **Large Containers:** Hero sections or large background panels may use `rounded-xl` (1.5rem) on bottom corners to create a modern, flowing transition between sections.

## Components

### Navbar
- **Structure:** Right-aligned logo, left-aligned navigation links, and a prominent "Contact Us" or "Request Quote" button in the primary blue.
- **Behavior:** Sticky on scroll with a slight backdrop blur and a fine bottom border for definition.

### Hero Section
- **Visuals:** High-resolution imagery of earth-toned pulses or global shipping vessels. 
- **Typography:** Large `display-lg` headline in primary blue, with a secondary call-to-action in the tertiary gold.

### Product Cards
- **Style:** White background, soft ambient shadow. 
- **Content:** Product image at the top, followed by a `headline-md` title and `label-md` for origin/specification.
- **Footer:** A subtle "View Details" link using an arrow icon (pointing left for RTL).

### Input Fields
- **Style:** Clean 1px border. On focus, the border transitions to Primary Blue with a 2px soft outer glow.
- **Labels:** Always positioned above the field, right-aligned.

### Buttons
- **Primary:** Solid Primary Blue with white text.
- **Secondary:** Earth Brown border with Earth Brown text.
- **Tertiary/Ghost:** Gold text with no background, used for less critical actions.

### Footer
- **Design:** Deep neutral background (`#212529`) with white or gold-leaf text. 
- **Layout:** 4-column layout including company bio, quick links, product categories, and contact details with integrated map markers.