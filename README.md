# Across the Atlantic: AI Exposure and Labor Market Dynamics

This project analyzes employment trends across Dow Jones companies from 2021-2025, examining how occupations with different levels of AI exposure evolved around the November 2022 ChatGPT release.

## Overview

The analysis implements the Brynjolfsson et al. (2024) methodology to control for firm-level shocks using high-dimensional fixed effects, studying the relationship between AI exposure and employment dynamics across different career stages.

## Data Sources

- **Exposure Scores**: 
  - `occ_level.csv`: Eloundou et al. (2023) occupation-level AI exposure scores
  - `pi_occ_level.csv`: π-weighted exposure ratings
  - `pierre_occ_level.csv`: Consolidated sentiment ratings

- **Employment Data**: 
  - Company employment data from Revelio Labs (position-level records with start/end dates and O*NET occupation codes)
  - **Note**: Company data is not included in this repository. Access can be requested from the author.

## Notebooks

### Analysis Files

- `Score_Comparison.ipynb`: Multi-exposure score comparison and visualization
- `EU_analysis.ipynb`: European market analysis
- `USA_analysis.ipynb`: US market analysis
- `R_800_Correlation_checker.ipynb`: Exposure score correlation analysis
- `R_800_EU_occupation.ipynb`: EU occupation-level analysis
- `R_800_USA_occupation.ipynb`: USA occupation-level analysis

## Results

Generated plots and analysis outputs are saved in the `Results/` directory.

## Data Access

Company employment data can be requested from the author. All other data files are included in the `Data/` directory.

## Requirements

- Python 3.8+
- pandas
- numpy
- matplotlib
- pyfixest

## Contact

For data access requests or questions about the analysis, please contact the author.
