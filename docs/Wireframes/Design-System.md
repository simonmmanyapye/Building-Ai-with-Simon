# Design System

This document defines the visual language and reusable design rules for the *Building AI with Simon* website. It ensures consistency across all pages and provides a foundation for future scaling.

---

## 1. Design Philosophy

The design system is based on three principles:

- **Clarity over complexity** — content must always be easy to read
- **Documentation-first UI** — inspired by technical documentation sites
- **Minimal but expressive** — simple layout with strong structure and hierarchy

The goal is not decoration, but **structured communication of ideas and progress**.

---

## 2. Typography

### Font Family
- Primary font: **Montserrat**
- Fallback: sans-serif

### Type Scale

| Element | Size | Usage |
|--------|------|------|
| H1 | 2.5rem | Page titles |
| H2 | 2rem | Section headings |
| H3 | 1.5rem | Sub-sections |
| Body | 1rem | Standard text |
| Small text | 0.875rem | Metadata, labels |

### Rules
- Headings must be bold and clearly separated from body text
- Line spacing should improve readability (1.5–1.8)
- Avoid decorative or overly stylised fonts

---

## 3. Colour Palette

### Core Colours

- Background: `#FFFFFF` (White)
- Primary Text: `#000000` (Black)
- Accent Colour: `#220647` (Deep Purple)

### Usage Rules

- Accent colour is used for:
- Links
- Buttons
- Highlights
- Active navigation items

- Black is used for all primary text content
- White is used as base background for clarity and readability

---

## 4. Layout System

### Structure Principles

- Mobile-first responsive design
- Flexible layouts using Flexbox and Grid
- Consistent spacing system

### Spacing Scale

- 4px (micro spacing)
- 8px (small spacing)
- 16px (default spacing)
- 24px (section spacing)
- 48px (large section separation)

---

## 5. Components

### Navigation Bar
- Persistent across all pages
- Includes links to all main sections
- Active page highlighted using accent colour

---

### Buttons

- Primary button:
- Background: Accent colour
- Text: White
- Secondary button:
- Border: Accent colour
- Text: Black

---

### Cards (for Projects & Skills)

- White background
- Subtle border or shadow
- Contains:
- Title
- Description
- Metadata (tech stack, status, etc.)

---

### Sections

Each page is built using consistent section blocks:

- Title
- Content area
- Optional divider

---

## 6. Responsiveness

The system is designed for:

- Mobile devices (320px+)
- Tablets (768px+)
- Desktop (1024px+)

### Rules

- Mobile is the default design baseline
- Navigation collapses into simplified layout on small screens
- Text remains readable without zooming
- Sections stack vertically on mobile

---

## 7. Iconography (Optional Future Use)

- Simple line icons only
- No heavy or decorative icon sets
- Used sparingly for navigation or metadata

---

## 8. UI Behaviour

- No complex animations in v1
- Optional smooth scrolling for navigation
- Hover states for buttons and links using accent colour
- Focus states must remain visible for accessibility

---

## 9. Accessibility Rules

- Maintain high contrast between text and background
- Ensure readable font sizes (minimum 16px body text)
- All interactive elements must be keyboard accessible
- Avoid colour-only meaning (use labels or structure)

---

## 10. Design Consistency Rules

- All pages must reuse the same spacing system
- All headings must follow the type scale
- Accent colour must not be changed per page
- Layout patterns must remain consistent across the site

---

## 11. Summary

This design system ensures that the website:

- Feels consistent across all pages
- Prioritises readability and structure
- Scales cleanly as the project grows
- Remains simple enough for rapid development
