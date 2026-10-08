---
name: Kinetic Enterprise Precision
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
  on-surface-variant: '#5a4136'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#8e7164'
  outline-variant: '#e2bfb0'
  surface-tint: '#a04100'
  primary: '#a04100'
  on-primary: '#ffffff'
  primary-container: '#ff6b00'
  on-primary-container: '#572000'
  inverse-primary: '#ffb693'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#006d2f'
  on-tertiary: '#ffffff'
  tertiary-container: '#00b050'
  on-tertiary-container: '#003a15'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbcc'
  primary-fixed-dim: '#ffb693'
  on-primary-fixed: '#351000'
  on-primary-fixed-variant: '#7a3000'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#66ff8e'
  tertiary-fixed-dim: '#3de273'
  on-tertiary-fixed: '#002109'
  on-tertiary-fixed-variant: '#005322'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 3.5rem
    fontWeight: '800'
    lineHeight: 4.25rem
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '800'
    lineHeight: 2.75rem
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 2.75rem
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.25rem
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.25rem
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '600'
    lineHeight: 1.5rem
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
    letterSpacing: -0.01em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.9375rem
    fontWeight: '400'
    lineHeight: 1.5rem
    letterSpacing: '0'
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: 1.25rem
    letterSpacing: 0.005em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: '0'
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.02em
  mono-code:
    fontFamily: JetBrains Mono
    fontSize: 0.8125rem
    fontWeight: '500'
    lineHeight: 1.25rem
    letterSpacing: '0'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
---

## Brand & Style

This design system expresses high-velocity precision, cognitive clarity, and executive trust. Tailored for enterprise-grade automation, intelligent CRM pipelines, and omnichannel messaging interfaces, it balances technical density with calm visual balance.

The visual style blends modern corporate SaaS rigor with high-performance operational ergonomics. Layouts leverage high contrast, clear information architecture, structural borders, and purposeful warm accents. The aesthetic eliminates visual clutter to ensure data-heavy tables, automated workflow canvases, and communication streams remain scannable and fatigue-free during all-day enterprise use.

## Colors

The palette establishes an authoritative, high-contrast light mode foundation:

- **Primary (`#FF6B00` / `#EA580C` hover):** Vibrant Orange reserved strictly for primary calls-to-action, high-priority status badges, active execution states, and key automation highlights.
- **Secondary (`#0F172A`):** Deep Navy/Slate anchor tone for primary headlines, high-emphasis icons, and structural interface contrast.
- **Tertiary (`#25D366`):** Channel-specific signal green for WhatsApp ecosystem integrations, verified connections, and healthy pipeline nodes.
- **Neutral Palette:**
  - Base Surfaces: `#FFFFFF` (Primary Canvas/Cards), `#F8FAFC` (App Shell & Sidebar Background), `#F1F5F9` (Nested Containers & Table Headers).
  - Borders & Dividers: `#E2E8F0` (Default Borders), `#CBD5E1` (Emphasized/Interactive Borders).
  - Typography Scale: `#0F172A` (Headings/Primary Body), `#334155` (Secondary Labels/Form Values), `#64748B` (Muted/Placeholders/Meta).

Avoid overusing the vibrant orange; it functions as a visual beacon across data-dense views.

## Typography

Plus Jakarta Sans powers all structural interface layers, chosen for its contemporary geometric balance, open counters, and high legibility at dense data scales.

- Numerical readouts, metric changes, and CRM data columns rely on proportional geometric figures with deliberate tabular lining when rendering data grids.
- `mono-code` utilizes JetBrains Mono for API payloads, webhook definitions, and variable triggers within AI automation graphs.
- Text colors strictly follow visual priority: `#0F172A` for primary titles and active values, `#334155` for descriptive copy, and `#64748B` for tertiary stamps, metadata, and placeholder states.

## Layout & Spacing

The interface employs a responsive 12-column grid layout across desktop environments with fixed-width navigation panels (collapsible 260px primary sidebar, 360px contextual inspector).

- **Grid System:** 12-column layout on desktop (breakpoint ≥ 1280px) with 24px gutters (`gutter: 1.5rem`) and 32px external canvas margin (`margin: 2rem`).
- **Tablet Reflow:** Scales to an 8-column layout (768px – 1279px) with 20px gutters and collapsing utility panels.
- **Mobile Reflow:** Single-column stacked view (< 768px) with 16px margins (`margin-mobile: 1rem`) and pinned navigation bars.
- **Rhythm Rules:** All layout heights, margins, and internal card spacings scale strictly on a 4px/8px modular base. Dense data panels use `space-xs` and `space-sm` for tight data alignment, while macro views utilize `space-xl` and `space-2xl` for structural air.

## Elevation & Depth

