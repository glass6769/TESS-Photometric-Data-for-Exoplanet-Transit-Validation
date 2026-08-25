# TESS-Photometric-Data-for-Exoplanet-Transit-Validation
# TESS-Photometric-Data-for-Exoplanet-Transit-Validation

## About the Project

This project presents a Python-based analysis of TESS photometric data for detecting and evaluating exoplanet transit signals.

The analysis uses real light curve data from NASA's **Transiting Exoplanet Survey Satellite (TESS)** and applies several methods for transit detection, modeling, and validation.

## Project Goal

The main goal of the project is to process TESS photometric observations, identify periodic transit signals, and estimate the properties of a potential exoplanet candidate.

The analysis includes:

- TESS light curve processing and normalization
- Data cleaning and detrending
- Box Least Squares (BLS) period search
- Transit signal identification
- Candidate validation
- Orbital period refinement
- Transit modeling with BATMAN
- Monte Carlo simulations
- Estimation of planetary and orbital parameters

## Methodology

The TESS light curve data are first cleaned, normalized, and detrended.

The **Box Least Squares (BLS)** algorithm is then used to search for periodic decreases in stellar brightness that may indicate an exoplanet passing in front of its host star.

Potential transit signals are further analyzed and the orbital period is refined.

A physical transit model is fitted using **BATMAN**, and Monte Carlo simulations are used to estimate uncertainties and evaluate the stability of the obtained parameters.

## Tools and Libraries

The project was developed in **Python** using **Jupyter Notebook**.

Main libraries used in the analysis include:

- NumPy
- Pandas
- Matplotlib
- SciPy
- Astropy
- Astroquery
- Lightkurve
- BATMAN

## Analysis Workflow

**TESS Data → Data Cleaning → Detrending → BLS Period Search → Candidate Validation → Period Refinement → Transit Modeling → Monte Carlo Analysis → Parameter Estimation**

## Project Status

This project is an educational and scientific analysis of real TESS photometric observations.

The results represent an independent analysis of the available photometric data and should not be interpreted as an official discovery or confirmation of an exoplanet.
