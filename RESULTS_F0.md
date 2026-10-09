# DOC-1-037 F0 RESULTS: microbiome aging-clock documentation audit

Unit: source position 37, A "Microbiome Clock" for Aging. Source request covers chronological host-age prediction and taxa associated with accelerated aging. This is the registered F0 documentation-only audit, not an implemented age predictor or association study. No participant age values, abundance values, sequences, clinical outcomes, model predictions or age scores opened. Research only, no clinical use or health assessment. Zero scientific success credit.

## Verdict

UNRESOLVED on the fixed A-G documentary set. Full GO is impossible by construction at F0 because actual F1 readiness remains untested/UNKNOWN. The records do not support even a complete GO-ready F1 registration yet: age measurement/unit, cohort independence/overlap, independent accelerated-aging endpoint, data rights and execution readiness remain unresolved.

This is not a full-set STOP. No affirmative incompatibility was established for all three enumerated designs (AGP-only, cMD-only single/multi-study, AGP+cMD pooled). None is registered for fitting. The pooled-without-bridge design remains UNKNOWN and unregistered: D explicitly describes AGP 16S V4, but the permitted C extract describes MetaPhlAn3/HUMAnN3 without explicitly stating the cMD assay is shotgun. That missing explicit statement cannot be supplied from general knowledge to trigger FAIL.

Predicted-minus-chronological age, a score built from the same microbiome features, age bins/percentiles or age correlation alone cannot support the requested biological accelerated-aging interpretation. Those proposed labels would be circular under M5. No such label or taxon claim was tested. Separately measured health/frailty/mortality linked at participant level and not a function of age alone would be non-circular in principle; it must exist in at least two independent families for a replicated-association claim. A disease label correlated with age would need F1 confounder handling. No qualifying endpoint is established by A-G.

## Lock, chronology and provenance

- Frozen protocol: PROTOCOL_LOCKED.md, commit 8ea493f33154da32164080731ebdfe07cb5812cc, GitHub API commit time 2026-10-09T22:15:01Z.
- Release f0-protocol-lock API created_at 2026-10-09T22:15:01Z, published_at 2026-10-09T22:15:28Z. Lightweight tag ref points to the same commit. Conservative chronology cutoff: later API published_at 22:15:28Z. No page-displayed time is treated as API time.
- Tagged protocol readback byte-identical, SHA256 e873b8edf842ab15bbbc16cd4a8b31d11c8dcd68f6c0eaf3817b1a40813fa08e.
- Builder-reported first-fetch UTC A-C: 2026-10-09T22:15:41Z; D-G: 2026-10-09T22:15:42Z. Both strictly after cutoff. These time files are not published; only their hashes below are published. They are builder records, not independently attested source timestamps.
- A-G were freshly re-fetched after lock. All exact-document markers matched. Pre-lock fetches are exposure, not RESULTS evidence.
- Lock gate SCOPED PASS received after admission; draft gate had already authorized locking and admission. No values or fitting occurred. The frozen admission prose retains the stale phrase "After the parent gates this draft"; RESULTS does not adopt that wording as current status.

## Fixed route records and raw-capture hashes

Hashes are SHA256 over the individually separated fetched UTF-8 Markdown route text, preserving each fetch header. Group captures/time-file hashes follow. Raw captures are private working evidence, not public datasets.

- A https://waldronlab.io/curatedMetagenomicData/reference/curatedMetagenomicData.html
  - Capture SHA256: 14f00c90cd0346d4412038d201705508f8a5514167d5ef901986df4cd441be0d
- B https://waldronlab.io/curatedMetagenomicData/reference/sampleMetadata.html
  - Capture SHA256: 6f64e252f87471a9c6680ef92964f275bbbb0f5ce1bfaa0919c3b6452e22c63b
- C https://github.com/waldronlab/curatedMetagenomicData/blob/master/README.md
  - Capture SHA256: 735fc1e12fd8dccc4a3adc9879a59940ba5fe985552fc381bcaf63cc5906b724
