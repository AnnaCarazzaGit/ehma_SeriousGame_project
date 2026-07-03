# Personas Analysis

This folder contains the persona analysis workflow developed to support the design of an educational serious game on addictions.

The analysis is based on an eHealth questionnaire dataset and is used to identify representative user profiles through preprocessing, psychometric score aggregation, dimensionality reduction, clustering, and persona interpretation. The resulting personas support user-centered design decisions for the serious game, including addiction-related mechanics, difficulty balancing, educational framing, and content adaptation.

## Files

- `EHealthGroup10Personas.ipynb`: Jupyter Notebook containing the full persona analysis workflow.
- `questionnaire_codebook_eHealth20252026.xlsx`: codebook describing the questionnaire items, variable names, response types, and codification options.
- `dataset_project_eHealth20252026.csv`: dataset required to run the notebook. This file is not included in the repository because it may contain sensitive questionnaire data.

## Data availability

The dataset used in this analysis is excluded from the public repository to avoid sharing potentially sensitive questionnaire data.

To run the notebook locally, place the dataset in this folder with the following exact filename:

```text
dataset_project_eHealth20252026.csv
```

The notebook expects the dataset and the codebook to be located in the same folder as the notebook.

## Analysis overview

The notebook includes the following steps:

1. Loading of the questionnaire dataset and the related codebook.
2. Identification and organization of demographic and questionnaire-related variables.
3. Computation of aggregated scores from psychometric questionnaire items.
4. Preprocessing of numerical and categorical features.
5. Dimensionality reduction and clustering.
6. Interpretation of clusters as representative user personas.
7. Export and visualization of persona-related results.

## Purpose within the serious game project

The persona analysis was used to better understand possible target users and their characteristics. This helped guide the design of the serious game by connecting questionnaire-based user profiles with gameplay and educational design choices.

In particular, the personas support:

- definition of representative player profiles;
- identification of different addiction-related risk patterns;
- adaptation of educational content to different user needs;
- design of game mechanics related to awareness, decision-making, and behavioral consequences;
- improvement of the user-centered design rationale of the project.

## Notes

This analysis was developed for academic and educational purposes as part of an eHealth serious game project.

If the dataset is shared in the future, it should only be included if it is fully anonymized and if public redistribution is explicitly allowed.
