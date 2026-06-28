---
name: Neighborhood Reliability System
colors:
  surface: '#f8f9fb'
  surface-dim: '#d9dadc'
  surface-bright: '#f8f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f6'
  surface-container: '#edeef0'
  surface-container-high: '#e7e8ea'
  surface-container-highest: '#e1e2e4'
  on-surface: '#191c1e'
  on-surface-variant: '#444653'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f3'
  outline: '#757684'
  outline-variant: '#c4c5d5'
  surface-tint: '#3755c3'
  primary: '#00288e'
  on-primary: '#ffffff'
  primary-container: '#1e40af'
  on-primary-container: '#a8b8ff'
  inverse-primary: '#b8c4ff'
  secondary: '#0060ac'
  on-secondary: '#ffffff'
  secondary-container: '#64a8fe'
  on-secondary-container: '#003c70'
  tertiary: '#003272'
  on-tertiary: '#ffffff'
  tertiary-container: '#00489e'
  on-tertiary-container: '#9cbbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b8c4ff'
  on-primary-fixed: '#001453'
  on-primary-fixed-variant: '#173bab'
  secondary-fixed: '#d4e3ff'
  secondary-fixed-dim: '#a4c9ff'
  on-secondary-fixed: '#001c39'
  on-secondary-fixed-variant: '#004883'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#adc6ff'
  on-tertiary-fixed: '#001a42'
  on-tertiary-fixed-variant: '#004395'
  background: '#f8f9fb'
  on-background: '#191c1e'
  surface-variant: '#e1e2e4'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.1px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.5px
  button:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.1px
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
  2xl: 48px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 32px
---

## Brand & Style

The design system is engineered to project absolute reliability, neighborly warmth, and modern efficiency. It targets local homeowners and service providers who value professionalism over flair. 

The aesthetic is a refined evolution of **Corporate Modern** with **Minimalist** leanings, heavily influenced by Material Design 3. It utilizes high-quality whitespace to reduce cognitive load during the booking process. The visual narrative focuses on "clarity through structure," ensuring that every interaction feels intentional and secure. The UI evokes an emotional response of being "in good hands," balancing the mechanical precision of a utility app with the approachability of a local community tool.

## Colors

The palette is anchored by **Deep Trust Blue (#1E40AF)**, used for primary actions and brand-critical touchpoints to establish authority. **Sky Blue (#60A5FA)** serves as a supportive accent, providing a friendlier, more accessible contrast for informational elements and secondary highlights.

- **Primary:** High-contrast blue for key buttons, active states, and icons.
- **Secondary:** Softer blue for decorative elements, badges, and background tints.
- **Neutral/Surface:** A tiered system of grays starting from #FFFFFF for the base, moving to #F3F4F6 for secondary containers to create subtle depth without relying on heavy lines.
- **Semantic:** Success (Green), Warning (Amber), and Error (Red) should follow standard WCAG-compliant tones to maintain the professional utility of the system.

## Typography

This design system utilizes **Inter** exclusively to leverage its systematic, utilitarian nature. The typeface's tall x-height and excellent legibility make it ideal for data-dense service listings and mobile navigation.

- **Headlines:** Use Bold (700) and SemiBold (600) weights with slight negative letter-spacing for a modern, compact look.
- **Body:** Standardized at 16px for primary reading to ensure accessibility for a wide demographic of users.
- **Labels:** Used for status chips, categories, and overlines. These use slightly increased letter-spacing and Medium (500) or SemiBold (600) weights for quick scanning.

## Layout & Spacing

The design system employs a **Fluid Grid** model based on an 8pt rhythm. 

- **Mobile:** A 4-column layout with 16px margins and 16px gutters. Components should generally span the full width or 2 columns.
- **Desktop/Tablet:** A 12-column grid with a maximum content width of 1200px. Margins expand to 32px or 48px to maintain focus.
- **Rhythm:** Vertical spacing between unrelated sections should use `xl` (32px), while spacing between related elements within a card should use `sm` (8px) or `md` (16px).

## Elevation & Depth

Visual hierarchy is established using **Tonal Layers** and **Ambient Shadows**. This system avoids harsh borders in favor of soft, diffused shadows that simulate a natural light source from above.

- **Level 0 (Base):** #FFFFFF background.
- **Level 1 (Cards/Surface):** Subtle 1px border in #E5E7EB or a very low-offset shadow (Y: 2, Blur: 4, Opacity: 0.05).
- **Level 2 (Active/Hover):** Enhanced shadow (Y: 4, Blur: 12, Opacity: 0.1) to indicate interactivity.
- **Level 3 (Modals/Overlays):** Deep shadow (Y: 10, Blur: 25, Opacity: 0.15) to pull the element significantly forward.

Use background blurs (10px - 20px) for bottom navigation bars and top app bars to maintain context of the content scrolling beneath them.

## Shapes

The shape language is consistently **Rounded**, promoting a friendly and safe atmosphere. 

- **Containers/Cards:** Use `rounded-lg` (16px) to provide a soft, modern container for service provider information.
- **Buttons:** Use full pill-shaped rounding for primary calls to action to maximize "tapability" and visual distinction from other UI elements.
- **Inputs:** Use `rounded-md` (8px) for form fields to maintain a professional, structured appearance.
- **Icons:** Use a 2px stroke weight with rounded caps and joins to match the typography and container corner radii.

## Components

- **Service Cards:** Feature a 16px corner radius. They should include a top-aligned image, a SemiBold title, a star rating in Sky Blue, and a secondary text row for "Starting price" or "Location."
- **Prominent Action Buttons:** Fixed-height (48px or 56px), pill-shaped, using the Primary Blue background with white text. Provide a subtle scale-down effect (0.98) on press.
- **Search Bars:** Placed prominently at the top of the home screen, featuring a 12px radius, a magnifying glass icon, and a "Current Location" trailing action.
- **Status Timelines:** Use a vertical line (2px, Gray-200) with solid dots for completed steps and a Primary Blue pulse for the "Active" status.
- **Bottom Navigation:** Uses a clear background blur, centered labels in Label-MD, and a tinted Sky Blue background for the active icon state.
- **Chips/Badges:** Small, 8px rounded containers with low-opacity background tints (e.g., 10% Primary Blue) and high-contrast text for categories like "Plumbing" or "Emergency."
- **Input Fields:** Outlined style with a 1px border that thickens to 2px Primary Blue on focus. Labels should float or sit clearly above the input.