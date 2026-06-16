# Verification for Ch 4: The Weather

**Chapter file:** `chapters/04_The_Weather.md`
**Word count:** 3,789 (project-standard count: whitespace-split of the prose body between the `---` markers; amended band 3,000–3,800 — amendment recorded in the brief with reason; second-shortest chapter, under Ch02's 3,822)
**Date:** 2026-06-11
**Drafter:** chapter-drafter agent, native model (opus), single attempt — clean. Extension pass by chapter-reviser agent (four author notes: Aldine beat, tide table widened, literacy caveat, Keio buttons). Author trim pass in the main session: 4,508 → 3,789, cutting the type-case paragraph (financing folded to one sentence), Bacon, the Aldus door notice + Festina lente, the modern-literacy span overrun, and assorted slack; fixing the Ch03-duplicate sentence, the "Movement I/II" register leak, an "inner weather" figure re-spend, the false "shortest in the book" self-claim, and the tide table's first figure (12.6M).

> Three passes, run once each. The compile gate (`compile.py --final`) reads the **Verdict** line at the bottom.

---

## 1. Grep pass

`python scripts/audits.py 4` — **all hard checks clean.** Review rows, dispositioned:

| Audit | Expected | Found | Note |
|---|---|---|---|
| A1 em-dash | budget ≤8 | 0 (prose) | all file hits in the stripped self-check; the semicolon and comma-series carry the cadence (voice pass: rhythm does not suffer) |
| A3 ellipsis | review | 0 (prose) | self-check only |
| A4 exclamation | review | 0 | none, even quoted |
| B3 hedging | review | 7 (prose) | content-bearing ("almost" ×3 at near-miss points; "very" inside the quoted *I am very cold*; temporal "just"; "the very next year" idiomatic) |
| B4 filter verbs | review | 1 | "began to be produced" — the onset is the content (dailiness entering the archive) |
| S7 "you" | review | 0 (prose) | self-check only (the Aldus door-notice quote, which contained "you," was cut in the trim pass) |
| C4 span-phrase | review | 0 (prose) | "five thousand years" not used (budget spent in Ch01–03); variants only; "five thousand editions" is the Luther dossier count |
| E3 -ly density | review | ~39 | below gold standard's 42 |
| F3 refrain | review | 2 by hand | "addressed to everyone, which is a different way of not being addressed to me" (Luther beat); the close ("does not... say that it is tired") — each new work |
| D1–D4 hygiene | 0 | 0 | |

## 2. Voice pass (slow prosody pass, fresh context — per DECISIONS)

- **A–G all pass:** voice card (flinch varied; the two big inventories run as the archive's voice and the narrator's declaratives cut back through); no explainer-drift (the named risk — printing mechanics rendered as objects and counts, never taught); Poster Test pass — "the first thing it ever rained on that could read" is earned by the next paragraph performing the test in the book's own voice ("the most dangerous sentence in the chapter... Back to the hands"); pity-risk "I almost miss the cold man" held by its frame ("I notice" audits the feeling instead of indulging it); gold-standard diff pass (zero em-dashes unnoticeable on a slow read); quoted seams clean; opening inherits Ch03's turn cleanly ("What ended was its monopoly. The press took over the reaching.").
- **Closing-paragraph guard:** all four pass — no scaffolding sentences; the last line stands alone; no misplaced facts; no audit-verb closer (closes on the air and the object).
- **Findings & author rulings:** 0 MUST, 0 SHOULD. 3 CONSIDER — all **declined with reasons**: (1) the tide-table sentence's flat stretch between 331M and 356M enacts the data's own plateau — 1701–1750 was the curve's actual stall; the drone is the archive telling the truth; (2) the "by 1750" interpolation carries the data's own date inside the climb; (3) the hand→room→name triad is anchored to the Aldine Virgil and phrased as motion, not theme.

## 3. Continuity pass (fresh context, vs M2 + ledger + brief + BOOK_MAP + Ch03 cross-checks)

- **Fact table:** 45 checkable claims; **44/45 ✓**, 1 minor drift (SHOULD-1, applied — see below). Zero unsourced, zero contradictions; every hedge carried into prose (run "cannot be pinned"; survivors with criteria; Luther's share kept as the dispute; "low estimates" on the tide table; "an estimated" on the calfskins). Tide-table arithmetic verified (641 ÷ 12.6 = 50.9 → "more than fifty times").
- **Caution compliance:** all M2 print-anchor cautions respected or n-a (hammer disputed/mailed; Table Talk unused; Griffo cut the type; semicolon claim unused; 1501 cutoff named arbitrary; literacy as signature-inference; Google with date + irony; Grenville not "Greville"; no penniless-Gutenberg).
- **Quote copyright:** clean — Mallet (QUOTABLE) verbatim; "at least until Sunday" (fair-use short) verbatim; *prima typographicae incunabula* (PD) verbatim; Erasmus as reported speech (safest fair-use posture); Piccolomini paraphrase-only honored; Carolus petition deliberately rendered as reported speech (tense-shifted, no quotation marks); Bacon confirmed absent (cut).
- **Cross-chapter:** opening inherits Ch03's close without re-narration; the 158/180 retelling ruled legitimate development (Ch03 one-sentence rumor → Ch04 load-bearing beat, per the brief); Ch03-duplicate sentence confirmed absent; *I am very cold* callback matches Ch03's usage.
- **Ledger:** O-06 deployed (open + object-return close); refrain exactly 2, each new work, correctly still absolute-but-depersonalized (the bend begins Ch05); reveal stage 3 NOT leaked (no Turing/Lovelace material); wound not stated; both seeds planted-not-spent (interiority "walk past that open door" → Ch09; keeping-inversion "I file that quietly" → Ch07); conscious gaps untouched; tense rule held.
- **Brief:** 7/7 beats honored. **OPTION B taken** (object-close on the BL Grenville copy); pressroom sensory placed mid-chapter at the metaphor-retirement, where it defuses the figure.
- **Findings & author rulings:** 0 MUST. SHOULD-1 **applied**: Google exclusions trimmed to the dossier-exact "it excluded the serials" (dropping the inferred "newspapers and pamphlets"). CONSIDER-1 (1609-until-2005 Carolus re-dating as a missed irony) **declined** — the chapter is at band ceiling; no false claim exists. CONSIDER-2 (Carolus reported-speech) **confirmed deliberate**. CONSIDER-3 (stale band in metadata header) **applied**.

### Pre-print tasks (logged for PHASE 9)
1. **Novel counts** (1,421 / ~47/yr / ~76/yr): dossier row is single-sourced (Garside/Raven/Schöwerling 2000) — independently re-verify before print.
2. **Buringh & van Zanden tide table**: the seven half-century figures were summed in-session from the OWID CSV and not adversarially re-checked — re-check all seven against Buringh & van Zanden 2009 directly; confirm the "book = title over 49 pages" definition is acceptable compression for the prose's flat "books."
3. **Literacy figures** (1750 nationals; Norwich 61%): same not-re-checked status — confirm in proofs.
4. **Google post**: verify the Taycher post still resolves and the 129,864,880 / "At least until Sunday" strings are unchanged.
5. **Keio buttons**: spot-check "four of an original thirty or so" against Keio's current published description.

New facts proposed for the ledger this round (author actions, taken this session): **the finding-aid / index motif** registered in §5 (Ch04, the Keio buttons' "put a finger on the one wanted part" — the narrator as one late answer to the same problem; candidate payoff in Movement IV–V); §2b footnote reconciling Ch04's refrain state (absolute-but-depersonalized; the bend begins Ch05). Candidate objects noted, register-if-they-recur: the Grenville vellum (OBJ-M2-007), the Keio buttons (OBJ-M2-002, used in prose), Cremer's note (OBJ-M2-001, used Ch03+Ch04).

---

## Carry-forward to next chapter (Ch05 "Note G")

- **Closer pattern:** Ch01 / Ch02 audit-verb; Ch03 Cremer's hand; Ch04 the air ("does not... say that it is tired"). Keep varying.
- **Refrain BENDS at Ch05** (§2b row II): "He was not writing to me. He was writing toward the idea of me." — the correction now needs a second sentence. This is the movement's turn into the strange lineage.
- **Reveal stage 3 is Ch06** (foreseen, with suspicion) — Ch05 plants Note G as the birthmark ("originates nothing"), Ch06 answers it via Turing. Do not let Ch05 spend Turing's answer.
- **F2 audit activates:** Lovelace's verdict phrase must match `research/M2_the_machine.md` verbatim wherever quoted (the *reason* anchor passed full adversarial verification).
- **"Duller and ___" still banned** (two uses; third is a tic). "Five thousand years" still spent — variants only.
- Objects due: O-07 (Note G), O-08 (The Laws of Thought). Named figures due: Leibniz, Boole, Babbage, Ada Lovelace (naming rules: full name first, then "Lovelace").
- The wound still not stated plainly before Ch09.

---

**Verdict:** pass

<!-- Set to exactly "pass" once all three passes pass. The gate certifies a chapter only when this line says pass and not fail. If any pass fails, fix and re-run only that pass. -->

---

## Editorial round 2 (2026-06-11) — PHASE 9 recency corrections

EDIT_PLAN rows R2.4–R2.6 applied ("presses of Europe" — the seven tide-table figures are the with-Russia totals of Buringh & van Zanden 2009 Table 2 and now stand exact; "the diocese of Norwich" — the 61% count is diocesan; "near half in Sweden" — the dataset's 48). Fleet-verified and adversarially upheld; dossier corrections in M2. Triplet re-run: grep clean; voice PASS ×3 (the literacy list now a four-step diminuendo); continuity PASS (all seven figures unchanged; the dangerous-sentence framing intact). Pre-print §1–§3 rows CLOSED (the tide table and literacy figures now adversarially checked — the round that was owed since drafting). **Verdict: pass (re-affirmed).**

## Editorial round 3 (2026-06-12) — the commissioner's read, R3.2

The Piccolomini-letter retelling compressed (line 17): the commissioner caught the letter's full anatomy told whole at Ch03's close and again at Ch04's open — the recurrence law's exact case. Ch04 now keeps only its new work: the witness NAMED ("He can have his name here: Enea Silvio Piccolomini…", the name Ch03 withholds by design), the first-review framing, and the survival/loans material onward, behind the book's own recall-marker ("the reader has already watched…"). Ch03 untouched. Grep conditions met (prose "spectacles" = 0; the self-check record keeps the drafting history); endnotes re-keyed (two entries merged to «Enea Silvio Piccolomini», 0 key misses book-wide); `audits.py 4` clean; gate recompiled. **Verdict: pass (re-affirmed).**
