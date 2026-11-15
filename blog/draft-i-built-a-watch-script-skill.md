---
seo_title: I Built a Claude Code Skill That Writes Watch Videos (Open Source)
meta_description: One prompt turns a watch reference into a 10-minute YouTube script, a 90-second short, titles and a blog post. Here is how the watch-script skill works, and the repo.
status: draft
---

# I built a Claude Code skill that writes our watch videos

*One reference in, a full video package out.*

Every Brothers in Watches video starts the same way: a single watch, a pile of research and a blank page. The research is the slow part, and the blank page is where retention gets lost, because a weak first ten seconds costs more views than a weak ending.

So I turned the process into a skill. You type a watch, for example `Omega Speedmaster 3570.50`, and get back a script I can film.

## What comes out

- A **retention map**: the one question the video answers, two or three open loops and a contrarian beat.
- A **10-minute script** in 11 segments, with a b-roll column beside the narration.
- A **90-second short** with the hook as the first line.
- **Titles, description, chapters** and a pinned comment.
- A **blog article** built from the same research, so the two never contradict each other.
- A list of **`⚠️ verify`** items to confirm before filming.

## The two rules that matter

**1. Never invent a fact.** The skill checks realized sale prices first, labels asking prices as asking and flags anything uncertain. Collectors notice a wrong production number straight away, and trust is the brand.

**2. Build retention into the structure.** No "welcome back" opening, a cold open of 60 words or fewer, and a forward-pulling line at every transition.

## Why the rules live in separate files

The skill file only describes the pipeline. The voice, the template and the pass/fail checklist sit in a `rules/` folder. To change how every script sounds, I edit one file and never touch the skill.

## Try it

The repo is here: *[link once published]*. Swap the style guide for your own channel's voice and you have your own version.

*If you build something with it, tell me what you filmed.*
