# Psycholinguistic-EDA
# Exploratory Data Analysis: Psycholinguistic Word Ratings
**An investigation into Age-of-Acquisition (AoA), Word Frequency, and Emotional Dimensions.**

## 📌 Project Overview
This project conducts a comprehensive Exploratory Data Analysis (EDA) on two primary psycholinguistic datasets: **Kuperman et al. (Age-of-Acquisition)** and **Warriner et al. (Valence, Arousal, Dominance)**. 

The analysis aims to uncover the hidden relationships between when humans learn words and how those words are perceived emotionally and used in contemporary language (SUBTLEX-US corpus).

## 📊 Key Analytical Workflows
* **Data Cleaning & Standardization:** Handled missing values (NaN) and specialized identifiers like the "Dunno" ratio. Managed domain-specific sparsity in the SUBTLEX-US corpus.
* **Feature Engineering:** Implemented **Logarithmic Transformations** on word frequency to manage skewed distributions, aligning with Zipf's Law.
* **Statistical Insights:** - Performed **Correlation Analysis** between AoA and Rating Variance (SD).
    - Conducted **ANOVA** to test frequency differences across various human lifespan stages.
* **Data Visualization:** Built advanced visualizations including density plots, regression facets by word length, and correlation heatmaps to facilitate intuitive data storytelling.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Plotly`, `Scipy`, `Statsmodels`
* **Workflow:** Jupyter Notebook for interactive analysis and documentation.

## 📈 Key Findings Preview
- **Frequency Effect:** Confirmed a strong negative correlation between word frequency and Age-of-Acquisition; frequently used words are acquired significantly earlier.
- **Reliability:** Analyzed raters' consensus, identifying that early-acquired words generally show higher rating stability among participants.
- **Domain Specificity:** Identified that words missing from subtitle-based corpora often have much higher AoA, suggesting they belong to more specialized or formal registers.

## 📂 File Structure
- `Scripting_Final_Project_r1077191.ipynb`: Full analytical pipeline with code and markdown commentary.
- `data/`: Contains raw CSV datasets (AoA ratings and Warriner et al. ratings).
- `visualizations/`: (Optional) Exported PNG images of key charts.


**Author:** Liangyu Gan  
