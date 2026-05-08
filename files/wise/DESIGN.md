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

Wise is a bold, optimistic fintech system built around oversized typography, soft off-white surfaces, and a single lime-green accent. The interface behaves more like a campaign poster than a traditional banking dashboard — giant headlines dominate the page while UI chrome fades into the background.

The visual identity depends on three ingredients:
- ultra-heavy Wise Sans headlines
- bright lime-green CTAs
- minimal elevation with ring-only borders

Unlike enterprise fintech products, Wise avoids dark blues and hard-edged cards. The entire experience feels warmer, friendlier, and more human. Rounded containers, pill buttons, and scale-based hover states reinforce that approachable feeling.

The layout rhythm alternates between:
- oversized editorial hero sections
- compact transfer utility modules
- dark financial comparison bands
- lime-highlighted conversion callouts

There are no decorative gradients, neumorphism effects, or aggressive glass layers. Depth comes almost entirely from spacing, typography scale, and subtle ring borders.

**Key Characteristics:**
- Massive Wise Sans headlines at weight 900
- Tight 0.85 display line-height
- Lime-green CTA system (`{colors.primary}`)
- Pill-shaped buttons and selectors
- Ring-style borders instead of traditional shadows
- Inter semibold body typography
- Warm off-white canvas instead of pure white
- Scale-based hover interaction language

## Usage Notes

- Prefer giant headlines over dense interface chrome.
- Use lime green sparingly for important actions only.
- Keep surfaces warm and slightly tinted.
- Avoid strong shadows and gradients.
- Maintain generous spacing between sections.
- Buttons should feel soft, oversized, and touch-friendly.
