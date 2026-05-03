---
version: alpha
name: Kigen
description: Light, tactile design-system tooling language for Figma tokens: soft gray surfaces, inset depth, rainbow glow accents, dense controls, color scales, variables, export panels, and crisp product-system messaging.
sources:
  - https://kigen.design/color
  - https://kigen.design/
  - https://kigen.design/system
notes:
  - Derived from Kigen public pages, rendered DOM, exposed CSS variables, metadata, and visible product UI.
  - Kigen's site states it is not affiliated with Figma. Use Figma references only as functional context, and do not imply endorsement.
  - Public website assets can change over time. Treat this as a design snapshot generated from the observed pages.
colors:
  background: "#F7F7F7"
  foreground: "#161718"
  white: "#FFFFFF"
  dark-gray: "#161718"
  gray-alpha: "#0000001F"
  gray-muted: "#00000080"
  gray-100: "#F2F3F5"
  gray-150: "#F1F2F4"
  gray-200: "#E8E8E8"
  border-subtle: "#00000014"
  ring: "#AAAAAA"
  blue: "#007BE5"
  blue-light: "#E5F4FF"
  blue-dark: "#034AC1"
  green: "#14AE5C"
  green-light: "#CFF7D3"
  green-dark: "#00632E"
  pink: "#FC07CF"
  pink-light: "#FFE0FC"
  pink-dark: "#A90279"
  teal: "#00A2C2"
  teal-light: "#CEF0F8"
  teal-dark: "#047195"
  accent-red: "#FF2222"
  accent-lime: "#31FF12"
  accent-blue: "#096FFF"
  accent-cyan: "#42ECFF"
  accent-purple: "#8E1DFF"
  mountain-meadow-50: "#BEFFDF"
  mountain-meadow-100: "#1AFDB5"
  mountain-meadow-200: "#16DF9F"
  mountain-meadow-300: "#12C48C"
  mountain-meadow-400: "#0EAC7A"
  mountain-meadow-500: "#0DA273"
  mountain-meadow-600: "#0B966A"
  mountain-meadow-700: "#08875F"
  mountain-meadow-800: "#077754"
  mountain-meadow-900: "#056748"
  mountain-meadow-1000: "#045F42"
  mountain-meadow-1100: "#03573C"
  mountain-meadow-1200: "#034F36"
  mountain-meadow-1300: "#024630"
  mountain-meadow-1400: "#023E2A"
  mountain-meadow-1500: "#013624"
  mountain-meadow-1600: "#012E1E"
  mountain-meadow-1700: "#012518"
  mountain-meadow-1800: "#001E12"
  mountain-meadow-1900: "#00150B"
gradients:
  light-surface: "linear-gradient(180deg, #F2F2F2 0%, #E8E8E8 100%)"
  blue-action: "linear-gradient(90deg, #75DAFF 5.87%, #588FFC 37.44%, #935AFA 102.82%)"
  orange-action: "linear-gradient(90deg, #FFC062 0%, #FF6456 94.7%)"
  rainbow-glow: "linear-gradient(90deg, #FF4242, #FFA201, #00B330, #0091BD, #4542FF, #8102FF, #FF4242)"
typography:
  display:
    fontFamily: "Inter Display"
    fallback: "Geist, Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 64px
    fontWeight: 600
    letterSpacing: "0"
    lineHeight: 1
  h1:
    fontFamily: "Geist"
    fallback: "Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 48px
    fontWeight: 600
    letterSpacing: "0"
    lineHeight: 1.06
  h2:
    fontFamily: "Geist"
    fallback: "Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 32px
    fontWeight: 600
    letterSpacing: "0"
    lineHeight: 1.14
  body:
    fontFamily: "Geist"
    fallback: "Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 16px
    fontWeight: 400
    letterSpacing: "0"
    lineHeight: 1.55
  ui:
    fontFamily: "Hanken Grotesk"
    fallback: "Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif"
    fontSize: 14px
    fontWeight: 600
    letterSpacing: "0"
    lineHeight: 1.2
  mono:
    fontFamily: "JetBrains Mono"
    fallback: "ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, Liberation Mono, monospace"
    fontSize: 13px
    fontWeight: 500
    letterSpacing: "0"
    lineHeight: 1.65
rounded:
  xs: 4px
  sm: 8px
  md: 10px
  lg: 12px
  xl: 16px
  xxl: 18px
  pill: 999px
spacing:
  hairline: 1px
  xs: 4px
  sm: 8px
  md: 12px
  lg: 16px
  xl: 24px
  xxl: 32px
  section: 72px
effects:
  shadow-sm: "inset .75px .75px 1px #fff, inset -.75px -.75px 1px #00000026, .222px .222px .314px -.5px #0003, .605px .605px .856px -1px #0000002e, 1.329px 1.329px 1.88px -1.5px #00000040, 2.95px 2.95px 4.172px -2px #0000001a, 2.5px 2.5px 3px -2.5px #00000026, -.5px -.5px 0 0 #0000001a"
  shadow-lg: "inset 1.5px 1.5px 1px 0 #fff, inset -1px -1px 1px 0 #00000026, .444584px .444584px .628737px -1px #00000042, 1.21072px 1.21072px 1.71222px -1.5px #0000003f, 2.5px 2.5px 3.75px -2.5px #0000003b, 6px 6px 8px -3px #0003, 10px 10px 22px -3px #0000000f, -.5px -.5px 0 0 #0000000d"
  inset-control: "inset 0 1px 2px #00000026, 0 1px 0 0 #ffffff40"
  component-box: "0px 1px 0px #fff, inset 0px 2px 8px #0000001a, inset 0px 1px 0px #0000001a, inset 0px -1px 0px 1px #0000000d"
