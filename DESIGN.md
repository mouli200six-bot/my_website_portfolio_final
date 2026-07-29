---
name: Academic Clarity
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#43474e'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#476083'
  primary: '#000613'
  on-primary: '#ffffff'
  primary-container: '#001f3f'
  on-primary-container: '#6f88ad'
  inverse-primary: '#afc8f0'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fd8b00'
  on-secondary-container: '#603100'
  tertiary: '#040607'
  on-tertiary: '#ffffff'
  tertiary-container: '#1c1f21'
  on-tertiary-container: '#848789'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d4e3ff'
  primary-fixed-dim: '#afc8f0'
  on-primary-fixed: '#001c3a'
  on-primary-fixed-variant: '#2f486a'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#e0e3e5'
  tertiary-fixed-dim: '#c4c7c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: 0.02em
  display-mobile:
    fontFamily: Geist
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.01em
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  label-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
    letterSpacing: '0'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
  section-gap-lg: 120px
  section-gap-md: 80px
---

## Brand & Style

This design system is engineered for the modern student portfolio, prioritizing clarity, professional confidence, and a focus on content. The brand personality is rooted in high-performance minimalism: it is clean enough to stay out of the way of the work, yet sophisticated enough to command respect from recruiters and collaborators.

The visual style is **Corporate Modern with Minimalist influences**. It leverages generous white space to create a "gallery" feel, ensuring that project thumbnails and case studies have room to breathe. The emotional response should be one of reliability and organized intelligence. Interactions should feel intentional and smooth, avoiding excessive decoration in favor of structural integrity.

## Colors

The palette is anchored by **Deep Navy**, used for high-level branding, primary navigation, and headings to establish authority. **Pure White** serves as the primary canvas, maximizing contrast and legibility. 

**Warm Orange** is used exclusively as an action color—reserved for call-to-action buttons, active states, and critical highlights—to guide the eye toward conversion points without overwhelming the professional tone. **Very Light Gray** (Surface) provides subtle containment for secondary information and card backgrounds, creating a soft hierarchy against the pure white page.

## Typography

The typography system uses a pairing of **Geist** for structural elements and **Inter** for reading experiences. Headlines are bold and feature increased letter spacing to enhance the modern, architectural feel of the layout. 

Body text utilizes Inter at a generous 1.6 line-height to maintain a conversational and approachable tone. All labels and metadata use Geist in a slightly heavier weight and uppercase styling to provide clear signposting throughout the portfolio.

## Layout & Spacing

This design system employs a **fixed-center grid** for desktop to ensure readability, transitioning to a fluid system for mobile devices. 

- **Desktop (1200px+):** A 12-column grid with 24px gutters. Large vertical gaps (120px) separate major content sections to prevent visual clutter.
- **Tablet:** An 8-column grid with 20px gutters. Vertical gaps reduce to 80px.
- **Mobile:** A 4-column fluid grid with 16px margins. 

Spacing is based on an 8px baseline rhythm. Padding within cards and containers should be generous (typically 32px or 40px) to maintain the minimalist aesthetic.

## Elevation & Depth

Depth is achieved through **low-contrast outlines** and **ambient shadows**. 

- **Level 0 (Base):** Pure White background.
- **Level 1 (Cards/Surface):** Very Light Gray (#F8FAFC) background with a 1px border in a slightly darker neutral (#E2E8F0).
- **Level 2 (Hover/Active):** When a user interacts with a project card, apply a soft, diffused shadow (0px 10px 25px rgba(0, 31, 63, 0.05)) and a subtle scale transform (1.02x) to provide tactile feedback.

Avoid heavy shadows; the goal is a "floating" effect that feels light and digital.

## Shapes

The design system uses a **Rounded** shape language to soften the professional Navy and Geist typography. 

- **Standard Buttons & Inputs:** 8px (0.5rem) corner radius.
- **Project Cards:** 16px (1rem) corner radius for a more substantial, friendly feel.
- **Tags/Chips:** Fully rounded (pill-shaped) to distinguish them from interactive buttons.

Consistent rounding across all components reinforces the approachable, student-focused nature of the brand.

## Components

### Buttons
- **Primary:** Deep Navy background, White text. 8px radius. High-contrast and authoritative.
- **Accent:** Warm Orange background, White text. Used for "Hire Me" or "View Project" actions.
- **Ghost:** Transparent background with a 1px Navy border. Used for secondary actions.

### Cards
Cards are the primary vehicle for projects. They should feature a Very Light Gray background, 16px corner radius, and a subtle transition on hover that lifts the card and deepens the border color slightly.

### Chips & Tags
Used for skills or software (e.g., "Figma", "Python"). Use a pill shape with a very light tint of the primary color and Navy text at the `label-md` size.

### Input Fields
Minimalist styling with a 1px border. On focus, the border should transition to Warm Orange with a soft glow to indicate activity.

### Lists
Project lists should be clean, using `body-md` for descriptions and `headline-md` for titles, with ample vertical padding between items to avoid a "dense" look.