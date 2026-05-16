---
name: Voyager Standard
colors:
  surface: '#f9f9ff'
  surface-dim: '#cadaff'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e8edff'
  surface-container-high: '#e0e8ff'
  surface-container-highest: '#d7e2ff'
  on-surface: '#041b3c'
  on-surface-variant: '#434654'
  inverse-surface: '#1d3052'
  inverse-on-surface: '#edf0ff'
  outline: '#737685'
  outline-variant: '#c3c6d6'
  surface-tint: '#0c56d0'
  primary: '#003d9b'
  on-primary: '#ffffff'
  primary-container: '#0052cc'
  on-primary-container: '#c4d2ff'
  inverse-primary: '#b2c5ff'
  secondary: '#785900'
  on-secondary: '#ffffff'
  secondary-container: '#fdc003'
  on-secondary-container: '#6c5000'
  tertiary: '#004b59'
  on-tertiary: '#ffffff'
  tertiary-container: '#006477'
  on-tertiary-container: '#76e2ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2ff'
  primary-fixed-dim: '#b2c5ff'
  on-primary-fixed: '#001848'
  on-primary-fixed-variant: '#0040a2'
  secondary-fixed: '#ffdf9e'
  secondary-fixed-dim: '#fabd00'
  on-secondary-fixed: '#261a00'
  on-secondary-fixed-variant: '#5b4300'
  tertiary-fixed: '#afecff'
  tertiary-fixed-dim: '#48d7f9'
  on-tertiary-fixed: '#001f27'
  on-tertiary-fixed-variant: '#004e5d'
  background: '#f9f9ff'
  on-background: '#041b3c'
  surface-variant: '#d7e2ff'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 40px
  xl: 64px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style

The design system is engineered for a dual-purpose experience: high-stakes reliability during travel safety incidents and evocative, open-ended exploration during the planning phase. The aesthetic leans into **Corporate Modern** with **Minimalist** influences—prioritizing clarity, precision, and efficiency without feeling clinical.

The target audience consists of frequent travelers, digital nomads, and safety-conscious explorers who require information that is digestible at a glance, even in high-stress or low-light environments. The UI should evoke a sense of "organized adventure"—where every logistics detail is accounted for, allowing the user the mental freedom to explore.

Visual weight is distributed through purposeful whitespace and a rigorous grid, ensuring that "Safety" features feel authoritative and "Discovery" features feel inspiring.

## Colors

The palette is anchored by **Adventure Blue (#0052CC)**, a deep, trustworthy sapphire that signals stability and institutional knowledge. This is the primary color for navigation, primary actions, and branding.

**Map Yellow (#FFC107)** serves as the high-visibility accent. It is used sparingly for highlights, active map markers, and primary call-to-outs. It bridges the gap between utilitarian "caution" and sunny "exploration."

A tertiary **Cyan (#00B8D9)** is introduced for information-heavy elements like weather or water-related safety data. The neutral scale uses cool-toned slates to maintain a modern, technical feel, avoiding the "muddy" look of warm grays.

For safety statuses:
- **Critical:** #DE350B (Deep Red)
- **Warning:** #FF8B00 (Amber)
- **Safe:** #36B37E (Emerald)

## Typography

This design system utilizes a tiered typographic approach. **Plus Jakarta Sans** is used for headlines to provide a friendly, rounded, and modern entry point into the content. It balances the "technical" nature of the app with a more humanistic touch.

**Inter** is the workhorse for all body copy, data, and labels. Its high x-height and neutral grotesque style ensure maximum legibility when reading travel alerts or itinerary details on the move. 

Key Rules:
- Use **Display-LG** only for marketing or landing states.
- Use **Label-MD** in uppercase for category headers and status indicators to create a clear visual distinction from body text.
- Tighten letter spacing on headlines to maintain a cohesive, "premium" feel.

## Layout & Spacing

The system follows a strict **8px square grid** to maintain alignment across varied components. 

- **Mobile:** 4-column fluid grid with 16px margins. Components should stack vertically, using full-width cards for itinerary items.
- **Desktop:** 12-column fixed grid (max-width 1280px) with 48px margins. The layout should utilize a "Master-Detail" pattern, where the left 4 columns contain lists or navigation, and the right 8 columns contain map views or deep-dive details.

Padding within cards and containers should remain generous (24px) to avoid visual clutter in data-dense areas like "Emergency Information."

## Elevation & Depth

Visual hierarchy is achieved through **Tonal Layers** and **Ambient Shadows**. 

1. **Background (Level 0):** Pure white (#FFFFFF) or very light cool gray (#F4F5F7).
2. **Cards & Containers (Level 1):** Raised by a subtle, extra-diffused shadow (Blur: 12px, Y: 4px, Color: Primary Blue at 5% opacity). This "tinted shadow" creates a more cohesive, branded feel than neutral gray shadows.
3. **Overlays & Drawers (Level 2):** High-diffusion shadow (Blur: 24px, Y: 8px, Color: Primary Blue at 10% opacity).

Maps should be treated as the bottom-most layer, with UI controls appearing as floating "islands" with high elevation to indicate they are interactive elements on top of the environment.

## Shapes

The design system uses a **Rounded (8px)** corner radius for standard UI elements (buttons, inputs, cards). This radius provides a modern, approachable feel that is softer than sharp corners but more professional than pill-shaped elements.

- **Standard Buttons/Inputs:** 8px (0.5rem)
- **Large Cards/Modals:** 16px (1rem)
- **Status Badges/Chips:** Full pill-shaped (999px) to distinguish them from interactive buttons.

This geometric consistency ensures that even when the content is dense, the interface feels cohesive and intentionally designed.

## Components

### Buttons
- **Primary:** Solid Adventure Blue with white text. 8px radius. High contrast.
- **Secondary:** Outlined Adventure Blue with 2px stroke.
- **Emergency Action:** Solid Red (#DE350B) with white text and a subtle pulse animation for high-urgency states.

### Cards
- **Itinerary Card:** Uses a left-border accent color to denote the category (e.g., Yellow for transport, Blue for stay).
- **Emergency Information Card:** Features a thick 4px top border in Red and utilizes `headline-md` for the most critical contact info.

### Status Badges & Chips
- Use the pill-shape.
- Backgrounds are 10% opacity of the status color with 100% opacity text of the same color (e.g., Light green background with dark green text for "Safe").

### Maps & Markers
- Custom map styling using desaturated cool tones to allow the **Map Yellow** markers to pop.
- Collaborative markers feature a small avatar ring for shared planning.

### Lists
- **Collaborative Lists:** Include "Presence Indicators" (small 8px dots) to show who is currently viewing or editing a specific item.
- **Checkbox:** Large 24x24px touch targets with a "tick" that animates in Adventure Blue when selected.

### Input Fields
- Floating labels using `label-sm`. 
- 2px border on focus in Adventure Blue. 
- Error states clearly defined with Red text and an icon.