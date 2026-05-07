---
version: alpha
name: Google
description: A highly systematic product-and-brand interface built on an ultra-clean white canvas, restrained typography, mathematically balanced spacing, and Google's iconic multi-color identity system. The experience relies on whitespace, compositional rhythm, and functional hierarchy rather than aggressive decoration. Product surfaces prioritize clarity, utility, accessibility, and scalable interaction patterns across billions of users and thousands of UI contexts.

colors:
  blue:
    primary: "#1a73e8"
    hover: "#1558b0"
    soft: "#e8f0fe"
  red:
    primary: "#ea4335"
  yellow:
    primary: "#fbbc04"
  green:
    primary: "#34a853"
  ink:
    primary: "#202124"
    secondary: "#3c4043"
    muted: "#5f6368"
  surface:
    canvas: "#ffffff"
    soft: "#f8f9fa"
    elevated: "#ffffff"
    strong: "#e8eaed"
  border:
    default: "#dadce0"
    strong: "#c4c7c5"
  semantic:
    success: "#34a853"
    warning: "#fbbc04"
    error: "#ea4335"
    info: "#1a73e8"

fonts:
  primary:
    family: "Google Sans, Roboto, Arial, sans-serif"
  secondary:
    family: "Roboto, Arial, sans-serif"

spacing:
  xxs: 2px
  xs: 4px
  sm: 8px
  md: 12px
  base: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  section: 72px

rounded:
  xs: 4px
  sm: 8px
  md: 12px
  lg: 16px
  xl: 24px
  full: 9999px

typography:
  display-xl:
    fontFamily: "Google Sans"
    fontSize: 64px
    fontWeight: 500
    lineHeight: 1.05
  display-lg:
    fontFamily: "Google Sans"
    fontSize: 48px
    fontWeight: 500
    lineHeight: 1.1
  display-md:
    fontFamily: "Google Sans"
    fontSize: 36px
    fontWeight: 500
    lineHeight: 1.15
  title-lg:
    fontFamily: "Google Sans"
    fontSize: 24px
    fontWeight: 500
    lineHeight: 1.3
  title-md:
    fontFamily: "Google Sans"
    fontSize: 20px
    fontWeight: 500
    lineHeight: 1.35
  body-lg:
    fontFamily: "Roboto"
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.6
  body-md:
    fontFamily: "Roboto"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.6
  body-sm:
    fontFamily: "Roboto"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
  caption:
    fontFamily: "Roboto"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.4
  button:
    fontFamily: "Google Sans"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1

components:
  button-primary:
    backgroundColor: "{colors.blue.primary}"
    textColor: "#ffffff"
    rounded: "{rounded.full}"
    typography: "{typography.button}"
    padding: 10px 24px
    height: 40px

  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.blue.primary}"
    borderColor: "{colors.border.default}"
    rounded: "{rounded.full}"
    typography: "{typography.button}"
    padding: 10px 24px
    height: 40px

  top-nav:
    backgroundColor: "{colors.surface.canvas}"
    textColor: "{colors.ink.primary}"
    height: 64px

  search-bar:
    backgroundColor: "{colors.surface.canvas}"
    borderColor: "{colors.border.default}"
    rounded: "{rounded.full}"
    height: 56px
    padding: 0 24px

  feature-card:
    backgroundColor: "{colors.surface.canvas}"
    borderColor: "{colors.border.default}"
    rounded: "{rounded.lg}"
    padding: 32px

  floating-card:
    backgroundColor: "{colors.surface.elevated}"
    rounded: "{rounded.lg}"
    padding: 24px

  chip:
    backgroundColor: "{colors.surface.soft}"
    textColor: "{colors.ink.secondary}"
    rounded: "{rounded.full}"
    padding: 8px 16px

  footer:
    backgroundColor: "{colors.surface.soft}"
    textColor: "{colors.ink.secondary}"
    padding: 64px

---

## Overview

Google's interface system is designed around clarity, scalability, neutrality, and computational consistency. Unlike expressive consumer brands that rely heavily on emotional UI styling, Google's design language intentionally minimizes visual friction so that products, information, and interactions become the primary focus.

The visual atmosphere is built on a pure white canvas (`{colors.surface.canvas}`), soft neutral surfaces, restrained borders, and sparse accent color usage. Google's signature colors — blue, red, yellow, and green — are rarely used together in interface components; instead, the system typically uses Google Blue (`{colors.blue.primary}` — #1a73e8) as the dominant action color while the remaining colors appear in branding, illustration systems, loading indicators, charts, onboarding moments, and product iconography.

Typography combines **Google Sans** for display hierarchy and navigation with **Roboto** for body content and dense interface readability. The system avoids extreme font weights and instead relies on spacing, alignment, scale progression, and whitespace to create hierarchy.

The entire system feels mathematically balanced. Elements align tightly to a structured spacing rhythm, interactions prioritize accessibility, and components are intentionally generic enough to scale across Search, Gmail, Workspace, Android, Cloud, Gemini, Maps, and thousands of internal tools.

