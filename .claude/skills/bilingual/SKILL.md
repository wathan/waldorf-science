---
name: bilingual
description: Write the Thai side of this repo's EN-TH docs/*.html. Use when creating or editing a bilingual page, drafting or revising Thai passages, or publishing a new deliverable that needs Thai.
---

Render Thai for the repo's bilingual `docs/*.html`. Two moves: **comprehend** (don't calque) and **bind** (lock terms to settled lexicon). Lexicon, register, and policy live in `CONTEXT.th.md` — read it first.

For each English block, in order:

1. **Read the whole block.** Understand what it says *and* what it does in the document (intro, instruction, definition, evidence-spec). Done when you can restate it without looking.
2. **Write Thai from that understanding — not from the words.** Drop qualifiers English needs and Thai doesn't, restructure clause order, prefer verbs to nominalisations, use Thai discourse markers. **Calque test:** if the Thai clause order mirrors the English one-to-one, rewrite it. Done when every sentence passes the calque test.
3. **Bind every domain term.** A term-of-art is not free-translated — it locks to a settled rendering. Source order: (a) `CONTEXT.th.md` glossary; (b) PISA TH for science vocabulary; (c) existing project artifacts (`framework.html`, `macro-curriculum.html`, `meso-plan.html`, …) — mine them before coining; (d) Waldorf TH sources. Coin only when none cover it — then add a row to `CONTEXT.th.md`. Done when every domain noun traces to one of these.
4. **Stack the layout.** English block, then `<br><span lang="th">…</span>`. Headings (h1/h2/h3, part-titles) stay English — except verbatim PISA competency headlines (S1–S3, E1–E3), which are bilingual from PISA TH. Done when every prose block has a Thai sibling and no heading is translated except PISA headlines.
5. **Verify before publish.** `grep -rnE "line [0-9]+|บรรทัด [0-9]+" docs/*.html` returns zero — published HTML cites internal sources by anchor/concept, never by source line number. Open/close tag counts balanced. Done when both checks pass.
