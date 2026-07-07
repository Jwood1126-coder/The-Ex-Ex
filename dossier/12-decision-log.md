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

### 2026-07-07 — The fact-gate: provenance governs events, not senses (Fable pass 1)
**Decision.** Adopted the three-layer fact-gate as the project's grounding license
(`02-grounding-engine.md`, Part II): **[E]** event-facts (require provenance, enter by `fact:`
commit), **[W]** world-facts (period-general truths — the era's furniture — requiring accuracy
and a [VERIFY] tag, not event-provenance), **[I]** invented specifics (banned in [BASE];
licensed in [NOVEL] only inside the record's genuine silence, flagged until checked).
**Why.** Root-cause finding of the grounding diagnosis: the provenance rule had been silently
over-applied to sensation, so vividness was outsourced to quoted witnesses and the narrator's
own sentences went aerial. The gate restores the narrator's senses without opening the door to
laundered guesses.
**Reversal cost.** Moderate. The grounding engine, its exemplars, and any passes run from it
are built on this distinction; reversing means re-auditing whatever those passes touched.

### 2026-07-07 — Boundary: 01 owns sound, 02 owns matter (Fable pass 1)
**Decision.** `01-voice-bible.md` governs how sentences *sound* (earned moves vs. tics,
including the curation-directive audit); `02-grounding-engine.md` governs what sentences
*touch* (matter, senses, the fact-gate). Each file points at the other instead of duplicating.
**Why.** The two commissions share a root (directives fire where images are under-rendered)
and would otherwise colonize each other.
**Reversal cost.** Trivial — move sections, update pointers.

### 2026-07-07 — Exemplar policy: crown jewels are never demonstration targets (Fable pass 1)
**Decision.** Worked exemplars are drawn from second-rank scenes (e.g., the *Peacock* ice nip),
never from the book's crown jewels — the belaying-pin prologue above all, and the Malolo
submission crawl. Demonstrations on those scenes are refused even if asked for casually.
**Why.** A model's version of the most important scene anchors the author's own before he
writes it; the demonstration's value (technique transfer) is identical on adjacent material,
and the contamination cost is not.
**Reversal cost.** None going forward; violating it retroactively can't be undone — which is
the point.

### 2026-07-07 — Grounding passes output "debts" routed to the read-throughs (Fable pass 1)
**Decision.** Every grounding pass keeps a debt ledger: details the fact-gate refused to
invent become named wants (item, likely primary source), appended to
`02-grounding-engine.md` §VI.4. The taxonomy's six anchor families double as the read-through
harvest template (margin codes: E event / S sensation / V voice).
**Why.** Ties the engine to the project's next milestone (Erskine, then Reynolds read-throughs)
so the passes fuel themselves from planned work instead of tempting invention — and makes the
read-throughs cheaper, not costlier.
**Reversal cost.** Low. Untracked debts simply revert to being rediscovered by later passes.

### 2026-07-07 — The directive test governs STYLE_GUIDE tell #1 (Fable pass 2)
**Decision.** Curation directives are judged by one test (`01-voice-bible.md` §II.1): an
imperative that outsources the book's bookkeeping to the reader (*remember/hold/mark/file/sit
with* for a later payoff) dies; an address that enacts its content in the moment it is spoken
may live, on the direct-address budget. Nine instances condemned with demonstration fixes; two
licensed survivors nominated ("The reader may hold the chart…" at Malolo; "Stand Charlie
Erskine next to that verdict") — survivors pending Jake's ratification.
**Why.** The blacklist banned the pattern but gave no principle, so enforcement would have
been taste-by-taste and inconsistent across sessions and models.
**Reversal cost.** Low — the test is a sentence; re-litigating the ten instances costs an
afternoon.

### 2026-07-07 — Voice certifications recorded; phantom fixes barred (Fable pass 2)
**Decision.** `01-voice-bible.md` Part III certifies as CLEAN (grep + read, this date):
thesaurus elegance, the not-X-but-Y reflex, hedge-stacking (one borderline, act_1 ch. 5).
Later passes do not re-fix certified categories; a new violation gets fixed and the
certification re-dated.
**Why.** The predictable failure mode of successive model passes is "improving" what isn't
broken — the certifications make restraint enforceable.
**Reversal cost.** None; certifications are dated observations, not rules.

### 2026-07-07 — The three-braid spine is the analysis of record (Fable pass 2)
**Decision.** The Wilkes unraveling is architecturally three braided chains
(`05-architecture-critique.md` Part I): slights received (rank), the wound passed downward
(power), the machinery of mutual fear (contact) — junction at Malolo, where Braid 2's
messenger (Underwood) and Braid 1's soft spot (Wilkes Henry) die inside Braid 3's machinery.
This supersedes the flat four-beat slight-chain as the working model; the ice is Braid 2's
Act IV rung, not an interruption.
**Why.** The braids escalate by different mechanisms; wiring them separately is what lets the
novel make each rung ignite the next without flattening Wilkes into a villain (hard rule 11).
**Reversal cost.** Moderate — 04, 06, 07, and 08 will reference braid/rung labels.

### 2026-07-07 — Structural decisions escalated, not taken (Fable pass 2)
**Decision.** Seven decisions are Jake's and are logged as OPEN in
`05-architecture-critique.md` Part VI: the frame (F2 "two documents" recommended ★), POV
alternation scheme, the February-traverse camera, act count, Utiroa treatment, the preface's
Tyson citation, and Vendovi's structural promotion (BS-3). No session builds `08-chapter-map`
or drafts the prologue until decisions 1–4 are ruled; the Erskine read-through carries the
architecture-grade question (his Act III–IV coverage) that gates several of them.
**Why.** Operating-manual escalation rule: frame changes and act reordering are the author's;
a recommendation on file plus an open flag beats a quiet fait accompli.
**Reversal cost.** None — that is the point of leaving them open.

### 2026-07-07 — The three windows into Wilkes (Fable pass 3)
**Decision.** Wilkes is accessed through exactly three channels (`04-cast-bible.md` Part I):
the names he put on the map (the chart as candid diary), his own prose when terrified (quote
him under fear, paraphrase him under vanity), and the witnessed body and its rituals (the
spyglass, the uniform, the pennant). Anything beyond — narrated interiority, inner grief — is
invention about the one man the book rules off-limits, and collapses the weather system into
a character.
**Why.** "Never simplified" (hard rule 11) needed an executable form; three windows make the
discipline checkable at draft time.
**Reversal cost.** Low on paper, high in practice — scenes built through a fourth window would
need rebuilding.

### 2026-07-07 — Witness-class dignity mechanics (Fable pass 3)
**Decision.** Every person the record flattened belongs to one of three classes
(`04-cast-bible.md` Part IV): named-with-record (scene presence, attested acts), named-without-
interior (presence without ventriloquism; the flattening itself may be named), collective-with-
agency (action rendered as action, plus the archive sentence). Assignments move **up** on
read-through evidence, never down.
**Why.** Hard rule 7 needed craft-level mechanics so "dignity" is a checkable property of a
draft, not a mood.
**Reversal cost.** Low — the classes are a lens; loosening them is one log entry (but see the
archive-test dependency in 06 §V).

### 2026-07-07 — The ledger discipline package (Fable pass 3)
**Decision.** Adopted in `06-double-ledger.md`: (a) two ledgers, moral and mortal, with
**no cross-netting** — American losses never offset inflicted dead; (b) "and" is the ledger's
conjunction — "but" between entries is a tilt, greppable; (c) the narrator-umpire declaration
("It has to be written both ways…") is budgeted **once per book and Malolo owns it**; (d) the
variation matrix rotates seven delivery forms — never the same form twice running, ≥3 forms
per act; (e) six tilt-tests gate any edit touching a ledger beat.
**Why.** Act V holds twelve of the book's eighteen ledger beats; without a rotation discipline
the balancing move metronomes exactly where it matters most (confirmed by the 01 §II.3
census).
**Reversal cost.** Moderate — 07's scene entries will carry form assignments; re-litigating
the package means re-tagging them.

### 2026-07-07 — Malolo-as-news is the recommended novel design, pending verification (Fable pass 3)
**Decision.** Unless the read-throughs place a witness on Malolo's beach, the novel renders
July 24–25, 1840 as *news reaching the witnesses* — smoke from the boats, the story passing
gun to gun, the crawl secondhand (`06` Part VI). If a witness was present, the scene stays
cost-side only (forms 1+2; never choreography).
**Why.** POV honesty and the spectacle test point the same direction; distance is
simultaneously the dignity rule and the dread. Marked **pending** on the whereabouts check
(11).
**Reversal cost.** None until drafting; afterward, a rebuilt centerpiece chapter.

### 2026-07-07 — Remote history replaced; prior remote state archived as tags
**Decision.** Pushed the real history to `origin/main` (`--force-with-lease`), superseding the
setup entry's "not yet done." Before overwriting, the remote was found to hold one commit
beyond the stub — a web-UI upload (`files.zip`) containing an *earlier* delivery of the
manuscript (same underlying commits, pre-dossier CLAUDE.md, no dossier/ or prompts/). Its
contents were diffed against local history: nothing unique. Both prior remote states are
preserved as tags: `archive/stub-initial` (the empty stub) and `archive/remote-upload` (the
zip upload).
**Why.** Provenance-by-commit makes the real history load-bearing; the upload was a redundant,
older snapshot — but nothing is deleted, only demoted to tags.
**Reversal cost.** None. `git checkout archive/remote-upload` recovers the uploaded state.

### 2026-07-07 — The research/ harvest tool established (Fable pass 4)
**Decision.** Created `research/` — the combined primary-source layer beneath the base:
`erskine-harvest.md` (direct page-cited harvest of the public-domain 1896 text; verified
extracts + coverage map + anchor table + continuation protocol), `reynolds-digest.md`
(Jake's Play Books export structured with Penguin page refs), `drive-archive-digest.md`
(Jake's Drive corpus inventoried, reconciled, and its errors marked dead), and a README
whose one rule governs everything: **a note without a page is a lead, not a fact.**
Erskine/Wikisource page-cite convention fixed (printed p. n = djvu p. n+17); quotes entering
the base must be spot-verified against the scan.
**Why.** The author asked for a comprehensive reference tool combining his research with
direct study of the primaries. First extractions immediately corrected the base's
crown-jewel scene geometry (the pin: deck level, cabin skylight, Wilkes at a table, the
weather roll — TYBTM pp. 19–20) and settled soft spots (Bowditch ~p. 10; Boyle; the hat at
the bridge draw; "foul scamp" wording; Case & Knox) — proof the layer earns its keep.
**Reversal cost.** Low structurally (additive directory). The findings, once committed as
`fact:` changes, are governed by the normal commit history.

### 2026-07-07 — Modern-knowledge usage tiers adopted (Fable pass 5)
**Decision.** All retrospective/modern knowledge (`research/modern-lens.md`) enters the
book under three tiers: **T1** wonder-aside fuel (narrator may say it, on the existing
one-per-chapter budget, witness-filtered when possible); **T2** mechanism knowledge (shapes
scenes and behavior, never named in the text — exits the pen wearing 1840's clothes);
**T3** hazard (informs the author's judgment, banned from the page in any form — framework
vocabulary, diagnoses, modern moralizing). Companion file `research/period-texture.md`
holds the [W]-class contextual layer (world events, sailor dailiness, dress, social
fabric), all tagged and story-tethered.
**Why.** The author asked for indirect research for texture and immersion, including what
modern psychology, medicine, and earth science can supply that the sources couldn't. The
tiers let that material enrich the book without anachronism leaking into the voice
(STYLE_GUIDE tell #3; grounding anti-pattern 3) — and they make misuse checkable at review.
**Reversal cost.** Low as structure; high in practice if ignored — untiered modern
knowledge is exactly how period voice dies.

### 2026-07-07 — First novel outline authored: "The Pin and the Pen" (Fable pass 7)
**Decision.** Created `novel/OUTLINE.md` (v0.1) at Jake's direction — the first outline,
with a hero's-journey/epic architecture. Conception: Charlie carries the monomyth with
both hinges inverted (the threshold trial is the *refusal* at the skylight; the elixir is
*testimony* — the pin becomes the pen), Wilkes carries the shadow epic (same monomyth,
boon seized, every return-gift refused, the Upshur reprimand as his atonement-with-the-
father), Reynolds carries the apostasy arc. Frame F2 (the two documents), movement-scale
POV, six parts + prologue/coda, Malolo as the braid junction and abyss, the trial as the
underworld of paper, nostos denied as the back half's shape. All 05 Part VI items adopted
as ★-recommendations are marked PROVISIONAL and reversible; a liberties register names
every invention and its gate class; monomyth stations are scaffolding only, never named
in the text (same rule as T2 modern knowledge).
**Why.** Jake asked for a first outline true to the sources with creative liberties for
storytelling and "some kind of hero's journey element… a sort of epic." A straight
Campbell arc would tilt the ledger (the boon is blood-bought); the inverted hinges keep
the epic and the double ledger in the same hand.
**Reversal cost.** Low — one additive file; every provisional choice lists its fallback
(F1 if F2 falls; generic-forecastle camera if Erskine starves the traverse; direct-witness
Malolo if whereabouts demand it).

### 2026-07-07 — Theme forge run; three candidate families delivered (Fable pass 8)
**Decision.** Ran a 29-agent forge (film-core study across 25 acclaimed philosophical
films; full corpus re-read; three independent synthesizers; three-lens adversarial panel
per conception) to find the novel's philosophical core, per Jake's directive that theme
is "the most important part of the whole project." Six conceptions judged, five
survived, resolving into three families now in `novel/THEME_CANDIDATES.md`: **A. The
Mirror** (first contact — can we ever see anything but ourselves; Solaris under sail;
the encountered world keeps passing the test the expedition fails), **B. The Signal**
(light-lag and custody — whom are you speaking to when no answer can come; the memoir as
the pin laid down or the pin swung at last), **C. The Second Signing** (consent — would
you sign again, knowing everything; the re-enlistment articles under the gallows-rig).
Recommendation marked ★: the Signal as core, the Mirror as encounter-grammar, the
Second Signing as Charlie's spine-decisions. Correction adopted from the panel: Vendovi's
captivity was two years, not four. New load-bearing gates: GAP 2 (1890 frame) and GAP 5
(encountered-world witnesses) promoted to theme-critical.
**Why.** The earlier want-grid themes were theses, not questions; the film study supplied
the laws (question felt before understood; metaphor literally true; openness structural;
the Other never the mirror's furniture; the talky climax needs a body) and the corpus
re-read proved which questions this material natively dramatizes.
**Reversal cost.** None until Jake rules; the menu is additive. Once a family is chosen,
OUTLINE.md goes to v0.2 and the research execution order re-ranks.

### 2026-07-07 — Theme RULED: the Signal; outline rebuilt to v0.2 (Fable pass 9)
**Decision.** Jake adopted the theme forge's ★ recommendation: the book's core is THE
SIGNAL (reaching people across the lag between sending and arriving — the pin as the
instant message refused, the memoir as the slow message sent), with the Mirror as the
encounter chapters' grammar and the Second Signing as Charlie's two spine-decisions.
`novel/OUTLINE.md` rebuilt to v0.2: every beat carries a theme move; the forge's
found-scene bank threaded in (dictated letters, mailbag chapters, skylark diptych, T3
tableau, Agate sitting, Columbia bar, crates cross-cut, blank page, desk-as-second-
signing); liberties register formalized with exactly one T3 (the articles/gallows-launch
adjacency, disclosed); 05 Part VI decisions 1 (frame = F2) and 5 (Utiroa flat-voice)
recorded as settled by the theme ruling. Openness is structural and governs the wanting
and the writing only — the killing stays adjudicated once, at Malolo.
**Why.** The Signal's metaphor is literally true in 1838 (film law: the frame must never
need arguing); it gives the already-adopted two-documents architecture its heart; its
climax mechanic (the reader as the pin night's only corroborating witness, watching the
old man choose the words) is the strongest ending in the judged field.
**Reversal cost.** Moderate and falling: v0.1 is in git; the fallback families (Mirror
alone, Second Signing alone) are fully worked in THEME_CANDIDATES.md. The in-flight
gate harvest (wf_f79b5783) derisks the two floors the choice made critical (GAP 2, the
TYBTM Signal questions) before drafting begins.

### 2026-07-07 — First prose drafted: the prologue, forge-reviewed (Fable pass 10)
**Decision.** At Jake's commission ("Start with the first draft of the story… a
masterpiece"), drafted the novel's prologue (`novel/prologue.md`, "The Weather Roll"):
the 1890 desk and the pin night up to the suspended pin, stopping before the choice per
the three-payment design. Floor built first: the 10-agent gates harvest closed GAP 2 to
first-draft standard (`research/1890-frame.md`) and answered the Signal questions from
the 1890 text itself. Draft v0.1 was then attacked by a four-lens adversarial panel
(voice law, fact floor, theme discipline, craft bar); all four blockers applied in v0.2
(explained-irony sentence cut; pen death-grip declared as transposed invention;
theme-announcing clause cut; the flogging-attribution fuse restored in Erskine's own
terms) plus the should-fixes. The crown-jewel exemplar policy is not breached: that
policy barred *demonstrations* in the dossier; this is the commissioned novel draft.
**Why.** The harvest made the scene honest before it was written (Wilkes awake at the
chart; flogging pre-voyage; the 1890 self-publication real), and the review made it
lawful before it was committed.
**Reversal cost.** None — a draft file; Jake's read rules. Spine-grade corrections
flagged in dossier/11 await his `fact:` ratification (they touch CLAUDE.md's own spine
line).

### 2026-07-07 — The landsman's eye codified; Chapter One landed; prep fleet running (Fable pass 11)
**Decision.** (1) Jake's directive — readers unfamiliar with ships must always be able
to see positions, heights, and objects — codified as the LANDSMAN'S EYE addendum in
dossier/02 (teach through consequence; apposition gloss; body-relative staging; drop
jargon when the picture works without it; one teach per object per book), with the
memoir's own explaining register as the period license. Prologue revised to v0.4 under
the rule. (2) Chapter One ("The Gunner's Daughter") drafted in the primary's true
chronology and passed through the four-lens panel (a legibility lens now standing);
v0.2 applies all blockers — explained irony cut, the flogging verdict-tail replaced
with the yard shown working, the gun unnumbered per harvest F5, the yard-return
geography rebuilt on the record's landing-and-boat picture, and Wilkes' introduction
corrected where v0.1 contradicted the base ("passed over" → "abler sea-officers than it
could employ"). pp. 1–16 evidence deposited in erskine-harvest.md Part I.b. (3) The
book-prep fleet (wf_b1b67759) runs in background: deck-geography brief, Erskine
front-to-back in four spans (incl. the Acts III–IV density question and the Malolo
whereabouts question), Reynolds' Fiji whereabouts, and Wilkes v3's Malolo/Vendovi/
Underwood extractions — the preparations gating every next chapter.
**Why.** "Any and all preparations needed to make the best possible product" — the
pipeline is now: research floor → draft → adversarial panel → revise → commit, with
legibility a standing lens.
**Reversal cost.** None; drafts are files, rules are additive, and every provisional
staging choice is declared in its chapter header.
