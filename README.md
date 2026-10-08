# PCA-Asteroid-Taxonomy

This repository contains the code, data organization, processed outputs, and figures associated with the study:

**Assessing PCA as a Baseline for Asteroid Spectral Classification: Robustness, Unsupervised Comparisons, and Quantum-Inspired Perspectives**

## Abstract

Principal Component Analysis (PCA) has played a central role in several asteroid taxonomic systems, including the Tholen, Bus--Binzel, and Bus--DeMeo classifications. In these systems, PCA provides a lower-dimensional representation of correlated spectral measurements, but final class assignments also rely on spectral criteria, boundaries, and sequential decision rules. This chapter evaluates PCA as a baseline representation for asteroid spectral classification using Bus--Binzel visible spectra and Bus--DeMeo-labeled visible--near-infrared spectra. PCA is fitted independently to both datasets, and KMeans is used as a fixed unsupervised probe over representations containing 2--50 principal components. Global agreement is quantified using the Adjusted Rand Index (ARI), while class-level recoverability is assessed using the F1-score. More than 90\% of the spectral variance is retained by only two components in both datasets, and four components retain more than 99\% in the VIS--NIR dataset. Nevertheless, maximum ARI reaches only 0.280 for Bus--Binzel and 0.264 for the Bus--DeMeo-labeled dataset. Only 9 of 25 and 6 of 21 classes, respectively, achieve F1 $\geq 0.60$, and no class reaches F1 $\geq 0.90$. Several classes attain their highest recovery only after higher-order components are included. These results show that explained variance and taxonomic discriminability are distinct properties and that low-dimensional PCA representations do not fully recover established asteroid taxonomies.

## Repository structure

```text
PCA-Asteroid-Taxonomy/
├── README.md
├── PCA_Asteroid_Taxonomy_Chapter.ipynb
├── requirements.txt
├── data/
│   ├── Bus_Binzel_original.csv
│   ├── 03_asteroids.csv
│   └── README.md
├── results/
│   └── figures/
└── LICENSE
