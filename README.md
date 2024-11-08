## Bike-Sales-Analysis
Customer Demographics and Purchase Behavior Analysis for Bike Sales

### Dataset Introduction
The dataset used in this project contains information on potential bike buyers across various regions in the U.S. It includes demographic details, financial status, commuting habits, and purchasing behavior related to bike ownership. Each row represents an individual with characteristics such as marital status, gender, income, education, occupation, home ownership, commute distance, region, age, and whether or not they purchased a bike.
The dataset contains 1,026 rows and 13 columns.

#### Project Overview
The goal of this project is to analyze bike purchasing behavior based on customer demographics and other attributes. By exploring the data, this project aims to identify trends, patterns, and insights that can inform business strategies and improve customer targeting for bike sales.


#### The analysis includes:

Data Cleaning: Ensuring data consistency and completeness.
Pivot Tables: Summarizing data to explore relationships between attributes and bike purchasing behavior.
Dashboard Creation: Visualizing key insights through charts and interactive filters to facilitate data-driven decision-making.
Generated Questions and Answers

#### Here are some key questions this project aims to address:

1. Does income influence bike purchasing behavior?
- Yes, higher-income individuals appear more likely to purchase bikes.
2. Is there a difference in bike purchasing based on gender?
- Males show slightly higher bike purchase rates compared to females.
3. How does commute distance affect bike purchasing?
- People with shorter commutes are more likely to purchase bikes.
4. Does marital status impact bike buying?
- Married individuals are more likely to purchase bikes than single individuals.

#### Handling Missing Values: 
I Checked for missing values in key columns and imputed or removed them as necessary.

#### Data Consistency: 
I Standardized categorical values, ensuring uniformity in fields like "Marital Status," "Commute Distance," and "Region."

#### Outlier Removal: 
I Identified and addressed outliers, particularly in fields like "Income" and "Age," to prevent skewed analysis.

- Here are some of the key questions identified in this bike sales dataset, along with the answers derived from the analysis:

1. Does Income Level Influence Bike Purchasing Behavior?
- Answer: Yes, income level appears to influence bike purchasing behavior. Individuals with higher incomes are more likely to purchase bikes. Specifically, females who purchased bikes had an average income of $40,000, while males who purchased had an average income of $35,294. This indicates that income may play a role, with a trend of higher-income individuals being more inclined to purchase bikes.

2. Is There a Difference in Bike Purchasing Between Genders?
- Answer: Males have a slightly higher purchase rate compared to females. However, both genders show similar tendencies when income levels are higher. Gender alone is not a strong predictor of bike purchasing behavior without considering other factors such as income and commute distance.

3. Does Marital Status Impact Bike Purchasing?
- Answer: Yes, marital status seems to have an impact. Married individuals show a higher likelihood of purchasing bikes compared to single individuals. This trend remains consistent across various income levels, suggesting that married individuals may have a stronger preference for or need for bikes, potentially due to shared income or family-related lifestyle choices.

4. How Does Commute Distance Affect Bike Purchasing?
- Answer: Commute distance has a significant influence on bike purchasing. People with shorter commute distances (0–1 miles) are the most likely to purchase bikes. As the commute distance increases, the likelihood of bike purchase decreases. This suggests that individuals with shorter commutes may view bikes as a convenient and economical option for transportation.

5. What Role Does Age Play in Bike Purchasing Decisions?
- Answer: Middle-aged individuals (30–45 years old) are more likely to purchase bikes compared to younger or older individuals. Older age groups show a decline in bike purchasing rates. This could indicate that middle-aged individuals are more interested in fitness, environmental benefits, or alternative commuting options that bikes provide.

6. Are There Regional Differences in Bike Purchasing Trends?
- Answer: Yes, there are regional differences. Individuals from urban or metropolitan regions are more likely to purchase bikes, possibly due to better infrastructure, shorter commute distances, or cultural factors that favor biking. This suggests that bike companies may want to focus their marketing efforts more heavily in urban areas where demand is higher.

7. Does Educational Background Influence the Decision to Purchase a Bike?
- Answer: Yes, individuals with higher educational backgrounds (such as bachelor’s degrees or graduate degrees) tend to purchase bikes more frequently than those with only high school or partial college education. This could be related to increased awareness of health and environmental benefits, or greater financial stability among those with higher education, influencing their purchasing behavior.

8. Are Certain Customer Occupations More Likely to Purchase Bikes?
- Answer: While not directly analyzed in the initial pivot tables, examining occupation could reveal that individuals in certain occupations (e.g., professional roles) may be more inclined to purchase bikes. Further analysis could uncover if professionals, clerical workers, or skilled manual workers exhibit different purchasing behaviors based on their job demands or commuting needs.

#### The pivot tables provide insights such as:

- Average Income per Purchase: Displays the average income of bike purchasers versus non-purchasers, segmented by gender.
Count of Purchased Bike by Commute Distance: Shows the distribution of bike purchases based on commute distance, indicating that individuals with shorter commute distances are more likely to buy bikes.
Dashboard Analysis
The dashboard consolidates key visualizations, including:

- Average Income per Purchase: Compares income by gender and bike purchasing status.
Customer Age Bracket: Highlights the age distribution among purchasers and non-purchasers.
Customer Commute: Visualizes bike purchasing trends across different commute distances.
Data Cleaning Process
To ensure data quality, the following steps were taken:


