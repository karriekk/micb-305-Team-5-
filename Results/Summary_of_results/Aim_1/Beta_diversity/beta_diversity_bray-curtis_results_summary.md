## Beta Diversity Analysis using Bray-Curtis

### Notes:
1. Because we will be controlling for entacapone in downstream analyses and it contains NA values, they will be removed from the filtered metadata.
   - 10 PD patients are removed because they do not have entacapone intakes recorded.
2. When running beta-diversity analysis, age, sex, and entacapone are accounted for as confounding variables.
3. A sampling depth of 6515 is used when doing the analysis. At this sampling depth, only 14 samples are excluded from the analysis and we have retained 1,192,428 (50.04%) features in 183 (92.89%) samples.

### Beta diversity analysis of Beta Carotene
<img width="1438" height="885" alt="Screenshot 2026-03-26 at 13 56 42" src="https://github.com/user-attachments/assets/1e012df1-0b15-4167-abbe-6023f8c45ce6" />

- BC low vs BC high: p-value = 0.003
- BC low vs BC medium: p-value = 0.296
- BC medium vs BC high: p-value = 0.002

### Beta diversity analysis of Alpha Carotene
<img width="1432" height="888" alt="Screenshot 2026-03-27 at 21 30 41" src="https://github.com/user-attachments/assets/a13726a7-3cbd-4bd0-9976-8522ebf85b68" />

- AC low vs AC high: p-value = 0.129
- AC low vs AC medium: p-value = 0.072
- AC medium vs AC high: p-value = 0.052

### Beta diversity analysis of Vitamin C
<img width="1423" height="875" alt="Screenshot 2026-03-27 at 21 54 18" src="https://github.com/user-attachments/assets/f0b5a70a-9a9f-4696-b42e-780bc7774a24" />

- VC low vs VC high: p-value = 0.006
- VC low vs VC medium: p-value = 0.258
- VC medium vs VC high: p-value = 0.002

### Beta diversity analysis of Vitamin A
<img width="1415" height="883" alt="Screenshot 2026-03-27 at 21 56 45" src="https://github.com/user-attachments/assets/ff4c75e0-3cbf-4942-ab4e-6404f2a4f190" />
  
- VA low vs VA high: p-value = 0.06
- VA low vs VA medium: p-value = 0.156
- VA medium vs VA high: p-value = 0.009

### Beta diversity analysis of Vitamin E
<img width="1415" height="884" alt="Screenshot 2026-03-27 at 22 00 42" src="https://github.com/user-attachments/assets/d86fa32b-e77b-4d0a-961e-7e4feaa955fd" />

- VE low vs VE high: p-value = 0.001
- VE low vs VE medium: p-value = 0.009
- VE medium vs VE high: p-value = 0.009

### Beta diversity analysis on combined dietary antioxidants
<img width="1440" height="884" alt="Screenshot 2026-03-27 at 22 02 47" src="https://github.com/user-attachments/assets/ffd7926b-770e-4b00-a4a8-6d837d1011fc" />

- Combined low vs Combined high: p-value = 0.001
- Combined low vs Combined medium: p-value = 0.172
- Combined medium vs Combined high: p-value = 0.003

