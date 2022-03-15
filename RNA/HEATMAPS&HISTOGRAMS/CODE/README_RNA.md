Here the RNA heatmap and histograms generated for the paper.
Inputs: The xlsx file in this directory.
Output: The visualziation of the pearson and spearman RNA heatmap and histograms.(in the Jupyter notebook)

NOTES:
1. There is a Jupyter notebook that changes the RNA patients names to match the proteins format (FIX_PATIENTS_NAMES.ipynb  generates RNA-HADAS-FIXED-NAMES.xlsx)
3. Wilcoxon test is done between each two groups (inter patients vs intra patients, inter patients vs control, intra patients vs control).
4. the error of a baysian model on the inter patients and intra patients histograms is calculated.
5. Analysis is done on Lysis
