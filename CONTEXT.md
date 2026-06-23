# Waldorf Science Curriculum Reform

Meso-level science curriculum reform for a Waldorf upper school (grades 9–12),
adding a student-facing question-thread and a shared competency framework on top
of an existing Waldorf curriculum. Anchored externally to PISA 2025 for eventual
university-credit legibility.

## Language

### Curriculum levels

**Macro level**:
Age-sensitive developmental themes (relational shift, epistemic stance,
potentiality modes) with no specific content. Bransby & Rawson's term.
_Avoid_: high level, overarching curriculum.

**Meso level**:
Where a school selects specific content, topics, methods, *and competency
frameworks* as one possible answer to macro-level developmental questions.
The Grade 12 competency framework lives here.
_Avoid_: school curriculum, content layer.

**Micro level**:
Individual teacher's lesson-by-lesson planning. The pilot teachers' post-Aug-17
work is micro level.
_Avoid_: lesson plan layer.

### Competency framework

**Grade 12 competency framework**:
A meso-level adaptation of PISA 2025's six competencies (S1–S3 science, E1–E3
environmental science) for the Grade 12 developmental stage. Preserves PISA's
six headline competencies verbatim; rewrites sub-abilities under each to match
Grade-12 modes from [Macro-curriculum](./waldorf-upper-school-macro-curriculum.md).
_Avoid_: PISA competencies (those are the age-15 source), Grade 12 standards,
Grade 12 assessment rubric.

**Headline competency**:
One of PISA 2025's six top-level competency statements (S1, S2, S3, E1, E2, E3).
Preserved verbatim in the Grade 12 framework.
_Avoid_: top-level competency, main competency.

**Sub-ability**:
A bulleted capability under a headline competency. PISA defines these calibrated
to age 15; the Grade 12 framework may add, remove, or rewrite them for
developmental fit. Written as named capacities in Grade-12 mode — recognisable
to teachers and (paraphrased) to students. Each carries an *operationalisation*
(see below). Not rubric-formatted.
_Avoid_: sub-competency, sub-skill, indicator.

