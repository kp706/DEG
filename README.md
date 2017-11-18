# DEG
Identification of differentially expressed genes
Consists of 1) generation of empirical null distribution; 2) integrative statistical tests based on the generated empirical distribution; and 3) identification of up- (labeled as 1) and down-regulated (labeled as 3) DEGs.


# function lists
1) emp_dist : generation of empirical null distribution composed of T-values and log2-fold-changes
2) DEGstat : integrative statistical tests. After applying Student's t-test and log2-median-ratio test for the individual genes, we obtained T-values and log2-fold-changes. Then, we compared T-values and log2-fold-changes with those of the null distributions, and obtained adjusted P-values for each test (Pt for t-test and Pf for log2-median-ratio test, respectively). Finally, we combined the two types of adjusted P-values into the combined P-value (Pcom).
3) identifyDEG : For each gene, we identified DEGs as up- (1), down-regulated genes (3), or genes with no significant change in their expression (2).

# The reference for the integrative statistical test
Hwang et al. PNAS (2005) A data integration methodology for systems biology.
