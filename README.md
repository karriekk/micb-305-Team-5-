# MICB 305 (2025-26 Winter Term 2) Group Project on Parkinson's Dataset

Team 5 members: Carrie Sun, Coe McGrath, Cynthia Lin, Emily Ju, Yanting Xiong

Link to the original dataset by Cirstea et al.:  https://doi.org/10.1002/mds.28052

## Project Summary
Parkinson’s disease, or PD, is an age-related, progressive neurodegenerative disorder characterized by both motor and non-motor symptoms. In addition to the well-established neuropathological and clinical features, growing evidence highlights the significance of gut microbiome in modulating the nervous system through the gut-brain axis, as well as its potential role in PD pathophysiology. 

Alterations in the gut microbiome of PD patients have been increasingly found in recent research, which is characterized by reduced short-chain fatty acid (SCFA)-producing bacteria and increased pro-inflammatory taxa. 

Diet plays a key role in shaping the microbiome, and healthy dietary patterns have been associated with beneficial microbial changes in PD patients. In particular, dietary antioxidants have been found to reduce gut inflammation and promote beneficial microbial activity. Thus, antioxidants are hypothesized to indirectly provide neuroprotection through microbiome modulation. 

Despite growing research in the field, most studies focus on comparing between PD patients and healthy controls, with few examining microbiome variability within PD populations. Additionally, it remains unclear whether antioxidant-driven microbiome changes are correlated with shifts in cognitive performance in PD patients. Therefore, our study aims to address these knowledge gaps using the dataset from Cirstea et al.

## Research Question
How is gut microbiota taxonomic and functional composition in Parkinson’s Disease patients affected by dietary antioxidant intake, and how are these microbial features correlated with cognitive performance change assessed by Montreal Cognitive Assessment (MoCA)?

## Project Aims with Links to the Corresponding R Scripts and Results

