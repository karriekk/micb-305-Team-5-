## Future Steps for Project Proposal
- Need to split the work (divide the job up by aim instead of by dietary antioxidant)
- Some tips for writing the project proposal
  - Connect all the dots and write it in a way that is clear (pretend that the audience has never heard of the project before)
  - Is the hypothesis worded as a question, are the aims describing what we are doing, know which aim is doing what and the biological relevance behind each analysis
  - Avoid vague parts (ensure that everything is super clear so that people do not have to make assumptions about our content) - add more explanations and content to parts that we think are vague
  - Note: feel free to email for feedback

* Some notes about finding no significant results: it's okay if the results are not significant, just tell the reader what do they mean biologically (e.g., PD patients can eat their favorite food without worrying about further altering their gut microbiome composition)

## Current Step Clarification and Feedback
- RDA value: sort the cohort based on recommended daily intake (but this categorization method would result in uneven grouping and for alpha and beta carotene, technically there is no RDA)
  - Reanalyze using DAI now because it gives even split of the PD cohort and neglects the need to reference RDA (can mention it in the proposal)
 
- Alpha diversity analysis (also applies to beta diversity analysis)
  - Shannon diversity only covers one part, so need to do more analyses that cover different parts of the alpha diversity analysis to get a more comprehensive analysis

- Instead of categorizing PD cohort based on DAI, we could also normalize the data and make it a continuous variable for analysis
  - Use hist() function to create a histogram for each antioxidant to see its distribution and normalize it using the his(df$antiox) command
  - If the distribution is skewed, then we could do a log transformation to transform it to a normal distribution using the function df$log_anti = log10(df$antiox), which can then be fed into ancombc/ggpicrust2 and be ran as a continuous variable
 
- We need to figure out the antioxidant and bacterial pathways that we want to look at
- Leave out random forest analysis for now
