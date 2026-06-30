### Data Processing Log LingzhiGuo & Zhao Sirui — 30 June 2026

* Merged the independently cleaned A and B OpenRefine projects into one final dataset.
* Used `Aleph system no.` as the primary matching key for the merge.
* Verified the matched records with `DOM ID` as a second checking key.
* Confirmed that all 980 records were matched one-to-one, with no duplicated or missing rows.
* Added the B-cleaned fields, including cleaned titles, author names, author life dates, other-author structure, Wikidata QIDs, Wikidata labels, and reconciliation status.
* Checked the merged dataset and preserved the original 980-record structure.

### Data Processing Log Zhao Sirui — 26 June 2026

Cleaned and structured the `Imprint` field.
- Extracted publication year, publication place, and publisher information.
- Created `Publication_place_final`, `Publisher_clean`, and `Publisher_role`.
- Performed QA for complex imprint statements and retained uncertain or multi-place records.
- Added a manually verified Wikidata QID sample for major publication places.

### Data Processing Log LingzhiGuo — 24 June 2026

* Reviewed and refined the OpenRefine data-cleaning workflow.
* Cleaned and standardised the `Title`, `Personal author`, and `Other personal authors` columns.
* Manually reviewed irregular author records and corrected name variants.
* Reconciled cleaned author names with Wikidata and extracted matched QIDs.
* Validated the final results and updated the cleaning log.
