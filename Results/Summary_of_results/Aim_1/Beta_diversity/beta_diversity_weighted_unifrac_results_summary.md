## Beta Diversity Analysis using Weighted UniFrac

### Notes:
1. Because we will be controlling for entacapone in downstream analyses and it contains NA values, they will be removed from the filtered metadata.
   - 10 PD patients are removed because they do not have entacapone intakes recorded.
2. When running beta-diversity analysis, age, sex, and entacapone are accounted for as confounding variables.
3. A sampling depth of 6515 is used when doing the analysis. At this sampling depth, only 14 samples are excluded from the analysis and we have retained 1,192,428 (50.04%) features in 183 (92.89%) samples.

### Beta diversity analysis of Beta Carotene
<img width="1431" height="898" alt="Screenshot 2026-03-28 at 06 39 26" src="https://github.com/user-attachments/assets/62a0d67e-ae7a-4da3-b698-04cea79d80df" />

- BC low vs BC high: p-value = 0.082
- BC low vs BC medium: p-value = 0.521
- BC medium vs BC high: p-value = 0.416

### Beta diversity analysis of Alpha Carotene
<img width="1432" height="897" alt="Screenshot 2026-03-28 at 06 44 16" src="https://github.com/user-attachments/assets/58a181ff-7ffb-4626-a21b-6090d3a0f5e8" />

- AC low vs AC high: p-value = 0.299
- AC low vs AC medium: p-value = 0.177
- AC medium vs AC high: p-value = 0.321

### Beta diversity analysis of Vitamin C
<img width="1432" height="894" alt="Screenshot 2026-03-28 at 06 48 14" src="https://github.com/user-attachments/assets/696879f0-93c7-4a19-a146-c8f96bed1db0" />

- VC low vs VC high: p-value = 0.455
- VC low vs VC medium: p-value = 0.694
- VC medium vs VC high: p-value = 0.184

### Beta diversity analysis of Vitamin A
<img width="1436" height="893" alt="Screenshot 2026-03-28 at 06 51 25" src="https://github.com/user-attachments/assets/7be970ba-537a-445e-9662-15c9cec64cf0" />

- VA low vs VA high: p-value = 0.275
- VA low vs VA medium: p-value = 0.421
- VA medium vs VA high: p-value = 0.539

### Beta diversity analysis of Vitamin E
<img width="1436" height="887" alt="Screenshot 2026-03-28 at 06 56 09" src="https://github.com/user-attachments/assets/cb49aa1c-e818-4a95-ba14-a055e920156f" />

- VE low vs VE high: p-value = 0.204
- VE low vs VE medium: p-value = 0.235
- VE medium vs VE high: p-value = 0.478

### Beta diversity analysis on combined dietary antioxidants
<img width="1439" height="900" alt="Screenshot 2026-03-28 at 06 58 46" src="https://github.com/user-attachments/assets/09f4e805-add0-4354-8208-309c49e71db0" />

- Combined low vs Combined high: p-value = 0.32
- Combined low vs Combined medium: p-value = 0.542
- Combined medium vs Combined high: p-value = 0.183
