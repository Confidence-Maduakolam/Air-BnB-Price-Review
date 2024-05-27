# Air-BnB-Price-Review
### Table Of Content
- [PROJECT INTRODUCTION](#project-introduction)
- [DATA CLEANING AND TRANSFORMATION](#data-cleaning-and-transformation)
- [DATA MODELING](#data-modeling)
- [DATA VISUALISATION](#data-visualisation)
- [KEY METRICS OVERVIEW](#key-metrics-overview)
- [INSIGHTS](#insights)
- [RECOMMENDATIONS](#recommendations)

### PROJECT INTRODUCTION
#### Airbnb Listings & Reviews:
Airbnb data for 250,000+ listings in 10 major cities, including information about hosts, pricing, location, and room type, along with over 5 million historical reviews.

### Explanatory Data Analysis EDA
1. What are major differences in the Airbnb market between cities?
2. Which attributes have the biggest influence in price?
3. Are you able to identify any trends or seasonality in the review data?
4. Which city offers a better value for travel?

#### Data set Link: [Download here](https://drive.google.com/file/d/1cFi7RGdTWRYFGGKGrj8LaFqHt1dVBhs4/view)
#### Tool
- Power BI

### DATA CLEANING AND TRANSFORMATION
Firstly I upload the csv dataset file to my power query to investigate for errors, null values or blank columns and check if the data is well structure to make a good visuals, After checking my data I noticed blank columns in the data which I removed the columns entirely since the columns wont affect my visuals.
To remove the empty Columns I selected the affected columns and clicked on Transform on my power query field then clicked on Remove columns, then I use first rows as headers for Listing_data_dictionary and Reviews_data_dictonary
This data set contain 4 Tables which are

•Listing Review

•Review Preview

•Listing_data_dictionary

•Review_data_dictionary

This Tables each have different fields which makes up and Table.
### DATA MODELING

 Power bi has already automatically built a relationship as seen in the picture below

 ### DATA VISUALISATION
 
 ### KEY METRICS OVERVIEW
Based on the "AIR BnB MARKET PRICE REVIEW" dashboard, here are the key metrics for the visualization.

•Listing_id: 279.71k

•Average Price : $608.792

•Number of Bedrooms: 250.28k

•Count of city: 10

### INSIGHTS:

 1. What are the Major Differences in the Airbnb Market Between Cities:
 
 Average Ratings: New York and Rome have the highest average ratings by price, indicating potentially better guest satisfaction.
 
 Price Variation by Room Type: The pie chart shows significant variation in the average price by room type, Hotel rooms ($800 and Entire places($673) have higher prices compared to 
 private($462) and shared rooms($579.9).
 
 Review Ratings Distribution: Cities like Paris and New York have a higher total review rating of 35.63% and 20.01% respectively, suggesting higher activity and possibly more developed 
 Airbnb markets in these cities.
 
 2. What are the Average Attributes Influencing Price:
 
 Room Type: As seen in the pie chart, the room type significantly influences the price. Entire homes and hotel rooms are more expensive than private or shared rooms.
 
 Location: The table and maps indicate that cities like Cape Town and Tokyo have higher average prices, suggesting location as a key price factor.
 
 Number of Bedrooms: The dashboard indicates a correlation between the number of bedrooms and the average price, with more bedrooms typically leading to higher prices.
 
3. Trends or Seasonality in Review Data:
   
Yearly Price Trends: The line graph showing the average price by year, city, and room type shows fluctuations over the years, indicating possible seasonal trends or market adjustments. For example, prices peak around 2011 and then show a decline, which could be due to various economic factors or changes in travel trends.
Review Ratings: The total review ratings by city can also reflect seasonal trends, where cities like Paris and New York might see peaks in ratings during high seasons.

4. City Offering Better Value for Travel:
   
##### Value Assessment: 
Considering both average ratings and average prices, cities like Paris and New York offer high ratings but also have high prices. In contrast, cities like Rome,Cape Town and Bangkok offer competitive prices with relatively high ratings, suggesting better value for travelers looking for cost-effective options.

##### Room Specifics:
For budget travelers, cities with lower average prices for private and shared rooms, such as Mexico City and Bangkok, might offer better value.

### RECOMMENDATIONS

##### For Budget Travelers: 
Consider cities with lower costs for private and shared rooms and reasonable average ratings.

##### For Luxury Experiences: 
Cities like Paris,New York and Rome, despite higher prices, offer top-rated experiences according to guest reviews.

##### Seasonal Planning: 
Review the trends in prices and ratings to plan travel during off-peak seasons for better deals in high-rated cities.

This analysis provides a comprehensive overview of Air BnB, to help make informed decisions regarding Airbnb accommodations in different cities.
