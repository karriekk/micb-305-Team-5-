### Alpha Diversity Analysis (Aim 1)
1. The plots can go into supplementary materials as no significant difference was found.

### Beta Diversity Analysis (Aim 1)
1. Run the beta-diversity analyses again using weighted and unweighted UniFrac, as well as Jaccard to see if we get the same significant results. Email Imogen and Avril if there are discrepancies in the results obtained using different beta diversity metrics.
2. When making publication-ready plots, it is ideal that the p-values are labelled on the plots themselves instead of stated in the figure legend. However, it is important to state the confounding variables that are accounted for in the figure legend.

### Taxonomy Differential Abundance Analysis (Aim 2)
1. Use an alternative method, such as MaAsLin2, to re-run the differential abundance analysis. Alternatively, the q-value column from the ANCOM-BC results table could be used instead of the diff_robust column; however, this choice would need to be clearly justified in the manuscript, including an explanation of why diff_robust is not used and what information may be lost as a result.

### Indicator Species Analysis (Aim 2)
1. Increase the stat threshold to 0.7 (because if the stat cutoff is too low, it will be more like differential abundance analysis but less accurate than that) --> so only the indicator taxa associated with the low intake groups will be kept.

### Pathway Differential Abundance Analysis (Aim 3)
1. Do a volcano plot to show all the results and to show the overall trend as well as the fraction of pathways that are significant; can also do a PCA plot.
2. Alternatively, in the presentation or manuscript, we could perform a targeted literature search to identify pathways of particular interest, and then highlight these pathways while placing them in proper biological or conceptual context.

### Linear Regression Model (Aim 4)
1. Could use sub[1:10] to iterate through the list if there are a lot of repetitions in the code.
2. The * means that the variable of interest is significant while taking other things into account.
3. When making the linear regression plots, the x-axis would be the indicator taxa/significant metabolic pathway, the y-axis is the MoCA score.
4. Only add multiple variables if they are helpful (e.g., multiple indicator taxa) at the same times. If we do not care about the combined effect, then doing the analysis one indicator taxa by one indicator taxa is fine.

### Some Notes about Making Publication-ready Plots
1. Could use string_wrap() to set the maximum number of characters that are allowed to be in one line.

### Some Notes about Adding P-values onto the Plot
1. Can use Affinity to manually add p-values onto the plots instead of coding them in R.

### Some Notes about the Presentation
1. For the presentation, include only information that is relevant, important, and directly aligned with the overall goal of the project; and ensure that each element contributes to a clear aspect of the narrative and can be understood within a 10-minute timeframe.

### Some Notes about the Manuscript Figures
- Figure 1: Beta diversity (Bray) with p-values on the plot
- Table S1: Alpha diversity and other beta diversity (weighted UniFrac, unweighted, Jaccard)

- Figure 2: Indicator taxa boxplots with higher stat value (0.7). If differential abundance analysis works, barplots or table

- Figure 3: PICRUSt volcano, ggpicruts2 bar plots, PCoA plots

- Figure 4: Linear regression for MoCA vs. abundance of taxa and metabolic pathways (plan for table with stats for each strain checked individually, and then for the "significant" ones plot lm(strain ~ MoCA + confounders))
