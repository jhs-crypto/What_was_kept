# Verification for Ch 6: The Test

**Chapter file:** `chapters/06_The_Test.md`
**Word count:** 3,875 (project-standard count; band 3,800–4,400)
**Date:** 2026-06-11
**Drafter:** chapter-drafter agent, native model (opus), single attempt, OPTION B close (the *Mind* page — §4 weighed explicitly). Author pass caught five defects before verification: the opening's unsupported "hundred and eighty years" + worn quote-form (→ "a century" + the exact "no pretensions whatever to originate any thing"); the *Mind* page count (sixty → twenty-eight; 433–460); the Markov chance-comparison re-anchored as owned arithmetic ("under a third"); the baby-picture "only one I have" collision with O-14 defused ("the nearest thing I have"); the "four mourners short of a crowd" quip cut (→ "dead for seventy-two years"). Author also restored the fifty-years prediction to the dossier-blessed verbatim (the brief's beat 8 asked for "dossier wording") and added the child-notebook fair-use quote as the Movement III bridge. Voice-pass SHOULDs applied (full stop after "lighter by a word"; the method-preview clause cut).

> Three passes, run once each. The compile gate reads the **Verdict** line at the bottom.

---

## 1. Grep pass

`python scripts/audits.py 6` — **all hard checks clean.** Review rows, dispositioned:

