---
name: Field Force Terracotta
colors:
  surface: '#fff8f5'
  surface-dim: '#f3d4c1'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff1e9'
  surface-container: '#ffeadd'
  surface-container-high: '#ffe3d1'
  surface-container-highest: '#fcddc9'
  on-surface: '#28180c'
  on-surface-variant: '#574238'
  inverse-surface: '#3f2d1f'
  inverse-on-surface: '#ffede3'
  outline: '#8b7266'
  outline-variant: '#dec0b3'
  surface-tint: '#9f4200'
  primary: '#9b4000'
  on-primary: '#ffffff'
  primary-container: '#c05407'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb691'
  secondary: '#855300'
  on-secondary: '#ffffff'
  secondary-container: '#fdb659'
  on-secondary-container: '#724700'
  tertiary: '#006a3c'
  on-tertiary: '#ffffff'
  tertiary-container: '#238551'
  on-tertiary-container: '#f6fff5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbcb'
  primary-fixed-dim: '#ffb691'
  on-primary-fixed: '#341100'
  on-primary-fixed-variant: '#793100'
  secondary-fixed: '#ffddb7'
  secondary-fixed-dim: '#ffb95e'
  on-secondary-fixed: '#2a1700'
  on-secondary-fixed-variant: '#653e00'
  tertiary-fixed: '#98f6b8'
  tertiary-fixed-dim: '#7dd99e'
  on-tertiary-fixed: '#00210f'
  on-tertiary-fixed-variant: '#00522d'
  background: '#fff8f5'
  on-background: '#28180c'
  surface-variant: '#fcddc9'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '800'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 22px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '500'
    lineHeight: 22px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
  numeric-kpi:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '800'
    lineHeight: 26px
    letterSpacing: -0.02em
  numeric-currency:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: -0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1rem
  margin-mobile: 0.875rem
  space-2xs: 0.25rem
  space-xs: 0.375rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.25rem
  space-2xl: 1.5rem
  space-3xl: 2rem
---

## Brand & Style

This design system is engineered for FMCG field sales forces, route merchandisers, and van sales operators who navigate demanding outdoor environments, rapid store visits, and variable glare under bright sunlight. The aesthetic combines industrial utility with high-energy tactile warmth—rejecting sterile corporate gray in favor of a robust, terracotta-and-espresso earth palette that feels purposeful, resilient, and human.

### Visual Character & Design Movement
- **Movement:** Modern Utilitarian Tactile with high-contrast functionalism.
- **Atmosphere:** Grounded, dynamic, highly legible, and dependable under harsh outdoor conditions.
- **Emotional Hook:** Instills urgency, competence, and friction-free task execution across high-tempo route cycles (Check-in, Audit Stok, Ambil Pesanan, Penagihan).
- **Core Principles:**
  - **Sunlight Legibility:** Ultra-sharp contrast ratios against rich biscuit and pure white backdrops to ensure clarity at full screen brightness on mid-tier Android devices.
  - **Single-Handed Ergonomics:** Bottom-anchored primary actions, large thumb targets (minimum 48dp), and unambiguous tactile affordances.
  - **Status Immediacy:** Persistent, glanceable telemetry for connectivity (Offline-first / Sinkronisasi Data) and daily quota trajectories (Target vs Capaian).

## Colors

The palette balances energetic earth tones with industrial-grade contrast. Surfaces move from a warm biscuit canvas into crisp white container cards, anchored by deep espresso for razor-sharp typography.

### Palette Hierarchy & Roles
- **Primary (`#D4621A` - Terracotta Orange):** The dominant action color. Reserved strictly for primary CTAs ("Check-In Toko", "Buat Order", "Kirim Laporan"), interactive highlights, and active navigation indicators.
- **Secondary (`#F4AE52` - Warm Ochre Gold):** Supporting contextual amber. Used for warning states, route progress indicators, mid-tier badges, and pending sync flags.
- **Tertiary (`#2A8A56` - Forest Green):** Operational success and sync validation color ("Tersinkron", "Efektif Call Tercapai", "Stok Cukup").
- **Neutral (`#2A1A0E` - Dark Espresso Brown):** The primary typographic and structural ink color. Replaces pure black to eliminate chromatic vibration while maintaining WCAG AAA contrast against cream and white surfaces.
- **Canvas Base (`#FEF3E2` - Warm Biscuit):** Default background canvas delivering reduced eye strain in intense ambient daylight without sacrificing brightness.
- **Surface Elevation Cards (`#FFFFFF`):** High-clarity white card backgrounds providing clean separation for inventory lists, store rosters, and transactional receipts.
- **Surface Borders (`#EBD8C3`):** Subtle raw-linen borders providing structural boundaries to cards without visual clutter.

## Typography

Plus Jakarta Sans is utilized across all typographic scales to deliver humanist warmth combined with geometric clarity. The font’s open counters, tall x-height, and robust stroke weights ensure rapid data scanning under direct glare.

### Typographic Principles
- **Tabular Numerics for Operational Speed:** All numeric metrics (IDR currency, target percentages, and SKU quantities) use tabular figure formatting (`tnum`) to maintain clean columnar vertical alignment across summary tallies and cart matrices.
- **Caps for Categorical Badges:** Operational markers (`TERTUNDA`, `SELESAI`, `OUTLET PARETO`, `RENCANA HARI INI`) leverage `label-sm` with letter spacing to maximize rapid visual identification.
- **Hierarchy Anchors:** Headlines drive route momentum; primary merchant names use `headline-sm` with zero ambiguity, while address and district subtexts sit comfortably in `body-sm`.

