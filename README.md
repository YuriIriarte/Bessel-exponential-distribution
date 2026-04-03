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

### Requirements

The package requires:

- R (>= 4.0.0)
- Recommended: the `remotes` package (for GitHub installation)

---

```markdown
### Install from source file (recommended for reproducibility)

This option ensures full reproducibility of the results reported in the associated manuscript.

```r
install.packages("besselexp_0.1.0.tar.gz", repos = NULL, type = "source")


## 📖 Citation

If you use this repository or the associated R package in your research, please cite:

### 📄 Associated article

```bibtex
@article{Iriarte2026BE,
  author  = {Yuri A. Iriarte},
  title   = {Bessel-Exponential Distribution: Theory and Applications},
  year    = {2026},
  note    = {Under review}
}