Unlike highly stylized brands, Google treats interface chrome as infrastructure rather than decoration.

**Key Characteristics:**
- Ultra-clean white interface system with restrained accent usage.
- Blue (`{colors.blue.primary}`) acts as the dominant CTA and interaction color.
- Multi-color identity appears mostly in branding moments rather than interface saturation.
- Typography relies on Google Sans + Roboto.
- Rounded geometry is soft but controlled — no aggressive skeuomorphism.
- Large whitespace blocks establish hierarchy instead of shadows or gradients.
- Minimal elevation system with soft shadows and light borders.
- Components prioritize accessibility, predictability, and scalability.
- Interface density adapts fluidly across desktop, tablet, and mobile.

## Colors

### Brand Identity
- **Google Blue** (`{colors.blue.primary}` — #1a73e8): Primary action color for buttons, links, focused states, and navigation highlights.
- **Google Red** (`{colors.red.primary}` — #ea4335): Error states, product branding, and identity moments.
- **Google Yellow** (`{colors.yellow.primary}` — #fbbc04): Warning states and illustration accents.
- **Google Green** (`{colors.green.primary}` — #34a853): Success states and positive metrics.

### Surface System
- **Canvas** (`{colors.surface.canvas}` — #ffffff): Default surface.
- **Soft Surface** (`{colors.surface.soft}` — #f8f9fa): Secondary containers, chips, navigation backgrounds.
- **Elevated Surface** (`{colors.surface.elevated}` — #ffffff): Dialogs and floating cards.
- **Strong Surface** (`{colors.surface.strong}` — #e8eaed): Dividers and structural containers.

### Text System
- **Primary Ink** (`{colors.ink.primary}` — #202124): Main content and headings.
- **Secondary Ink** (`{colors.ink.secondary}` — #3c4043): Supporting content.
- **Muted Ink** (`{colors.ink.muted}` — #5f6368): Captions and metadata.

## Typography

### Philosophy
Google's typography system emphasizes neutrality, readability, and scale consistency. Instead of dramatic typographic personality, hierarchy emerges from spacing, sizing, and rhythm.

### Principles
- Google Sans is reserved for branding, navigation, and major hierarchy.
- Roboto handles dense body content and productivity-heavy interfaces.
- Font weights remain moderate.
- Large display headlines often use weight 400–500 instead of heavy 700+.
- Body typography prioritizes long-form readability.
- Mobile and desktop scales remain visually consistent.

## Layout

### Spacing Rhythm
The system uses a highly consistent 4px baseline grid with major layouts aligned around 8px multiples. Large editorial sections expand into 72px vertical spacing while utility-heavy interfaces compress spacing density dynamically.

### Containers
- Marketing layouts use centered max-width containers.
- Workspace products prioritize adaptive fluid layouts.
- Search-driven products minimize unnecessary gutters.
- Cards and modules align through predictable spacing increments.

### Whitespace Strategy
Whitespace is a structural tool rather than decoration. Google frequently allows large empty areas around content to improve readability and reduce cognitive overload.

## Elevation

Google's elevation system is intentionally restrained.

### Characteristics
- Soft shadows with low opacity.
- Light border separation instead of dramatic depth.
- Floating surfaces appear subtly lifted.
- Most pages remain visually flat.
- Elevation is used functionally, not decoratively.

## Components

### Buttons
Primary buttons use Google Blue backgrounds with white text and fully rounded pill geometry. Secondary buttons are often outline-only.

### Navigation
Top navigation systems are sparse, lightweight, and heavily whitespace-driven. Navigation labels typically use Google Sans.

### Search
Search bars are one of Google's strongest visual signatures:
- large pill geometry;
- subtle shadows;
- centered interaction model;
- icon-led actions;
- minimal framing.

### Cards
Cards use:
- soft borders;
- restrained elevation;
- large internal padding;
- minimal decoration;
- modular responsiveness.

### Chips
Chips and filters use rounded pill geometry with low-contrast surfaces.

## Responsive Behavior

| Breakpoint | Behavior |
|---|---|
| Mobile | Navigation collapses into compact utility flows; spacing compresses; cards stack vertically. |
| Tablet | Multi-column layouts begin appearing; cards expand horizontally. |
| Desktop | Full whitespace rhythm, centered containers, large editorial spacing. |
| Wide | Layout width caps to preserve readability and structural rhythm. |

## Accessibility

Google's system strongly prioritizes:
- keyboard navigation;
- readable contrast;
- predictable interaction patterns;
- scalable typography;
- screen-reader compatibility;
- large touch targets;
- consistent semantic structure.

## Known Gaps

- Internal Google products frequently diverge slightly from the canonical Material ecosystem.
- Some Workspace products still contain legacy visual patterns.
- Different Google divisions apply different density strategies.
- Gemini, Cloud, Workspace, Android, and Search each introduce localized component variations.
- Exact spacing tokens vary between marketing and product surfaces.
