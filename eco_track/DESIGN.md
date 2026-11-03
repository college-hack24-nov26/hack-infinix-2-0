---
name: Eco Track
colors:
  surface: '#101417'
  surface-dim: '#101417'
  surface-bright: '#36393d'
  surface-container-lowest: '#0b0f12'
  surface-container-low: '#191c1f'
  surface-container: '#1d2023'
  surface-container-high: '#272a2e'
  surface-container-highest: '#323539'
  on-surface: '#e0e2e7'
  on-surface-variant: '#bfc8cf'
  inverse-surface: '#e0e2e7'
  inverse-on-surface: '#2d3134'
  outline: '#899298'
  outline-variant: '#3f484e'
  surface-tint: '#7fd0fb'
  primary: '#7fd0fb'
  on-primary: '#003548'
  primary-container: '#449ac2'
  on-primary-container: '#002e3f'
  inverse-primary: '#006688'
  secondary: '#adcbde'
  on-secondary: '#153443'
  secondary-container: '#2d4a5a'
  on-secondary-container: '#9bb9cc'
  tertiary: '#ffb86a'
  on-tertiary: '#492900'
  tertiary-container: '#c48335'
  on-tertiary-container: '#3f2300'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c2e8ff'
  primary-fixed-dim: '#7fd0fb'
  on-primary-fixed: '#001e2b'
  on-primary-fixed-variant: '#004d67'
  secondary-fixed: '#c8e7fa'
  secondary-fixed-dim: '#adcbde'
  on-secondary-fixed: '#001e2c'
  on-secondary-fixed-variant: '#2d4a5a'
  tertiary-fixed: '#ffdcbc'
  tertiary-fixed-dim: '#ffb86a'
  on-tertiary-fixed: '#2c1700'
  on-tertiary-fixed-variant: '#683d00'
  background: '#101417'
  on-background: '#e0e2e7'
  surface-variant: '#323539'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 3rem
    fontWeight: '800'
    lineHeight: 3.5rem
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '800'
    lineHeight: 2.75rem
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 2rem
    fontWeight: '700'
    lineHeight: 2.5rem
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.5rem
    fontWeight: '700'
    lineHeight: 2rem
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.01em
  metric-value:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2rem
    letterSpacing: -0.02em
  body-lg:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-md:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.375rem
  body-sm:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '400'
    lineHeight: 1.125rem
  label-md:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 0.6875rem
    fontWeight: '700'
    lineHeight: 0.875rem
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-tablet: 1.5rem
  margin: 1rem
  margin-tablet: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system is engineered for utility-scale environmental monitoring and smart resource management within dynamic Indian municipal, commercial, and residential IoT contexts. It marries ecological clarity with uncompromising precision, instilling instantaneous trust and data confidence.

The visual style blends crisp modern minimalism with soft tactile layering and subtle glassmorphic telemetry badges. It embraces a sophisticated dark-mode-first aesthetic with surgical ocean blues, slate neutrals, and earthy amber highlights against deep functional backgrounds. The aesthetic communicates real-time environmental consciousness, technical reliability, and effortless metric consumption under challenging lighting conditions.

## Colors

The palette establishes an immediate relationship between technology and environmental data:

- **Primary Ocean (`#2080A7` / `#1279A0`)**: Grounded, authoritative technical precision. Represents active monitoring, optimal efficiency, and affirmative confirmation.
- **Secondary Slate (`#5E7B8C`)**: Balanced accent for visual anchors, state highlights, and low-stress status cues.
- **Metric Accents**: Distinct functional identifiers for resource silos:
  - **Water / Grid Telemetry (`#2080A7`)**: Deep cyan & cerulean for fluid tracking and pressure levels.
  - **Power & Grid Load (`#9E6316`)**: Amber for kilowatt consumption, peak tariffs, and warning thresholds.
  - **Air Quality & Particulate Index (`#5E7B8C`)**: Muted slate for AQI ranges (PM2.5, PM10) and chemical monitoring.
  - **Critical Alert (`#EF4444`)**: Immediate red for burst lines, hazardous surges, or contamination leaks.
- **Surfaces & Neutrals**:
  - `Canvas`: Dark surgical slate `#0B0F19` to isolate visual heat.
  - `Card / Surface`: Elevated dark slate `#111827`.
  - `Divider / Border`: Subdued dark border `#334155`.
  - `Text Primary`: Crisp high-contrast light text `#F8FAFC`.
  - `Text Secondary / Label`: Muted slate `#94A3B8`.

## Typography

The type system balances the friendly, human-centric geometry of **Plus Jakarta Sans** for headers, visual titles, and telemetry counters with the industrial, utilitarian clarity of **Inter** for dense sensor feeds and micro-labels.

All dynamic numbers (kilowatt hours, cubic meters, AQI scores, particulate parts-per-million) must enforce tabular figures (`font-variant-numeric: tabular-nums`) to prevent horizontal jitter during live telemetry polling. All tracking indicators and units (kWh, kL, µg/m³) utilize uppercase `label-sm` with widened letter-spacing for glanceable parsing in mobile field conditions.

