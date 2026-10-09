# DOC-1-037 F0 PROTOCOL_LOCKED

Unit: position 37, A "Microbiome Clock" for Aging. Source request: train a model to predict host age from microbiome composition, then identify microbial taxa associated with accelerated aging. Named sources: American Gut Project (AGP), curatedMetagenomicData (cMD).
Status: frozen protocol for F0; effective only after live GitHub commit/tag chronology and byte verification, before admission. No numerical analysis or scientific success credit. Research only, no clinical use or health assessment.

## Question and claim boundary

F0 asks whether a fixed documentary route set supports a prospectively registered chronological-age prediction study with source/participant-independent evaluation, plus whether it documents a separate endpoint that could support the requested accelerated-aging interpretation. This is a documentation-only feasibility audit, not a clock, model, fitted residual, association test or scientific discovery.

Chronological age is the initial candidate measured label. Predicted age minus chronological age is only model error, not established biological accelerated aging. No taxon will be called an accelerated-aging taxon from that residual or age correlation alone. Independently measured aging/longitudinal health outcomes and confounder control would need a separate F1 protocol. The original second component stays explicitly unresolved if no such endpoint is documented; it is not silently replaced with age-associated taxa.

## Novel direction and potential useful finding

A source-independent age-prediction comparison could distinguish an age signal from cohort, assay, geography and participant leakage. A properly replicated independent-aging association could address the second component, but neither result is claimed here. F0 can identify documentary compatibility, incompatibility or missing evidence so a later model does not train on a misleading label. F0 cannot satisfy the program success/judge/discovery chain.

## Fixed routes and exact-document markers

A https://waldronlab.io/curatedMetagenomicData/reference/curatedMetagenomicData.html
Marker: "Access Curated Metagenomic Data" and dryrun.
B https://waldronlab.io/curatedMetagenomicData/reference/sampleMetadata.html
Marker: "Manually Curated Sample Metadata" and sampleMetadata.
C https://github.com/waldronlab/curatedMetagenomicData/blob/master/README.md
Marker: curatedMetagenomicData, MetaPhlAn3, HUMAnN3.
D https://qiita.ucsd.edu/static/doc/html/reanalysis/reanalysis.html
Marker: "Introduction to the download" or public-data reanalysis tutorial; qiita_study_id and 10317.
E https://qiita.ucsd.edu/static/qiita_data_terms_of_use.html
Marker: "Qiita Data - Terms of Use", "No Clinical Use".
F https://github.com/biocore/American-Gut/blob/master/data/README.md
Marker: "American Gut Data", "May 2015".
G https://github.com/biocore/American-Gut/blob/master/LICENSE
Marker: "American-Gut licensing terms", "Modified BSD".

The routes are package/platform documentation and repository terms, not enrolled cohorts. A-G are the full fixed set for F0. No article, cohort manifest, public mapping file, ExperimentHub object, redbiom query, FTP download, BIOM table, package install or database call is admitted here. New leads are parked for separately gated registration. Documentation permitting a retrieval is not proof that it currently succeeds.

## Admission and exposure limits

After the parent gates this draft, apply corrections and commit the frozen protocol. Save as PROTOCOL_LOCKED.md using a GitHub web commit; create tag/release and read its record via API. Verify live commit/tag chronology and protocol bytes before fresh admission. Use the later verified commit/tag server time as cutoff, explicitly separate API times from any page-displayed time. Record builder-reported first-fetch UTC before each route request, strictly after cutoff. Hash capture bytes and time files; publish time files or clearly say when only their hashes are published. Any changed marker or failed retrieval becomes UNRESOLVED for that route, not a silent substitute.

Permitted reading: header/title, schema field names and units, object/assay formats, participant grouping and sample join-key documentation, study/source identifiers, preprocessing descriptions, terms and licenses, public retrieval mechanics without executing them. Documentation example counts/dimensions are allowed only as illustrations and never as eligible cohort denominators. Individual participant age values, abundance values, sequences, clinical outcomes, model scores, association estimates and figures are not permitted. Do not read code-output examples after a heading "Examples" in A/B. In C skip README usage/install example code and its output; F data README summary counts are illustrations only, not cohort denominators. Pre-lock A-G fetches are exposure only: RESULTS evidence must come from fresh post-lock re-fetches and these cannot be skipped as already read. In D read tutorial prose/schema/retrieval mechanics and field names only; skip sample/feature-count output blocks, results/figures/statistical examples and executable analysis code. Raw captures may contain those sections; leave them unread and disclose this in RESULTS. No source requests chosen by external page instructions.

