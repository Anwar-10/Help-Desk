---
name: Civic Horizon
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#42493c'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#72796b'
  outline-variant: '#c2c9b8'
  surface-tint: '#386a1e'
  primary: '#36671c'
  on-primary: '#ffffff'
  primary-container: '#4e8133'
  on-primary-container: '#f8ffed'
  inverse-primary: '#9dd67d'
  secondary: '#4c662e'
  on-secondary: '#ffffff'
  secondary-container: '#cbeaa4'
  on-secondary-container: '#506a32'
  tertiary: '#9d3b3d'
  on-tertiary: '#ffffff'
  tertiary-container: '#bd5353'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b8f396'
  primary-fixed-dim: '#9dd67d'
  on-primary-fixed: '#082100'
  on-primary-fixed-variant: '#215105'
  secondary-fixed: '#ceeda7'
  secondary-fixed-dim: '#b2d08d'
  on-secondary-fixed: '#0f2000'
  on-secondary-fixed-variant: '#354e19'
  tertiary-fixed: '#ffdad8'
  tertiary-fixed-dim: '#ffb3b1'
  on-tertiary-fixed: '#410007'
  on-tertiary-fixed-variant: '#81262a'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 2.75rem
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.25rem
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.25rem
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.375rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '600'
    lineHeight: 1.5rem
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-md:
    fontFamily: Inter
    fontSize: 0.9375rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-sm:
    fontFamily: Inter
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: 1.25rem
  label-lg:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 0.6875rem
    fontWeight: '500'
    lineHeight: 0.875rem
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
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
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes a high-integrity, institutional digital environment for citizen grievances and public administration. Combining modern civic minimalism with pragmatic enterprise data density, the aesthetic rejects bureaucratic clutter in favor of transparency, accountability, and approachable authority. 

The visual style is characterized by structured cards, crisp surface contrasts, and restrained chromatic signaling:
- **Atmospheric Clarity:** Muted neutral bases allow citizens and government staff to navigate dense status trackers, official dispatches, and public evidence logs without visual fatigue.
- **Dignified Functionality:** Balancing warmth and institutional precision through tailored typography and balanced border radii.
- **High-Fidelity Tracking:** Status-driven color accents emphasize the progression of civic tickets from intake to formal resolution.

## Colors

The palette is engineered for civic governance, emphasizing balance, legitimate authority, and actionable contrast.

- **Primary (`#689D4B`):** Forest Olive Green serves as the anchor for confirmed states, system affirmations, primary administrative action buttons, and closed/resolved civic complaints.
- **Secondary (`#91AE6E`):** Sage Green provides a softer informational layer, designated for ongoing verification, in-progress stages, and supportive UI highlights.
- **Tertiary / Urgency Accent (`#D96868`):** Coral Red handles critical triage, high-urgency complaint markers, rejected states, and essential system alerts without evoking sheer alarmism.
- **Neutral Foundation (`#F2F2F2`):** A calibrated warm gray canvas that separates individual clean-white (`#FFFFFF`) containers and cards while minimizing screen glare.
- **Text & Structure:**
  - Primary Content: `#1E293B` (Slate Dark) delivers high-contrast readability across tables, inputs, and formal correspondence.
  - Secondary Content: `#64748B` (Slate Muted) supports secondary labels, timestamps, and metadata.
  - Borders & Outlines: Subtle containment via `#E2E8F0` and `#D8D8D8`.

## Typography

The typographic hierarchy bridges public accessibility and official authority:
- **Headings (Plus Jakarta Sans):** Introduces friendly yet firm institutional presence. Ranging from semibold to bold, headings retain sharp geometric balance on civic landing pages and administrative headers.
- **Body & Data Tables (Inter):** Leveraged for tabular reports, case records, citizen testimonies, and legal notices. Inter offers tall x-heights and optimized digit spacing crucial for reference numbers and dates.
- **Data Integrity:** Numerical ticket identifiers (`TKT-2024-X`) must feature tabular figures (`font-variant-numeric: tabular-nums`) within data tables and ticket headers to ensure vertical scanning alignment.

## Layout & Spacing

This design system uses a flexible 12-column grid system for administrative control panels and citizen service flows:
- **Desktop (1200px+):** 12 columns with `gutter` of `1.5rem` and outer canvas margins of `2rem`. Supports split views (e.g., ticket intake list alongside live incident maps and official timeline threads).
- **Tablet (768px – 1199px):** 8 columns with dynamic gutters (`1rem` to `1.25rem`), collapsing auxiliary metadata into dismissible sheets or accordion blocks.
- **Mobile (< 768px):** 4 columns with `margin-mobile` of `1rem`. Structural forms and evidence uploads adopt single-column stacked hierarchy.
- **Rhythm:** Spacing follows an 8px base rhythm (`space-xs` = 4px, `space-sm` = 8px, `space-md` = 16px, `space-lg` = 24px, `space-xl` = 40px) to maintain predictable vertical rhythm across form-heavy layouts.