## Layout & Spacing

The layout model is mobile-first, designed around vertical continuous flow with fixed bottom sheets and anchored quick-action docks.

### Screen Architecture & Form Factors
- **Mobile (Primary Target, <640px):** Single-column fluid layout with an outer safe gutter of `14px` (`margin-mobile`). Vertical rhythm is pegged to a strict 4px/8px incremental grid.
- **Tablet / Mounted In-Van Dashboard (640px - 1024px):** 2-column split master-detail view: Left column displays the geographic outlet route list (40% width); Right column displays the selected outlet's real-time transaction pane, order basket, and KPI telemetry (60% width).
- **Touch Zone Constraints:** All critical field buttons maintain a minimum physical touch box of 48×48px with a minimum separation of `space-sm` (8px) to prevent accidental mis-taps during transit or manual handling.

## Elevation & Depth

To preserve crisp readability under ambient daylight, depth is achieved primarily through warm surface tiering, high-contrast outlines, and purposeful tactile drop shadows rather than vague diffuse blurs.

### Elevation Hierarchy
- **Canvas Base (Level 0):** Flat background in `#FEF3E2`. No shadow.
- **Surface Cards (Level 1):** `#FFFFFF` surfaces wrapped with a 1px solid `#EBD8C3` stroke and a crisp contact shadow: `0 2px 4px rgba(42, 26, 14, 0.05)`.
- **Active / Focused Outlets (Level 2):** Elevated card state indicating active store visits: 1.5px solid `#D4621A` stroke with dual shadow `0 4px 12px rgba(212, 98, 26, 0.12), 0 1px 3px rgba(42, 26, 14, 0.06)`.
- **Bottom Navigation & Floating Cart Docks (Level 3):** Anchored control surfaces utilizing `#FFFFFF` backed by `0 -4px 16px rgba(42, 26, 14, 0.08)`.
- **Tactile Button Press Feedback:** Primary action buttons feature an intentional physical inset transition on tap (`active:translate-y-0.5`), reinforcing physical feedback for field operators wearing gloves or working on the move.

## Shapes

The design system employs a structured, friendly curvature that softens the dense, high-frequency data typical of FMCG logistics.

### Radius Assignments
- **Card Containers (`rounded-xl` / 16px):** Primary content groups (Outlet Cards, KPI Matrices, Invoice Line Items).
- **Action Buttons & Inputs (`rounded-lg` / 10px - 12px):** Form fields, order quantity toggles, and call-to-action blocks.
- **Badges, Tags & Numeric Steppers (`rounded-full` / Pill-shape):** Status indicators, category chips, and filter toggles.
- **Segmented Controls & Tab Strips (`rounded-lg` / 8px):** Route switchers ("Kunjungan Hari Ini", "Jadwal Esok", "Riwayat").

## Components

### Buttons
- **Primary Action (e.g., "Check-In Toko", "Buat Order"):** Full-width or dominant button with `#D4621A` solid fill, white text (`label-lg`), 12px corner radius, and 48px height. Includes active tap depression.
- **Secondary Utility (e.g., "Direksi Peta", "Lihat Riwayat"):** `#FFFFFF` background, 1.5px stroke in `#D4621A`, text in `#D4621A`.
- **Destructive / Cancellation (e.g., "Batal Kunjungan"):** Soft cream fill `#FDEEE9` with deep rust text `#B83A14`.

### KPI Stat Counters (Field Dashboard)
- **Container:** Pure white card with 1px `#EBD8C3` border.
- **Structure:** 2×2 or 4×1 horizontally scrollable metric blocks.
- **Visuals:** Top label in `label-sm` (`#2A1A0E` with 60% opacity), value in `numeric-kpi` (`#2A1A0E`), and target comparison in `body-sm` using contextual tint badges:
  - *Plan Call vs Actual Call:* "18/24 Toko"
  - *Effective Call (EC):* "75% Target"
  - *Capaian Omset:* "Rp 14.250.000 / Rp 20.000.000"

### Offline Sync Status Indicator
- **Global Header Component:** Sticky micro-bar or header pill displaying real-time telemetry.
- **Tersinkron (Synced):** Pill badge with `#E8F5E9` background, `#2A8A56` text, and a solid green checkmark icon ("Tersinkron").
- **Pending Sync (Offline Queue):** Pill badge with `#FFF3E0` background, `#D4621A` text, and a rotating amber sync icon (e.g., "3 Tertunda", "Offline Mode").

### Outlet Route Cards
- **Card Structure:** White card containing:
  - Merchant name (`headline-sm`), category chip (e.g., "Grosir", "Star Outlet", "Warung"), and pareto indicator.
  - Verification state (Geofenced GPS status, distance in meters).
  - Quick action cluster: Call icon button, Map icon button, and primary "Check-In" trigger.

### Input Fields & Search Bars
- **Style:** 44px height, `#FFFFFF` fill with 1.5px border in `#DDC7B0`. Focus state shifts border to `#D4621A` with a 2px outer aura in `rgba(212, 98, 26, 0.15)`. Text sits in `#2A1A0E`.

### SKU Counter & Stepper (Order Taking)
- **Compact Field Stepper:** Deep brown rounded container containing `-` and `+` touch points (minimum 36px) flanking a bold numeric quantity input.
- **Pricing Breakdown:** Subtotal dynamically displayed in `numeric-currency` directly adjacent to carton/renceng/pcs units.