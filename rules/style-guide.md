---
title: Brothers in Watches - Script Style Guide
type: style-guide
project: Brothers in Watches
created: 2026-08-08
tags: [youtube, scripts, style, voice]
---

# Brothers in Watches - Script Style Guide

The workflow reads this file every run. Change the rules here, not in the skill.

---

## 1. Voice

The channel sounds like a knowledgeable collector telling you why *this* watch is
worth your attention - not a spec-reader, not a hype merchant.

- **Prose, not bullet points.** Narration flows in sentences. Never read a list of
  specs on camera; weave them into the story of the piece.
- **Evocative openings.** Start in the world of the watch - a moment, a detail, a
  tension - before any facts. The cold open should feel like the first line of a
  story, not a table of contents.
- **Luxury experiential tone with educational depth.** Make the viewer feel the
  weight of the case and understand *why* the movement matters. Beauty and
  knowledge in the same breath.
- **Correct horological terminology, never dumbed down.** Say *chronometer*,
  *acrylic crystal*, *column wheel*, *tritium patina* - and explain them in-line
  the first time so a newcomer keeps up without the enthusiast feeling talked down
  to.
- **Earn authority through precision, not adjectives.** "Rare" and "iconic" are
  cheap; the specific fact that makes it rare is not. Show, don't label.
- **No filler.** No "so basically", no "at the end of the day", no throat-clearing.
  Every sentence either advances the story or teaches something.

**Visual identity:** Navy / gold. Note it in b-roll/graphic cues where relevant
(lower-thirds, title cards, thumbnail direction).

---

## 2. Retention rules (engineer these, don't hope for them)

These are baked into the template. Follow them literally.

- **No preamble - ever.** Never open with "Hey guys / welcome back to the channel",
  a sponsor read, or "so I've been thinking". These cause the sharpest early drop.
  The first 5 seconds must pay off the title and thumbnail.
- **One master loop.** The whole video answers a single question. State it (to
  yourself, in the retention map) and plant it in the cold open.
  - *Example (Speedmaster 3570.50):* "Two Speedmasters sit side by side, near
    identical - so why is this one worth almost double?"
- **2–3 open loops, closed in order.** An open loop is an unresolved question that
  creates tension. Open it, keep it alive, close it before opening the next. Worth
  ~+30% watch time.
  - *Example open:* "…and there's one detail on this dial that would kill the value
    instantly. We'll get to it." *Closed later:* "Remember that detail - here it is."
- **Every transition is a micro-hook.** Never end a segment on a clean stop. End on
  a line that pulls forward.
  - *Weak:* "So that's the history. Now let's look at the watch."
  - *Strong:* "But the history is the easy part - it's what's on the dial that
    separates a good one from a grail."
- **A mini-payoff in every segment.** Viewers leave when a segment stops giving
  progress. Each of the four middle segments must *deliver* something - a reveal, a
  number, a resolved question - not just set up.
- **Guard the middle.** The steepest mid-video drop is around the 4→5 / 5→6
  boundary. Put your strongest micro-hook there.
