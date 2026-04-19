# E156 Protocol — `ctgov-country-condition-hiddenness`

This repository is the source code and dashboard backing an E156 micro-paper on the [E156 Student Board](https://mahmood726-cyber.github.io/e156/students.html).

---

## `[199]` CT.gov Country-Condition Hiddenness

**Type:** methods  |  ESTIMAND: 2-year no-results rate across selected country-by-condition cells among eligible older CT.gov studies  
**Data:** 249,507 eligible older closed interventional studies exploded into named-country condition-family cells

### 156-word body

Which disease-country cells look quietest on ClinicalTrials.gov once older closed interventional studies are split simultaneously by condition family and named study location? We analysed 249,507 eligible older closed interventional studies from the March 29, 2026 full-registry snapshot and exploded named-country involvement within selected condition families. The project compares two-year no-results rates, ghost-protocol rates, and visible shares for oncology, cardiovascular, and metabolic studies across country-condition cells with at least 400 studies. Oncology studies involving China reached 79.0 percent no results versus 52.6 percent for oncology studies involving the United States. Cardiovascular studies involving Egypt reached 95.9 percent no results, while metabolic studies involving China reached 78.9 percent and Denmark 79.6 percent. Disease and geography therefore interact rather than add independently, because the same condition family looks materially different once specific country footprints are named inside the same nominal therapeutic area. Country-condition cells reflect recorded study locations rather than country-specific enrollment shares, sponsor domicile, or national reporting mandates.

### Submission metadata

```
Corresponding author: Mahmood Ahmad <mahmood.ahmad2@nhs.net>
ORCID: 0000-0001-9107-3704
Affiliation: Tahir Heart Institute, Rabwah, Pakistan

Links:
  Code:      https://github.com/mahmood726-cyber/ctgov-country-condition-hiddenness
  Protocol:  https://github.com/mahmood726-cyber/ctgov-country-condition-hiddenness/blob/main/E156-PROTOCOL.md
  Dashboard: https://mahmood726-cyber.github.io/ctgov-country-condition-hiddenness/

References (topic pack: network meta-analysis):
  1. Rücker G. 2012. Network meta-analysis, electrical networks and graph theory. Res Synth Methods. 3(4):312-324. doi:10.1002/jrsm.1058
  2. Lu G, Ades AE. 2006. Assessing evidence inconsistency in mixed treatment comparisons. J Am Stat Assoc. 101(474):447-459. doi:10.1198/016214505000001302

Data availability: No patient-level data used. Analysis derived exclusively
  from publicly available aggregate records. All source identifiers are in
  the protocol document linked above.

Ethics: Not required. Study uses only publicly available aggregate data; no
  human participants; no patient-identifiable information; no individual-
  participant data. No institutional review board approval sought or required
  under standard research-ethics guidelines for secondary methodological
  research on published literature.

Funding: None.

Competing interests: MA serves on the editorial board of Synthēsis (the
  target journal); MA had no role in editorial decisions on this
  manuscript, which was handled by an independent editor of the journal.

Author contributions (CRediT):
  [STUDENT REWRITER, first author] — Writing – original draft, Writing –
    review & editing, Validation.
  [SUPERVISING FACULTY, last/senior author] — Supervision, Validation,
    Writing – review & editing.
  Mahmood Ahmad (middle author, NOT first or last) — Conceptualization,
    Methodology, Software, Data curation, Formal analysis, Resources.

AI disclosure: Computational tooling (including AI-assisted coding via
  Claude Code [Anthropic]) was used to develop analysis scripts and assist
  with data extraction. The final manuscript was human-written, reviewed,
  and approved by the author; the submitted text is not AI-generated. All
  quantitative claims were verified against source data; cross-validation
  was performed where applicable. The author retains full responsibility for
  the final content.

Preprint: Not preprinted.

Reporting checklist: PRISMA 2020 (methods-paper variant — reports on review corpus).

Target journal: ◆ Synthēsis (https://www.synthesis-medicine.org/index.php/journal)
  Section: Methods Note — submit the 156-word E156 body verbatim as the main text.
  The journal caps main text at ≤400 words; E156's 156-word, 7-sentence
  contract sits well inside that ceiling. Do NOT pad to 400 — the
  micro-paper length is the point of the format.

Manuscript license: CC-BY-4.0.
Code license: MIT.

SUBMITTED: [ ]
```


---

_Auto-generated from the workbook by `C:/E156/scripts/create_missing_protocols.py`. If something is wrong, edit `rewrite-workbook.txt` and re-run the script — it will overwrite this file via the GitHub API._