# Strava Run Analysis

This project analyzes running performance data collected from Strava using statistical and mathematical techniques.

## Dataset
The dataset (`filtered_runs.xlsx`) contains recorded runs including:
- Date
- Distance
- Time
- Calculated average speed

## Analysis
Key statistical techniques used:
- Descriptive statistics (mean, median, IQR)
- Boxplots and trend lines
- Correlation analysis
- Outlier detection using IQR
- Hypothesis testing (Welch’s t-test)

## Notebook
The full analysis is available in [`Strava_Final_Report.ipynb`](notebooks/Strava_Final_Report.ipynb), which walks through:
- Speed progression by year and month
- Speed distributions
- Endurance vs. speed tradeoff
- Statistically significant improvements across training blocks

## References
See the final section of the notebook for academic references behind each formula and method used.

## ▶How to Run
1. Clone the repository  
2. Open the Jupyter notebook from the `notebooks/` folder  
3. Make sure you have `pandas`, `matplotlib`, `scipy`, and `seaborn` installed  
4. Execute cells to reproduce the analysis

---
