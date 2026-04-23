---
name: brand-to-design-md
description: Convert a public brand URL into a practical DESIGN.md file and optional single-file HTML demo. Use when the user asks to extract, distill, compile, generate, or validate a DESIGN.md/design system from a website, brand page, press kit, or public visual identity.
---

# Brand To DESIGN.md

## Overview

Use this skill to turn public brand evidence into a token-ready `DESIGN.md` that a coding agent can use to generate consistent UI. When useful, also create a demo HTML page and verify it in a browser.

Start from the Google Labs `DESIGN.md` standard, not from example directories or third-party showcase pages. The output should be practical, source-aware, and executable by an agent.

## Workflow

### 1. Confirm Scope And Standard

Clarify only if needed:

- Target brand URL or brand name.
- Required outputs: `DESIGN.md` only, or `DESIGN.md` plus demo HTML and screenshots.
- Target context: website, app UI, developer docs, product page, editorial asset, or general system.

Use the Google Labs `DESIGN.md` format as the structural reference: metadata, design tokens, component guidance, imagery rules, logo boundaries, and Do/Don't guidance.

### 2. Gather Evidence

Prefer primary and high-signal sources:

- Official homepage and product pages.
- Official brand, press, newsroom, media kit, or legal trademark pages.
- Public CSS, font declarations, SVG logos, favicons, images, and screenshots.
- Design agency case studies when they explain the identity system.
- Third-party brand databases only as secondary support.

Record evidence in four groups:

- **Direct evidence:** observed CSS, SVG fills, image colors, font names, layout behavior.
- **Official prose:** brand usage rules, typography descriptions, press-kit notes.
- **Design rationale:** motifs, concepts, color names, type-system explanations.
- **Inference:** practical agent decisions not explicitly stated by sources.

If access is blocked by a CAPTCHA, login, or security challenge, do not bypass it. Use accessible official pages, cached/search snippets, press kits, downloaded public assets, or clearly mark the limitation.

### 3. Extract Tokens

Translate evidence into roles, not just values.

Core token groups:

- `colors`: primary, secondary, tertiary, neutral, surface, on-primary, text, border, status/accent colors.
- `typography`: display, h1, h2, body, label, mono/code when present.
- `rounded`: small, medium, large, special brand shapes.
- `spacing`: base scale, common section gaps.
- `components`: buttons, cards, inputs, links, code panels, notices, navigation.
- `imagery`: photography style, illustration style, texture, gradient, motion, icon rules.

For each major token, prefer a role explanation:

- Where it came from.
- What it should be used for.
- What should not use it.

### 4. Compile DESIGN.md

Write a concise but usable file:

```markdown
---
version: alpha
name: Brand Name
description: One sentence identity summary.
sources:
  - https://...
notes:
  - Evidence and limitation notes.
colors:
  primary: "#..."
typography:
  display:
    fontFamily: ...
components:
  button-primary:
    backgroundColor: "{colors.primary}"
---

## Overview
...

## Colors
...

## Typography
...

## Layout
...

## Components
...

## Imagery
...

## Logo And Usage
...

## Do's and Don'ts
...
```

Keep the writing concrete. Avoid generic claims such as "modern, clean, innovative" unless the evidence supports them and they are translated into specific design actions.

### 5. Generate A Demo When Useful

If asked for a demo, build a single-file HTML artifact in the workspace.

The demo should prove that the `DESIGN.md` is usable:

- First screen should be an actual branded product or site experience, not an explanation page.
- Include palette, typography, buttons, cards, forms, data/code panels, and one brand-specific motif.
- Use extracted public assets when allowed and useful.
- Recreate the brand's behavior and hierarchy, not only its colors.
- Keep the page responsive and readable on mobile.

For browser-based artifacts, use real browser or preview-environment verification:

- Open the file in an available browser or preview environment.
- Check console errors.
- Check horizontal overflow.
- Capture desktop and mobile screenshots.
- Confirm critical images and fonts fall back cleanly.

### 6. Report Output

Return:

- `DESIGN.md` path.
- Demo HTML path if created.
- Screenshot paths if created.
- Source summary.
- Verification result.
- Any limitations or inferred choices.

## Quality Bar

A good output lets a future coding agent produce a page that feels recognizably tied to the brand without needing more context.

Check for:

- Tokens map to meaningful roles.
- The brand has distinct visual behavior beyond color.
- Logo and trademark boundaries are respected.
- Demo page uses the system in several UI contexts.
- The output distinguishes evidence from inference.

## When To Read More

For a compact checklist and output templates, read `references/workflow-checklist.md`.
