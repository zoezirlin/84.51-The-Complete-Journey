# 84.51-The-Complete-Journey
Case Study for the 84.51 Complete Journey Data Set

This is the case study for the 84.51 Complete Journey data set. There are three files: products, households and transactions. The final merged set has 27,269 rows and 21 columns.
The data represents 5,000 Kroger consumer households. There is transaction data for each household for roughly two years, spanning from 1/3/2016 to 12/30/2017.
Househld demographics, loyalty, regional information are included.



#### Table of Contents
1. Data Importation: lines 162-165
2. Categorical Variable ANOVA and Tukey Modeling: lines 166-183
3. Pivot Tables: lines 184-187
4. Indicator Variable Engineering and Correlation Visualization: lines 232-255
5. Exploratory Regression Modeling: lines 270-280
6. Basket Penetration for Varying Commodities: lines 36-99
7. Market Share for Private vs. National Brands for Each Commodity: lines 119-155



#### Bite Sized Takeaways
1. There are significant differences in spending habits between those of varying income brackets at Kroger grocery stores. The spending of those in the 35-49K subcategory is significantly different than the spending of those in the 100-150K and 150K+ subcategories.


2. There is no statistically significant difference in spending between those who are married, single, or unknown. It would most likely not be beneficial to segment target consumers by their marital status.


3. There is a statistically significant difference between spending for homeowners and renters. Looking at the boxplot, it seems as though there is a much larger spread for homeowner spending, meaning that homeowner outliers tend to spend a lot more than renters. While it may not be feasible to segment consumers into homeowners/renters, it seems as though homeowners "bulk shop" often enough to make a sizeable difference in spending. When it comes to seasonal/ holiday promotional advertising, this may be of interest.


4. We can see that there are significant differences in consumer spending between the food, non-food and pharma categories. These relationships may have been logically predicted, as pharamceuticals can become very expensive, (notice the larger spread of the accompanying boxplot,) and non-food items at Kroger stores can include costly blenders, pens or home supplies, whereas food item prices tend to be more normally distributed.


5. We can see that there does not seem to be a change in patterns of spend or unit consumption among shoppers of different income ranges *across years*.


6. We cannot predict units bought, or spend of a consumer, from a customer's income range, homeowner status, or loyalty flag status.


7. We can see that shoppers with the loyalty flag tend to spend more money throughout all of the weeks recorded; this relationship doesn't diminish as the weeks continue on.


8. The overall percent change in basket penetration for all commodities for these 5,000 shoppers, from 2016 to 2017, is 163.3%.


9. The largest percent change in basket penetration from 2016 to 2017 was for the commodity FLORAL. Basket penetration increased by 352.7%.


10. The second largest change in basket penetration from 2016 to 2017 was for the commodity ACTIVITY. Basket penetration increased by 306.3%.


11. The third largest change in basket penetration from 2016 to 2017 was for the commodity TOBACCO. Basket penetration increased by 275.5%. This is very interesting, as tobacco sales have been dropping for the past few years. This may be an indicator that this sample of 5,000 shoppers is not entirely representative of an average Kroger consumer.


12. The only commodity that saw a negative percent change in basket penetration was MEAT-POULTRY with a -2.4% change. This makes sense, as poultry products did have a slight downturn in overall market value in 2017. This is a very small change, though, in comparison to other commodities, and is most likely not representative.
https://tradingeconomics.com/commodity/poultry



13. By far, these 5,000 consumers purchased more within national brands than within private brands. However, there were 5 commodities that were more popular within private brands than national brands.
    - DAIRY represented 331,566 more purchases for private brands than national.
    - MEAT- BEEF represented 195,124 more purchases for private brands than national.
    - MEAT- CHICKEN represented 105,412 more purchases for private brands than national.
    - MEAT- PORK represented 272,187 more purchases for private brands than national.
    - MEAT- TURKEY represented 81,041 more purchases for private brands than national.
