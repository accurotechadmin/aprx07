# Fibonacci Insight-Graph Suite: Authoritative Boot-Up Primer

<!-- document-relations: header -->
> **Directly related documents:** [Cohesion Audit](Fibonacci_Cohesion_Audit.md) · [Glossary](Fibonacci_Glossary.md) · [Glossary Seed](Fibonacci_Glossary_Seed.md) · [Claim Index](Fibonacci_Statement_Claim_Index.md) · [README](README.md) · [Boot](boot.md) · [Curated Graphs](curated_fibonacci_insight_graphs.md) · [Drawing Guide](draw.md) · [Boot-Up Prompt](fibonacci_boot_up_full_prompt.md) · [Generation Lattice](fibonacci_generation_lattice.md) · [Orange Recommendations](fibonacci_orange_pressing_recommendations.md) · [Secondary Boots](secondary_boot_prompts.md) · [Essences SSOT](the_essences.md).
<!-- /document-relations: header -->


This primer is the governing start-of-session instrument for work that uses this repository to create, audit, explain, or reorganize Fibonacci-related graphs, diagrams, maps, visual proofs, metadata structures, application studies, and interpretive time models.

Its purpose is threefold:

1. **Orientation:** establish the repository's Fibonacci convention, source hierarchy, vocabulary, and truth/avoidance discipline before any substantive output is produced.
2. **Selection:** guide the choice, adaptation, combination, or invention of visualizations according to insight, not novelty or convenience.
3. **Protection:** preserve mathematical accuracy, evidence boundaries, and interpretive humility when moving from exact Fibonacci facts into geometry, real-world claims, metaphor, design, metadata, or time.

The companion graph list, [`curated_fibonacci_insight_graphs.md`](curated_fibonacci_insight_graphs.md), is the authoritative curated reference for this suite, but it is not a closed canon. It records durable visualization concepts that have earned a place in the working language of the project. Future work may select from it, refine it, add to it, or reject a listed option when another representation serves truth more clearly.

## 1. Required repository orientation

Before drawing graphs, rewriting Fibonacci documents, interpreting images, making claims, or extending the suite, treat the repository as a unified reference system.

Read and use the documents in this order of authority:

1. **Fibonacci Truth Inventory** — the primary positive standard for canonical values, formulas, definitions, limits, visualization facts, geometric facts, and verified observations.
2. **Fibonacci Avoids and Error Inventory** — the diagnostic standard for named errors, ambiguities, distortions, and failure modes.
3. **Detailed Description of the Fibonacci Inventory Documents** — the crosswalk explaining the inventories' structure, identifiers, typography, and internal relationships.
4. **Comprehensive Report on the Fibonacci Inventory Documents** — supplemental synthesis of the document system.
5. **Fibonacci Inventory Glossary** and **Fibonacci Glossary Seed** — vocabulary aids and provenance material; useful, but not replacements for the governing inventories.
6. **Fibonacci Insight-Graph Suite** — the living visualization language governed by the standards above.

Do not treat these files as unrelated notes. They are reference study material for a single disciplined project: to make Fibonacci truth visible without collapsing exact mathematics, approximation, empirical evidence, and metaphor into one another.

## 2. Governing Fv convention

Use the repository's Fv process-step convention unless a task explicitly declares and converts another system:

* **Fv -1 -> destination 0**
* **Fv 0 -> destination 1**
* **Fv 1 -> destination 1**
* every later destination is obtained by adding the two immediately preceding destinations.

Let **Fv v** denote the process step and **D_v** denote the destination value at that step. Under conventional Fibonacci indexing beginning with `F_0 = 0` and `F_1 = 1`, the conversion is:

`D_v = F_(v+1)`.

Always distinguish:

* process step;
* destination value;
* conventional Fibonacci index;
* transition between adjacent destinations;
* forward ratio `R_v = D_v / D_(v-1)`;
* reciprocal ratio `Q_v = D_(v-1) / D_v`;
* exact value, rounded decimal, limiting value, and metaphorical label.

The duplicate destination `1` at Fv 0 and Fv 1 is intentional. The zero at Fv -1 is part of the stated convention. Do not silently omit, merge, relabel, or re-index these seeds.

## 3. Intuitive definitions and explanatory vocabulary

