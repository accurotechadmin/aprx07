# Fibonacci Inventory Glossary

## Governing convention and source hierarchy

This glossary follows the repository's governing **Fv convention**: **Fv -1 -> destination 0**, **Fv 0 -> destination 1**, **Fv 1 -> destination 1**, and every later destination is obtained by adding the two immediately preceding destinations. **Fv** names a process step; **D_v** names the destination value at that step. Under conventional Fibonacci indexing with `F_0 = 0` and `F_1 = 1`, `D_v = F_(v+1)`.

Source hierarchy: the **Fibonacci Truth Inventory** is the primary positive standard for definitions, values, formulas, limits, and verified observations; the **Fibonacci Avoids and Error Inventory** is the diagnostic standard for named failure modes; the **Detailed Description** is the crosswalk explaining the inventories' structure; the **Comprehensive Report** is supplemental synthesis; and this glossary is an aid, not a replacement for the inventories.

## Reading guide

Each entry gives: **Definition**; **Role/domain**; **Caution**; and **Identifiers**. Identifier prefixes are distinct: **TR** entries are truths, **AV** entries are avoid/error conditions, and **REF** entries are canonical destination references. Entries marked **Supplemental** or **External context** are helpful concepts inferred from or adjacent to the documents, not new inventory claims.

## A. Governing documents, identifiers, and workflow

### Fibonacci Inventory Documents
- **Definition:** The unified document set consisting chiefly of the Avoids Inventory, Truth Inventory, and Detailed Description, supplemented by the Comprehensive Report, Boot-Up Primer, and glossary seed.
- **Role/domain:** Document structure; workflow.
- **Caution:** Treat the three governing inventories as one reference system, not as independent or conflicting sources.
- **Identifiers:** TR inventory generally; AV inventory generally; REF-001--REF-030.

### Fibonacci Avoids and Error Inventory
- **Definition:** The negative and diagnostic standard listing 100 named avoid conditions for Fibonacci arithmetic, indexing, ratios, visualization, rendering, geometry, explanation, and document integrity.
- **Role/domain:** Error taxonomy; audit workflow.
- **Caution:** AV identifiers name failure modes; they do not establish positive values by themselves except through the canonical appendix.
- **Identifiers:** AV-001--AV-100; REF-001--REF-030.

### Fibonacci Truth Inventory
- **Definition:** The positive standard listing canonical values, formulas, ratio inventories, limits, visualization facts, geometric facts, and verified observations about seven examined images.
- **Role/domain:** Mathematical reference; visualization standard; image audit.
- **Caution:** TR entries are declarative inventory facts, not full proofs of every theorem.
- **Identifiers:** TR-001--TR-163.

### Detailed Description of the Fibonacci Inventory Documents
- **Definition:** The structural guide explaining the inventories' shared convention, identifier namespaces, sections, typography, cross-document relationships, and intended use.
- **Role/domain:** Metadata; crosswalk; document structure.
- **Caution:** It explains the inventories but does not replace the Truth or Avoids inventories as the source of values and error labels.
- **Identifiers:** Supports AV, TR, and REF namespace interpretation.

### Comprehensive Report
- **Definition:** A supplemental report summarizing the document set as a coordinated reference system for Fibonacci math, graphics, and auditing.
- **Role/domain:** Supplemental synthesis; workflow.
- **Caution:** Use it as interpretation and overview, not as the highest authority when it conflicts with explicit TR, AV, or REF statements.
- **Identifiers:** No independent TR/AV/REF namespace.

### Fibonacci Boot-Up Primer
- **Definition:** The required start-of-session procedure directing the reader to study the governing inventories as a unified reference system before doing substantive Fibonacci work.
- **Role/domain:** Workflow; source hierarchy.
- **Caution:** Boot-up is preparatory; it does not add mathematical claims beyond the inventories.
- **Identifiers:** Reinforces TR-001--TR-015; AV-001--AV-015; REF-001--REF-030.

### Fibonacci Glossary Seed
- **Definition:** The raw vocabulary list and drafting prompt from which this glossary was built.
- **Role/domain:** Workflow; document provenance.
- **Caution:** The seed is intentionally not a finished glossary and should not be treated as alphabetized authority.
- **Identifiers:** Supplemental; no TR/AV/REF identifiers.

### Entry
- **Definition:** A named unit in an inventory, usually containing an identifier, short label, and concise description.
- **Role/domain:** Document structure.
- **Caution:** Do not confuse an entry's label with the identifier namespace to which it belongs.
- **Identifiers:** TR entries; AV entries; REF entries.

### Stable ID
- **Definition:** A persistent identifier used to cite a truth, avoid condition, or canonical reference without relying on page layout.
- **Role/domain:** Document structure; audit.
- **Caution:** Keep namespaces separate: AV-031 and TR-031 are different entries.
- **Identifiers:** AV-001--AV-100; TR-001--TR-163; REF-001--REF-030.

### AV identifier
- **Definition:** An identifier for a recognized failure mode or avoid condition.
- **Role/domain:** Error classification.
- **Caution:** Use AV labels when something is wrong or risky; do not use them as positive definitions unless paired with TR/REF support.
- **Identifiers:** AV-001--AV-100.

### TR identifier
- **Definition:** An identifier for a positive truth statement, value, formula, visualization fact, geometric fact, or verified image observation.
- **Role/domain:** Truth reference.
- **Caution:** TR statements govern correctness but may not include full derivations.
- **Identifiers:** TR-001--TR-163.

### REF identifier
- **Definition:** An identifier in the Avoids appendix anchoring a specific Fv step to its canonical destination.
- **Role/domain:** Canonical reference; indexing.
- **Caution:** REF entries cover destinations Fv -1 through Fv 28 only.
- **Identifiers:** REF-001--REF-030.

### Source hierarchy
- **Definition:** The priority order for resolving definitions and claims: Truth Inventory first for positive facts, Avoids Inventory for failure modes, Detailed Description for organization, Comprehensive Report for synthesis.
- **Role/domain:** Workflow.
- **Caution:** Do not attribute supplemental interpretations to the inventories unless the inventories establish them.
- **Identifiers:** TR generally; AV generally; REF generally.

### Governing standard
- **Definition:** The set of conventions, values, formulas, and audit rules that Fibonacci work in this repository must follow.
- **Role/domain:** Workflow; document structure.
- **Caution:** External Fibonacci conventions may be valid elsewhere but must be converted explicitly here.
- **Identifiers:** TR-001--TR-015; AV-001, AV-004, AV-013.

### Audit procedure
- **Definition:** The checklist-based review of indexing, seed values, destinations, recurrence, ratios, exactness, limits, axes, scales, rendering, geometry, labels, and range completeness.
- **Role/domain:** Workflow; audit.
- **Caution:** A visually attractive chart still fails if numerical, labeling, or rendering checks fail.
- **Identifiers:** AV-100; TR visualization and geometry sections.

### Stage 1: establish the reference
- **Definition:** The audit step in which the Fv convention, canonical sequence, ratio definitions, limits, and relevant TR/REF values are fixed before inspecting a representation.
- **Role/domain:** Workflow.
- **Caution:** Skipping this stage invites convention mixing and index drift.
- **Identifiers:** TR-001--TR-015; REF-001--REF-030; AV-001, AV-004.

### Stage 2: inspect a representation
- **Definition:** The audit step in which the chart, diagram, image, table, or prose is examined for visible data, labels, scales, geometry, and rendering features.
- **Role/domain:** Workflow; image audit.
- **Caution:** Separate visible evidence from calculated source values and screenshot estimates.
- **Identifiers:** AV-066--AV-077; TR measurement facts.

### Stage 3: classify findings
- **Definition:** The audit step in which observed issues are mapped to AV failure modes and confirmed facts are mapped to TR/REF statements.
- **Role/domain:** Workflow; error taxonomy.
- **Caution:** Do not overgeneralize image-specific findings to other graphics.
- **Identifiers:** AV-001--AV-100; TR image observations.

## B. Indexing, destination values, and recurrence

### Fv
- **Definition:** The repository's symbol for a Fibonacci process step.
- **Role/domain:** Indexing; notation.
- **Caution:** Fv is not itself the destination value; avoid step-value swaps.
- **Identifiers:** TR-001; AV-006.

### Fv convention
- **Definition:** The document-defined process: `Fv -1 -> 0`, `Fv 0 -> 1`, `Fv 1 -> 1`, then addition of the two preceding destinations.
- **Role/domain:** Indexing; recurrence.
- **Caution:** Do not silently mix this with conventional `F_0 = 0, F_1 = 1` notation.
- **Identifiers:** TR-003--TR-007; AV-001--AV-005, AV-013; REF-001--REF-030.