- D https://qiita.ucsd.edu/static/doc/html/reanalysis/reanalysis.html
  - Capture SHA256: b3cec16dac147fc59f0dd06466bb31792980523a48af6de2ce24035432b04164
- E https://qiita.ucsd.edu/static/qiita_data_terms_of_use.html
  - Capture SHA256: 167400be55f1af74844bd316c5487c665bb138f84c9f4ad653b2712caefea071
- F https://github.com/biocore/American-Gut/blob/master/data/README.md
  - Capture SHA256: 81c992400e636a010a236c89cb3838e216d39083a09e21ecda31efc5f7a045ef
- G https://github.com/biocore/American-Gut/blob/master/LICENSE
  - Capture SHA256: 9471b243335630e422a3811d3e7b0067727e51eb46ea44b9162b261db1ae8717
- A-C.txt: 0e047f9b94a968af73b108dc23da4ffecc4a118d165610327505b8e59166d0a8
- D-G.txt: 21b85b06d3eeacb586453335455453d3895e90f10f27be15b74bfafb706c2179
- A-C-first-fetch-utc.txt: 6a86c6c82e754b57e764ea5a4f06aaf7f358fa907f3250007a4f6942832775eb
- D-G-first-fetch-utc.txt: cac23873bc9edc8588c725e48504e6cf21d5230bf6ea5cfa333d7f8cd3a210dd

## Per-route gates and documentary support

M1-M4 are UNKNOWN-by-construction for cohort admission across this documentation set. Documentary fragments below are not an exception to that classification. M5 independent endpoint UNKNOWN throughout. M7 actual readiness UNKNOWN throughout because no route retrieval, resource budget, split, training or comparator execution was tested. M6 partial terms evidence does not license all cohort data.

| Route | Permitted documentary support | Remaining gates |
|---|---|---|
| A cMD access reference | dryrun resource-name discovery; study-level ExperimentHub matrices with metadata; relative_abundance representations and row-name modes. Documentation says counts are rounded read-depth-scaled proportions, not proof of raw integer counts. | M1 age field/unit not established. M2 specific fecal cohort/assay/linkage incomplete. M3/M4 identity/independence not established. M5 UNKNOWN. M6 UNKNOWN. M7 UNKNOWN. |
| B sampleMetadata reference | manually curated data.frame schema description, 22588 rows and 141 columns as documentation object dimensions only. | No participant values or eligible cohort denominators inferred. M1-M5 UNKNOWN, M6 UNKNOWN, M7 UNKNOWN. |
| C cMD README | human microbiome samples from different body sites; taxonomic profiles calculated with MetaPhlAn3, functional potential with HUMAnN3; metadata packaged in (Tree)SummarizedExperiment. | Not a gut-only eligible cohort list; age field, unit, exact/self-reported/binned status absent from permitted extract. Assay not explicitly shotgun in this extract. M1-M5 UNKNOWN, M6 UNKNOWN, M7 UNKNOWN. |
| D Qiita reanalysis tutorial | AGP identified as study 10317; sample metadata/feature-table retrieval described; AGP assay V4 16S, Illumina, 150nt, deblur; host_subject_id field and duplicate-subject handling illustration. | A field/illustration is not verified participant lineage or age linkage. Gut-only restriction and exact-age status not verified for eligible cohort rows. AGP/cMD overlap undocumented. M1-M5 UNKNOWN; M6 UNKNOWN apart from E terms; M7 UNKNOWN. |
| E Qiita terms | research-only, no clinical use including health assessment; data ownership/rights responsibilities and transfer restrictions; platform states data may be re-annotated. | Terms do not establish cohort rights for proposed research/derivative release/redistribution. M1-M5 UNKNOWN-by-construction, M6 PARTIAL/UNKNOWN, M7 UNKNOWN. No legal agreement or upload performed. |
| F AGP data README | de-identified OTU and QIIME mapping files; old repository tables unchanged since May 2015; Greengenes 13_8/97% SortMeRNA; contextual HMP/Global Gut/PGP sources. Different versions are not interchangeable. | Listed sources not an independently recruited age-cohort eligibility list. Date/data-format prose and illustrative processing depths not sample denominators. FTP not followed. M1-M5 UNKNOWN, M6 UNKNOWN, M7 UNKNOWN. |
| G AGP LICENSE | Modified BSD software/source/binary terms. | Software terms not a proved cohort phenotype/sequence license. M1-M5 UNKNOWN-by-construction, M6 PARTIAL/code-only, M7 UNKNOWN. |

