# The Ex. Ex. — Editorial Dossier

**What this is.** The project's craft-and-direction system: a set of rubrics, bibles, and
reusable generators that codify how *The Ex. Ex.* is written and improved. It is the layer
between the frozen reference (the acts) and the future novel — it governs how the base is
sharpened and how the novel gets built, without either bleeding into the other.

**Relationship to the rest of the repo.**
- `act_1.md`–`act_5.md`, `00_preface.md` — the base narrative. Telling-mode reference.
- `STYLE_GUIDE.md`, `CLAUDE.md`, `PROJECT_NOTES.md`, `README.md` — the editorial DNA and rules.
- `prompts/fable-master-prompt.md` — the prompt that commissions the deep Fable pass which
  fills this dossier.
- `dossier/` (this folder) — the durable output of that pass: the system.

**Status (2026-07-07).** Scaffolded. `00-operating-manual.md` and `12-decision-log.md` are
partly seeded (boot order, do-not list, setup decisions). Every other file is a **stub** with a
purpose header and a "what belongs here" list, awaiting the Fable pass. The judgment-heavy
content is deliberately left blank — that is Fable's work, per the master prompt's commissions.

**The structure is provisional.** This layout is a strong default, not a cage. Fable, or any
successor model, may reshape, split, merge, or replace these files where a better system serves
the book. Any structural change gets an entry in `12-decision-log.md`.

## Contents

| # | File | Fed by commission | Status |
|---|------|-------------------|--------|
| 00 | operating-manual.md | K | seeded (recipes pending) |
| 01 | voice-bible.md | A | **authored** — Fable pass 2, 2026-07-07 |
| 02 | grounding-engine.md | B | **authored** — Fable pass 1, 2026-07-07 |
| 03 | world-bible.md | C | stub |
| 04 | cast-bible.md | D | **authored** — Fable pass 3, 2026-07-07 |
| 05 | architecture-critique.md | E | **authored** — Fable pass 2, 2026-07-07 |
| 06 | double-ledger.md | F | **authored** — Fable pass 3, 2026-07-07 |
| 07 | scene-bank.md | G | stub |
| 08 | chapter-map.md | G | stub |
| 09 | cold-opens.md | H | stub |
| 10 | throughlines.md | I | stub |
| 11 | provenance-recency.md | J | seeded + pass-findings table (2026-07-07) |
| 12 | decision-log.md | K | seeded |

## Conventions
- **Mode tags.** Every entry is tagged `[BASE]` (improves the reference), `[NOVEL]` (governs the
  scene-level novel), or `[BOTH]`.
- **`[VERIFY]`** on every factual specific until a primary source confirms it.
- **★** marks a favorite/recommended option; the writer discards freely.
- **Menu, not verdict.** These files over-generate on purpose.
- **Append-only decision log.** Don't relitigate logged calls; add new ones.
- **kebab-case filenames, one concept per file** — matches the repo's habits.
