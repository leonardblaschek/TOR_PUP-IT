# TOR_PUP-IT

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14960064.svg)](https://doi.org/10.5281/zenodo.14960064)

Code and source data to recreate analyses performed in Zheng, Blaschek & Pottier et al. (2025). *Advanced Science.* DOI: [10.1002/advs.202414496](https://doi.org/10.1002/advs.202414496).

Note that `2023-11_TOR_PPIN_vis.rmd` depends on the output of `2023-11_TOR_PPIN_vis.rmd` and `2023-11_TOR_phospho.rmd`.
`2024-01_manuscript_figures.rmd` depends on the output of all other scripts. However, intermediate output files are included in the repository, so each script should execute by itself. `/data/output/FP_maxLFQ-TRUE_hurdle-FALSE_glMinProb-TRUE_PPI_FC_annotated.tar.gz` (compressed to abide by Github's size limits) needs to be extracted before running any scripts depending on it.

Raw proteomics data is deposited in MassIVE:

* [MSV000096513](https://doi.org/doi:10.25345/C59P2WJ4T)
* [MSV000096657](https://doi.org/doi:10.25345/C5Q52FR36)
* [MSV000096862](https://doi.org/doi:10.25345/C5M902F77)
* [MSV000096864](https://doi.org/doi:10.25345/C5BR8MT89)
* [MSV000096866](https://doi.org/doi:10.25345/C53B5WM32)
