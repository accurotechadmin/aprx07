# Secondary Fibonacci Boot Prompts

<!-- document-relations: header -->
> **Directly related documents:** [Cohesion Audit](Fibonacci_Cohesion_Audit.md) · [Glossary](Fibonacci_Glossary.md) · [Glossary Seed](Fibonacci_Glossary_Seed.md) · [Claim Index](Fibonacci_Statement_Claim_Index.md) · [README](README.md) · [Boot](boot.md) · [Curated Graphs](curated_fibonacci_insight_graphs.md) · [Drawing Guide](draw.md) · [Boot-Up Prompt](fibonacci_boot_up_full_prompt.md) · [Generation Lattice](fibonacci_generation_lattice.md) · [Orange Recommendations](fibonacci_orange_pressing_recommendations.md) · [Insight-Graph Suite](insightgraphsuite.md) · [Essences SSOT](the_essences.md).
<!-- /document-relations: header -->

## Purpose

This is a menu of recommended secondary boot prompts. These are not the full secondary documents themselves. They are named boot paths that a future session can fully enter **after** completing the primary boot in [boot.md](boot.md).

Use the second prompt pattern:

> finish booting with `[secondary boot name]`

A future curated secondary boot document may be created from any item below. Until those documents exist, the booting session should use the named path, read the listed sources, and state what working mode it has entered.


## Interactive boot UI prompt system

When a user says only **`boot`**, the booting session should complete the primary boot described in [boot.md](boot.md), then automatically open this secondary boot menu as an interactive UI prompt. The UI should be text-only, compact, and safe for plain chat clients.

### Boot menu behavior

1. Read the available secondary boot options from the **Recommended secondary boot list** below.
2. Present each option with a stable number, its short name, and a one-line purpose.
3. Accept either the number or the short name as the user's selection.
4. Show the selected option's recommended secondary actions before finalizing the boot path.
5. Accept zero, one, or several action selections by number or short action name.
6. Finish loading the selected secondary boot path and execute any selected secondary actions concurrently with final boot confirmation.
7. If the user gives a task instead of a menu selection, infer the smallest relevant boot path and state the inference before proceeding.

### Recommended prompt shape after primary boot

```text
Primary boot complete. Choose a secondary boot path:

1. truth-inventory-mathematician — exact values, recurrence, ratios, limits, proofs
2. avoid-auditor — indexing, ratio, rendering, geometry, and claim-error audit
...

Reply with a number, a short name, or a task description.
Optional: add actions after a plus sign, e.g. "3 + sketch-plan, cite-sources".
Controls: menu, actions <boot>, info <boot>, add option, edit option, add action, edit action, combine <a> + <b>, cancel.
```

### Selection grammar

- **Number:** `3` selects menu item 3.
- **Short name:** `graph-artist` or `graph-artist.boot.md` selects the same path.
- **With actions:** `3 + sketch-plan, cite-sources` selects a path and secondary actions.
- **Combination:** `combine graph-artist + svg-drawing-engine` loads both paths, unless the task would be better served by choosing only one.
- **Task inference:** `I need to audit a shell spiral claim` routes to the minimum relevant path, usually `empirical-claim-skeptic.boot.md` plus `spiral-geometry.boot.md` if geometry is central.

### Basic UI controls

These controls are prompt-level controls for future sessions and for maintainers editing this document:

| Control | Effect | Safety rule |
|---|---|---|
| `menu` | Reprint the numbered secondary boot list. | Do not reread all source documents merely to reprint the menu. |
| `actions <boot>` | Show the secondary actions available for one boot path. | If the boot name is ambiguous, ask for clarification. |
| `info <boot>` | Show purpose, required sources, and suggested actions for one boot path. | Summarize; do not perform the boot unless the user confirms. |
| `combine <a> + <b>` | Load two complementary boot paths. | Prefer at most two boot paths at first. |
| `add option` | Draft a new secondary boot option with name, purpose, sources, actions, and link-index updates. | Ask for missing required fields before editing the repository. |
| `edit option <boot>` | Draft or apply changes to an existing boot option. | Preserve stable names unless the user explicitly asks to rename. |
| `add action <boot>` | Draft a new reusable secondary action for a boot path. | Keep actions modular and safe to run during boot. |
| `edit action <boot>:<action>` | Draft or apply changes to an existing action. | Preserve action short names unless explicitly asked to rename. |
| `cancel` | Stop the interactive secondary selection flow. | Keep primary boot state loaded. |

