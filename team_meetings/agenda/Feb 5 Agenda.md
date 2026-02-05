## 1.30 Office Hour Notes
### Aims
Overall Goal:
- To understand how dietary antioxidant intake shapes the gut microbiome and whether microbiome-mediated antioxidant metabolism is associated with cognitive outcomes.

Aim 1:
- Determine how antioxidant intake is associated with gut microbiome composition and diversity. Specifically, we will assess how varying levels of antioxidant intake select for specific microbial taxa and examine corresponding changes in alpha and beta diversity.

Aim 2 (taxa):
- Identify gut microbial taxa that are differentially abundant across levels of antioxidant intake.

Aim 3 (function):
- Characterize the functional capacity of the gut microbiome related to antioxidant metabolism.

Aim 4 (Research Question):
- Evaluate whether the presence of microbial genes involved in antioxidant metabolism modifies the relationship between antioxidant intake and cognitive performance (e.g., if individuals lacking genes involved in antioxidant metabolism actually have a lower cognitive score than the ones have the genes).

### Questions
- How can we start apporach those questions
- What specific modules we need to look at
- What kind of analysis is needed
- Current plan for analysis:
  - Find One antioxidant → beta diversity → beta diversity of each antioxidant
  - Transform the data from highest intake to lowest intake: → as need to normalize the columns —> most intake
  - Take Top 1% for antioxidant → most of the all antioxidant and Top 1% for antioxidant but another is median → median
- Not exactly sure how to start processing data
    - Which files do we need to work on right now
    - What needs to be run in R - which modules would be useful for us right now since we are doing our project in a different order than other groups
    - Finding a solid workflow for the coming weeks
 
## Literature Review Notes 
### 1. Regulation of gut microbiota by vitamin C, vitamin E and β-carotene 
(https://doi.org/10.1016/j.foodres.2023.112749)

- VC and betaC increase the alpha-diversity of the gut microbiota - indicator of gut microbiome health.
- VC, VE, and betaC significantly affect the ratio of Firmicutes/Bacteroidetes (increase in ratio), which is important in regulating and maintaining the homeostasis of the gut microbiota environment.
- VC, VE, and betaC intake provide health benefits by regulating the metabolic activity of the host gut microbiota (e.g., increase the abundance of butyrate-producing microbiomes).
- The authors noted that alteration in gut microbiota composition my also be caused by some other food intake.
  - ###### Question: should we control for other food/dietary nutrients intake when doing the analysis?
- Need to further explore the role of antioxidant activity of vitamins in regulating the gut microbiota and the corresponding molecular mechanisms in further studies. 


