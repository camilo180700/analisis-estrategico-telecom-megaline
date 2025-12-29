# 📈 Strategic Analysis of Telecom Plan Profitability (Megaline)

## 📌 Business Context and Problem
Working as a data analyst for the telecommunications provider Megaline, the goal of this project was to determine **which of its two prepaid plans, Surf or Ultimate, generates higher average revenue**, in order to optimize the company’s advertising strategy.

The analysis is based on a sample of 500 customers during the year 2018.

## 🎯 Key Objectives of the Analysis

1. **Data Preprocessing:** Apply strict business rules (e.g., rounding up call durations and data usage) and consolidate each user’s monthly activity (calls, messages, and internet usage).
2. **Revenue Metric:** Develop a function to calculate total monthly revenue per user, considering the fixed monthly fee and **overage charges** for each plan.
3. **Usage Analysis:** Calculate and visualize the mean, variance, and standard deviation of usage (minutes, SMS, and GB) for each plan.
4. **Hypothesis Testing:**
   * Evaluate whether there is a **statistically significant difference** in average revenue between users of the Surf and Ultimate plans.
   * Evaluate whether the average revenue of users in the **New York–New Jersey** area differs from that of users in other regions.

## 💡 Strategic Insights (Portfolio-Ready)

| Metric | Surf Plan | Ultimate Plan | Business Impact |
| :--- | :--- | :--- | :--- |
| **Average Monthly Revenue** | **[Surf Average Revenue]** | **[Ultimate Average Revenue]** | **The Ultimate plan generates significantly higher average revenue.** *You should replace this placeholder with the actual value obtained in your analysis.* |
| **Revenue Variance** | **High** | **Low** | The high variance of **Surf** indicates that a portion of its users generates substantial additional revenue by exceeding plan limits, mainly due to **excessive data usage (GB)**. The Ultimate plan provides a more predictable cash flow. |
| **Average Minutes Usage** | Close to its limit (500) | Well below its limit (3000) | Surf users operate closer to their usage limits, confirming higher exposure to *overage* charges. |

### Hypothesis Test Results:
* **Most Profitable Plan:** Statistical analysis (t-test) confirms that **the average revenue of the Ultimate plan is higher**, and the difference is statistically significant.
* **Regional Impact:** No statistically significant evidence was found to suggest that geographic location (NY/NJ vs. other regions) impacts average customer revenue.

## 🛠️ Technologies
* `Python`
* `Pandas` (Data manipulation and aggregation)
* `NumPy` (Numerical computations, especially rounding up)
* `SciPy.stats` (T-test hypothesis testing)
* `Matplotlib` & `Seaborn` (Distribution visualization)

