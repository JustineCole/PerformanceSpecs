# PerformanceSpecs
A project to investigate the effects of analytical bias and variability in lipid panel assays on clinical results and interpretation.

Data was freely downloaded from the NHANES database (https://wwwn.cdc.gov/nchs/nhanes/Default.aspx)
Notebooks are numbered for ease of reference:

A - Directories created in the parent folder for outputs of analysis

B - Dictionaries for coded dataframes, and tables of error values used

C - Data exploration and cleaning

D - Data wrangling for analysis using the current analytical performance specifications

E - Data wrangling for analysis using the newly proposed analytical performance specifications

F - Bar chart showing the original risk classification distribution in the cohort

G - Functions to apply error, calculate dependent parameters, determine risk group and cross-tabulate with the original risk group determined_Current performance specs

H - Iterations through bias and imprecision in each lipid panel assay to determine individual effects of risk group determination

I - Functions to apply error, calculate dependent parameters, determine risk group and cross-tabulate with the original risk group determined_New performance specs

J - Box and whisker charts showing distribution of results over 50 replicate analyses

K - Bar charts showing misclassifications based on LDL-C, using current and new performance specs

L - Bar charts showing misclassifications based on non-HDL-C, using current and new performance specs

M - Summary of misclassification rates based on calculated LDL-C, direct LDL-C and non-HDL-C, using current and new performance specs

N - Analytical and sample replicates to address analytical and biological variability, respectively
