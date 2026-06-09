# 🌍 World Happiness Report 2015 — Probability & Statistics Term Project

**Course:** Probability & Statistics (007330) — Sejong University  
**Dataset:** [World Happiness Report 2015](https://www.kaggle.com/datasets/unsdsn/world-happiness)

---

## 📌 Project Overview

This project applies core **Probability and Statistics** concepts to the 2015 World Happiness Report dataset, which contains happiness scores and related indicators for 158 countries.

The main goal is to analyze what factors influence a country's **Happiness Score**, with a focus on **Economy (GDP per Capita)** as the strongest predictor (r = 0.78).

---

## 📁 Repository Structure

```
📦 world-happiness-stats-project
 ┣ 📓 World_Happiness_Term_Project.ipynb   ← Main analysis notebook
 ┣ 📊 2015.csv                             ← Dataset (158 countries)
 ┣ 📑 term_project_presentation.pptx       ← Slide deck presentation
 ┗ 📄 README.md                            ← You are here
```

---

## 📊 Dataset Description

| Column | Description |
|---|---|
| `Country` | Country name |
| `Region` | Geographic region |
| `Happiness Score` | Overall happiness index (target variable) |
| `Economy (GDP per Capita)` | Economic output per person |
| `Family` | Social support score |
| `Health (Life Expectancy)` | Average life expectancy index |
| `Freedom` | Freedom to make life choices |
| `Trust (Government Corruption)` | Perception of government corruption |
| `Generosity` | Generosity score |
| `Dystopia Residual` | Baseline comparison score |

---

## 🔬 Topics Covered

The notebook is structured as 12 steps:

1. **Data Loading & Preprocessing** — Load CSV, handle missing values
2. **Descriptive Statistics** — Mean, median, std, min, max
3. **Outlier Detection** — IQR method with before/after boxplots
4. **Histogram + Normal PDF Overlay** — Distribution shape & skewness
5. **Empirical CDF** — Cumulative probability visualization
6. **Empirical Probability** — P(Happiness Score > threshold)
7. **Conditional Probability** — Joint 2D distribution analysis
8. **Sampling** — Random sampling techniques
9. **Confidence Intervals** — 95% CI for the mean Happiness Score
10. **Hypothesis Testing** — t-test on Happiness Score
11. **Correlation Analysis** — Pearson r between all variables
12. **Linear Regression** — Predicting Happiness Score from GDP per Capita

---

## ▶️ How to Run

1. **Clone this repository:**
   ```bash
   git clone https://github.com/omarfaruk07/world-happiness-stats-project.git
   cd world-happiness-stats-project
   ```

2. **Install required libraries:**
   ```bash
   pip install numpy pandas matplotlib scipy
   ```

3. **Open the notebook:**
   ```bash
   jupyter notebook World_Happiness_Term_Project.ipynb
   ```

4. Make sure `2015.csv` is in the **same folder** as the notebook. ✅

---

## 🛠️ Libraries Used

- `numpy` — Numerical calculations
- `pandas` — Data loading and manipulation
- `matplotlib` — Plotting and visualization
- `scipy` — Statistics (t-tests, PDF, confidence intervals)

---

## 📈 Key Findings

- **GDP per Capita** is the strongest predictor of happiness (r = 0.78)
- Countries in **Western Europe** consistently rank highest
- The distribution of Happiness Scores is approximately **normal** with slight left skew
- Linear regression confirms a statistically significant positive relationship between GDP and happiness

---

## 👤 Author

**Omar**  
Sejong University — Probability & Statistics (007330)
