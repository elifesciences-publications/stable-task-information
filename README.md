This code is associated with the paper from Rule et al., "Stable task information from an unstable
neural population". eLife, 2020. http://doi.org/10.7554/eLife.51121

# Stable Task Information from an Unstable Neural Population

Source code files for the paper ["Stable Task Information from an Unstable Neural Population". ](https://www.biorxiv.org/content/10.1101/796334v2)

Datasets from [Driscoll et al. 2017](https://www.sciencedirect.com/science/article/pii/S0092867417308280) are needed to run these analyses. Contact LND or CDH to obtain the datasets necessary to reproduce these analyses. These datasets are also available from the [Dryad repository](https://doi.org/10.5061/dryad.gqnk98sjq).

`Version 1/Loback` contains ARL's Matlab source code. This was used to render Figure 2, as well as in prelimenary analyses for Figures 3 and 4. There are also some plotting scipts in Python. 

`Version 2/Rule/` contains MER's analysis code used to prepare figures 3, 4, 5, and the supplemental figures, in the form of iPython notebooks and Python source files. A copy of the [neurotools](https://github.com/michaelerule/neurotools) Python library is included. This has a lot of dependencies, but only a limited subset of the library is needed for these analyses. Regenerating all figures from scratch should take about a week on a high-performance laptop. To avoid recomputation, intermediate results are cached in `PPC_cache`.

`Version 2/Raman/` contains DVR's simulation code in Julia for sampling from the null model. 
