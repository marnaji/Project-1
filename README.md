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
Uber and Lyft's ride prices are not constant like public transport. They are greatly affected by the demand and supply of rides at a given time. Our analysis aims to understand the relationships of rideshare pricing when compared against external factors like time of day, day of the week, and possibly even weather. The dataset we are analyzing covers simulated rides between a few hot locations in Boston, MA taken in the span of about a week in Nov/Dec of 2018.


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
<img src="/Images/3_6.png" width="300" >  
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
- Average surge multiplier based on the day of the week 

<img src="/Images/4_5.png" width="350" >

#### Statistical Analysis of Combined Weather: Ride Relationships
- Heat map
- Summary statistics of Ride relationships with pricing (IQR, Outliers, Quartiles)
- ANOVA Testing

<img src="/Images/6_4.png" width="350" > <img src="/Images/6_3.png" width="350" >

# Final Summary 

***
#### Calvin's Analysis/Write-up
When extracting the data and merging the data frames we found that Uber has more rides than Lyft.  
People have a tendency to travel short distances with Uber and Lyft because the majority of rides between both apps tend to fit between the ranges of 0 miles to 4 miles. 
It is rare to have the rides be beyond 4 miles. Although Uber has about 11 percent more rides, Lyft generates more revenue. This is most likely due to Lyft charging more per ride.

#### Prachi's Analysis/Writeup
By comparing the overall and monthly revenues of Lyft and Uber, we can see that Lyft has more revenue as compared to Uber. Further comparing ride frequency for different ride types we can see that Uber has slightly more rides on each of its ride types than Lyft. Although Uber had a higher percentage of rides, Lyft made more revenue.

We further analyzed carpooling preferences between Uber and Lyft across days of the week. The general trend shows that shared rides are more at the start of the week than on weekends. This indicates people traveling to offices/workplaces during the weekdays by carpooling.

#### Maryam's Analysis/WriteUp
On average, Lyft's prices are higher, with fares amounting to $17.34 compared to Uber's $13.55. Additionally, Lyft initiates rides at a higher base charge of $10.05, whereas Uber starts at $9.50. Moreover, Lyft imposes higher additional charges per mile, with a rate of $3.38, while Uber charges a lower rate of $1.93 per mile. Despite these differences, the average prices for both apps throughout the week exhibit relative stability, showing minimal fluctuations across different days.

The analysis reveals that rainfall shows the most robust correlation with revenue, indicating that weather conditions positively impact revenue. Conversely, distance exhibits a negative effect on income, suggesting that shorter-distance rides could be a more effective strategy to increase overall revenue.

#### Nivetha's Analysis/WriteUp
In our analysis of weather relationships, we first observed that the preference for taking rideshare apps was more prevalent when there were very small amounts of rain or no rain at all. This is understandable. We also noticed that when there was rainfall of over 15mm, commuters took Uber or Lyft, while there were no rides between 7.5mm to 15mm. With this, we can theorize that either Boston only had rainfall extremes, or people just didn't prefer to take rideshare when it was raining moderately.

While we saw that cloudiness and windspeed were pretty consistent in our time series, these weather conditions didn't affect rideshare as much. Possibly because there was not much-hindering visibility or driveability. We can make the assumption here that taking Uber or Lyft during bad weather is viable and a popular option. People still need to get where they're going! And above all, it seems the bigger preference is for Uber than Lyft.

#### Pratik's Analysis/WriteUp

After analyzing the dataset for Surge Multiplier, it was observed that Surge happens most on Wednesday and 3.0 Surge multiplier is the
less occurring surge multiplier. Also, we could derive that with the dataset provided, weekends see less surge compared to weekdays.
After analyzing further it was observed that on most of the days, we see a rise in surge multiplier in morning and evening time frame.
Also, we see the highest surge on Monday in the afternoon.

When analyzing the correlation between distance vs surge, it was observed that distance is not correlated with surge multiplier price.

Additional analysis on finding what time of the day gets more shared rides. We observed it mostly at night time that we see people taking most shared rides. 

#### Mike Analysis Writeup

Comparing Pick Up and Destination Locations, only Financial District and Northeastern University showed the direct correlation between Total Ride Counts and Total Revenue. Many other Locations ranking high in the Total Revenue list did not have a correlating high Total Ride Count.

Locations Total Revenue vs. Total Ride Counts:
1- Boston University: $730135.0 // 9- Boston University: 41870 
2- Financial District: $716308.45 // 1- Financial District: 42844 
3- Fenway: $698492.5 // 12- Fenway: 41666
4- Northeastern University: $694077.0 // 3- Northeastern University: 42214
5- North Station: $635235.0 // 11- North Station: 41622 
6- Theatre District: $624418.35 // 7- Theatre District: 41737 
7- Back Bay: $619977.0 // 5- Back Bay: 41951 
8- West End: $619902.85 // 8- West End: 41684 
9- Beacon Hill: $617377.5 // 4- Beacon Hill: 41989 
10- South Station: $585813.5 // 6- South Station: 41777 
11- North End: $578567.0 // 10- North End: 41722 
12- Haymarket Square: $546134.15 // 2- Haymarket Square: 42578 

When comparing: Ride Type Counts Overall, Total Revenue by Ride Type, and Revenue Per Mile we notice interesting divergence in the trends. For instance, Lux Black XL is 10th in Ride Type Counts at 18579 but is 1st in Revenue per Mile at $14.82 per mile. On the other side of the coin, Lux Black is 13th in Ride Type Counts at 18458 but is 3rd in Revenue per Mile at $10.57 per mile. Also divergent, Uber XL is 1st in Ride Type Counts at 20197 but is 6th in Revenue per Mile at $7.16 per mile. As such, the difference between Ride Type Counts, Total Revenue by Ride Type, and Revenue per mile can be quite divergent. However, comparing Total-Revenue-by-Ride-Type to Revenue-Per-Mile directly confirms the correlating trend between those two variables.



#### Link to Datasets
***
(Uber vs Lyft Cab Prices)[https://www.kaggle.com/datasets/ravi72munde/uber-lyft-cab-prices] contains two csv files,
- cab-rides.csv
- weather.csv
image one : https://blog.shift.com/best-cars-uber-lyft/
 

