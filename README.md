# PCA-Asteroid-Taxonomy

This repository contains the code, data organization, processed outputs, and figures associated with the study:

**Assessing PCA as a Baseline for Asteroid Spectral Classification: Robustness, Unsupervised Comparisons, and Quantum-Inspired Perspectives**

## Abstract

Principal Component Analysis (PCA) has played a central role in several asteroid taxonomic systems, including the Tholen, Bus--Binzel, and Bus--DeMeo classifications. In these systems, PCA provides a reduced representation of correlated spectral measurements, but final class assignments also rely on spectral criteria, boundaries, and sequential decision rules. This study evaluates PCA as a baseline representation for asteroid spectral classification using visible spectra labeled according to Bus--Binzel and VIS--NIR spectra labeled according to the Bus--DeMeo system. PCA is fitted independently to both datasets, and KMeans clustering is used as a fixed unsupervised probe over representations containing 2--50 principal components. Global agreement is quantified through the Adjusted Rand Index, while class-level recoverability is assessed using the F1-score. Although more than 90% of the spectral variance is retained by only two components in both datasets, maximum global agreement remains below 0.30. Several classes attain their highest recovery only after higher-order components are included. These results show that explained variance and taxonomic discriminability are distinct properties and that low-dimensional PCA projections do not fully reproduce established asteroid taxonomies.

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
