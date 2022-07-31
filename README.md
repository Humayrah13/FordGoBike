# FordGoBike Trip Exploratory Analysis
## by Aishat Adeyemo


## Dataset

The data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. It contains attributes for approximately 183,500 trips taken in the month of February, year 2019. These attributes include user's biodata, user type (subscriber/non-subscriber), trip duration, trip start and end time, and start/end locations and whether the trips were shared or not.
The dataset can be downloaded via this [link](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv).
For this exploratory analysis, I did some preliminary wrangling to improve the quality of my data. I replaced null values with the modal values in the gender and birth year columns, then dropped rows where there null values were presnt in the whole dataset. Afterwards, I converted all the data types to their appropriate data types.
I also did some feature engineerig to derive some features that were not originally in the dataset but would make more insights to be drawn from the data. I converted duration in seconds to minutes, derived users age from their year of birth, Extracted weekday from the start time and categorized start time into different periods of the day (i.e, Morning, Mid-day, Afternoon, Evening, Night and Midnight)  

## Summary of Findings

At the end of the whole Exploratory Analysis, the following were deduced;

   1. 9% of all trips taken in the month of February were shared. 
   
   2. Most of the trips were taken on Thursdays.
    
   3. Male users were the highest users of the bike hailing service.
   
   4. The Peak periods of the trips taken were Morning and Evening.
    
   5. Shared trips were taken only by subscribers of the bike hailing service. These subscribers are majorly of the male
    gender and the trips were taken in broad daylight.
    
   6. Average age of users who shared their trips is within the range of 35-40 years.
   
   7. Other-gendered subscribers took shared trips of longer duration in the night and midnight.
   

## Key Insights for Presentation

The following are the Insights for the Presentation;

   I started by showing the percentage of shared trips which is the focus of the analysis. I then showed the distribution of users' ages 
   and trip durations. Both are skewed to the right.
   
   Peak periods of the trips and the major users of the bike service are then shared.
   
   Category of users who shared their trips was analyzed.
   
   The pattern for users who shared their trips was also analyzed.
