# Reproducibility Analysis in the Psilocybin Neuroimaging Pipeline

A neuroimaging methods project evaluating how preprocessing, atlas selection, statistical thresholds, and analytical decisions influence conclusions in psilocybin brain imaging research.

This repository completes the psychedelic neuroplasticity track by focusing on robustness, transparency, and the reliability of findings across alternative analysis pipelines.

## Project Aim

To test whether commonly reported psilocybin neuroimaging findings remain stable under reasonable methodological variation, and to establish a reproducibility-focused framework for future open neuroscience research.

## Dataset Used

- Domain: Psychedelic Neuroplasticity  
- Focus: Reproducibility of functional connectivity findings  
- Reference Dataset: OpenNeuro ds006072  
- Population: Healthy adult participants  
- Design: Multi-pipeline methodological sensitivity framework  
- Modalities Referenced: Resting-state fMRI, network-level analyses

## Analytical Scope

This repository focuses on a proof-of-concept framework using:

- Pipeline decision landscape mapping
- Preprocessing sensitivity analysis
- Atlas and connectivity metric comparison
- Statistical inference robustness testing
- Integrated reproducibility summary reporting

## Why a Reproducibility Pipeline Was Used

Single analytical pipelines can create false certainty. A reproducibility pipeline was used to test whether observed conclusions persist across alternative but defensible methodological choices.

This preserves the central scientific question: are reported neural effects robust or pipeline-dependent?

Future repositories may extend this framework using preregistration, multi-lab replication, and raw-data reprocessing at scale.

## Methods

The repository used a lightweight and scalable workflow:

- Map common methodological decision points
- Compare effect estimates across preprocessing variants
- Test atlas and metric sensitivity
- Evaluate significance under correction strategies
- Summarize robustness across analytical dimensions

## Main Findings

- Effect direction was more stable than exact effect magnitude
- Atlas selection influenced reproducibility scores meaningfully
- Preprocessing choices altered some network estimates
- Statistical correction methods changed significance conclusions
- Transparent multi-pipeline reporting improves interpretability

## Repository Workflow

### Notebook 1 - Pipeline Decision Landscape

Mapped common preprocessing and analysis choices with reproducibility risk points.

### Notebook 2 - Preprocessing Sensitivity Analysis

Tested how preprocessing variants changed network effect estimates.

### Notebook 3 - Atlas Model Comparison

Compared atlas and connectivity metric combinations.

### Notebook 4 - Statistical Inference Robustness

Assessed how correction methods altered significance conclusions.

### Notebook 5 - Reproducibility Summary Report

Integrated findings into a final robustness framework.

## Limitations

- Proof-of-concept methodological simulation framework
- Network-level rather than voxel-wise replication testing
- Illustrative sensitivity values rather than full raw reprocessing
- Focused on resting-state style analyses

## Future Directions

- Full raw-data multi-pipeline reprocessing
- Pre-registered confirmatory analyses
- Cross-dataset psychedelic replication studies
- Multi-site harmonization benchmarking
- Automated reproducibility dashboards

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- SciPy
- Google Colab

## Maintained By

Aditya Sundaray
