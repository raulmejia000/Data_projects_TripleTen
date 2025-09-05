Statistical Analysis of Megaline Prepaid Plans 

[Sprint 3 – Statistical Data Analysis (Megaline Plans)](https://github.com/raulmejia000/Data_projects_TripleTen/blob/main/Statistical%20Analysis%20of%20Megaline%20Prepaid%20Plans%20Project/Sprint%203%20Statistical%20Data%20Analysis%20Project.ipynb)

Introduction

In this project, I worked as a data analyst for the telecom company Megaline, which offers two prepaid plans: Surf and Ultimate. The business goal was to determine which plan generates more revenue so that the commercial department could make informed decisions about advertising budgets. By analyzing customer usage data, I aimed to uncover behavioral patterns and revenue differences between the two plans.

What Was Done

Data Preparation:
- Loaded datasets containing information on users, calls, text messages, internet usage, and plan details.
- Cleaned the data by converting columns to the correct data types and addressing inconsistencies.
- Aggregated customer behavior per month (calls, minutes, texts, and internet usage).

Feature Engineering:
- Calculated monthly revenue for each user by accounting for included plan limits and additional usage costs.
- Created distributions for calls, messages, and data usage across both plans.

Statistical Analysis:
- Calculated descriptive statistics (mean, variance, standard deviation) for usage and revenue.
- Plotted histograms and boxplots to visualize customer behavior differences.
- Formulated and tested hypotheses:
  1. The average revenue of Ultimate users differs from that of Surf users.
  2.The average revenue of users in the NY–NJ area differs from that of users in other regions.

Tools & Libraries used:
Python, pandas, numpy, matplotlib, seaborn, scipy.

Project Features (Screenshots)

Here are some visual examples from the analysis:


Distribution of data usage among Surf and Ultimate users.


Boxplot comparing monthly revenue between Surf and Ultimate plans.

Results & Conclusion
- Surf users tend to exceed their plan limits more often, leading to higher additional charges.
- Ultimate users pay a higher fixed monthly fee but rarely exceed their allowances.
- The average revenue between Surf and Ultimate users is significantly different, confirming the first hypothesis.
- No significant revenue difference was found between the NY–NJ area and other regions, rejecting the second hypothesis.
- Overall, while the Ultimate plan provides stability, the Surf plan can sometimes generate more revenue when customers exceed usage limits.

Improvements & Business Suggestions

Improvements: Future analysis could use larger datasets or more recent customer data for better accuracy. Additional factors like customer churn or satisfaction scores could be integrated.

Business Outcomes:
- Megaline could increase profitability by promoting the Surf plan to heavy users who frequently exceed their limits.
- Alternatively, targeted advertising could be used to upsell the Ultimate plan to customers seeking predictable monthly bills.
- Regional marketing strategies should focus on usage behavior rather than geography since no significant regional differences were found.
