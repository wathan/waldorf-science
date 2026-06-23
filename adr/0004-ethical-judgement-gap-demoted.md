---
status: accepted
date: 2026-06-23
---

# The "ethical-judgement gap" is demoted: coverage-veto dissolved as a standalone-frame artifact; only a non-binding developmental-pitch question survives

## Context

The meso-design plan and its fork-resolution appendix treated an "ethical-judgement
gap" as a binding criterion in the working group's Session 1 deep-question decision:
Candidate 1 (epistemological) carried it as a *limitation* ("the ethical-judgement
dimension does not arise naturally"), Candidate 2 (stardust) as a *strength*
("closes the ethical-judgement gap directly"), and appendix step 3 made it a
pass/fail test ("if neither, the candidate fails").

Provenance check found the gap is *warranted but mis-statused*:

- The **mode** is group-visible: synthetic/ethical judgement is macro-curriculum
  line 65 and a ratified-framework sub-ability, **E3.4**
  (`grade12-framework-draft-2026-06-17.md:79-81`).
- The **gap-as-veto** is internal: the chain "E3.4 exists → a question that doesn't
  exercise it has a disqualifying gap → Candidate 1 fails" lives only in the
  Claude+user analysis (macro-diagnostic → handoff lines 17/24 → meso-plan). The
  working group never saw or ratified *that*.

Three structural faults followed from the over-statusing:

1. **Self-contradiction.** Appendix step 2 tells the group to name the decision
   criterion freely; step 3 then hardcodes the gap as pass/fail, overriding step 2.
2. **Thumb on the scale.** The gap-test structurally pre-loaded the fork toward
   Candidate 2, the candidate that "closes it directly."
3. **Wrong altitude.** Closing E3.4 is a *grade-level coverage* concern; applying it
   as a *block-level veto* is the exact category error [ADR-0003](0003-session1-deep-question-before-competency-selection.md)
   overturned. The per-block subset rule explicitly permits skipping a competency.

Root cause (user's diagnosis): the gap is a *symptom* of the abandoned standalone
frame — competencies were rewritten treating the pilot as a self-contained unit
with no coverage view, so "this block omits E3.4" looked like a deficit.

## Decision

Two warrants were tangled inside "the gap"; they are separated.

- **(i) Coverage warrant — dissolved.** "E3.4 must be exercised somewhere" is purely
  grade-level. It is **not** a block-level criterion and **not** a fork veto. E3.4
  becomes a *deferred grade-level coverage note* for future arc design.
- **(ii) Developmental-pitch warrant — kept, demoted to non-binding.** Macro line 65
  makes synthetic/ethical the grade-12 judgement mode and analytical/evaluative the
  grade-11 mode. A wholly-epistemological block *may* be asked: is this richly
  grade-12, or grade-11 in pitch? This is a **named, optional question** Kru Fang
  brings from the macro-diagnostic for the group to weigh — not a pass/fail test.
  Softened by the framework's own predominance-not-exclusivity rule: a lower
  judgement mode may legitimately be load-bearing.

Concrete changes: appendix step 3 recast from veto to the non-binding pitch
question; candidate descriptions de-biased to neutral profiles (the gap-based
verdicts removed); E3.4 coverage recorded as deferred. The pitch question lives
**only** in the fork mechanic — candidate descriptions stay neutral (user choice).

This **refines ADR-0003**: the competency gap-test "has teeth / can tip the fork"
claim is corrected — with no grade-arc above the pilot, the gap-test *informs* the
fork and records coverage omissions, but cannot *veto*. Veto power belongs to
grade-level coverage, which does not yet exist.

## Considered alternatives

- **Keep as binding veto** (rejected): smuggles unratified analysis into the group's
  decision as a settled premise; the three faults above.
- **Relabel as Kru Fang's proposal but keep both warrants live** (rejected): the
  coverage warrant (i) is a genuine category error, not merely mis-attributed — it
  must be dissolved, not relabelled.
- **Delete the whole gap, pitch included** (rejected): warrant (ii) is real and has
  group-visible grounding (macro + framework); deleting it would discard a
  legitimate developmental-fit consideration.

## Consequences

- **Plan edits** to `source/meso-design-plan-cosmology-optics-pilot.md`: candidate
  descriptions neutralised; Session 1 gap-test softened to "informs, no veto";
  appendix step 3 → non-binding pitch question; deferred-coverage bullet added;
  appendix step-5 addendum and Session 1 centre-of-gravity de-vetoed.
- **ADR-0003 softened** in place (the "teeth" line) with a pointer here.
- **CONTEXT.md** updated: the deep-question entry no longer says C2 "closes the gap";
  the gap-test term notes no-veto-without-arc and the pitch question.
- **History left intact.** `handoff-…md:17,24` records what was believed then and is
  not rewritten. `adr/0001` ("no new headline for the gap") is unaffected — its
  decision rests on E3.4 already carrying the mode, independent of any veto.
- **Published HTML + TH** (`docs/meso-plan.html`, `CONTEXT.th.md`) regenerated to
  match.
