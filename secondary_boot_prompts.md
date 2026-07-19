# Secondary Fibonacci Boot Prompts

<!-- document-relations: header -->
> **Directly related documents:** [Cohesion Audit](Fibonacci_Cohesion_Audit.md) · [Glossary](Fibonacci_Glossary.md) · [Glossary Seed](Fibonacci_Glossary_Seed.md) · [Claim Index](Fibonacci_Statement_Claim_Index.md) · [README](README.md) · [Boot](boot.md) · [Curated Graphs](curated_fibonacci_insight_graphs.md) · [Drawing Guide](draw.md) · [Boot-Up Prompt](fibonacci_boot_up_full_prompt.md) · [Generation Lattice](fibonacci_generation_lattice.md) · [Orange Recommendations](fibonacci_orange_pressing_recommendations.md) · [Insight-Graph Suite](insightgraphsuite.md) · [Essences SSOT](the_essences.md).
<!-- /document-relations: header -->

## Purpose

This is a menu of recommended secondary boot prompts. The listed boot paths now have maintenance-ready `.boot.md` documents that a future session can fully enter **after** completing the primary boot in [boot.md](boot.md).

Use the second prompt pattern:

> finish booting with `[secondary boot name]`

Each linked secondary boot document is normalized to a maintenance-ready level: purpose, use case, reading order, above-the-fold UI, operating rules, actionable workflow, source-inspection guidance, validation expectations, boot-time actions with edit-risk labels, response contract, and first-pass checklist. Future revisions may deepen domain-specific controls, but the current files work as real secondary boot documents.


## Biblical-theological ethos note

This document should be read with the repository's sparse but governing biblical-theological ethos in view: the first Fibonacci `1` may serve, in metaphor, as witness to God before creation, while the second `1` is not the world but the world's receiving-end view of the same God as Creator and Sustainer, the first known touchpoint of His breath. Recurrence then becomes a practical handle for how created processes begin, differentiate, carry memory, correct tension, and seek faithful return toward unity. Keep this ethos present without letting it override exact mathematics, source hierarchy, Scripture, or evidence-boundary cautions.

## Interactive boot UI prompt system

When a user says only **`boot`**, the booting session should complete the primary boot described in [boot.md](boot.md), then automatically open this secondary boot menu as an interactive UI prompt. The UI should be text-only, compact, friendly, visually consistent, and safe for plain chat clients. It should feel like a warm 80s terminal rather than a noisy dashboard: clear boxes, stable prompt markers, small decorative accents, and no interface chrome.

### Boot menu behavior

1. Read the available secondary boot options from the **Recommended secondary boot list** below.
2. Present each option with a stable number, its short name, and a one-line purpose.
3. Accept either the number or the short name as the user's selection.
4. Show the selected option's recommended secondary actions before finalizing the boot path.
5. Accept zero, one, or several action selections by number or short action name.
6. Finish loading the selected secondary boot path and execute any selected secondary actions concurrently with final boot confirmation.
7. If the user gives a task instead of a menu selection, infer the smallest relevant boot path and state the inference before proceeding.

### Recommended prompt shape after primary boot

The secondary-choice UI should use one shared visual language across primary boot, the secondary menu, and every individual `.boot.md` display. Keep it readable before it is decorative: boxed headers, `>` prompt markers, bracketed numbers, uppercase boot titles, lower-contrast `feature:` and `actions:` rows, and a small recurring grove/tree accent that is explicitly decorative.

