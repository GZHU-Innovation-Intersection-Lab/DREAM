# DREAM initial labeling dataset

This repository provides the peer-review-stage public data release for the manuscript:

**DREAM: Deployment-Time Priority Stratification, Review Routing, and Threshold Adaptation for Generative AI Incidents**

The current release contains the initial incident-level labeling table used as the manuscript input layer. It includes 1,134 generative AI incident records together with the six-dimensional scores `Da`, `A`, `R`, `E`, `Di`, and `M`.

## Repository contents

| File | Purpose |
| --- | --- |
| `dream_initial_labels_1134.csv` | Public release of the initial 1,134-incident labeling dataset |
| `DATASET_SCHEMA.md` | Column-level description of the released dataset |
| `RELEASE_NOTE.md` | Release boundary and post-acceptance expansion note |
| `DATA_AVAILABILITY.md` | Submission-ready statement of what is released now and what will follow |
| `CHANGELOG.md` | Versioned update record for the public data release |
| `LICENSE` | Dataset license text for the current public release |
| `CITATION.cff` | Machine-readable citation metadata for the repository |
| `SHA256SUMS.txt` | SHA256 checksums for the public release files |

## Data summary

The released CSV contains:

- 1,134 incident records
- six-dimensional scores: `Da`, `A`, `R`, `E`, `Di`, `M`
- incident descriptors including date, title, description, risk domain, and risk subdomain
- completeness and alignment fields retained from the study pipeline

Direct download:

- [dream_initial_labels_1134.csv](https://raw.githubusercontent.com/GZHU-Innovation-Intersection-Lab/DREAM/main/dream_initial_labels_1134.csv)

Complete release package:

- [GitHub release page](https://github.com/GZHU-Innovation-Intersection-Lab/DREAM/releases/tag/v0.1.0-peer-review)
- [DREAM_initial_labeling_dataset_v0.1.0_peer_review.zip](https://github.com/GZHU-Innovation-Intersection-Lab/DREAM/releases/download/v0.1.0-peer-review/DREAM_initial_labeling_dataset_v0.1.0_peer_review.zip)

## Integrity check

The repository provides `SHA256SUMS.txt` so users can verify that the downloaded files match the public release.

- [SHA256SUMS.txt](https://raw.githubusercontent.com/GZHU-Innovation-Intersection-Lab/DREAM/main/SHA256SUMS.txt)

Example verification on a local machine:

```bash
sha256sum -c SHA256SUMS.txt
```

## Release boundary

This repository currently releases only the initial labeling table used at the manuscript input stage.

It does **not** yet include the full validation package, expert-panel materials, proxy-validation artifacts, or code.

All remaining data products and code will be released after article acceptance.

Additional release-context documents:

- `DATA_AVAILABILITY.md`
- `CHANGELOG.md`

## Citation

If you use this repository or dataset, please cite:

- this GitHub repository release
- the associated DREAM manuscript

Citation metadata are provided in `CITATION.cff`.

## License

The dataset materials currently released in this repository are provided under the
[Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/).

This choice is intended for the current data release. If code is added in a later
post-acceptance expansion, code files may be marked under a separate software
license where appropriate.

## Contact

Corresponding author: Jiayin Qi  
The Cyberspace Institute of Advanced Technology, Guangzhou University  
Email: qijiayin@139.com
