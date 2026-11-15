---
name: watch-script
description: Use when you want a YouTube script for a single-watch showcase video. Give it a watch (brand + reference, e.g. "Omega Speedmaster 3570.50") and optional notes; it researches, then drafts BOTH a retention-engineered ~10-min long-video script (with a b-roll column) AND a ~90s short cut, plus a title/SEO pack and a companion blog article.
---

# Watch Script — single-watch showcase generator

Turns a watch reference into a camera-ready script and a blog post. Format: single-watch showcase only.

## Input

- **Required:** a watch, brand + reference (e.g. `Omega Speedmaster 3570.50`).
- **Optional:** a few bullets from the host: price paid, condition quirks, the hunt story. Weave them in; never invent them if absent.

If no watch was given, ask for one before doing anything else.

## Source of truth: read these first, every run

The rules live in `rules/`, not in this file:

1. `rules/style-guide.md`: voice, retention rules, facts and sourcing, titles, blog. Governs everything.
2. `rules/script-template.md`: the exact skeleton to fill.
3. `rules/validation-checklist.md`: the acceptance bar the output must pass.

If any of these is missing, stop and say so. Do not improvise the rules.

## Pipeline

1. **Research.** Model history, movement facts, market value. Realized (sold) prices first; asking prices only as labelled asking. Tag every factual claim; mark anything uncertain `⚠️ verify`. Never fabricate a spec, date, production figure or comp.
2. **Outline.** Fill the retention map before any prose: master loop, 2-3 open loops, a contrarian beat, a micro-hook for every segment boundary.
3. **Long video (~10 min).** 11 blocks (10 content segments + CTA), about 2,200-2,600 words of narration, cold open of 60 words or fewer, with a b-roll / pattern-interrupt column.
4. **Short cut (~90s).** 220-260 spoken words. The hook is the first spoken line and the first on-screen text. One idea, three beats, land the number, end on a follow CTA.
5. **Package.** 3-5 titles (brand first, 100 characters or fewer), description, chapters, pinned-comment hook.
6. **Blog.** Companion article from the same research, in the "Deep Research Watch Report" format from the style guide.

## Self-check

Score the draft against every item in `rules/validation-checklist.md`. Fix any FAIL before saving.

## Output

One Markdown file: `scripts/YYYY-MM-DD-<watch-slug>.md`, containing frontmatter, retention map, the 11 long-video blocks, the short cut, the package and the blog.

## Report back

The filename, the title options, the short cut, and a bulleted list of every `⚠️ verify` item to confirm before filming.