## Secondary action model

Secondary actions are optional boot-time shortcuts. They are not separate boot paths. They are modular actions that can run concurrently with finishing a secondary boot so a user does not need a third prompt for common setup work.

Each action should have:

- a short kebab-case name;
- a one-line effect;
- whether it is read-only, draft-only, or can modify repository files;
- the output it should produce at boot completion;
- any extra source documents it needs.

Default safety rule: unless the user clearly authorizes repository edits, secondary actions should prepare plans, checklists, outlines, or reading queues rather than modifying files.

## Secondary actions by boot path

| Secondary boot name | Suggested boot-time actions |
|---|---|
| `truth-inventory-mathematician.boot.md` | `formula-sheet` — summarize active formulas; `index-convert` — prepare Fv/conventional conversion notes; `proof-mode` — enable proof-first response framing; `edge-cases` — list exactness and finite-ratio cautions. |
| `avoid-auditor.boot.md` | `audit-checklist` — prepare common error checklist; `claim-risk-map` — rank likely failure modes; `source-trace` — prepare source citation map; `red-team` — respond adversarially before proposing fixes. |
| `graph-artist.boot.md` | `sketch-plan` — propose 2–5 visual concepts; `question-first` — force each graph to answer a stated question; `aesthetic-variants` — prepare restrained, vivid, and minimalist variants; `label-audit` — precheck title, axes, legend, and caveats. |
| `svg-drawing-engine.boot.md` | `canvas-spec` — define dimensions and coordinate system; `export-check` — prepare SVG validation checklist; `accessibility-pass` — plan title/description/contrast labels; `reuse-assets` — inspect existing drawings before creating new ones. |
| `spiral-geometry.boot.md` | `square-layout` — set up square and arc constraints; `golden-comparison` — separate Fibonacci spiral approximation from logarithmic golden spiral; `geometry-audit` — check centers, radii, tangency, and scaling; `claim-caveats` — prepare geometry limitation notes. |
| `normalized-time-metaphor.boot.md` | `metaphor-badge` — state metaphor status and normalized quantity; `asymmetry-note` — include interval asymmetry; `concept-map` — draft planning/salience/memory axes; `caveat-card` — list what the metaphor does not prove. |
| `document-indexer.boot.md` | `link-audit` — check bidirectional links; `catalog-row` — prepare catalogue metadata; `source-hierarchy-map` — summarize authority relationships; `staleness-check` — identify likely stale index entries. |
| `claim-traceability.boot.md` | `claim-table` — prepare claim/source/status columns; `contradiction-scan` — look for tension across documents; `citation-pack` — collect relevant citations; `open-questions` — list unresolved claims. |
| `glossary-terminologist.boot.md` | `term-card` — create definition/source/usage cards; `namespace-check` — preserve identifier namespaces; `synonym-merge` — identify duplicate terms; `definition-audit` — separate claims from vocabulary. |
| `orange-pressing-expander.boot.md` | `branch-map` — generate expansion branches; `artifact-list` — propose documents, graphs, datasets, and lessons; `priority-sort` — rank expansions by value; `return-to-core` — map creative ideas back to exactness. |
| `generation-lattice-planner.boot.md` | `lattice-position` — place work on horizontal/vertical lattice; `next-three` — propose next three artifacts; `dependency-map` — list prerequisites; `manifest-draft` — draft JSON/Markdown updates. |
| `empirical-claim-skeptic.boot.md` | `rival-models` — list non-Fibonacci explanations; `evidence-grid` — separate resemblance, correlation, mechanism, and proof; `sample-check` — ask sample-size and measurement questions; `claim-softener` — rewrite overclaims safely. |
| `spreadsheet-data.boot.md` | `range-declare` — state canonical vs extended range; `column-map` — map spreadsheet columns to terms; `recompute-check` — plan formula validation; `export-plan` — define CSV/table outputs. |
| `teacher-lesson-builder.boot.md` | `lesson-outline` — draft staged lesson arc; `misconception-list` — prepare learner-safe warnings; `exercise-set` — create practice prompts; `reveal-sequence` — sequence examples from concrete to abstract. |
| `repository-curator.boot.md` | `maintenance-plan` — identify add/archive/normalize work; `relation-update` — prepare link-index edits; `canon-check` — verify source hierarchy compliance; `release-notes` — draft summary of repository changes. |

