# Wine Quality — Exploratory Data Analysis (EDA)

Exploratory Data Analysis of the UCI Wine Quality dataset (Cortez et al., 2009), examining 1,599 red and 4,898 white Portuguese *Vinho Verde* wine samples across 11 physicochemical measurements and sensory quality ratings (0–10 scale).

## Repository Contents
* `Wine_Quality_EDA.ipynb` — Complete Jupyter Notebook containing data preprocessing, univariate/bivariate visualizations, correlation matrices, outlier detection, and statistical hypothesis tests (Questions 1–35).
* `Wine_Quality_EDA_Report.pdf` — Exported project documentation covering approach, implementation, and analytical outcomes.

## Key Findings
1. **Chemical Differentiation:** Red and white wines differ significantly (p < 0.0001) across all 11 physicochemical features; white wines carry higher residual sugar and sulfur dioxide, while red wines contain higher fixed/volatile acidity and chlorides.
2. **Population Mixing:** Combining red and white samples masks within-group relationships (e.g., fixed acidity vs. pH drops from r = -0.68 in red wine to r = -0.25 combined), requiring stratified analysis.
3. **Sensory Quality Drivers:** Higher alcohol (r = 0.44) and lower volatile acidity (r = -0.27) are the strongest single correlates of sensory quality, while combining alcohol, volatile acidity, and sulphates improves explanatory power (R = 0.52).

## Tools Used
Python 3, Pandas, NumPy, Matplotlib, Seaborn, SciPy.
