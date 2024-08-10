# Row Health-Visualization
Founded in 2016, Row Health is a medical insurance company serving thousands of customers throughout the United States. In 2019, they launched a new set of marketing campaign categories that spans from topics like wellness tips, plan affordability, and preventative care. Their customers can sign up for 4 different plans - bronze, silver, gold, and platinum - each with different premiums and claim coverage rates. 

As an Analyst, I will be analyzing their data and attempt to help form actionable insights that will capitalize on their marketing budget. The company's aim is to create a better understanding of their campaign catergory options and how they relate to signups and claims from patients.

The analysis will involve a dynamic visualization that the marketing team can use to create self-serve insights and regular reporting. The current goal is to investigate the relationship between the marketing metrics, signup metrics, and claims metric within the various categories.

## Entity Relationship Diagram
The database structure as seen below consists of three tables: Customers, Campaigns, and Claims

![Healthrow Data ERD](https://github.com/user-attachments/assets/8c2ebb27-d55a-4b85-9427-279552f9342f)

## Visualization
Completed Dashboard can be accessed <a href= https://public.tableau.com/app/profile/tung.le4521/viz/HealthcareDataVisualization_17225690685310/Dashboard2>here</a>.

![Dashboard 2](https://github.com/user-attachments/assets/ffd25858-59a5-436d-b5bb-6eed6d744819)

## Insights
### Marketing:
* The top 3 campaign (Tailored Health Plans, #HealthyLiving, Preventative Care News) all had over 1,100,000 impression while all maintaining a low cost per click of $0.05. Click through rate ranges from 6% to 12%.
* Golden Years Security is on the lower side of impressions. However, this campaign cost $0.68 per click which is nearly 10x the cost of the highest campaigns. The campaign also has the lowest click through rate.
  
### Signups:
* Golden Years Security has the highest cost per signup at $176 while having the lowest signup rate at .01% and lowest count of 23. 
* Health for All has the highest sign up rate of 2% and a total signup count of 3,545 while having a relatively low cost in comparsion. The campaign is also in the top 3 higest count of signups.
* A quick glance shows that lower cost campaigns have higher counts of signups while higher cost campaigns have lower counts.
### Claims:
* Compare Health Coverage had the highest claim amount of $3,900,000 but also has the higest claim amount, while Gold Years Security has the lowest with $16,000.
* The average claim amount is $246.75. However, claims amount ranges from $16,000 to $3,000,000. There is no correlation between the two due to the wide range of claim amount for each claim amount.

## Historical Trends
* There was a big increase in Signups in early 2020 and has steadliy decreased before leveling back to pre 2020 levels. The pandamic event may have caused more patients to be concern with their help resulting in an increase need for insurance.
* Coverage Matters, #healthyLiving, and Health for all claims amount increased in 2020 but has remained relatively stagnant. Compare Health Coverage steadily increased up til mid 2020 but dropped to similar levels as the other 3. All Other campaigns remained low.

## Recommendations
### Metrics:
* Decrease the budget for Golden Years Security due to its high cost and low click through rate and sign up rate. Budget should be reallocated to other higher performing campaigns.
* Focus on marketing low costing campaigns that have high click through rate and sign up rate to increase patient count while maintaing a low budget usage. (i.e. Tailored Health Plans, #HealthyLiving, Preventative Care News...)
### Signups:
* Similar to the above, look into Golden Years Security due to its high cost and low count.
* Run additional analysis with marketing on and compare the top 50% of campaigns against the bottom 50% campaigns and see why the low costing campaigns have a higher count. (i.e. better offers/content for value)
### Claims:
* Research into why claims amount increased for Compare Health Coverage, which had a high claims increased, while the rest remained leveled.
* Research into the exact reason why the cause for the increase in sign up in 2020.
### Additional Reccomendation:
* Data on customers age should be collected to help segment based on age and allow for tailoring of campaigns based on those age buckets.