## Recommended secondary boot list

| Secondary boot name | Best for | Required repository sources to read next |
|---|---|---|
| `truth-inventory-mathematician.boot.md` | Exact Fibonacci values, recurrence, ratios, limits, proofs, convention conversions, and finite/exact distinction. | [02_Fibonacci_Truth_Inventory.docx](02_Fibonacci_Truth_Inventory.docx), [01_Fibonacci_Avoids_and_Error_Inventory.docx](01_Fibonacci_Avoids_and_Error_Inventory.docx), [Fibonacci_Glossary.md](Fibonacci_Glossary.md), [Fibonacci_Cohesion_Audit.md](Fibonacci_Cohesion_Audit.md) |
| `avoid-auditor.boot.md` | Finding indexing errors, ratio reversals, rendering mistakes, geometry problems, weak claims, and document-integrity failures. | [01_Fibonacci_Avoids_and_Error_Inventory.docx](01_Fibonacci_Avoids_and_Error_Inventory.docx), [02_Fibonacci_Truth_Inventory.docx](02_Fibonacci_Truth_Inventory.docx), [Fibonacci_Cohesion_Audit.md](Fibonacci_Cohesion_Audit.md), [Fibonacci_Statement_Claim_Index.md](Fibonacci_Statement_Claim_Index.md) |
| `graph-artist.boot.md` | Selecting meaningful visualizations, generating graph concepts, designing SVGs, and balancing truth with aesthetics. | [insightgraphsuite.md](insightgraphsuite.md), [curated_fibonacci_insight_graphs.md](curated_fibonacci_insight_graphs.md), [draw.md](draw.md), [fibonacci_generation_lattice.md](fibonacci_generation_lattice.md) |
| `svg-drawing-engine.boot.md` | Creating precise repository-quality SVG diagrams, plots, spirals, and visual-proof assets. | [draw.md](draw.md), [insightgraphsuite.md](insightgraphsuite.md), [curated_fibonacci_insight_graphs.md](curated_fibonacci_insight_graphs.md), existing files in [drawings/](drawings/) |
| `spiral-geometry.boot.md` | Fibonacci square layouts, quarter-circle spirals, golden rectangles, geometry audits, and golden-spiral comparisons. | [02_Fibonacci_Truth_Inventory.docx](02_Fibonacci_Truth_Inventory.docx), [01_Fibonacci_Avoids_and_Error_Inventory.docx](01_Fibonacci_Avoids_and_Error_Inventory.docx), [draw.md](draw.md), [insightgraphsuite.md](insightgraphsuite.md) |
| `normalized-time-metaphor.boot.md` | Yesterday/today/tomorrow metaphor, reciprocal time, planning horizons, salience, memory, anticipation, and caveat-rich conceptual graphics. | [the_essences.md](the_essences.md), [insightgraphsuite.md](insightgraphsuite.md), [fibonacci_generation_lattice.md](fibonacci_generation_lattice.md), [fibonacci_orange_pressing_recommendations.md](fibonacci_orange_pressing_recommendations.md) |
| `document-indexer.boot.md` | Cataloguing documents, building indexes, adding bidirectional cross-links, maintaining source hierarchy, and preparing master catalogue work. | [README.md](README.md), [Fibonacci_Statement_Claim_Index.md](Fibonacci_Statement_Claim_Index.md), [Fibonacci_Cohesion_Audit.md](Fibonacci_Cohesion_Audit.md), [the_essences.md](the_essences.md) |
| `claim-traceability.boot.md` | Tracing claims across documents, locating contradictions, mapping statements, and building audit reports. | [Fibonacci_Statement_Claim_Index.md](Fibonacci_Statement_Claim_Index.md), [Fibonacci_Cohesion_Audit.md](Fibonacci_Cohesion_Audit.md), [02_Fibonacci_Truth_Inventory.docx](02_Fibonacci_Truth_Inventory.docx), [01_Fibonacci_Avoids_and_Error_Inventory.docx](01_Fibonacci_Avoids_and_Error_Inventory.docx) |
| `glossary-terminologist.boot.md` | Defining terms, cleaning vocabulary, separating supplemental terms from inventory claims, and preserving stable identifier namespaces. | [Fibonacci_Glossary.md](Fibonacci_Glossary.md), [Fibonacci_Glossary_Seed.md](Fibonacci_Glossary_Seed.md), [03_Fibonacci_Inventory_Documents_Detailed_Description.docx](03_Fibonacci_Inventory_Documents_Detailed_Description.docx), [the_essences.md](the_essences.md) |
| `orange-pressing-expander.boot.md` | Expanding small insights into families of documents, graphs, data manifests, workbooks, lessons, and future creative branches. | [fibonacci_orange_pressing_recommendations.md](fibonacci_orange_pressing_recommendations.md), [fibonacci_generation_lattice.md](fibonacci_generation_lattice.md), [insightgraphsuite.md](insightgraphsuite.md), [draw.md](draw.md) |
| `generation-lattice-planner.boot.md` | Planning next documents and figures by horizontal topic family and vertical development level. | [fibonacci_generation_lattice.md](fibonacci_generation_lattice.md), [fibonacci_generation_lattice.json](fibonacci_generation_lattice.json), [curated_fibonacci_insight_graphs.md](curated_fibonacci_insight_graphs.md), [fibonacci_orange_pressing_recommendations.md](fibonacci_orange_pressing_recommendations.md) |
| `empirical-claim-skeptic.boot.md` | Auditing claims about nature, shells, bodies, markets, architecture, behavior, and art without overclaiming Fibonacci mechanisms. | [02_Fibonacci_Truth_Inventory.docx](02_Fibonacci_Truth_Inventory.docx), [01_Fibonacci_Avoids_and_Error_Inventory.docx](01_Fibonacci_Avoids_and_Error_Inventory.docx), [insightgraphsuite.md](insightgraphsuite.md), [the_essences.md](the_essences.md) |
| `spreadsheet-data.boot.md` | Working with extended tables, first-100-step ratios, canonical-vs-extended ranges, and workbook-derived calculations. | [fibonacci_first_100_with_ratios.xlsx](fibonacci_first_100_with_ratios.xlsx), [02_Fibonacci_Truth_Inventory.docx](02_Fibonacci_Truth_Inventory.docx), [the_essences.md](the_essences.md), [Fibonacci_Glossary.md](Fibonacci_Glossary.md) |
| `teacher-lesson-builder.boot.md` | Turning Fibonacci concepts into lessons, staged reveals, learner-safe diagrams, prompts, and exercises. | [boot.md](boot.md), [Fibonacci_Glossary.md](Fibonacci_Glossary.md), [insightgraphsuite.md](insightgraphsuite.md), [fibonacci_orange_pressing_recommendations.md](fibonacci_orange_pressing_recommendations.md) |
| `repository-curator.boot.md` | Maintaining the repository as a living canon, deciding what to add, archive, normalize, denormalize, or cross-link next. | [README.md](README.md), [the_essences.md](the_essences.md), [Fibonacci_Cohesion_Audit.md](Fibonacci_Cohesion_Audit.md), [secondary_boot_prompts.md](secondary_boot_prompts.md) |

