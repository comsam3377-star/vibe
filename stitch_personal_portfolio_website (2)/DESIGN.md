---
name: Terra & Cream Portfolio
colors:
  surface: '#fdf9f4'
  surface-dim: '#ddd9d5'
  surface-bright: '#fdf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ee'
  surface-container: '#f1ede8'
  surface-container-high: '#ebe8e3'
  surface-container-highest: '#e6e2dd'
  on-surface: '#1c1c19'
  on-surface-variant: '#54433f'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f4f0eb'
  outline: '#87726e'
  outline-variant: '#dac1bc'
  surface-tint: '#944936'
  primary: '#702e1d'
  on-primary: '#ffffff'
  primary-container: '#8e4432'
  on-primary-container: '#ffc3b5'
  inverse-primary: '#ffb4a3'
  secondary: '#6a5c4c'
  on-secondary: '#ffffff'
  secondary-container: '#f3dfcb'
  on-secondary-container: '#706252'
  tertiary: '#543d37'
  on-tertiary: '#ffffff'
  tertiary-container: '#6d544d'
  on-tertiary-container: '#eccac1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad2'
  primary-fixed-dim: '#ffb4a3'
  on-primary-fixed: '#3c0700'
  on-primary-fixed-variant: '#763221'
  secondary-fixed: '#f3dfcb'
  secondary-fixed-dim: '#d6c4b0'
  on-secondary-fixed: '#231a0e'
  on-secondary-fixed-variant: '#514536'
  tertiary-fixed: '#fedbd2'
  tertiary-fixed-dim: '#e0bfb7'
  on-tertiary-fixed: '#291712'
  on-tertiary-fixed-variant: '#59413b'
  background: '#fdf9f4'
  on-background: '#1c1c19'
  surface-variant: '#e6e2dd'
typography:
  display:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Source Serif 4
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Source Serif 4
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.05em
  caption:
    fontFamily: Source Serif 4
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  stack-sm: 16px
  stack-md: 32px
  stack-lg: 80px
---

## Brand & Style
The design system is centered on the concept of **"Warm Minimalism."** It targets a professional audience that values human connection, organic growth, and approachable expertise. The emotional goal is to feel like a well-lit studio: calm, curated, and inviting rather than cold or institutional.

The style blends **Minimalism** with **Tactile** warmth. It avoids the harshness of pure white (#FFFFFF) in favor of layered creams. It prioritizes heavy whitespace to allow creative work to breathe, but uses soft depth and organic curves to ensure the interface feels "held" and intentional.

## Colors
This design system utilizes a palette inspired by natural pigments and clay.

*   **Primary (#8E4432 - Terracotta):** Used for call-to-action elements, active states, and high-impact accents. It provides the "warmth" in the professional narrative.
*   **Secondary (#EAD7C3 - Soft Sand):** Used for large surface areas, secondary buttons, and subtle component backgrounds to differentiate from the main page background.
*   **Tertiary (#4A342E - Chocolate Brown):** Reserved for high-contrast text and grounding elements. It replaces pure black to maintain the organic feel.
*   **Neutral (#F9F5F0 - Cream):** The base background color for all pages. It is softer on the eyes than pure white and reinforces the tactile, paper-like quality of the brand.

## Typography
The typography system pairs the geometric clarity of **Montserrat** for structural elements with the literary elegance of **Source Serif 4** for long-form content.

*   **Headlines:** Montserrat is used in medium to bold weights. The letter spacing is slightly tightened in larger sizes to create a modern, "designed" look.
*   **Body:** Source Serif 4 provides a sophisticated, scholarly feel to case studies and bios. It is highly legible and adds the "expertise" layer to the "approachable" brand.
*   **Labels:** Use all-caps Montserrat for small labels or category tags to create a clear visual hierarchy against serif body text.

## Layout & Spacing
The design system employs a **Fixed Grid** on desktop and a **Fluid Grid** on mobile.

*   **Desktop:** Content is centered within a 1200px container. Large vertical gaps (80px+) are encouraged between sections to maintain a sense of "warm minimalism" and avoid clutter.
*   **Mobile:** 4-column layout with 20px side margins. Typography scales down (see `headline-lg-mobile`) to ensure titles do not break awkwardly.
*   **Rhythm:** All spacing is based on an 8px modular scale. Components should lean toward generous internal padding (e.g., 24px or 32px) to feel soft and accessible.

## Elevation & Depth
In this design system, depth is achieved through **Tonal Layers** and **Ambient Shadows** rather than sharp borders.

*   **The Surface Hierarchy:**
    1.  Base: `Neutral` (#F9F5F0)
    2.  Raised: `Secondary` (#EAD7C3) or white with a very soft shadow.
*   **Shadows:** Use extremely diffused, low-opacity shadows with a hint of the primary color (e.g., `rgba(142, 68, 50, 0.05)`). Shadows should feel like a soft glow or a natural lift off the page, never heavy or grey.
*   **Outlines:** Avoid high-contrast borders. If a boundary is needed, use a 1px stroke in a color only slightly darker than the surface it sits on.

## Shapes
The shape language is "Pronounced Softness." 

*   **Standard Elements:** Buttons, inputs, and small cards use an 8px radius (0.5rem).
*   **Large Containers:** Feature cards and image containers use a 16px radius (1rem) to emphasize the friendly, organic nature of the brand.
*   **Interactive Elements:** Hover states may include a slight increase in "lift" (shadow depth) rather than a change in shape.

## Components
Consistent implementation of these components ensures the "Warm Minimalism" aesthetic is maintained:

*   **Buttons:** 
    *   *Primary:* Solid Terracotta with White or Cream text. Rounded 8px.
    *   *Secondary:* Transparent with a 1px Terracotta border or solid Sand (#EAD7C3) background with Chocolate Brown text.
*   **Cards:** Use a white or Sand background with a 16px corner radius and a soft ambient shadow. Keep internal padding at 32px to ensure content doesn't feel cramped.
*   **Input Fields:** Use a subtle Sand background instead of a white one. The focus state should be a 2px Terracotta bottom-border or a soft inner glow.
*   **Chips/Tags:** Rounded-pill shapes using the Secondary color and 12px Montserrat Bold text.
*   **Lists:** For portfolio "process" lists, use large, low-opacity Terracotta numbers as icons to guide the user through the narrative.
*   **Navigation:** Minimalist top bar with a centered logo. Navigation links should use Montserrat Medium with a 2px underline appearing on hover in the Primary color.