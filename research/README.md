# research/ — The Primary-Source Harvest

**What this is.** The combined research tool for the novel: Jake's Drive-archive research
merged with direct harvests of the public-domain primaries, every entry carrying its source
and page so nothing rests on memory — his or a model's. This is the layer *underneath* the
base narrative: the base tells the story; these files hold the raw material with citations.

**Relationship to the rest of the repo.**
- Base acts cite nothing inline; corrections flow **from here** into `fact:` commits.
- The dossier's grounding debts (02 §VI.4), cast wants (04 §VI), and provenance table (11)
  are the harvest's standing shopping list; entries here mark which debt they settle.
- `SCENE_BANK.md` (novel phase) will be assembled largely from V- and S-coded entries here.

## Files

| file | source | status |
|---|---|---|
| `erskine-harvest.md` | Erskine, *Twenty Years Before the Mast* (1896) — public domain, full text local | **in progress** — key scenes verified pp. 10–21; coverage map ingested; front-to-back harvest continuing |
| `reynolds-digest.md` | Jake's Play Books highlights of *The Private Journal of William Reynolds* (Penguin 2004) | **complete for existing notes** (25 highlights) — full journal read remains Jake's |
| `drive-archive-digest.md` | Jake's Drive docs: Erskine Accounts, Erskine Timeline, Ex. Ex. References, research mega-doc | inventoried + key findings; mega-doc processing pending |
| `wilkes-narrative-harvest.md` | Wilkes, *Narrative* (1844/45) — all 5 vols, public domain, full texts local | **in progress** — Honolulu General Orders (named floggings), the capitulation-crawl custom, Piner's Bay verified; Malolo/Vendovi/Underwood anchored |
| `other-eyewitnesses.md` | Colvocoresses 1852/1855 (midshipman, Emmons overland); J.G. Clark 1848 (second forecastle voice) — public domain, full texts local | **acquired** — identity-verified; harvests pending |
| `period-texture.md` | indirect/contextual: the world of 1838–42, sailor dailiness, joys, grievances, normal-then-crazy-now, dress, social fabric | **authored** — [W]-class throughout, [VERIFY] discipline; fuel for dossier 03 |
| `modern-lens.md` | what modern psychology, medicine, ocean/earth science, and historiography add that the sources couldn't know | **authored** — governed by T1/T2/T3 usage tiers; the wonder-aside's fuel depot |

## Conventions

**Entry format:** page cite → verbatim quote (or kernel) → codes → what it feeds.
**Codes:** `E` event (→ `fact:`/`enrich:` commit candidates) · `S` sensation (→ grounding
taxonomy family A–F) · `V` voice/dialogue seed (→ scene bank). `★` = high value.
**Page cites (Erskine):** printed page of the 1896 edition. Working text is the Archive.org
OCR (`twentyyearsbefor00ersk`); printed page *n* = Wikisource djvu page *n+17* at
`en.wikisource.org/wiki/Page:Twenty_years_before_the_mast_-_Charles_Erskine,_1896.djvu/`.
OCR is lightly cleaned (spacing, hyphenation); **any quote entering the base must be
spot-verified against the Wikisource scan first** — OCR cleanup is flagged where it matters.
**Page cites (Reynolds):** bracketed page numbers from Jake's Play Books export (Penguin
ebook pagination) — usable for retrieval, but the print edition's pages may differ; final
cites come from Jake's copy.
**Layer discipline:** everything here is [E]-class evidence or candidate evidence; the
[E]/[W]/[I] gate (dossier 02, Part II) governs how it may be used.

## The one rule here

**A note without a page is a lead, not a fact.** Jake's archive notes are treated as leads
until matched to a primary page (some trace to Philbrick — facts usable, words never).
Conflicts between a note, the base, and the primary are resolved by the primary, by `fact:`
commit, with the page in the commit body.