### Process step
- **Definition:** A position in the Fv process, such as Fv 12, which has an associated destination D_12.
- **Role/domain:** Indexing.
- **Caution:** Distinguish process step from destination value, conventional index, transition, and ratio label.
- **Identifiers:** TR-001, TR-015; AV-006, AV-007.

### Destination
- **Definition:** The value reached at a process step; written `D_v` for step Fv v.
- **Role/domain:** Indexing; recurrence.
- **Caution:** Destination values are not interchangeable with Fv labels.
- **Identifiers:** TR-002; AV-006, AV-007, AV-092.

### D_v
- **Definition:** The notation for the destination value associated with Fv v.
- **Role/domain:** Notation; recurrence; ratio.
- **Caution:** In the repository convention, `D_v = F_(v+1)` under standard `F_0=0, F_1=1` indexing.
- **Identifiers:** TR-002, TR-007.

### Fv -1
- **Definition:** The initial zero step in the repository convention, with destination 0.
- **Role/domain:** Indexing; seed values.
- **Caution:** Omitting this step is Zero Omission if the stated convention includes it.
- **Identifiers:** TR-003, TR-016; REF-001; AV-002.

### Fv 0
- **Definition:** The first one step, with destination 1.
- **Role/domain:** Indexing; seed values.
- **Caution:** Do not merge it with Fv 1; the two ones occupy separate steps.
- **Identifiers:** TR-004, TR-017; REF-002; AV-003.

### Fv 1
- **Definition:** The second one step, with destination 1, and the first step with a valid forward ratio `R_1 = D_1/D_0 = 1/1`.
- **Role/domain:** Indexing; seed values; ratio.
- **Caution:** The ratio is valid because the prior positive destination is D_0 = 1, not D_-1 = 0.
- **Identifiers:** TR-005, TR-018, TR-046; REF-003; AV-014.

### Destination 0
- **Definition:** The canonical destination at Fv -1.
- **Role/domain:** Indexing; sequence value.
- **Caution:** It cannot be used as a denominator for a standard reciprocal or forward ratio.
- **Identifiers:** TR-003, TR-016; REF-001; AV-014.

### Destination 1
- **Definition:** The destination at both Fv 0 and Fv 1.
- **Role/domain:** Indexing; seed values.
- **Caution:** The duplicate one is intentional and must not be collapsed into one step.
- **Identifiers:** TR-004, TR-005, TR-011, TR-017, TR-018; REF-002, REF-003; AV-003.

### Seed destinations
- **Definition:** The initial destination values that determine the recurrence, here 0, 1, and 1 as positioned by the Fv convention.
- **Role/domain:** Recurrence; indexing.
- **Caution:** A recurrence without seeds is underdetermined; wrong seed pairs create a different sequence.
- **Identifiers:** TR-003--TR-006; AV-005, AV-016.

### Continuing by addition
- **Definition:** The rule that every later destination is the sum of the two immediately preceding destinations.
- **Role/domain:** Recurrence.
- **Caution:** Addition must preserve process order and exact integer values.
- **Identifiers:** TR-006; AV-017, AV-020, AV-021, AV-026.

### Recurrence
- **Definition:** For `v >= 1`, the destination relation `D_v = D_(v-1) + D_(v-2)`.
- **Role/domain:** Recurrence; mathematical fact.
- **Caution:** Do not explain ratio convergence without also respecting the ratio recurrence where relevant.
- **Identifiers:** TR-006; AV-005, AV-016, AV-017, AV-040.

### Conventional Fibonacci indexing
- **Definition:** The external standard notation beginning `F_0 = 0` and `F_1 = 1`.
- **Role/domain:** Indexing; external mathematical context.
- **Caution:** In this repository, convert by `D_v = F_(v+1)` and never mix labels silently.
- **Identifiers:** TR-007; AV-004, AV-013.

### Fv-to-conventional conversion
- **Definition:** The mapping from repository steps to conventional Fibonacci labels: Fv v corresponds to conventional `F_(v+1)`.
- **Role/domain:** Indexing; notation.
- **Caution:** A chart using both systems must state the relationship explicitly.
- **Identifiers:** TR-007; AV-004, AV-013.

### Conventional Map
- **Definition:** The Truth Inventory's statement that `D_v = F_(v+1)` under conventional `F_0=0, F_1=1` indexing.
- **Role/domain:** Indexing.
- **Caution:** It is a conversion, not permission to relabel steps inconsistently.
- **Identifiers:** TR-007; AV-004, AV-013.

### Canonical destination sequence
- **Definition:** The inventory sequence from Fv -1 through Fv 28: 0, 1, 1, 2, 3, 5, 8, 13, ..., 514229.
- **Role/domain:** Recurrence; canonical reference.
- **Caution:** Values beyond the declared range may be Fibonacci values, but REF coverage ends at Fv 28.
- **Identifiers:** TR-016--TR-045; REF-001--REF-030.

### Compact destination table
- **Definition:** The Truth Inventory table mapping Fv steps -1 through 28 to destinations and conventional indices.
- **Role/domain:** Document structure; canonical reference.
- **Caution:** Use it to prevent copied-value and index errors.
- **Identifiers:** TR-016--TR-045; REF-001--REF-030; AV-094.

### Thirty Values
- **Definition:** The fact that Fv -1 through Fv 28 contains 30 destination values.
- **Role/domain:** Counting; indexing.
- **Caution:** Do not call these 30 values 30 transitions.
- **Identifiers:** TR-008; AV-008.

### Twenty-Nine Transitions
- **Definition:** The fact that the same Fv -1 through Fv 28 range contains 29 adjacent transitions.
- **Role/domain:** Counting; indexing.
- **Caution:** Transitions are between destinations, not destinations themselves.
- **Identifiers:** TR-009; AV-008.

### Nonnegative destinations
- **Definition:** Every canonical destination in the stated range is a nonnegative integer.
- **Role/domain:** Sequence value.
- **Caution:** Large unused negative plot ranges need a stated purpose.
- **Identifiers:** TR-010; AV-063.

### Duplicate One / Twin One
- **Definition:** The intentionally repeated positive destination 1 at Fv 0 and Fv 1.
- **Role/domain:** Indexing; seed values.
- **Caution:** Collapsing the two ones causes Twin-One Confusion.
- **Identifiers:** TR-011; AV-003.

### Strict Growth
- **Definition:** Destinations increase strictly from Fv 1 onward.
- **Role/domain:** Sequence property.
- **Caution:** Strict growth does not apply across Fv 0 to Fv 1 because both destinations are 1.
- **Identifiers:** TR-012.

### Prior Value
- **Definition:** The prior destination for Fv v is `D_(v-1)`.
- **Role/domain:** Indexing; ratio.
- **Caution:** A ratio annotation should not omit the prior destination used as denominator.
- **Identifiers:** TR-013; AV-009, AV-093.

### Next Value
- **Definition:** The destination after Fv v is `D_(v+1)`.
- **Role/domain:** Indexing; recurrence.
- **Caution:** Keep next-value language separate from Tomorrow in the metaphor.
- **Identifiers:** TR-014; AV-034.

### Step Format
- **Definition:** The unambiguous text form `Fv v -> destination D_v`.
- **Role/domain:** Notation; explanation.
- **Caution:** Use this format when labels might otherwise be mistaken for values.
- **Identifiers:** TR-015; AV-006, AV-007.

### Index Drift
- **Definition:** Shifting the same destination value among incompatible step numbers without declaring an indexing change.
- **Role/domain:** Indexing error.
- **Caution:** Especially likely when converting between Fv and conventional `F_n` notation.
- **Identifiers:** AV-001; TR-007.

### Zero Omission
- **Definition:** Beginning the displayed process at 1 while the stated convention includes `Fv -1 -> 0`.
- **Role/domain:** Indexing error.
- **Caution:** Omitting zero changes counts, transitions, and ratio-domain explanations.
- **Identifiers:** AV-002; TR-003, TR-016; REF-001.

### Twin-One Confusion
- **Definition:** Treating the two initial 1 destinations as one step.
- **Role/domain:** Indexing error.
- **Caution:** Fv 0 and Fv 1 must remain distinct.
- **Identifiers:** AV-003; TR-004, TR-005, TR-011.

### Convention Mixing
- **Definition:** Combining conventional `F_0=0` indexing with the Fv convention in one chart, caption, table, or equation without conversion.
- **Role/domain:** Indexing error; notation.
- **Caution:** State `D_v = F_(v+1)` whenever both systems appear.
- **Identifiers:** AV-004; TR-007.

### Implicit Seeds
- **Definition:** Presenting a recurrence without the seed destinations that determine it.
- **Role/domain:** Recurrence error.
- **Caution:** Different seed pairs can satisfy the same addition form but produce different sequences.
- **Identifiers:** AV-005; TR-003--TR-006.