## Selection rule

Choose the smallest secondary boot that covers the task. If a task spans domains, combine at most two boot paths at first, then add more only when a concrete need appears.

Examples:

- For a new SVG: combine `graph-artist.boot.md` and `svg-drawing-engine.boot.md`.
- For a claim audit of a shell image: combine `empirical-claim-skeptic.boot.md` and `spiral-geometry.boot.md`.
- For a master catalogue: start with `document-indexer.boot.md`, then add `claim-traceability.boot.md` if statement-level mapping is required.
- For a philosophical time diagram: combine `normalized-time-metaphor.boot.md` and `graph-artist.boot.md`.

## Naming convention for future secondary boot documents

When a listed prompt becomes a real file, use lowercase kebab-case and the suffix `.boot.md`, for example:

- `graph-artist.boot.md`
- `document-indexer.boot.md`
- `truth-inventory-mathematician.boot.md`

Each future secondary boot document should include:

1. its purpose;
2. when to use it;
3. required reading order;
4. required formulas, cautions, and vocabulary;
5. expected output behavior;
6. links back to [boot.md](boot.md), [README.md](README.md), and this menu.

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
- [Fibonacci Insight-Graph Suite: Authoritative Boot-Up Primer](insightgraphsuite.md)
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
- [Fibonacci Insight-Graph Suite: Authoritative Boot-Up Primer](insightgraphsuite.md)
- [The Essences: Canon / SSOT for Fibonacci Boot-Up Prompts](the_essences.md)
<!-- /document-relations: footer -->
