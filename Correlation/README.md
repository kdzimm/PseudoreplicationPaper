This is the R code used to estimate the intra-individual and inter-individual correlation for each cell type. Data were filtered to remove noisy, correlated, and lowly expressed genes prior to carrying out the following steps:

  1) For intra-individual correlation, compute the spearman correlation between each pair of cells within an individual
  2) For inter-individual correlation, draw one cell from each individual, compute the pairwise correlations for that draw, and then repeat.
  3) Store the results, and visualize by building box plots