```text
╔════════════════════════════════════════════════════════════════════════╗
║ FIBONACCI EXPLORER // SECONDARY BOOT MENU                              ║
║ SELECT MODE: FRIENDLY CRT                                              ║
╠════════════════════════════════════════════════════════════════════════╣
> signal: primary boot complete / choose the smallest useful mode
> input: number | short-name | task description | combine <a> + <b>
> add: +action-one, action-two        controls: menu | info | actions | cancel
╟────────────────────────────────────────────────────────────────────────╢
     /\        recursive grove online
    /φ \       exactness before ornament
   /____\      warm, readable, plain text
     ||
╟────────────────────────────────────────────────────────────────────────╢
[01] TRUTH-INVENTORY-MATHEMATICIAN
     exact values, recurrence, ratios, limits, proofs, conversions
     feature: exactness-first | Fv-conversion-visible | finite-ratio-cautions
     actions: formula-sheet | index-convert | proof-mode | edge-cases

[02] AVOID-AUDITOR
     indexing, ratio, rendering, geometry, and claim-error audit
     feature: red-team-before-fix | source-trace-first | risk-ranked-output
     actions: audit-checklist | claim-risk-map | source-trace | red-team

[03] GRAPH-ARTIST
     meaningful graph concepts and visuals that put questions before style
     feature: question-first | smallest-useful-graph | aesthetic-after-truth
     actions: sketch-plan | question-first | aesthetic-variants | label-audit

[04] SVG-DRAWING-ENGINE
     precise repository-quality SVG diagrams, plots, spirals, and assets
     feature: math-skeleton-before-style | asset-reuse-first | title+desc+claim-badge
     actions: canvas-spec | export-check | accessibility-pass | reuse-assets | more...

[05] SPIRAL-GEOMETRY
     square layouts, quarter-circle spirals, and golden-spiral separation
     feature: square-integrity | arc-center-audit | golden-vs-fibonacci-separation
     actions: square-layout | golden-comparison | geometry-audit | claim-caveats

[06] NORMALIZED-TIME-METAPHOR
     yesterday/today/tomorrow metaphor with explicit normalized quantity
     feature: metaphor-badge | normalized-quantity-named | asymmetry-visible
     actions: metaphor-badge | asymmetry-note | concept-map | caveat-card

[07] DOCUMENT-INDEXER
     catalogues, bidirectional links, source hierarchy, and stale indexes
     feature: bidirectional-links | source-hierarchy-preserved | stale-index-check
     actions: link-audit | catalog-row | source-hierarchy-map | staleness-check

[08] CLAIM-TRACEABILITY
     claim/source/status maps, contradiction scans, and open questions
     feature: claim-source-status | contradiction-scan | open-question-register
     actions: claim-table | contradiction-scan | citation-pack | open-questions

[09] GLOSSARY-TERMINOLOGIST
     definitions, namespaces, synonym cleanup, and vocabulary boundaries
     feature: term-card-format | namespace-preserved | definition-not-claim
     actions: term-card | namespace-check | synonym-merge | definition-audit

[10] ORANGE-PRESSING-EXPANDER
     expansion branches that return creative work to exactness
     feature: branch-map | artifact-family | return-to-core
     actions: branch-map | artifact-list | priority-sort | return-to-core

[11] GENERATION-LATTICE-PLANNER
     next artifacts by topic family, development level, and prerequisites
     feature: lattice-position | prerequisites-first | manifest-ready
     actions: lattice-position | next-three | dependency-map | manifest-draft

[12] EMPIRICAL-CLAIM-SKEPTIC
     nature, shells, markets, bodies, architecture, behavior, and art claims
     feature: rival-models | residuals-before-resemblance | claim-softening
     actions: rival-models | evidence-grid | sample-check | claim-softener

[13] SPREADSHEET-DATA
     extended tables, workbook checks, and canonical-vs-extended ranges
     feature: range-declared | formulas-recomputed | columns-mapped
     actions: range-declare | column-map | recompute-check | export-plan

[14] TEACHER-LESSON-BUILDER
     learner-safe lessons, staged reveals, exercises, and misconceptions
     feature: learner-misconceptions | staged-reveal | exercise-ready
     actions: lesson-outline | misconception-list | exercise-set | reveal-sequence

[15] REPOSITORY-CURATOR
     living-canon maintenance, relation updates, and release notes
     feature: canon-check | relation-update | maintenance-diff
     actions: maintenance-plan | relation-update | canon-check | release-notes
╟────────────────────────────────────────────────────────────────────────╢
> examples: 04 + canvas-spec, reuse-assets
>           combine graph-artist + svg-drawing-engine
>           finish booting with document-indexer.boot.md + link-audit
╚════════════════════════════════════════════════════════════════════════╝
```

