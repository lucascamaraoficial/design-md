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

Wise transforms financial infrastructure into a bold editorial experience. Instead of behaving like a traditional banking dashboard filled with dense tables, gradients, and conservative blue surfaces, the interface behaves more like a campaign system: giant headlines dominate the viewport, actions are oversized and optimistic, and the UI removes almost every unnecessary decorative layer.

The visual identity is built around three core signals:
- ultra-heavy Wise Sans typography
- vibrant lime-green interactions
- warm off-white surfaces with minimal shadows

The headline system is the defining characteristic of the brand. Display typography reaches extreme scales (`{typography.display-mega}` at 126px / 900) with an unusually compressed line-height of 0.85. Headlines feel stamped, urgent, and physical — closer to protest signage or editorial campaigns than enterprise fintech interfaces.

Unlike most financial products that rely on navy, cobalt, or cold grayscale palettes, Wise intentionally introduces warmth. The base canvas (`{colors.canvas}` — #f6f8f3) carries a subtle green tint, while the primary lime accent (`{colors.primary}` — #9fe870) injects energy without feeling aggressive. The combination creates a softer and more approachable interpretation of fintech.

The interaction language is equally distinctive. Buttons do not rely on heavy hover shadows or glow effects. Instead, Wise uses physical scale transformations:
- hover → `scale(1.05)`
- active → `scale(0.95)`

This makes interactions feel tactile and alive while preserving the system's minimal aesthetic.

The shape language is intentionally oversized and human:
- pill buttons (`{rounded.full}`)
- large rounded cards (`{rounded.lg}` / `{rounded.xl}`)
- circular utility controls
- generous spacing between modules

There are almost no sharp corners in the experience.

The layout rhythm alternates between:
- giant billboard-style hero sections
- compact transfer/conversion utilities
- comparison bands
- lime-highlighted statistical callouts
- dark financial showcase surfaces

Wise avoids decorative complexity:
- no gradients
- almost no traditional shadows
- no glassmorphism
- no neumorphism
- no excessive outlines

Depth is created almost entirely through:
- typography scale
- spacing rhythm
- contrast between green / cream / near-black
- thin ring borders

The result feels unusually confident for a fintech platform: energetic without being playful, minimal without feeling sterile, and premium without relying on luxury visual tropes.

**Key Characteristics:**
- Billboard-scale Wise Sans typography
- Ultra-tight display line-height (0.85)
- Lime-green primary CTA system
- Warm cream/off-white canvas
- Ring-border elevation instead of shadow-heavy depth
- Pill-shaped interaction system
- Scale-based hover animations
- Inter semibold body typography
- Minimal decorative styling
- Editorial campaign-style composition

## Usage Notes

### Do
- Use oversized headlines aggressively.
- Keep primary CTAs lime-green and highly visible.
- Preserve large spacing between sections.
- Use pill buttons for most important actions.
- Prefer ring borders over strong shadows.
- Maintain warm off-white surfaces instead of pure white.
- Let typography carry hierarchy instead of visual effects.

### Don't
- Do not introduce blue fintech palettes.
- Do not use gradients or glass effects.
- Do not add aggressive drop shadows.
- Do not use tiny typography scales.
- Do not over-densify layouts.
- Do not use sharp corner radii.
- Do not make buttons visually flat or lifeless.