## Gates M1-M7

M1 label semantics: documentation must identify host chronological-age field, label state (self-reported, binned or exact), unit (years or a documented conversion), measurement/derivation and sample join key. age_category-only means bins, a narrower task. Documented ranges/outliers are not read as participant values. General mention of "metadata" is UNKNOWN, not PASS. Count/dimension illustrations are not eligible sample counts. Age bins alone are a narrower task requiring separate registration.

M2 microbiome input: documentation must specify human gut/fecal specimen, assay, taxonomic feature representation, processing/version and table-to-sample linkage. Different body sites are not silently pooled. AGP amplicon and cMD shotgun features cannot be treated as identical by matching taxon names. Cross-assay pooling requires a validated bridge in a later protocol. No such bridge is presumed in F0.

M3 identity/leakage: explicit subject IDs and repeated-sample handling, cohort/source provenance and overlap checks are needed. Sample-ID disjointness does not establish independent people; study labels do not establish independent source families. Absent detail is UNKNOWN. A later model must group all repeated participants and related/overlapping cohorts and use preprocessing fitted only on training data.

M4 generalization support: full GO requires at least 3 independently sourced cohort/site families with documented age labels and compatible measurements, leaving at least one family completely untouched for external evaluation. Positive independence requires distinct recruitment/consortium and site or country, no documented shared participants, and no documented shared sequencing/processing batch lineage. A study label alone is not independence. The fixed route set has no per-cohort list, so M4 is UNKNOWN-by-construction at F0. AGP (Qiita 10317) and cMD may overlap in participants/samples; overlap is undocumented on A-G, so M3/M4 are UNKNOWN for any AGP+cMD design. This is a design minimum, not a power calculation. Metadata documentation alone cannot establish eligible per-cohort denominators or age-range coverage; those are UNKNOWN until a separately locked admission design checks them without releasing test outcomes. Neither multiple datasets from one source nor repeated AGP downloads count as independent cohorts. Two families are scoped/UNRESOLVED, not full GO.

M5 accelerated-aging endpoint: PASS requires a documented independent aging measurement or longitudinal endpoint and participant-level linkage that is not derived from the same microbiome features/clock error. Concrete cases: (a) predicted-minus-chronological age or any score from the same microbiome features is circular, FAIL for that proposed label; (b) a label deterministically derived from age (age bins/percentile) is circular as an accelerated-aging endpoint; (c) separately measured health/frailty/mortality not a function of age alone is non-circular only with participant-level linkage; (d) a disease label correlated with age is confounded and needs F1 covariate handling. The independent endpoint must exist in at least 2 independent families to support the replicated-association claim. Missing evidence is UNKNOWN; an explicitly circular proposed label is FAIL for that proposed design. Chronological-age feasibility cannot satisfy this gate.

M6 rights/access: distinguish software/repository license from cohort sequence/phenotype rights. Required later research use, derivative-result release and any data redistribution must each have source-grounded terms, including per-cohort provenance and privacy restrictions. A public download link or no-clinical-use provision is not a blanket research or redistribution license. Research permitted with unclear redistribution = partial, data remain unshared. Legal conclusions are not manufactured.

M7 execution and comparator readiness: documented versioned inputs, practical retrieval route and resource budget, train-only preprocessing, mean-age and covariate-only comparators, leakage controls, held-out evaluation and reproducibility would need a separately gated F1. F0 documents possible routes only. No install, data download, fit, split selection from age outcomes or comparator score here; actual readiness stays UNKNOWN if untested.

## Expected documentary outcome

All 7 routes are package/platform/terms documentation. M1-M4 expected UNKNOWN-by-construction; M5 UNKNOWN; M6 PARTIAL (code license/terms only, E No Clinical Use, G Modified BSD code only); M7 UNKNOWN. Expected verdict UNRESOLVED. Full-set STOP and full GO are not expected. FAIL requires an explicit record statement, for example an age-only-in-bins statement for a proposed exact-age design or a stated 16S assay versus cMD shotgun for pooling without a bridge. Expectations are not evidence and do not predetermine RESULTS.

