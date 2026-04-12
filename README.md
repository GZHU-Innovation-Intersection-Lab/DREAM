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
| `CITATION.cff` | Machine-readable citation metadata for the repository |

## Data summary

The released CSV contains:

- 1,134 incident records
- six-dimensional scores: `Da`, `A`, `R`, `E`, `Di`, `M`
- incident descriptors including date, title, description, risk domain, and risk subdomain
- completeness and alignment fields retained from the study pipeline

Direct download:

- [dream_initial_labels_1134.csv](https://raw.githubusercontent.com/GZHU-Innovation-Intersection-Lab/DREAM/main/dream_initial_labels_1134.csv)

## Release boundary

This repository currently releases only the initial labeling table used at the manuscript input stage.

It does **not** yet include the full validation package, expert-panel materials, proxy-validation artifacts, or code.

All remaining data products and code will be released after article acceptance.

## Citation

If you use this repository or dataset, please cite:

- this GitHub repository release
- the associated DREAM manuscript

Citation metadata are provided in `CITATION.cff`.

## Contact

Corresponding author: Jiayin Qi  
The Cyberspace Institute of Advanced Technology, Guangzhou University  
Email: qijiayin@139.com
