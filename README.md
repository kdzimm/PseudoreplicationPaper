# PseudoreplicationPaper
This repository contains the R code used to carry out parameter estimation, correlation estimation, type 1 error analysis, and power analysis for our "Pseudoreplication in Single-Cell RNA-Seq Data" study.

There are four folders: Parameter_Estimation, Correlation, Type_1_Error, and Power. Each folder contains R code and descriptor file. 

### It is highly recommended you download and walk through the "Simulation Example" html in the parameter estimation folder to get an understanding of how the simulation steps work prior to attempting to implement any of the power or type 1 error scripts. 

There is no package to install for these particular functions, but a number of dependencies are required. They are listed below. All code here was executed in R versions 3.5.1 or later. 

R packages and dependencies for the example demo scripts provided are: ggplot2, fitdistrplus, MASS, tidyr, gdata, Seurat, data.table, EnvStats, purrr, dplyr, sn, matrixStats, and fmsb. Other pacakges or libraries that are specific only to the tool being assessed in one of the scripts are listed in the code. 

With additional refinement, these scripts and tidbits of code will soon be coalesced into an R-package for others to easily access and use. Until then, we hope this code is helpful to other researchers. Any questions about our code can be sent to kdzimmer@wakehealth.edu. 
