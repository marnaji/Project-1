# Project-1
<img src="/Images/uberLyft.png" width="350" >

## Project Title - RIDE SHARE COMPARISON, UBER v LYFT 

### Team Members 
* Prachi Shingvi
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

<img src="/Images/2_7.png" width="450" >

<img src="/Images/2_3.png" width="350" > <img src="/Images/2_4.png" width="350" >

<img src="/Images/2_9.png" width="350" > <img src="/Images/2_8.png" width="350" >

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

#### Prachi's Analysis/Writeup
By comparing overall and monthly revenue's of Lyft and Uber, we can see that Lyft has more revenue as compared to Uber. Further comparing ride frequency for different ride types we can see that Uber has slightly more rides on each of its ride types than Lyft. Although Uber had higher percentage of rides, Lyft made more revenue.

We further analyzed carpooling preference between Uber and Lyft across days of week. The general trend shows shared rides are more at the start of week as compared to weekends. This indicates people travelling to offices/work places during the weekdays by carpooling.

#### Maryam's Analysis/WriteUp
On average, Lyft's prices are higher, with fares amounting to $17.34 compared to Uber's $13.55. Additionally, Lyft initiates rides at a higher base charge of $10.05, whereas Uber starts at $9.50. Moreover, Lyft imposes higher additional charges per mile, with a rate of $3.38, while Uber charges a lower rate of $1.93 per mile. Despite these differences, the average prices for both apps throughout the week exhibit relative stability, showing minimal fluctuations across different days.

The analysis reveals that rainfall shows the most robust correlation with revenue, indicating that weather conditions have a positive impact on revenue. Conversely, distance exhibits a negative effect on revenue, suggesting that shorter distance rides could be a more effective strategy to increase overall revenue.

#### Pratik's Analysis/WriteUp

After analyzing the dataset for Surge Multiplier, it was observed that Surge happens most on wednesday's and 3.0 Surge multiplier is the
less occuring surge multiplier. Also, we could derive that with the dataset provided, weekends see less surge compared to weekdays.
After analyzing further it was observed that on most of the days we see a rise in surge multiplier in morning and evening time frame.
Also we see the highest surge on monday in afternoon.

When did a correlation between distance vs surge, it was observed that distance is not corelated with surge multiplier price.

Additional analysis on finding what time of the day gets more shared rides. We observed its mostly at night time that we see people taking most shared rides. 

#### Mike Analysis // Writeup

When comparing: RIDE TYPE COUNTS OVERALL, TOTAL REVENUE by RIDE TYPE, MEAN REVENUE PER MILE by RIDE TYPE we notice interesting divergence in the trends. For instance, Lux Black XL is 10th in Ride Type Counts at 18579, but is 1st in Revenue per Mile at $14.82 per mile. On the other side of the coin, Lux Black is 13th in Ride Type Counts at 18458, but is 3rd in Revenue per Mile at $10.57 per mile. Also divergent, Uber XL is 1st in Ride Type Counts at 20197, but is 6th in Revenue per Mile at $7.16 per mile. As such, the difference between Ride Type Counts, Total Revenue by Ride Type, and Revenue per mile can be quite divergent.



#### Link to Datasets
***
(Uber vs Lyft Cab Prices)[https://www.kaggle.com/datasets/ravi72munde/uber-lyft-cab-prices] contains two csv files,
- cab-rides.csv
- weather.csv
image one : https://blog.shift.com/best-cars-uber-lyft/
 