components:
  announcement-bar:
    backgroundColor: "{colors.foreground}"
    textColor: "{colors.white}"
    rounded: "{rounded.pill}"
    shadow: "{effects.shadow-sm}"
    padding: "8px 12px"
  navigation:
    backgroundColor: "transparent"
    textColor: "{colors.foreground}"
    activeContext: "slash separator plus lowercase page label"
    actionButton:
      backgroundColor: "{colors.foreground}"
      textColor: "{colors.white}"
      rounded: "{rounded.md}"
      padding: "8px 14px"
  surface-card:
    background: "{gradients.light-surface}"
    borderColor: "{colors.border-subtle}"
    rounded: "{rounded.xl}"
    shadow: "{effects.shadow-lg}"
  control-field:
    backgroundColor: "{colors.white}"
    borderColor: "{colors.border-subtle}"
    rounded: "{rounded.lg}"
    shadow: "{effects.inset-control}"
    minHeight: 44px
  gradient-button:
    background: "{gradients.blue-action}"
    textColor: "{colors.white}"
    rounded: "{rounded.md}"
    shadow: "{effects.shadow-sm}"
  color-swatch:
    rounded: "{rounded.lg}"
    shadow: "{effects.shadow-lg}"
    labelStyle: "{typography.mono}"
  segmented-tabs:
    backgroundColor: "{colors.gray-100}"
    borderColor: "{colors.border-subtle}"
    rounded: "{rounded.pill}"
    activeBackground: "{colors.white}"
    activeShadow: "{effects.shadow-sm}"
  code-panel:
    backgroundColor: "{colors.foreground}"
    textColor: "{colors.white}"
    rounded: "{rounded.xl}"
    font: "{typography.mono}"
  token-badge:
    backgroundColor: "{colors.white}"
    borderColor: "{colors.border-subtle}"
    rounded: "{rounded.pill}"
    shadow: "{effects.shadow-sm}"
---

## Overview

Kigen's design language is a tactile product-tool interface. It combines a quiet light-gray canvas with rounded control surfaces, layered inset shadows, vivid gradient accents, and compact token-generation workflows. The strongest brand signals are the soft physical depth, rainbow glow, color-scale output, and design-system vocabulary around variables, components, dark/light mode, accessibility, and handoff.

The result should feel like a practical design-system workbench: polished, dense, and interactive, with most of the page occupied by controls, palettes, tokens, previews, and export-ready code.

## Colors

Use `#F7F7F7` as the default page background and `#161718` as the main text and dark control color. Keep white surfaces for editable fields and panels. The neutral system should carry most of the UI; color enters through tokens, gradients, state badges, and swatches.

The selected color generator sample uses Mountain Meadow `#0EAC7A` with RGB `14, 172, 122`, expanded into a 20-step Tailwind CSS scale from `#BEFFDF` to `#00150B`. This cooler green-teal range fits Kigen's technical product-tool tone better than the brighter mint sample while still preserving the brand's color-generation behavior.

## Typography

Use `Geist` for body and headings, `Hanken Grotesk` for UI controls, `Inter Display` for larger marketing or product-system headings, and `JetBrains Mono` for token names, code, numeric fields, and generated CSS.

Keep letter spacing at `0`. The brand depends more on compact hierarchy, medium weights, and well-spaced control groups than on decorative type treatment.

## Layout

Favor a centered, max-width workbench on a light-gray background. The top area typically includes a small black announcement pill, a sparse navigation row, and a direct product context label such as `/ color generator` or `/ design system`.

Primary screens should present the tool first: color picker, RGB values, algorithm settings, generated shades, export tabs, and code. Use multi-column layouts on desktop and stacked panels on mobile. Keep controls compact but not cramped; the tactile shadows need enough room to remain readable.

## Components

Kigen components are rounded and physical:

- **Controls:** white fields, 12px radius, inset shadow, black text, compact labels.
- **Buttons:** black filled actions for installation or purchase; gradient actions for generation and export.
- **Cards:** light gradient surfaces with layered inset and outer shadows.
- **Tabs:** pill-shaped segmented controls with a raised active state.
- **Swatches:** rounded color blocks with mono labels and shade numbers.
- **Code panels:** dark, rounded, mono, with syntax-like color accents.
- **Badges:** small, pill-shaped, often used for NEW, WIP, accessibility scores, and token metadata.

## Imagery

Prefer product UI screenshots, generated interface previews, token boards, color ramps, and component examples. A subtle rainbow glow can sit behind the first screen, but avoid turning it into a generic gradient landing page. The page should still read as a working design-system tool.

## Logo And Usage

Kigen uses a compact mark and product-wordmark treatment on its public site. When creating demos, use the mark sparingly, usually in the navigation or footer. Do not imply that Kigen is affiliated with Figma; the public site explicitly separates itself from Figma.

## Do's and Don'ts

- **Do** build actual tool-like screens with controls, generated tokens, and export panels.
- **Do** use soft gray surfaces, inset shadows, rounded fields, and compact mono token labels.
- **Do** combine neutral UI with vivid color scales and rainbow gradient accents.
- **Do** include dark/light mode, semantic colors, accessibility, variables, and handoff as design-system concepts.
- **Don't** make the brand a generic neon gradient style.
- **Don't** overuse heavy glass effects or large decorative blobs.
- **Don't** stretch the rainbow accent across every surface.
- **Don't** imply Figma endorsement or ownership.