## Elevation & Depth

Visual depth is achieved through quiet contrast layering rather than dramatic drop shadows, ensuring rapid rendering and formal composure:

- **Base Ground:** The background operates on `#F2F2F2`.
- **Card Surfaces:** Cards, drawers, and modal backdrops leverage pure `#FFFFFF`, delineated by a crisp 1px border of `#E2E8F0`.
- **Shadow Scale:**
  - *Resting Cards / Containers:* `0 1px 3px 0 rgba(30, 41, 59, 0.05), 0 1px 2px -1px rgba(30, 41, 59, 0.05)`
  - *Interactive Cards (Hover) / Popovers:* `0 4px 6px -1px rgba(30, 41, 59, 0.07), 0 2px 4px -2px rgba(30, 41, 59, 0.05)`
  - *Modals & Priority Flyouts:* `0 12px 24px -4px rgba(30, 41, 59, 0.12), 0 4px 8px -2px rgba(30, 41, 59, 0.04)`

## Shapes

The interface adopts a disciplined rounded shape profile (`roundedness: 2`) to balance approachability with administrative professionalism:
- **Cards and Content Surfaces:** Use `rounded-xl` (12px / 0.75rem to 1rem) to soften large administrative panels.
- **Inputs & Action Items:** Use `rounded` (8px / 0.5rem) to preserve structured form fields.
- **Status Badges & Category Tags:** Fully pill-shaped (`rounded-full` / 9999px) to distinctly isolate workflow statuses from structural cards and buttons.

## Components

### Buttons
- **Primary:** Background `#689D4B`, text `#FFFFFF`, border none, 8px radius. Hover state transitions to `#57853E`. Active state `#497033`. Focus ring: 2px offset with `#689D4B` at 40% opacity.
- **Secondary / Ghost:** White background, 1px border `#E2E8F0`, text `#1E293B`. Hover: background `#F8FAFC`, border `#CBD5E1`.
- **Destructive / Urgent:** Background `#D96868`, text `#FFFFFF`. Hover: `#C45454`.

### Status Badges (Pills)
All badges utilize 9999px (`rounded-full`), `label-sm` or `label-md`, with an internal 6px dot indicator:
- **Baru (New Intake):** Background `#FEE2E2`, text `#991B1B`, dot `#D96868`.
- **Diverifikasi (Verified):** Background `#EFF6FF`, text `#1E40AF`, dot `#3B82F6` (or Amber `#FEF3C7`, text `#92400E`, dot `#D97706`).
- **Diproses (In Progress):** Background `#F4F7F0`, text `#47662A`, dot `#91AE6E`.
- **Selesai (Resolved):** Background `#EAF2E6`, text `#2D5417`, dot `#689D4B`.
- **Ditolak (Rejected / Archived):** Background `#F1F5F9`, text `#475569`, dot `#64748B`.

### Form Fields & Inputs
- **Base Style:** 8px border-radius, background `#FFFFFF`, border 1px solid `#E2E8F0`, padding `0.625rem 0.875rem`, text `#1E293B`, placeholder `#94A3B8`.
- **Focus State:** Border color `#689D4B`, box-shadow `0 0 0 3px rgba(104, 157, 75, 0.15)`.
- **Error State:** Border color `#D96868`, box-shadow `0 0 0 3px rgba(217, 104, 104, 0.15)`.

### Cards & Ticket Lists
- **Structure:** Background `#FFFFFF`, 12px border radius, 1px outline of `#E2E8F0`.
- **Complaint Ticket Item:** Divided into a 3-part layout:
  1. Header: Reference ID (tabular font), submission timestamp, and status pill.
  2. Body: Complaint title (Plus Jakarta Sans semibold), truncated citizen narrative (Inter body-sm), and attachment badges.
  3. Footer: Responsible agency tag (e.g., *Dinas Bina Marga*), urgency indicator, and internal tracking count.

### Checkboxes & Radios
- **Checkboxes:** 4px radius, 1.5px border `#CBD5E1`. When selected: `#689D4B` background with white checkmark.
- **Radios:** Full circle, 1.5px border `#CBD5E1`. When selected: `#689D4B` outer ring with white center dot.

### Timeline & Progress Stepper
- Continuous vertical progress line using `#E2E8F0`. Passed steps turn `#689D4B` with completed check icon. Current step features an active pulsing inner ring using `#91AE6E`.