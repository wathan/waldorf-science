---
status: accepted
date: 2026-06-23
---

# Session 1 sequences the deep question (B) before competency selection (A); competency-reasoning is the hinge, not the opener

## Context

The Jun 24 meso-design protocol (`source/meso-design-plan-cosmology-optics-pilot.md`)
originally had Session 1 decide **A (block competency selection)** first, then
**B (deep question)**, justified by "A first narrows the deep-question viability."

That order railroads. The pilot block is not built from the ground up — it builds
on prior blocks, and the pilot teachers already hold candidate driving questions.
A competency-selection pass run *before* the question is therefore reverse-justified
theatre: it looks like a free choice but is not, which trains teachers to *perform*
the framework rather than use it — directly corrupting the protocol's stated
meta-goal of being a repeatable design method teachers can apply to the whole
future curriculum.

Diagnosis (two altitudes):

- **Grade level (4 blocks).** The design object is a coherent *question-arc*; the
  four questions are the generative act. Competency **coverage** is a constraint on
  the *union* of the four blocks (a checklist), not a per-block opener.
- **Block level (one block).** A block exercises a *subset*; full coverage is
  explicitly not a per-block goal (`CONTEXT.md`). Competency selection is mostly
  *entailed* by the question plus whatever coverage gap the grade level pushes down.

At **both** altitudes competency-reasoning is the **constraint/test**, never the
generative first move. The original A-first order was a **category error**: it
applied whole-grade coverage logic as a single block's opening move.

The pilot is the *first* block, with no grade-arc above it yet (framework built
Jun 17). It can honestly demonstrate only the block-level method.

## Decision

Session 1 runs **B then A** as a hinge sequence:

1. **Surface** the question candidates openly (they pre-exist).
2. **Competency gap-test** each candidate against the framework map — what it
   entails, and what it *omits*. (Refined by [ADR-0004](0004-ethical-judgement-gap-demoted.md):
   with no grade-arc above this pilot, the gap-test *informs* the fork and records
   omissions as deferred grade-level coverage notes — it does **not** veto a
   candidate. The earlier "has teeth / can tip the fork" framing borrowed its force
   from the dissolved ethical-judgement gap.)
3. **Decide B** via the fork-resolution mechanic.
4. **Finalise A** from B: the entailed subset plus deliberate gap-test-driven
   additions.

Competency-reasoning is the **hinge** the question must survive, not the opener and
not a post-hoc rubber stamp. The competency map is brought as a *gap-test scaffold*,
not a pre-selected shortlist to ratify.

A **two-altitudes framing note** is added to the plan: the pilot models the
block-level method honestly; the grade-level question-arc-first / coverage-checked
method is *named and seeded* for future whole-curriculum design but not demonstrated
by one block.

## Considered alternatives

- **Keep A-first** (rejected): the category error above; manufactures a fake free
  choice and trains ritual framework-performance, the worst outcome for the
  learning-opportunity goal.
- **Strict flip to B→A with no hinge** (rejected): moves the theatre, doesn't
  remove it. Whichever output comes second with no teeth becomes a rubber stamp;
  a bare B→A makes A a reverse-derived justification of the question. The fix is
  teeth (the gap-test), not order alone.
- **Sketch a hypothetical 4-question grade arc inside the pilot** so teachers see
  the altitude above (deferred): scope creep, and a fabricated arc could mislead.
  The framing note names the grade-level method without faking an instance of it.

## Consequences

- **Plan edits** to `source/meso-design-plan-cosmology-optics-pilot.md`: new
  "Two altitudes" section; Session 1 rewritten as the hinge sequence; schedule row
  1 now "B then A"; output-A description, originator table, document-structure TOC,
  and fork-resolution appendix all updated to "A finalised from B."
- **Published HTML stale.** `docs/meso-plan.html` and the TH mirror
  (`CONTEXT.th.md` glossary terms) must be regenerated to match. Not done in this
  change.
- **Glossary additions** to `CONTEXT.md`: *two-altitude design model*,
  *competency gap-test (the hinge)*, *question-arc (grade level)*.
- **Binds future grade-level work.** When the real 4-block arc is designed, the
  method is already named: question-arc generative, competency-coverage as the
  union constraint.