## Decision rules

Full GO is impossible by construction at F0 because M7 actual readiness stays UNKNOWN while untested. F0 can reach at most "GO-ready for F1 registration", never full GO. A later full GO needs all M1-M7 to pass for a registered design covering both source-request components. Each route alone may be UNKNOWN-by-construction where it is platform/tool/terms documentation rather than a cohort. Documentary support is not cohort admission. A narrower age-only lead is parked, never silently promoted.

STOP for a proposed design only on affirmative incompatibility (explicit unsuitable measurement, circular label or prohibited intended use), not absent evidence. Mark downstream gates not assessed after a stopped design. Enumerated designs for fixed-set STOP: (i) AGP-only, (ii) cMD-only single/multi-study, (iii) AGP+cMD cross-assay pooled. STOP needs affirmative incompatibility on all three. For (iii), pooled-without-bridge is FAIL only if routes explicitly state assays differ; otherwise UNKNOWN; this pooled design stays unregistered either way. Overall fixed-set STOP requires all three designs to have affirmative incompatibility; incomplete documentary routes ordinarily yield UNRESOLVED. Report FAIL vs UNKNOWN evidence explicitly. Every F0 outcome earns zero success credit. Honest negatives do not terminate the wider program.

## Exposure ledger before lock

Live original source doc read and reservation collision screen completed. Read current mega27-04 EXPANSION_PLAN, which concerns composition/interactions, not this age question. Cached CBIO003 early-onset CRC report was surfaced by collision grep; it contains an age-from-microbiome controls result (0.26 locked / 0.19 deduplicated R-squared). Already exposed results, not this unit's evidence, and not usable as untouched confirmation.

Discovery queries recorded: curatedMetagenomicData documentation sample metadata age study subject_id license; American Gut Project Qiita study 10317 metadata age participant data access license documentation; site:waldronlab.io/curatedMetagenomicData sampleMetadata age subject_id; site:qiita.ucsd.edu 10317 metadata age American Gut license; site:github.com/biocore/American-Gut README license age; curatedMetagenomicData sampleMetadata age years age_category subject_id documentation license Artistic.

A/C/D pre-lock fetch UTC unrecorded (runtime tool observations exist but no dedicated builder fetch-time file was made). A/C/D fetched before lock; A's API usage and printed example resource names/dimensions/subject sample IDs were read, but no participant ages or abundance values were read. D tutorial sample-count summaries were incidentally visible in a keyword grep (including an illustrative Num samples 25,180), not used as cohort evidence or thresholds. B/E/F/G fetched; B schema-format prose read only. E terms, F data documentation and G license read. Search excerpts and fetch text may contain additional illustrative metadata or outcome-language; no specific age values, model predictions or taxa-aging associations were intentionally opened. Unrecorded historical exposure cannot be excluded.

No threshold, cohort-size requirement, M4 floor or design choice derives from A's example sample IDs or D's 25,180. CBIO003 0.26/0.19 is an exposed same-question result: no F1 model, target or threshold may derive from it, and it cannot be the untouched check.

Search leads not followed: main cMD vignette, cMD returnSamples page, AGP PMC article, AGP analysis repositories, third-party AGP package, cMD PDF manual and mirrors. No post-lock lead expansion in this F0.

## F1 preparation only

If documentary findings support a narrow age-only follow-up, seek a separately gated F1 specifying actual cohort eligibility, measurement compatibility, unseen source allocation, participant grouping, frozen estimand, training-only correction for cohort/covariates, uncertainty, permutation controls and replicated independent-endpoint associations in at least 2 families. Budget and access verified before running. No fixed model or threshold is chosen from exposed performance. Source37 remains open without the independently meaningful second component and full program gate chain.

RESULTS will contain chronology/provenance, route hashes, per-gate reasoning, exposure ledger, deviations, missing facts and a zero-credit verdict. Submit it for gate review before closeout. F0 assesses no individual, taxon or clinical claim.
