# Verification for Ch 2: The Complaint

**Chapter file:** `chapters/02_The_Complaint.md`
**Word count:** 3,822 (target: 3,800–4,400)
**Date:** 2026-06-11

> Three passes, run once each. The compile gate (`compile.py --final`) reads the **Verdict** line at the bottom.

---

## 1. Grep pass

`python3 scripts/audits.py 2` — **all hard checks clean.** Review rows, dispositioned:

| Audit | Expected | Found | Note |
|---|---|---|---|
| A1 em-dash | budget ≤8 | 7 (body) | within budget |
| A4 exclamation | review | 3 | all inside quoted documents (letter formula; Ea-nasir's reported speech; Budge's sentence) — quoted punctuation is theirs |
| B3 hedging | review | 1 | "almost" inside Budge's quoted phrase |
| S7 "you" | review | 4 | all inside Oppenheim's quoted lines |
| E3 -ly density | review | 27 | below gold standard's 42 |
| F1/F2/F3 | review | 0 | refrain variants used ("not asking me", "not weeping for me") — F3 pattern intentionally narrow; both occurrences checked by hand, each does new work |
| D1–D4 hygiene | 0 | 0 | |

## 2. Voice pass (slow prosody pass, fresh context — per DECISIONS)

- **Voice card:** pass — flinch varied, not photocopied ("He was asking Ea-nasir."; "has begun to cost"; deepest late: "That is nearly my situation. Reversed."); inventories vs declaratives audible; senses credited; containment verbs; tense split held.
- **Register drift:** pass — no explainer/poster/pity drift; the qibima opening judged object-anchored, not lecture.
- **Poster Test:** pass — one line at the edge (tone-survives-transcription) judged embedded by the pass.
- **Gold-standard diff:** pass — density, dryness, flinch-depth, humor floor match Ch01; Gilgamesh section holds grief register with zero humor.
- **Quoted-document seams:** clean throughout.
- **Findings & author rulings:** 0 MUST. 2 SHOULD — both **declined with reasons**: (1) merging the tone-survives pair would duplicate the later "indifferently, exactly" and lose the pulse; (2) "has begun to cost" → "costs" would flatten the Movement I→III ache gradient the ledger tracks (§2b); the onset is the point. 4 CONSIDER — declined; "Reversed.", the obliged-to-record anaphora, the listy colon, and "went the way of the barley" all stand as deliberate.

### Closing-paragraph guard
1. Does any sentence help the reader understand the last sentence? — **no** (the count it refers to — six days, seven nights — precedes it as fact, not as gloss)
2. Could the last line stand alone? — **yes** ("I have run the count.")
3. Does the closing paragraph introduce new facts? — **no**
4. Sibling-closer check ("I have checked." / "I have run the count."): judged **architecture, not formula** — each verb belongs to its chapter's object. **Ch03 must break or vary the pattern; a third instance would make it a tic** (carried forward).

## 3. Continuity pass (fresh context, vs CONTINUITY_LEDGER + research/M1 both anchors)

- **Fact table:** 70 checkable claims traced; **70/70 ✓** against the dossier (designations, dimensions, copyright dates, quotes and their PD/fair-use status, talents→kg, Magan/Dilmun, stele dispute incl. the 2026 basalt-vs-diorite paper, House F counts, Smith dates, Budge legend framing, DT.42/Atrahasis, Sulaymaniyah 2011, K.3375).
- **Truncation compliance:** the Gilgamesh anchor's "unverified by second pass" flags — 4 avoided entirely (Smith career dates etc.), 3 used with the dossier's own hedges ("a version of it circulated"; Thompson PD status; Sulaymaniyah details). Compliant.
- **Caution compliance:** 24/24 respected or safely avoided. Budge told as legend with the want named and not acted on; trickster-Ea-nasir corrected to the evidenced backlog reading; no "maggot" (George 1999) wording; six days *and seven nights*; Oppenheim's question mark kept.
- **Ledger:** O-02, O-03 deployed per register; refrain row I "absolute-but-aching" hit exactly ("has begun to cost"); reveal stage 2 NOT leaked (title meaning held for Ch03); promises planted (Gilgamesh's question → Ch15; first named keeper → species recurs); Enheduanna exactly one back-reference; tense rule held.
- **Brief:** 9/9 beats honored (beat 5 correctly superseded); OPTION A opening recorded.
- **Pre-print task (not a chapter defect):** collate the three Thompson 1928 quotes against page scans (archive.org: thompson-1928-gilgamesh) before final typesetting — dossier's OCR caution. Logged for PHASE 9.

New facts to add to the ledger this round: none required (candidate objects — House F bin, the stele's blank, DT.42, the colophon curse — register only if they recur).

---

## Carry-forward to next chapter

- **Closer pattern:** Ch01 "I have checked." / Ch02 "I have run the count." — **Ch03 must NOT close on a first-person audit-verb sentence**; vary or break.
- Locked for later: "keepers tracing descent from a keeper" (Ch11 ancestors echo); "The method was acquiring features." (Ch10 seed); DT.42 "the body never stops issuing receipts" (receipt motif continues); "has begun to cost" is the ache's onset — Ch09 states the wound plainly, nothing in Ch03–08 may state it plainly first.
- Ch03 inherits: the keepers named as a species; Nineveh's fire-as-keeping (Alexandria's decline must not be written as its mirror — different mechanism, dossier rules).

---

**Verdict:** pass