### Step-Value Swap
- **Definition:** Using Fv as if it were both a step label and destination number.
- **Role/domain:** Terminology error.
- **Caution:** Separate Fv v from `D_v` with notation or prose.
- **Identifiers:** AV-006; TR-001, TR-002.

### Term Ambiguity
- **Definition:** Using term, step, index, value, and destination interchangeably.
- **Role/domain:** Terminology error.
- **Caution:** These words have distinct audit roles in the document set.
- **Identifiers:** AV-007; TR-001--TR-015.

### Count Ambiguity
- **Definition:** Confusing displayed destinations with adjacent transitions.
- **Role/domain:** Counting error.
- **Caution:** Fv -1 through Fv 28 has 30 destinations but 29 transitions.
- **Identifiers:** AV-008; TR-008, TR-009.

### Missing Range / Endpoint Loss
- **Definition:** Stopping before the declared endpoint or omitting final required destinations from a complete reference graphic.
- **Role/domain:** Range error; visualization.
- **Caution:** A complete 30-destination reference must include through Fv 28; endpoint loss specifically warns about Fv 23 through Fv 28.
- **Identifiers:** AV-010, AV-027; TR-040--TR-045; REF-025--REF-030.

### Tick Gaps
- **Definition:** Missing a step label on a sequential axis, such as skipping 22.
- **Role/domain:** Visualization; indexing error.
- **Caution:** A missing tick can falsely imply missing or shifted data.
- **Identifiers:** AV-011; TR image observations for Image Seven.

### Duplicate Labels
- **Definition:** Assigning one Fv label to two destinations or repeating a step label on an axis.
- **Role/domain:** Labeling error.
- **Caution:** Duplicate labels obscure the process-to-destination mapping.
- **Identifiers:** AV-012; TR-015.

### Legacy Symbols
- **Definition:** Retained `F_n` notation after relabeling data as Fv without stating the relationship.
- **Role/domain:** Notation error.
- **Caution:** Legacy symbols require explicit conversion to avoid convention mixing.
- **Identifiers:** AV-013; TR-007.

## C. Ratios, limits, convergence, and the time metaphor

### Forward ratio
- **Definition:** `R_v = D_v / D_(v-1)` for steps with a valid prior positive destination; it approaches phi.
- **Role/domain:** Ratio; convergence.
- **Caution:** It is not the reciprocal ratio and no finite forward ratio equals phi exactly.
- **Identifiers:** TR-046--TR-073; AV-014, AV-028, AV-031.

### R_v
- **Definition:** The Truth Inventory notation for the forward adjacent-destination ratio at Fv v.
- **Role/domain:** Ratio; notation.
- **Caution:** Its step label must correspond correctly to numerator and denominator.
- **Identifiers:** TR-046--TR-073; AV-009, AV-091.

### Undefined Ratio
- **Definition:** The error of assigning a forward ratio where no valid prior positive destination exists, notably Fv -1 or Fv 0.
- **Role/domain:** Ratio-domain error.
- **Caution:** Avoid zero denominators and absent prior positive destinations.
- **Identifiers:** AV-014; TR-046.

### Fraction Offset
- **Definition:** Labeling `D_v/D_(v-1)` with the wrong step, numerator, or denominator association.
- **Role/domain:** Ratio labeling error.
- **Caution:** State numerator and denominator definitions near ratio labels.
- **Identifiers:** AV-009; AV-091, AV-093.

### Reciprocal ratio
- **Definition:** `Q_v = D_(v-1) / D_v`, the reciprocal of the forward ratio where defined; it approaches `1/phi`.
- **Role/domain:** Ratio; convergence.
- **Caution:** Do not reverse it with `R_v`; no finite reciprocal ratio equals `1/phi` exactly.
- **Identifiers:** Reciprocal-ratio sample TR section; AV-028, AV-032.

### Q_v
- **Definition:** The Truth Inventory notation for reciprocal adjacent-destination ratios, sampled from Fv 1 through Fv 12.
- **Role/domain:** Ratio; notation.
- **Caution:** The reciprocal inventory is incomplete by design compared with the forward-ratio inventory through Fv 28.
- **Identifiers:** Reciprocal-ratio sample TR entries; AV-028, AV-030, AV-032.

### R_1 = 1/1
- **Definition:** The first forward ratio, `D_1/D_0 = 1/1 = 1.000000000000`.
- **Role/domain:** Ratio; canonical value.
- **Caution:** It begins at Fv 1, not Fv -1 or Fv 0.
- **Identifiers:** TR-046; AV-014.

### R_2 = 2/1
- **Definition:** The second forward ratio, `D_2/D_1 = 2/1 = 2.000000000000`.
- **Role/domain:** Ratio; canonical value.
- **Caution:** Its high value is part of the oscillatory convergence pattern.
- **Identifiers:** TR-047; AV-035, AV-036.

### R_3 = 3/2
- **Definition:** The third forward ratio, `D_3/D_2 = 3/2 = 1.500000000000`.
- **Role/domain:** Ratio; canonical value.
- **Caution:** Keep the exact fraction when exactness matters.
- **Identifiers:** TR-048; AV-015.

### R_4 = 5/3
- **Definition:** The fourth forward ratio, `D_4/D_3 = 5/3 ≈ 1.666666666667`.
- **Role/domain:** Ratio; canonical value.
- **Caution:** Decimal form is rounded; do not write it as exact equality to the rounded decimal.
- **Identifiers:** TR-049; AV-015.

### R_28 = 514229/317811
- **Definition:** The forward ratio at Fv 28, `D_28/D_27 = 514229/317811 ≈ 1.618033988754`.
- **Role/domain:** Ratio; canonical endpoint.
- **Caution:** Despite being close to phi, it remains a finite rational ratio, not phi.
- **Identifiers:** TR-073; AV-031, AV-045.

### Q_1 = 1/1
- **Definition:** The first reciprocal ratio, `D_0/D_1 = 1/1`.
- **Role/domain:** Ratio; canonical sample.
- **Caution:** It is a reciprocal-ratio value, not evidence that reciprocal ratios equal `1/phi`.
- **Identifiers:** Reciprocal-ratio sample TR entries; AV-032.

### Q_2 = 1/2
- **Definition:** The reciprocal ratio `D_1/D_2 = 1/2`.
- **Role/domain:** Ratio; canonical sample.
- **Caution:** Do not plot it on a forward-ratio curve.
- **Identifiers:** Reciprocal-ratio sample TR entries; AV-028.

### Q_12 = 144/233
- **Definition:** The reciprocal-ratio sample value at Fv 12, `D_11/D_12 = 144/233 ≈ 0.618025751073`.
- **Role/domain:** Ratio; canonical sample.
- **Caution:** It approximates `1/phi` but is not exactly `1/phi`.
- **Identifiers:** Reciprocal-ratio sample TR entries; AV-032.

### Golden ratio / phi
- **Definition:** `phi = (1 + sqrt(5)) / 2`, the irrational limiting value of forward Fibonacci ratios.
- **Role/domain:** Limit; external mathematical constant established in inventory.
- **Caution:** No finite ratio of integer Fibonacci destinations equals phi exactly.
- **Identifiers:** Golden Ratio and Forward Limit TR entries; AV-031, AV-041, AV-044.

### Reciprocal limit / 1/phi
- **Definition:** `1/phi = phi - 1`, the irrational limiting value of reciprocal Fibonacci ratios.
- **Role/domain:** Limit; ratio.
- **Caution:** No finite reciprocal ratio equals `1/phi` exactly.
- **Identifiers:** Reciprocal Limit TR entry; AV-028, AV-029, AV-032.

### Forward Limit
- **Definition:** The statement that forward ratios `R_v` approach phi as v increases.
- **Role/domain:** Convergence.
- **Caution:** Approach is alternating, not monotone.
- **Identifiers:** Forward Limit TR entry; AV-035, AV-036.

### Ratio Update
- **Definition:** The recurrence `R_(v+1) = 1 + 1/R_v` for forward ratios.
- **Role/domain:** Ratio recurrence; convergence.
- **Caution:** Omitting it weakens or obscures convergence explanations.
- **Identifiers:** Ratio Update TR entry; AV-040.

### Error Identity
- **Definition:** The signed-error relation `R_(v+1) - phi = -(R_v - phi)/(phi * R_v)`.
- **Role/domain:** Convergence; error analysis.
- **Caution:** It describes signed errors; do not confuse with absolute errors or step-to-step swings.
- **Identifiers:** Error Identity TR entry; AV-037, AV-038.

