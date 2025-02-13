# CI_CD_Pipeline

# Bioinformatics CI/CD Pipeline

This repository demonstrates a bioinformatics data analysis pipeline using GitHub Actions for CI/CD.

## Setup
1. Clone this repository.
2. Ensure that you have the necessary R and Python scripts in the `src` folder.
3. The pipeline is triggered on push to the `main` branch or on pull requests targeting `main`.

## Requirements
- Python 3.8+
- R (with required packages: `dplyr`, `ggplot2`, `data.table`)

## Running the Pipeline
The pipeline runs automatically via GitHub Actions whenever there is a push or pull request to the `main` branch.

### Outputs
The pipeline generates output files in the `out/` and `out/figures/` directories. These include tables and plots summarizing the analysis.

### Cleanup
Temporary files such as `Rplots.pdf` are automatically removed after each pipeline run.
