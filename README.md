# PerformanceSpecs
A project to investigate the effects of analytical bias and variability in lipid panel assays on clinical results and interpretation.

Data was freely downloaded from the NHANES database (https://wwwn.cdc.gov/nchs/nhanes/Default.aspx)
Notebooks are numbered for ease of reference:

0 - Directories created in the parent folder for outputs of analysis
1 - Dictionaries for coded dataframes, and tables of error values used
2 - Data exploration and cleaning
3 - Data wrangling for analysis using the current analytical performance specifications
4 - Data wrangling for analysis using the newly proposed analytical performance specifications
5 - Bar chart showing the original risk classification distribution in the cohort
6 - Functions to apply error, calculate dependent parameters, determine risk group and cross-tabulate with the original risk group determined_Current performance specs
7 - Iterations through bias and imprecision in each lipid panel assay to determine individual effects of risk group determination
8 - Functions to apply error, calculate dependent parameters, determine risk group and cross-tabulate with the original risk group determined_New performance specs
9- Box and whisker charts showing distribution of results over 50 replicate analyses
10 - Bar charts showing misclassifications based on LDL-C, using current and new performance specs
11 - Bar charts showing misclassifications based on non-HDL-C, using current and new performance specs
12 - Summary of misclassification rates based on calculated LDL-C, direct LDL-C and non-HDL-C, using current and new performance specs
13 - Analytical and sample replicates to address analytical and biological variability, respectively
