---
name: Scholastic Serenity
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
  on-surface-variant: '#434655'
  inverse-surface: '#233144'
  inverse-on-surface: '#eaf1ff'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#006c4a'
  on-secondary: '#ffffff'
  secondary-container: '#82f5c1'
  on-secondary-container: '#00714e'
  tertiary: '#824500'
  on-tertiary: '#ffffff'
  tertiary-container: '#a65900'
  on-tertiary-container: '#ffede1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#85f8c4'
  secondary-fixed-dim: '#68dba9'
  on-secondary-fixed: '#002114'
  on-secondary-fixed-variant: '#005137'
  tertiary-fixed: '#ffdcc3'
  tertiary-fixed-dim: '#ffb77d'
  on-tertiary-fixed: '#2f1500'
  on-tertiary-fixed-variant: '#6e3900'
  background: '#f8f9ff'
  on-background: '#0d1c2e'
  surface-variant: '#d5e3fc'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  title-md:
    fontFamily: Manrope
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  stats-number:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
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
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  gutter: 16px
  margin-mobile: 16px
  margin-tablet: 32px
---

## Brand & Style
The design system is built on the "Calm Academic" aesthetic—a fusion of modern minimalism and professional scholarly structure. It is designed to reduce cognitive load for students, prioritizing focus and local task management over social connectivity.

The style leverages **Modern Minimalism** with a **Tactile** touch. It avoids the clinical coldness of enterprise software by using soft transitions, organic rounded corners, and a nature-inspired palette. The emotional response is one of "focused capability"—the user should feel organized, grounded, and in control of their personal progress without the distractions of the cloud.

## Colors
The palette is rooted in "Academic Blue" to signify stability and intelligence. 

- **Primary (Blue):** Used for main actions, active states, and progress indicators.
- **Secondary (Green):** Specifically reserved for "Success," "Completed Tasks," and "Study Streaks." It provides a calming sense of achievement.
- **Tertiary (Amber):** Used sparingly for "Deep Work" sessions or high-priority deadlines.
- **Neutral:** A range of slate grays that provide high legibility without the harshness of pure black.

**Dark Mode Strategy:** In dark mode, the background shifts to a deep navy (`#0F172A`) rather than pure black to maintain the academic, ink-like feel. Surfaces use a slightly lighter slate to indicate elevation.

## Typography
The typography system uses a tiered approach to balance character with utility:
- **Manrope** is used for headlines and statistics, providing a modern, refined, and slightly tech-forward academic look.
- **Inter** handles all body copy and descriptions, ensuring maximum readability during long study sessions.
- **JetBrains Mono** is utilized for metadata, "Local Storage" status indicators, and counters to emphasize the offline, structured nature of the data.

Scale font sizes appropriately for mobile; titles should never exceed 32px on handset devices to avoid awkward line breaks.

## Layout & Spacing
This design system follows a strict **8dp grid system** to ensure vertical rhythm and consistent alignment. 

- **Layout Model:** A fluid grid that adapts to the viewport. 
- **Mobile:** 4-column grid with 16px side margins and 16px gutters.
- **Tablet/Desktop:** 12-column grid with 32px margins. 
- **Vertical Spacing:** Use `16px` (md) as the standard gap between related items in a list, and `24px` (lg) for separating distinct sections like "Today's Schedule" from "Weekly Goals."

## Elevation & Depth
Hierarchy is established through **Tonal Layering** and **Ambient Shadows**.

- **Level 0 (Base):** The main background color.
- **Level 1 (Cards):** Use a white surface (or dark slate) with a very soft, diffused shadow: `0px 4px 12px rgba(0, 0, 0, 0.05)`.
- **Level 2 (Active/Pressed):** When a user interacts with a card, the shadow should deepen slightly, and the border-color should shift to the primary color.
- **Outlines:** Use subtle `1px` borders (`#E2E8F0` in light mode) for secondary elements like input fields and inactive chips to keep the UI flat and non-distracting.

## Shapes
Shapes are intentionally friendly but structured. 

- **Standard Elements:** Buttons and input fields use a `0.5rem` (8px) radius.
- **Containers:** Large cards (e.g., Study Session summaries) use `1rem` (16px) to feel more like physical notebooks or planners.
- **Progress Bars:** Use fully rounded (pill-shaped) caps to signify fluidity and growth.
- **Icons:** Use a 2px stroke weight with slightly rounded corners (not sharp) to match the typography.

## Components

### Buttons
- **Primary:** Solid blue background, white text, 8px radius. Minimum height 48dp.
- **Secondary:** Blue text, light blue ghost background or 1px blue border.
- **Floating Action Button (FAB):** Large 56dp circle, primary color, used exclusively for "Add Task" or "Start Study Timer."

### Cards
Cards are the primary organizational unit. Every card should have a `16px` internal padding. For study tasks, include a small "local" icon (a tiny disk or dot) to reinforce the offline-only nature of the data.

### Chips
Use chips for "Subject Tags" (e.g., Math, History). They should use a low-saturation background of the subject's assigned color with high-contrast text.

### Inputs
Text fields must have clear labels using the `label-caps` typography style. The focus state uses a 2px primary color border.

### Study Timer / Progress
The "Progress" component should be a prominent circular or linear gauge using the Secondary (Green) color to indicate completion. Use high-contrast stats for "Minutes Studied" and "Current Streak."

### Lists
Lists use 72dp row heights for items with sub-text and 48dp for simple items. Every list item must have a clear touch-feedback ripple effect.