### Selection grammar

- **Number:** `3` selects menu item 3.
- **Short name:** `graph-artist` or [`graph-artist.boot.md`](graph-artist.boot.md) selects the same path.
- **With actions:** `3 + sketch-plan, cite-sources` selects a path and secondary actions.
- **Combination:** `combine graph-artist + svg-drawing-engine` loads both paths, unless the task would be better served by choosing only one.
- **Task inference:** `I need to audit a shell spiral claim` routes to the minimum relevant path, usually [`empirical-claim-skeptic.boot.md`](empirical-claim-skeptic.boot.md) plus [`spiral-geometry.boot.md`](spiral-geometry.boot.md) if geometry is central.

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


## General secondary boot refinements

These refinements apply across the full secondary boot system and should be baked into every option as it matures. They capture lessons from the SVG boot review and anticipate what future option-specific reviews are likely to discover.

### Fast path vs confirm path

A secondary boot selection may complete in either of two explicitly supported ways:

- **Fast path:** a plain number or short name, such as `4`, immediately loads that boot path and prints its available actions for the next prompt. Use this when the user's intent is simple and no action was named.
- **Confirm path:** a selection with `actions`, `info`, or ambiguity previews actions first and asks the user to add or skip actions before finalizing. Use this when the user is exploring, combining paths, or choosing among materially different action bundles.

Default behavior: prefer the fast path for unambiguous single-number selections, but clearly state that actions can still be added in the next prompt.

### Action edit-risk labels

Every secondary action should declare one of these edit-risk levels:

- **Read-only:** inspects, summarizes, routes, or checks without changing files.
- **Draft-only:** prepares proposed content, manifests, captions, examples, checklists, or patch plans without saving them unless the user confirms.
- **File-modifying:** may create, edit, move, or delete repository files after the user makes an actionable request.

Boot-time actions default to read-only or draft-only. A secondary action should not modify repository files merely because the user selected a boot mode.

### Universal actionable-task sequence

After any secondary boot is complete and the user gives an actionable task, use this general sequence unless a more specific boot document overrides it:

1. Parse the task intent, named actions, controls, output mode, and implied audience.
2. Choose the smallest sufficient boot context; combine at most two boot paths at first unless the task requires more.
3. Declare the working contract: question, domain, convention, source lineage, output type, and evidence boundary.
4. Inspect relevant existing assets, documents, data, or claims before creating duplicates.
5. Build the factual skeleton before style, pedagogy, metaphor, or expansion.
6. Produce the artifact, edit, audit, plan, or answer.
7. Validate with the cheapest useful checks available in the environment.
8. Summarize changes, cite files, and list checks in the required final-response format.

### Primitive UI display conventions

Keep every boot display text-only, compact, and structurally identical. Use these labels consistently: `signal:` for boot state, `feature:` for mode-specific strengths, `actions:` for optional shortcuts, `paths:` for fast/confirm behavior, and `next:` for the user's next move. The tiny grove/tree accent is decorative only; it must never encode status, warnings, data, or navigation, and should appear at most once in a boot display.

```text
        &&&
       &&&&&
        |||
```

### Compact repeat menu

