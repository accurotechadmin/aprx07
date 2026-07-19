# Fibonacci Generation Lattice: Recommended Graphs, Figures, and Documents

<!-- document-relations: header -->
> **Directly related documents:** [Cohesion Audit](Fibonacci_Cohesion_Audit.md) · [Glossary](Fibonacci_Glossary.md) · [Glossary Seed](Fibonacci_Glossary_Seed.md) · [Claim Index](Fibonacci_Statement_Claim_Index.md) · [Curated Graphs](curated_fibonacci_insight_graphs.md) · [Drawing Guide](draw.md) · [Boot-Up Prompt](fibonacci_boot_up_full_prompt.md) · [Orange Recommendations](fibonacci_orange_pressing_recommendations.md) · [Insight-Graph Suite](insightgraphsuite.md) · [Essences SSOT](the_essences.md).
<!-- /document-relations: header -->


## Purpose

This planning document turns the repository's Fibonacci graph suite into a generative lattice. It recommends `.svg` graphs/images/figures and `.md`, `.json`, and `.xlsx` documents that should be generated next, then classifies them by **horizontal topical family** and **vertical development level** so future requests can be addressed by coordinates.

A request such as "give me 20 more documents like this in a positive vertical" should mean: keep the same horizontal family and move upward into more developed levels. A request such as "give me a document like this one across all horizontals on the same level and three up and three down" should mean: keep the source document's vertical level, produce analogues in other horizontal families, and include levels `-3` through `+3` around that source level where meaningful.

## Coordinate system

### Horizontal topical families

| Horizontal ID | Family | Governing question | Typical outputs |
|---|---|---|---|
| H1 | Canonical sequence and recurrence | What does the repository Fv convention produce, and how is each destination known from the prior two? | Destination tables, addition decompositions, dependency graphs, recurrence primers. |
| H2 | Ratios, convergence, and error | How do adjacent ratios approach `phi` and `1/phi` without finite equality? | Ratio plots, signed-error panels, cobweb diagrams, convergence workbooks. |
| H3 | Exact identities and discrete structures | Which exact Fibonacci identities, combinatorial structures, and integer patterns are visible? | Cassini, sums, matrix, modulo, gcd, Zeckendorf, Pascal, Fibonacci word. |
| H4 | Geometry, spirals, and golden forms | What geometric constructions are exact, approximate, or visually related? | Square-and-arc SVGs, aspect-ratio plots, golden-angle figures, spiral residuals. |
| H5 | Empirical and reality-test applications | What evidence would distinguish a Fibonacci claim from alternatives? | Fit/residual protocols, measured datasets, model comparisons, claim matrices. |
| H6 | Metadata, systems, and workflow | How can recurrence illuminate documents, dependency, storage, prioritization, and cadence? | Cross-reference graphs, dependency maps, JSON manifests, systems workbooks. |
| H7 | Normalized time metaphor | What does the declared `1/phi`, `1`, `phi` time coordinate reveal without becoming a theorem? | Time-reference number lines, interval maps, planning ladders, salience figures. |

### Vertical development levels

| Vertical level | Name | Role | Positive vertical action |
|---:|---|---|---|
| -3 | Seed / premise | Minimal statement of the idea, convention, variables, and caveats. | Expand into a small worked example. |
| -2 | Data / source table | Canonical, computed, measured, or metaphorical source rows. | Add calculations, lineage, and validation. |
| -1 | Micro figure | One-page or one-panel introduction with near-horizon scope. | Extend to a complete explanatory figure. |
| 0 | Core reference | Mid-horizon or canonical artifact suitable as the baseline document. | Build companion audit, workbook, and advanced figure. |
| +1 | Comparative / analytic | Contrasts views, models, residuals, or transformations. | Add robustness, alternatives, or overlays. |
| +2 | Audit / protocol | Explicit checks, failure modes, assumptions, and evidence boundaries. | Turn into repeatable generation/evaluation procedure. |
| +3 | Synthesis / generative suite | Full chapter, package, or template family that can spawn variants. | Generate collections across levels and horizontals. |

## Recommended `.svg` graphs, images, and figures

### H1 — Canonical sequence and recurrence

