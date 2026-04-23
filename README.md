# Brand to DESIGN.md Skill

Convert a public brand URL into a practical `DESIGN.md` file for coding agents. The skill can also guide the creation of a single-file HTML demo and browser-based verification screenshots.

## What it does

- Gathers public brand evidence from official pages, press kits, CSS, SVGs, images, and design case studies.
- Translates brand evidence into design tokens and practical component guidance.
- Produces a source-aware `DESIGN.md` with colors, typography, layout, components, imagery, logo boundaries, and Do/Don't guidance.
- Optionally creates and verifies a responsive HTML demo.

## Skill location

The skill lives at:

```text
skills/brand-to-design-md/SKILL.md
```

This repository intentionally excludes agent-specific metadata so the skill stays portable.

## Usage

Install or copy the `skills/brand-to-design-md` folder into any agent environment that supports local skills, including Codex, Claude Code, Cursor, and OpenClaw.

If your environment supports the `skills` CLI, install directly from GitHub with:

```bash
npx skills add https://github.com/shaom/brand-to-design-md-skill --skill brand-to-design-md
```

Example prompt:

```text
Use brand-to-design-md to extract https://example.com into a DESIGN.md and demo HTML.
```