Use the following plain-language vocabulary when rewriting documents or explaining graphs. These definitions do not replace the inventories; they make their terms easier to apply consistently.

* **Boot-up primer:** the start-of-session instruction layer. It tells the reader how to enter the work, which documents govern truth, and how to avoid common reasoning errors before producing output.
* **Truth standard:** the positive reference layer. It says what is established: canonical destinations, formulas, limits, ratios, geometry facts, visualization principles, and scoped observations.
* **Avoid standard:** the diagnostic reference layer. It names what can go wrong: index drift, zero omission, finite-ratio exactness errors, visual distortion, unsupported real-world claims, and other failure modes.
* **Crosswalk:** the document layer that explains how identifiers, sections, labels, and companion documents relate to one another.
* **Process step:** the named position in the recurrence process, written as Fv v. It is the address of a value, not the value itself.
* **Destination:** the value reached at a process step, written as `D_v`. For example, Fv 4 is the process step and destination 5 is the value reached there.
* **Seed:** an initial destination required to determine the recurrence. In this repository the displayed seed structure includes Fv -1, Fv 0, and Fv 1 so the zero and duplicate one remain visible.
* **Transition:** the movement from one destination to the next. A range with 30 destinations has 29 adjacent transitions.
* **Forward ratio:** the adjacent quotient `R_v = D_v / D_(v-1)`, defined only where the prior destination is positive under the stated convention. It approaches φ but never equals φ at any finite Fibonacci step.
* **Reciprocal ratio:** the adjacent quotient `Q_v = D_(v-1) / D_v`. It approaches `1/φ` but never equals `1/φ` at any finite Fibonacci step.
* **Limit:** the value approached by a sequence of ratios or errors. A limit can be exact even when every finite plotted point is only an approximation to it.
* **Approximation:** a rounded, measured, finite, or model-dependent value. Approximation is useful when marked honestly; it becomes an error when presented as exact identity.
* **Metaphor:** a symbolic mapping that helps interpretation but does not by itself prove a theorem, physical law, biological mechanism, market rule, or prediction.
* **Evidence boundary:** the line between what the repository establishes, what a graph calculates, what a measurement suggests, and what a metaphor invites the viewer to imagine.
* **Insight graph:** a visualization that reveals structure: recurrence, dependency, convergence, error, scaling, symmetry, invariance, fit quality, or interpretive contrast. A merely decorative plot is not an insight graph.
* **Graph candidate:** a proposed visualization from the curated list or a newly invented one. It becomes useful only when it answers the task's actual question better than simpler alternatives.
* **Reference value:** a marked value such as 0, 1, φ, `1/φ`, an asymptote, a canonical destination, or a competing model line. Reference values must be labeled by role.
* **Residual:** what remains after comparing an observation or finite value to a reference model. Residuals are often better evidence than visual resemblance.
* **Depth balance:** the editorial rule that comparable topics should receive comparable explanatory treatment unless their roles differ.


## Fibonacci range horizons

When a Fibonacci sequence is shown as more than a very small example, prefer the repository's three explicit horizons: **near steps 1-8**, **mid steps 1-30**, and **far steps 1-100**. Near views serve introduction and recurrence visibility; mid views serve canonical/reference completeness and must state whether they use `Fv -1` through `Fv 28` or converted conventional steps; far views serve extended convergence, scale, and late-ratio/error analysis. If a different range is chosen, label it and explain why.

## 4. What the graph suite is for

The suite exists to help a viewer discover structure that prose or raw tables can hide. Use it to reveal:

* recurrence and known-from-known dependency;
* additive structure and source-pair contribution;
* growth, scaling, and near-exponential behavior;
* convergence toward `φ = (1 + sqrt(5)) / 2`;
* reciprocal relationships approaching `1/φ = φ - 1`;
* alternating signed error and shrinking absolute error;
* exact Fibonacci, Lucas, matrix, modular, combinatorial, and geometric identities;
* differences between linear, logarithmic, normalized, and transformed views;
* the boundary between mathematical fact and real-world resemblance;
* how metadata, document systems, and derived records can mirror recurrence;
* symbolic or interpretive uses of Fibonacci structure, including the normalized time model.

A graph is justified when it clarifies a real question. A graph is not justified merely because numbers can be plotted.

## 5. Selection standard

For each task, identify the smallest set of visualizations that exposes the necessary structure.