| ID | Recommended file | Level | Figure type | Description |
|---|---|---:|---|---|
| SVG-H1-001 | `drawings/canonical_fv_near_horizon.svg` | -1 | SVG graph | Near-horizon `Fv -1` through `Fv 8` destination markers with zero and duplicate-one seeds visible. |
| SVG-H1-002 | `drawings/canonical_fv_mid_horizon.svg` | 0 | SVG graph | Canonical `Fv -1` through `Fv 28` destination reference with readable scale strategy. |
| SVG-H1-003 | `drawings/destination_addition_decomposition.svg` | 0 | SVG figure | Each destination shown as the visible sum of its two predecessors. |
| SVG-H1-004 | `drawings/recurrence_dependency_graph.svg` | +1 | SVG network | Directed dependency graph showing each `D_v` as known from `D_(v-1)` and `D_(v-2)`. |
| SVG-H1-005 | `drawings/linear_vs_log_destination_comparison.svg` | +1 | SVG multi-panel | Linear and log views showing early-value compression and growth clarity. |

### H2 — Ratios, convergence, and error

| ID | Recommended file | Level | Figure type | Description |
|---|---|---:|---|---|
| SVG-H2-001 | `drawings/forward_ratio_line_chart.svg` | 0 | SVG graph | Forward ratios with discrete markers and a labeled `phi` reference line. |
| SVG-H2-002 | `drawings/forward_ratio_alternating_envelope.svg` | +1 | SVG graph | Odd/even side-of-limit envelopes around `phi`. |
| SVG-H2-003 | `drawings/signed_error_alternation_plot.svg` | +1 | SVG graph | Signed `R_v - phi` errors with zero reference and side-of-limit preservation. |
| SVG-H2-004 | `drawings/absolute_error_by_step.svg` | +1 | SVG graph | `|R_v - phi|` decay without conflating signed and absolute error. |
| SVG-H2-005 | `drawings/ratio_recurrence_cobweb.svg` | +2 | SVG figure | Iteration of `r_(n+1)=1+1/r_n` toward the fixed point `phi`. |
| SVG-H2-006 | `drawings/late_ratio_zoom_panel.svg` | +2 | SVG inset figure | Late-ratio zoom with enough precision to retain above/below-limit status. |

### H3 — Exact identities and discrete structures

| ID | Recommended file | Level | Figure type | Description |
|---|---|---:|---|---|
| SVG-H3-001 | `drawings/cassini_identity_alternation.svg` | 0 | SVG graph | `F_(n+1)F_(n-1)-F_n^2=(-1)^n` as a permanent ±1 alternation. |
| SVG-H3-002 | `drawings/cumulative_destination_sum.svg` | 0 | SVG graph | Running sums beside the identity `sum F_k = F_(n+2)-1` under stated indexing. |
| SVG-H3-003 | `drawings/zeckendorf_decomposition_map.svg` | +1 | SVG map | Integers decomposed into unique sums of nonconsecutive Fibonacci numbers. |
| SVG-H3-004 | `drawings/fibonacci_modulo_heatmap.svg` | +1 | SVG heatmap | Fibonacci residues by modulus, showing Pisano repetition. |
| SVG-H3-005 | `drawings/gcd_identity_landscape.svg` | +2 | SVG heatmap | `gcd(F_m,F_n)=F_gcd(m,n)` as a two-dimensional exact structure. |

### H4 — Geometry, spirals, and golden forms

| ID | Recommended file | Level | Figure type | Description |
|---|---|---:|---|---|
| SVG-H4-001 | `drawings/fibonacci_square_construction_near.svg` | -1 | SVG diagram | Valid 1,1,2,3,5,8,13 square construction with labels and equal side discipline. |
| SVG-H4-002 | `drawings/spiral_radius_growth_by_quarter_turn.svg` | 0 | SVG graph | Quarter-turn radii connected directly to Fibonacci destinations. |
| SVG-H4-003 | `drawings/golden_rectangle_aspect_ratio_by_stage.svg` | 0 | SVG graph | Rectangle ratios approaching `phi` or `1/phi` by orientation. |
| SVG-H4-004 | `drawings/golden_spiral_vs_fibonacci_spiral.svg` | +1 | SVG overlay | Piecewise quarter-circle Fibonacci spiral distinguished from exact logarithmic golden spiral. |
| SVG-H4-005 | `drawings/golden_angle_rotation_map.svg` | +1 | SVG radial figure | Repeated rotations by `360/phi^2` with even-distribution caveats. |
| SVG-H4-006 | `drawings/spiral_fit_residual_comparison.svg` | +2 | SVG analytic figure | Residual comparison among Fibonacci-square, golden-logarithmic, and alternative spirals. |

