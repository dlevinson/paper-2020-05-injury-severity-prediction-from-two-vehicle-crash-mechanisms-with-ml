# Injury Severity Prediction From Two-Vehicle Crash Mechanisms With ML

This package is a public-ready archival package for the available local materials associated with Ji and Levinson (2020), IEEE Open Journal of Intelligent Transportation Systems, DOI: https://doi.org/10.1109/OJITS.2020.3033523.

## Contents

- `paper/Injury_Severity_Prediction_Two_Vehicle_Crash_ML.pdf`: local article PDF copy available during the audit.
- `data/derived_results/model_accuracy_summary_from_different_algorithms.csv`: modern CSV extract from Ang Ji's Dropbox workbook `ML Accuracy and Var.Imp/Different Algorithms.xlsx`, recording model accuracy/AUC/sensitivity/specificity summaries.
- `metadata/PUBLIC_REFERENCE_LINKS.csv`: DOI and public NHTSA NASS/CDS source-data pointers.
- `metadata/SOURCE_FILE_DECISIONS.csv`: source files checked and archive decisions.
- `metadata/SEARCH_LOG.csv`: audit trail for the local/Dropbox/online search.

## Data and Code Boundary

The paper states that the empirical source data are public NHTSA NASS/CDS crash records from 2009-2015. Those agency-maintained raw files are not duplicated here. The paper-specific modeling extract and executable analysis scripts were not found in the local source folder or the checked Ang Ji Dropbox folders.

The staged CSV is a derived-results summary, not a complete reproduction pipeline. This package is therefore ready for public upload as the available paper-associated material plus public source-data pointers, with the limitation that no executable modeling script was found.

## Rights and Privacy

No personal or restricted crash-level records are staged. NHTSA describes public NASS files as excluding direct personal identifiers.



<!-- topic-shared-source: two-vehicle-crash-injury-severity-nass-cds-2020 -->
## Ang Ji Dissertation Source Update

Ang Ji provided a paper-sorted dissertation-folder export and described this bundle as final code/data for this paper family.

Shared source staged in this repository:

`../../../_shared_sources/two-vehicle-crash-injury-severity-nass-cds-2020`

Shared source ID: `two-vehicle-crash-injury-severity-nass-cds-2020`

What was added:

- `files/injury_severity_energy_loss_2020/`: received code/data/results files.
- `SOURCE_MANIFEST.csv`: per-file source path, staged path, size, SHA-256, role, and Git LFS recommendation.
- `SOURCE_PROVENANCE_NOTE.md`: provenance note from Ang's explanation.
- `GIT_LFS_RECOMMENDATIONS.gitattributes`: patterns to review before GitHub upload.

Release and validation status:

public_candidate_with_git_lfs_and_source_data_provenance_review

Validation note:

Ang Ji stated these two 2020 papers use the same open-access NASS/CDS dataset and similar processing methods; the R and data files were kept together because the workflows are mixed.
<!-- /topic-shared-source: two-vehicle-crash-injury-severity-nass-cds-2020 -->

<!-- package-hardening-status:start -->
## Package Hardening Status

Generated: 2026-05-20 13:31:26 AEST

- Pipeline: `READY-TO-UPLOAD/PUBLIC`
- Sidecars added/updated: `PACKAGE_STATUS.md`, `PACKAGE_MANIFEST.csv`, `LICENSE_STATUS.md`.
- Paper reference copies are for local audit convenience and are not public-upload assets without rights review.
- Final GitHub upload should use the manifest include statuses and the license-status note.
<!-- package-hardening-status:end -->