### Alternating Sign
- **Definition:** Forward-ratio errors alternate above and below phi.
- **Role/domain:** Convergence.
- **Caution:** Do not claim one-sided or monotone convergence.
- **Identifiers:** Alternating Sign TR entry; AV-035, AV-036.

### Shrinking Error
- **Definition:** The magnitudes of forward-ratio errors decrease as ratios converge toward phi.
- **Role/domain:** Convergence; error analysis.
- **Caution:** Shrinking error is not the same as a fixed exact multiplier at every step.
- **Identifiers:** Shrinking Error TR entry; AV-039.

### Asymptotic Factor
- **Definition:** The ratio of successive forward-error magnitudes approaches `1/phi^2`.
- **Role/domain:** Convergence; error analysis.
- **Caution:** The factor approaches `1/phi^2`; it is not exactly that factor at every finite step.
- **Identifiers:** Asymptotic Factor TR entry; AV-039.

### Finite Rational
- **Definition:** Every finite Fibonacci ratio formed from integer destinations is rational.
- **Role/domain:** Exactness; ratio.
- **Caution:** Finite rational ratios can approximate irrational limits but cannot equal them.
- **Identifiers:** Finite Rational TR entry; AV-031, AV-032.

### Irrational Limit
- **Definition:** Phi and `1/phi` are irrational limiting constants.
- **Role/domain:** Exactness; convergence.
- **Caution:** Decimal approximations are not exact symbolic values.
- **Identifiers:** Irrational Limit TR entry; AV-015, AV-031, AV-032.

### No Equality
- **Definition:** The inventory fact that no finite forward ratio equals phi exactly and no finite reciprocal ratio equals `1/phi` exactly.
- **Role/domain:** Exactness; ratio.
- **Caution:** Use `≈` for rounded numerical approximations.
- **Identifiers:** No Equality TR entry; AV-015, AV-031, AV-032.

### Signed Error
- **Definition:** A signed difference such as `R_v - phi`, retaining whether the ratio is above or below phi.
- **Role/domain:** Error analysis.
- **Caution:** Do not label it as absolute error.
- **Identifiers:** Signed Error TR entry; AV-038.

### Absolute Error
- **Definition:** A nonnegative distance such as `|R_v - phi|`.
- **Role/domain:** Error analysis.
- **Caution:** Do not confuse it with signed error or step-to-step ratio swing.
- **Identifiers:** Absolute Error TR entry; AV-037, AV-038.

### Step Swing
- **Definition:** The change between consecutive ratios, such as `|R_v - R_(v-1)|`.
- **Role/domain:** Error analysis; visualization.
- **Caution:** It is not the same quantity as distance from phi.
- **Identifiers:** Step Swing TR entry; AV-037.

### Ratio Reversal
- **Definition:** Confusing `D_v/D_(v-1)` with `D_(v-1)/D_v`.
- **Role/domain:** Ratio error.
- **Caution:** Forward ratios approach phi; reciprocal ratios approach `1/phi`.
- **Identifiers:** AV-028.

### Exact Phi
- **Definition:** The error of claiming a finite Fibonacci ratio exactly equals phi.
- **Role/domain:** Exactness error.
- **Caution:** Finite ratios are rational; phi is irrational.
- **Identifiers:** AV-031; Finite Rational, Irrational Limit, No Equality TR entries.

### Exact Yesterday
- **Definition:** The error of claiming a finite reciprocal ratio exactly equals `1/phi`.
- **Role/domain:** Exactness error; metaphor.
- **Caution:** `1/phi` is the reciprocal limit, not a finite reciprocal ratio.
- **Identifiers:** AV-032; Reciprocal Limit and No Equality TR entries.

### Unmarked Approximation
- **Definition:** Writing rounded decimals such as 0.618 or 1.618 with an equality sign.
- **Role/domain:** Exactness; notation error.
- **Caution:** Mark rounded decimals with `≈` or explicit wording.
- **Identifiers:** AV-015; Approximation Sign TR entry.

### Decimal Truncation
- **Definition:** Using too few decimals for phi when a chart claims to resolve late oscillations.
- **Role/domain:** Exactness; visualization.
- **Caution:** Insufficient precision can hide or fabricate above/below relationships.
- **Identifiers:** AV-044; AV-045.

### Rounding Sign
- **Definition:** Rounding late ratios so aggressively that above-phi and below-phi values appear identical.
- **Role/domain:** Exactness; rendering.
- **Caution:** Preserve enough precision or use exact fractions/error panels when sign matters.
- **Identifiers:** AV-045; Rounding Loss TR entry.

### Yesterday, Today, Tomorrow metaphor
- **Definition:** A document-defined metaphor mapping Yesterday to `1/phi ≈ 0.618`, Today to `1`, and Tomorrow to `phi ≈ 1.618`.
- **Role/domain:** Metaphor; visualization.
- **Caution:** It is not a Fibonacci theorem and does not redefine time or recurrence.
- **Identifiers:** Today Value, Yesterday Value, Tomorrow Value, Metaphor Status TR entries; AV-029--AV-034, AV-042.

### Yesterday Value
- **Definition:** The metaphorical reference value `1/phi = phi - 1 ≈ 0.618`.
- **Role/domain:** Metaphor; reciprocal limit.
- **Caution:** It belongs to the reciprocal-ratio limit, not the forward-ratio limit.
- **Identifiers:** Yesterday Value TR entry; AV-029, AV-032, AV-052.

### Today Value / Unity Point
- **Definition:** The metaphorical reference value `1`.
- **Role/domain:** Metaphor; reference line.
- **Caution:** Include it when the time metaphor is part of the display.
- **Identifiers:** Today Value and Unity Point TR entries; AV-042.

### Tomorrow Value
- **Definition:** The metaphorical reference value `phi ≈ 1.618`.
- **Role/domain:** Metaphor; forward limit.
- **Caution:** It belongs to the forward-ratio limit, not the reciprocal-ratio curve.
- **Identifiers:** Tomorrow Value TR entry; AV-030, AV-031.

### Unequal Spacing
- **Definition:** The fact that `1/phi`, `1`, and `phi` are not equally spaced on a linear number axis.
- **Role/domain:** Metaphor; visualization.
- **Caution:** Do not draw or imply equal spacing among Yesterday, Today, and Tomorrow on a linear scale.
- **Identifiers:** Unequal Spacing TR entry; AV-033.

### Linear Time
- **Definition:** The error of implying `0.618`, `1`, and `1.618` are equally spaced on a linear axis.
- **Role/domain:** Metaphor error; visualization.
- **Caution:** The labels are metaphorical references, not equal time intervals.
- **Identifiers:** AV-033; Unequal Spacing TR entry.

### Metaphor Fact
- **Definition:** The error of presenting Yesterday/Today/Tomorrow as a theorem of Fibonacci mathematics.
- **Role/domain:** Explanation error.
- **Caution:** Label the mapping as document-declared metaphor.
- **Identifiers:** AV-034; Metaphor Status TR entry.

## D. Exactness, evidence, and mathematical context

### Exact fraction
- **Definition:** A ratio represented symbolically as an integer numerator over an integer denominator, such as `233/144`.
- **Role/domain:** Exactness; ratio.
- **Caution:** Prefer exact fractions where equality matters; decimal expansions may be rounded.
- **Identifiers:** Forward-ratio TR entries; AV-015, AV-064.

### Twelve-place decimal
- **Definition:** The displayed decimal precision used in the forward-ratio inventory.
- **Role/domain:** Exactness; table representation.
- **Caution:** These decimals are rounded representations of exact fractions, not replacement exact values.
- **Identifiers:** TR-046--TR-073; AV-015, AV-064.

### Approximation sign
- **Definition:** The notation or wording indicating a rounded value, commonly `≈`.
- **Role/domain:** Exactness; notation.
- **Caution:** Use it for rounded phi, reciprocal phi, and finite ratio decimals.
- **Identifiers:** Approximation Sign TR entry; AV-015.

### Mathematical exactness
- **Definition:** Faithfulness to exact values, fractions, symbolic constants, and logical distinctions.
- **Role/domain:** Exactness; audit.
- **Caution:** Exactness can be lost through rounding, plotting resolution, screenshots, or verbal overclaiming.
- **Identifiers:** AV-015, AV-031, AV-032, AV-064, AV-098.

### Rational approximation
- **Definition:** A finite rational Fibonacci ratio used as an approximation to phi or `1/phi`.
- **Role/domain:** Ratio; convergence; external context.
- **Caution:** Approximation does not imply equality.
- **Identifiers:** Finite Rational, Irrational Limit, No Equality TR entries; AV-031, AV-032.

