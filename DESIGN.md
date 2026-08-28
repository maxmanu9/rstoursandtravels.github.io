---
name: Saffron & Sage Luxury
colors:
  surface: '#faf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#faf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeeb'
  surface-container-high: '#e9e8e5'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1a'
  on-surface-variant: '#564337'
  inverse-surface: '#2f312f'
  inverse-on-surface: '#f2f1ee'
  outline: '#897365'
  outline-variant: '#dcc1b1'
  surface-tint: '#944a00'
  primary: '#944a00'
  on-primary: '#ffffff'
  primary-container: '#e67e22'
  on-primary-container: '#502600'
  inverse-primary: '#ffb783'
  secondary: '#4d6453'
  on-secondary: '#ffffff'
  secondary-container: '#cde6d1'
  on-secondary-container: '#516857'
  tertiary: '#8d4f11'
  on-tertiary: '#ffffff'
  tertiary-container: '#d38847'
  on-tertiary-container: '#4e2700'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcc5'
  primary-fixed-dim: '#ffb783'
  on-primary-fixed: '#301400'
  on-primary-fixed-variant: '#713700'
  secondary-fixed: '#d0e9d4'
  secondary-fixed-dim: '#b4cdb8'
  on-secondary-fixed: '#0b2013'
  on-secondary-fixed-variant: '#364c3c'
  tertiary-fixed: '#ffdcc3'
  tertiary-fixed-dim: '#ffb77d'
  on-tertiary-fixed: '#2f1500'
  on-tertiary-fixed-variant: '#6e3900'
  background: '#faf9f6'
  on-background: '#1a1c1a'
  surface-variant: '#e3e2e0'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

The design system is rooted in the concept of **Warm Minimalism**—a modern luxury travel aesthetic that balances the raw, sun-baked textures of nature with a sophisticated, editorial lens. It aims to evoke feelings of tranquility, exclusivity, and warmth, inviting the user to step into a curated travel experience.

The visual direction draws heavily from "Golden Hour" photography. It utilizes heavy whitespace to create a sense of breathability and calm, paired with rich, organic color accents. The personality is professional and high-end, yet remains approachable through its use of soft corners and natural color palettes.

## Colors

The palette is extracted from the natural elements of a luxury coastal or villa retreat. 

- **Primary (Sun-Baked Orange):** Used for primary calls to action and highlights, representing the warmth of the sun.
- **Secondary (Forest Green):** A deep, near-black green used for text, navigation, and grounding elements to represent lush landscapes.
- **Tertiary (Golden Sand):** Used for accents, secondary buttons, and subtle hover states.
- **Neutral (Parchment):** A warm off-white used for backgrounds to avoid the harshness of pure white and maintain the "warm" narrative.
- **Semantic Colors:** Success (Soft Sage), Warning (Amber), and Error (Cotta) should be desaturated to fit the organic theme.

## Typography

The typography strategy employs a classic "Serif for display, Sans for utility" pairing. 

- **Display & Headlines:** Use **Playfair Display**. It provides the high-end editorial feel necessary for a luxury travel brand. Tighten letter-spacing slightly for larger displays to create a more customized, premium look.
- **Body & Interface:** Use **DM Sans**. This geometric sans-serif offers exceptional clarity and a clean modernism that contrasts beautifully with the serif headlines.
- **Hierarchy:** Ensure a clear distinction between the expressive, storytelling headlines and the functional, readable body text.

## Layout & Spacing

This design system uses a **Fluid Grid** approach with generous margins to reinforce the feeling of space and luxury. 

- **Desktop:** A 12-column grid with a 1280px max-width container. Use large vertical margins (80px–120px) between sections to allow the eye to rest.
- **Tablet:** 8-column grid with 40px margins.
- **Mobile:** 4-column grid with 20px margins. 
- **Rhythm:** All spacing (padding, margins, gap) should be multiples of 8px. Use larger gaps (32px+) for layout elements and smaller gaps (8px-16px) for component internals.

## Elevation & Depth

Depth is conveyed through a combination of **Tonal Layers** and **Ambient Shadows**. 

- **Surface Strategy:** Use the Neutral (Parchment) as the base. Elevated elements like cards or modals should use a pure white background to subtly pop against the parchment base.
- **Shadows:** Shadows must be extremely soft and diffused, mimicking natural ambient light. Use a multi-layered shadow approach with low opacity (3-5%) and large blur radii (20px+) to avoid a "digital" look.
- **Interactive Depth:** On hover, buttons and cards should subtly lift using a slightly more pronounced shadow rather than a heavy color shift.

## Shapes

The shape language is defined by "Softened Geometry." 

- **Core Radius:** Use a base radius of 12px-16px for primary containers and cards. This removes the clinical feel of sharp corners while maintaining a modern structure.
- **Interactive Elements:** Buttons should carry a slightly more pronounced radius (up to pill-shaped for secondary actions) to make them feel tactile and inviting.
- **Media:** Photography should always feature the standard 16px corner radius to blend seamlessly into the layout.

## Components

### Buttons
- **Primary:** Solid Sun-Baked Orange with white text. High-contrast, 16px rounded corners, with a subtle "lift" shadow on hover.
- **Secondary/Ghost:** Deep Forest Green border (1px) with transparent background and Forest Green text. Used for less urgent actions.

### Input Fields
- Use a soft off-white background with a subtle 1px border in a muted green-grey. Labels should use the **label-md** style (uppercase DM Sans) for a professional, form-like appearance.

### Cards
- Cards are the primary storytelling vehicle. Use white backgrounds, 16px corner radii, and ample internal padding (32px). Images within cards should bleed to the top and sides with rounded top corners.

### Chips & Tags
- Used for travel categories (e.g., "Villas", "Safari"). Small, pill-shaped elements with a light Forest Green tint background and dark green text.

### Navigation
- A clean, transparent header that transitions to a solid Parchment background on scroll. Links use **label-md** with a subtle underline effect for the active state.