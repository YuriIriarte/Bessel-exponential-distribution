[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19402357.svg)](https://doi.org/10.5281/zenodo.19402357)
# Bessel-exponential-distribution

This repository provides an implementation of the Bessel-Exponential (BE) distribution, including tools for density evaluation, distributional properties, random generation, and maximum likelihood estimation, both with and without covariates.

The repository also contains the scripts used in the simulation studies and real data applications presented in the associated research work.

---

## 📦 Contents

- `besselexp_0.1.0.tar.gz`  
  Installable R package containing all core functions.

- `01 Figures`  
  Scripts used to generate the figures in the manuscript.

- `02–05 Applications`  
  Scripts corresponding to real data applications (with and without covariates).

- `06 bcarotene.R`  
  Script for loading and preparing the plasma beta-carotene dataset.

- `README.md`  
  Project description and usage instructions.

---

## ⚙️ Installation

# Install from source file
install.packages("besselexp_0.1.0.tar.gz", repos = NULL, type = "source")

# Or install directly from GitHub
# install.packages("remotes")
remotes::install_github("YuriIriarte/Bessel-exponential-distribution")

## Citation

If you use this repository in your research, please cite:

Iriarte, Y. A. (2026). *Bessel-Exponential distribution R package*.  
Zenodo. https://doi.org/10.5281/zenodo.19402357