**Operationalisation**:
A brief statement, paired with each sub-ability, specifying what authentic
in-classroom evidence would demonstrate the ability. Supports the block-design
menu use (teachers know what they're designing toward). Distinct from a
graduation rubric — no scoring criteria, just evidence-shape. Rendered in the
rewrite-draft HTML as the *Evidence-shape · การกำหนดเชิงปฏิบัติ* line.
_Avoid_: rubric, performance criterion, success indicator.

**Description / operationalisation division**:
The ability *description* carries the macro developmental mode (what the
student does, in grade-12 mode); the *operationalisation* carries the
assessment *locus* (where evidence is gathered — e.g. classroom/seminar). The
two are not mixed: locus does not belong in the statement. See
[ADR-0002](./adr/0002-action-ethics-subabilities-in-community-position-taking.md).
For action/ethics sub-abilities this means the statement says "a considered
position within *a community*" (macro-faithful), and the classroom bound lives
only in the operationalisation.
_Avoid_: putting "class/seminar" or evidence locus into the ability statement.

**Worked-exemplar competencies (S1, E3)**:
S1 and E3 were drafted first, in full — grade-12 statements *plus*
operationalisations — to model the pattern for the working group. The other
four competencies (S2, S3, E1, E2) carry rewritten statements but no
operationalisation yet (deferred per schedule). The S1/E3 evidence-shapes are
kept and marked as worked examples so the asymmetry reads as deliberate, not
unfinished.
_Avoid_: treating the missing S2/S3/E1/E2 operationalisations as incomplete
drafting rather than a deferred phase.

**Framework purpose ordering**:
Primary use = *shared spine* making blocks legible as one developmental project
(including retrospectively to students). Operational use = *block-design menu*
teachers select from. Deferred = graduation-assessment criteria and
credit-recognition mapping.

**Grade-12 mode (predominance, not exclusivity)**:
Synthetic and ethical judgement is the *predominant* developmental challenge at
grade 12, but earlier modes (descriptive, relational, analytical) remain in use
and may legitimately be strengthened here. A Grade-12 sub-ability sits at
whichever mode the competency genuinely requires; forcing synthetic mode where
a lower mode is load-bearing is wrong (cf. macro-curriculum lines 269–271).

### Pilot

**Pilot block**:
The Grade 12 Cosmology + Optics combined block starting 2026-08-17. Tests
cross-system capstone-question integration; not a template for ordinary
single-system blocks. A block exercises a *subset* of the framework's
competencies and sub-abilities — full coverage is not required per block.
_Avoid_: combined block, cross-disciplinary block.

**Block deep question**:
The single guiding question a pilot block organises around. Two drafts under
working-group consideration: epistemological-capstone ("what does light let us
know and keep us from knowing", S-leaning) vs stardust/self↔Earth (E-leaning,
matches school's prior cosmology teaching). Decision deferred to working-group
session post-Jun-17. The two are weighed on neutral profiles plus the group's own
named criterion — *not* on the old "ethical-judgement gap," dissolved as a
block-level criterion per [ADR-0004](./adr/0004-ethical-judgement-gap-demoted.md).
Three tiers, do not conflate: *illustrative phrasing* (one provisional sentence
per candidate, carried in the Session-1 input drafts) ≠ *final wording* (fixed at
the moment of decision; may be a hybrid) ≠ *student-facing register* (how a
grade-12 student hears it; deferred until phase structure C and capstone E exist).
_Avoid_: capstone question, central question, theme; framing C2 as "closing a gap"
C1 leaves open (that verdict is dissolved).

### Meso-design

**Meso-design outputs (the seven)**:
The artefacts meso-design must produce before pilot teachers can begin
micro-design. (A) Block-level competency selection — subset of framework
exercised by the block. (B) Deep question. (C) Phase structure. (D) Bridge
questions for the secondary teacher. (E) Capstone artifact. (F) Teacher
coordination protocol. (G) Block-level operationalisations for the selected
sub-abilities.
_Avoid_: block plan, block design (use these as informal references; the formal
artefact set is "the seven").

**Two-altitude design model**:
Curriculum design runs at two altitudes; competency-reasoning is the *constraint*
at both, never the generative first move. *Grade level* (4 blocks): the question-arc
is the generative act, competency *coverage* is the constraint on the union of the
four blocks. *Block level* (one block): the question is inherited/chosen, the
competency subset is mostly entailed by it. Choosing block competencies before the
block question is a category error (whole-grade coverage logic applied as one
block's opener) — the railroading source fixed in
[ADR-0003](./adr/0003-session1-deep-question-before-competency-selection.md).
_Avoid_: "competencies first" stated flatly (true of coverage at grade level,
false as a per-block opener).

**Competency lean source (content-native vs theme-carried)**:
A competency is *exercised through* content — it is never "part of" or "absent
from" a discipline (that phrasing is a category error). A deep-question
candidate's competency lean has a *source*: **content-native** — the
discipline's own content exercises it (optics content surfaces the
S/epistemic competencies because light is itself the object of knowing —
Optics-map caveat); or **theme-carried** — the question's framing/orientation
exercises it where the discipline supplies no native content hook (Candidate 2's
stardust theme reaching E1/E2/E3, since cosmology/optics hold no
environmental-science content). Neither is a defect: per the two-altitude model
the question generates and content carries whatever competencies it organises,
and E3 is dispositional by PISA intent. On the Session-1 review page the
distinction is recorded only *implicitly* (the "through the material-science"
qualifier sits on S1/S2, not on the E's) and must stay *symmetric* — stating it
as a one-sided C2 cost ("E-competencies not part of the discipline") would
reintroduce the thumb-on-scale [ADR-0004](./adr/0004-ethical-judgement-gap-demoted.md)
removed, polarity flipped.
_Avoid_: saying a competency is "part of / not part of" a discipline;
framing C2's theme-carried E-lean as a block-level cost (mirror of the dissolved
gap-verdict).

**Competency gap-test (the hinge)**:
The Session-1 step where each deep-question candidate is tested against the
framework map — what profile it entails, and what it *omits*. With no grade-arc
above the pilot it *informs* the fork and records omissions as deferred
grade-level coverage notes; it does **not** veto a candidate (veto power belongs to
grade-level coverage, which does not yet exist — [ADR-0004](./adr/0004-ethical-judgement-gap-demoted.md)).
Block competency selection (A) is still finalised *from* the resolved question (B),
not chosen ahead of it. The one optional consideration it may raise is the
*developmental-pitch question* (below).
_Avoid_: treating A as a free pre-question choice, or as a post-hoc rubber stamp;
calling the gap-test a veto.

**Developmental-pitch question (non-binding)**:
The single surviving residue of the dissolved "ethical-judgement gap." Macro line 65
makes synthetic/ethical the grade-12 judgement mode and analytical/evaluative the
grade-11 mode; a wholly-epistemological candidate *may* be asked whether it pitches
richly grade-12 or grade-11. A named, optional question Kru Fang brings from the
macro-diagnostic — not a pass/fail test, not a coverage veto, softened by
predominance-not-exclusivity. Lives only in the fork mechanic (appendix step 3);
candidate descriptions stay neutral. See [ADR-0004](./adr/0004-ethical-judgement-gap-demoted.md).
_Avoid_: "ethical-judgement gap" as a block-level criterion (dissolved); treating
the pitch question as disqualifying C1.

**Question-arc (grade level)**:
The set of four block deep questions across a grade, designed *as a set* to tell one
coherent developmental story while jointly covering all six competencies. The
generative object of grade-level design. Not demonstrated by the pilot (one block,
no arc above it) — named and seeded for future whole-curriculum design.
_Avoid_: equating one block's deep question with the arc.

**Block-level operationalisation**:
The operationalisation of a sub-ability *within the pilot block's specific
context* — gets its bite from the block's phase structure and capstone artifact.
Distinct from a framework-wide operationalisation (which doesn't yet exist for
S2/S3/E1/E2 anyway and was deferred).
_Avoid_: operationalisation (ambiguous), assessment criterion.

**Working group**:
The group convening 2026-06-17 that decides the Grade 12 competency framework
and the pilot block's meso-level design. Kru Fang brings drafts as input.
_Avoid_: committee, planning team.

**Kru Fang's dual role**:
Kru Fang is both the framework architect (drafts inputs to working group;
holds macro-curriculum diagnostic expertise) *and* one of the two pilot
teachers (will teach the block; co-author of D and F). When she speaks in
a working-group session, both roles are present — group should treat them
as distinct contributions where it matters (architectural vs teaching-stake).
_Avoid_: collapsing her into "the framework person" or "a teacher".

**Cosmology possibility-space map**:
Retained as a single-subject reference but no longer linked from the site —
superseded in the published navigation by the "Cosmology + Optics integrating
map" (below), which carries it as one half.
The interactive infinite-canvas concept map (`docs/cosmology-map.html`) of
what a Grade-12 cosmology main-lesson block *could* contain — the full content
universe, not a chosen design. Content organized into six thematic clusters,
each node tagged by deep-question candidate affinity (1 epistemological /
2 stardust / shared) and the PISA competencies it would exercise; within a
theme nodes form a builds-on dependency tree, with cross-theme bridges marking
the synthesis space. A Session-1 (Jun 24) decision aid for outputs A (competency
selection) and B (deep question) — it surfaces the fork rather than presuming it.
English-only working instrument, not a published bilingual deliverable.
Carries a reading caveat: the map leans Candidate 2 because that material was
already realised as a taught course (so it is deeper/richer there) — prior
teaching, not evidence Candidate 2 is the stronger choice.
_Avoid_: cosmology block plan, the syllabus (it is a content inventory, not a
design or sequence).

**Optics possibility-space map**:
Retained as a single-subject reference but no longer linked from the site —
superseded in the published navigation by the "Cosmology + Optics integrating
map" (below), which carries it as one half.
The companion interactive map (`docs/optics-map.html`) for the Optics half of
the combined block — same engine and structure as the Cosmology possibility-space
map (six thematic clusters, builds-on dependency trees, cross-theme bridges,
nodes tagged by deep-question candidate affinity and PISA competency). Blends
*both* traditions — Waldorf/Goethean phenomenological optics and conventional
science-education optics — as one content universe; tradition is deliberately
*not* a tag or filter (the Goethe↔Newton contrast lives inside the content, e.g.
the Colour theme, not as an axis). Carries the mirror reading caveat: it leans
Candidate 1 because optics naturally surfaces epistemological material (light as
the object of knowing) more richly than instrumental material — a property of
the subject, not evidence Candidate 1 is stronger. The two maps are a
complementary pair (Cosmology leans C2, Optics leans C1) feeding the same
Session-1 A/B decision.
_Avoid_: optics block plan, the syllabus; "Waldorf-vs-conventional map" (it is
not split by tradition).

**Cosmology + Optics integrating map**:
The single published whole-block map (`docs/integrating-map.html`) — the only
possibility-space map linked from the site. A superset that carries the entire
combined block on one canvas: both halves side by side (Optics left, Cosmology
right) as twelve themes, every node from the two single-subject maps, plus a
third edge type — the *cross-block hinges* (gold) joining Optics to Cosmology
where the two genuinely meet (e.g. spectroscopy ↔ stardust evidence, finite
speed of light ↔ deep time, model-vs-reality across both epistemology themes).
Within-theme builds-on `dep` edges and within-half `bridge` edges are retained
from the source maps; the hinges are the new integration layer, isolable via a
"synthesis only" view that dims everything except them. Same candidate-affinity
and competency filters as the source maps; carries a combined reading caveat
(Cosmology half leans C2, Optics half leans C1 — depth reflects origin, not the
strength of either deep question). The two single-subject maps are kept as
references but delinked.
_Avoid_: "block plan" or "syllabus" (still a content inventory, not a design);
calling the hinges "bridges" (bridge = within a half; hinge = across halves).