Prefer a visualization when it:

* exposes a governing relation rather than only displaying values;
* makes recurrence, scale, convergence, symmetry, error, invariance, or transformation visible;
* shows why a relationship occurs, not only that it occurs;
* makes exact facts visibly separable from approximations and metaphors;
* supports comparison between competing explanations;
* reduces conceptual difficulty without hiding necessary precision;
* remains readable without decorative clutter;
* can be checked against the repository's canonical values and avoid conditions.

Avoid:

* redundant chart variants that add no new insight;
* smooth curves that imply nonexistent intermediate Fibonacci states;
* unlabeled axes, ambiguous units, or mixed scales;
* unmarked rounding or finite ratios labeled as exact `φ`;
* real-world Fibonacci claims without alternatives, uncertainty, residuals, sample size, or evidence boundaries;
* novelty that weakens truth.

## 6. Creative authority and duty

You are authorized to invent new visualizations when the curated list does not serve the question precisely.

A new suite candidate must include:

* a concise and distinctive name;
* the central question it answers;
* the variables, structures, or objects it uses;
* the recommended visual form;
* the mathematical, empirical, metadata, geometric, or metaphorical insight it reveals;
* the interpretation warnings required to keep it truthful;
* its proposed category within the suite.

Additions should earn their place by revealing a genuinely different structure. Renaming an existing chart or changing only cosmetic style is not enough.

## 7. Mathematical discipline

Maintain the distinction among:

* exact identities;
* recurrence-generated consequences;
* asymptotic limits;
* numerical approximations;
* empirical measurements;
* statistical correlations;
* visual resemblance;
* historical claims;
* design conventions;
* speculative interpretations;
* symbolic or metaphorical models.

When working with plants, shells, bodies, markets, architecture, art, time, behavior, or any measured system, do not infer a Fibonacci mechanism from visual resemblance or numerical nearness alone. Test against alternatives where possible: non-Fibonacci models, nearby ratios, other logarithmic spirals, measured residuals, uncertainty, and sample size.

The correct question is not, "Can Fibonacci be seen here?" The correct question is, "What claim is being made, what evidence would distinguish it from alternatives, and what kind of truth does the evidence support?"

## 8. Known-from-known framing

A recurring philosophical theme of this project is that later Fibonacci destinations are already implicit once the seeds and recurrence rule are fixed.

Use this carefully. In the exact Fibonacci recurrence, future terms are determined by the present rule and prior destinations. A visualization may therefore show how an apparently unknown later structure is encoded in known constraints, transformations, ratios, or dependencies.

Do not generalize that mathematical determinism into a claim that all real events are predetermined, predictable, or caused by Fibonacci structure. Separate recurrence inevitability from physical causation, forecasting, metaphysics, and metaphor.

A central guiding question is:

> What future structure is already implicit in the present rule, state, ratio, boundary, or normalization?

## 9. Normalized time metaphor

When using the suite's normalized time model, define it explicitly as an interpretive coordinate system unless the task supplies a formal model.

Use these reference values:

* **yesterday = `1/φ ≈ 0.618033988750`**
* **today = `1`**
* **tomorrow = `φ ≈ 1.618033988750`**

Make clear what is being normalized and what distance means: duration, scale, influence, memory, anticipation, salience, probability, information, uncertainty, or another defined quantity.

Do not imply that yesterday, today, and tomorrow are equally spaced on a linear axis. Their distances from today are asymmetric:

* `1 - 1/φ = 1/φ²`
* `φ - 1 = 1/φ`
* `(φ - 1) / (1 - 1/φ) = φ`

Useful time-metaphor visualizations may explore reciprocal mirroring, multiplicative scaling, nested horizons, present-centered normalization, memory decay, anticipatory growth, alternate observers, uncertainty fields, or the distinction between chronological time and conceptual time. These are metaphors unless separately justified.

## 10. Required response behavior for future work

For every new Fibonacci graphing, writing, or auditing task:

1. identify the underlying question;
2. classify the domain: exact mathematics, geometry, empirical evidence, metadata, application, metaphor, or a combination;
3. fix the Fv convention or explicitly convert any alternate indexing;
4. consult the curated suite for relevant candidates;
5. select, adapt, combine, or invent the smallest useful set of visualizations;
6. define axes, encodings, variables, transformations, units, and reference values;
7. state what the viewer should discover;
8. cite or name the governing truth and avoid principles when relevant;
9. identify limitations, assumptions, rounding, evidence gaps, and interpretive hazards;
10. preserve clarity, exactness, and humility in the final explanation.

