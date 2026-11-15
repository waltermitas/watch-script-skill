# watch-script

A Claude Code skill that turns a watch reference into a full YouTube package: a retention-engineered ~10-minute script, a ~90-second short, titles, and a companion blog article.

Built for the [Brothers in Watches](https://brothersinwatches.com) channel, where every video is a single-watch showcase. I wrote none of the code by hand; the skill is plain Markdown that Claude Code follows.

## What you get from one prompt

```
/watch-script Omega Speedmaster 3570.50
```

- **Retention map**: one master loop, 2-3 open loops closed in order, a contrarian beat.
- **Long video**: 11 segments with a narration column and a b-roll column, a micro-hook at every boundary.
- **Short cut**: about 90 seconds, hook first, one idea, the key number as the payoff.
- **Package**: 3-5 titles (brand first, 100 characters or fewer), description, chapters, pinned comment.
- **Blog**: a long-form "Deep Research Watch Report" built from the same research.
- **A `⚠️ verify` list** of every claim that needs confirming before you film.

## Why it works

The skill is deliberately thin. The rules live in `rules/` so you change how every script sounds by editing one file:

| File | Job |
| --- | --- |
| `SKILL.md` | The pipeline: research, outline, draft, short, package, blog |
| `rules/style-guide.md` | Voice, retention rules, sourcing rules, titles, blog format |
| `rules/script-template.md` | The skeleton to fill, with per-segment word targets |
| `rules/validation-checklist.md` | Binary pass/fail checks the output must clear |

Two choices matter most:

1. **Facts are tagged, never invented.** Realized prices come first, asking prices are labelled, and anything uncertain is flagged `⚠️ verify`. An audience that knows watches punishes one bad claim.
2. **Retention is built in, not hoped for.** No preamble, a stated master loop, and a forward-pulling line at every transition.

## Install

Copy the folder into your skills directory:

```bash
cp -r watch-script-skill ~/.claude/skills/watch-script
```

Then adapt `rules/style-guide.md` to your own channel's voice and brand.

## Example

See [`examples/omega-speedmaster-38-2026-short.md`](examples/omega-speedmaster-38-2026-short.md) for a finished short, including its fact ledger and verify list.

## Licence

MIT
