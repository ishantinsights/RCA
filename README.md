
Root Cause Analysis 

Decoding Supply-Demand Gap: A Data-Driven Analysis of Cab Services

Problem Statement
Company has been experiencing significant issues related to ride cancellations and non-availability of cars, particularly for routes between the City and the Airport. These issues have resulted in negative customer feedback and a loss of revenue. 

#Column Profiling:
Request id: Unique identifier for each cab request.
Pickup point: Location where the ride was requested (City or Airport).
Driver id: Unique identifier for each driver.
Status: Status of the ride request (Trip Completed, No Cars Available, Canceled).
Request timestamp: Timestamp when the ride was requested.
Drop timestamp: Timestamp when the ride was completed.

#Before jumping on to solution ,Let us clarify few of the things:

What is ride cancellation as per company?
Ride cancellation rate = No of cancelled bookings / No of confirmed bookings

Categorise the ride cancellations into two groups -

Intercity
City to Airport (or vice-versa)

#First of all, irrespective of the data that we have, there are some questions that we need to ask as a Data/Product Analyst to get some clarity on the issue

Q.Is this thing happening for specific devices? (Android or iOS)

Q. Has there been any major change/upgrade in the product?

Q. Is this increase in cancellation rate gradual or sudden?'

Q. Have we checked for any issues on the driver app?

Q. Are we receiving any major complaints or bug reports?

Q. Is the change observed across several regions specifically or is it uniform?

Q. Are we seeing a high cancellation rate for driver’s belonging to a specific age group?

Q. Any pattern in ride cancellations in terms of the vehicle category? (Auto, Mini or Sedan)

Q. Has there been any major holiday in the past week?

Q. Have we done any recent experiments related to the platform?

Q. Has there been any recent strike or protest by the drivers?

Q. Has company been involved in any controversy lately?

Q. Are we currently facing any connectivity related issues throughout the region? Q. Do we have any reports of frequent app crashes or something like that?

Q. Is there any change detected in the usual user behavior over the last week?

Q. Is it possible that the drivers might be using some other ride sharing platforms as well?

#Analysis Goals
The primary objectives of this analysis are to:
Identify the significant factors contributing to ride cancellations and car non-availability.
Understand how these factors affect the supply-demand gap.
Provide actionable recommendations to mitigate these issues.

#Step 1: Understanding the Data
The analysis began with exploring and preparing the dataset. Key steps included:

Data Cleaning: Handling missing values, duplicate rows, and outliers.
Feature Engineering: Extracting useful features such as request hour and time slots from the timestamps.
Categorization: Converting relevant numerical columns into categorical columns for better analysis.

#Step 2: Exploratory Data Analysis (EDA)
Univariate and bivariate analyses were conducted to understand the distribution and relationships between various factors and the ride status. 
Visualizations revealed significant patterns:
High Demand, Low Supply Periods: Identified specific times of the day where demand far exceeds supply.
Request Patterns: Noted differences in request patterns between City to Airport and Airport to City routes.

High Demand, Low Supply Periods: Identified specific times of the day where demand far exceeds supply.
Request Patterns: Noted differences in request patterns between City to Airport and Airport to City routes.

#Step 3: Detailed Analysis of Demand-Supply Gaps
To further understand the factors contributing to the supply-demand gap, a detailed analysis was conducted. Key focus areas included:

Time of Day Effects: Analyzing how different times of the day impact ride cancellations and car availability.
Route-Specific Trends: Examining the differences in supply-demand dynamics for City to Airport versus Airport to City routes.

#Step 4: Insights and Recommendations
Based on the analysis, several insights were gained, leading to actionable recommendations:

A.)Incentivize Waiting Time: Offering incentives for drivers to wait at the Airport could reduce ride cancellations and 'No Cars Available' issues.
B.)Shift Adjustments: Encourage drivers to work during peak demand hours (Late Evening and Early Morning) by offering higher incentives or bonuses.
c.)Dynamic Pricing: Implement dynamic pricing to attract more drivers during high-demand periods.
D.)Pre-Booking Option: Allow customers to pre-book cabs for Airport trips, providing drivers with more certainty and reducing cancellations.
E.)Driver Redistribution: Strategically redistribute drivers based on predicted demand patterns to ensure better availability of cabs.
Conclusion

This data-driven analysis provided a comprehensive understanding of the supply-demand gap in cab services between the City and the Airport. By leveraging the insights from this analysis, company can make informed decisions to enhance customer satisfaction, optimize operations, and improve revenue. The recommendations offered aim to address the root causes of ride cancellations and car non-availability, ultimately leading to a more reliable and efficient service.