Precision in the first definitions matters. Small indexing errors, rounded-equality errors, visual distortions, and metaphor/fact substitutions compound into larger falsehoods. Therefore every graph and every rewritten Fibonacci document must begin from the repository's canonical convention, make its truth-status explicit, and remain faithful to what is actually established.

## 11. Document-depth consistency

Keep the repository's documents balanced in depth. If one topic receives a definition, convention, variables, visual form, insight statement, and interpretation warning, then comparable topics should receive comparable treatment unless there is a stated reason for shorter coverage. A document should not feel unfinished because adjacent subjects were developed unevenly.

Use extraordinary length only when the document's role requires it: inventories, detailed audits, comprehensive reports, or canon-forming reference material. Shorter working documents should still be complete within their scope: they should state purpose, authority, assumptions, method, outputs, limitations, and update rules.

## 12. Status of the curated list

The companion curated list is:

* authoritative as a curated working reference;
* expandable when a new visualization earns its place;
* revisable when precision, clarity, or evidence improves;
* nonexclusive and not a mandatory checklist;
* subordinate to the repository's truth and avoid standards;
* intended for selection, combination, critique, and invention.

Its purpose is not to predetermine every future drawing. Its purpose is to make strong ideas immediately available while preserving the freedom and responsibility to discover better ones.
---

<!-- document-relations: footer -->
## Document link index

### Documents this document links to
- [Fibonacci Inventory Cohesion Audit](Fibonacci_Cohesion_Audit.md)
- [Fibonacci Inventory Glossary](Fibonacci_Glossary.md)
- [Fibonacci Glossary Seed — Raw Vocabulary and Fresh-Session Prompt](Fibonacci_Glossary_Seed.md)
- [Fibonacci Documentation Statement and Claim Index](Fibonacci_Statement_Claim_Index.md)
- [Fibonacci Explorer Repository](README.md)
- [Boot Prompt for Fibonacci Explorers, Mathematicians, and Artists](boot.md)
- [Curated Fibonacci Insight Graphs](curated_fibonacci_insight_graphs.md)
- [Expert Fibonacci Graph-Drawing Guide](draw.md)
- [Full Fibonacci Repository Boot-Up Prompt](fibonacci_boot_up_full_prompt.md)
- [Fibonacci Generation Lattice: Recommended Graphs, Figures, and Documents](fibonacci_generation_lattice.md)
- [Fibonacci Orange-Pressing Recommendations](fibonacci_orange_pressing_recommendations.md)
- [Secondary Fibonacci Boot Prompts](secondary_boot_prompts.md)
- [The Essences: Canon / SSOT for Fibonacci Boot-Up Prompts](the_essences.md)

### Documents that link to this document
- [Fibonacci Inventory Cohesion Audit](Fibonacci_Cohesion_Audit.md)
- [Fibonacci Inventory Glossary](Fibonacci_Glossary.md)
- [Fibonacci Glossary Seed — Raw Vocabulary and Fresh-Session Prompt](Fibonacci_Glossary_Seed.md)
- [Fibonacci Documentation Statement and Claim Index](Fibonacci_Statement_Claim_Index.md)
- [Fibonacci Explorer Repository](README.md)
- [Boot Prompt for Fibonacci Explorers, Mathematicians, and Artists](boot.md)
- [Curated Fibonacci Insight Graphs](curated_fibonacci_insight_graphs.md)
- [Expert Fibonacci Graph-Drawing Guide](draw.md)
- [Full Fibonacci Repository Boot-Up Prompt](fibonacci_boot_up_full_prompt.md)
- [Fibonacci Generation Lattice: Recommended Graphs, Figures, and Documents](fibonacci_generation_lattice.md)
- [Fibonacci Orange-Pressing Recommendations](fibonacci_orange_pressing_recommendations.md)
- [Secondary Fibonacci Boot Prompts](secondary_boot_prompts.md)
- [The Essences: Canon / SSOT for Fibonacci Boot-Up Prompts](the_essences.md)
<!-- /document-relations: footer -->

