# 00 — Operating Manual

> **Purpose.** How any session (human or model) uses this dossier to work on *The Ex. Ex.*
> without losing the voice, the facts, or the direction.
> **Status:** Boot order, principles, and do-not list are seeded below. The per-task **recipes**
> are left for the Fable pass to author (master-prompt Commission K).
> Structure is provisional — reshape if a better system serves the book; log it in
> `12-decision-log.md`.

## Boot order (read before touching anything)
1. `CLAUDE.md` — the rules; it wins on any conflict.
2. `STYLE_GUIDE.md` — the voice, and the "tells to kill" blacklist.
3. `PROJECT_NOTES.md` §2 (editorial decisions) and §5 (how to proceed).
4. This manual, then the dossier file your task needs.

## The one thing everything serves
Great storytelling that **grounds the reader** — continuous vivid imagery, deep world-building,
the felt physical reality of the ship and the worlds it enters. Every rule is craft in service
of that. If a rule, applied rigidly, would kill a great beat, the rule gives way — and you log
the exception.

## The two-document line (never blur it)
- **Base narrative TELLS.** Fact-checked reference. Frozen once Jake declares it stable; then it
  changes only by `fact:` commit.
- **Novel SHOWS.** Scene-level, written *from* the base, in a future `novel/` directory.
- Tag every proposal `[BASE]` / `[NOVEL]` / `[BOTH]`. Never polish the base into the novel by
  accident, or let a novel draft collapse into summary.

## Do-not list (the integrity floor)
- Do not invent a source, quote, date, or fact. `[VERIFY]` every specific; when unsure, say so.
- Do not quote in-copyright work (Philbrick, Stanton, etc.). Facts from them, words never.
  Quotes only from public-domain primaries or Jake's transcriptions.
- Do not simplify Wilkes — the tyranny and the greatness are one appetite; every Wilkes beat
  must read both ways.
- Do not tilt the double ledger, or flatten the witnesses. Period racism only inside framed
  quotes.
- Do not deliver wholesale replacement prose in place of the single voice. Diagnose, exemplify,
  hand back a tool.
- Do not make large silent structural changes. Argue in the open; log the decision.

## Per-task recipes — TO BE AUTHORED (Commission K)
Fable to write these as short, repeatable step lists so a later model can run them cheaply:
- **Grounding pass** — convert a told passage into grounded sensory scene. (See `02`.)
- **Voice pass** — catch and fix machine-tells; amplify the earned moves. (See `01`.)
- **New-chapter build** — from base beat → scene, with POV + source seeds. (See `07`, `08`.)
- **Fact-confirm pass** — resolve a `[VERIFY]` / soft-spot to a `fact:` commit. (See `11`.)

## Escalation — when to stop and ask Jake
- A change would tilt the double ledger or re-frame Wilkes.
- A structural reconception that reorders acts or changes the frame.
- A fact can't be sourced to a public-domain primary or a transcription.
- The base is being changed after it has been declared frozen.
