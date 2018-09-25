---
layout: publication
title: pyTFA and matTFA - A Python package and a Matlab toolbox for Thermodynamics-based Flux Analysis
authors: Salvy, P. and Fengos, G. and Ataman, M. and Pathier, T. and Soh, K. C. and Hatzimanikatis, V.
journal: Bioinformatics
volume: 1
number: 3
pages: 
year: 2018
doi: 10.1093/bioinformatics/bty499
icon: mdi-file-document
---
Summary: pyTFA and matTFA are the first published implementations of the original TFA paper.
Specifically, they include explicit formulation of Gibbs energies and metabolite concentrations,
which enables straightforward integration of metabolite concentration measurements.

Motivation: High-throughput analytic technologies provide a wealth of omics data that can be used
to perform thorough analyses for a multitude of studies in the areas of Systems Biology and
Biotechnology. Nevertheless, most studies are still limited to constraint-based Flux Balance Analyses
(FBA), neglecting an important physicochemical constraint: thermodynamics. Thermodynamicsbased
Flux Analysis (TFA) in metabolic models enables the integration of quantitative metabolomics
data to study their effects on the net-flux directionality of reactions in the network. In addition, it
allows us to estimate how far each reaction operates from thermodynamic equilibrium, which
provides critical information for guiding metabolic engineering decisions.

Results: We present a Python package (pyTFA) and a Matlab toolbox (matTFA) that implement
TFA. We show an example of application on both a reduced and a genome-scale model of E. coli.,
and demonstrate TFA and data integration through TFA reduce the feasible flux space with respect
to FBA.

Availability and implementation: Documented implementation of TFA framework both in Python
(pyTFA) and Matlab (matTFA) are available on www.github.com/EPFL-LCSB/.
