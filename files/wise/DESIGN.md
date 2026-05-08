---
version: alpha
name: Wise
description: A bold fintech interface built around billboard-scale typography, lime-green CTAs, and warm off-white surfaces. Wise Sans headlines run at ultra-heavy weights with dense line-height, while Inter handles body copy with confident semibold rhythm. The system avoids decorative gradients and traditional shadows, relying instead on ring borders, oversized rounded cards, and scale-based interactions.

colors:
  primary: "#9fe870"
  primary-active: "#cdffad"
  primary-disabled: "#e2f6d5"
  primary-dark: "#163300"
  ink: "#0e0f0c"
  body: "#454745"
  muted: "#868685"
  muted-soft: "#a4a4a3"
  hairline: "#d8ddd4"
  hairline-soft: "#e8ebe6"
  canvas: "#f6f8f3"
  surface-soft: "#e8ebe6"
  surface-card: "#ffffff"
  surface-dark: "#0e0f0c"
  surface-dark-elevated: "#1b1d1a"
  on-primary: "#163300"
  on-dark: "#ffffff"
  success: "#054d28"
  warning: "#ffd11a"
  error: "#d03238"
  accent-cyan: "#38c8ff"
  accent-orange: "#ffc091"

typography:
  display-mega:
    fontFamily: "'Wise Sans', Inter, sans-serif"
    fontSize: 126px
    fontWeight: 900
    lineHeight: 0.85
    letterSpacing: 0

  display-xl:
    fontFamily: "'Wise Sans', Inter, sans-serif"
    fontSize: 96px
    fontWeight: 900
    lineHeight: 0.85
    letterSpacing: 0

  display-lg:
    fontFamily: "'Wise Sans', Inter, sans-serif"
    fontSize: 64px
    fontWeight: 900
    lineHeight: 0.85
    letterSpacing: 0

  display-md:
    fontFamily: "'Wise Sans', Inter, sans-serif"
    fontSize: 40px
    fontWeight: 900
    lineHeight: 0.9
    letterSpacing: 0

  title-lg:
    fontFamily: "Inter, sans-serif"
    fontSize: 26px
    fontWeight: 600
    lineHeight: 1.23
    letterSpacing: -0.39px

  title-md:
    fontFamily: "Inter, sans-serif"
    fontSize: 22px
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: -0.396px

  body-lg:
    fontFamily: "Inter, sans-serif"
    fontSize: 18px
    fontWeight: 600
    lineHeight: 1.44
    letterSpacing: -0.108px

  body-md:
    fontFamily: "Inter, sans-serif"
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.44
    letterSpacing: 0.18px

  body-sm:
    fontFamily: "Inter, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: -0.084px

  caption:
    fontFamily: "Inter, sans-serif"
    fontSize: 12px
    fontWeight: 600
    lineHeight: 1.33
    letterSpacing: -0.084px

  button:
    fontFamily: "Inter, sans-serif"
    fontSize: 18px
    fontWeight: 600
    lineHeight: 1
    letterSpacing: -0.108px

  nav-link:
    fontFamily: "Inter, sans-serif"
    fontSize: 14px
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: 0

rounded:
  xs: 4px
  sm: 10px
  md: 16px
  lg: 30px
  xl: 40px
  full: 9999px

spacing:
  xxs: 2px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  section: 96px

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.primary-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.full}"
    padding: 14px 24px
    height: 52px

  button-primary-active:
    backgroundColor: "{colors.primary-active}"
    textColor: "{colors.primary-dark}"
    rounded: "{rounded.full}"

  button-primary-disabled:
    backgroundColor: "{colors.primary-disabled}"
    textColor: "{colors.muted}"
    rounded: "{rounded.full}"

  button-secondary:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.full}"
    padding: 14px 24px
    height: 52px

  button-secondary-dark:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.full}"
    padding: 14px 24px

  button-text-link:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.body-lg}"

  button-icon-circle:
    backgroundColor: "{colors.surface-soft}"
    textColor: "{colors.ink}"
    rounded: "{rounded.full}"
    size: 40px

  text-link:
    backgroundColor: transparent
    textColor: "{colors.primary-dark}"
    typography: "{typography.body-lg}"

  top-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    height: 72px

  hero-band:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.display-xl}"
    padding: 96px

  hero-card-green:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.primary-dark}"
    typography: "{typography.display-lg}"
    rounded: "{rounded.xl}"
    padding: 48px

  feature-card:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.title-md}"
    rounded: "{rounded.lg}"
    padding: 32px

  pricing-card:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.body-lg}"
    rounded: "{rounded.xl}"
    padding: 40px

  pricing-card-dark:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body-lg}"
    rounded: "{rounded.xl}"
    padding: 40px

  stats-band:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.primary-dark}"
    typography: "{typography.display-md}"
    rounded: "{rounded.lg}"
    padding: 48px

  transfer-card:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.lg}"
    padding: 32px

  currency-selector:
    backgroundColor: "{colors.surface-soft}"
    textColor: "{colors.ink}"
    typography: "{typography.body-lg}"
    rounded: "{rounded.full}"
    padding: 12px 20px
    height: 48px

  input-field:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.md}"
    padding: 14px 16px
    height: 52px

  badge-positive:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.primary-dark}"
    typography: "{typography.caption}"
    rounded: "{rounded.full}"
    padding: 6px 12px

  footer:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body-sm}"
    padding: 64px

