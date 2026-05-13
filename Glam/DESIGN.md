---
name: Luxe Petal & Gold
colors:
  surface: '#fff8f8'
  surface-dim: '#e5d7d9'
  surface-bright: '#fff8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0f2'
  surface-container: '#f9eaec'
  surface-container-high: '#f4e5e7'
  surface-container-highest: '#eedfe1'
  on-surface: '#211a1b'
  on-surface-variant: '#504444'
  inverse-surface: '#372e30'
  inverse-on-surface: '#fcedef'
  outline: '#827473'
  outline-variant: '#d4c2c2'
  surface-tint: '#7b5455'
  primary: '#7b5455'
  on-primary: '#ffffff'
  primary-container: '#d4a5a5'
  on-primary-container: '#5d3a3b'
  inverse-primary: '#ecbbba'
  secondary: '#7f5353'
  on-secondary: '#ffffff'
  secondary-container: '#fdc3c3'
  on-secondary-container: '#7a4e4f'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#d2ad35'
  on-tertiary-container: '#534100'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad9'
  primary-fixed-dim: '#ecbbba'
  on-primary-fixed: '#2f1314'
  on-primary-fixed-variant: '#603d3e'
  secondary-fixed: '#ffdad9'
  secondary-fixed-dim: '#f1b8b8'
  on-secondary-fixed: '#311213'
  on-secondary-fixed-variant: '#643c3c'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#fff8f8'
  on-background: '#211a1b'
  surface-variant: '#eedfe1'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  section-desktop: 120px
  section-mobile: 64px
  gutter: 24px
  container-max: 1200px
---

## Brand & Style

The brand identity for Dherbyz_Glam is rooted in the intersection of high-end editorial luxury and a welcoming, feminine sanctuary. Located in the heart of Kwashieman, Ghana, the visual language must communicate international standards while remaining approachable to a local clientele seeking a premium escape.

The design style is **Minimalist Glassmorphism**. This approach utilizes the clarity and whitespace of minimalism to highlight high-end beauty imagery, layered with the translucent, frosted-glass effects of glassmorphism to add depth and a sense of "soft-focus" beauty. The emotional response should be one of immediate serenity and "attainable luxury"—where every client feels like a VIP. 

Visuals should prioritize "visually rich" simplicity: expansive layouts, high-contrast serif headings, and delicate gold metallic accents that shimmer against a matte, tonal pink backdrop.

## Colors

The palette is a monochromatic exploration of pinks, grounded by the warmth of gold. 

- **Primary & Secondary:** Dusty Pink (#D4A5A5) and Rose Pink (#C28E8E) act as the functional anchors for interaction states and primary brand elements.
- **Surface Palette:** Blush Pink (#F5E6E8) and Soft Nude (#FDF5F6) are used for large background areas and container surfaces, creating a "skin-tone" warmth that feels organic and inviting.
- **Accents:** Gold (#D4AF37) is reserved for high-impact moments: call-to-action buttons, icon highlights, and borders. 
- **Typography Colors:** Use the Rose Pink for primary text to maintain softness; avoid pure black. Use White for text on darker pink backgrounds to maintain a high-fashion, airy feel.

## Typography

The typography strategy relies on the contrast between the classic, high-contrast elegance of **Playfair Display** and the clean, geometric precision of **Plus Jakarta Sans** (serving as a professional alternative to Poppins).

- **Headlines:** Use Playfair Display for all major headings. Large display sizes should use tighter letter spacing to feel like a high-end magazine cover.
- **Body Text:** Plus Jakarta Sans provides a friendly yet corporate legibility. Keep line heights generous (1.6x) to ensure a sense of "premium breathing room."
- **Utility Text:** Use the `label-caps` style for small headers above sections, navigation items, and buttons to inject a modern, structured rhythm into the soft aesthetic.

## Layout & Spacing

This design system utilizes a **Fixed Grid** model for desktop to maintain an editorial, centered feel, transitioning to a **Fluid Grid** for mobile devices.

- **Desktop:** 12-column grid with a 1200px max-width. Use significant "white space" (negative space) between sections (120px) to prevent the UI from feeling cluttered.
- **Mobile:** 4-column grid with 20px side margins.
- **Rhythm:** All spacing (padding, margins, gap) must be multiples of the 8px base unit.
- **Alignment:** Center-align hero content for a formal, symmetrical look; left-align functional service lists and forms for professional clarity.

## Elevation & Depth

Hierarchy is achieved through **Glassmorphism** and **Ambient Shadows** rather than stark borders.

- **Glassmorphic Layers:** Use background blurs (10px–20px) on navigation bars and floating cards. Surfaces should have a 60-80% opacity of White or Soft Nude, creating a "frosted" effect that allows the underlying beauty imagery to peak through.
- **Shadows:** Avoid gray shadows. Use a "Rose-tinted Glow"—shadows should be soft, extra-diffused, and use a low-opacity Rose Pink (#C28E8E) instead of black. This creates a warm, natural lift.
- **Gold Strokes:** For the highest level of hierarchy (e.g., "Book Now" buttons), use a 1px solid Gold border to provide a crisp, metallic edge.

## Shapes

The shape language is organic and soft, avoiding harsh 90-degree angles to maintain a feminine appeal.

- **Standard Radius:** 0.5rem (8px) for buttons and inputs.
- **Large Radius:** 1rem (16px) for cards, images, and modal containers.
- **Feature Shapes:** Use perfect circles for staff profile pictures and floating action buttons to introduce a more organic, "bubble" aesthetic that complements the glassmorphism.
- **Imagery:** All beauty photography should have the `rounded-xl` (24px) treatment to feel like soft-edged portraits.

## Components

- **Buttons:** Primary buttons use a solid Gold fill with white text in `label-caps`. Secondary buttons use a Rose Pink outline with a subtle glassmorphic hover state.
- **Cards:** Service cards should be semi-transparent White with a 1px Blush Pink border. On hover, the Rose-tinted shadow increases in diffusion.
- **Input Fields:** Use the Soft Nude (#FDF5F6) for the fill. Borders should be invisible until focus, at which point they transition to a 1px Gold stroke.
- **Chips:** Used for "Service Categories" (e.g., Nails, Hair, Facial). These should be fully rounded (pill-shaped) with a Blush Pink background and Rose Pink text.
- **Navigation:** A top-sticky bar with a high backdrop-blur and a very thin Gold bottom border to separate it from the content without adding bulk.
- **Booking Modal:** A centered, large-radius card that utilizes a full-screen blurred background, focusing the user entirely on the appointment selection process.