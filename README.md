# Urban Mobility Analysis: Bikeshare Data Exploration #

## Project Overview ##
This project explores massive, multi-city transportation datasets to uncover urban mobility patterns and answer key questions about user behavior. Specifically, it analyzes bikeshare system data from three major U.S. cities: Washington, Chicago, and New York.

## Data Sources ##

The analysis utilizes three primary CSV datasets containing historical bikeshare transaction data:

new_york_city.csv

washington.csv

chicago.csv

**Technologies Used**
R Programming Language (Data Ingestion, Manipulation, and Statistical Summary)

Jupyter Notebook (Development and Reporting Environment)

## Core Analysis & Insights ##
The project methodology focuses on rapid data ingestion, standardizing dataframes across different cities, and writing R scripts to calculate statistical summaries. The analysis answers the following core questions:

**1. What is the most common day of the week for bike rentals?**

**Insight**: The line graph shows a clear weekly pattern in bike share usage. Trips steadily increase from Monday and peak in the middle of the week, with the highest number of rides (142,773) occurring on Wednesday. After that, usage drops as the weekend approaches. This pattern supports the idea that most riders are using the bikes for regular weekday commuting rather than for occasional weekend trips.

**2. What is the average travel time for users in different cities?**

**Insight**: When looking at trip duration, Washington has the longest average travel time at about 1,237 seconds (roughly 20 minutes). Chicago follows with an average of 936 seconds, and New York has the shortest average at around 900 seconds. In all three cities, the median trip time is much lower than the average, which suggests the data are right-skewed. This means most trips are fairly short, but a smaller number of much longer trips raise the overall average.

**3. What are the counts of each user type?**

**Insight**: Across all three cities, the majority of users are Subscribers rather than short-term Customers. New York has the highest number of subscribers, with a total of 269,149. Chicago also includes a third user category called 'Dependent', but this group is extremely small, with only 13 users, making it statistically insignificant.

**Skills Demonstrated**:

Rapid upskilling and application of a new statistical programming language (R).

Wrangling and comparing large, disparate CSV files.

Translating raw transit data into actionable answers for urban mobility questions.
