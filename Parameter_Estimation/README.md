This is the R code used to estimate the parameters we used to simulate hierarchical single-cell RNA-seq data. First we removed cells or genes that were all zeros and provided no valuable information and, if the data was raw, we converted it to RPM to standardize the expression counts across cells. Then we carried out the following steps:

  1) Compute grand mean, dropout, intra-individual means, intra-individual variances, intra-individual dispersions, and inter-individual standard deviation for each gene.
  2) Estimate the parameters of a gamma distribution for the grand mean using maximum likelihood estimation.
  3) Estimate the sigmoidal curve that best fits the relationship between dropout and the grand mean.
  4) Estimate the quadratic function that best fits the relationship between global dropout and the standard deviation in intra-individual dropout values.
  5) Estimate the linear relationship between inter-individual standard deviation and the grand mean .
  6) Estimate the logarithmic relationship between intra-indvidual means and intra-indivdiual dispersion parameters. 