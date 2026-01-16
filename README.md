# **Instagram Usage & Lifestyle Patterns Analysis**

*Description:*
This project analyzes a large Instagram usage dataset (\~1.55M users) to explore patterns in **daily activity, lifestyle behaviors, and network characteristics**. You can find the dataset on [Kaggle](https://www.kaggle.com/datasets/rockyt07/social-media-user-analysis)

- - -

# 1\. Project Objective

The goal of this project is to perform a **descriptive exploratory data analysis (EDA)** to understand:

* User demographics and geographic distribution
* Daily Instagram usage patterns and categorization
* Lifestyle behaviors (sleep, exercise, steps) across usage levels
* Network characteristics (followers/following trends by account age)
* Income distribution across urban and rural users

The analysis focuses on **distributional patterns, group comparisons, and compositional insights**, without attempting causal inference.

- - -

# 2\. Questions Asked in the Notebook & Their Answers

* **Question 1:** How is daily Instagram usage distributed?
**Answer:** Usage follows a single-peaked distribution; users were categorized into Short, Medium, and Long using 25th and 75th percentiles.
* **Question 2:** Do lifestyle metrics differ by usage category?
**Answer:** Boxplots show medians are very similar across groups, with substantial overlap in interquartile ranges, suggesting minimal differences.
* **Question 3:** Does account age predict network size?
**Answer:** Average followers and followings vary mildly by account creation year; account age alone does not strongly explain network size.
* **Question 4:** How does income differ between urban and rural users?
**Answer:** Within-group percentages show users across all income levels in both groups, with compositional differences but no extreme separation.

- - -

# 3\. Key Findings

* Many variables have **narrow, controlled distributions**, possibly standardized.
* **Group comparisons** (usage intensity, urban/rural) reveal compositional differences but **not large separations** in medians.
* **Lifestyle metrics** appear largely similar across usage groups.
* **Percentile-based categorization** and **within-group normalization** ensure fair comparisons and accurate visualization.

- - -

# 4\. Notebook Structure

1. **Data Loading & Overview** – Inspect dataset, check distributions.
2. **Daily Instagram Usage Analysis** – Categorize usage, plot histograms.
3. **Lifestyle Metrics Analysis** – Compare steps, exercise, sleep across usage groups.
4. **Network Size Analysis** – Followers/following trends by account creation year.
5. **Income Analysis** – Urban vs rural distribution of income levels.
6. **Summary & Conclusion** – Key insights, data restraints, and overall observations.

- - -

# 5\. How to Run

1. Clone the repository.
2. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/rockyt07/social-media-user-analysis)
3. Ensure all dependencies are installed: `pandas`, `numpy`, `matplotlib`, `seaborn`.
4. Open the notebook `Instagram_analysis.ipynb` in Jupyter Notebook or VS Code.
5. Execute cells sequentially to reproduce the analysis and visualizations.