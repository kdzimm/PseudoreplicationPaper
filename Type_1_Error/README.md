This is the R code used to estimate the type 1 error rates for a variety of different methods or analysis methods when being applied to hierarchical single-cell RNA-seq data. We carried out the following steps for each of the different methods:

  1) Simulate a new dataset with the desired structure (number of genes, number of cells per individual, number of individuals, etc.)(See "Simulate-Example" script prior to using these scripts)
  2) Filter and normalize the data according to each method's recommended settings.
  2) Compute the statistical tests using each method's recommended settings.
  3) Store the pvalues and compute the type 1 error rate(s) at the desired alpha(s).
