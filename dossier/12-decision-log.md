# 12 — Decision Log

> **Purpose.** Positions taken and defended, append-only, so future sessions don't relitigate
> settled calls. Each entry: date, decision, why, and the cost of reversing it.
> Fable and later models add their architectural positions here.

---

### 2026-07-07 — Working repo adopts the book's real git history
**Decision.** The Codespaces repo (`github.com/Jwood1126-coder/The-Ex-Ex`) was an empty GitHub
stub ("Initial commit", README `# The-Ex-Ex`). We reset `main` to the manuscript's actual
history (the `meta:` scaffolding commit + the `manuscript:` base-v2 commit) delivered in
`files.zip`.
**Why.** The README names this exact repo as the book's intended remote; the stub carried no
content. Provenance-by-commit (hard rule 3) makes the real history load-bearing.
**Reversal cost.** Low. The original stub commit is preserved as tag `archive/stub-initial`.
Pushing to the remote will require `--force` (unrelated histories) — not yet done.

### 2026-07-07 — Editorial dossier + Fable master prompt established
**Decision.** Added `prompts/fable-master-prompt.md` (the deep-pass prompt) and the `dossier/`
system: an operating manual, a decision log, and stubs for voice, grounding, world, cast,
architecture, double-ledger, scene-bank, chapter-map, cold-opens, throughlines, and
provenance-recency. Judgment-heavy content left blank for the Fable pass.
**Why.** The author wants a durable system to maintain quality and direction, inspired by the
BZ-Age project's Editorial-DNA + dossier + operating-manual model — not a mirror of it.
Scaffolding is cheap; the rubrics and critique are Fable-level work and were deliberately not
pre-filled, to spend Fable credits only where Fable is irreplaceable.
**Reversal cost.** Low. The dossier is additive; the acts and DNA files are untouched. The
structure is explicitly provisional and may be reshaped by Fable (log the change here).