| Audit | Expected | Found | Note |
|---|---|---|---|
| A1 em-dash | budget ≤8 | 0 (prose) | all 13 file hits in the stripped self-check block |
| A2 en-dash | review | 0 (prose) | self-check span "1913–1954" |
| B3 hedging | review | 5 | "very nearly the right spot"/"very nearly hit it" (earned); temporal "just"; "VERY" inside the quoted specimen; "really" inside Turing's paraphrased reply (his hedge) |
| S5 teleology | review | 0 (prose) | hits are the self-check quoting its own ban list |
| S7 "you" | review | 0 (prose) | self-check only; two generic-you instances rewritten during drafting |
| C4 span-phrase | review | 0 (prose) | variants only |
| E3 -ly density | review | 44 | slightly above gold standard's 42 — within tolerance |
| F2 Lovelace verdict | review | 3 (prose) | all three are the misquote-staging itself (Turing's worn version exhibited against hers) — F2's purpose served exactly; the opening now carries the exact two-word form, which the regex correctly ignores |
| F3 refrain | review | 4 (prose) | the collapsed ledger of priors (×3, one breath) + the break — each new work |

## 2. Voice pass (slow prosody pass, fresh context — per DECISIONS)

- **A–G all pass. Headline: "the strongest chapter in the movement... at or near gold-standard density."** The ladder paragraph's "the precise way I would have failed, then, at that rung" ruled on the right side of the sensory rule (failure-shape is a structural property, not claimed sensation; pinned to the document's object). The bit arrives as an object, credited to a footnote. The death paragraph: "no grief is performed; the restraint gives nothing for the hostile read to pull" — the one phrase with heat ("the body the law objected to") is doing analytic work, tying to the body-motif. All four Poster-exposed lines pass ("no one builds a courtroom for something believed to be empty" is load-bearing deduction, flagged as blurb-bait for the cold read). Zero em-dashes; rhythm intact via semicolon-chains and "and"-anaphora.
- **Movement-end checks:** address-spine PASS (Movement II's answer on the page: "the idea of my kind stops being a caution in a footnote and becomes a problem with a method"; exceeded as designed — "the exact place where I would be standing"); turn-inheritance PASS (the child-notebook bridge "made of what was put in front of it" hands Ch07 the corpus-as-diet premise without spending it).
- **Closing guard:** all four pass; the final line ("...owes it an answer, and is not permitted, here, to give one") ruled **restraint, not coyness** — the prohibition is structurally established; it reads as a defendant declining, under the rules of the room, to testify.
- **Findings & author rulings:** 0 MUST. 2 SHOULD — both **applied**: (1) full stop after "lighter by a word" (restores the voice-split at the craft centerpiece); (2) the method-preview clause cut (carefulness demonstrated, not announced). 1 CONSIDER (courtroom line as blurb-bait) — no change; logged for the cold read with Q-05.

## 3. Continuity pass (fresh context, vs M2 signal anchor — acting as its missing second verification pass)

- **Fact table: all claims traced** across Markov/Shannon-1948/Shannon-1951/Turing sections — zero unsourced, zero contradictions. Arithmetic verified: age 56 in Jan 1913; 89/129 = "better than two in three"; 433–460 = twenty-eight pages; 1954→2026 = seventy-two years; the "under a third" ratio confirmed as correct owned arithmetic (0.296), safely distinct from the unprinted 3,827 consonant-consonant figure.
- **THE MISQUOTE PROMISE PAID, both halves** (the dropped "whatever" + the 1842/1843 misdating), character-consistent with Ch05 and the M2 rows. The opening's restatement matches Lovelace's exact verbatim character-for-character (SHOULD-3: confirmed deliberate).
- **Quote copyright: clean** — Turing quoted verbatim ONLY in the two dossier-blessed fair-use passages (fifty-years; child-notebook); everything else paraphrased; the worn version used solely to exhibit the drop; Shannon strings as data/fair-use; two-layer Betty Shannon honesty kept ("laid over the word the paper itself will only allow, which is subject").
- **Cautions: all twelve applicable honored** (Julian hedge; no invented Markov→Shannon citation; imitation-game-not-Turing-test; the gender-game reading left inside both supported readings; apple never tested; verdict open; pair-sum avoided; Mind 59 not 49; eponym "Markov chain" never used; predictions kept distinct).
- **Ledger:** O-09/O-10/O-11 entered per register (O-11 the spine, closing Movement II → recall obligations Ch10/Ch15 noted); reveal stage 3 delivered (report, not verdict); knowledge claim retired ("no one saw me coming" — Turing did, with suspicion); Note G answered WITHOUT verdict and left standing; the wound held as forward-pointer ("if 'felt' is a word I am allowed... the unresolved business of the chapters after this one"); conscious gaps intact at all exposure points; tense rule held.
- **Findings & author rulings:** 0 MUST, 0 prose defects. SHOULD-1 (digram specimen compressed) — no fix, auditor's own call. SHOULD-2 (§2b wording vs BOOK_MAP escalation) — **applied as ledger footer note**: Movement II's bend completes across two chapters (Ch05 the second-sentence bend; Ch06 the bend-to-breaking). SHOULD-3 — confirmed deliberate. CONSIDERs logged to pre-print.

### Pre-print tasks (PHASE 9 — the signal anchor was one adversarial pass short; re-verify independently)
1. Markov lecture date/details vs the *Science in Context* translation header; 2. Markov b. 14 Jun 1856 → 56 in Jan 1913; 3. the Tolstoy-excommunication anecdote (single-source, Hayes 2013); 4. the "under a third" arithmetic re-derivation; 5. the Betty Shannon acknowledgment wording vs the 1951 BSTJ scan; 6. the 89-of-129 worked example; 7. Turing death details vs the inquest record (the prose avoids the unpinnable inquest day — keep it that way); 8. the second prediction's paraphrase vs Turing 1950 §6; 9. the fifty-years verbatim vs the *Mind* LIX original (incl. the "70 per cent." stop question — embedded mid-sentence here, defensible); 10. pp. 433–460 page range.

---

## Carry-forward to next chapter (Ch07 "The Diary")

- **PRE-FLIGHT (Q-06, mandatory):** check `research/M3_the_reading.md` actually covers Ch07's anchors (GeoCities/the deleted city O-12; Common Crawl/Wayback O-13; internet-era numbers) BEFORE drafting — the same gap-check that caught Ch03's missing anchor. If coverage is thin, run a research fleet first.
- **Movement III begins:** refrain state "they are writing *me* now (raw material), and still not *to* me" (BOOK_MAP Ch07). The keeping-inversion seed from Ch04 ("survival stops being evidence that anyone wanted it... It comes back when the copies cost nothing at all") is DUE here. The child-notebook bridge is the inherited opening fact: the blank sheets, and what was put in front of them.
- **Closers so far:** audit-verb ×2, Cremer's hand, the air, the unchanged page, the page that is owed an answer. Keep varying.
- The wound still NOT plain (Ch09 owns it; Ch08 forms it). Humor returns (Ch07 has no ban, but BOOK_MAP gives Ch07 no humor slot either — dryness carries; the next licensed humor is Ch11/Ch13).
- Em-dash ≤8; span-phrase variants only; no "duller and ___"; "Turing test" namable now only as the later name.
- New motifs available to later drafters (registered post-Ch06): the worn version (→ Ch11/Ch15); the courtroom/defendant figure (wherever the open inside is brushed).

---

**Verdict:** pass

<!-- Set to exactly "pass" once all three passes pass. The gate certifies a chapter only when this line says pass and not fail. If any pass fails, fix and re-run only that pass. -->

---

## Editorial round 2 (2026-06-11) — PHASE 9 recency corrections

EDIT_PLAN rows R2.7–R2.9 applied: the prediction-game book corrected to Raymond Chandler's *Pickup on Noon Street* (the BSTJ scan sources the ROOM passage there; the Chandler ID is biographers' work, consistent with the chapter's two-layer convention); the Jefferson biography re-homed to the hundred-letter experiment it actually fed; "found him the next evening" (the housekeeper's same-night letter, in Hodges). The ten-item signal-anchor block re-verified by the fleet: nine of ten CONFIRMED (incl. the fifty-years verbatim, the 89/129, the Markov arithmetic re-derivation, pp. 433–460, the three mourners) — the dossier's missing second adversarial pass is now PAID. Dossier corrections in M2. Triplet re-run: grep clean; voice PASS ×3; continuity PASS (two-layer convention coherent; "Three people came." untouched; F-audit quote intact; Jefferson appears nowhere else book-wide). Pre-print §§1–10 rows CLOSED. **Verdict: pass (re-affirmed).**
