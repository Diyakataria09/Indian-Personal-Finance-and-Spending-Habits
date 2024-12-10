# Indian-Personal-Finance-and-Spending-Habits
# Project Overview
This dashboard provides an in-depth analysis of personal finance habits and spending patterns of individuals across India, leveraging financial and demographic data. The visualizations highlight income distribution, savings goals, expenses, and potential savings opportunities segmented by age, city tiers, and family size.

# Key Features
# Interactive Dashboard:
1. Provides a holistic view of personal finance metrics such as income, expenses, savings goals, and disposable income.
2. Offers segmentation across key demographics like age groups, family size, and city tiers.

# Visualizations Included:
1. KPI Cards to summarize total income, expenses, available expenses, and savings goals.
2. Pie and Donut Charts to depict the distribution of city tiers and disposable income proportions.
3. Line Charts to show the relationship between available income and savings percentage across age groups and locations.
4. Stacked and Column Bar Charts for a comparative view of income and expenses across demographics.
5. Additional Insights into dependent groups, showing how family size impacts income and spending.

# Data Insights:
1. Breakdown of income, expenses, and savings potential by location and demographic group.
2. Identification of high-saving and high-spending groups to assist in financial planning.
3. Dataset Description
4. The dataset includes financial and demographic details of 20,000 individuals in India.

# Key Columns:
# Demographics:
1.Age: Age of the individual.
2. City_Tier: Classification of cities (Tier 1, Tier 2, Tier 3).
3. Dependents: Number of dependents (used to classify individuals into family size groups).
# Income and Expenses:
1. Income: Monthly income in currency units.
2. Disposable_Income: Income left after expenses.
3. Expense categories like Groceries, Healthcare, Transport, etc.
# Savings Goals:
1. Desired_Savings: Monthly savings targets.
2. Potential_Savings: Estimated savings across various spending categories.

# Data Preparation
## Steps Taken to Clean and Process the Data:
Removed duplicate and missing values.
Ensured data consistency (e.g., checked for valid ranges in numeric fields like age and income).

# Added calculated columns for better insights:
1. Age_Group: Categorized individuals into groups like Young Adults, Early Career, etc.
2. Dependent_Group: Classified families based on the number of dependents into No Dependents, Small Family, Large Family.

# Created DAX Measures for enhanced metrics:
1.Total_Potential_Savings: Aggregated potential savings across all expense categories.
2.Total_Expenses: Calculated as the difference between income and disposable income.
3. Available_Expenses: Difference between income and savings goals.
# Insights and Observations
# Key Findings:
## Income vs Spending:
1. Tier 1 cities show the highest income and expenses, followed by Tier 2 and Tier 3.
2. Individuals in the Mid-Career age group contribute the largest share of total income and spending.
# Savings Trends:
1. Savings goals are highest among individuals in Tier 1 cities but are met more efficiently by individuals in Tier 2 and Tier 3 cities.
2. Young Adults and Early Career individuals save less due to lower disposable income.
# Family Size Impact:
1. Large Families have significantly higher expenses but lower disposable income compared to Small Families and individuals with no dependents.
# Potential Savings:
High potential savings opportunities in Eating Out and Entertainment categories.
# Visualizations Used
1. KPI Cards:
"Total Monthly Income," "Total Monthly Expenses," "Savings Goals," and "Disposable Income."
# Charts and Graphs:
1. Line Chart:
Tracks "Available Income vs Savings Percentage" segmented by Age Group and City Tier.
2. Stacked Bar Chart:
Compares "Income vs Expenses" across city tiers.
3. Column Chart:
Highlights total expenses by City Tier and Age Group.
Visualizes income distribution by family size (dependent groups).
4. Pie and Donut Charts:
Show the distribution of city tiers and disposable income percentages.

# Usage
1. Open the Power BI file (https://drive.google.com/file/d/1x11uuWR7CAYoqLaWaQp-t_2oJ9Nhye7o/view?usp=sharing) to interact with the dashboard.
2. Use slicers to filter data by City Tier, Age Group, and Dependent Group.
3. Hover over charts to view detailed tooltips for precise insights.
# Future Enhancements
1. Add predictive analytics to forecast income, expenses, and savings trends.
2. Include additional demographic segmentation (e.g., education level, job role).
3. Develop actionable recommendations for financial planning based on insights.
# Conclusion
This dashboard empowers individuals, policymakers, and financial institutions to:
1. Understand spending habits and savings potential across demographics.
2. Identify opportunities to improve financial health and promote savings.
