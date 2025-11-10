# Diabetes-Data-EDA

This project explores blood glucose trends and variability across 70 diabetic patients using real-world time-series data.  
Through data cleaning, visualization, and statistical exploration, this notebook uncovers meaningful insights into patient-level glucose behavior and highlights potential patterns relevant for medical and data science research.

---

##  Project Overview
The dataset contains longitudinal glucose measurements for multiple patients.  
The objective of this analysis was to:
- Understand the structure and quality of the raw diabetes data.
- Explore individual and aggregate glucose trends over time.
- Identify variability, potential anomalies, and long-term stability patterns.
- Build a foundation for predictive or anomaly-detection models.

---

##  Key Steps Performed
1. **Data Inspection & Cleaning**
   - Handled missing, duplicated, and irregular time entries.
   - Standardized timestamp formats and normalized glucose units.
2. **Feature Engineering**
   - Derived rolling averages and smoothed trends to analyze glucose stability.
   - Computed per-patient descriptive statistics.
3. **Visualization & Interpretation**
   - Created time-series plots for each patient’s glucose pattern.
   - Compared raw vs. rolling mean glucose trajectories.
   - Highlighted variability across patients and time segments.
4. **Insights**
   - Visualized intra- and inter-patient glucose dynamics.
   - Observed recurring temporal patterns (e.g., morning spikes).
   - Identified patients with consistently stable or erratic glucose levels.

---

##  Tools & Libraries
- **Python**, **Jupyter Notebook**
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `datetime`, `warnings`

---

##  Results & Learnings
- Revealed glucose fluctuation behaviors and smoothed temporal trends.
- Gained hands-on experience with real-world messy biomedical data.
- Built visual narratives that make patient-level variability intuitive.

---

##  Next Steps
- Develop predictive models for glucose forecasting.
- Correlate glucose levels with other biometric or lifestyle factors.
- Extend the analysis to anomaly detection and patient clustering.

