# Strava Run Analysis

This project analyzes running performance data collected from Strava using statistical and mathematical techniques.

It aims to evaluate whether performance has improved over time, identify trends, and apply hypothesis testing to validate training effects.


## Dataset

- File: `filtered_runs.xlsx`
- Fields include: Date, Distance, Duration, Calculated Average Speed

## Analysis Highlights

- Descriptive statistics (mean, median, standard deviation)
- Boxplots and distribution analysis
- Speed trends over time
- Outlier detection using IQR
- Pearson correlation (distance vs speed)
- Welch's t-test (2023 vs 2024 comparison)

## Notebook

The complete analysis is in [`notebooks/Strava_Final_Report.ipynb`](notebooks/Strava_Final_Report.ipynb)

## References
See the final section of the notebook for academic references behind each formula and method used.

## ▶How to Run
1. Clone the repository  
2. Open the Jupyter notebook from the `notebooks/` folder  
3. Make sure you have `pandas`, `matplotlib`, `scipy`, and `seaborn` installed  
4. Execute cells to reproduce the analysis

---