### H5 — Empirical and reality-test applications

| ID | Recommended file | Level | Figure type | Description |
|---|---|---:|---|---|
| SVG-H5-001 | `drawings/natural_pattern_claim_evidence_matrix.svg` | 0 | SVG matrix | Claims classified by evidence type, sample size, uncertainty, and alternative explanation. |
| SVG-H5-002 | `drawings/observed_spiral_counts_vs_fibonacci_pairs.svg` | +1 | SVG scatter | Measured clockwise/counterclockwise spiral counts against nearby consecutive pairs. |
| SVG-H5-003 | `drawings/leaf_angle_distribution_around_golden_angle.svg` | +1 | SVG distribution | Divergence angles with uncertainty and competing angular models. |
| SVG-H5-004 | `drawings/human_proportion_fit_vs_alternatives.svg` | +1 | SVG comparison | Human measurements tested against `phi` and non-Fibonacci ratios. |
| SVG-H5-005 | `drawings/market_retracement_hit_rate_vs_random.svg` | +2 | SVG analytic figure | Hit rates near Fibonacci levels compared with matched random/uniform baselines. |
| SVG-H5-006 | `drawings/population_recurrence_model_vs_observations.svg` | +2 | SVG model comparison | Fibonacci-style recurrence compared with logistic and age-structured alternatives. |

### H6 — Metadata, systems, and workflow

| ID | Recommended file | Level | Figure type | Description |
|---|---|---:|---|---|
| SVG-H6-001 | `drawings/cross_reference_growth_by_document_layer.svg` | 0 | SVG graph | References accumulating from facts to rules, explanations, audits, and applications. |
| SVG-H6-002 | `drawings/recursive_metadata_dependency_graph.svg` | 0 | SVG network | Derived records depending on the previous two records. |
| SVG-H6-003 | `drawings/concept_compression_by_recurrence.svg` | +1 | SVG comparison | Storing seeds plus rule versus storing every derived value. |
| SVG-H6-004 | `drawings/fibonacci_backoff_timeline.svg` | +1 | SVG timeline | Retry intervals compared with linear and exponential backoff. |
| SVG-H6-005 | `drawings/fibonacci_priority_weight_curve.svg` | +1 | SVG graph | Fibonacci-normalized weights for attention, confidence, or resource allocation. |
| SVG-H6-006 | `drawings/sparse_to_dense_annotation_schedule.svg` | +2 | SVG schedule | Annotation density governed by Fibonacci-indexed review points. |

### H7 — Normalized time metaphor

| ID | Recommended file | Level | Figure type | Description |
|---|---|---:|---|---|
| SVG-H7-001 | `drawings/normalized_time_reference_number_line.svg` | 0 | SVG graph | Yesterday `1/phi`, Today `1`, Tomorrow `phi` on a labeled number line. |
| SVG-H7-002 | `drawings/time_reference_interval_comparison.svg` | 0 | SVG figure | Unequal intervals `1/phi^2` and `1/phi`, with ratio `phi`. |
| SVG-H7-003 | `drawings/reciprocal_time_mirror.svg` | +1 | SVG transformation | The map `x -> 1/x` exchanging yesterday and tomorrow while fixing today. |
| SVG-H7-004 | `drawings/fibonacci_calendar_interval_ladder.svg` | +1 | SVG timeline | Calendar intervals at ±1, ±2, ±3, ±5, ±8 around today. |
| SVG-H7-005 | `drawings/golden_time_uncertainty_cone.svg` | +2 | SVG conceptual figure | Uncertainty widening away from today under an explicitly metaphorical model. |
| SVG-H7-006 | `drawings/temporal_self_similarity_across_scales.svg` | +2 | SVG multi-scale figure | Repeated `1/phi`–`1`–`phi` frames at multiple temporal scales. |

