# Airbnb Exploratory Data Analysis (EDA) Project Report

# 1. Introduction

Airbnb has revolutionized the hospitality industry by providing an online platform for property rentals. This project aims to analyze Airbnb listings data to extract meaningful insights about pricing, availability, host behavior, and customer preferences. The analysis was conducted using Python libraries such as Pandas, Matplotlib, Seaborn, and Power BI for visualization.

# 2. Objectives

* To understand pricing trends and factors influencing Airbnb rental prices.

* To analyze host activity and customer preferences.

* To study geographical distribution and availability of listings.

* To visualize key findings using Power BI dashboards.

# 3. Dataset Description

The dataset used for this analysis contains Airbnb listings from a major city and includes the following key attributes:

* Listing ID: Unique identifier for each listing.

* Host ID & Host Name: Information about the property owner.

*Neighbourhood: Location of the listing.

* Latitude & Longitude: Geospatial data for mapping.

* Room Type: Type of accommodation (Entire home/apartment, Private room, Shared room).

* Price: Cost per night in the local currency.

* Minimum Nights: Minimum number of nights required for booking.

* Number of Reviews: Customer feedback count.

* Availability_365: Number of available days in a year.

# 4. Data Cleaning and Preprocessing

Handling Missing Values: Identified and treated missing values for key attributes such as price and availability.

* Removing Duplicates: Ensured data integrity by removing duplicate entries.

* Outlier Detection: Used box plots and statistical methods to detect and remove price anomalies.

* Data Transformation: Standardized formats for better readability and consistency.

# 5. Exploratory Data Analysis (EDA)

**5.1 Price Distribution Analysis**

* The price distribution showed a right-skewed pattern with a few high-priced listings.

* Most Airbnb properties were priced between $50 to $150 per night.

* Luxury listings (> $500 per night) were outliers, mainly concentrated in premium locations.

**5.2 Room Type Analysis**

* Entire homes/apartments were the most common, followed by private rooms.

* Shared rooms had the least number of listings, indicating lower demand.

**5.3 Geographical Analysis**

* Listings were clustered around city centers and tourist hotspots.

* High-priced listings were primarily located in downtown and beachside areas.

* Mapped geographical insights using Power BI for better visualization.

**5.4 Host Activity Analysis**

* A small percentage of hosts controlled multiple listings.

* Superhosts (highly rated hosts) had higher booking rates and pricing power.

**5.5 Review Analysis**

* Listings with more than 50 reviews tended to have higher occupancy rates.

* Positive reviews correlated with better customer satisfaction and repeat bookings.

# 6. Insights and Recommendations

* Pricing Strategy: Hosts should optimize their pricing based on location, demand, and competitor analysis.

* Enhanced Customer Experience: Encouraging reviews and maintaining high cleanliness ratings can boost bookings.

* Targeted Marketing: Areas with high tourist activity should be promoted more aggressively.

* Optimal Availability: Hosts should increase availability during peak travel seasons to maximize revenue.

# 7. Conclusion

This project successfully analyzed Airbnb listings data to uncover patterns in pricing, availability, and customer preferences. The use of Power BI for interactive visualizations enhanced insights and helped in making data-driven recommendations for hosts and Airbnb stakeholders.

PowerBI Dashboard: https://app.powerbi.com/view?r=eyJrIjoiYjYwOGQ2YTAtMjM4Ni00ZWQwLWJkMDAtOGJjZTMyNzRiZDk3IiwidCI6IjU2NjAxYzUzLTE4NTctNGI0Ni1hYzQzLTExOGI0N2VjMWExZiJ9
