# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a **Claude Code skills workspace** for BioTalk's social media team. It contains custom skills that Claude uses to assist with Instagram content planning. There is no build system or test suite — the "code" here is Markdown-based skill definitions.

## Repository Structure

- `.claude/skills/biotalksocialmedia/` — the primary skill for monthly Instagram content planning
  - `SKILL.md` — skill logic, steps, and output format
  - `BioTalk_BrandGuidelines.md` — brand identity reference (colors, typography, logo rules)
- `.claude/agents/` — place future agent definitions here

## The `biotalksocialmedia` Skill

Triggered via `/biotalksocialmedia`. This skill **must not run autonomously** — it requires two sequential user inputs before generating any content:

1. **Monthly theme & moodboard** — month/year, visual mood, special events/moments
2. **Product distribution (%)** — percentage allocation per product, must sum to 100%

Only after both inputs are confirmed does the skill produce:
- Monthly strategy summary
- Content table (min. 16 posts/month, 4/week) with format, pillar, concept, caption hook, and visual direction
- Monthly hashtag recommendations
- Production notes

## BioTalk Brand Essentials

When generating any visual direction or copy, adhere to:

- **Primary color:** Dark Green `#153B34`
- **Tone:** natural, clean, friendly, educational
- **Language:** Bahasa Indonesia for all captions and copy
- **Headline typeface:** Bianco Serif | **Body:** Basis Grotesque Pro
- Each product has its own accent color (see `BioTalk_BrandGuidelines.md` §1.6)

## Modifying the Skill

To update the skill logic, edit `.claude/skills/biotalksocialmedia/SKILL.md`. To update brand colors, typography, or product list, edit `BioTalk_BrandGuidelines.md`. The product list lives in `SKILL.md` under **Produk BioTalk** — keep it in sync if products are added or removed.
