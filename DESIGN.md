---
name: Larissa Rodrigues de Castro Portfolio
description: A professional portfolio for IT support and computer maintenance.
colors:
  background: "#07131f"
  background-deep: "#050d16"
  surface: "#0e1d2b"
  surface-raised: "#142635"
  divider: "#293d4d"
  foreground: "#f3f6f7"
  secondary-text: "#b2c0ca"
  signal-blue: "#70c8ee"
  signal-blue-strong: "#3ba5d6"
  copper: "#e5a56a"
typography:
  display:
    fontFamily: "Inter, Segoe UI, Arial, sans-serif"
    fontSize: "clamp(3.2rem, 7vw, 6.2rem)"
    fontWeight: 650
    lineHeight: 0.96
    letterSpacing: "-0.065em"
  body:
    fontFamily: "Inter, Segoe UI, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.65
  label:
    fontFamily: "Cascadia Code, SFMono-Regular, Consolas, monospace"
    fontSize: "0.74rem"
    fontWeight: 400
rounded:
  square: "0px"
spacing:
  sm: "12px"
  md: "20px"
  lg: "32px"
  xl: "48px"
components:
  button-primary:
    backgroundColor: "{colors.signal-blue}"
    textColor: "#06121d"
    rounded: "{rounded.square}"
    padding: "0 18px"
    height: "48px"
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.foreground}"
    rounded: "{rounded.square}"
    padding: "0 18px"
    height: "48px"
---

# Design System: Larissa Rodrigues de Castro Portfolio

## Overview

**Creative North Star: "Circuito de confiança"**

The portfolio treats professional experience as a clear signal path: the visitor can see the technical focus, follow the work history, and reach the curriculum or contact links without guesswork. Its visual language adapts the premium navy-and-copper reference requested by Larissa to computing, hardware, and technical support.

Deep navy and graphite establish the working surface. Blue marks active routes and primary actions; copper appears as a restrained connection point. Circuit traces frame the portrait, while the experience timeline makes the career history the central proof.

**Key Characteristics:**
- High-contrast navy surfaces with blue and copper accents.
- Precise rectangular geometry and fine technical linework.
- Verified curriculum content, without unsupported skill ratings.

## Colors

The palette pairs a deep navy base with readable cool text, blue routing, and copper details.

### Primary
- **Deep Navy** (#07131f): Main page background and navigation.
- **Signal Blue** (#70c8ee): Primary actions, active navigation, and circuit emphasis.

### Secondary
- **Graphite Surface** (#0e1d2b): Raised content and contact panels.
- **Copper Contact** (#e5a56a): Secondary emphasis, timeline dates, and circuit endpoints.

### Neutral
- **Deep Field** (#050d16): Footer and darkest background.
- **Foreground** (#f3f6f7): Headings and primary text.
- **Cool Secondary Text** (#b2c0ca): Supporting copy.
- **Technical Divider** (#293d4d): Section and list separators.

## Typography

**Display Font:** Inter (with Segoe UI and Arial fallbacks)
**Body Font:** Inter (with Segoe UI and Arial fallbacks)
**Label/Mono Font:** Cascadia Code (with SFMono-Regular and Consolas fallbacks)

**Character:** Compact, direct display text gives the name and section titles a confident hierarchy. Monospace is reserved for small technical labels and dates.

### Hierarchy
- **Display** (650, `clamp(3.2rem, 7vw, 6.2rem)`, `.96` line-height): Name in the first viewport.
- **Headline** (620, `clamp(2.2rem, 4.5vw, 3.8rem)`, `1.05` line-height): Section headings.
- **Title** (620–650, `1.06–1.42rem`): Education, experience, and contact titles.
- **Body** (400, `1rem`, `1.65` line-height): Explanatory and descriptive copy.
- **Label** (400, `.64–.77rem`, tracked uppercase where used): Dates and technical labels.
- **Responsive display** (`clamp(3rem, 13vw, 5rem)`): Smaller-screen name treatment.
- **Responsive headline** (`clamp(2.25rem, 10vw, 3.25rem)`): Smaller-screen section headings.
- **Supporting text sizes** (`.58rem`, `.63rem`, `.64rem`, `.68rem`, `.72rem`, `.73rem`, `.74rem`, `.76rem`, `.77rem`, `.78rem`, `.8rem`, `.82rem`, `.85rem`, `.86rem`, `.88rem`, `.9rem`, `.91rem`, `.94rem`, `.95rem`, `.98rem`, `1.05rem`, `1.06rem`, `1.08rem`, `1.12rem`, `1.2rem`, `1.28rem`): Context-specific navigation, metadata, body, and title sizes.

## Layout

The page uses a centered 1180px maximum container with 24px side gutters, reduced to 18px below 760px and 14px below 420px. The hero pairs text and portrait on wider screens, then stacks them on smaller screens. Education and experience use a two-column heading/content arrangement on desktop and a single column on mobile. Experience stays a dated timeline; education stays a ruled list rather than a grid of cards.

Primary layout breakpoints are 980px, 760px, and 420px. Keep content readable at narrow widths without horizontal scrolling. The mobile navigation becomes a disclosure controlled by a button, while the curriculum action remains available in the hero.

## Elevation & Depth

The design is flat at rest and does not use drop shadows. Depth comes from solid tonal surfaces, thin dividers, the framed portrait, and the overlaid circuit paths. Avoid decorative blur or glowing halos.

## Shapes

Components use square corners and clear rectangular silhouettes. One-pixel borders and carefully routed circuit lines carry the technical character; avoid rounded, pill-heavy containers.

## Components

### Buttons
- **Shape:** Square, with a transparent or solid fill and no rounded corners.
- **Primary:** Signal blue background with dark text, 48px minimum height, and 18px horizontal padding.
- **Secondary:** Transparent background with a fine slate border and light text.
- **Hover / Focus:** Small vertical hover lift; keyboard focus uses a visible copper outline.

### Cards / Containers
- **Background:** Solid navy or graphite surfaces.
- **Border:** Fine slate or blue/copper framing lines.
- **Internal Padding:** 24–30px for the contact panel; lists use open rows with separators.
- **Shadow Strategy:** None; separate surfaces by tone and linework.

### Navigation
- **Desktop:** Sticky dark bar with understated links and a blue underline for the active section.
- **Mobile:** Collapsible vertical list controlled by a button with an updated `aria-expanded` state; Escape and link selection close it.

### Experience Timeline
- Dates sit beside a vertical line on wide screens and above each entry on mobile. The copper date and blue point markers make chronology scannable.

## Do's and Don'ts

### Do:
- **Do** keep education, dates, roles, and experience aligned with the supplied curriculum.
- **Do** use circuit geometry as a framing device, not as a substitute for content.
- **Do** preserve clear focus states and the responsive mobile navigation.

### Don't:
- **Don't** add skill percentages, certifications, projects, or outcomes not documented in the curriculum.
- **Don't** use decorative grid backgrounds, generic neon effects, or icon cards as the page structure.
- **Don't** let the circuit theme imply electronics repair experience that the curriculum does not state.
