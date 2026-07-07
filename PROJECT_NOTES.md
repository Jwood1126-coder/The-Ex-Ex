# PROJECT_NOTES.md — The Ex. Ex.
## Development Log, Decisions, and Handoff

**Status as of July 7, 2026:** Base narrative v2 complete — preface + five acts, ~30,200 words, fact-checked, voice-passed. Ready for primary-source read-throughs. Novel phase not yet begun.

This document is the source of truth for how this project got here and how to continue it — in Claude Projects, GitHub Codespaces, Claude Code, or by hand. Read it together with `README.md` (what the repo is) and `STYLE_GUIDE.md` (how it must sound).

---

## 1. What exists and where

```
The-Ex-Ex/
├── README.md          Repo purpose, provenance, the one rule
├── STYLE_GUIDE.md     The voice, codified — including the "tells to kill" blacklist
├── PROJECT_NOTES.md   This file
├── CLAUDE.md          Operating instructions for AI sessions (Projects / Code / Codespaces)
├── 00_preface.md      Front matter (~740 words)
├── act_1.md           The Making of a Commander, 1828–Aug 1838 (~5,200 words)
├── act_2.md           The Atlantic and the First Ice, Aug 1838–Apr 1839 (~7,700 words)
├── act_3.md           Paradise and Poison, May–Dec 1839 (~4,700 words)
├── act_4.md           The Continent, Dec 1839–Apr 1840 (~4,300 words)
└── act_5.md           The Price of the Chart, May 1840–1842 + codas to 1943 (~6,300 words)
```

Acts I–II are refined from the 2015–2020 Google Docs drafts (which stopped at Orange Harbor, April 1839). Acts III–V are new, written from the record in the same voice. Act II is the longest because it had the richest draft material; III–V now match Act I's density and will keep thickening as the primary read-throughs feed corrections and detail.

**Original source archive (Google Drive):** "The Ex. Ex." main draft; the research mega-doc currently misnamed **"Sales Order Cycle Research"** (⚠️ rename this before it's lost forever); "Ex. Ex. References"; "Erskine Accounts"; the Reynolds Play Books highlight export; Characters / Introduction / Timeline docs. The best transcribed quotes in the manuscript came from these.

---

## 2. The editorial decisions (the plan of record)

**Form: novel, not narrative nonfiction.** The verdict from the archive review. Reasons: the story's engine is interior (a commander's unraveling witnessed from two vantages), the POV assets are extraordinary (Erskine's memoir from below decks; Reynolds' *illegal* secret journal from the wardroom), and Philbrick already owns the definitive nonfiction. The novel is the open lane.

**Structure:** Dual POV — Charlie Erskine (the body, below decks) and William Reynolds (the pen, the wardroom). Wilkes is never a POV character; he is the weather system both men live under. Frame: old Erskine in 1890, writing his memoir, opens the book at the taffrail with the belaying pin; the confession closes it. Title stays **The Ex. Ex.**

**Two-document discipline (the one rule):** The base narrative *tells*; the novel *shows*. The base stays frozen as reference once the read-throughs stabilize it. Novel work happens only in a future `novel/` directory, one file per chapter, written *from* the base. Never polish the base into the novel by accident.

**Voice:** Jake's narrative voice — the wonder-aside, the scale shock, dry irony, sparse direct address, deck-level sensory grounding — fused with tight narrative-nonfiction discipline, with machine-prose patterns explicitly banned. The full spec, including the seven "tells to kill" (curation directives, aphorism stacking, the not-X-but-Y reflex, book-meta stage management, explained irony, uniform paragraph rhythm, thesaurus elegance), lives in `STYLE_GUIDE.md`. Every writing session, human or AI, reads it first.

---

## 3. The verification pass — what was checked, fixed, and cut

The v1 draft used inline `[VERIFY]` tags. All were resolved in v2 by a research pass against: Wikipedia (United States Exploring Expedition; Charles Wilkes; USS Sea Gull; William Reynolds), DANFS ship histories (history.navy.mil), the Smithsonian's Ex. Ex. digital collections (sil.si.edu), USNI *Proceedings* Feb 1962 ("Tarawa: The Tide that Failed"), Wikisource (Erskine's 1896 front matter), the Franklin & Marshall Reynolds Family Papers timeline, the Oregon Encyclopedia, and Philbrick's C-SPAN Booknotes interview. Stanton and Philbrick remain navigation charts — **facts only, never prose**.

