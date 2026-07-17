# Analysis ConnectaTel
As Data Analyst, this project evaluates customer behavior for ConnectaTel, a Latin American telecommunications company, using data recorded through 2024.

## 📝Project Overview

As Data Analyst, this project evaluates customer behavior for ConnectaTel, a Latin American telecommunications company, using data recorded through 2024.
Analyze customer mobile usage (calls/texts) at ConnectaTel (Mexico/Colombia). Using three data sources, I identified usage patterns and customer segments to optimize our commercial offers and improve user experience.

The analysis draws on three datasets:

* **plans.csv** — current plan details (price, included minutes, included GB, overage costs)
* **users.csv** — customer information (age, city, registration date, plan, churn)
* **usage.csv** — actual service usage (calls and messages)

The work encompasses data exploration, cleaning, and analysis to build a statistical customer profile, identify outlier behavior, and develop customer segments. These insights support the identification of consumption patterns, the design of retention strategies, and recommendations for plan optimization.

## Analysis Stages

**1. Data Loading & Exploration**
Loaded and explored the `plans`, `users_latam`, and `usage` datasets to understand their structure and column types. → *Provided a clear baseline of each dataset before analysis.*

**2. Data Quality Assessment**
Counted null values, detected sentinel placeholders, and reviewed out-of-range dates. → *Produced a prioritized list of data issues that could bias business decisions.*

**3. Data Cleaning**
Replaced sentinel values, converted date formats, and imputed or flagged missing values according to defined rules. → *Delivered a consistent, analysis-ready dataset.*

**4. Summary Statistics**
Reviewed key measures across categorical and numerical variables. → *Surfaced core metrics (mean, median, percentiles) reflecting typical and extreme customer behavior.*

**5. Visualization & Outlier Detection**
Built histograms and boxplots to inspect distributions. → *Revealed skew, usage patterns, and atypical data points.*

**6. Segmentation**
Created rule-based customer segments and visualized proportions with countplots. → *Generated actionable segments to guide offers, campaigns, and plan migrations.*

**7. Executive Insights**
Drafted conclusions and business recommendations based on the previous steps. → *Answered key business questions and proposed concrete next steps.*

## 📂 Repository Contents

- `S7Project-ConnectaTel.ipynb`
  → Main notebook covering data cleaning, EDA, distributions, outliers, and conclusions.

## ▶ Opening the Notebook in Google Colab

Click the button below:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/reyesc1710/Telecom-Analysis/blob/main/S7Project_ConnectaTel.ipynb)
Or:

1. Open the `.ipynb` file on GitHub
2. Click **Open in Colab**

## 📘 Reproducing the Analysis

1. Open `S7Project-ConnectaTel.ipynb`
2. Run the cells in order
3. The notebook automatically loads the dataset from `/data/` or from a public link, as applicable
