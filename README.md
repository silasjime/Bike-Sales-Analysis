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


#### Interpretation of the Pivot Table Calculations

Average Income by Gender and Purchase Status

- Objective: To find the average income of individuals segmented by gender and whether they purchased a bike or not.
Structure: The pivot table displays the average income for each gender (Male, Female) based on whether they purchased a bike.

Findings:

- Female:
Non-purchasers: Average income is $39,375.
Purchasers: Average income is $40,000.

- Male:
Non-purchasers: Average income is $40,000.
Purchasers: Average income is $35,294.

- Interpretation: This indicates that for both genders, income levels vary slightly with bike purchasing decisions, though higher income does not always guarantee a purchase.
Count of Bike Purchases by Commute Distance

- Objective: To show how bike purchases vary across different commute distances.
- Structure: The pivot table displays the count of bike purchases (Yes/No) for commute distances segmented into ranges (0–1 miles, 1–2 miles, 2–5 miles, and more than 10 miles).

- Findings:
Shorter commute distances (0–1 miles) have the highest count of bike purchases.
As commute distance increases, the count of purchases declines.
Interpretation: This suggests that shorter commutes are more conducive to bike purchasing, likely because biking is more feasible for shorter distances.

- Dashboard Visualization Analysis
The dashboard in your screenshots provides a quick visual summary of several aspects of the dataset:

- Avg Income per Purchase (Bar Chart)

- Description: This bar chart shows the average income of individuals by gender and bike purchasing status (Yes/No).

Insight: It highlights that, generally, income and purchasing behavior show subtle differences across gender, which can inform targeted marketing efforts based on gender and income.

- Customer Age Bracket (Line Chart)

- Description: This line chart shows the count of bike purchases across different age brackets, with separate lines for purchasers (Yes) and non-purchasers (No).

- Insight: Middle-aged customers have the highest purchase count, suggesting that this age group is a significant target audience for bike sales.
Customer Commute (Line Chart)

- Description: This line chart displays bike purchasing behavior by commute distance, showing purchase counts for each distance range.

- Insight: There is a strong preference for bike purchases among individuals with shorter commute distances (0–1 miles), confirming that bikes are a popular mode of transport for short distances.

- Summary
The dashboard effectively uses visual elements to communicate insights from the pivot tables, allowing for easy analysis of key factors like income, gender, age, and commute distance in relation to bike purchasing behavior. This layout supports strategic decision-making for targeting specific customer segments based on demographic and lifestyle factors.


![Screenshot (437)](https://github.com/user-attachments/assets/44c8ddff-ad64-43b1-8975-b16b093106ed)
![Screenshot (436)](https://github.com/user-attachments/assets/f88af8fd-f0e4-47c6-bc2a-a68619f7ba10)
![Screenshot (435)](https://github.com/user-attachments/assets/bc5304f3-7848-479b-8dd2-4939d771fa40)



- Based on the analysis of this bike sales dataset, here are some actionable recommendations i thought to help the company boost their business:
- Base on my pwersonal recommwndation

1. Target High-Income Segments for Premium Bike Models
Insight: The analysis shows that customers with higher incomes are more likely to purchase bikes, especially in the female demographic.
Recommendation: Introduce or emphasize premium models with enhanced features for high-income segments. Use targeted marketing that highlights quality, durability, and features to appeal to this group.

2. Focus Marketing Efforts on Middle-Aged Customers
Insight: Middle-aged individuals (ages 30–45) show the highest purchase rate.
Recommendation: Develop marketing campaigns that resonate with middle-aged consumers, such as promoting health benefits, convenience for commuting, and environmentally friendly transportation options. Partnerships with fitness influencers or community-based health programs could further increase engagement with this group.

3. Leverage the Urban Commute Market
Insight: Customers with shorter commutes (0–1 miles) are more inclined to purchase bikes, possibly as an alternative to cars or public transit.
Recommendation: Position bikes as a convenient and eco-friendly option for urban commuting, emphasizing the cost savings and environmental benefits. Marketing in densely populated areas with shorter commute distances, such as city centers or suburban neighborhoods, could be particularly effective.

4. Consider Region-Specific Campaigns
Insight: There are regional differences in bike purchasing behavior, likely influenced by factors like infrastructure, commute distance, and lifestyle.
Recommendation: Tailor marketing and distribution strategies by region. In areas with high demand, consider offering promotions or expanding availability through local retailers or partnerships. In regions with lower bike sales, focus on awareness campaigns highlighting the benefits of biking.

5. Expand Educational Initiatives and Awareness
Insight: Higher education levels correlate with increased bike purchases, possibly due to greater awareness of health, fitness, and environmental benefits.
Recommendation: Conduct awareness campaigns that emphasize these benefits, such as the impact on health and the environment. Collaborating with universities or offering educational content on social media can help build an informed customer base that values biking as a lifestyle choice.

6. Introduce Bundle Offers or Discounts for Families
Insight: Married individuals show a higher likelihood of purchasing bikes, potentially indicating a preference for family or household purchases.
Recommendation: Offer family or group purchase discounts and bundle packages to encourage households to buy multiple bikes. For example, a family-oriented bundle could include a discount for purchasing two or more bikes, with free accessories like helmets or lights.

7. Expand Accessibility Through Flexible Financing Options
Insight: Income still plays a role in bike purchasing decisions. Some customers may be deterred by the upfront cost, particularly those with lower incomes.
Recommendation: Provide flexible financing options, such as installment plans or partnerships with buy-now-pay-later services. This could make bikes more accessible to lower-income individuals who may prefer paying over time.

8. Leverage Digital Marketing to Enhance Customer Engagement
Insight: Digital channels are effective in reaching targeted demographics with tailored messages.
Recommendation: Implement data-driven digital marketing strategies, like targeted ads on social media, where demographics (age, marital status, income, etc.) align with customer profiles identified in the analysis. Additionally, create content that showcases real-life benefits and testimonials to enhance brand trust.

9. Encourage Test-Ride Events and Pop-Up Shops in High-Traffic Areas
Insight: Biking interest can often be increased through direct engagement and test experiences.
Recommendation: Host events or pop-up shops in urban areas where people can test-ride bikes. Allowing customers to experience the product firsthand could increase their likelihood of purchasing, especially for those considering bikes for commuting.

10. Invest in After-Sales Support and Customer Loyalty Programs
Insight: Retaining existing customers can be as valuable as acquiring new ones.

- Recommendation: Offer after-sales support, warranties, and maintenance packages to enhance customer satisfaction. Develop a loyalty program where customers can earn discounts on accessories or future bike upgrades. Positive customer experiences can lead to referrals, repeat purchases, and long-term brand loyalty.
These recommendations are intended to capitalize on the identified trends within your customer data and address potential barriers to bike purchasing. By focusing on targeted demographics, improving accessibility, and expanding awareness, the company can boost sales and strengthen its market presence.

This data was strictly cleaned and analyzed using Excel
#### Tools
- Excel - [Dowload Here](https://microsoft.com)

- The primary source of this data is an Excel file "C:\Users\Admin pc\Downloads\Data Science\Data Science\Bike Sales Analysis project.xlsx". gotten and cleaned by me.

