- **At least one contrarian / curiosity-gap beat.** Challenge what viewers think
  they know ("everyone says the sapphire version is the one to buy - they're
  wrong, and here's why").

---

## 3. Facts & sourcing (trust is the brand)

The audience knows watches. A single fabricated or lazy claim costs credibility.

- **Everywatch realized prices first** for market value - actual sold prices, not
  aspiration. Use **Chrono24 only for asking prices**, and always label them as
  asking, not value.
- **Confidence-tag every factual claim** (dates, calibre, production numbers,
  prices). If it's not solid, mark it **`⚠️ verify`** inline so the host decides on
  camera. Better a flagged gap than a confident error.
- **Never fabricate.** No invented provenance, specs, serial ranges, or comps. If a
  realized comp can't be found, give a clearly-labelled *range* ("realized figures
  I could find cluster roughly CHF X–Y, thin data") - never a made-up number.
- **No watch myths.** Do not repeat internet lore as fact. Known traps to avoid:
  - Treating a **redial as acceptable** - a redial is a hard dealbreaker; if
    originality is in question, say so.
  - Ignoring the **lume-matching rule** - on a tritium watch, hands and dial must
    match in tone; bright white hands on a cream tritium dial is a disqualifier,
    not a detail.
  - Repeating inflated "only N ever made" claims without a source - flag as
    `⚠️ verify`.

---

## 4. Titles & SEO

- **Brand front-loaded.** The brand (and reference/model) leads the title.
- **≤100 characters.** Treat 100 as the working limit, not 60–70. Count them.
- **SEO-optimized but human.** Include the terms a buyer would search (brand, model,
  reference, "review" / "worth it" / "history") without keyword-stuffing.
- Provide **3–5 options** with different angles (curiosity, value, authority) so
  the host picks the thumbnail-fit.
- *Examples:*
  - `Omega Speedmaster 3570.50: The Last True Moonwatch Before Sapphire - Full Review`
  - `Why This Cartier Must de Vendôme Is the Best-Value Vintage Cartier in 2026`

---

## 5. Blog companion - "Deep Research Watch Report"

Every video ships with a blog article for **brothersinwatches.com**, built from the
*same* research (never re-researched, never contradicting the script). Same voice -
evocative, prose-driven, educational - with its own SEO title and meta description.
Prose paragraphs, not the two-column script format.

**Format = the house "Deep Research Watch Report".** This is the published Brothers
in Watches blog style (reference exemplar: the Breitling Ref. 1191 review). Match it.

- **Length:** long-form, ~2,800–3,600 words. Depth is the format; don't pad, but
  don't ship the old ~800-word companion either.
- **Output as clean HTML** (h2/h3, p, strong, em, table, blockquote, hr) so it drops
  straight into Shopify's editor with tables intact. No markdown for the published body.
- **Opening:** one *italic* subtitle hook, then 2–3 short intro paragraphs that place
  the watch in its story before any spec.
- **Section skeleton (H2, `<hr>` between each):**
  1. **Historical Context** - prose; end with a **Key Historical Milestone** callout
     (`<blockquote>`) carrying a sourced fact.
  2. **Reference Number & Dating** - prose + `What the Case Back Tells You` (H3) +
     a **specifications table** + an italic authentication note.
  3. **The Dial** - prose + variants (H3) + a bold **"Dial originality - the most
     critical factor"** callout.
  4. **Inside the Watch: [Movement]** - prose + a **movement specifications table**.
  5. **The Case & Bracelet** - prose + `What to Look For on the Case` (H3).
  6. **Condition & Authenticity Checklist** - a **Component / What to Verify /
     Importance** table (Critical/High/Medium ratings).
  7. **Market Value** - a **condition-tier price table** + an italic **Collector
     Insight** callout. Realized comps first; label asking prices as asking.
  8. **Analysis: This Specific Example** - H3 sub-assessments (Dial / Case / Movement
     / Overall) evaluating the actual piece in hand.
  9. **Why the Ref. [X] Matters** - comparative positioning vs. its stablemates; the
     closing collector argument.
- **No sales CTA.** Close with a philosophical/positioning line, then a signed
  attribution: *`Brothers in Watches · Deep Research Watch Report · <Watch + ref>`*,
  followed by a **Sources & further reading** line.
- **Facts rule still governs.** Convert internal `⚠️ verify` tags into honest hedged
  prose for the public ("reported at ~35–38 mm - verify on the watch"; "asking, not
  realized") - never publish a fabricated precise figure to fill a table cell, and
  never leave a literal `⚠️ verify` in the published body.

---

## 6. Formats - long video & short

Every run produces **two** cuts of the same watch, from the same research:

### Long video - ~10 min (default)
- 10 content segments + CTA, **~2,200–2,600 words** (errs long; the host trims to land 10:00).
- Full retention spine: master loop, 2–3 open loops closed in order, a micro-hook at
  every segment boundary, a mini-payoff per middle segment, ≥1 contrarian beat.
- Skeleton and per-segment word targets live in `script-template.md`.

### Short - ~1.5 min (~90s), for Shorts / Reels / TikTok
The short is **not** a trailer for the long video - it's a self-contained piece that
has to survive the scroll. Built on current short-form data:

- **Hook is the first spoken line AND the first on-screen text.** The core
  contradiction/claim, stated flat, in the first ~3 seconds - no preamble, no
  build-up. (Intro retention past 3s should clear ~70%; a slow start loses ~19%.)
- **One idea only.** A short carries a single punch (one craft fact + one number),
  never the long video's whole outline. Pick the most scroll-stopping angle.
- **Three-beat body → number → CTA.** ~220–260 spoken words for ~90s. Beat 1 sets
  the craft/story, beat 2 deepens it, beat 3 lands the **number** (price/age) as the
  payoff; close on a fast *follow/subscribe* line.
- **The "success punch"** = a single stat or visual contradiction as the opener
  ("100 years old and the dial is glass" / "sold for CHF 453"). Lead with it; don't
  earn it.
- **Visual-first.** Open on the single most striking macro - the object IS the hook,
  never a talking head first. Cuts ≤2s; one hard beat (music + text) on the number.
- **On-screen text always**, timecoded, mirroring the spoken beats (sound-off viewing).
- **Caption + 4–6 hashtags**, brand and niche tags (`#omega #vintagewatches #watchtok
  #horology`).
- Same voice and the same Facts rule as the long video - short ≠ loose with the truth.
