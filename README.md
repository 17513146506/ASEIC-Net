# ASEIC-Net

ASEIC-Net is a heterogeneity-aware multi-instance learning framework for
multi-output quality prediction from LIBS measurements of unpressed granular coal.

It jointly models observation-level, feature-level, and task-level heterogeneity
through relevance-aware multi-instance aggregation, domain-informed spectral
enhancement, and quality-specific element–indicator modeling.

ASEIC-Net achieves R² values of 0.96, 0.94, 0.95, 0.89, and 0.94 on the
source-region test set. After regional adaptation, it achieves R² values of
0.92, 0.94, 0.89, 0.89, and 0.93 on 50 newly collected coal samples evaluated
through a conveyor-based online inspection workflow.

Approximately 5 kg of 6-mm unpressed granular coal can be measured within
about 80 s per inspection without pelletization.

## Availability

If the associated paper is accepted, the full code implementation and a small
set of example industrial field data will be released in this repository.