#### Aim 0: QIIME2 + Metadata Filtering and Wrangling
- [QIIME2](https://github.com/karriekk/micb-305-Team-5-/blob/main/terminal_code_record/terminal_code_record.Rmd)

- [Metadata filtering and wrangling](https://github.com/karriekk/micb-305-Team-5-/blob/main/R_scripts/Aim%200/metadata_filtering_and_wrangling.Rmd)

#### Aim 1: Diversity Analysis
- Alpha diversity analysis

  - [R script](https://github.com/karriekk/micb-305-Team-5-/blob/main/R_scripts/Aim_1/Alpha_diversity/alpha_diversity_analysis.Rmd)
 
  - [Summary of results](https://github.com/karriekk/micb-305-Team-5-/blob/main/Results/Summary_of_results/Aim_1/Alpha_diversity/alpha_diversity_results_summary.md)

  - [Figures](https://github.com/karriekk/micb-305-Team-5-/tree/main/Results/Figures/Aim_1/Alpha_diversity)
 
- Beta diversity analysis

  - R scripts

    - [Bray-Curtis](https://github.com/karriekk/micb-305-Team-5-/blob/main/R_scripts/Aim_1/Beta_diversity/beta_diversity_analysis_bray-curtis.Rmd)
   
    - [Weighted UniFrac](https://github.com/karriekk/micb-305-Team-5-/blob/main/R_scripts/Aim_1/Beta_diversity/beta_diversity_analysis_weighted_unifrac.Rmd)
   
    - [Unweighted UniFrac](https://github.com/karriekk/micb-305-Team-5-/blob/main/R_scripts/Aim_1/Beta_diversity/beta_diversity_analysis_unweighted_unifrac.Rmd)
   
    - [Jaccard](https://github.com/karriekk/micb-305-Team-5-/blob/main/R_scripts/Aim_1/Beta_diversity/beta_diversity_analysis_jaccard.Rmd)
 
  - Summary of results
 
    - [Bray-Curtis](https://github.com/karriekk/micb-305-Team-5-/blob/main/Results/Summary_of_results/Aim_1/Beta_diversity/beta_diversity(bray-curtis)_results_summary.md)
   
    - [Weighted UniFrac](https://github.com/karriekk/micb-305-Team-5-/blob/main/Results/Summary_of_results/Aim_1/Beta_diversity/beta_diversity_weighted_unifrac_results_summary.md)
   
    - [Unweighted UniFrac](https://github.com/karriekk/micb-305-Team-5-/blob/main/Results/Summary_of_results/Aim_1/Beta_diversity/beta_diversity_unweighted_unifrac_results_summary.md)
   
    - [Jaccard](https://github.com/karriekk/micb-305-Team-5-/blob/main/Results/Summary_of_results/Aim_1/Beta_diversity/beta_diversity_jaccard_results_summary.md)
 
  - Figures

#### Aim 2: Taxonomy Analysis
- Indicator species analysis

  - [R script](https://github.com/karriekk/micb-305-Team-5-/blob/main/R_scripts/Aim_2/indicator_species_analysis/indicator_species_analysis(final_version).Rmd)
 
  - [Summary of results](https://github.com/karriekk/micb-305-Team-5-/blob/main/Results/Summary_of_results/Aim_2/Indicator_species_analysis_results_summary.md)

  - [Figures](https://github.com/karriekk/micb-305-Team-5-/tree/main/Results/Figures/Aim_2/Indicator_species)

- Differential abundance analysis

  - [R script](https://github.com/karriekk/micb-305-Team-5-/blob/main/R_scripts/Aim_2/differential_abundance_analysis_maaslin2.Rmd)
 
  - [Tables](https://github.com/karriekk/micb-305-Team-5-/tree/main/Results/Tables/Aim_2/Differential_abundance_analysis)

#### Aim 3: Metabolic Pathway Analysis
- Alpha-carotene
  
  - R script
 
  - [Figures](https://github.com/karriekk/micb-305-Team-5-/tree/main/Results/Figures/Aim_3/Alpha-carotene)
 
- Beta-carotene
  
  - R script
 
  - [Figures](https://github.com/karriekk/micb-305-Team-5-/tree/main/Results/Figures/Aim_3/Beta-carotene)
 
- Vitamin A
  
  - R script
 
  - [Figures](https://github.com/karriekk/micb-305-Team-5-/tree/main/Results/Figures/Aim_3/Vitamin_A)
 
- Vitamin C
  
  - R script
 
  - [Figures](https://github.com/karriekk/micb-305-Team-5-/tree/main/Results/Figures/Aim_3/Vitamin_C)
 
- Vitamin E
  
  - R script
 
  - [Figures](https://github.com/karriekk/micb-305-Team-5-/tree/main/Results/Figures/Aim_3/Vitamin_E)
 
- Combined
  
  - R script
 
  - [Figures](https://github.com/karriekk/micb-305-Team-5-/tree/main/Results/Figures/Aim_3/Combined)

#### Aim 4: Link Everything to Cognitive Performance (MoCA)
- Indicator Taxon - Escherichia-Shigella

  - [R script](https://github.com/karriekk/micb-305-Team-5-/blob/main/R_scripts/Aim_4/Aim4_Indicator_Taxa(version_2_relative_abundance).Rmd)
 
  - Figure

## Weekly Meeting Agenda
You can access all of our weekly meeting agendas [here](https://github.com/karriekk/micb-305-Team-5-/tree/main/meeting_agenda), or click the hyperlinks below to open a specific agenda.

#### April
- [Apr 7](https://github.com/karriekk/micb-305-Team-5-/blob/main/meeting_agenda/Apr%207%20Agenda.md)

- [Apr 2](https://github.com/karriekk/micb-305-Team-5-/blob/main/meeting_agenda/Apr%202%20Agenda.md)

#### March
- [Mar 26](https://github.com/karriekk/micb-305-Team-5-/blob/main/meeting_agenda/Mar%2026%20Agenda.md)

- [Mar 19](https://github.com/karriekk/micb-305-Team-5-/blob/main/meeting_agenda/Mar%2019%20Agenda.md)

- [Mar 12](https://github.com/karriekk/micb-305-Team-5-/blob/main/meeting_agenda/Mar%2012%20Agenda.md)

- [Mar 5](https://github.com/karriekk/micb-305-Team-5-/blob/main/meeting_agenda/Mar%205%20Agenda.md)

#### February
- [Feb 26](https://github.com/karriekk/micb-305-Team-5-/blob/main/meeting_agenda/Feb%2026%20Agenda.md)

- [Feb 19 Reading Week](https://github.com/karriekk/micb-305-Team-5-/blob/main/meeting_agenda/Reading%20Week%20Agenda.md)

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
