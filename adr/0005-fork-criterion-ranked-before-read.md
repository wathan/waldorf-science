---
status: accepted
date: 2026-06-24
---

# The fork criterion is *ranked before the candidates are read*: a silent, sealed, pre-ranked menu replaces "name the criterion after the silent read"

## Context

The Session 1 fork-resolution mechanic (meso-design plan §Appendix) is built to stop
the most consequential meso decision being made "by drift or by the most articulate
voice in the room." Its prior ordering was:

1. Side-by-side review — **group reads both candidates silently first.**
2. Name the criterion (the prose said "before the question is *chosen* — not after").
3. Developmental-pitch question (non-binding).
4. Cross-system test.
5. Record the decision with its criterion.

So the criterion was named **after** the analytic page was read and **before** the
question was chosen. That ordering leaves the mechanic's own target failure mode open:
having read both candidates' profiles, the group can quietly favour one and then select
the criterion that makes it win — a **motivated criterion**, reverse-engineered to
justify a pre-formed preference. This is the same disease as articulate-voice capture,
one step upstream.

## Decision

The criterion is **established before the candidates' analytic page is read**, not after.
Concretely, the act is restructured along four resolved choices:

1. **Target the motivated criterion, not the vacuous one.** The primary enemy is a
   criterion reverse-engineered to fit a pre-formed favourite. The opposite risk — naming
   a criterion in a vacuum that fails to discriminate the candidates — is real but cheaper
   (it is recoverable; a candidate you have fallen for is not).

2. **"Before" means *hard*: criterion anchored to external debt, not to the candidates.**
   The criterion answers *"which proof does this pilot most owe the macro-curriculum?"* —
   answerable with zero candidate detail. The candidates' bare themes being known going in
   is tolerable because the criterion anchors to an external need, not to the comparison.

3. **Fixed, pre-published menu — and pre-*ranked*, not single-pick.** The three proofs
   (a) distinctive new pedagogy, (b) full grade-12 fit incl. ethical-synthetic judgement,
   (c) continuity-with-improvement) are the *only* admissible criteria, published ahead of
   Session 1. The group **ranks all three** (1st/2nd/3rd). The lock is irrevocable once the
   page is opened; the read may only *score* candidates against the locked ranking, never
   re-open it. A tie on the top criterion falls **lexicographically** to the next — itself
   candidate-blind, so no reopening.

4. **Group ranks live, silently, then aggregates — friction, not blindness.** The people
   who built the candidates cannot be blinded to the theme↔criterion correspondence; perfect
   blindness is impossible. The protection is therefore (i) **silent individual ranking**,
   revealed simultaneously and aggregated (the doc already trusts silence-before-speech for
   the read; the rank is now the higher-stakes act), (ii) the ranking **recorded before the
   columns are opened** so any reversal is visible, (iii) **lexicographic** application so it
   cannot be quietly re-weighted mid-decision, and (iv) step-5 recording of the governing
   criterion so the decision is auditable after the fact. A split ranking is itself signal —
   the group disagrees on what the pilot owes — and is recorded as such.

The analytic side-by-side (`session1-deep-question-review.md`) splits into two layers:
a **rank-safe layer** (the three-proof menu + the two bare candidate themes), already
delivered to the group as a brief introduction in the prior session, and a **scoring
layer** (competency-profiles, macro-fit, what-each-closes), which stays **sealed until the
ranking is recorded** and is opened only in Session 1. The page's old instruction —
"read both columns silently first" — inverts: **rank first (scoring layer sealed), then
open the columns.**

## Considered alternatives

- **Keep "name criterion after the silent read"** (rejected): leaves the motivated-criterion
  door open — the exact capture the mechanic exists to stop.
- **Soft "before": criterion named before the page but candidates fully in view** (rejected):
  candidate-blindness becomes theatre if the criterion is judged against the specific two.
  Anchoring to external debt is what makes "before" load-bearing.
- **Single-pick criterion, live tiebreak on a tie** (rejected): a tie forces the group back
  into the room to name a tiebreak, reopening the motivated-criterion door. Pre-ranking
  keeps the tiebreak candidate-blind.
- **Author pre-ranks in the doc ahead of session** (rejected): buys auditable pre-commitment
  but reintroduces the single-articulate-voice problem one level up and strips the group of a
  mission judgment that is legitimately theirs.
- **Open-consensus ranking** (rejected): the articulate voice captures the ranking instead of
  the question — same disease relocated.

## Consequences

- **Refines ADR-0003 and ADR-0004.** ADR-0003 established A-from-B (criterion before the
  question is *chosen*); this sharpens "before" to *before the candidates are read* and makes
  the criterion a ranked, sealed menu. ADR-0004's non-binding developmental-pitch and
  no-veto gap-test are unchanged — they still *inform* (never re-rank) and sit after the read.
- **Mechanic edits** to `source/meso-design-plan-cosmology-optics-pilot.md` §Appendix:
  steps reordered to rank-first (silent, sealed, recorded) → open & read → score
  lexicographically → pitch → cross-system → record.
- **`session1-deep-question-review.md` edits**: header no longer a pre-circulated full "input
  paper"; the scoring layer is opened in-session after the ranking; "read silently first"
  replaced by "rank first, then read."
- **CONTEXT.md** gains the *fork criterion ranking* term and the rank-before-read rule.
- **Published HTML + TH** (`docs/meso-plan.html`, `docs/session1-deep-question-review.html`,
  `CONTEXT.th.md`) to be regenerated to match — deferred to the bilingual publish step.
