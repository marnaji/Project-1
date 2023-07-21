# Project-1
<img src="/Images/uberLyft.png" width="350" >

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


### Research Questions to Answer - 
***

1. General Behavior of Car Ride Frequency
2. How are Car Rides affected by different Weather Conditions?
3. How is Price & Revenue affected by Distance Travelled/Weather?
4. Deep Dive on Surge Effectiveness in ride revenue
5. Statistical Analysis of Combined Weather: Ride Relationships
6. Final Summary 

#### General Behavior of Car Ride Frequency
- Percentage Distribution against Uber & Lyft
- Preferred Distance Travelled by each App
- Average Rate of Rides on a given day of the week
- Preference of Ride Type

<img src="/Images/2_1.png" width="350" > <img src="/Images/2_2.png" width="350" >
#### How are Car Rides affected by different Weather Conditions?
- Relationships of Rides Affected by Rainfall, Wind Speed, and Cloudiness
  
<img src="/Images/3_1.png" width="300" > <img src="/Images/3_2.png" width="300" > 
<img src="/Images/3_3.png" width="300" > <img src="/Images/3_4.png" width="300" >
#### How is Price & Revenue affected by Distance Travelled/Weather? 
- Summary statistics of price relationship with Lyft and Uber
- Mean price Vs. Day of the week
- How pricing is governed between Uber and Lyft


<img src="/Images/5_Price($)_Pick_Up_Location.png" width="350" > <img src="/Images/5_Price($)_Destination.png" width="350" >
<img src="/Images/PriceLineRegLyft.png" width="350" > <img src="/Images/PriceLineRegUbr.png" width="350" >
  
#### Deep Dive on Surge Effectiveness in ride revenue
- Max Surge depending on the Day of the Week
- Time Series showing the frequency of Surge throughout the day
- Average of surge multiplier based on the day of the week 

<img src="/Images/4_5.png" width="350" >

#### Statistical Analysis of Combined Weather: Ride Relationships
- Heat map
- Summary statistics of Ride relationships with pricing (IQR, Outliers, Quartiles)
- ANOVA Testing

<img src="/Images/RevenueVsWeather.png" width="350" > <img src="/Images/PriceVsWeather.png" width="350" >

# Final Summary 

***
#### Calvin's Analysis/Write-up
When extracting the data and merging the data frames we found that Uber has more rides than Lyft.  
People have a tendency to travel short distances with Uber and Lyft because majority rides between both apps tend to fit between the ranges of 0 miles to 4 miles. 
It is rare to have the rides be beyond 4 miles. Although Uber has about 11 percent more rides, Lyft generates more revenue. This is most likely due to Lyft charging more per ride.

#### Maryam's Analysis/WriteUp
On average, Lyft's prices are higher, with fares amounting to $17.34 compared to Uber's $13.55. Additionally, Lyft initiates rides at a higher base charge of $10.05, whereas Uber starts at $9.50. Moreover, Lyft imposes higher additional charges per mile, with a rate of $3.38, while Uber charges a lower rate of $1.93 per mile. Despite these differences, the average prices for both apps throughout the week exhibit relative stability, showing minimal fluctuations across different days.

The analysis reveals that rainfall shows the most robust correlation with revenue, indicating that weather conditions have a positive impact on revenue. Conversely, distance exhibits a negative effect on revenue, suggesting that shorter distance rides could be a more effective strategy to increase overall revenue.

#### Mike Analysis // Writeup

When comparing: RIDE TYPE COUNTS OVERALL, TOTAL REVENUE by RIDE TYPE, MEAN REVENUE PER MILE by RIDE TYPE we notice interesting divergence in the trends. For instance, Lux Black XL is 10th in Ride Type Counts at 18579, but is 1st in Revenue per Mile at $14.82 per mile. On the other side of the coin, Lux Black is 13th in Ride Type Counts at 18458, but is 3rd in Revenue per Mile at $10.57 per mile. Also divergent, Uber XL is 1st in Ride Type Counts at 20197, but is 6th in Revenue per Mile at $7.16 per mile. As such, the difference between Ride Type Counts, Total Revenue by Ride Type, and Revenue per mile.



#### Link to Datasets
***
(Uber vs Lyft Cab Prices)[https://www.kaggle.com/datasets/ravi72munde/uber-lyft-cab-prices] contains two csv files,
- cab-rides.csv
- weather.csv
image one : https://blog.shift.com/best-cars-uber-lyft/
 

