# PMF_toolkits Documentation

## Overview

PMF_toolkits is a Python package designed for working with Positive Matrix Factorization (PMF) analysis results from the EPA PMF 5.0 software. It provides tools for loading, analyzing, and visualizing PMF outputs, enabling researchers to effectively interpret source apportionment results in environmental studies.

Positive Matrix Factorization (PMF) is a multivariate factor analysis technique that decomposes a matrix of environmental sample data into two matrices: factor contributions and factor profiles. It is widely used for source apportionment studies in air quality research to identify and quantify the sources of atmospheric pollutants.

## Package Features

PMF_toolkits offers a comprehensive suite of tools for working with PMF results:

### Data Loading and Preprocessing

- Read EPA PMF 5.0 output files (Base, Constrained, Bootstrap, DISP, BS-DISP)
- Support for both single-site and multi-site data
- Handle below-detection-limit values and missing data
- Calculate uncertainties using various methods (percentage, detection limit-based, Polissar)

### Analysis

- Calculate explained variation by each factor
- Compute similarity metrics between profiles (SID, PD, COD)
- Analyze temporal patterns and seasonal contributions
- Detect potentially mixed factors
- Compare results from different runs

### Visualization

- Factor profile plots with uncertainties
- Time series plots of source contributions
- Seasonal contribution patterns
- Stacked profiles and contributions
- Comprehensive diagnostic plots

### Uncertainty Analysis

- Bootstrap analysis
- Displacement (DISP) analysis
- BS-DISP combined analysis
- Visualization of uncertainties

## Getting Started

To begin using PMF_toolkits, see the [Quickstart Guide](quickstart.md) for installation instructions and basic usage examples.

## Citation

If you use PMF_toolkits in your research, please cite:

```
Dinh, N.T.V. (2025). PMF_toolkits: Python tools for analysis of Positive Matrix Factorization results.
GitHub repository: https://github.com/DinhNgocThuyVy/PMF_toolkits
```