## Recommended `.md`, `.json`, and `.xlsx` documents

### H1 — Canonical sequence and recurrence documents

| ID | Recommended file | Format | Level | Role |
|---|---|---|---:|---|
| DOC-H1-001 | `canonical_fv_reference_table.md` | `.md` | 0 | Human-readable canonical `Fv -1` through `Fv 28` table with convention notes. |
| DOC-H1-002 | `canonical_fv_reference_table.json` | `.json` | -2 | Machine-readable Fv destinations, conventional-index mapping, and lineage fields. |
| DOC-H1-003 | `canonical_fv_reference_table.xlsx` | `.xlsx` | -2 | Spreadsheet table for destinations, transitions, and recurrence checks. |
| DOC-H1-004 | `recurrence_dependency_guide.md` | `.md` | +1 | Explains known-from-known dependency, arrows, and generation rules. |
| DOC-H1-005 | `fv_range_horizon_policy.md` | `.md` | +2 | Protocol for near, mid, far, canonical, converted, and extended ranges. |

### H2 — Ratio, convergence, and error documents

| ID | Recommended file | Format | Level | Role |
|---|---|---|---:|---|
| DOC-H2-001 | `forward_ratio_inventory_extended.md` | `.md` | 0 | Forward ratio definitions, exact fractions, rounded values, and side-of-limit notes. |
| DOC-H2-002 | `ratio_convergence_workbook.xlsx` | `.xlsx` | -2 | Computed ratios, reciprocals, signed errors, absolute errors, and precision flags. |
| DOC-H2-003 | `ratio_convergence_manifest.json` | `.json` | -2 | Machine-readable formulas, reference constants, precision policy, and graph bindings. |
| DOC-H2-004 | `ratio_error_audit_protocol.md` | `.md` | +2 | Audit procedure for monotonicity, exactness, rounding, and false-equality errors. |
| DOC-H2-005 | `ratio_cobweb_explainer.md` | `.md` | +1 | Explanation of `r -> 1 + 1/r` and fixed-point convergence to `phi`. |

### H3 — Exact identity documents

| ID | Recommended file | Format | Level | Role |
|---|---|---|---:|---|
| DOC-H3-001 | `fibonacci_identity_atlas.md` | `.md` | +3 | Chapter-like guide grouping sums, Cassini, matrices, gcd, modulo, and decompositions. |
| DOC-H3-002 | `fibonacci_identity_manifest.json` | `.json` | 0 | Machine-readable identity list with variables, domains, proof notes, and graph links. |
| DOC-H3-003 | `fibonacci_identity_workbook.xlsx` | `.xlsx` | -2 | Computation sheets for identity verification over finite ranges. |
| DOC-H3-004 | `zeckendorf_decomposition_reference.md` | `.md` | +1 | Human guide to unique nonconsecutive Fibonacci decompositions. |
| DOC-H3-005 | `pisano_and_modular_patterns.md` | `.md` | +1 | Modular periodicity primer with heatmap lineage. |

### H4 — Geometry and spiral documents

| ID | Recommended file | Format | Level | Role |
|---|---|---|---:|---|
| DOC-H4-001 | `fibonacci_geometry_construction_standard.md` | `.md` | 0 | Square, rectangle, arc, center, tangency, and scaling rules for geometry figures. |
| DOC-H4-002 | `spiral_geometry_manifest.json` | `.json` | -2 | Coordinates, square sizes, arc centers, radii, and SVG lineage for spiral assets. |
| DOC-H4-003 | `golden_rectangle_aspect_workbook.xlsx` | `.xlsx` | -2 | Stage ratios, errors from `phi`, and orientation conversions. |
| DOC-H4-004 | `golden_spiral_vs_fibonacci_spiral.md` | `.md` | +1 | Distinguishes logarithmic golden spirals from square-based quarter-circle approximations. |
| DOC-H4-005 | `geometry_figure_audit_protocol.md` | `.md` | +2 | Checklist for nonsquare tiles, wrong radii, broken tangency, and nonuniform resizing. |

