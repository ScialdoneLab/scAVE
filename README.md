# scAVE

This repository includes data and codes associated with the pre-print **TITLE** LINK. We provide three Jupyter notebooks for the analysis of a Visceral Endoderm enriched single-cell RNA-sequencing dataset of mouse embryos at the stages E5.5 and E6.25, obtained through the Smart-seq2 protocol.

The [SoS Polyglot notebooks](https://vatlab.github.io/sos-docs/) "E55_Analysis.ipynb" and "E625_Analysis.ipynb" include the following analyses at the stages E5.5 and E6.25, respectively:
* Highly Variable Genes identification
* Iterative cell clustering
* Computation of marker genes for each cluster
* Diffusion pseudotime analysis for Anterior Visceral Endoderm (AVE) and EmVE cells

The python3 Jupyter notebook "RNA_velo_Analysis.ipynb" includes the RNA velocity analysis on AVE and Epi-VE cells, performed with the [scvelo](https://scvelo.readthedocs.io) implementation, at the stages E5.5 and E6.25, both separated and integrated.
