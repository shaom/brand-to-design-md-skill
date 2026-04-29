---
version: alpha
name: Poolside
description: Off-white research-lab interface language with mono navigation, sharp grid structure, black text, blue-violet actions, code-first panels, and enterprise-grade model storytelling.
sources:
  - https://poolside.ai/
  - https://poolside.ai/models
  - https://poolside.ai/enterprise
  - https://poolside.ai/blog/introducing-laguna-xs2-m1
  - https://poolside.ai/blog/laguna-a-deeper-dive
notes:
  - Derived from Poolside public pages, observed DOM/CSS variables, public font declarations, and official brand asset links exposed in the site footer.
  - The public site exposes press-kit, logo, and logomark download links, but this file does not grant trademark permission. Use official marks only when the project has rights to do so.
  - Some component choices are inferred from Poolside page behavior: flat rectangular surfaces, mono uppercase action labels, left-side navigation, highlighted hover states, and code/model comparison panels.
colors:
  background: "#FBFAF6"
  surface: "#FFFFFF"
  surface-muted: "#F7F6EF"
  surface-subtle: "#EEEDE6"
  text: "#000000"
  text-secondary: "#6F6D69"
  text-tertiary: "#93908B"
  border: "#DAD9D2"
  border-subtle: "#3629001F"
  primary: "#4137FF"
  primary-soft: "#D8BEFF"
  primary-pale: "#EFEBFE"
  primary-dark: "#010080"
  accent-yellow: "#FEFF5E"
  accent-orange: "#FF8040"
  accent-red: "#FF2E2E"
  accent-green: "#67AE00"
  code-background: "#F7F6EF"
  code-comment: "#848484"
  code-keyword: "#D12A2A"
  code-function: "#3B31FF"
  code-string: "#6C0081"
  code-type: "#038A4B"
  code-variable: "#286FE8"
typography:
  display:
    fontFamily: "Untitled Sans"
    fallback: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica, Arial, sans-serif"
    fontSize: 48px
    fontWeight: 400
    letterSpacing: "0"
    lineHeight: 1.2
  heading:
    fontFamily: "Untitled Sans"
    fallback: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica, Arial, sans-serif"
    fontSize: 32px
    fontWeight: 400
    letterSpacing: "0"
    lineHeight: 1.3
  subheading:
    fontFamily: "Untitled Sans"
    fallback: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica, Arial, sans-serif"
    fontSize: 24px
    fontWeight: 400
    letterSpacing: "0"
    lineHeight: 1.5
  body:
    fontFamily: "Untitled Sans"
    fallback: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica, Arial, sans-serif"
    fontSize: 16px
    fontWeight: 400
    letterSpacing: "0"
    lineHeight: 1.5
  mono:
    fontFamily: "JetBrains Mono"
    fallback: "ui-monospace, Menlo, Monaco, Cascadia Mono, Segoe UI Mono, Roboto Mono, Consolas, Courier New, monospace"
    fontSize: 13px
    fontWeight: 500
    letterSpacing: "0"
    lineHeight: 1.6
  code:
    fontFamily: "JetBrains Mono"
    fallback: "ui-monospace, Menlo, Monaco, Cascadia Mono, Segoe UI Mono, Roboto Mono, Consolas, Courier New, monospace"
    fontSize: 13px
    fontWeight: 400
    letterSpacing: "0"
    lineHeight: 1.6
rounded:
  none: 0px
  xs: 2px
  sm: 4px
  md: 6px
  lg: 8px
  pill: 999px
spacing:
  page-x-desktop: 80px
  page-top-desktop: 48px
  page-x-mobile: 16px
  page-top-mobile: 16px
  nav-width-desktop: 160px
  section-gap-sm: 24px
  section-gap-md: 32px
  section-gap-lg: 196px
  tile-gap-x: 24px
  tile-gap-y: 48px
components:
  left-nav:
    width: "{spacing.nav-width-desktop}"
    textStyle: "{typography.mono}"
    textTransform: uppercase
    activeColor: "{colors.primary}"
    hoverBehavior: "highlight bar behind text"
  link-action:
    textStyle: "{typography.mono}"
    textColor: "{colors.primary}"
    prefix: "arrow glyph"
    textTransform: uppercase
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.background}"
    borderRadius: "{rounded.none}"
    borderColor: "{colors.primary}"
    padding: "10px 16px"
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.text}"
    borderColor: "{colors.border}"
    borderRadius: "{rounded.none}"
    padding: "10px 16px"
  tile:
    backgroundColor: "{colors.surface-muted}"
    textColor: "{colors.text}"
    borderColor: "{colors.border-subtle}"
    borderRadius: "{rounded.none}"
    padding: "24px"
  code-panel:
    backgroundColor: "{colors.code-background}"
    textColor: "{colors.text}"
    borderColor: "{colors.text}"
    borderRadius: "{rounded.none}"
    fontFamily: "{typography.code.fontFamily}"
  input:
    backgroundColor: "{colors.background}"
    textColor: "{colors.text}"
    borderColor: "{colors.border}"
    focusBorderColor: "{colors.primary}"
    borderRadius: "{rounded.none}"
    padding: "12px 14px"
