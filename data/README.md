# Data

This directory contains the datasets used by the analysis notebook.

## Files

### `Bus_Binzel_original.csv`

Visible asteroid spectra associated with the Bus--Binzel taxonomy.

Source:
- Small Main-Belt Asteroid Spectroscopic Survey, Phase II (SMASSII)
- NASA Planetary Data System (PDS)

The original SMASSII observations and taxonomy are described by Bus and Binzel (2002).

### `03_asteroids.csv`

Imputed VIS--NIR asteroid spectral dataset used in the Bus--DeMeo-labeled experiment.

The database originates from the asteroid spectral compilation of Mahlke et al. (2022):

https://github.com/maxmahlke/classy

The imputed version was developed by Ojeda et al. (2025) and is publicly available at:

https://github.com/AnaOjedaVera/ImputedDatabase

## Notes

The notebook expects the datasets to be located at:

```text
data/Bus_Binzel_original.csv
data/03_asteroids.csv
