# PCA-Asteroid-Taxonomy

[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![PCA + KMeans](https://img.shields.io/badge/PCA-KMeans-8A2BE2)
![Springer](https://img.shields.io/badge/Springer-Book_Chapter-0077B5)
![Publication Status](https://img.shields.io/badge/Publication-In_Preparation-orange)

This repository contains the code, data organization, processed outputs, and figures associated with the study:

**Assessing PCA as a Baseline for Asteroid Spectral Classification: Robustness, Unsupervised Comparisons, and Quantum-Inspired Perspectives**

Book chapter prepared for publication with Springer.

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
```

---

## Contact

**Ana V. Ojeda Vera**  
Doctoral Student in Data Science  
CITEDI – Instituto Politécnico Nacional (IPN), Mexico. 
Email: **anaojedavera@gmail.com**

[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:anaojedavera@gmail.com)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0009-0002-0748-9630)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=flat&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=HO17QvAAAAAJ&hl=es)
[![ResearchGate](https://img.shields.io/badge/ResearchGate-00CCBB?style=flat&logo=researchgate&logoColor=white)](https://www.researchgate.net/profile/Ana-V-Ojeda)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anaojedavera/)