### H5 — Empirical and reality-test documents

| ID | Recommended file | Format | Level | Role |
|---|---|---|---:|---|
| DOC-H5-001 | `fibonacci_reality_test_protocol.md` | `.md` | 0 | Evidence-boundary standard for plants, shells, bodies, markets, architecture, and other claims. |
| DOC-H5-002 | `natural_pattern_claims_manifest.json` | `.json` | -2 | Claim records with source, measurement method, uncertainty, alternatives, and status. |
| DOC-H5-003 | `empirical_spiral_fit_workbook.xlsx` | `.xlsx` | -2 | Measured points, fitted models, residuals, and uncertainty calculations. |
| DOC-H5-004 | `market_retracement_test_design.md` | `.md` | +1 | Test design comparing Fibonacci levels with random/uniform baselines. |
| DOC-H5-005 | `empirical_claim_audit_matrix.md` | `.md` | +2 | Audit matrix classifying exact, approximate, selected, unsupported, and alternative-explained claims. |

### H6 — Metadata, systems, and workflow documents

| ID | Recommended file | Format | Level | Role |
|---|---|---|---:|---|
| DOC-H6-001 | `fibonacci_document_generation_lattice.md` | `.md` | 0 | Expanded operational version of this coordinate system. |
| DOC-H6-002 | [`fibonacci_generation_lattice.json`](fibonacci_generation_lattice.json) | `.json` | 0 | Machine-readable horizontal/vertical coordinate map and generation rules. |
| DOC-H6-003 | `document_dependency_manifest.json` | `.json` | -2 | Source-to-derived document dependency records and lineage constraints. |
| DOC-H6-004 | `recursive_metadata_dependency_guide.md` | `.md` | +1 | Explains recurrence as an information-system dependency model. |
| DOC-H6-005 | `fibonacci_backoff_and_cadence_workbook.xlsx` | `.xlsx` | -2 | Retry, review, sampling, and annotation schedules compared with linear/exponential alternatives. |
| DOC-H6-006 | `generation_request_interpreter.md` | `.md` | +2 | Defines how commands such as "20 more like this" resolve into coordinates and constraints. |

### H7 — Normalized time metaphor documents

| ID | Recommended file | Format | Level | Role |
|---|---|---|---:|---|
| DOC-H7-001 | `normalized_time_reference_standard.md` | `.md` | 0 | Declares Yesterday/Today/Tomorrow coordinate values and metaphor boundaries. |
| DOC-H7-002 | `normalized_time_manifest.json` | `.json` | -2 | Machine-readable time-reference constants, labels, transformations, and caveats. |
| DOC-H7-003 | `golden_time_planning_workbook.xlsx` | `.xlsx` | -2 | Calendar ladders, scale intervals, and φ-scaled horizon calculations. |
| DOC-H7-004 | `reciprocal_time_mirror_explainer.md` | `.md` | +1 | Explains `x -> 1/x` as an interpretive symmetry around today = 1. |
| DOC-H7-005 | `time_metaphor_audit_protocol.md` | `.md` | +2 | Prevents theorem-overclaim, equal-spacing errors, and misplaced ratio references. |

## Horizontal/vertical generation rules

1. **Same document, positive vertical.** Keep the horizontal ID fixed and generate documents at higher vertical levels first. If the source is level `0`, candidate levels are `+1`, `+2`, then `+3`; after level `+3`, generate sibling specializations at `+3` before returning to `+2` variants.
2. **Same document, negative vertical.** Keep the horizontal ID fixed and generate supporting lower-level artifacts: premises, source tables, manifests, and micro figures.
3. **Across horizontals, same level.** Keep the vertical level fixed and generate one analogue in each other horizontal family with the same role. Example: a level `+2` audit protocol in H2 maps to level `+2` audit protocols in H4, H5, and H7.
4. **Across horizontals, three up and three down.** For a source coordinate `(Hn, Lx)`, generate coordinates `(H1..H7, Lx-3..Lx+3)` clipped to the allowed range `[-3,+3]`, then prioritize same-level analogues before vertical expansions.
5. **Twenty more like this.** Rank candidates by topical closeness, missing artifact type, and authority need: first same horizontal/adjacent level, then same level/across horizontals, then adjacent horizontal/adjacent levels.
6. **Format pairing.** A major `.md` reference should have a `.json` manifest when it defines reusable fields, and an `.xlsx` workbook when it depends on tabular calculations or measurements.
7. **Graph pairing.** A major `.svg` should identify its source `.md` explanation, `.json` data manifest, and `.xlsx` workbook if calculations or measurements are involved.
8. **Evidence boundary.** Empirical, application, and time-metaphor documents must state what they do not prove, and must separate exact recurrence facts from measurements, models, and metaphors.