**Corrections made (including errors inherited from the old drafts):**

| Was | Now |
|---|---|
| Rio commodore "Downes" | **John B. Nicolson**, razee *Independence*, Brazil Squadron |
| Orange Harbor "in the Hermite Islands" | On **Hoste Island**; squadron joined *Relief* + both schooners there Feb 19, 1839 |
| *Sea Gull* "twenty days from the end" | **Eleven days**; last seen midnight April 28, 1839, lee of Staten Island; complement 15; PM James Reid + PM Frederick Bacon; monument at Mount Auburn |
| *Flying Fish* record, vague | **70°S on March 22, 1839** vs Cook's 71°10′; Cape Flying Fish / Walker Mountains named for her |
| Captain's uniform "at Callao" | **At sea, August 1839**, after leaving Peru July 12; broad pennant with it; Hudson in captain's coat by arrangement |
| House resolution "May 1828" | **May 21, 1828**; authorization act **May 18, 1836** |
| Reynolds' return from the *Annawan* stranding | Home via frigate ***Potomac*** as the commodore's secretary |
| Deaths "28" flat | **28 by the strict count, "close to forty" by looser ones** — text states the range |
| Malolo dead, single figure | **74–104** (an old Malolo man later reckoned "some eighty") — text states the range |

**Cut as unverifiable** (restore only if a primary source produces them): the 1827 *Peacock*-whale collision; the Downes "competent lieutenant" quote; the Reid berth-swap anecdote; a late-life Erskine–Wilkes reunion scene (the codas now stand on verified material — the 1890/1896 memoir, the Smithson epigraph, the "Crew of the Ship Universal" dedication, the panorama lectures).

**Load-bearing facts confirmed** (sample): *Relief* dispatched home June 21, 1839 from Callao (after the Noir Island anchors ordeal; 100-day Rio crossing record); Reao/Clermont-Tonnerre Aug 13, 1839 — bird-shot to clear the beach = the expedition's first shots; Sydney night entrance Nov 29, 1839; Eld Peak / Reynolds Peak from the Jan 16, 1840 *Peacock* masthead sighting; d'Urville's Jan 21 landing, Adélie naming, and his 1842 death in the Versailles railway fire; *Peacock* rudder disaster Jan 24 (~30 hours); Feb 12 "Antarctic Continent" avowal (coast 140°30′E–112°16′E); Termination turn Feb 21; Ross's 1841 sail-over + Wilkes' chart gift from Sydney; Waitangi witnesses Feb 1840; Vendovi's capture at Rewa (hostage-feast method; 1834 *Charles Doggett* / Ono Island backstory) and his death June 11, 1842, the day after New York — skull to the Patent Office; Malolo July 24, 1840 (Underwood & Wilkes Henry; ~70 landed; two villages razed; the submission crawl); Honolulu floggings past the lawful twelve → the **single 1842 court-martial conviction: illegal punishment → public reprimand**; Mauna Loa Dec 1840–early 1841 (Pendulum Peak, hundreds of porters, snow blindness, ʻaʻā-shredded boots); Upolu bombardment Feb 1841; Drummond's Island/Utiroa April 1841 (missing sailor never found; ~12 killed; town burned); **Tarawa surveyed April 1841 — chart still in use 1943 "with only slight modifications," and its missing tide data part of why the landing bled**; *Peacock* wreck July 18, 1841 (no lives lost; journals/chronometers saved; pilot George; Peacockville; Birnie/HBC); first July 4th west of the Mississippi, Nisqually, July 5, 1841; Emmons–Meek overland party of 39, Sept 7–Oct 23, Siskiyou Trail to Sausalito; *Flying Fish* sold at Singapore Feb 1842; NY June 10, 1842; publication act Aug 26, 1842 (100 copies; 19 of 28 volumes ever published); collections → Patent Office → Smithsonian backbone; Wilkes codas (Trent Nov 8, 1861; 1864 court-martial guilty on all charges, Lincoln cut suspension to one year; rear admiral retired list 1866; d. Feb 8, 1877; Arlington 1909; gravestone "He discovered the Ant-arctic continent."); Reynolds codas (lieutenant Sept 1841 mid-voyage; married Rebecca Krug Aug 16, 1842; Honolulu storekeeper 1850s; claimed **Midway** 1867; **Acting Secretary of the Navy** 1873–74; rear admiral Dec 1873; d. Nov 5, 1879; buried in Lancaster beside his brother, Maj. Gen. John F. Reynolds of Gettysburg; journal published 2004).

