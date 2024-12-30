# The Economic Impact of Retail Mask Policies
The Economic Impact of Retail Mask Policies

## Final Report:
[Economic Impact of Mask Policy](https://jiaqi2022.github.io/Economic_Impact_of_Mask_Policy_EDA/)

## Insights

On May 18, Walmart implemented a reversal policy, resulting in a noticeable increase in customer traffic, particularly on the 23rd and 27th, following the relaxation of mask restrictions. This trend highlights that consumers not only consider the products but also factors such as service quality and shopping environment. With the easing of mask policies, customers likely feel more comfortable and autonomous in their shopping choices, leading to increased store visits.

![image](https://github.com/user-attachments/assets/f9ba0cd6-180a-47e7-9948-ff983573085e)

**Conclusion: The relaxation of mask restrictions positively influenced Walmart's customer traffic, emphasizing the importance of service quality and shopping environment in consumer behavior.**

![image](https://github.com/user-attachments/assets/ea284250-ed7b-4122-ac3a-d9836da23619)
This section visualizes daily data from various states to assess the regional impact of the mask policy on consumer behavior. The analysis shows a significant increase in customer visits in most states following the policy reversal, with notable differences in baseline traffic levels across states, particularly higher in Hawaii. Additionally, trends vary by date, prompting the use of individual and time fixed effects models in the regression analysis to account for these variations.

**Conclusion: The mask policy reversal led to a notable increase in customer visits across most states, highlighting regional differences in consumer behavior and necessitating fixed effects models for accurate analysis.**

## Background
On May 13, 2021, the Centers for Disease Control and Prevention (CDC) announced that people who have completed the New Crown Pneumonia vaccination are no longer required to wear masks in most settings and are no longer required to maintain social distance from others. Major retail brands have reacted quickly to this mask reversal policy, and several major supermarket chains and merchants, including Walmart, have already rescinded or re-evaluated their mask requirements. It is not difficult to infer that the change in mask policy would have a significant impact on consumer psychology and consumer behavior. Therefore, in this project, I start from this mask reversal and use the mask reversal implemented by Walmart on May 18 as a sample to study how changes in retail policies regarding mask use affect consumer behavior. At the same time, we will consider how factors such as vaccination hesitancy and partisanship will play into this impact.

The main elements of this project are as follows: In the fist part, I will introduce the raw data, do the basic processing, and also cover the basic exploratory data analysis. The second part is about the graphical exploratory data analysis. I will display some maps showing the location of Walmart stores in the county or state as an overview of the dataset. Several time series plots of the average foot traffic (by day) at Walmart stores over a 28-day period will be created to evaluate the effect of mask reversal policy. In the third part, I will use a multiple linear regression model to investigate specific impact of the reversal policy and further explores it by adding a series of mediating variables. Also, there will be some basic correlation analysis and plots.
