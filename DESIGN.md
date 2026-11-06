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
  button-hover: "#a4e0fa"
  secondary-button-border: "#476071"
  circuit-line: "#32779a"
  contact-border: "#3c5262"
  light-background: "#f2f7fa"
  light-background-deep: "#e4edf3"
  light-surface: "#eaf2f7"
  light-foreground: "#102331"
  light-secondary-text: "#405969"
  light-signal-blue: "#0879a8"
  light-copper: "#89501f"
  light-button-hover: "#06688f"
  light-secondary-button-border: "#668191"
  light-circuit-line: "#267894"
  light-contact-border: "#76909f"
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

The portfolio treats professional experience as a clear signal path: the visitor can see the technical focus, follow the work history, and reach the curriculum or contact links without guesswork. Its visual language adapts the premium navy-and-copper reference requested by Larissa to computing, hardware, and technical support, with a matching light theme and circuits spanning the page.

Both themes use translucent section surfaces so the full-page circuit network stays visible behind the content. Blue marks active routes and primary actions; copper appears as a restrained connection point. Animated signal dashes add motion to the circuitry, while the experience timeline makes the career history the central proof.

**Key Characteristics:**
- Matching light and dark surfaces with blue routing and copper connection points.
- Precise rectangular geometry and fine technical linework.
- A persistent animated circuit backdrop, with reduced-motion support.
- A one-time signal journey from the hero through training, experience, and contact.
- Verified curriculum content, without unsupported skill ratings.

## Colors

The two themes share the same semantic roles: blue routes and controls, copper marks nodes and secondary emphasis, and text/divider tokens keep content legible over translucent surfaces.

### Dark
- **Deep Navy** (#07131f): Main page background and navigation.
- **Deep Field** (#050d16): Footer and darkest background.
- **Graphite Surface** (#0e1d2b): Section surface.
- **Foreground** (#f3f6f7): Headings and primary text.
- **Cool Secondary Text** (#b2c0ca): Supporting copy.
- **Signal Blue** (#70c8ee): Primary actions, active navigation, and circuit emphasis.
- **Copper Contact** (#e5a56a): Secondary emphasis, timeline dates, and circuit endpoints.
- **Blue Hover** (#a4e0fa): Hover fill for the primary action.

### Light
- **Cool Mist** (#f2f7fa): Main page background and navigation.
- **Blue Gray** (#e4edf3): Deep surface and footer.
- **Light Surface** (#eaf2f7): Section surface.
- **Ink** (#102331) and **secondary text** (#405969): Main and supporting text.
- **Signal Blue** (#0879a8): Actions, active navigation, and circuit emphasis.
- **Copper** (#89501f): Circuit nodes and secondary emphasis.
- **Deep Blue Hover** (#06688f): Hover fill for the primary action, retaining white-text contrast.

### Shared
- **Technical Divider** (#293d4d): Dark theme separators; light theme uses a softer blue-gray divider.
- Circuit lines stay decorative and low-opacity so they do not compete with content.

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
- **Background:** Theme-matched translucent navy or pale-blue surfaces.
- **Border:** Fine slate or blue/copper framing lines.
- **Internal Padding:** 24–30px for the contact panel; lists use open rows with separators.
- **Shadow Strategy:** None; separate surfaces by tone and linework.

### Navigation
- **Desktop:** Sticky theme-matched bar with understated links and a blue underline for the active section.
- **Mobile:** Collapsible vertical list controlled by a button with an updated `aria-expanded` state; Escape and link selection close it.
- **Theme:** A labeled, keyboard-focusable control switches light/dark, follows system preference on first visit, and remembers an explicit choice.

### Experience Timeline
- Dates sit beside a vertical line on wide screens and above each entry on mobile. The copper date and blue point markers make chronology scannable.

### Circuit Backdrop
A fixed, full-viewport SVG routes behind the page content. Low-opacity tracks and node points span the visible page; short dashed signal pulses travel along selected paths, with the animation paused when the tab is hidden. Translucent section fills reveal the routes.

### Motion
The hero introduces Larissa's role, contact action, and portrait in a single staggered signal sequence. As visitors scroll, headings draw their blue routing line and education, career, and contact items arrive in reading order. Small circuit nodes pulse, buttons respond to hover/press, the active navigation route draws into place, and the mobile menu opens along a short vertical path. Observed elements animate once and then remain still. The content is visible without JavaScript, and `prefers-reduced-motion` disables motion while preserving every item and state.

## Do's and Don'ts

### Do:
- **Do** keep education, dates, roles, and experience aligned with the supplied curriculum.
- **Do** use circuit geometry as a framing device, not as a substitute for content.
- **Do** preserve clear focus states and the responsive mobile navigation.

### Don't:
- **Don't** add skill percentages, certifications, projects, or outcomes not documented in the curriculum.
- **Don't** use decorative grid backgrounds, generic neon effects, or icon cards as the page structure.
- **Don't** let the circuit theme imply electronics repair experience that the curriculum does not state.