M4 positive independence requires distinct recruitment/consortium and site or country, no documented shared people, no documented shared sequencing/processing batch lineage. A label alone is insufficient. The route set has no per-cohort list, so the locked >=3-family floor and untouched-family requirement cannot be assessed. AGP and cMD may overlap; A-G do not establish otherwise, so M3/M4 are UNKNOWN for their combination. A minimum family floor is not a power calculation and the documentation dimensions/sample counts are not eligible denominators.

## Enumerated design disposition and FAIL versus UNKNOWN

1. AGP-only: UNRESOLVED. Specific chronological-age label state/unit, eligible participants, independent family coverage, endpoint and rights remain unknown. Public retrieval documentation is not actual readiness.
2. cMD-only single/multi-study: UNRESOLVED. Study-level packaging supports a possible route but does not establish eligible cohorts, exact-age state/unit, independent families, independent aging endpoint or per-cohort rights. Single/multi-study names are not admissions.
3. AGP+cMD cross-assay pooled: UNKNOWN/unregistered. No validated bridge or participant overlap audit. D's 16S statement plus C's pipeline description is insufficient under the locked explicit-assay-difference FAIL rule. No pooling performed.

There is no affirmative route-based FAIL establishing fixed-set STOP. The circular M5 cases and explicit-assay-difference case are pre-stated decision rules, not observed failures from executed designs. Absence is UNKNOWN, not incompatibility. Neither narrower chronological-age-only work nor alternate data sources are promoted here.

## Reading limits, exposure and deviations

Pre-lock exposure ledger is retained verbatim in the frozen protocol: A-G were discovered/fetched before lock; A illustrative resources/sample IDs/dimensions and D tutorial counts were seen, not used to set thresholds, cohort sizes, M4 floor or design. Pre-lock A/C/D fetch UTC times are unrecorded; no dedicated time files were made. Discovery queries and unvisited leads are listed in the protocol. Unrecorded historical exposure cannot be excluded.

The collision screen exposed CBIO003 controls age-prediction R-squared 0.26/0.19. This is an exposed same-question result, not an untouched check. No F1 model, target, threshold or design derives from it; its data could not later be relabeled unseen confirmation.

Post-lock raw A contains Examples text left unread; C retains usage/install examples left unread; D retains count/output/analysis/figure sections left unread apart from the extraction deviations below. B object dimensions and F processing-depth/debug-subset illustrations were read, but are not cohort eligibility counts. No raw capture of public examples is treated as an enrolled dataset.

Deviations:
- D's initial field-name extraction included a duplicate-subject example code line containing host_subject_id. It was seen, never executed, and removed from the curated extract. Only the field name and documentary grouping illustration are used.
- A second D extraction to recover study 10317 incidentally displayed exercise-category illustrative counts (1510, 28017, 26027) and command text. They were seen, not executed or used for any gate or design threshold, then removed from curated evidence. This broad substring extraction was too permissive; final extract uses only predefined documentary facts.
- These are tutorial examples, not participant ages/abundances or age-prediction outcomes. All unrelated tutorial model/statistical outputs remain unread during admission. No analysis code, redbiom request, package install, FTP download, data table or mapping-file read occurred.

## Closeout scope

F0 outcome: UNRESOLVED, documentation-only, zero success credit. No microbiome clock or accelerated-aging taxa result exists from this unit. No clinical claim, fit, split, scoring, participant health assessment or biological discovery. Original source37 remains open. A new F1 would need its own gated protocol, cohort rights and lineage audit, untouched-source evaluation and independent endpoint in >=2 families for the replicated-association component. Honest unresolved findings are preserved; they do not terminate the wider program.