**Soft spots — confirm during read-throughs** (these rest on Jake's transcriptions or single tellings; each should get a page-number note by commit): Bowditch's "neatest charts" line and the eleven-days-out count (Erskine, ~p. 224); Erskine's age at the 1838 flogging (fifteen vs sixteen); the Tuetila episode's name/spelling and details; the full "foul scamp" entry wording; the Sydney "are your wills made" story; the Reao bird-shot sequence specifics; the *Vincennes* crew cheering the *Peacock* clear of the ice; John Sac/Tuati; "Old Whittle"; the Orange Harbor launch-survey dates; Malolo village names (text currently says "two villages" — Philbrick/Wilkes give names); the water-casks-via-President anecdote; the Captain Joseph Smith command offer; Wilkes' "I never thought of such a thing" quote.

---

## 4. Tools and methods used (for the record)

Google Drive (read-only) for the archive review; web search and page fetches for the verification pass (sources listed in §3); a scripted regex pass to strip resolved `[VERIFY]` tags; manual surgical edits for every fact change and voice fix; git assembled in a sandboxed Linux container. No prose was taken from any in-copyright secondary source; all embedded quotes are from public-domain primaries (Erskine 1896, Reynolds journal excerpts as transcribed in Jake's notes, Wilkes' *Narrative*) or from Jake's own transcriptions pending page-check.

---

## 5. How to proceed

**Immediate:**
1. Push this repo (commands below, or via a GitHub connector in Claude).
2. Rename the "Sales Order Cycle Research" Google Doc → "Ex Ex — Research Notes."
3. Begin read-through one: Erskine, *Twenty Years Before the Mast* (Archive.org/Wikisource), with `act_1.md`–`act_3.md` open. Fix by commit.

**Read-through order:** Erskine → Reynolds *Private Journal* (Penguin 2004) → Wilkes' *Narrative* (sil.si.edu, dip as needed) → Stanton/Philbrick only to arbitrate conflicts.

**Commit conventions** (the history is the fact-check log):
- `fact:` — correction or page-number confirmation, cite source in the body (e.g., `fact: Erskine flogging age 15, TYBTM p. 24`)
- `enrich:` — new verified material added to an act
- `voice:` — style fix per STYLE_GUIDE
- `novel:` — anything under `novel/`
- `meta:` — README / NOTES / CLAUDE.md changes

**Working in Claude Projects:** add all repo `.md` files to project knowledge; project instructions should say, in effect, "Read CLAUDE.md and obey STYLE_GUIDE.md; base narrative is telling-mode reference; propose changes as diffs against specific files." Re-sync project knowledge after meaningful commit batches.

**Working in Codespaces / Claude Code:** clone, and the `CLAUDE.md` at repo root takes over — it encodes the rules so any session starts oriented.

**Novel phase (when the base is stable):** create `novel/` with `CHAPTER_MAP.md` first — mapping base-act beats to novel chapters and assigning POV (Charlie / Reynolds / frame). Draft order recommendation: prologue (1890 frame + the pin), then the Act II storm material (richest, best-sourced), then forward in sequence. A `SCENE_BANK.md` harvested from the primary read-throughs (verbatim quotes with page cites, sensory details, dialogue seeds) should precede any chapter drafting.

**Push commands (from a machine with GitHub auth):**
```bash
git clone <this-folder-or-unzip-it>   # if starting from the zip
cd The-Ex-Ex
git push -u origin main               # remote 'origin' is already configured
```
If the GitHub repo doesn't exist yet, create it empty (no README) at github.com/Jwood1126-coder/The-Ex-Ex first, or run `gh repo create Jwood1126-coder/The-Ex-Ex --private --source . --push`.