---

## Overview

Wise reimagines financial infrastructure as a bold editorial experience rather than a traditional banking dashboard. The interface avoids the cold visual language commonly associated with fintech products and instead builds its identity around oversized typography, warm surfaces, optimistic color, and simplified interaction patterns.

The experience feels closer to a modern publishing platform or campaign system than to enterprise banking software.

---

### Typography as the Main Visual System

Typography is the single most dominant element across the entire experience.

Wise Sans is used at extremely heavy weights (`900`) with compressed line-heights (`0.85`) to create headlines that feel physically stamped onto the interface. Headlines are intentionally oversized and frequently occupy entire sections without relying on additional decorative elements.

Large marketing areas often contain only:
- one massive headline
- one supporting sentence
- one CTA

The system trusts typography to carry hierarchy, emotion, and rhythm.

Unlike traditional SaaS products that rely on:
- sidebars
- dashboard density
- widget systems
- separators
- elevated cards

Wise builds hierarchy almost entirely through:
- scale
- spacing
- typography rhythm
- controlled contrast

---

### Color Philosophy

The Wise palette intentionally rejects conventional fintech aesthetics.

There are:
- no dark navy palettes
- no enterprise blues
- no metallic gradients
- no glossy surfaces
- no futuristic neon accents

Instead, the identity is built around three core surfaces:

- warm off-white canvas (`{colors.canvas}`)
- near-black typography (`{colors.ink}`)
- vibrant lime-green highlights (`{colors.primary}`)

The lime-green accent is used strategically and sparingly.

Rather than flooding the interface with saturated color, green appears mainly in:
- primary CTAs
- onboarding moments
- transfer confirmations
- conversion modules
- statistical highlight bands
- interaction feedback

This restraint is what gives the brand its distinctive energy.

---

### Surface and Depth Language

Wise intentionally minimizes visual decoration.

The interface avoids:
- glassmorphism
- neumorphism
- layered gradients
- dramatic shadows
- excessive elevation systems

Instead, depth is created through:
- spacing rhythm
- tonal separation
- ring borders
- typography scale
- contrast between light and dark sections

Most surfaces remain visually flat while still feeling tactile and premium.

Cards use:
- oversized corner radii
- subtle borders
- minimal shadow depth
- generous padding

The result feels softer and significantly less stressful than traditional financial interfaces.

---

### Shape Language

The entire product uses oversized rounded geometry to reinforce approachability.

Core patterns include:
- `{rounded.full}` pill buttons
- `{rounded.lg}` utility cards
- `{rounded.xl}` hero containers
- circular icon controls
- large touch-friendly interaction areas

Sharp corners are almost entirely absent from the interface.

Even complex financial utilities maintain a softened visual appearance.

---

### Interaction Philosophy

Interactions are intentionally restrained and physical.

Wise avoids:
- glowing hover states
- flashy animations
- exaggerated transitions
- complex motion systems

Instead, interactions rely mainly on scale transformations.

Typical hover behavior:
- `transform: scale(1.03)`
- `transform: scale(1.05)`

Active states slightly compress:
- `transform: scale(0.96)`

This creates tactile feedback without adding visual noise.

The interface feels alive while remaining minimal.

---

### Layout Rhythm

The layout system alternates between:
- billboard-scale hero sections
- compact conversion utilities
- dark informational comparison bands
- editorial content blocks
- oversized statistical highlights
- simplified onboarding modules

This creates pacing similar to modern editorial layouts instead of traditional application dashboards.

The experience constantly balances:
- emotional branding
- financial utility
- conversion clarity
- product education

without overwhelming the user.

---

### Emotional Positioning

Traditional fintech platforms often attempt to communicate trust through:
- technical density
- corporate rigidity
- financial seriousness
- enterprise visual language

Wise takes the opposite approach.

Trust is created through:
- clarity
- simplicity
- breathing room
- visual confidence
- reduced interface anxiety

The experience feels:
- optimistic instead of institutional
- human instead of mechanical
- global instead of regional
- editorial instead of enterprise
- modern without feeling experimental

The system communicates that financial infrastructure can feel approachable, lightweight, and emotionally positive while still maintaining credibility.

---

### Key Characteristics

- Billboard-scale typography
- Ultra-heavy Wise Sans headlines
- Tight 0.85 display line-height
- Lime-green CTA system
- Warm off-white surfaces
- Oversized rounded geometry
- Editorial composition rhythm
- Minimal elevation language
- Scale-based hover interactions
- Ring-border depth system
- Humanized fintech UX
- Calm financial interface design
- Conversion-first hierarchy
- Softened utility modules
- Minimal decorative styling
- Anti-corporate visual direction