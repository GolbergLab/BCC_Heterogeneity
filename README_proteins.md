Here the proteins heatmap and histograms generated for the paper.
Inputs: The xlsx file in this directory.
Output: The visualziation of the pearson and spearman proteins heatmap and histograms.(in the Jupyter notebook)

NOTES:
1. There are old and new datasets, the outer join of them is genetated and will serve us as the final data.
2. There is a dataset for control group (same sample, 5 different LCMS outputs).
3. Wilcoxon test is done between each two groups (inter patients vs intra patients, inter patients vs control, intra patients vs control).
4. the error of a baysian model on the inter patients and intra patients histograms is calculated.
5. Analysis is done on Lysis
