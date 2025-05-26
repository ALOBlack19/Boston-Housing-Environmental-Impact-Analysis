# 🏘️ Boston Housing & Environmental Inequality Analysis

**Student:** Amir Lima Oliveira  
**College:** Cornerstone International Community College of Canada (CICCC)  
**Course:** Applied Statistics / Data Science  
**Project Type:** In-Class Lab – Spearman’s Rank Correlation Test  
**Due Date:** May 26, 2025  

---

## 📘 Project Overview

This project explores **environmental and socioeconomic inequalities** in the Boston Housing dataset by focusing on **NOX (nitric oxide concentration)** as a proxy for air pollution. Using **Spearman’s Rank Correlation**, we evaluate how pollution relates to:

- Housing prices  
- Industrial land use  
- Lower socioeconomic status  
- Crime rates  

The objective is to provide **insights into how urban pollution correlates with social vulnerability and economic degradation** in metropolitan contexts.

---

## 🧪 Statistical Method Used

- **Spearman’s Rank Correlation Coefficient (ρ)**  
Used to measure the strength and direction of monotonic relationships between NOX and selected variables. Implemented with `scipy.stats.spearmanr()`.

---

## 📊 Variables Analyzed

| Pair                  | Meaning / Hypothesis |
|-----------------------|----------------------|
| `NOX` & `MEDV`        | Does air pollution lower housing values? |
| `NOX` & `INDUS`       | Is pollution associated with industrial areas? |
| `NOX` & `LSTAT`       | Is pollution more concentrated among lower-income populations? |
| `NOX` & `CRIM`        | Does pollution correlate with crime and urban decline? |

---

## 🔍 Key Findings

| Variable Pair        | Spearman ρ | P-Value  | Interpretation |
|----------------------|------------|----------|----------------|
| `NOX` & `MEDV`       | -0.5626    | 0.0000   | Moderate negative – higher pollution linked to lower housing prices |
| `NOX` & `INDUS`      |  0.7912    | 0.0000   | Strong positive – industrial areas show higher pollution |
| `NOX` & `LSTAT`      |  0.6368    | 0.0000   | Moderate positive – lower-status populations exposed to more pollution |
| `NOX` & `CRIM`       |  0.8215    | 0.0000   | Strong positive – areas with more pollution also see higher crime |

> ✅ All results are statistically significant at α = 0.05.

---

## 🌎 Environmental Perspective

This project highlights how **environmental conditions reflect social inequalities**. Areas with high NOX levels not only have lower real estate value but also concentrate crime, industry, and marginalized communities. These patterns reveal:

- **Environmental injustice**
- **Urban stressors linked to degradation**
- **Need for urban planning with a social-ecological lens**

---

## 🔮 Future Directions

To deepen this analysis, future versions may incorporate:

- Green space coverage (km²)  
- Proximity to rivers or natural features  
- Cement/asphalt land cover metrics  
- Urban park distribution  
- Industry proximity and zoning layers  

---

## 💾 Dataset Credits

This project uses the **Boston House Prices – Advanced Regression Techniques** dataset:

- 📌 **Source**: [Kaggle - fedesoriano](https://www.kaggle.com/datasets/fedesoriano/the-boston-houseprice-data)  
- 🧑‍🔬 **Publisher**: Federico Soriano  
- 📄 **Original Research**:  
  Harrison, D., & Rubinfeld, D.L. (1978). *Hedonic prices and the demand for clean air*.  
  *Journal of Environmental Economics and Management*, 5(1), 81–102.

> 🔍 This dataset is a modernized version of the classic Boston Housing dataset, tailored for regression and data science tasks.

---

## 🛠️ Tools & Libraries Used

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- SciPy (Spearman’s correlation)  
- Jupyter Notebook / VSCode  

---

## 📁 File Structure

📦 boston-housing-environment-analysis/
├── 📄 README.md
├── 📓 boston_spearman_analysis.ipynb
├── 📊 plots/
│ ├── nox_vs_medv.png
│ ├── nox_vs_indus.png
│ ├── nox_vs_lstat.png
│ ├── nox_vs_crim.png
│ └── spearman_heatmap.png
├── 📁 data/
│ └── boston.csv

---

---

## 📫 Contact

For questions, feedback, or collaborations:

**Amir Lima Oliveira**  
📍 Vancouver, BC  
✉️ https://www.linkedin.com/in/amirloliveira/

---