### Convergence theorem versus inventory assertion (Supplemental)
- **Definition:** The distinction between a fully proved mathematical theorem and the inventory's declarative statement of convergence facts.
- **Role/domain:** External mathematical context; document scope.
- **Caution:** The inventories state accepted facts for audit; they are not organized as a proof textbook.
- **Identifiers:** Forward Limit, Reciprocal Limit, Error Identity TR entries.

### Data lineage
- **Definition:** The trace from source Fibonacci values through calculations to displayed chart elements, labels, and prose.
- **Role/domain:** Workflow; audit evidence.
- **Caution:** Broken lineage permits copied errors, silent corrections, or source mismatch.
- **Identifiers:** AV-020--AV-025, AV-065, AV-094, AV-096.

### Source-data-first principle
- **Definition:** The rule that calculated source values are more authoritative than screenshot measurements when originals are available.
- **Role/domain:** Measurement; rendering; audit.
- **Caution:** Screenshots can be distorted by pixels, antialiasing, scaling, and export.
- **Identifiers:** AV-070, AV-077; Source Values TR entry.

### Audit evidence classification
- **Definition:** Separating what is mathematically verified, directly visible, screenshot-estimated, or indeterminate.
- **Role/domain:** Image audit; workflow.
- **Caution:** Do not promote an estimate to a verified fact.
- **Identifiers:** AV-067--AV-077; TR image-observation standards.

### Directly visible evidence
- **Definition:** Features that can be seen in an image without reconstructing missing data, such as labels, cropped elements, markers, or UI chrome.
- **Role/domain:** Image audit.
- **Caution:** Visible appearance may still be mathematically misleading.
- **Identifiers:** AV-074, AV-075; UI Element and Crop Fact TR entries.

### Mathematically verified evidence
- **Definition:** A finding confirmed by source values, formulas, recurrence checks, or exact construction rules.
- **Role/domain:** Audit; mathematics.
- **Caution:** Mathematical verification outranks visual resemblance.
- **Identifiers:** TR-006, TR-016--TR-073; AV-070, AV-098.

### Screenshot-estimated evidence
- **Definition:** A finding inferred from raster position, pixel measurement, or visible screenshot geometry.
- **Role/domain:** Image audit; rendering.
- **Caution:** Treat as limited by resolution, antialiasing, line width, crop, and scale.
- **Identifiers:** AV-067--AV-070, AV-074--AV-077.

### Indeterminate evidence
- **Definition:** A condition that cannot be decided from the available document, crop, resolution, scale, or labels.
- **Role/domain:** Image audit; workflow.
- **Caution:** State indeterminacy instead of inventing or assuming a rule.
- **Identifiers:** AV-098; missing-information guidance in Boot-Up Primer.

### Word equation rendering loss (Supplemental)
- **Definition:** Loss or placeholder corruption that can occur when equations from Word documents are extracted as plain text.
- **Role/domain:** Document provenance; extraction.
- **Caution:** Verify symbolic expressions against readable document context before relying on extracted placeholders.
- **Identifiers:** Supplemental; related to document fidelity requirements.

### OCR-free text extraction (Supplemental)
- **Definition:** Extracting text directly from document structure rather than recognizing rendered images of text.
- **Role/domain:** Document provenance.
- **Caution:** It avoids OCR errors but may still serialize tables or equations imperfectly.
- **Identifiers:** Supplemental.

### Embedded image absence (Supplemental)
- **Definition:** The limitation that the inventory documents report observations about images not included as independently inspectable source images.
- **Role/domain:** Document scope; image audit.
- **Caution:** Do not independently re-confirm image claims without the original images.
- **Identifiers:** TR image observations; Comprehensive Report limitation.

## E. Chart construction and data visualization

### Discrete Data
- **Definition:** Fibonacci destinations and ratios exist at integer process steps in this document set.
- **Role/domain:** Visualization; recurrence.
- **Caution:** Do not present them as continuous signals without markers at observations.
- **Identifiers:** Discrete Data TR entry; AV-046--AV-048.

### Straight Segments
- **Definition:** Line segments may connect discrete observations to guide the eye without inventing intermediate recurrence values.
- **Role/domain:** Visualization.
- **Caution:** The connecting line should not dominate the markers or imply a continuous process.
- **Identifiers:** Straight Segments TR entry; AV-047, AV-048, AV-062.

### Spline Fiction
- **Definition:** The error of using a smoothed spline through discrete Fibonacci ratios, thereby inventing intermediate values, crossings, and extrema.
- **Role/domain:** Visualization error.
- **Caution:** Use discrete markers and, if needed, straight connecting segments instead.
- **Identifiers:** AV-046; Spline Meaning TR entry.

### Continuous Implication
- **Definition:** Presenting integer-step recurrence data as if it were a continuous physical signal.
- **Role/domain:** Visualization error.
- **Caution:** Show markers for exact observations.
- **Identifiers:** AV-047; Discrete Data TR entry.

### Marker Loss
- **Definition:** A connected line without visible data markers when exact step positions matter.
- **Role/domain:** Visualization error.
- **Caution:** Fibonacci ratio and destination plots generally need markers to identify discrete steps.
- **Identifiers:** AV-048; Discrete Data TR entry.

### Axis Identity
- **Definition:** The requirement that each axis identify the quantity it represents, such as destination, forward ratio, reciprocal ratio, error, or Fv step.
- **Role/domain:** Visualization standard.
- **Caution:** Generic labels like “Value” or “Index” are insufficient when multiple quantities are possible.
- **Identifiers:** Axis Identity TR entry; AV-049.

### Vague Axis
- **Definition:** An axis label that does not specify the plotted quantity.
- **Role/domain:** Visualization error.
- **Caution:** Distinguish destination plots, ratio plots, reciprocal-ratio plots, error plots, and pair plots.
- **Identifiers:** AV-049.

### Missing Units
- **Definition:** An unlabeled dashed or guide line whose mathematical role is not defined.
- **Role/domain:** Visualization error.
- **Caution:** Define phi, `1/phi`, unity, `y = phi*x`, or other references explicitly.
- **Identifiers:** AV-050; AV-088.

### Boundary Clipping
- **Definition:** Placing a plotted point on a boundary so the marker is clipped by the axis spine.
- **Role/domain:** Visualization; rendering.
- **Caution:** Clipping can hide the true value or falsely imply contact with an axis.
- **Identifiers:** AV-051.

### Excluded Yesterday
- **Definition:** Setting a ratio-chart minimum above approximately 0.618 while claiming to display the Yesterday reference.
- **Role/domain:** Metaphor visualization error.
- **Caution:** Include the reference if the label is claimed.
- **Identifiers:** AV-052; Yesterday Value TR entry.

### Crowded Ticks
- **Definition:** Overlapping or unreadable x-axis ticks, especially long fraction expressions at every step.
- **Role/domain:** Visualization error.
- **Caution:** Use tables, selected labels, rotation, or cleaner annotations when necessary.
- **Identifiers:** AV-053.

### Crowded Labels
- **Definition:** Dense point labels, such as six-decimal labels at every late ratio point, that obscure the data.
- **Role/domain:** Visualization error.
- **Caution:** Label precision should serve, not damage, readability.
- **Identifiers:** AV-054.

### Origin Collapse / Early Collapse
- **Definition:** Compression of early Fibonacci values near zero on a linear scale dominated by later large destinations.
- **Role/domain:** Visualization; scale.
- **Caution:** Use an inset or transformed view when early values need to be visible.
- **Identifiers:** AV-055; Early Collapse and Inset Need TR entries.

### Inset Need
- **Definition:** The need for an inset or error panel when convergence details or early values are not resolvable on the main scale.
- **Role/domain:** Visualization.
- **Caution:** Do not claim visibility of details that the main scale cannot show.
- **Identifiers:** Inset Need TR entry; AV-055, AV-067.

### Zero Baseline
- **Definition:** The ordinary baseline for nonnegative destination plots when appropriate to the chart type.
- **Role/domain:** Visualization.
- **Caution:** It differs from the prohibition against putting zero on a standard logarithmic axis.
- **Identifiers:** Zero Baseline and Log Restriction TR entries; AV-056.

### Zero Log
- **Definition:** The error of placing the zero destination directly on a standard logarithmic axis.
- **Role/domain:** Visualization error; scale.
- **Caution:** Standard log axes do not accept zero.
- **Identifiers:** AV-056; Log Restriction TR entry.

### Scale Collision
- **Definition:** Combining absolute destinations up to 514229 and near-unity ratios on one undifferentiated y-axis.
- **Role/domain:** Visualization error; scale.
- **Caution:** Use separate axes, panels, or explicit transformations.
- **Identifiers:** AV-043.

### Scale consistency
- **Definition:** Agreement of numeric scales across panels or chart elements where comparison is intended.
- **Role/domain:** Visualization; rendering.
- **Caution:** Similar-looking panels can be numerically incompatible.
- **Identifiers:** AV-071, AV-095; Panel Consistency TR entry.

