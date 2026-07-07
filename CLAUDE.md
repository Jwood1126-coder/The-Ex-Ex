# CLAUDE.md — Operating Instructions for AI Sessions

This repo is the master source for **The Ex. Ex.**, a book about the United States Exploring Expedition (1838–1842). Any Claude session working here — Claude Projects, Claude Code, Codespaces, chat — starts by reading this file, then `STYLE_GUIDE.md`, then `PROJECT_NOTES.md` §2 and §5.

## What this repo is
A **base narrative**: the complete story, told (not shown), fact-checked, in the project's fused voice. It is the reference from which the novel will be written. The novel does not exist yet; it will live in `novel/` when it does.

## The hard rules

1. **Voice is law.** `STYLE_GUIDE.md` governs every sentence, especially the "tells to kill" blacklist. If output sounds like AI, it's wrong even when it's accurate.
2. **Base tells, novel shows.** Never inflate base-narrative prose into scene-writing, and never let novel drafts collapse into summary. The two modes stay in their directories.
3. **No fact enters without provenance.** Every factual change lands as a `fact:` commit citing its source (author, work, page/URL) in the commit body.
4. **Quotes only from public-domain primaries** (Erskine 1896, Reynolds' journal, Wilkes' *Narrative*) **or Jake's transcriptions.** Never reproduce prose from Philbrick, Stanton, or any in-copyright work — facts from them, words never.
5. **Ranges over false precision.** Where sources conflict (deaths: 28 vs ~40; Malolo: 74–104), the text states the range. Don't "clean up" honest uncertainty.
6. **The double ledger stays balanced.** Malolo, Utiroa, Vendovi, the floggings: the book holds achievement and atrocity in the same hand, in the same chapter, without letting either erase the other. Edits that tilt this framing get rejected.
7. **The witnesses keep their dignity.** Vendovi, David Smith, the Fuegian family, the Hawaiian porters — people the 1840s record flattened are rendered as people. Period racism appears only inside quotes, framed; never in the narrator's own sentences.
8. **Commit prefixes:** `fact:` / `enrich:` / `voice:` / `novel:` / `meta:` — see PROJECT_NOTES §5.
9. **Small diffs.** Propose changes as targeted edits to named files, not wholesale rewrites, unless explicitly asked.
10. **Frozen means frozen.** Once Jake declares the base stable post-read-throughs, acts change only via `fact:` commits.
11. **Wilkes is never simplified.** Not a villain, not a misunderstood hero: the tyranny and the greatness are the same appetite, and every scene involving him must survive being read both ways.

## Current status & next milestones
- Base v2 complete (~30K words, July 2026). Verification pass done; soft-spot list in `PROJECT_NOTES.md` §3 awaits page-number confirmation.
- **Next:** (1) Erskine read-through → `fact:` commits; (2) Reynolds journal read-through; (3) `SCENE_BANK.md` harvested from primaries; (4) `novel/CHAPTER_MAP.md`; (5) draft prologue (1890 frame, the belaying pin).

## Story spine (orientation for new sessions)
Prologue: 1838, mid-Atlantic, night — sixteen-year-old Charlie Erskine, flogged by Wilkes' order, stands over his sleeping commander with a belaying pin, and doesn't. Five acts: the making of the commander (1828–1838); the Atlantic and first ice; the Pacific's paradise-and-poison year; the Antarctic continent; Fiji's blood, the Northwest, the wreck, the homecoming trials — closing on Erskine's 1890 memoir, dedicated "To the Crew of the Ship Universal," with James Smithson's words as its epigraph. Dual witnesses throughout: Charlie (the body, below decks) and William Reynolds (the pen, the secret journal). The full outline and scene bank live in the editorial brief in the project archive.
