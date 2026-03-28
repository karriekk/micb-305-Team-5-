## Beta Diversity Analysis using Unweighted UniFrac

### Notes:
1. Because we will be controlling for entacapone in downstream analyses and it contains NA values, they will be removed from the filtered metadata.
   - 10 PD patients are removed because they do not have entacapone intakes recorded.
2. When running beta-diversity analysis, age, sex, and entacapone are accounted for as confounding variables.
3. A sampling depth of 6515 is used when doing the analysis. At this sampling depth, only 14 samples are excluded from the analysis and we have retained 1,192,428 (50.04%) features in 183 (92.89%) samples.

### Beta diversity analysis of Beta Carotene
<img width="1433" height="897" alt="Screenshot 2026-03-27 at 22 15 57" src="https://github.com/user-attachments/assets/bc6bf9b1-9618-4f97-9048-7ed662cfe713" />

- BC low vs BC high: p-value = 0.04
- BC low vs BC medium: p-value = 0.397
- BC medium vs BC high: p-value = 0.028

### Beta diversity analysis of Alpha Carotene
<img width="1434" height="897" alt="Screenshot 2026-03-27 at 22 21 35" src="https://github.com/user-attachments/assets/805e9d73-3e9c-4e50-8f84-5160672ca5a5" />

- AC low vs AC high: p-value = 0.28
- AC low vs AC medium: p-value = 0.195
- AC medium vs AC high: p-value = 0.068

### Beta diversity analysis of Vitamin C
<img width="1437" height="898" alt="Screenshot 2026-03-27 at 22 25 44" src="https://github.com/user-attachments/assets/fec979ee-765b-43b7-b6e7-7aa122f07968" />

- VC low vs VC high: p-value = 0.033
- VC low vs VC medium: p-value = 0.661
- VC medium vs VC high: p-value = 0.017

### Beta diversity analysis of Vitamin A
<img width="1417" height="874" alt="Screenshot 2026-03-27 at 22 37 31" src="https://github.com/user-attachments/assets/608850ff-8668-4d95-b454-49d4e0538d87" />
  
- VA low vs VA high: p-value = 0.116
- VA low vs VA medium: p-value = 0.02
- VA medium vs VA high: p-value = 0.17

### Beta diversity analysis of Vitamin E
<img width="1434" height="900" alt="Screenshot 2026-03-27 at 22 42 01" src="https://github.com/user-attachments/assets/e0c99d16-1d05-41fa-a1bd-dbb81c866779" />

- VE low vs VE high: p-value = 0.001
- VE low vs VE medium: p-value = 0.017
- VE medium vs VE high: p-value = 0.014

### Beta diversity analysis on combined dietary antioxidants
<img width="1439" height="896" alt="Screenshot 2026-03-27 at 22 45 57" src="https://github.com/user-attachments/assets/f2ba67ca-0a56-4fd1-9730-a8b3711a1080" />

- Combined low vs Combined high: p-value = 0.077
- Combined low vs Combined medium: p-value = 0.13
- Combined medium vs Combined high: p-value = 0.046
