## Beta Diversity Analysis using Bray-Curtis

### Notes:
1. Because we will be controlling for entacapone in downstream analyses and it contains NA values, they will be removed from the filtered metadata.
   - 10 PD patients are removed because they do not have entacapone intakes recorded.
2. When running beta-diversity analysis, age, sex, and entacapone are accounted for as confounding variables.
3. A sampling depth of 6515 is used when doing the analysis. At this sampling depth, only 14 samples are excluded from the analysis and we have retained 1,192,428 (50.04%) features in 183 (92.89%) samples.

### Beta diversity analysis of Beta Carotene
- BC low vs BC high: p-value = 0.003
- BC low vs BC medium: p-value = 0.296
- BC medium vs BC high: p-value = 0.002

### Beta diversity analysis of Alpha Carotene
- AC low vs AC high: p-value = 0.129
- AC low vs AC medium: p-value = 0.072
- AC medium vs AC high: p-value = 0.052

### Beta diversity analysis of Vitamin C
- VC low vs VC high: p-value = 0.006
- VC low vs VC medium: p-value = 0.258
- VC medium vs VC high: p-value = 0.002

### Beta diversity analysis of Vitamin A  
- VA low vs VA high: p-value = 0.06
- VA low vs VA medium: p-value = 0.156
- VA medium vs VA high: p-value = 0.009

### Beta diversity analysis of Vitamin E
- VE low vs VE high: p-value = 0.001
- VE low vs VE medium: p-value = 0.009
- VE medium vs VE high: p-value = 0.009

### Beta diversity analysis on combined dietary antioxidants
- Combined low vs Combined high: p-value = 0.001
- Combined low vs Combined medium: p-value = 0.172
- Combined medium vs Combined high: p-value = 0.003

