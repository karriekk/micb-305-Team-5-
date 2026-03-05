## Proposal Plan
### Current Progress
-  Everyone gets a specific part of the proposal to work on during our own time.
-  Try to finish everything and have a complete proposal draft by the end of this week. 
-  Compile everything together; improve and optimize if needed.
-  Git hub has been updated with some work in the R scripts folder for everyone to view and edit

## Questions 
-  Which antioxidant should we focus on based on our current finding after running the random forest and ggpicrust2?
  - Problem = no significant results found in any of the groups we looked at
      - Might be because of the way we are indexing our intake groups causing there to be very uneven distributions therefore making it harder to find significance within the limited sample size -> should we try another way of indexing? How can another way of indexing be justified? Would this count as us manipulating data to get our desired result? :((

### Reran Code
- Note: This result still needs to be verified since it was written at 1AM and the writer might have missed something somewhere :((
- Reran beta-carotene analysis with standardized DAI method instead of RDI threshold and still didn't find significant difference between groups in terms of alpha and beta diversity but found 8/25 significant genera through differential abundance analysis
  - Note from another person: I also reran the analysis and if we look at "diff" then there are some significant results, but if we look at "diff_robust" column all the results are still FALSE. (I haven't updated the R script yet because it is very messy right now and I still need to double-check my work:,))
- Reran the picrust anaylsis as well and actually did find some significant pathways with p < 0.05 but all the log2foldchange values were way below 1 -> what does this mean?
- Also weird results with p-values where many pathways have the same p value
  - How to understand this new plot?
- <img width="5400" height="3000" alt="peb Error Bar Fixed" src="https://github.com/user-attachments/assets/736b3ec1-4fcc-48c6-895c-538ae485227a" />

