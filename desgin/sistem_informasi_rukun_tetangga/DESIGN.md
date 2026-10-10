---
name: Sistem Informasi Rukun Tetangga
colors:
  surface: '#f8f9ff'
  surface-dim: '#ccdbf3'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d5e3fc'
  on-surface: '#0d1c2e'
  on-surface-variant: '#3e4943'
  inverse-surface: '#233144'
  inverse-on-surface: '#eaf1ff'
  outline: '#6e7a72'
  outline-variant: '#bec9c1'
  surface-tint: '#006c4c'
  primary: '#005f42'
  on-primary: '#ffffff'
  primary-container: '#0d7a57'
  on-primary-container: '#a7ffd5'
  inverse-primary: '#7cd8af'
  secondary: '#4a5f7e'
  on-secondary: '#ffffff'
  secondary-container: '#c6dbff'
  on-secondary-container: '#4b607f'
  tertiary: '#7f4300'
  on-tertiary: '#ffffff'
  tertiary-container: '#a35700'
  on-tertiary-container: '#ffe8d9'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#98f5ca'
  primary-fixed-dim: '#7cd8af'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#005138'
  secondary-fixed: '#d4e3ff'
  secondary-fixed-dim: '#b2c8eb'
  on-secondary-fixed: '#031c37'
  on-secondary-fixed-variant: '#324865'
  tertiary-fixed: '#ffdcc3'
  tertiary-fixed-dim: '#ffb77d'
  on-tertiary-fixed: '#2f1500'
  on-tertiary-fixed-variant: '#6e3900'
  background: '#f8f9ff'
  on-background: '#0d1c2e'
  surface-variant: '#d5e3fc'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  code-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0em
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
---

## Brand & Style

This design system establishes a modern civic governance language for Indonesian neighborhood administration (Rukun Tetangga / RT). It rejects the antiquated, bureaucratic visual tropes of public-sector interfaces in favor of an authoritative, clean, and highly functional civic dashboard. The emotional signature communicates security, transparent governance, communal welfare, and administrative efficiency.

The design philosophy combines contemporary civic functionalism with structured data architecture:
- **Tone & Identity:** Orderly, democratic, reassuring, and dignified. It conveys the institutional stability of local public service alongside the approachable intimacy of community life (*gotong royong*).
- **Aesthetic Movement:** Corporate Modern infused with Structured Civic Utilitarianism. Interfaces prioritize clarity over decoration, utilizing purposeful status indicators, rigorous visual rhythm, deliberate whitespace, and meticulous tabular styling.
- **Audience:** Neighborhood heads (*Ketua RT*), administrators, treasurers, and resident citizens seeking immediate clarity on dues (*iuran warga*), security logs, social assistance distributions, and civic documentation.

## Colors

The palette balances administrative institutional authority with civic accessibility through calibrated contrast ratios compliant with WCAG AAA specifications for core readouts.

- **Primary (`#0D7A57` — Emerald Civic):** Symbolizes community welfare, social balance, and ecological neighborhood upkeep. Used for primary calls to action, active navigation indicators, approval statuses, and key fiscal tallies.
- **Secondary (`#132A46` — Deep Navy):** Represents institutional authority, public order, and foundational structure. Anchors persistent app shells, top banners, high-priority system tables, and primary headings.
- **Tertiary (`#D97706` — Amber Civic Notice):** Dedicated to pending resident authorizations, citizen complaints under review, overdue fee alerts, and caution-grade municipal notices.
- **Neutral Palette (`Slate` Family):** Built upon `#475569` base slate with cool-tinted foundations:
  - App Canvas Surface: `#F8FAFC`
  - Subdued Card Interior: `#FFFFFF`
  - Structural Dividing Lines: `#E2E8F0`
  - High-Contrast Body Text: `#0F172A`
  - Secondary Metadata Text: `#475569`

## Typography

The typographic hierarchy pairs **Plus Jakarta Sans** for prominent headers with **Inter** for data layers, tables, and functional controls. 

- **Display & Headlines (Plus Jakarta Sans):** Crafted with balanced Indonesian-friendly letterforms, offering an inviting yet unmistakably official presence for statistical summaries, resident census numbers, and dashboard views.
- **Data & Body (Inter):** Deployed for high legibility within dense citizen registries, financial balance ledgers, and demographic forms. Tabular figures must be enabled via `font-feature-settings: 'tnum' 1` for all numeric values, monetary data (*Rupiah*), and national identity numbers (*NIK/KK*).

## Layout & Spacing

The system runs on a 12-column adaptive grid configured for dense data presentation without visual clutter.