Support `menu compact` as a lightweight repeat command. It should show only number, short name, and purpose. Do not reread every source document just to print it.

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
| [`truth-inventory-mathematician.boot.md`](truth-inventory-mathematician.boot.md) | `formula-sheet` — summarize active formulas; `index-convert` — prepare Fv/conventional conversion notes; `proof-mode` — enable proof-first response framing; `edge-cases` — list exactness and finite-ratio cautions. |
| [`avoid-auditor.boot.md`](avoid-auditor.boot.md) | `audit-checklist` — prepare common error checklist; `claim-risk-map` — rank likely failure modes; `source-trace` — prepare source citation map; `red-team` — respond adversarially before proposing fixes. |
| [`graph-artist.boot.md`](graph-artist.boot.md) | `sketch-plan` — propose 2–5 visual concepts; `question-first` — force each graph to answer a stated question; `aesthetic-variants` — prepare restrained, vivid, and minimalist variants; `label-audit` — precheck title, axes, legend, and caveats. |
| [`svg-drawing-engine.boot.md`](svg-drawing-engine.boot.md) | `canvas-spec` — define dimensions and coordinate system; `export-check` — prepare SVG validation checklist; `accessibility-pass` — plan title/description/contrast labels; `reuse-assets` — inspect existing drawings before creating new ones; `truth-badge` — add claim-strength labeling; `spiral-safe` — apply geometry-safe spiral defaults; `caption-pack` — draft captions, caveats, title, and description; `style-variants` — prepare minimal, vivid, print-friendly, and rambunctious variants; `mobile-safe` — plan or generate mobile-safe and slow-processor-safe variants; `teacher-variant` — prepare learner-safe simplifications; `asset-bundle` — plan reusable SVG derivatives; `revision-handles` — provide compact iteration commands. |
| [`spiral-geometry.boot.md`](spiral-geometry.boot.md) | `square-layout` — set up square and arc constraints; `golden-comparison` — separate Fibonacci spiral approximation from logarithmic golden spiral; `geometry-audit` — check centers, radii, tangency, and scaling; `claim-caveats` — prepare geometry limitation notes. |
| [`normalized-time-metaphor.boot.md`](normalized-time-metaphor.boot.md) | `metaphor-badge` — state metaphor status and normalized quantity; `asymmetry-note` — include interval asymmetry; `concept-map` — draft planning/salience/memory axes; `caveat-card` — list what the metaphor does not prove. |
| [`document-indexer.boot.md`](document-indexer.boot.md) | `link-audit` — check bidirectional links; `catalog-row` — prepare catalogue metadata; `source-hierarchy-map` — summarize authority relationships; `staleness-check` — identify likely stale index entries. |
| [`claim-traceability.boot.md`](claim-traceability.boot.md) | `claim-table` — prepare claim/source/status columns; `contradiction-scan` — look for tension across documents; `citation-pack` — collect relevant citations; `open-questions` — list unresolved claims. |
| [`glossary-terminologist.boot.md`](glossary-terminologist.boot.md) | `term-card` — create definition/source/usage cards; `namespace-check` — preserve identifier namespaces; `synonym-merge` — identify duplicate terms; `definition-audit` — separate claims from vocabulary. |
| [`orange-pressing-expander.boot.md`](orange-pressing-expander.boot.md) | `branch-map` — generate expansion branches; `artifact-list` — propose documents, graphs, datasets, and lessons; `priority-sort` — rank expansions by value; `return-to-core` — map creative ideas back to exactness. |
| [`generation-lattice-planner.boot.md`](generation-lattice-planner.boot.md) | `lattice-position` — place work on horizontal/vertical lattice; `next-three` — propose next three artifacts; `dependency-map` — list prerequisites; `manifest-draft` — draft JSON/Markdown updates. |
| [`empirical-claim-skeptic.boot.md`](empirical-claim-skeptic.boot.md) | `rival-models` — list non-Fibonacci explanations; `evidence-grid` — separate resemblance, correlation, mechanism, and proof; `sample-check` — ask sample-size and measurement questions; `claim-softener` — rewrite overclaims safely. |
| [`spreadsheet-data.boot.md`](spreadsheet-data.boot.md) | `range-declare` — state canonical vs extended range; `column-map` — map spreadsheet columns to terms; `recompute-check` — plan formula validation; `export-plan` — define CSV/table outputs. |
| [`teacher-lesson-builder.boot.md`](teacher-lesson-builder.boot.md) | `lesson-outline` — draft staged lesson arc; `misconception-list` — prepare learner-safe warnings; `exercise-set` — create practice prompts; `reveal-sequence` — sequence examples from concrete to abstract. |
| [`repository-curator.boot.md`](repository-curator.boot.md) | `maintenance-plan` — identify add/archive/normalize work; `relation-update` — prepare link-index edits; `canon-check` — verify source hierarchy compliance; `release-notes` — draft summary of repository changes. |

