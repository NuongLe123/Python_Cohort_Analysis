# Python_Cohort_Analysis
Use Python to analyze transaction data from KPMG and evaluate user engagement from their first transaction

## I. Introduction
### 1. Cohort Analysis
### What is cohort and cohort analysis?
- **A cohort** is a group of users who share a common characteristic, and cohort analysis is a tool to measure their engagement over time.
- **Cohort analysis** helps to differentiate between actual improvements in user engagement and those that may be driven by growth, while vanity indicators do not provide the same level of insight.
### Three major types of Cohort
- **Time cohorts**: customers who signed up for a product or service during a particular time frame.
- **Behavior cohorts**: customers who purchased a product or subscribed to a service in the past.
- **Size cohorts**: refer to the various sizes of customers who purchase the company’s products or services.
### Which type of cohort is for this project?
- I will focus on performing Cohort Analysis based on **Time cohorts**.
- Customers will be divided into acquisition cohorts depending on the month of their first purchase.
- The cohort index would then be assigned to each of the customer’s purchases, which will represent the number of months since the first transaction.
### 2. Business Questions
Using Python to analyze transaction data from KPMG and creating a cohort that allows stakeholders, to assess user engagement starting from their first transaction.

## II. Data Visualization with Python

<img width="744" alt="Screenshot_1" src="https://github.com/NuongLe123/RFM_analysis/assets/168357450/8e32aad8-a09c-42d4-90cd-947791b47df5">

## III. Insights
### Insights from the heatmap above:
- It is concluded that customers who start ordering from mid-year 4,5,6,7,8 tend to order stable, and these retention rates are relatively higher than the rest months of the year. Specifically: Customers who register and place their first order in July 2017 have a high retention rate (up to 48.1%) after 5 months of operation. Customers who register and place their first order in April 2017 have a stable and relatively high retention rate: 45.1% (4th month), 42.1% (5th month), and 42.7% (7th month).
- Customers who place orders from January to March only show stability (about 33% to 43%).
### Recommendations
- Overall, KPMG did a good job of maintaining stable retention rates over the user's lifetime. There should be attractive preferential policies for customers in the first months of the year to increase the order rate (retention) over the months.
- Since Mid-year months have higher retention rates than other month, we need to find out the reasons as well as the characteristics of these groups in order) to apply to other months of the year.
