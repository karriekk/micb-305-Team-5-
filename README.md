# MICB 305 (2025-26 Winter Term 2) Group Project on Parkinson's Dataset

Team 5 members: Carrie Sun, Coe McGrath, Cynthia Lin, Emily Ju, Yanting Xiong

Link to the original dataset by Cirstea et al.:  https://doi.org/10.1002/mds.28052

## Project Summary
Parkinson's disease (PD) is an age-related neurodegenerative disorder characterized by both motor and non-motor symptoms. In addition to the well-characterized neuropathological and clinal features, growing evidence highlights the significance of the gut microbiome in modulating the nervous system through the gut-brain axis, and its potential role in PD pathophysiology.

Diet plays a key role in modulating the gut microbiome, and dietary antioxidants have gained increasing attention for their potential neuroprotective effects, which may be explained by their ability to modulate the gut microbiome and reduce oxidative stress. 

However, there is limited insight into how antioxidant-driven microbiome changes are correlated with shifts in cognitive performance within PD populations. Therefore, this study aimed to investigate the impact of dietary antioxidant intake, specifically vitamins A, C, E, alpha- and beta-carotene, and their synergistic effects, on the gut microbiome in association with the cognitive performance in PD patients.

To achieve this, this study utilized a previously published dataset from Cirstea et al., which includes 16S rRNA gene sequencing data generated from fecal samples collected from 197 PD patients and 103 age-matched healthy controls between the ages of 40 and 85. Using this dataset, we focused exclusively on PD patients to investigate how varying levels of dietary antioxidant intake influence the taxonomic composition and predicted functional capacity of the gut microbiome, and how these changes are associated with cognitive performance assessed using the Montreal Cognitive Assessment (MoCA).

Ultimately, this study aimed to identify potential dietary targets and optimal intake levels to modulate PD progression and mitigative cognitive decline. 

## Research Question
How is gut microbiota taxonomic and functional composition in Parkinson’s Disease patients affected by dietary antioxidant intake, and how are these microbial features correlated with cognitive performance change assessed by Montreal Cognitive Assessment (MoCA)?

## Project Aims with Links to the Corresponding R Scripts and Results

#### Aim 0: QIIME 2 + Metadata Filtering and Wrangling
- [QIIME 2](https://github.com/karriekk/micb-305-Team-5-/blob/main/terminal_code_record/terminal_code_record.Rmd)

- [Metadata filtering and wrangling](https://github.com/karriekk/micb-305-Effects-of-Antioxidant-intake-on-Parkinson-s-Disease-Patients/blob/main/R_scripts/Aim_0/metadata_filtering_and_wrangling.Rmd)

#### Aim 1: Diversity Analysis (Table 1, Figure S1)
- Alpha diversity analysis (Figure S1)

  - [R script](https://github.com/karriekk/micb-305-Effects-of-Antioxidant-intake-on-Parkinson-s-Disease-Patients/blob/main/R_scripts/Aim_1%20(Table%201%2C%20Figure%20S1)/Alpha_diversity%20(Figure%20S1)/alpha_diversity_analysis_final.Rmd)
 
  - [Summary of results](https://github.com/karriekk/micb-305-Effects-of-Antioxidant-intake-on-Parkinson-s-Disease-Patients/blob/main/Results/Summary_of_results/Aim_1/Alpha_diversity/alpha_diversity_results_summary.md)

  - Figures
 
    - [Simpson](https://github.com/karriekk/micb-305-Effects-of-Antioxidant-intake-on-Parkinson-s-Disease-Patients/tree/main/Results/Figures/Aim_1_Alpha_Diversity%20(Figure_S1)/Alpha_diversity%20(Figure_S1)/Simpson)
   
    - [Shannon](https://github.com/karriekk/micb-305-Effects-of-Antioxidant-intake-on-Parkinson-s-Disease-Patients/tree/main/Results/Figures/Aim_1_Alpha_Diversity%20(Figure_S1)/Alpha_diversity%20(Figure_S1)/Shannon)
   
    - [Chao1](https://github.com/karriekk/micb-305-Effects-of-Antioxidant-intake-on-Parkinson-s-Disease-Patients/tree/main/Results/Figures/Aim_1_Alpha_Diversity%20(Figure_S1)/Alpha_diversity%20(Figure_S1)/Chao1)
   
    - [Observed](https://github.com/karriekk/micb-305-Effects-of-Antioxidant-intake-on-Parkinson-s-Disease-Patients/tree/main/Results/Figures/Aim_1_Alpha_Diversity%20(Figure_S1)/Alpha_diversity%20(Figure_S1)/Observed)
 
- Beta diversity analysis (Table 1)

  - R scripts

    - [Bray-Curtis](https://github.com/karriekk/micb-305-Team-5-/blob/main/R_scripts/Aim_1/Beta_diversity/beta_diversity_analysis_bray-curtis.Rmd)
   
    - [Weighted UniFrac](https://github.com/karriekk/micb-305-Team-5-/blob/main/R_scripts/Aim_1/Beta_diversity/beta_diversity_analysis_weighted_unifrac.Rmd)
   
    - [Unweighted UniFrac](https://github.com/karriekk/micb-305-Team-5-/blob/main/R_scripts/Aim_1/Beta_diversity/beta_diversity_analysis_unweighted_unifrac.Rmd)
   
    - [Jaccard](https://github.com/karriekk/micb-305-Team-5-/blob/main/R_scripts/Aim_1/Beta_diversity/beta_diversity_analysis_jaccard.Rmd)
 
  - [Table](https://github.com/karriekk/micb-305-Effects-of-Antioxidant-intake-on-Parkinson-s-Disease-Patients/blob/main/Results/Tables/Aim_1/Beta_diversity.md)
  
#### Aim 2: Taxonomy Analysis (Figure 1, Table S1, Table S2)
- Indicator species analysis (Figure 1, Table S2)

  - [R script](https://github.com/karriekk/micb-305-Team-5-/blob/main/R_scripts/Aim_2/indicator_species_analysis/indicator_species_analysis(final_version).Rmd)
 
  - [Summary of results](https://github.com/karriekk/micb-305-Team-5-/blob/main/Results/Summary_of_results/Aim_2/Indicator_species_analysis_results_summary.md)

  - [Figures](https://github.com/karriekk/micb-305-Team-5-/tree/main/Results/Figures/Aim_2/Indicator_species)

- Differential abundance analysis (Table S1)

  - [R script](https://github.com/karriekk/micb-305-Effects-of-Antioxidant-intake-on-Parkinson-s-Disease-Patients/blob/main/R_scripts/Aim_2/Differential_abundance_analysis/differential_abundance_analysis_maaslin2.Rmd)
 
  - [Tables](https://github.com/karriekk/micb-305-Team-5-/tree/main/Results/Tables/Aim_2/Differential_abundance_analysis)

#### Aim 3: Functional Analysis (Figure 3, Figure S3, Figure S4)
- Alpha-carotene
  
  - [R script](https://github.com/karriekk/micb-305-Team-5-/blob/main/R_scripts/Aim_3/Alpha-caro/ACpicrust_differential_abundance.Rmd)
 
  - [Figures](https://github.com/karriekk/micb-305-Team-5-/tree/main/Results/Figures/Aim_3/Alpha-carotene)
 
- Beta-carotene
  
  - [R scripts](https://github.com/karriekk/micb-305-Team-5-/tree/main/R_scripts/Aim_3/Beta-caro)
 
  - [Figures](https://github.com/karriekk/micb-305-Team-5-/tree/main/Results/Figures/Aim_3/Beta-carotene)
 
- Vitamin A
  
  - [R script](https://github.com/karriekk/micb-305-Team-5-/blob/main/R_scripts/Aim_3/Vitamin_A/VA_Picrust_differential_abundance.Rmd)
 
  - [Figures](https://github.com/karriekk/micb-305-Team-5-/tree/main/Results/Figures/Aim_3/Vitamin_A)
 
- Vitamin C
  
  - [R scripts](https://github.com/karriekk/micb-305-Team-5-/tree/main/R_scripts/Aim_3/Vitamin_C)
 
  - [Figures](https://github.com/karriekk/micb-305-Team-5-/tree/main/Results/Figures/Aim_3/Vitamin_C)
 
- Vitamin E
  
  - [R scripts](https://github.com/karriekk/micb-305-Team-5-/tree/main/R_scripts/Aim_3/Vitamin_E)
 
  - [Figures](https://github.com/karriekk/micb-305-Team-5-/tree/main/Results/Figures/Aim_3/Vitamin_E)
 
- Combined
  
  - [R script](https://github.com/karriekk/micb-305-Team-5-/blob/main/R_scripts/Aim_3/Combined_index/combined_picrust_differential_abundance.Rmd)
 
  - [Figures](https://github.com/karriekk/micb-305-Team-5-/tree/main/Results/Figures/Aim_3/Combined)

#### Aim 4: Link Everything to Cognitive Performance (MoCA) (Figure 2)
- Indicator Taxon - Escherichia-Shigella

  - [R script](https://github.com/karriekk/micb-305-Effects-of-Antioxidant-intake-on-Parkinson-s-Disease-Patients/blob/main/R_scripts/Aim_4/Aim4_Indicator_Taxon(log-transformed_relative_abundance).Rmd)
 
  - [Figure](https://github.com/karriekk/micb-305-Team-5-/blob/main/Results/Figures/Aim_4/Indicator_taxon/Association%20Between%20Log-10%20Transformed%20Relative%20Abundance%20of%20Escherichia-Shigella%20and%20MoCA%20Score%20in%20PD%20Patients.png)

## Weekly Meeting Agenda
You can access all of our weekly meeting agendas [here](https://github.com/karriekk/micb-305-Team-5-/tree/main/meeting_agenda), or click the hyperlinks below to open a specific agenda.

#### April
- [Apr 15](https://github.com/karriekk/micb-305-Effects-of-Antioxidant-intake-on-Parkinson-s-Disease-Patients/blob/main/meeting_agenda/Apr%2015%20Agenda.md)

- [Apr 7](https://github.com/karriekk/micb-305-Team-5-/blob/main/meeting_agenda/Apr%207%20Agenda.md)

- [Apr 2](https://github.com/karriekk/micb-305-Team-5-/blob/main/meeting_agenda/Apr%202%20Agenda.md)

#### March
- [Mar 26](https://github.com/karriekk/micb-305-Team-5-/blob/main/meeting_agenda/Mar%2026%20Agenda.md)

- [Mar 19](https://github.com/karriekk/micb-305-Team-5-/blob/main/meeting_agenda/Mar%2019%20Agenda.md)

- [Mar 12](https://github.com/karriekk/micb-305-Team-5-/blob/main/meeting_agenda/Mar%2012%20Agenda.md)

- [Mar 5](https://github.com/karriekk/micb-305-Team-5-/blob/main/meeting_agenda/Mar%205%20Agenda.md)

#### February
- [Feb 26](https://github.com/karriekk/micb-305-Team-5-/blob/main/meeting_agenda/Feb%2026%20Agenda.md)

- [Feb 19 Reading Week](https://github.com/karriekk/micb-305-Effects-of-Antioxidant-intake-on-Parkinson-s-Disease-Patients/blob/main/meeting_agenda/Feb%2019%20Reading%20Week%20Agenda.md)

- [Feb 12](https://github.com/karriekk/micb-305-Team-5-/blob/main/meeting_agenda/Feb%2012%20Agenda.md)

- [Feb 5](https://github.com/karriekk/micb-305-Team-5-/blob/main/meeting_agenda/Feb%205%20Agenda.md)

#### January
- [Jan 29](https://github.com/karriekk/micb-305-Team-5-/blob/main/meeting_agenda/Jan%2029%20Agenda.md)

- [Jan 22](https://github.com/karriekk/micb-305-Team-5-/blob/main/meeting_agenda/Jan%2022%20Agenda.md)

## Weekly Team Meeting Notes
You can access all of our weekly team meeting notes [here](https://github.com/karriekk/micb-305-Team-5-/tree/main/team_meeting_notes), or click the hyperlinks below to open a specific note.

#### April
- [Apr 7](https://github.com/karriekk/micb-305-Team-5-/blob/main/team_meeting_notes/Apr%207%20Team%20Meeting%20Notes.md)

- [Apr 2](https://github.com/karriekk/micb-305-Team-5-/blob/main/team_meeting_notes/Apr%202%20Team%20Meeting%20Notes.md)

#### March
- [Mar 26](https://github.com/karriekk/micb-305-Team-5-/blob/main/team_meeting_notes/Mar%2026%20Team%20Meeting%20Notes.md)

- [Mar 19](https://github.com/karriekk/micb-305-Team-5-/blob/main/team_meeting_notes/Mar%2019%20Team%20Meeting%20Notes.md)

- [Mar 12](https://github.com/karriekk/micb-305-Team-5-/blob/main/team_meeting_notes/Mar%2012%20Team%20Meeting%20Notes.md)

- [Mar 5](https://github.com/karriekk/micb-305-Team-5-/blob/main/team_meeting_notes/Mar%205%20Team%20Meeting%20Notes.md)

#### February
- [Feb 26](https://github.com/karriekk/micb-305-Team-5-/blob/main/team_meeting_notes/Feb%2026%20Team%20Meeting%20Notes.md)

- [Feb 19 Reading Week](https://github.com/karriekk/micb-305-Team-5-/blob/main/team_meeting_notes/Feb%2019%20RW%20Team%20Meeting%20Notes.md)

- [Feb 12](https://github.com/karriekk/micb-305-Team-5-/blob/main/team_meeting_notes/Feb%2012%20Team%20Meeting%20Notes.md)

- [Feb 5](https://github.com/karriekk/micb-305-Team-5-/blob/main/team_meeting_notes/Feb%205%20Team%20Meeting%20Notes.md)

#### January
- [Jan 29](https://github.com/karriekk/micb-305-Team-5-/blob/main/team_meeting_notes/Jan%2029%20Team%20Meeting%20Notes.md)

- [Jan 22](https://github.com/karriekk/micb-305-Team-5-/blob/main/team_meeting_notes/Jan%2022%20Team%20Meeting%20Notes.md)

- [Jan 15](https://github.com/karriekk/micb-305-Team-5-/blob/main/team_meeting_notes/Jan%2015%20Team%20Meeting%20Notes.md)
