# RNA Pol II Length and Disorder Enable Cooperative Scaling of Transcriptional Bursting

[![DOI](https://data.caltech.edu/badge/215094635.svg)](https://data.caltech.edu/badge/latestdoi/215094635)

This repository contains all the code used for data analysis in [this paper](https://www.biorxiv.org/content/10.1101/825299v1) by Porfirio Quintero-Cadena, Tineke L. Lenstra and Paul W. Sternberg.

Requires `python 3.6`

## analysis
Generate data that can be visualized: extract features from imaging, sequencing and simulation data.
## figures
Generate all main and supplementary figures. Almost every figure\* can be generated and saved in `figures/output` by running `python figures/figureX.py` from this directory, where X is the figure script suffix.

\*Except for figures that require a file larger than github's 100MB size limit (Figures 6F, S2 and S8). Those figures will be skipped automatically if the file is not found.
## utils
Supporting functions for data analysis.
## data
Output from `analysis` functions used to generate figures. Mostly `csv` files
