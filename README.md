![image](https://github.com/JoshuaKab/Porfolio/assets/135429439/487a2b87-77e2-48c6-a63e-0d7bc17fb33c)

# Porfolio
**Google case study**

Python notebook code [Click here](https://github.com/JoshuaKab/Machine-Learning/blob/main/EDA_%20Analysis%20divvy%20bike%20sharing%20progra%2C.ipynb)
<h1>Introduction:</h1>

Welcome to the Cyclistic bike-share analysis Google case study!
This case study represents course 8 “Capstone project” of the Google Data Analytics Professional Certificate on Coursera


**About the company:**

In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network
of 692 stations across Chicago. Cyclistic has flexible pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day 
passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members.

The Scenario:

Cyclistic is a fictional bike-share company in Chicago. The director of marketing believes the company’s future success
depends on maximising the number of annual memberships. Therefore, the data analytics team wants to understand how casual riders and annual members use Cyclistic bikes
differently. From these insights, the team will design a new marketing strategy to convert casual riders into annual members.


Moreno, the director of marketing, has set a clear goal: Design marketing strategies aimed at converting casual riders into annual members.

There are three questions that will guide the future marketing program:
1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?

Moreno has assigned me the first question to answer: 

How do annual members and casual riders use Cyclistic bikes differently?

****The business task:****
Analyse the Cyclistic data set for the pass 12 months to understand how annual members and casual riders use Cyclistic bikes differently.

**Stakeholders:**

***Lily Moreno:*** The director of marketing. Moreno is responsible for the development of campaigns and initiatives to promote the bike-share program.
Cyclistic marketing analytics team: A team of data analysts who are responsible for collecting, analysing, and reporting data that helps guide Cyclistic marketing strategy.
Cyclistic executive team: The executive team will decide whether to approve the recommended marketing program.
Deliverables:

1. A description of all data sources used
1. Documentation of any cleaning or manipulation of data
1. A summary of the analysis
1. Supporting visualisations and key findings
1. Top three to four recommendations based on the analysis
Timeline:

A week Periode 

***1- A description of all data sources used:***
The data-set which will be used for the analysis has been provided by Cyclistic management. It consists of 12 CSV files, one file for each month, from march 2022 to Feb 2023.
*This is public data that has been made available by Motivate International Inc. under this licence

***2- Cleaning and manipulating the data:***
Cleaning and ensuring data quality is a vital part of the data analytics process. If the data has inconsistencies and/or errors it will lead probably to bad insights.
In a field like marketing, bad insights can mean wasting money on poorly targeted campaigns.
There are nine columns in each file containing data about all rides that took place in the year 2020:

1. ride_id
2. rideable_type: the type of the bike (docked_bike, electric_bike and classic_bike)
3. started_at: the date and time the ride started at
4. ended_at: the date and time the ride ended at
5. start_station_name: station’s name the ride started at
6. start_station_id: station’s ID the ride started at
7. end_station_name: station’s name the ride ended at
8. end_station_id: station’s ID the ride ended at
9. member_casual: casual rider or member rider

**Added columns**

after 5 more columns was add

1. date
2. day of the week
3. Month
4. Yeath
5. duration

### Summary and Recommendation

1.Summary:
This notebook performs an exploratory data analysis (EDA) on the Cyclistic bike-share dataset, which includes data from March 2022 to February 2023. The analysis includes the following steps:

Data Loading and Preparation:

Loaded 12 CSV files, each representing a month of data, and combined them into a single DataFrame.
Converted date columns to datetime format and extracted additional features such as month, day of the week, and hour.
Calculated ride duration and removed negative values.
Data Cleaning:

Checked for and removed duplicate entries.
Ensured the data types of columns were appropriate for analysis.

## Exploratory Data Analysis (EDA):

Analyzed ride duration statistics and grouped data by month, bike type, and customer type.
Created pivot tables to summarize ride duration and count by bike type and customer type.
Visualized data distributions using histograms, boxplots, and bar plots.
Identified the busiest times of day and the most popular bike types and stations.
Statistical Analysis:

Performed a t-test to compare ride durations between members and casual riders.
Conducted an ANOVA to analyze the effect of bike type on ride duration.
2.Recommendations:
Marketing Strategy:

Focus marketing efforts on promoting electric bikes, as they are the most popular among customers.
Develop targeted campaigns for casual riders, who have longer ride durations on average.
Operational Improvements:

Increase the availability of bikes during peak hours (8 AM and 5 PM) to meet high demand.
Ensure that popular stations are well-stocked with bikes, especially during weekends.
Customer Experience:

Consider offering incentives or discounts for rides during off-peak hours to balance demand.
Improve the user experience for casual riders to encourage them to become members.
Further Analysis:

Investigate the reasons behind the high usage of electric bikes and explore opportunities to expand the fleet.
Analyze the impact of weather conditions on ride patterns and adjust operations accordingly.
By implementing these recommendations, Cyclistic can enhance customer satisfaction, optimize operations, and increase overall usage of the bike-share program.






