---
name: Adithya Hari Bhat Cinematic Editorial Portfolio
description: Futuristic cinematic portfolio with Space Grotesk, Inter, and JetBrains Mono typography
colors:
  primary: "#10b981"
  secondary: "#059669"
  accent-glow: "rgba(16, 185, 129, 0.15)"
  neutral-bg: "#050505"
  surface: "#0c0c0c"
  surface-elevated: "#141414"
  text-primary: "#ffffff"
  text-muted: "#8c8c8c"
  border-subtle: "rgba(255, 255, 255, 0.08)"
typography:
  display:
    fontFamily: "Space Grotesk, sans-serif"
    fontSize: "5.5rem"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.04em"
  headline:
    fontFamily: "Space Grotesk, sans-serif"
    fontSize: "3rem"
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: "-0.03em"
  body:
    fontFamily: "Inter, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.7
  label:
    fontFamily: "JetBrains Mono, monospace"
    fontSize: "0.75rem"
    fontWeight: 600
    letterSpacing: "0.25em"
rounded:
  sm: "6px"
  md: "12px"
  lg: "24px"
  full: "9999px"
spacing:
  sm: "8px"
  md: "16px"
  lg: "32px"
  xl: "64px"
components:
  nav-pill:
    backgroundColor: "rgba(10, 10, 10, 0.8)"
    textColor: "{colors.text-primary}"
    rounded: "{rounded.full}"
    padding: "12px 24px"
  cta-button:
    backgroundColor: "{colors.text-primary}"
    textColor: "{colors.neutral-bg}"
    rounded: "{rounded.full}"
    padding: "16px 32px"
---

# Design System: Adithya Hari Bhat Cinematic Editorial Portfolio

## Overview

**Creative North Star: "The Futuristic Cinematic Monolith"**

A sophisticated, modern, futuristic aesthetic inspired by premium developer portfolios and award-winning creative agency websites. The typography pairing combines the geometry of **Space Grotesk** for oversized, bold display headings with the legibility of **Inter** for narrative copy and **JetBrains Mono** for technical telemetry and code blocks.

**Key Characteristics:**
- **Space Grotesk Display**: Monumental name, section headings, and titles set with tight letter spacing (-0.03em to -0.04em).
- **Inter Body & Navigation**: Generously spaced, clean, comfortable body reading with high-contrast neutral palette.
- **JetBrains Mono Metadata**: Small technical tags, track labels, and code snippets.
- **Selective Emerald Highlights**: Sparing use of forest green / emerald (#10b981) to accentuate critical words.

## Colors

### Primary
- **Emerald Accent** (#10b981): Highlights key words and active interactive elements.

### Secondary
- **Forest Green** (#059669): Ambient gradients and glow accents.

### Neutral
- **Deep Black Ground** (#050505): Canvas backdrop.
- **Charcoal Surface** (#0c0c0c): Elevated cards and code containers.
- **Crisp White** (#ffffff): Major titles and active text.
- **Muted Grey** (#8c8c8c): Secondary narrative body and telemetry coordinates.

## Typography

**Display Font:** Space Grotesk (with sans-serif fallback)  
**Body Font:** Inter (with system-ui fallback)  
**Label/Mono Font:** JetBrains Mono  

- **Display** (800, clamp(3rem, 9vw, 5.5rem), -0.04em): Oversized, bold Space Grotesk personal name and section titles.
- **Headline** (700, clamp(2rem, 5vw, 3rem), -0.03em): Space Grotesk section titles.
- **Body** (400, 1rem–1.125rem, 1.7): Inter text for natural reading ergonomics.
- **Label** (600, 0.75rem, +0.25em, uppercase): JetBrains Mono minimal track markers (`01 // ABOUT ME`, `PORTFOLIO 2026`).

## Layout

- Full viewport scroll orchestration across 8 cinematic acts.
- Minimal floating glass capsule navigation.

## Elevation & Depth

- Parallax scroll depth separating background portrait, ambient emerald smoke, and typography.

## Components

### Floating Navigation Pill
- Ultra-minimal glass capsule with Inter font and active emerald indicator.

### Editorial Project Feature
- Large container with Space Grotesk title, Inter narrative, and JetBrains Mono code block.

## Do's and Don'ts

### Do:
- **Do** use Space Grotesk exclusively for headings, hero text, and section titles.
- **Do** use Inter for body text, navigation links, and descriptions.
- **Do** use JetBrains Mono for small technical labels, metadata, and code blocks.
- **Do** use tight letter spacing for oversized headings.

### Don't:
- **Don't** introduce a fourth font family.
- **Don't** use generic percentage-based skill progress bars.
