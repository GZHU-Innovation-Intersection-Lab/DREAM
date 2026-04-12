# Dataset schema

## Primary file

- `dream_initial_labels_1134.csv`

## Column definitions

- `row_id`: release row index
- `incident_id`: incident identifier used in the study
- `date`: incident date in the source table
- `title`: short incident title
- `description`: short incident description
- `Risk Domain`: top-level incident domain
- `Risk Subdomain`: incident subdomain
- `Da`: damage-related score
- `A`: affectedness-related score
- `R`: reproducibility-related score
- `E`: exploitability-related score
- `Di`: discoverability-related score
- `M`: mitigation-difficulty-related score
- `gemini_complete`: completeness flag for one evaluator stream
- `gpt_complete`: completeness flag for one evaluator stream
- `qwen_complete`: completeness flag for one evaluator stream
- `avg_complete`: whether the released averaged row is complete
- `all_three_model_complete`: whether all three evaluator streams were present
- `at_least_two_model_complete`: whether at least two evaluator streams were present
- `avg_alignment_max_abs_diff`: alignment diagnostic for the averaged release view

## Release boundary

This schema describes only the initial labeling table released during peer review. Additional validation outputs, expert-panel materials, and code are planned for release after article acceptance.
