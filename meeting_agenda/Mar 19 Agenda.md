## Questions related to data analysis
1. Do we need to specify permutations = when doing beta diversity analysis
2. Is there a way to factor in confounding variables when generating plots for beta-diversity analysis? Although the p-value indicates a statistically significant difference after adjusting for confounding variables, this difference is not readily apparent from visual inspection of the plots generated, therefore I was wondering if this might be an issue.
3. I used linear regression model when running the alpha diversity analysis, and was wondering how to add the corresponding p-values onto the plots.
4. Having troubles filtering the statistical_table generated when doing taxonomy differential abundance analysis due to the space in between words (want to filter for it and show the stats even though no significant difference is obeserved across all groups of dietary antioxidants).
<img width="169" height="22" alt="diff_ robust_Tert_BCBC High" src="https://github.com/user-attachments/assets/2bc9ec26-b81d-41f4-83e1-34bf0c9da324" />

5. Would it be possible to go over the code together to ensure that we are doing all the analyses correctly and logically?

## Some updates about the analysis
### Indicator taxa analysis
- Was able to find indicator taxa for "BC High", "VA High", "VC High", "VE High", and "Combine High" groups (p-values smaller than 0.05), but the stat values are all below 0.5. This means that although several taxa are significantly associated with the high intake groups, they all exhibited relatively low indicator values, which is drive primarily by the low within-group prevalence. This suggests that these taxa are not consistently present across individuals within the high-intake group and therefore represent weak indicators. And because of this, it is possible to generate meaningful plots because there are many zeros in both high and low groups.
  - Some of the taxa that are enriched are associated with SCFA-producing.
  - I was wondering if I should keep these taxa and use them to perform analyses in aim 4 (and state the limitations in the discussion), or if I should filter out all these indicator taxa due to the stat threshold of 0.7.
  - Yanting did a indicator taxa analysis which compares only high and low groups (as she filtered high and low group out first), but Carrie has the default code on the MICB305 GiHhub. Is it necessary to compare all 3 or just high and low is enough?
      - One issue when comparing three groups together is that there are some cases where some taxa are significantly abundant in both high and low groups.
      - And one limitation associated with including only the high and low groups in the analysis is that we're excluding 1/3 of the PD patients.
