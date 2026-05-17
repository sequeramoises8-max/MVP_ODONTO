---
name: Clinical Precision
colors:
  surface: '#faf8ff'
  surface-dim: '#d9d9e5'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3fe'
  surface-container: '#ededf9'
  surface-container-high: '#e7e7f3'
  surface-container-highest: '#e1e2ed'
  on-surface: '#191b23'
  on-surface-variant: '#434655'
  inverse-surface: '#2e3039'
  inverse-on-surface: '#f0f0fb'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#5c5f61'
  on-secondary: '#ffffff'
  secondary-container: '#e0e3e5'
  on-secondary-container: '#626567'
  tertiary: '#943700'
  on-tertiary: '#ffffff'
  tertiary-container: '#bc4800'
  on-tertiary-container: '#ffede6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#e0e3e5'
  secondary-fixed-dim: '#c4c7c9'
  on-secondary-fixed: '#191c1e'
  on-secondary-fixed-variant: '#444749'
  tertiary-fixed: '#ffdbcd'
  tertiary-fixed-dim: '#ffb596'
  on-tertiary-fixed: '#360f00'
  on-tertiary-fixed-variant: '#7d2d00'
  background: '#faf8ff'
  on-background: '#191b23'
  surface-variant: '#e1e2ed'
typography:
  display-xl:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-xl-mobile:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
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
  label-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
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
  gutter: 24px
  section-padding-v: 96px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system is anchored in the concept of "Human-Centric Clinical Excellence." It bridges the gap between medical authority and approachable care. The visual language avoids the sterile coldness of traditional clinics, instead favoring a modern, high-end hospitality aesthetic that reassures patients.

The style is **Corporate / Modern** with a strong leaning toward **Minimalism**. By prioritizing generous whitespace and a restricted, high-quality palette, the UI communicates transparency and cleanliness. High-resolution photography of real clinical environments and warm, professional portraits replace generic medical imagery to establish an immediate sense of trust and human connection.

## Colors

The palette is rooted in "Modern Dental Blue," a vibrant yet stable hue that symbolizes technology and health. 

- **Primary Blue:** Used for calls to action, active states, and key brand identifiers. It provides the "clinical" anchor.
- **Background Tones:** Pure White (#FFFFFF) is the primary canvas to ensure a feeling of sterility and light. Very Light Gray (#F7F9FB) is used for section differentiation and card backgrounds to prevent optical fatigue.
- **Typography:** Dark Gray (#1F2937) provides high-contrast legibility for headings, while Secondary Gray (#4B5563) is reserved for body copy and metadata to maintain a soft, welcoming hierarchy.

## Typography

This design system utilizes **Inter** for its systematic clarity and modern architectural feel. The typeface’s high x-height ensures exceptional readability, which is critical for patient trust.

The typographic scale is intentionally dramatic in the Hero section (`display-xl`) to create a high-end, editorial feel. As the user moves into informational sections, the scale settles into a highly legible, functional rhythm. Tighten letter spacing on larger headlines to maintain a cohesive, "premium" look.

## Layout & Spacing

The design system employs a **Fixed Grid** model for desktop to ensure content remains centered and easy to scan, transitioning to a fluid layout for mobile devices.

- **Desktop (1280px+):** 12-column grid with 24px gutters.
- **Tablet (768px - 1024px):** 8-column grid with 20px gutters.
- **Mobile (<768px):** 4-column grid with 16px gutters and 16px side margins.

Vertical rhythm is governed by a 4px/8px baseline. Use expansive section padding (96px+) to create "breathable" transitions between different service offerings, reinforcing the premium nature of the clinic.

## Elevation & Depth

To maintain a clean and professional look, depth is achieved through **Subtle Ambient Shadows** and **Tonal Layers**. 

Avoid heavy, dark shadows. Use a "Soft Lift" approach for interactive cards: a very low-opacity blue-tinted shadow (e.g., `rgba(37, 99, 235, 0.08)`) that expands slightly on hover. Tonal layering is used to separate the background from content: pure white cards should sit on the Very Light Gray secondary background to create a crisp, stacked hierarchy without relying on borders.

## Shapes

The shape language is defined by "Soft Precision." 

Standard UI elements like input fields and small buttons use a 0.5rem radius. However, major containers and cards use `rounded-2xl` (1rem to 1.5rem) to convey a modern, welcoming, and organic feel. This softening of the corners balances the "clinical" nature of the blue and the sharp Inter typography, making the interface feel more "human."

## Components

### Buttons
- **Primary:** Solid Modern Dental Blue with white text. Hover state involves a subtle darkening of the blue or a slight upward float with a more pronounced shadow.
- **Secondary:** Transparent background with a 1px border in Modern Dental Blue. 

### Cards
- White background, `rounded-2xl` corners, and a `shadow-sm`. Cards should have generous internal padding (min 32px) to keep content from feeling cramped.

### Badges & Chips
- Used for service categories or "New Patient" labels. Use a light blue tint background (10% opacity of Primary) with saturated blue text for high legibility and a professional, "badged" look.

### Input Fields
- Clean, 1px border in Light Gray. On focus, the border transitions to Primary Blue with a subtle outer glow.

### Service Lists
- Use custom medical icons (geometric, thin-line) instead of bullets. Icons should be housed in a small, rounded-square container with a light blue background.