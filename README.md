# Project-1

## Project Title - RIDE SHARE COMPARISON, UBER v LYFT

### Team Members 
* Shingvi Prachi
* Maryam Najiarani
* Nivetha Sundar
* Calvin Kleber
* Mike Strati
* Pratik Deshmane

### Project Description/Outline 
*** 
Uber and Lyft's ride prices are not constant like public transport. They are greatly affected by the demand and supply of rides at a given time. Our analysis aims to understand the relationships of rideshare pricing when compared against external factors like time of day, day of the week and possibly even weather. The dataset we are analyzing covers simulated rides between a few hot locations in Boston, MA taken in the span of about a week in Nov/Dec of 2018.


### Research Questions to Answer
***
1. Weather relationship to Rides
2. Distance relationship to Price 
3. Frequency of Rides relationship Days of the Week
4. Price Surge Trends
5. Surge Multiplier relationship to Type of Car

### car ride analysis 
***
1. Percentage of uber vs lyft:
    The data includes _55.8%_ of Uber rides and _44.2%_ of Lyft rides. 
2. Number uber ride vs distance range
3. Number lyft ride vs distance range
4. Surge_Multiplier 

### car ride vs wheater anlysis 
***
1. **how rain fall affects rides?**  
2. **how cloud affects rides?**


3. **How revenue will be effected by weather conditions? And Does Distance effect revenue ?**
**Maryam's Analysis:** I used heatmap to perform these analysis.
    * Revenue has the highest correlation with Rainfall, and revenue will change based on different weather conditions. 
    * The distance has the negative effect on revenue. The best strategy to increase revenue is to focuse on more short distance rides,because the bulk of the price comes from the initial charges on each ride per day.  
<img src="/Images/RevenueHeatmap.png" width="350">

### Datasets to be Used -
***
### Price IQR, Outliers, and Summary statitics : 
***
**Maryam's Analysis:**
    Lyft has higher price on avaerage (17.34 vs.13.55 )and the Standard deviation is higher (10.02 vs. 9.66). Lyft max price is 92.0 and the min price is 2.5. Uber max price is 89.5 and the min price is 0.0.

<img src="/Images/IQR.png" width="350" >  
<img src="/Images/summaryStatistic ofPrice.png" width="350" >

### Study the relationship between price and the distance
***
**Maryam's Analysis:**
Lyft charges more for based rides compare to Uber (10.05 vs. 9.50) and charges more for each additional miles compare to Uber (3.38 vs. 1.93).

<img src="/Images/LyftLinearReg.png" width="350" > 
<img src="/Images/UberLiearReg.png" width="350" >

### Hypothesis Testing (Comparison of Distance vs. Price for Each ride): 
***
1. **The problem: How do we know if Distance would effect the price charges on each app?**
2. **The solution: ANOVA - Does Distance not effect the price that each ride charges?**

**Maryam's Analysis:**
* Uber : includes more rides, and has the p-Value of pvalue=1.1480829994832444e-127 which is a very small number. So, the null hypothesis that Distance would not have effect on the Price can be rejected.
* Lyft : includes less rides, and had the pvalue=4.858273627090331e-168 which will also reject the null hypohesis that Distance would not have an affect on Price.


#### Link to Datasets
***
(Uber vs Lyft Cab Prices)[https://www.kaggle.com/datasets/ravi72munde/uber-lyft-cab-prices] contains two csv files,
- cab-rides.csv
- weather.csv

### Rough Breakdown of Tasks -
- Merge & Clean dataset. Tentative key - Timestamp data (originally listed in epoch datetime formatting)
- pending tasks...
