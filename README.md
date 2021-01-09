# Bike Sharing Project

## Overview

This analysis uses bike data from the New York City Citi bike share program collected in the month of August in 2019. Visualizations are generated to allow for an underatandinging of the bike share program. Insight generated from the data will be used to explore the viability of implementing a similar system in the city of Des Moines, Iowa.

## Results

[NYC Citi Bike Project Dashboard](https://public.tableau.com/profile/matthew.kaufmann#!/vizhome/NYCCitiBikeProjectDashboard/NYCCitiBike) 
- Dashboard visualization for the Citi Bike Project.

[NYC Citi Bike Project Story](https://public.tableau.com/profile/matthew.kaufmann#!/vizhome/NYCCitiBikeProject_16098901306970/NYCCitiBikeStory)
- Story for the NYC Citi Bike Project.

[NYC Citi Bike Challenge Story](https://public.tableau.com/profile/matthew.kaufmann#!/vizhome/NYCCitiBikeChallenge_16098898415460/NYCCitibikeStory)
- Story for the NYC Citi Bike Challenge analysis.

![Peak hours of use for August](https://github.com/MattK1454/bikesharing/blob/main/images/August%20Peak%20Hours.png)

This visualization shows bike trips per hour in the month of August. The graph reflects two periods of peak usage of the bikes during the day. The first peak of use starts at 6am and ends around 10am. The second peak occurs between 4pm and 8pm. The visualization helps demonstrate the availabilty of bike during which hours it would be best to schedule repairs.

![Gender Breakdown](https://github.com/MattK1454/bikesharing/blob/main/images/Gender%20Breakdown.png)

The idea behind generating this visualization is to attempt to understand the breakdown of customer by gender (male, female, unkown). The data shows males generated the greatest number of trips.

![Checkout time for Users](https://github.com/MattK1454/bikesharing/blob/main/images/Checkout%20Time%20for%20Users.png)

In order to properly manage resources and schedule repairs, it is necessary to look for when the greatest number of bikes are available for repairs.

![Checkout times by gender](https://github.com/MattK1454/bikesharing/blob/main/images/Checkout%20Times%20by%20Gender.png)

This visualization breaks down the previous visualization to show how bike trips by hour are broken down by gender. Data here supports the second visualization showing males made use of the bike sharing system the most in the month of August.

![Trips by Weekday per hour](https://github.com/MattK1454/bikesharing/blob/main/images/Trips%20by%20Weekday%20per%20Hour.png)

This visualization maps number of bike trips for each hour by weekday. This visualization shows the highest level of trips for bikes on weekdays is between 7am and 10am on weekdays and between 5pm to 8pm on the evenings of Monday, Tuesday, Thursday, and Friday. The weekends show a roughly consistent level of bike uses throughout the midday period on Saturdays and Sundays.

Note: Wednesdays appear to have a lower number of bike returns during the evening hours of 5pm to 8pm as compared to the other weekdays.

![Trips by gender (weekday per hour)](https://github.com/MattK1454/bikesharing/blob/main/images/Trips%20by%20Gender%20(Weekday%20per%20Hour).png)

This visualization is a breakdown of the previous visualization by gender. The data supports males generated the highest returns of bikes.

![User trips by gender by weekday](https://github.com/MattK1454/bikesharing/blob/main/images/User%20Trips%20by%20Gender%20by%20Weekday.png)

This visualization looks at how many bikes are checked out by user type with respect to gender by weekday. This data shows subscriber user types generated the most bike trips versus the customer types. To clarify, customer user types are users of the system who are infrequent users of the system - they will only checkout bikes when they need to use them. Subscriber user types are those who will pay a subscription fee to the system to use the bikes - they use bikes consistently and on a regular basis.

## Summary

After looking through the data, there are some reasonable conclusions to be drawn about how best initiate a similar system in Des Moines, Iowa. The initial setup of the system should focus on advertising to enroll as many subscriber user types as possible vs relying on advertising toward random use customer types. According to the visualizations provided, the repairs of bikes should be scheduled for evening to early morning hours. Presumably, repairs could be scheduled to begin after 8pm and end at 6am. Data also suggests focusing the use of advertising dollars to target users to use the system for morning and evening commutes. It may also help to tailor system in relation to gender usage data. This would mean designing a system targeted toward drawing male users roughly twice as much as female users.

Two possible visualizations that could be added to this analysis are:
* Bike use by id by station
* Customer type by age and average trip duration

## References

1. Module 14 Challenge. (n.d.). Retrieved January 05, 2021, from https://courses.bootcampspot.com/courses/453/assignments/6111?module_item_id=91338
