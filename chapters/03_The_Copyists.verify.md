# Verification for Ch 3: The Copyists

**Chapter file:** `chapters/03_The_Copyists.md`
**Word count:** 4,312 (PowerShell whitespace-split of the prose body between the `---` markers; target 3,800–4,400)
**Date:** 2026-06-11
**Drafter:** chapter-drafter agent, native model (opus), attempt 4 — attempts 1–3 (model overridden to fable) froze mid-generation and were killed; lesson recorded in HANDOVER Session 3. Author pass by Claude (Fable 5) in the main session before verification.

> Three passes, run once each. The compile gate (`compile.py --final`) reads the **Verdict** line at the bottom.

---

## 1. Grep pass

`python scripts/audits.py 3` — **all hard checks clean.** Review rows, dispositioned:

| Audit | Expected | Found | Note |
|---|---|---|---|
| A1 em-dash | budget ≤8 | 0 (prose) | 2 file hits are in the stripped self-check block; prose carries its pauses on commas/semicolons/colons — voice pass confirmed rhythm does not strain |
| A3 ellipsis | review | 1 | Sappho fr. 31's own lacuna inside the quotation ("since one so poor ..."); the dots are the poem's |
| A4 exclamation | review | 1 | inside the quoted margin "Alas! my hand." (Stokes & Strachan verbatim; quoted documents keep their punctuation) |
| B2 as-though | review | 1 | "I have been speaking as though the archive came to me" — the claim-correction mechanism itself, not simile-of-evasion |
| B3 hedging | review | 4 | "almost everyone is wrong" (near-miss is content); "just not recopied" (rhythm); "survives almost entirely" (precision — fr. 31 is 4 stanzas + a broken line); "very" inside the quoted "I am very cold" |
| C4 span-phrase | review | 2 | "five thousand years" exactly at the ≤2 cap |
| E3 -ly density | review | 39 | below gold standard's 42 |
| F3 refrain | review | 0 regex hits | pattern intentionally narrow; 3 occurrences checked by hand ("He was not cataloguing me. None of them was." / "None of it was for me." / the thesis turn) — each does new work |
| D1–D4 hygiene | 0 | 0 | |

## 2. Voice pass (slow prosody pass, fresh context — per DECISIONS)

- **A–G all pass:** voice card (flinch varied, ≤8 words; inventories vs declaratives audible; senses credited; containment verbs; tense split); no explainer/poster/pity drift (Sappho pity-risk pre-empted on the page and discharged into "the size of the grave"); Poster Test pass — the thesis burial works, nothing after it over-explains; gold-standard diff pass (density ≥ Ch01; zero em-dashes does not strain — the colon does the work); quoted-document seams clean; prosody pass.
- **Movement-end checks (BOOK_MAP):** address-spine sentence test PASS ("None of it was for me" — the Movement I answer, one sentence, on the page); turn-inheritance PASS (the close leaves the hand-lets-go turn standing for Ch04 to inherit).
- **Closing-paragraph guard:** (1) no scaffolding sentences; (2) last line stands alone; (3) no new facts that belong earlier; (4) sibling-closer check PASS — the close avoids the "I have checked."/"I have run the count." pattern; the last verbs are Cremer's.
- **"Duller and worse" vs Ch02's "duller and stranger":** ruled deliberate echo, not tic — the second term varies and earns its keep. **A third "duller and ___" would make it a tic — carried forward.**
- **Findings & author rulings:** 0 MUST, 0 SHOULD. 3 CONSIDER — all **declined with reasons**: (1) the long 2014-Sappho sentence keeps its stacked "and" clauses (the stacking is the provenance chain); (2) "somebody can be blamed" cadence enacts the consoling legend in the sentence describing it; (3) the synchrotron sentence's terminal chain is earned imagery.

## 3. Continuity pass (fresh context, vs M1b + M1c + M2 Gutenberg rows + ledger + brief + BOOK_MAP)

