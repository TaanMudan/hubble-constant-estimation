# hubble-constant-estimation
Estimating the Hubble constant from observational data using statistical modelling and uncertainty analysis.


## Overview

This project estimates the Hubble constant using observational astronomical data and statistical modelling techniques. The analysis combines measurements of Cepheid variable stars and galaxy recession velocities to estimate the expansion rate of the Universe while quantifying the uncertainty associated with the final result.

Developed as part of a Computational Physics module at the University of Southampton, the project demonstrates a complete quantitative analysis workflow, from processing observational data and fitting statistical models to validating results using multiple independent methods.


## Methodology

The project first estimates distances to nearby galaxies by calibrating the relationship between the period and absolute magnitude of Cepheid variable stars using observational data from the Milky Way. These calibrated parameters are then used to estimate distances to Cepheids in the galaxy NGC4527 before combining these results with galaxy recession velocities to estimate the Hubble constant.

To assess the reliability of the analysis, both analytical uncertainty propagation and Monte Carlo uncertainty estimation were implemented and compared. Linear regression, chi-squared goodness-of-fit testing and residual analysis were then used to evaluate the quality of the fitted models and identify potential issues within the observational data.

Key techniques used include:

- Statistical model fitting
- Linear regression
- Error propagation
- Monte Carlo uncertainty estimation
- Chi-squared goodness-of-fit testing
- Residual analysis


## Results

The project successfully estimated the Hubble constant using real observational data while comparing multiple approaches for uncertainty estimation and model validation. Independent validation techniques highlighted the importance of data quality and uncertainty estimation when interpreting experimental observations.

The project demonstrates how statistical modelling and scientific computing can be combined to extract physical parameters from noisy real-world datasets.


## Repository Contents

- `hubble_constant_estimation.ipynb` – Complete analysis
- `report.pdf` – Project report
- `data/` – Observational datasets
- `requirements.txt` – Python dependencies


## Technologies

- Python
- NumPy
- SciPy
- Matplotlib


## Future Improvements

Possible extensions include analysing larger observational datasets, applying weighted regression techniques and comparing alternative cosmological models to investigate their impact on the estimated value of the Hubble constant.
