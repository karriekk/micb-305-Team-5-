#### Aim 1: How dietary antioxidant intake impacts gut microbiome composition and diversity.
- Taxa: differential abundance analysis (module 14)
  - Filter for a specific threshold, which is usually a level of how different they are and filter by significance (things that have significantly changed) to get different taxa that are significantly different between different antioxidant intake
- Alpha and beta diversity: module 13 (more qualitative instead of statistical analysis)

#### Aim 3: Metabolism analysis
1. PICRUSt
   - PCA plots (every sample/person will be a dot, the further apart things are, the more different they are in terms of microbiome taxa and functions)
   - Have 2 people working on PICRUSt because it is the most dense part
2. Functional analysis
3. Heat map to see which pathways are up and down-regulated (module 15)
   - For taxa and PICRUSt
  
#### Aim 4: Gene analysis
- Make a profile of people who have the genes and people who do not have the genes and look at cognitive score
- Make a linear correlation graph
- Depend on what we see from the results from other aims (later work)

Look at the Canadian dietary intake guide or literature to see what the recommended dose is for each antioxidant - use this to rank the patients in terms  of dosage intake (consider it as aim 1 or aim 0)
- Categorize intake for aim 1
- Maybe don't need to consider about individual's weight (but it depends)

Aim 1 for each antioxidant to see which ones stand out to have an impact
- Pick the ones that potentially have an impact and do analysis based on these
- Get everything exported to R and prioritize figuring out in the literature, how patients could be categorized based on antioxidant intake
- Do aim 1 first to select antioxidants of interest to see if we want to work on one or combine them, work on aim 2 and 3 cocurrently
- Aim 4 last because we will be looking at all the genes in the microbiome
  - Break patients into subgroups (break down patients based on if they have the gene and also the level of antioxidant intake)
    - End up with a 4 group split
   
#### For Group Assignment 1
- Don't use language such as correlation or causation because there are a lot of confounding variables in gut microbiome analysis
- Rarefaction depth is a bit low because even though we want to keep all the samples, only 27% of the reads is kept, so it is okay to lose a few samples to get a higher percentage of reads included for the analysis
  - Higher percentage of features retained and lose a few samples is fine (balance between features retained and sample size)
    - Keep ~180 patients
    - Somewhere around the 6000 mark is good