### Orderless Scatter
- **Definition:** An unlabeled scatter plot of consecutive pairs when progression order matters.
- **Role/domain:** Visualization error.
- **Caution:** Add labels, arrows, or ordering cues when the sequence path is part of the meaning.
- **Identifiers:** AV-057; Pair Plot TR entry.

### Pair Plot / Consecutive-pair point
- **Definition:** A plot using points `(D_v, D_(v+1))` to show adjacent Fibonacci destinations.
- **Role/domain:** Visualization; convergence of slope.
- **Caution:** Use the correct coordinate order and label progression if needed.
- **Identifiers:** Pair Plot and consecutive-pair point TR entries; AV-057, AV-058.

### Slope Limit
- **Definition:** In a consecutive-pair plot, the slope `D_(v+1)/D_v` approaches phi.
- **Role/domain:** Convergence; visualization.
- **Caution:** The limiting slope reference is not the same as the line `y=x`.
- **Identifiers:** Slope Limit TR entry; AV-058.

### Reference Line / y = phi*x
- **Definition:** The appropriate limiting-slope reference line for consecutive-pair plots when convergence of slope is at issue.
- **Role/domain:** Visualization; ratio.
- **Caution:** Define the reference mathematically; do not leave it as an unlabeled dashed line.
- **Identifiers:** Reference Line TR entry; AV-050, AV-058.

### y = x
- **Definition:** The equality reference line sometimes relevant for judging whether y and x are equal.
- **Role/domain:** Visualization; external context.
- **Caution:** It is not the phi limiting-slope line for consecutive Fibonacci pairs.
- **Identifiers:** Boot-Up Primer guidance; AV-058 by contrast.

### Bar Scale
- **Definition:** The scale mapping values to bar heights in destination bar charts.
- **Role/domain:** Visualization.
- **Caution:** Equal pixel height must mean equal numeric amount unless a break or transformation is stated.
- **Identifiers:** Bar Scale TR entry; AV-059--AV-061.

### Bar Compression
- **Definition:** Changing the scale of later bars while preserving earlier scale without disclosure.
- **Role/domain:** Visualization error.
- **Caution:** A visible break or transformation label is required for transformed scales.
- **Identifiers:** AV-059, AV-061.

### Guide Distortion
- **Definition:** Placing guide lines at distorted bar tops while presenting them as a regular numeric scale.
- **Role/domain:** Visualization error.
- **Caution:** Guides must match the actual axis transform.
- **Identifiers:** AV-060.

### Unstated Break
- **Definition:** A broken, compressed, or transformed axis without a visible break or transformation label.
- **Role/domain:** Visualization error.
- **Caution:** State transformed scales explicitly.
- **Identifiers:** AV-061.

### Line Dominance
- **Definition:** Making a connecting line visually heavier than discrete markers in a sequence plot.
- **Role/domain:** Visualization caution.
- **Caution:** The line can overpower the discrete observations it is meant to support.
- **Identifiers:** AV-062.

### Excess Range
- **Definition:** Large unused negative axis range for a nonnegative sequence without a stated purpose.
- **Role/domain:** Visualization error.
- **Caution:** It wastes resolution and may visually diminish meaningful variation.
- **Identifiers:** AV-063; TR-010.

### False Precision
- **Definition:** Displaying more decimal places than the plotting resolution can distinguish.
- **Role/domain:** Visualization; exactness error.
- **Caution:** Numerical labels should not imply visual certainty beyond the chart's resolution.
- **Identifiers:** AV-064; Pixel Limit TR entry.

### No Source Table
- **Definition:** A complex educational chart lacking an accessible table or textual list of its source values.
- **Role/domain:** Visualization; auditability.
- **Caution:** Without source data, chart values are hard to verify.
- **Identifiers:** AV-065; Source Values TR entry.

## F. Pixel accuracy, scaling, rendering, and export

### Pixel accuracy
- **Definition:** The degree to which raster pixels can represent exact mathematical positions.
- **Role/domain:** Rendering; measurement.
- **Caution:** Pixel displays have finite resolution and cannot establish subpixel claims by sight alone.
- **Identifiers:** AV-066--AV-077; Pixel Limit TR entry.

### Pixel Limit
- **Definition:** The Truth Inventory principle that pixel resolution limits what can be visually distinguished.
- **Role/domain:** Rendering; visualization.
- **Caution:** Do not claim visible late-stage alternation below one pixel of displacement.
- **Identifiers:** Pixel Limit TR entry; AV-067.

### Pixel Nudging
- **Definition:** Manually moving mathematically generated points by a few pixels to make an oscillation clearer.
- **Role/domain:** Rendering error; data integrity.
- **Caution:** It sacrifices source-data fidelity for appearance.
- **Identifiers:** AV-066; AV-099.

### Subpixel Claim
- **Definition:** Claiming a visible distinction when the true displacement is below one pixel.
- **Role/domain:** Rendering error.
- **Caution:** Use calculated values or an error/inset panel instead.
- **Identifiers:** AV-067; Pixel Limit and Inset Need TR entries.

### Stroke Bias
- **Definition:** Ignoring line thickness when judging whether a plotted point lies above or below a reference line.
- **Role/domain:** Rendering caution.
- **Caution:** The stroke can overlap the reference even when the mathematical point is on one side.
- **Identifiers:** AV-068; Line Width TR entry.

### Antialias Bias
- **Definition:** Reading antialiased edge pixels as exact coordinates.
- **Role/domain:** Rendering caution.
- **Caution:** Antialiasing creates blended edge pixels, not exact data positions.
- **Identifiers:** AV-069.

### Raster Authority
- **Definition:** Treating a screenshot as the numerical source of truth when original calculated values are available.
- **Role/domain:** Rendering error; source authority.
- **Caution:** Prefer source values over screenshot measurement.
- **Identifiers:** AV-070; Source Values TR entry.

### Scale Drift
- **Definition:** Separate panels using visually similar but numerically incompatible scales.
- **Role/domain:** Visualization; rendering.
- **Caution:** Cross-panel comparisons require explicit, consistent scales or stated differences.
- **Identifiers:** AV-071; Panel Consistency TR entry.

### Aspect Distortion
- **Definition:** Resizing one axis independently when geometry or slope is supposed to remain meaningful.
- **Role/domain:** Rendering; geometry.
- **Caution:** Nonuniform resizing can corrupt slopes, squares, circles, and spirals.
- **Identifiers:** AV-072; AV-087.

### Reference Shift
- **Definition:** Moving the phi line to meet rounded point labels rather than calculating its position from the axis transform.
- **Role/domain:** Rendering; visualization error.
- **Caution:** Reference lines must be generated from mathematical constants and axis transforms.
- **Identifiers:** AV-073; AV-050.

### Hidden Crop / Crop Fact
- **Definition:** Cropping technical screenshots so titles, definitions, notes, or endpoints are missing.
- **Role/domain:** Rendering; image audit.
- **Caution:** Crops limit what can be verified and may remove necessary context.
- **Identifiers:** AV-074; Crop Fact TR entry.

### UI Capture / UI Element
- **Definition:** Retaining menus, overflow controls, browser chrome, or interface elements in a finished explanatory graphic.
- **Role/domain:** Rendering; presentation.
- **Caution:** UI artifacts distract and may imply the graphic is an uncurated screenshot.
- **Identifiers:** AV-075; UI Element TR entry.

### Resolution Mismatch
- **Definition:** Using tiny type, thin lines, or dense labels in a raster image too small to preserve them.
- **Role/domain:** Rendering.
- **Caution:** Export size and resolution must match the detail being shown.
- **Identifiers:** AV-076.

### Unchecked Export
- **Definition:** Assuming a chart remains accurate after export, scaling, compression, or format conversion.
- **Role/domain:** Rendering; workflow.
- **Caution:** Re-audit exported outputs.
- **Identifiers:** AV-077.

## G. Fibonacci rectangles, squares, and spirals

### Fibonacci rectangle
- **Definition:** A rectangle assembled or discussed in relation to Fibonacci side lengths.
- **Role/domain:** Geometry.
- **Caution:** It is not automatically a golden rectangle.
- **Identifiers:** AV-078--AV-087; geometric TR entries.

### Golden Rectangle
- **Definition:** A rectangle whose width-to-height ratio is phi, subject to orientation and exact ratio specification.
- **Role/domain:** Geometry; ratio.
- **Caution:** Verify aspect ratio; visual resemblance is insufficient.
- **Identifiers:** Golden Rectangle TR entry; AV-078.