- **Desktop (1280px and above):** 12 columns, `margin: 2rem`, `gutter: 1.5rem`. Side-navigation retains a fixed width of 260px; the primary workspace occupies the remaining fluid area with a maximum content container cap of 1440px.
- **Tablet (768px - 1279px):** 8 columns, `margin: 1.5rem`, `gutter: 1.25rem`. Global navigation condenses to a slim icon-dock or collapsible off-canvas drawer.
- **Mobile (below 768px):** 4 columns, `margin-mobile: 1rem`, `gutter-mobile: 1rem`. Multi-column analytical widgets collapse into single-column vertical stacks.
- **Vertical Rhythm:** Components adhere to an 8px base grid, using `space-xs` (4px) and `space-sm` (8px) for internal micro-padding, and `space-md` (16px) through `space-xl` (32px) for block-level module separations.

## Elevation & Depth

This system avoids heavy shadows, instead using subtle, tonal stacking combined with crisp slate outlines to deliver an uncluttered civic aesthetic.

- **Flat Canvas:** Background is permanently set to cool slate-neutral tint `#F8FAFC`, against which all content cards read as elevated through pure `#FFFFFF` fill.
- **Structural Borders:** Surface boundaries rely on 1px crisp borders (`#E2E8F0`) rather than drop shadows to delimit card edges and table modules.
- **Ambient Focus Elevation:** Interactive floating elements (dropdowns, popover action menus, modals) apply a diffused low-contrast drop shadow tinted with secondary navy: `0 8px 24px -4px rgba(19, 42, 70, 0.08), 0 2px 6px -1px rgba(19, 42, 70, 0.04)`.
- **Active State Layers:** Highlighted rows, pending items, and active selections apply a low-opacity color tint overlay rather than physical elevation changes (e.g., `#0D7A57` at 6% opacity).

## Shapes

The design uses a clean, controlled shape language (`roundedness: 1`, 0.25rem base radius). This geometry matches institutional clarity, preserving sharp screen density and maintaining table alignment integrity across extensive data records.

- **Base Controls:** Inputs, buttons, and select fields utilize `0.25rem` (4px) corner radii.
- **Containers & Cards:** Metric blocks and content sections scale to `0.5rem` (`rounded-lg`).
- **Pill Exception:** Status tags and category badges use a full capsule border-radius (`9999px`) to create clear differentiation from rectangular data fields.

## Components

### Buttons
- **Primary:** Background `#0D7A57`, text white, `0.25rem` corner radius, `font-weight: 600`. Hover transitions to `#0A6044`.
- **Secondary / Institutional:** Background `#132A46`, text white. Hover shifts to `#1D3B60`.
- **Outline / Filter:** Background transparent, border 1px solid `#CBD5E1`, text `#1E293B`. Hover introduces `#F1F5F9`.
- **Destructive:** Background `#DC2626`, text white. For evictions, deletion of records, or security alerts.

### Status Badges & Chips
Capsule-shaped (`9999px` radius) with low-saturation backgrounds and high-contrast text:
- **Verified / Lunas (Paid):** `#ECFDF5` background, `#065F46` label.
- **Pending / Menunggu:** `#FEF3C7` background, `#92400E` label.
- **Overdue / Menunggak:** `#FEF2F2` background, `#991B1B` label.
- **Informational / Warga Tetap:** `#F1F5F9` background, `#334155` label.

### Data Tables (Civic Registries & Ledgers)
- Header row styled in `#F8FAFC` background with uppercase `label-sm` slate text and crisp bottom border `#CBD5E1`.
- Row height: 48px standard for administrative density; 56px when secondary citizen descriptions are included.
- Hover state: full row receives `#F8FAFC` background. Active/selected row: `#0D7A57` at 4% tint with a 3px solid `#0D7A57` left anchor indicator.

### Input Fields & Search Bars
- Standard height: 40px. Border: 1px solid `#CBD5E1`. Internal horizontal padding: `space-md` (16px).
- Focus state: border turns `#0D7A57` accompanied by an emerald-tinted outer glow ring (`0 0 0 3px rgba(13, 122, 87, 0.15)`).

### Metric Cards (Ringkasan RT)
- Background `#FFFFFF`, border 1px solid `#E2E8F0`, padding `space-lg` (24px).
- Upper metadata: title in uppercase `label-sm` with slate tone, paired with an icon colored in primary emerald or secondary navy.
- Numerical value: `headline-xl` using tabular numbers.
- Lower trendline: subtle comparison tag indicating percentage change or demographic delta against previous periods.

### Citizen Quick Actions
Dedicated floating or fixed action dock with icon-led short paths: *Input Warga Baru*, *Buat Surat Pengantar*, *Catat Kas Masuk*, and *Broadcast Pengumuman*. Built with `#FFFFFF` surfaces, 1px `#CBD5E1` outlines, and bold primary micro-accents.