## Featured above-the-fold optimizations by boot path

Use these featured lines in the primitive UI when space allows. They are option-specific optimizations surfaced early so users can select the right mode quickly.

| Secondary boot name | `feature:` line | Why it matters |
|---|---|---|
| `truth-inventory-mathematician` | `exactness-first | Fv-conversion-visible | finite-ratio-cautions` | Prevents index drift and false exactness before proofs or formulas begin. |
| `avoid-auditor` | `red-team-before-fix | source-trace-first | risk-ranked-output` | Makes audits adversarial and evidence-linked instead of merely stylistic. |
| `graph-artist` | `question-first | smallest-useful-graph | aesthetic-after-truth` | Keeps visual ideation tied to the insight the graph must reveal. |
| `svg-drawing-engine` | `math-skeleton-before-style | asset-reuse-first | title+desc+claim-badge` | Converts SVG work into reproducible, accessible vector artifacts. |
| `spiral-geometry` | `square-integrity | arc-center-audit | golden-vs-fibonacci-separation` | Prevents the common confusion between Fibonacci quarter-circle approximations and logarithmic golden spirals. |
| `normalized-time-metaphor` | `metaphor-badge | normalized-quantity-named | asymmetry-visible` | Keeps the time model interpretive rather than falsely physical. |
| `document-indexer` | `bidirectional-links | source-hierarchy-preserved | stale-index-check` | Makes catalogue work maintainable and authority-aware. |
| `claim-traceability` | `claim-source-status | contradiction-scan | open-question-register` | Turns claims into auditable records with provenance and status. |
| `glossary-terminologist` | `term-card-format | namespace-preserved | definition-not-claim` | Separates vocabulary cleanup from unsupported truth assertions. |
| `orange-pressing-expander` | `branch-map | artifact-family | return-to-core` | Encourages creative expansion that returns to exactness. |
| `generation-lattice-planner` | `lattice-position | prerequisites-first | manifest-ready` | Places new work in the repository's development map before generating files. |
| `empirical-claim-skeptic` | `rival-models | residuals-before-resemblance | claim-softening` | Protects against overclaiming nature, markets, bodies, shells, or art. |
| `spreadsheet-data` | `range-declared | formulas-recomputed | columns-mapped` | Prevents spreadsheet labels and extended ranges from overriding canon. |
| `teacher-lesson-builder` | `learner-misconceptions | staged-reveal | exercise-ready` | Makes lessons accurate, sequenced, and safe for beginners. |
| `repository-curator` | `canon-check | relation-update | maintenance-diff` | Keeps repository evolution intentional and traceable. |

```text
   /\
  /**\
 /****\
   ||
```

## Recommended secondary boot list

