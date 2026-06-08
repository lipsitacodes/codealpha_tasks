---
name: Warm Hospitality Delivery
colors:
  surface: '#fff8f6'
  surface-dim: '#eed5cd'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff1ed'
  surface-container: '#ffe9e3'
  surface-container-high: '#fde3db'
  surface-container-highest: '#f7ddd5'
  on-surface: '#261814'
  on-surface-variant: '#594139'
  inverse-surface: '#3c2d28'
  inverse-on-surface: '#ffede8'
  outline: '#8d7168'
  outline-variant: '#e1bfb5'
  surface-tint: '#ab3500'
  primary: '#ab3500'
  on-primary: '#ffffff'
  primary-container: '#ff6b35'
  on-primary-container: '#5f1900'
  inverse-primary: '#ffb59d'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e4e2e1'
  on-secondary-container: '#656464'
  tertiary: '#00677e'
  on-tertiary: '#ffffff'
  tertiary-container: '#00a7cb'
  on-tertiary-container: '#003744'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd0'
  primary-fixed-dim: '#ffb59d'
  on-primary-fixed: '#390c00'
  on-primary-fixed-variant: '#832600'
  secondary-fixed: '#e4e2e1'
  secondary-fixed-dim: '#c8c6c6'
  on-secondary-fixed: '#1b1c1c'
  on-secondary-fixed-variant: '#474747'
  tertiary-fixed: '#b5ebff'
  tertiary-fixed-dim: '#59d5fb'
  on-tertiary-fixed: '#001f28'
  on-tertiary-fixed-variant: '#004e60'
  background: '#fff8f6'
  on-background: '#261814'
  surface-variant: '#f7ddd5'
typography:
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  container-margin: 20px
  gutter: 16px
---

## Brand & Style
The design system focuses on a **Friendly Modernism** style, blending the approachability of soft, rounded shapes with the efficiency of a high-performance delivery service. The brand personality is "The Helpful Neighbor": energetic, reliable, and warm. 

The aesthetic avoids the sterile look of traditional logistics apps by utilizing a cream-based background and high-energy accent colors. It aims to evoke an emotional response of hunger and excitement while maintaining a sense of professional trustworthiness. Visuals are clean but tactile, using soft depth to make elements feel "plump" and interactive.

## Colors
The palette is anchored by **Primary Orange (#FF6B35)**, a high-arousal color intended to stimulate appetite and signal speed. **Charcoal (#2D2D2D)** provides the necessary grounding for typography and high-contrast iconography, ensuring legibility and a sense of "premium" service. 

The **Cream Background (#FFF8F0)** acts as a soft canvas that feels more appetizing and premium than pure white, while **Pure White (#FFFFFF)** is reserved strictly for interactive cards and surfaces to create clear visual separation. **Accent Yellow (#FFD93D)** is used sparingly for promotional highlights, ratings, and "joy" moments like successful order completions.

## Typography
This design system uses **Plus Jakarta Sans** for headings to provide a modern, friendly, and slightly rounded geometric feel that aligns with the brand's warmth. **Be Vietnam Pro** is used for body copy and labels to ensure maximum legibility and a contemporary, professional tone at smaller sizes.

- **Headings:** Use bold weights to establish a clear hierarchy. Tighten letter-spacing slightly on larger displays to maintain a punchy, editorial look.
- **Body:** Standardized at 14px for density without sacrificing readability on mobile devices.
- **Labels:** Use medium or semi-bold weights for navigation and small metadata like "Estimated Delivery Time" or "Calories."

## Layout & Spacing
The layout follows a **Fluid Grid** model optimized for a 390px mobile frame. It uses a 4-column system for mobile and a 12-column system for desktop.

- **Margins:** A standard 20px "safe area" margin is applied to the left and right of the viewport.
- **Rhythm:** An 8px linear scale (4, 8, 16, 24, 32) governs all padding and margins. 
- **Stacking:** Use 16px (md) spacing between related items in a list (e.g., restaurant cards) and 24px (lg) spacing between distinct sections (e.g., "Featured" vs "All Restaurants").
- **Verticality:** Content should prioritize vertical scrolling with horizontal "overflow" carousels used for category chips and "Recommended" items to maximize screen real estate.

## Elevation & Depth
The design system utilizes **Ambient Shadows** and **Tonal Layering** to create a sense of physical space. 

- **Level 0 (Background):** The Cream surface (#FFF8F0).
- **Level 1 (Cards/Surfaces):** Pure White (#FFFFFF) with a soft shadow: `0px 2px 8px rgba(0, 0, 0, 0.08)`. This creates a subtle lift that suggests the card is hovering just above the background.
- **Level 2 (Interactive/Floating):** Used for "Add to Cart" sticky bars or floating action buttons. This uses a slightly more aggressive shadow: `0px 8px 24px rgba(0, 0, 0, 0.12)` to indicate higher priority and physical proximity to the user.
- **Depth Cues:** Background blurs (15px-20px) are used behind fixed navigation headers to maintain context of the content being scrolled underneath.

## Shapes
The shape language is defined by extreme **Roundedness** to reinforce the "friendly" and "fast" brand pillars. 

- **Cards & Modals:** Use a 16px radius. This is soft enough to feel approachable but structured enough to hold high-density information like restaurant menus.
- **Buttons & Chips:** Use a **Pill (999px)** radius. This shape is used exclusively for primary actions and filtering, making them easily identifiable and "tappable" targets.
- **Images:** All food photography should use the 16px radius to match the container, ensuring a unified and polished look.

## Components
Consistent component behavior is critical for building user trust during the fast-paced ordering process.

- **Buttons:** 
    - *Primary:* Pill-shaped, Primary Orange background, White text. High-shadow on hover/press.
    - *Secondary:* Pill-shaped, White background with Charcoal border or Charcoal text.
- **Chips:** Small pill-shaped containers used for tags like "Free Delivery" or "Under 30 mins." Use light-tinted backgrounds (e.g., 10% opacity of Primary Orange) with dark text.
- **Input Fields:** 12px rounded corners (slightly sharper than cards for precision). Use a subtle 1px border (#E0E0E0) that changes to Primary Orange on focus.
- **Cards:** The workhorse of the UI. Must include the standard 16px radius and Level 1 shadow. Content should be padded with 16px internally.
- **Quantity Pickers:** Use a rounded rectangle with +/- icons. Ensure the "hit area" is at least 44x44px for easy thumb interaction.
- **Trackers:** Use a horizontal line with pill-shaped progress indicators to visualize the order status (Preparing, Out for Delivery, Arrived).