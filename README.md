# SparkFoundation-GRIPAUG24Task
DATA SCIENCE AND BUSINESS ANALYTICS INTERN - DEBANJANA DASGUPTA

TASK-3

Overview of the EDA Retail Task:

Objective:
The task is aimed to identify weak areas in a retail business where profitability can be improved using Exploratory Data Analysis (EDA). The analysis was performed on the 'SampleSuperstore'[ https://bit.ly/3i4rbWl] dataset to derive insights that could help in making data-driven decisions to enhance business performance.

Steps Followed:

1. Loading and Understanding the Dataset:
   - The dataset was loaded and initially explored to understand its structure and contents.
   - Columns like 'Country' and 'Postal Code' were identified as redundant and dropped to avoid unnecessary complexity.

2. Data Quality Check:
   - Missing values and data inconsistencies were checked and addressed to ensure the dataset was clean and reliable for analysis.

3. Exploratory Data Analysis (EDA):
   - Univariate Analysis:
     - Focused on understanding individual features like transaction types, customer segments, regional performance, and product categories.
   - Bivariate Analysis:
     - Analyzed relationships between two variables, such as the impact of discounts on profit and the performance of different segments and regions.
   - City-wise Analysis:
     - A detailed exploration of profits and losses across different cities and sub-categories, identifying key areas for improvement.

4.  Conclusion Summary:

i. Data Considerations:
   - The dataset is heavily biased towards the United States, so the 'Country' column was dropped.
   - The 'Postal Code' column was dropped due to redundancy with 'Region,' 'City,' and 'State' columns.
   - In the absence of a 'Product' column, the 'Sub-Category' column was used for more detailed analysis.
   - Outliers in 'Sales' and 'Profit' columns were retained as they could represent important events like sales days or discounts.

5.Key Findings:

i. Univariate Analysis:
   - Standard Class Transactions:* Highest frequency, whereas same-day transactions are the lowest.
   - Consumer Segment: Largest segment in terms of transaction count.
   - Regional Performance: The West region had the highest transactions.
   - Category Distribution:* Office supplies had the highest transaction count, with binders leading in the sub-category.

ii. Bivariate Analysis:
   - Discount Impact: Profit decreases with higher discounts, with a significant drop at a 50% discount.
   - Segment Analysis: The Home Office segment, despite high average profits, has fewer transactions, impacting overall profit.
   - State and City Performance:
     - States like Florida and North Carolina are consistently in loss.
     - Cities like Philadelphia and Houston show significant losses in certain sub-categories.

iii. City-wise Profit Exploration:
   - Philadelphia shows substantial losses across multiple sub-categories.
   - Positive profit noted in cities like Santa Clara across several sub-categories.
   - Some cities perform poorly in specific sub-categories, e.g., Houston in Bookcases and Tables.

6. Recommendations:

i. Discount Strategy:
   - Avoid discounts above 23% to prevent losses. Large discounts might harm the perceived quality of products.

ii. Stock Management:
   - Increase stock in cities like Burlington and San Francisco for sub-categories like Bookcases, which are profitable.
   - Reduce stock in areas with consistent losses, such as Philadelphia and Houston.

iii. Product Focus:
   - Increase stock for categories like Copiers, which are performing well.
   - Be cautious with Binders, which have high transaction counts but also high discounts leading to losses.

iv. Geographic Focus:
   - Avoid increasing stock in states that are consistently in loss, like Florida and North Carolina.
   - Explore and address the reasons for the Central region's low profitability.

v. Product Category Strategies:
   - Re-evaluate the discount strategy for the Furniture category, which shows good sales but low profit.
   - Increase focus on the Technology category by boosting transactions since it shows high average profit despite fewer sales.

These conclusions and recommendations should help in optimizing business strategies to enhance profitability, minimize losses, and efficiently manage inventory and discounts across various regions and product categories.