## First recommended generation wave

These twenty artifacts are the best first expansion because they establish the coordinate system, canonical data, visualization standards, and the most reusable exact/math/time/metadata branches.

1. [`fibonacci_generation_lattice.json`](fibonacci_generation_lattice.json)
2. `canonical_fv_reference_table.md`
3. `canonical_fv_reference_table.json`
4. `canonical_fv_reference_table.xlsx`
5. `drawings/canonical_fv_mid_horizon.svg`
6. `drawings/destination_addition_decomposition.svg`
7. `ratio_convergence_workbook.xlsx`
8. `ratio_convergence_manifest.json`
9. `drawings/forward_ratio_line_chart.svg`
10. `drawings/signed_error_alternation_plot.svg`
11. `fibonacci_identity_manifest.json`
12. `fibonacci_identity_workbook.xlsx`
13. `drawings/cassini_identity_alternation.svg`
14. `fibonacci_geometry_construction_standard.md`
15. `spiral_geometry_manifest.json`
16. `drawings/fibonacci_square_construction_near.svg`
17. `fibonacci_reality_test_protocol.md`
18. `natural_pattern_claims_manifest.json`
19. `normalized_time_reference_standard.md`
20. `drawings/normalized_time_reference_number_line.svg`
---

<!-- document-relations: footer -->
## Document link index

### Documents this document links to
- [Fibonacci Inventory Cohesion Audit](Fibonacci_Cohesion_Audit.md)
- [Fibonacci Inventory Glossary](Fibonacci_Glossary.md)
- [Fibonacci Glossary Seed — Raw Vocabulary and Fresh-Session Prompt](Fibonacci_Glossary_Seed.md)
- [Fibonacci Documentation Statement and Claim Index](Fibonacci_Statement_Claim_Index.md)
- [Curated Fibonacci Insight Graphs](curated_fibonacci_insight_graphs.md)
- [Expert Fibonacci Graph-Drawing Guide](draw.md)
- [Full Fibonacci Repository Boot-Up Prompt](fibonacci_boot_up_full_prompt.md)
- [Fibonacci Orange-Pressing Recommendations](fibonacci_orange_pressing_recommendations.md)
- [Fibonacci Insight-Graph Suite: Authoritative Boot-Up Primer](insightgraphsuite.md)
- [The Essences: Canon / SSOT for Fibonacci Boot-Up Prompts](the_essences.md)

### Documents that link to this document
- [Fibonacci Inventory Cohesion Audit](Fibonacci_Cohesion_Audit.md)
- [Fibonacci Inventory Glossary](Fibonacci_Glossary.md)
- [Fibonacci Glossary Seed — Raw Vocabulary and Fresh-Session Prompt](Fibonacci_Glossary_Seed.md)
- [Fibonacci Documentation Statement and Claim Index](Fibonacci_Statement_Claim_Index.md)
- [Curated Fibonacci Insight Graphs](curated_fibonacci_insight_graphs.md)
- [Expert Fibonacci Graph-Drawing Guide](draw.md)
- [Full Fibonacci Repository Boot-Up Prompt](fibonacci_boot_up_full_prompt.md)
- [Fibonacci Orange-Pressing Recommendations](fibonacci_orange_pressing_recommendations.md)
- [Fibonacci Insight-Graph Suite: Authoritative Boot-Up Primer](insightgraphsuite.md)
- [The Essences: Canon / SSOT for Fibonacci Boot-Up Prompts](the_essences.md)
<!-- /document-relations: footer -->