### Golden Claim
- **Definition:** Labeling a rectangle golden when its width-to-height ratio is not phi.
- **Role/domain:** Geometry error.
- **Caution:** Approximate Fibonacci rectangles may approach but are not necessarily exact golden rectangles.
- **Identifiers:** AV-078.

### Fibonacci Square
- **Definition:** A square tile in a Fibonacci construction whose side length follows the Fibonacci side-length series.
- **Role/domain:** Geometry.
- **Caution:** Width and height must be equal.
- **Identifiers:** Fibonacci Square TR entry; AV-079, AV-080, AV-085.

### Square Series
- **Definition:** The side-length series `1, 1, 2, 3, 5, 8, 13, ...` used for Fibonacci-square constructions.
- **Role/domain:** Geometry; recurrence.
- **Caution:** Wrong side lengths invalidate the construction.
- **Identifiers:** Square Series TR entry; AV-080.

### Non-Square Tiles
- **Definition:** Calling subdivisions Fibonacci squares when their width and height differ.
- **Role/domain:** Geometry error.
- **Caution:** Nonuniform resizing can turn squares into rectangles after construction.
- **Identifiers:** AV-079, AV-087.

### Quarter Arc
- **Definition:** A quarter-circle segment drawn inside a Fibonacci square with radius equal to that square's side length.
- **Role/domain:** Geometry; spiral construction.
- **Caution:** Radius and center must match the containing square.
- **Identifiers:** Quarter Arc TR entry; AV-081, AV-082.

### Arc Radius
- **Definition:** The radius of a spiral arc, required to equal the side length of its containing square in the Fibonacci-square construction.
- **Role/domain:** Geometry requirement.
- **Caution:** A mismatched radius breaks the construction.
- **Identifiers:** AV-081; Quarter Arc TR entry.

### Arc Center
- **Definition:** The required square corner from which a quarter-circle arc is drawn.
- **Role/domain:** Geometry requirement.
- **Caution:** Moving the center away from the correct corner invalidates the arc geometry.
- **Identifiers:** AV-082; Quarter Arc TR entry.

### Tangent Join / Broken Tangency
- **Definition:** Adjacent quarter-circle arcs should meet tangentially; broken tangency is failure to do so at shared square boundaries.
- **Role/domain:** Geometry; spiral construction.
- **Caution:** Smooth-looking arcs are not sufficient if centers, radii, or joins are wrong.
- **Identifiers:** Tangent Join TR entry; AV-083.

### Fibonacci Spiral
- **Definition:** In these documents, the piecewise quarter-circle spiral approximation built from Fibonacci squares.
- **Role/domain:** Geometry; visualization.
- **Caution:** Distinguish it from the exact logarithmic golden spiral.
- **Identifiers:** Fibonacci Spiral and Fibonacci spiral approximation TR entries; AV-084.

### Fibonacci spiral approximation
- **Definition:** The square-and-quarter-circle construction that resembles a spiral through discrete circular arcs.
- **Role/domain:** Geometry; construction.
- **Caution:** It is not the exact golden logarithmic spiral.
- **Identifiers:** Fibonacci spiral approximation TR entry; AV-084.

### Golden Spiral
- **Definition:** The exact logarithmic golden spiral, external to the piecewise Fibonacci-square approximation.
- **Role/domain:** Geometry; external mathematical context.
- **Caution:** Do not present a Fibonacci-square approximation as the exact logarithmic golden spiral.
- **Identifiers:** Golden Spiral TR entry; AV-084.

### Decorative Spiral
- **Definition:** A freehand or generic logarithmic-looking spiral presented as an exact Fibonacci-square construction.
- **Role/domain:** Geometry error; rendering.
- **Caution:** Visual resemblance alone does not establish mathematical correctness.
- **Identifiers:** AV-084.

### Unlabeled Tiles
- **Definition:** Omitting side-length or Fv labels from a quantitative geometric construction.
- **Role/domain:** Geometry; annotation error.
- **Caution:** Labels are needed when the construction claims Fibonacci quantities.
- **Identifiers:** AV-085.

### Recursive Misfit
- **Definition:** A tile arrangement whose next square is not attached along the side created by the previous rectangle.
- **Role/domain:** Geometry error.
- **Caution:** Preserve the recursive attachment pattern.
- **Identifiers:** AV-086.

### Resize Damage / Uniform Resize
- **Definition:** Resize damage is nonuniform stretching after construction; uniform resize preserves proportions.
- **Role/domain:** Rendering; geometry.
- **Caution:** Nonuniform stretching corrupts squares, circles, aspect ratios, and slopes.
- **Identifiers:** AV-087; Uniform Resize TR entry.

### Exact construction versus decorative resemblance
- **Definition:** The distinction between a construction satisfying side-length, square, arc, center, and tangency rules and one that merely looks Fibonacci-like.
- **Role/domain:** Geometry; audit.
- **Caution:** Resemblance is not mathematical verification.
- **Identifiers:** AV-078--AV-087; geometric TR entries.

## H. Explanation, annotation, and document integrity

### Legend Ambiguity
- **Definition:** A legend that names colors without defining the formula or data each color represents.
- **Role/domain:** Annotation error.
- **Caution:** Define datasets, formulas, and reference lines, not just colors.
- **Identifiers:** AV-088.

### Color Only
- **Definition:** Relying on color alone to distinguish quantities such as forward ratio, reciprocal ratio, phi, unity, or error.
- **Role/domain:** Accessibility; annotation error.
- **Caution:** Use labels, line styles, markers, or text in addition to color.
- **Identifiers:** AV-089.

### Missing Convention
- **Definition:** A standalone image lacking its indexing convention.
- **Role/domain:** Annotation error; indexing.
- **Caution:** Standalone Fibonacci graphics must state the convention they use.
- **Identifiers:** AV-090; TR-015.

### Missing Formula
- **Definition:** A ratio label without numerator and denominator definitions.
- **Role/domain:** Annotation error; ratio.
- **Caution:** State formulas such as `R_v = D_v/D_(v-1)`.
- **Identifiers:** AV-091; AV-009.

### Missing Destination
- **Definition:** An Fv label without its associated destination when the mapping is central.
- **Role/domain:** Annotation error; indexing.
- **Caution:** Use `Fv v -> destination D_v` when ambiguity is possible.
- **Identifiers:** AV-092; TR-015.

### Missing Prior
- **Definition:** A ratio annotation that omits the preceding destination used in the calculation.
- **Role/domain:** Annotation error; ratio.
- **Caution:** The denominator is essential for ratio direction.
- **Identifiers:** AV-093; TR-013.

### Unverified Copy
- **Definition:** Copying values from a prior image without checking them against the canonical sequence.
- **Role/domain:** Document integrity; audit.
- **Caution:** Use TR and REF values to verify copied content.
- **Identifiers:** AV-094; TR-016--TR-045; REF-001--REF-030.

### Panel Conflict
- **Definition:** Combining panels that disagree about counts, labels, ranges, scales, or step boundaries.
- **Role/domain:** Document integrity; visualization.
- **Caution:** Every panel, table, caption, and prose section must agree about convention and range.
- **Identifiers:** AV-095; Panel Consistency TR entry.

### Silent Correction
- **Definition:** Correcting a picture while leaving its accompanying table or prose unchanged.
- **Role/domain:** Document integrity error.
- **Caution:** Corrections must propagate across all representations.
- **Identifiers:** AV-096.

### Orphan Formula
- **Definition:** A formula placed far from the graph element it defines without a leader, caption, or matching symbol.
- **Role/domain:** Annotation error.
- **Caution:** Formulas should be visually tied to the data or reference line they define.
- **Identifiers:** AV-097.

### Overclaiming
- **Definition:** Stating that a chart proves more than its data, range, and resolution demonstrate.
- **Role/domain:** Explanation error; audit.
- **Caution:** Qualify claims according to evidence and resolution.
- **Identifiers:** AV-098.

### Aesthetic Override
- **Definition:** Prioritizing symmetry, smoothness, or balanced spacing over numerical fidelity.
- **Role/domain:** Visualization error; workflow.
- **Caution:** Beauty does not override arithmetic, scale, geometry, or labels.
- **Identifiers:** AV-099.

### Missing Audit
- **Definition:** Finalizing a multi-panel Fibonacci explanation without checking values, indexing, formulas, scales, labels, and rendering separately.
- **Role/domain:** Workflow error.
- **Caution:** Use the audit procedure before publishing or accepting complex graphics.
- **Identifiers:** AV-100.

## I. Image-specific observations and evidence boundaries

### Uploaded images / seven examined images
- **Definition:** The images whose properties were recorded in the Truth Inventory when the inventories were created.
- **Role/domain:** Image audit; document scope.
- **Caution:** Their observations are facts about those images only, not automatic judgments about new images.
- **Identifiers:** TR image-specific observation section.

