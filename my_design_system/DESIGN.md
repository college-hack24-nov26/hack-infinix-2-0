---
name: My Design System
colors:
  surface: '#f3fcea'
  surface-dim: '#d4ddcb'
  surface-bright: '#f3fcea'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#edf7e4'
  surface-container: '#e8f1df'
  surface-container-high: '#e2ebd9'
  surface-container-highest: '#dce6d3'
  on-surface: '#161e13'
  on-surface-variant: '#3e4a38'
  inverse-surface: '#2a3327'
  inverse-on-surface: '#ebf4e1'
  outline: '#6e7b67'
  outline-variant: '#bdcbb4'
  surface-tint: '#026e00'
  primary: '#026e00'
  on-primary: '#ffffff'
  primary-container: '#29b91d'
  on-primary-container: '#014100'
  inverse-primary: '#58e245'
  secondary: '#296c1f'
  on-secondary: '#ffffff'
  secondary-container: '#a9f294'
  on-secondary-container: '#2e7023'
  tertiary: '#aa2c60'
  on-tertiary: '#ffffff'
  tertiary-container: '#ff6fa2'
  on-tertiary-container: '#710038'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#77ff61'
  primary-fixed-dim: '#58e245'
  on-primary-fixed: '#002200'
  on-primary-fixed-variant: '#015300'
  secondary-fixed: '#abf597'
  secondary-fixed-dim: '#90d87d'
  on-secondary-fixed: '#002200'
  on-secondary-fixed-variant: '#0b5306'
  tertiary-fixed: '#ffd9e2'
  tertiary-fixed-dim: '#ffb1c7'
  on-tertiary-fixed: '#3f001c'
  on-tertiary-fixed-variant: '#8a0f48'
  background: '#f3fcea'
  on-background: '#161e13'
  surface-variant: '#dce6d3'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '500'
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
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
---

# Design System

## Brand & Style
The design system adopts a **Modern / Corporate** style, balancing a fresh, nature-inspired palette with the clean, highly legible structure of the Inter typography family. It is engineered to evoke clarity, reliability, and eco-conscious innovation. The UI is designed to feel approachable yet precise, utilizing balanced whitespace, clear visual hierarchies, and natural color accents that inspire confidence and ease of use.

## Colors
The palette is rooted in vibrant, sustainable greens paired with a striking accent and grounded neutrals.
- **Primary (`#05a801`)**: A vibrant, energetic green used for primary actions, active states, and key interactive elements.
- **Secondary (`#438636`)**: An earthy, reliable deep green that supports hierarchy and structural elements.
- **Tertiary (`#ff6fa2`)**: A warm, contrasting pink/magenta accent used sparingly for calls to action, badges, and high-priority notifications.
- **Neutral (`#717a6b`)**: A balanced slate-olive neutral providing readability for text, borders, and subtle backgrounds.

## Typography
The typography system uses **Inter** exclusively across headlines, body text, and labels, ensuring a uniform, highly legible digital experience. Inter's exceptional legibility at small sizes and clean geometric forms at larger scales create a modern, professional typographic rhythm.

## Layout & Spacing
A flexible fluid grid system is utilized, featuring standard 16px (1rem) gutters and 24px (1.5rem) outer margins. Component spacing scales cleanly via a structured token set (`space-xs` to `space-xl`), ensuring consistent rhythm across form factors.

## Elevation & Depth
Visual hierarchy is achieved through a combination of subtle tonal layers and soft, diffused ambient shadows. Low-contrast outlines using the neutral color are employed for card borders and inputs to maintain a clean, modern aesthetic without heavy visual clutter.

## Shapes
The design system employs a **Rounded** shape language (`roundedness: 2`). Standard UI elements feature a baseline 0.5rem border radius, creating a friendly, accessible, and contemporary feel. Larger containers utilize `rounded-lg` (1rem) and `rounded-xl` (1.5rem).

## Components
- **Buttons**: Rounded (0.5rem radius) with primary green backgrounds (`#05a801`) and clear text labels using Inter. Hover and active states scale subtly.
- **Chips**: Compact tags utilizing neutral backgrounds or secondary green outlines for filtering and categorization.
- **Lists**: Clean vertical groupings with generous padding (`space-md`) and subtle dividers.
- **Checkboxes & Radio Buttons**: Custom-styled inputs featuring the primary green accent for selected states.
- **Input Fields**: Outlined containers with neutral borders, transitioning to primary green on focus, paired with clear Inter body text.
- **Cards**: Surface containers utilizing rounded corners (1rem) and low-contrast borders for gentle depth separation.