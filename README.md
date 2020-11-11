# Tutorial_GEM_and_FBA

## Introductory course "Working with GEMs and FBA in a Jupyter Notebook"
A four-part introductory course is offered here to facilitate the introduction to the topic and the work with GEMs and flow balance analysis. This course is available in form of jupyter notebooks. Jupyter notebooks can be opened and edited using binder or colab at git hub. However, for the second course “Metabolic pathway visualizations with Escher.ipynb” it is necessary to open the jupyter notebook with Anaconda because the visualization of the maps with binder and colab does not work. For a frequent use of flow balance analyses it is recommended to install Anaconda. Anaconda is an open source distribution for the programming languages Python and R, which contains among others the development environment Spyder, the command line interpreter IPython, and a web-based frontend for Jupyter. The main focus is on processing large amounts of data, predictive analysis and scientific computing. Instructions for installation can be found via the following link:

https://docs.anaconda.com/anaconda/install/

## Genome scale metabolic modeling and Flux balance analysis
Genome-level metabolic models (GEMs) computationally describe gene-protein reaction associations for entire metabolic pathways in an organism and can be simulated to predict metabolic fluxes for various system-level metabolic studies.Thus a GEM represents a compilation of transcriptomic, proteomic and metabolomic omics data sets. A metabolic network consists of two main components: the stoichiometric matrix (S-matrix) and a set of rules for gene-protein reaction relationships (GPR). The S-matrix consists of biochemical reactions that take place in an organism, while GPR relationships represent conditional statements in Boolean logic between open reading frames (ORFs) and their enzymatic functions in the S-matrix.

Flux balance analysis (FBA) is a mathematical procedure for simulating metabolism in genome-wide reconstructions of metabolic networks. This method uses linear programming to obtain the maximum potential of the target function under consideration, and therefore FBA is used to find a single solution to the optimisation problem. This is done by constraining the S-matrix of a genome-scale model by defining recording limits and setting lower and upper limits for reactions.


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/BrigidaF/Course-RWTH_GEM_and_FBA/main)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb)