### Image One: dark screenshot
- **Definition:** A previously examined dark screenshot associated with ratio recurrence, signed-error identity, asymptotic contraction, and conventional indexing display.
- **Role/domain:** Image-specific observation.
- **Caution:** Treat as image-specific and do not generalize without re-auditing a new image.
- **Identifiers:** Image One TR observations; AV-040, AV-039 by relevance.

### Image Two: white ratio infographic
- **Definition:** A previously examined infographic using an `F_0=1, F_1=1` convention with visible destination values and forward ratios corresponding to Fv 1 through Fv 16.
- **Role/domain:** Image-specific observation; indexing.
- **Caution:** Its convention differs from conventional `F_0=0, F_1=1`; conversion must be explicit.
- **Identifiers:** Image Two TR observations; AV-004, AV-013.

### Image Three: decorative dot panel
- **Definition:** A previously examined image containing early addition dot groups, stacked bars, a non-golden rectangle, and a lower-right oscillation panel.
- **Role/domain:** Image-specific observation; geometry; visualization.
- **Caution:** Decorative elements must still satisfy arithmetic and geometry before being treated as quantitative.
- **Identifiers:** Image Three TR observations; AV-017--AV-019, AV-078.

### Image Four: blue forward-ratio chart
- **Definition:** A previously examined chart using conventional `F_0=0, F_1=1` indexing, first point `F_2/F_1 = 1`, and an orange dashed reference.
- **Role/domain:** Image-specific observation; ratio chart.
- **Caution:** State conversion to Fv if analyzing under the repository convention.
- **Identifiers:** Image Four TR observations; AV-004, AV-050.

### Image Five: consecutive-number scatter points
- **Definition:** A previously examined plot of conventional pairs `(F_n, F_(n+1))` with final visible pair `(17711, 28657)`.
- **Role/domain:** Image-specific observation; pair plot.
- **Caution:** Pair order and progression must be labeled when meaningful.
- **Identifiers:** Image Five TR observations; AV-057, AV-058.

### Image Six: destination bar chart
- **Definition:** A previously examined destination bar chart displaying conventional `F_0=0` through `F_23=28657`.
- **Role/domain:** Image-specific observation; bar chart.
- **Caution:** Convert to Fv if comparing with repository steps.
- **Identifiers:** Image Six TR observations; AV-004, AV-059--AV-061.

### Image Seven: destination line chart
- **Definition:** A previously examined line chart with an omitted x-axis label 22, displayed label 23, 24 destinations, and 23 adjacent transitions.
- **Role/domain:** Image-specific observation; indexing; visualization.
- **Caution:** Missing labels and count ambiguity require careful audit.
- **Identifiers:** Image Seven TR observations; AV-008, AV-011.

### Independent re-audit requirement
- **Definition:** The requirement to inspect each new image independently against canonical truths and avoid categories.
- **Role/domain:** Image audit; workflow.
- **Caution:** Do not transfer judgments from one of the seven examined images to a different graphic.
- **Identifiers:** Boot-Up Primer guidance; AV-094, AV-098.

### No overgeneralization from image-specific statements
- **Definition:** The rule that verified statements about the seven examined images remain limited to those images.
- **Role/domain:** Image audit; document scope.
- **Caution:** New graphics require new evidence.
- **Identifiers:** TR image observation section; AV-098.

## J. Common raw-seed words used in the inventory sense

### Errors / discrepancies / failure modes
- **Definition:** Conditions that introduce wrong values, ambiguous indexing, visual distortion, explanatory confusion, rendering inaccuracy, or document-integrity problems.
- **Role/domain:** Error taxonomy.
- **Caution:** Classify them with AV identifiers when the inventory names the condition.
- **Identifiers:** AV-001--AV-100.

### Studying, drawing, charting, explaining
- **Definition:** The major activities governed by the inventories: learning Fibonacci facts, constructing diagrams, plotting data, and presenting prose explanations.
- **Role/domain:** Workflow; visualization; explanation.
- **Caution:** Each activity must preserve the same convention, values, ratios, limits, and evidence boundaries.
- **Identifiers:** AV-001--AV-100; TR-001--TR-163.

### Chart / caption / table / equation
- **Definition:** Representation forms that may carry Fibonacci data, labels, formulas, or explanatory context.
- **Role/domain:** Document integrity; visualization.
- **Caution:** They must agree with one another; correcting only one form creates silent correction or panel conflict.
- **Identifiers:** AV-004, AV-095, AV-096.

### Label
- **Definition:** Text identifying a step, value, axis, dataset, formula, reference line, tile, or panel.
- **Role/domain:** Annotation; visualization.
- **Caution:** Labels must not be duplicated, vague, missing, or inconsistent with the data.
- **Identifiers:** AV-011, AV-012, AV-049, AV-085, AV-088--AV-093.

### Terminology
- **Definition:** The controlled vocabulary distinguishing step, index, destination, value, ratio, transition, limit, and metaphor.
- **Role/domain:** Explanation; notation.
- **Caution:** Loose terminology is itself an avoid condition when it blurs required distinctions.
- **Identifiers:** AV-007; TR-001--TR-015.

### Mathematical error
- **Definition:** A departure from canonical arithmetic, formulas, ratios, limits, or exactness.
- **Role/domain:** Audit; recurrence; ratio.
- **Caution:** Even one value typo can contaminate downstream recurrence values.
- **Identifiers:** AV-016--AV-045.

### Indexing ambiguity
- **Definition:** Unclear or conflicting step/index labeling.
- **Role/domain:** Indexing; audit.
- **Caution:** Ambiguity can shift every value or ratio label.
- **Identifiers:** AV-001--AV-015.

### Visual distortion
- **Definition:** A graphical choice that misrepresents scale, continuity, geometry, or value relationships.
- **Role/domain:** Visualization; rendering.
- **Caution:** Distortion can occur even when source values are correct.
- **Identifiers:** AV-043, AV-046--AV-064, AV-071--AV-073, AV-087.

### Explanatory confusion
- **Definition:** Prose, labels, captions, or formulas that obscure the intended mathematical meaning.
- **Role/domain:** Explanation; annotation.
- **Caution:** Avoid conflating metaphor, theorem, finite approximation, and exact identity.
- **Identifiers:** AV-034, AV-088--AV-098.

### Rendering inaccuracy
- **Definition:** Error introduced by raster resolution, antialiasing, line width, crop, UI capture, scaling, compression, or export.
- **Role/domain:** Rendering.
- **Caution:** Rendered pixels are not automatically the source of mathematical truth.
- **Identifiers:** AV-066--AV-077.

### Numerical fidelity
- **Definition:** Faithful preservation of values, ratios, scales, and formulas from source data to representation.
- **Role/domain:** Audit; visualization.
- **Caution:** Do not sacrifice it to aesthetics, smoothness, or convenient spacing.
- **Identifiers:** AV-023, AV-066, AV-099.

### Visual responsibility
- **Definition:** The practice of designing graphics whose labels, scales, markers, rendering, and claims match the underlying mathematics.
- **Role/domain:** Visualization; workflow.
- **Caution:** It includes accessibility and auditability, not merely visual appeal.
- **Identifiers:** AV-046--AV-100; TR visualization facts.

### Clear labeling
- **Definition:** Explicit naming of indexing convention, axes, formulas, datasets, reference lines, destinations, and relevant units.
- **Role/domain:** Annotation; workflow.
- **Caution:** Color alone or unlabeled guides are insufficient.
- **Identifiers:** AV-049, AV-050, AV-088--AV-093.

### No silent convention change
- **Definition:** The rule that a change of indexing convention must be declared and converted explicitly.
- **Role/domain:** Indexing; workflow.
- **Caution:** Silent changes produce index drift and convention mixing.
- **Identifiers:** AV-001, AV-004, AV-013; TR-007.

### No unstated rule attribution
- **Definition:** The rule that claims not established by the inventories must not be presented as inventory-defined.
- **Role/domain:** Document integrity; external context.
- **Caution:** Label supplemental or external mathematical context clearly.
- **Identifiers:** Boot-Up Primer missing-information guidance; AV-098.

## Audit-use note

Use this glossary as a navigation aid alongside the governing documents. For correctness, check positive facts against the **Truth Inventory**, classify deviations with the **Avoids Inventory**, consult the **Detailed Description** for identifier namespaces and document organization, and use the **Comprehensive Report** for high-level synthesis and known limitations. In every audit, preserve the Fv convention, keep process steps distinct from destination values, maintain exact fractions and symbolic constants where exactness matters, mark rounded decimals as approximations, and avoid claiming that any finite Fibonacci ratio equals phi or `1/phi` exactly.
