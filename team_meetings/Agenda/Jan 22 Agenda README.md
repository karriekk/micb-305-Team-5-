# Jan 22 Team Meeting Agenda
## 1. Look through the literature (i.e., Google Scholar or similar) to see what’s been previously done

### Research question 1: Are specific co-abundance groups (CAGs) more strongly associated with central adiposity (waist circumference) than with BMI? (Colombia dataset)
- Link: https://doi.org/10.1111/j.2047-6310.2014.218.x
  - Study conducted using subjects with an European origin, and researchers found that BMI is strongly correlated with measures of central adiposity, fat distribution, insulin resistance and dyslipidaemia.
- Link: https://doi.org/10.1016/j.csbj.2020.09.026
  - Investigated the relationship between gut microbiome and visceral fat accumulation (VFA), as well as other obese parameters such as waist (gauges both visceral fat and upper-body subcutaneous fat), hipline, waist-to-hip ratio (WHR), and BMI.
  - They found that among other obese parameters, VFA has the largest number of correlation with microbial species. They also pointed out that BMI can only evaluate total body fat, but not fat distribution.
    - This is a bit similar to our research question, except that one of the independent variables we are interested in exploring is central adiposity (broad term for fat around the abdomen, encompassing both the fat just under the skin (subcutaneous) and the deeper, more harmful fat surrounding organs (visceral fat)) instead of visceral fat, and that the above research focuses on the Chinese cohort, whereas the dataset we will be using focuses on the Colombia cohort.
      -  Some thoughts: maybe consider about doing a cross-comparison between these two cohorts and link the differences (if any) to other factors such as genetics, geographical factors, and diets? Not sure how feasible this would be though.
      -  Question: Is waist circumference the same as waist (which is what is measured as one of the obese parameters in a previous study)? 

### Research question 2: To what extent does the predicted functional capacity of the gut microbiota (via 16S rRNA sequencing) to metabolize dietary antioxidants act as a critical moderator for cognitive performance (MoCA) in Parkinson’s Disease patients? (PD dataset)
- Overall trying to investigate if the effect of diet on MoCA is dependent on the microbes where considering role of oxidative stress is relatively new idea in comparison to just looking at motor symptoms
- Many studies have been done to relate diet and and the neurodegeneration aspect of PD but don’t directly look at a moderation model for antioxidant metabolic capacity:
  - Metcalfe-Roach, Avril. Diet and the microbiome in Parkinson’s disease. Diss. UNIVERSITY OF BRITISH COLUMBIA (Vancouver, 2024.)
    - Discussed relation of diet and disease onset
    - Looked more at correlation and longitudinal analysis
    - We will be looking more at how microbiome mediates the diet-brain linkage and specifically focusing on moca scores
  - Wallen et al. established that dietary patterns and microbial dysbiosis independently characterize the PD gut environment but what remains unknown is whether the microbiome’s functional capacity to metabolize antioxidants is a necessary condition for dietary neuroprotection (https://doi.org/10.1101/2021.07.28.21261293) (note that paper has not been peer reviewed yet)
    - Our research question can extend their work by testing a moderation model where microbial antioxidant pathways determine the clinical efficacy of dietary intake on cognitive performance
  - Previous UJEMI study: https://ojs.library.ubc.ca/index.php/UJEMI/article/view/196778
    - Looked at how Dietary vitamin B1, B2, and B6 intake influence the microbial composition and functional potential of the gut microbiome in Parkinson’s disease
    - Sokolovska et al. argue that many dietary antioxidants are bio-inactive until gut microbes transform them
    - We want to see if the link between diet and MoCA only exists in patients with high microbial capacity
    - Sokolovska et al. looked for inflammation of the gut as a marker where we will try to look at antioxidant capacity of the microbiome as a marker
    -Mentioned certain strains (like Bifidobacterium) actually synthesize antioxidants like Folate and Riboflavin (which are the dataset as Total_folate and Vitamin_B2)
- Data considerations:
  - Noted that moca scores data are very skewed towards higher end of the spectrum which could cause problems if we use linear regression models
  - Methods to address this problem:
    - We could try to transform our data through normalization via a reflected log transformation
    - Categorical conversion could be applied by treating the scores as a binary state
    - Without applying data transformations we could use non-parametric modelling like random forest regressors where the distribution doesn’t affect the results

### Research question 3: Are microbiome differences in Hispanic populations more strongly associated with obesity-related measures than with type 2 diabetes diagnosis itself? (Hispanic Datasets #14)
Gut Microbiome and Its Impact on Obesity and Obesity-Related Disorders
- DOI: https://doi.org/10.1007/s11894-022-00859-0
- A great review articles contains many research articles related to the research question. 

Gut Microbiota in Human Adults with Type 2 Diabetes Differs from Non-Diabetic Adults
- DOI: https://doi.org/10.1371/journal.pone.0009085
- One of the research article mention in the review article
- Conducted using 36 male adults (gender not as diverse as #14 datasets) with UNKNOWN religion (not the same as our hispanic group and comparison with the human microbiome genome)
- Found out that “Bacteroidetes to Firmicutes ratio as well as the Bacteroides-Prevotella/Clostridium coccoides-Eubacterium ratio were positively correlated with serum glucose levels”
- Compare to #14 datasets : “ a significantly higher Firmicutes:Bacteroidetes ratio compared to the HMP . Higher fecal concentrations of short-chain fatty acids (SCFA) in obese compared with lean individuals have been attributed to a higher Firmicutes:Bacteroidetes ratio”--> Somehow similar result is happening

A core gut microbiome in obese and lean twins
- DOI: 10.1038/nature07540
- Phylum Level changes will cause obesity and metabollic pathway.
- Compare to #14 datasets: the datasets are showing the difference in microbiome in hispanic group that cause the differences in obesity related measures (such as cholestrol pathway)

Overall:
- Novelty: Think it is novel enough that no one has really tested on this specific population
- Issue: How do we actually define “more strongly related”---> is it by statistical inferences? But they are measuring in different degree, how do we measure the comparison 


## 2. Download the metadata and open it in Excel. What groups would you need to define for your project idea? How many samples would be in each group, and is that a feasible number for an analysis? (bare minimum = 3/group)

### Research question 1: Are specific co-abundance groups (CAGs) more strongly associated with central adiposity (waist circumference) than with BMI? (Columbia dataset)
- Variables of interest:
  - Co-abundance groups 
  - BMI (numeric value)
    - Can group individuals based on BMI to study co-abundance differece between different groups of individuals
      - In the metadata, it classifies individuals as "overweight", "obese" and "lean" based on BMI, each group has more than 3 samples.
  - Central adiposity/waist circumference (numeric value)
    - Can group individuals based on central adoposity to study co-abundance difference between different groups of individuals (need to define the standards that will be used to group individuals)

### Research Question 3:  Are microbiome differences in Hispanic populations more strongly associated with obesity-related measures than with type 2 diabetes diagnosis itself? (Hispanic Dataset #14)
Variable Investigating (Y variable )
- Obesity related measure:
  - Weight (64 numerical values)
  - BMI (64 numerical values)
  - Cholesterol (64 numerical values)
  - Triglycerides (64 numerical values)
  - Hdl_chol (64 numerical values)
  - Ldl_chol (62 numerical values, 2 NAs)
    
- Type II Diamete related measure 
  - Mmol_glucose (Fasting Plasma glucose) (64 numerical values)
  - Homa_ir (Insulin resistence)  (64 numerical values)
  - Homa_beta (insulin deficiency→ measure the B cell activity)  (64 numerical values)