imagery:
  motifs:
    - foundation-model diagrams
    - code traces
    - agent execution paths
    - benchmark grids
    - flat editorial cards
  avoid:
    - glossy SaaS gradients as the main identity
    - overly rounded app-store style cards
    - generic robot imagery
    - low-density marketing hero screens
---

## Overview

Poolside's current public site reads like a research lab and enterprise systems company rather than a typical SaaS landing page. The strongest signals are the off-white page background, strict black typography, blue-violet action color, mono uppercase navigation, flat rectangular panels, and dense long-form sections about models, agents, deployment boundaries, and benchmarks.

The visual system should feel technical, direct, and high-consequence. It should favor clear hierarchy, visible structure, source-like code panels, and measured editorial pacing. Avoid making it glossy or playful.

## Colors

Use `#FBFAF6` as the default page background. Pair it with black text, warm neutral dividers, and muted gray copy. The primary action color is Poolside's vivid blue-violet, observed as `#4137FF` in CSS and `color(display-p3 .2549 .2157 1)` in the rendered page.

- **Background (`#FBFAF6`):** Default page canvas.
- **Surface muted (`#F7F6EF`):** Cards, article cells, code backgrounds, grouped content.
- **Text (`#000000`):** Primary headings, body copy, table labels.
- **Secondary text (`#6F6D69`):** Section headings, supporting text, footers.
- **Border (`#DAD9D2`):** Quiet separators and secondary buttons.
- **Primary (`#4137FF`):** Active nav, primary links, API buttons, focus.
- **Accent yellow/orange/red/green:** Use sparingly for model status, code syntax, event/category markers, or benchmark emphasis.

## Typography

Poolside uses `Untitled Sans` for the main interface and `JetBrains Mono` for navigation, labels, actions, and code. The typography is restrained: normal and medium weights, tight but readable heading tracking, and very little decorative styling.

Use large sans headlines for product claims and mono uppercase for commands or navigation. Avoid bold, oversized marketing copy that breaks the research-lab tone.

## Layout

Desktop layouts should reserve a fixed left navigation rail around 160px wide and keep content in a wide but controlled column. Large vertical gaps are part of the rhythm; the site often places editorial sections with substantial spacing rather than stacking dense blocks immediately.

Mobile should collapse the left rail into a compact header, keep the same off-white canvas, and preserve mono labels. Cards and model grids should stack without changing the flat rectangular character.

## Components

Buttons and links are usually rectangular, text-led, and direct. Use arrow glyphs for action links. Primary buttons are filled blue-violet with off-white text. Secondary actions are transparent or muted with visible borders.

Cards should be flat tiles with little or no radius. Code panels should use `JetBrains Mono`, off-white or muted backgrounds, visible borders, syntax colors, and a copy action. Model cards and benchmark rows should prioritize labels, numbers, and provenance over decoration.

## Imagery

Use abstract system diagrams, terminal/code screenshots, benchmark grids, execution traces, and model-factory motifs. Visuals should feel like operational intelligence: agents planning, tools running, traces being audited, models being compared.

Avoid generic AI imagery, glossy product mockups, and overuse of gradients. When using the Poolside mark, rely on official brand assets only when usage is permitted. For generated demos, use original abstract motifs rather than copying official marks.

## Logo And Usage

Poolside exposes official logo, logomark, and press-kit links from the site footer. That confirms public asset availability, not unrestricted trademark permission.

Use the word "Poolside" correctly. Do not modify the logo, redraw the official mark, or combine it into unrelated product names unless a project has explicit permission. For internal demos, prefer a text wordmark or original abstract mark.

## Do's And Don'ts

- **Do** use off-white backgrounds, black text, warm gray dividers, and blue-violet actions.
- **Do** use mono uppercase labels for navigation, actions, table headings, and small system metadata.
- **Do** build flat, rectangular cards and code panels with visible structure.
- **Do** show model, agent, benchmark, and security-boundary concepts as concrete interface elements.
- **Don't** make the interface glossy, bubbly, or overly rounded.
- **Don't** replace technical evidence with generic AI metaphors.
- **Don't** use the official logo or press assets unless the usage is permitted.
- **Don't** rely on color alone for status or model comparison.