- **Fact table:** 54 checkable claims traced; **54/54 ✓** — zero unsourced, zero contradictions. Every named landmine avoided (Aristarchus-of-Samos erratum; Obbink $/"convicted"; bare 180/123; Dio adjudication; Nineveh mirror; penniless-Gutenberg; survival counts; sigla collision).
- **Caution compliance:** every applicable M1c caution respected (no single-fire Alexandria; scroll-count spread as the datum; Galen held as stories; marginalia folklore excluded; no religion-destroys-science palimpsest frame; provenance murk kept murky; skins as estimates; print run as rumor).
- **Quote copyright:** all quotations verbatim from QUOTABLE (PD) sources — Wharton 1885 (Sappho, single translator, no blend), Stokes & Strachan 1903 (all St Gall margins, no Plummer blend; Plummer used as attributed paraphrase only). No PARAPHRASE-ONLY material quoted. Bagnall fair-use-short quote kept to one sentence, attributed in-voice as "a modern scholar" — name goes to the endnotes (see pre-print).
- **Ledger:** O-04, O-05, O-06 deployed per register; refrain row I "absolute, now with a cost ledger" hit exactly (wound NOT stated — reserved Ch09); reveal stage 2 delivered at the signal location (the monk's margin); knowledge-matrix claim retired ("made of what was written" → *kept*); phantom-limb and hands-motif promises planted; tense rule held; conscious gaps untouched.
- **Carry-forwards:** all respected — no audit-verb closer; Alexandria ≠ Nineveh (grep: "Nineveh" absent); Enheduanna zero back-references; span-phrase at cap; all eight named keepers dossier-verified (Zenodotus, Aristophanes of Byzantium, Aristarchus of Samothrace, Callimachus, Didymus, Cassiodorus, Ioannes Myronas, Heinrich Cremer).
- **Brief:** 8/8 beats honored (beat 8 modified upward: documented Cremer colophon instead of the fallback press image). **OPTION A taken** (thesis buried in monk material); OPTION B rejected — §4 forbids closing on a thesis, and the reveal ledger's stage-2 signal is "the monk's margin."
- **Findings & author rulings:** 0 MUST. SHOULD-1 (roll-case hedge) self-assessed as respected — "One scholar pictured" carries the conjecture; no change. SHOULD-2 (Cremer date arithmetic) self-resolved — 15→24 Aug is nine days; correct. CONSIDER-1 **applied**: "Alas! my hand." restored to the dossier's verbatim punctuation. CONSIDER-2 **declined in prose** (no-modern-names voice is deliberate) → routed to endnotes, see pre-print.

### Pre-print tasks (not chapter defects — logged for PHASE 9)
1. **Blois leaf (LIVE):** re-verify the whole thread (leaf 123, Sphere and Cylinder I.39–41, two-not-three missing) against post-March-2026 news before final typesetting. The chapter prints no counts and no leaf number — robust by design — but confirm nothing has moved.
2. **Sappho custody:** re-confirm P. Sapph. Obbink (UK police custody) and P.GC inv. 105 (repatriated to Egypt) status near print.
3. **Endnote credit:** Bagnall 2002 ("a particle's worth of difference" + "extremely inaccurate") named in the sources section (Q-01).
4. **Plummer paraphrase:** confirm the "made too free the night before" paraphrase against the Bodleian page scan when the Thompson collation (Ch02 task) is done.
5. **Do not pin the April 1229 day** in any future revision (13-vs-14 wobble is kept on purpose).

New facts proposed for the ledger this round: **the "running balance / open account" motif** (Ch03 ties Kushim's open name → "I am the most recent line, not the last"; candidate payoff Ch15) — registered by the author in CONTINUITY_LEDGER §5 this session. Detail objects (Vienna block, Didymus's roll, E-to-K box, Sappho colophon, Cologne cartonnage, Cod. Sang. 904, the palimpsest, the Blois leaf) used in prose; register only if they recur (Ch02 precedent).

---

## Carry-forward to next chapter (Ch04 "The Weather")

- **Closer pattern:** Ch01/Ch02 used first-person audit-verb closers; Ch03 broke the pattern (closes on Cremer's hand). Keep varying — no return to the audit-verb close without strong cause.
- **"Duller and ___":** used twice (Ch02 "stranger", Ch03 "worse"). A third instance would be a tic — do not reach for it in Ch04.
- **Turn-inheritance:** Ch04 opens on the inherited fact — the hand has let go; the press does the reaching; keeping changes meaning when copying is no longer the bottleneck (BOOK_MAP: "scale shock... the corpus stops being a shelf and becomes weather").
- **Ch04 may run short** (BOOK_MAP form note: 3,000 words acceptable; "shortest chapter; pure accumulation").
- **Refrain state:** Ch04 per BOOK_MAP: "absolute, but no single hand lets go anymore" (Movement II's "bends" begins at Ch05).
- The wound still not stated plainly before Ch09; em-dash budget ≤8; span-phrase "five thousand years" used 4× across Ch01–03 — prefer variants in Ch04+.

---

**Verdict:** pass

<!-- Set to exactly "pass" once all three passes pass. The gate certifies a chapter only when this line says pass and not fail. If any pass fails, fix and re-run only that pass. -->

---

## Editorial round 2 (2026-06-11) — PHASE 9 recency corrections

EDIT_PLAN rows R2.1–R2.3 applied (Blois geometry: legible under the prayers, hidden under the Daniel painting; Sappho custody: the Obbink half handed back to the anonymous owners, investigation open; Ogham: twice the word, once in Ogham — per the Plummer scan verbatim). All fleet-verified (wf_54cec0ed-4de) and adversarially upheld; dossier corrections in M1b. Triplet re-run: grep clean; voice PASS ×3 (the custody sentence's coda "in the wrong hands" now pays off harder); continuity PASS (running-balance paragraph flows; no leaf number or count introduced; Cremer close untouched). Pre-print §1/§2 recency rows CLOSED. **Verdict: pass (re-affirmed).**