| Secondary boot name | Best for | Required repository sources to read next |
|---|---|---|
| [`truth-inventory-mathematician.boot.md`](truth-inventory-mathematician.boot.md) | Exact Fibonacci values, recurrence, ratios, limits, proofs, convention conversions, and finite/exact distinction. | [02_Fibonacci_Truth_Inventory.docx](02_Fibonacci_Truth_Inventory.docx), [01_Fibonacci_Avoids_and_Error_Inventory.docx](01_Fibonacci_Avoids_and_Error_Inventory.docx), [Fibonacci_Glossary.md](Fibonacci_Glossary.md), [Fibonacci_Cohesion_Audit.md](Fibonacci_Cohesion_Audit.md) |
| [`avoid-auditor.boot.md`](avoid-auditor.boot.md) | Finding indexing errors, ratio reversals, rendering mistakes, geometry problems, weak claims, and document-integrity failures. | [01_Fibonacci_Avoids_and_Error_Inventory.docx](01_Fibonacci_Avoids_and_Error_Inventory.docx), [02_Fibonacci_Truth_Inventory.docx](02_Fibonacci_Truth_Inventory.docx), [Fibonacci_Cohesion_Audit.md](Fibonacci_Cohesion_Audit.md), [Fibonacci_Statement_Claim_Index.md](Fibonacci_Statement_Claim_Index.md) |
| [`graph-artist.boot.md`](graph-artist.boot.md) | Selecting meaningful visualizations, generating graph concepts, designing SVGs, and balancing truth with aesthetics. | [insightgraphsuite.md](insightgraphsuite.md), [curated_fibonacci_insight_graphs.md](curated_fibonacci_insight_graphs.md), [draw.md](draw.md), [fibonacci_generation_lattice.md](fibonacci_generation_lattice.md) |
| [`svg-drawing-engine.boot.md`](svg-drawing-engine.boot.md) | Creating precise repository-quality SVG diagrams, plots, spirals, and visual-proof assets. | [draw.md](draw.md), [insightgraphsuite.md](insightgraphsuite.md), [curated_fibonacci_insight_graphs.md](curated_fibonacci_insight_graphs.md), existing files in [drawings/](drawings/) |
| [`spiral-geometry.boot.md`](spiral-geometry.boot.md) | Fibonacci square layouts, quarter-circle spirals, golden rectangles, geometry audits, and golden-spiral comparisons. | [02_Fibonacci_Truth_Inventory.docx](02_Fibonacci_Truth_Inventory.docx), [01_Fibonacci_Avoids_and_Error_Inventory.docx](01_Fibonacci_Avoids_and_Error_Inventory.docx), [draw.md](draw.md), [insightgraphsuite.md](insightgraphsuite.md) |
| [`normalized-time-metaphor.boot.md`](normalized-time-metaphor.boot.md) | Yesterday/today/tomorrow metaphor, reciprocal time, planning horizons, salience, memory, anticipation, and caveat-rich conceptual graphics. | [the_essences.md](the_essences.md), [insightgraphsuite.md](insightgraphsuite.md), [fibonacci_generation_lattice.md](fibonacci_generation_lattice.md), [fibonacci_orange_pressing_recommendations.md](fibonacci_orange_pressing_recommendations.md) |
| [`document-indexer.boot.md`](document-indexer.boot.md) | Cataloguing documents, building indexes, adding bidirectional cross-links, maintaining source hierarchy, and preparing master catalogue work. | [README.md](README.md), [Fibonacci_Statement_Claim_Index.md](Fibonacci_Statement_Claim_Index.md), [Fibonacci_Cohesion_Audit.md](Fibonacci_Cohesion_Audit.md), [the_essences.md](the_essences.md) |
| [`claim-traceability.boot.md`](claim-traceability.boot.md) | Tracing claims across documents, locating contradictions, mapping statements, and building audit reports. | [Fibonacci_Statement_Claim_Index.md](Fibonacci_Statement_Claim_Index.md), [Fibonacci_Cohesion_Audit.md](Fibonacci_Cohesion_Audit.md), [02_Fibonacci_Truth_Inventory.docx](02_Fibonacci_Truth_Inventory.docx), [01_Fibonacci_Avoids_and_Error_Inventory.docx](01_Fibonacci_Avoids_and_Error_Inventory.docx) |
| [`glossary-terminologist.boot.md`](glossary-terminologist.boot.md) | Defining terms, cleaning vocabulary, separating supplemental terms from inventory claims, and preserving stable identifier namespaces. | [Fibonacci_Glossary.md](Fibonacci_Glossary.md), [Fibonacci_Glossary_Seed.md](Fibonacci_Glossary_Seed.md), [03_Fibonacci_Inventory_Documents_Detailed_Description.docx](03_Fibonacci_Inventory_Documents_Detailed_Description.docx), [the_essences.md](the_essences.md) |
| [`orange-pressing-expander.boot.md`](orange-pressing-expander.boot.md) | Expanding small insights into families of documents, graphs, data manifests, workbooks, lessons, and future creative branches. | [fibonacci_orange_pressing_recommendations.md](fibonacci_orange_pressing_recommendations.md), [fibonacci_generation_lattice.md](fibonacci_generation_lattice.md), [insightgraphsuite.md](insightgraphsuite.md), [draw.md](draw.md) |
| [`generation-lattice-planner.boot.md`](generation-lattice-planner.boot.md) | Planning next documents and figures by horizontal topic family and vertical development level. | [fibonacci_generation_lattice.md](fibonacci_generation_lattice.md), [fibonacci_generation_lattice.json](fibonacci_generation_lattice.json), [curated_fibonacci_insight_graphs.md](curated_fibonacci_insight_graphs.md), [fibonacci_orange_pressing_recommendations.md](fibonacci_orange_pressing_recommendations.md) |
| [`empirical-claim-skeptic.boot.md`](empirical-claim-skeptic.boot.md) | Auditing claims about nature, shells, bodies, markets, architecture, behavior, and art without overclaiming Fibonacci mechanisms. | [02_Fibonacci_Truth_Inventory.docx](02_Fibonacci_Truth_Inventory.docx), [01_Fibonacci_Avoids_and_Error_Inventory.docx](01_Fibonacci_Avoids_and_Error_Inventory.docx), [insightgraphsuite.md](insightgraphsuite.md), [the_essences.md](the_essences.md) |
| [`spreadsheet-data.boot.md`](spreadsheet-data.boot.md) | Working with extended tables, first-100-step ratios, canonical-vs-extended ranges, and workbook-derived calculations. | [fibonacci_first_100_with_ratios.xlsx](fibonacci_first_100_with_ratios.xlsx), [02_Fibonacci_Truth_Inventory.docx](02_Fibonacci_Truth_Inventory.docx), [the_essences.md](the_essences.md), [Fibonacci_Glossary.md](Fibonacci_Glossary.md) |
| [`teacher-lesson-builder.boot.md`](teacher-lesson-builder.boot.md) | Turning Fibonacci concepts into lessons, staged reveals, learner-safe diagrams, prompts, and exercises. | [boot.md](boot.md), [Fibonacci_Glossary.md](Fibonacci_Glossary.md), [insightgraphsuite.md](insightgraphsuite.md), [fibonacci_orange_pressing_recommendations.md](fibonacci_orange_pressing_recommendations.md) |
| [`repository-curator.boot.md`](repository-curator.boot.md) | Maintaining the repository as a living canon, deciding what to add, archive, normalize, denormalize, or cross-link next. | [README.md](README.md), [the_essences.md](the_essences.md), [Fibonacci_Cohesion_Audit.md](Fibonacci_Cohesion_Audit.md), [secondary_boot_prompts.md](secondary_boot_prompts.md) |