Visual hierarchy is maintained primarily through crisp, low-contrast structural outlines paired with light, multi-layered neutral ambient drop shadows. This preserves a lightweight tactile feel without dirtying the light canvas.

- **Level 0 (Base Canvas):** `#F8FAFC` solid fill, zero elevation, no border.
- **Level 1 (Card & Modular Panel):** Background `#FFFFFF`, border `1px solid #E2E8F0`, shadow `0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.04)`.
- **Level 2 (Dropdowns, Popovers, Hover Cards):** Background `#FFFFFF`, border `1px solid #CBD5E1`, shadow `0 4px 6px -1px rgba(15, 23, 42, 0.06), 0 2px 4px -2px rgba(15, 23, 42, 0.04)`.
- **Level 3 (Modals, Automation Trays):** Background `#FFFFFF`, border `1px solid #E2E8F0`, shadow `0 20px 25px -5px rgba(15, 23, 42, 0.08), 0 8px 10px -6px rgba(15, 23, 42, 0.04)`.
- **Level 4 (Workflow Floating Nodes):** Background `#FFFFFF`, border `1px solid #E2E8F0`, shadow `0 10px 15px -3px rgba(15, 23, 42, 0.05)`. Active nodes transition to border `1.5px solid #FF6B00` and soft orange halo `0 0 0 3px rgba(255, 107, 0, 0.12)`.

## Shapes

The design system employs a soft, measured border-radius scale (`roundedness: 1` base 0.25rem / 4px to 0.5rem / 8px) conveying structured architectural rigor rather than consumer playfulness:

- **Micro Controls (Inputs, Small Badges, Checkboxes):** 4px (`rounded-sm`).
- **Standard Controls (Buttons, Inputs, Select Menus, Dropdown Panels):** 6px to 8px (`rounded-md` / `rounded-lg`).
- **Containers & Surfaces (Cards, Data Grids, Modal Drawers):** 10px to 12px (`rounded-xl`).
- **Full Radius (Pills):** Status indicator tags, channel indicators, and avatar wrappers use 9999px.

## Components

### Buttons
- **Primary:** Background `#FF6B00`, text `#FFFFFF`, border `none`, font weight 600. Hover state: background `#EA580C`. Focus-visible: outer outline `2px solid rgba(255, 107, 0, 0.35)`.
- **Secondary:** Background `#FFFFFF`, text `#0F172A`, border `1px solid #E2E8F0`. Hover state: background `#F8FAFC`, border `#CBD5E1`.
- **Ghost/Tertiary:** Background transparent, text `#334155`. Hover state: background `#F1F5F9`, text `#0F172A`.
- **Destructive:** Background `#FEF2F2`, text `#DC2626`, border `1px solid #FEE2E2`. Hover: background `#FEE2E2`.

### Inputs & Form Controls
- Text inputs, textareas, and dropdown pickers feature a `#FFFFFF` fill, 1px border in `#E2E8F0`, text `#0F172A`, and placeholder text `#64748B`.
- Interactive focus state: border `#FF6B00` with box-shadow ring `0 0 0 3px rgba(255, 107, 0, 0.12)`.
- Checkboxes and radios use a 1.5px solid `#CBD5E1` border in unchecked states; checked states trigger a `#FF6B00` fill with a crisp white icon indicator.

### Cards & Container Panels
- Base Cards: Solid `#FFFFFF` fill with `1px solid #E2E8F0` border and Level 1 elevation.
- Header bands are delineated by a 1px border-bottom in `#E2E8F0` using `#F8FAFC` or `#FFFFFF` backgrounds.
- Metric display cards feature high-contrast `#0F172A` values with micro change badges underneath.

### Chips & Badges
- **Brand Highlights:** Soft background `rgba(255, 107, 0, 0.08)`, text `#EA580C`, border `1px solid rgba(255, 107, 0, 0.2)`.
- **Status Neutral:** Background `#F1F5F9`, text `#334155`, border `1px solid #E2E8F0`.
- **WhatsApp Direct Indicator:** Background `#DCFCE7`, text `#15803D`, border `1px solid #BBF7D0`.

### Data Tables & Lists
- Table header row uses a `#F8FAFC` background with `1px solid #E2E8F0` top/bottom dividers, uppercase tracking `label-sm` font in `#64748B`.
- Row states: alternating transparent backgrounds with hover highlight `#F8FAFC` transitioning over 150ms. Row separation divider: `1px solid #F1F5F9`.

### Automation Canvas & AI Flow Nodes
- Canvas background `#F8FAFC` mapped with a geometric `#E2E8F0` dot grid spaced at 24px increments.
- Step cards utilize `#FFFFFF` surfaces with subtle left-border color accents designating trigger type: `#FF6B00` (Automation/AI), `#25D366` (WhatsApp Action), `#0F172A` (CRM Database Update).