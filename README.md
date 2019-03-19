# HWE_LD_Jack_tests
Multi-test corrected tests for LD and HWE, with jackknife analysis to ID genotypes affecting HWE. 

This R-markdown document contains R-scripts to select genotypes based on a stratification scheme, then test the genotypes within the stratum for linkage disequilibrium (LD) and deviations from the expectations of Hardy-Weinberg Equilibrium (HWE). For each test, a p-value sequential correction for multiple tests (Holm, 1979) is applied, and the resulting adjusted p-values are output in .csv files. Other multiple-correction tests can be implemented instead of the Holm (1979) version.

A Jacknife analysis to identify genotypes responsible for deviations from HWE is added as a way to detect samples or loci that have unlikely genotypes (given HWE expectations) and may be errors. 

Example data and stratification files are included.

References:
Holm, S. (1979), A simple sequentially rejective multiple test proceedure. Scand. J. Statist. 6:65-70. 

Morin, P.A., R.G. LeDuc, F.I. Archer, K.K. Martien, R. Huebinger, J.W. Bickham, and B.L. Taylor. 2009. Significant deviations from Hardy-Weinberg equilibirum caused by low levels of microsatellite genotyping errors. Molecular Ecology Resources 9:498-504.
