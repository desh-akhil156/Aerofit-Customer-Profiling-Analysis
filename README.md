# Aerofit Customer Profiling & Probability Analysis

An exploratory data analysis (EDA) and probability study evaluating Aerofit's treadmill customer data to understand buyer demographics, product positioning, and conditional probabilities for targeted marketing.

---

## 📊 Project Overview
Aerofit offers a diverse range of treadmills (KP281, KP481, and KP781) catering to different fitness levels and budgets. This project analyzes customer characteristics—including age, gender, education, marital status, income, usage, fitness levels, and expected weekly mileage—to create accurate customer profiles for each treadmill model. 

The primary objective is to use descriptive statistics and conditional probabilities to uncover patterns in customer preferences and provide data-driven product recommendations for sales and marketing.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Manipulation & Cleaning:** Pandas, NumPy
* **Statistical Analysis:** SciPy (Probability metrics)
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Google Colab

---

## 🔍 Key Analysis Steps
1. **Data Inspection & Metrics:** 
   * Checked data shapes, data types, and converted categorical variables (like `Gender`, `MaritalStatus`, and `Product`) into appropriate categories.
   * Generated comprehensive statistical summaries to understand central tendencies and spreads.
2. **Non-Graphical Analysis:**
   * Examined value counts, unique attribute frequencies, and baseline distributions across all features.
3. **Visual Analysis (Univariate, Bivariate & Correlation):**
   * **Univariate:** Plotted histograms, count plots, and distplots for continuous variables (Age, Income, Miles, Usage) and categorical variables.
   * **Bivariate & Outlier Detection:** Used box plots to detect outliers and evaluate relationships between customer characteristics and product choices.
   * **Correlation:** Generated heatmaps and pair plots to check multicollinearity and relationships among factors like income, fitness score, and expected mileage.
4. **Probability Analysis:**
   * Constructed two-way contingency tables (using Pandas cross-tabulation) to compute marginal and conditional probabilities (e.g., probability of a customer buying the high-end KP781 model given specific income or fitness tiers).

---

## 💡 Key Business Insights
* **Model KP281 (Entry-Level):** Purchased predominantly by casual, lower-to-middle income customers with moderate fitness levels and average weekly usage expectations.
* **Model KP481 (Mid-Level):** Appealing to a broad, balanced demographic with moderate income and steady usage patterns, serving as a reliable middle-tier option.
* **Model KP781 (Advanced):** Highly correlated with higher income brackets, higher self-rated fitness scores, and greater expected weekly mileage, skewing predominantly male.

---

## 🚀 Strategic Recommendations
* **Targeted Marketing Campaigns:** Direct premium digital ads for the high-end KP781 treadmill toward high-income demographics and individuals with self-rated fitness scores of 4 or 5.
* **In-Store Upselling:** Use customer income and expected usage intake questionnaires at retail touchpoints to guide entry-level buyers toward the KP281 or KP481 models effectively.
* **Inventory Optimization:** Align regional stock levels with local income distributions and fitness trends identified via demographic probability cross-tabs.

---