## Layout & Spacing

A 4-column fluid mobile grid scaling to an 8-column layout on tablets and foldables ensures high data density without crowding. The core canvas maintains a strict baseline unit of 4px.

- **Mobile (<640px)**: Outer margin is fixed at `1rem` (16px) to maximize horizontal data footprint for dual-column resource metric widgets. Row gap between telemetry modules defaults to `1rem`.
- **Tablet / Large Foldable (>=640px)**: Margins expand to `2rem` (32px) with `1.5rem` gutters, transforming vertical feed cards into a side-by-side split screen (e.g., Live Utility Map adjacent to Real-time consumption stream).
- **Safe Area Padding**: The bottom navigation container preserves a 24px clearance above system home indicators to prevent misclicks on critical actions.

## Elevation & Depth

Visual hierarchy uses dark tonal surface layering combined with ambient illumination to create depth in low-light environments, maintaining precise contrast across all telemetry tiles and floating HUDs.

1. **Floor Level (Canvas)**: Background tint `#0B0F19` establishes physical distance beneath cards.
2. **Surface Tier (Cards & Dashboard Tiles)**: `#111827` resting with low-stress ambient shadows: `box-shadow: 0 4px 20px -2px rgba(0, 0, 0, 0.4)`. Borders utilize a subtle hairline boundary: `1px solid rgba(51, 65, 85, 0.8)`.
3. **Glassmorphic Overlays (Pills, Chips, Floating HUDs)**: Background of `rgba(17, 24, 39, 0.85)` with `backdrop-filter: blur(12px)` and a crisp hairline inner border `1px solid rgba(255, 255, 255, 0.1)`. Used exclusively for real-time status pills ("Active Sensor", "Connected").
4. **Interactive Action Tiers (Modals & Bottom Sheets)**: Soft ambient lift: `box-shadow: 0 20px 25px -5px rgba(32, 128, 167, 0.15)`.

## Shapes

The geometric silhouette relies on generous, ergonomic curvatures (`roundedness: 2` with extended tier scaling) to soften technical telemetry and invite interaction:

- **Metrics & Telemetry Cards**: Styled with `rounded-2xl` (1rem / 16px) or `rounded-3xl` (1.5rem / 24px) to evoke an organic, modern appliance hardware aesthetic.
- **Pills, Chips & Floating Status Indicators**: Fully rounded capsules (`rounded-full` / 9999px) to preserve visual contrast against rectilinear charts.
- **Buttons & Control Inputs**: `rounded-xl` (0.75rem / 12px) for consistent thumb reach and tactile tap targets.

## Components

### Buttons
- **Primary Action**: Solid `#2080a7` fill, white `#FFFFFF` text, `font-semibold`, height `48px`, `rounded-xl`. Active tap states depress smoothly with a slight scale transition (`scale: 0.98`).
- **Secondary Utility**: Slate tinted container, text `#2080a7`, zero border, height `48px`.
- **Tertiary / Ghost**: Transparent container, `#F8FAFC` text, subtle slate hover/touch highlight.

### Telemetry Cards
- Encased in dark surface `#111827` with `rounded-2xl` and 1px border `#334155`.
- Top-right corner houses live pulse indicators (a continuous 8px pulsating dot indicating hardware ping).
- Metrics display primary numeric figures in tabular `Plus Jakarta Sans` followed by secondary muted unit labels (`kWh`, `Liters`).

### Sensor Status Badges
- Capsule pills (`rounded-full`, padding `4px 10px`) utilizing semantic soft background washes paired with high-contrast text:
  - **Optimal / Good**: Background `#064e3b`, text `#34d399`, dot `#10b981`.
  - **Moderate / Fair**: Background `#78350f`, text `#fcd34d`, dot `#f59e0b`.
  - **Severe / High Alert**: Background `#7f1d1d`, text `#fca5a5`, dot `#ef4444`.

### Quick Metric Chips & Filter Tabs
- Segmented filters positioned horizontally with touch scroll.
- Inactive: Surface `#1e293b`, border `#334155`, text `#94a3b8`.
- Active: Background `#2080a7`, text `#FFFFFF`, soft elevation glow.

### Form Inputs & Threshold Sliders
- Text fields use height `52px`, `rounded-xl`, neutral background `#1e293b`, border `#475569`.
- Focused state transitions border to `#2080a7` with a 3px ring of `rgba(32, 128, 167, 0.25)`.
- Sliders for resource budgets feature a chunky thumb with an inset numeric readout bubble.

### Bottom Navigation Bar
- Fixed height `68px` floating bar or docked container with `rgba(17, 24, 39, 0.92)` frosted glass blur (`16px`).
- Icons: 24px stroked geometric SVG icons with 2px line-weight.
- Active item displays an active indicator dot in `#2080a7` beneath the active icon, with typography switching to primary accent bold.