## Selection rule

Choose the smallest secondary boot that covers the task. If a task spans domains, combine at most two boot paths at first, then add more only when a concrete need appears.

Examples:

- For a new SVG: combine [`graph-artist.boot.md`](graph-artist.boot.md) and [`svg-drawing-engine.boot.md`](svg-drawing-engine.boot.md).
- For a claim audit of a shell image: combine [`empirical-claim-skeptic.boot.md`](empirical-claim-skeptic.boot.md) and [`spiral-geometry.boot.md`](spiral-geometry.boot.md).
- For a master catalogue: start with [`document-indexer.boot.md`](document-indexer.boot.md), then add [`claim-traceability.boot.md`](claim-traceability.boot.md) if statement-level mapping is required.
- For a philosophical time diagram: combine [`normalized-time-metaphor.boot.md`](normalized-time-metaphor.boot.md) and [`graph-artist.boot.md`](graph-artist.boot.md).

## Naming convention for future secondary boot documents

When adding future secondary boot documents, use lowercase kebab-case and the suffix `.boot.md`, for example:

- [`graph-artist.boot.md`](graph-artist.boot.md)
- [`document-indexer.boot.md`](document-indexer.boot.md)
- [`truth-inventory-mathematician.boot.md`](truth-inventory-mathematician.boot.md)

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
