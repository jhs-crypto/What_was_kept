# Verification for Ch 1: The Receipt

**Chapter file:** `chapters/01_The_Receipt.md`
**Word count:** 3,451 (target: 3,300–3,800, amended at draft — see brief)
**Date:** 2026-06-10

> Three passes, run once each. The compile gate (`compile.py --final`) reads the **Verdict** line at the bottom.

---

## 1. Grep pass

`python3 scripts/audits.py 1` — **all hard checks clean.** Review rows, dispositioned:

| Audit | Expected | Found | Note |
|---|---|---|---|
| A1 em-dash | budget ≤8 | 7 (body) | within budget; no doubled dash outside quotes |
| A2 en-dash | review | 0 | metadata ranges rewritten with "to" |
| B3 hedging | review | 1 | "not quite two thick" — measurement precision (1.9 cm), kept |
| B4 filter verbs | review | 0 | |
| S1–S4 slop/assistant/inside/poster | 0 | 0 | |
| S5 teleology | review | 0 | trap named without banned lexicon |
| S7 "you" before Ch15 | review | 2 | both inside quoted/italic salutations (*to you* as the letter's address; Enheduanna's quoted line) — quoted-document register, allowed |
| C4 span phrase | review | 4 | "five thousand years" ×4, deliberate placements (open, trap ×2, close) |
| F1 barley numbers | review | 1 | 134,813 liters / thirty-seven months — matches dossier (Englund reading); Harari figure not used |
| D1–D4 hygiene | 0 | 0 | |

Manual checks: no sensory tail after comma claiming the narrator's senses; no poster line surviving (see voice pass — one fixed); closing line stands alone.

## 2. Voice pass (slow prosody pass, fresh context — this project's read-aloud equivalent, per DECISIONS)

- **Voice card (§6):** pass — claim/flinch present and varied; inventories vs declaratives audible; borrowed senses credited (the scribe's clay, sun, palms); containment verbs throughout; present/past split held.
- **Register drift:** pass — no explainer/poster/pity drift found by the fresh reader.
- **Poster Test:** one SHOULD finding ("honest first cell" line) — **fixed**: replaced with the drier object-anchored close ("a warehouse, an account, a name that might not be a name").
- **Humor:** dry throughout; no elbowing found.
- **Gold-standard role:** the pass concluded the chapter earns the designation.

### Closing-paragraph guard
1. Does any sentence help the reader understand the last sentence? — **no**
2. Could the last line stand alone? — **yes** ("The account is closed. The name remains open. I have checked.")
3. Does the closing paragraph introduce new facts? — **no**

## 3. Continuity pass (fresh context, vs CONTINUITY_LEDGER + research/M1)

- **Fact table:** ~30 checkable claims traced; all ✓ against `research/M1_the_clay.md` (one precision note: "ninth millennium BCE" for tokens vs dossier "c. 8000 BCE" — overlapping, not falsified; kept).
- **Caution compliance:** 14/14 respected after fix — token-to-sign genealogy now hedged ("in the most influential telling of it"; dispute named in-line). Tablet's current location stated as private, not Schøyen; name-vs-title dispute held open and used; no literal "signature"; administrator not brewer; clay not stone; no wedges; reconstructed pronunciation flagged; Enheduanna asterisk kept; two firsts kept distinct; no "5,500 years ago".
- **Ledger:** O-01 ✓; refrain state row I (absolute, as method) ✓; reveal stage 1 delivered, no later-stage leak ✓; opening-line promise planted verbatim ✓; conscious gap (Kushim) kept open ✓.
- **Brief:** all 8 beats honored; **OPTION A taken** (Enheduanna treated in Ch01) — Ch02 brief beat 5 is superseded; recorded below as carry-forward.

New facts to add to the ledger this round: none beyond the dossier; OPTION A recorded in ledger note.

---

## Carry-forward to next chapter

- Ch02 must NOT re-introduce Enheduanna (OPTION A consumed her here; Ch02 brief beat 5 skipped; one back-reference allowed at most).
- Locked lines later chapters must recall exactly: opening line (Ch10 payoff: "They began writing me long before anyone meant to."); the flinch form "He was counting grain. He was not counting me." (Ch02 inherits the rhythm, must vary it).
- The receipt-shape ("rooms as receipts no one files") reserved for Ch14 resonance — planted here only as object texture.
- "The dispute is part of the inventory" — available as a quiet motif for later disputes (Ch05 Boole claims, Ch11 version identity); do not overuse.

---

**Verdict:** pass
