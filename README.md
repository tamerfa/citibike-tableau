# Citibike Analysis for Rides between 2018-2021

## Preparing the source files
- Due to the fact that the resources files and the cleaned data file are too large to upload to Github, I could only describe them below
- The resources files that were downloaded from https://s3.amazonaws.com/tripdata/index.html are the files from "JC-201801-citibike-tripdata.csv" to "JC-202111-citibike-tripdata.csv"
- The downloaded files were kept in the "Resources" folder.
- You need to run "Compining the source files.ipynb" to create the cleaned data file "\Resources\Cleaned_data\jc18_21.csv"
- The tableau file "Citibike 2018-2021 Analytics.twbx" is downloadable from https://public.tableau.com/app/profile/tamer.abdelaal/viz/Citibike2018-2021Analytics/CitibikeAnalysisforRidesbetween2018-2021?publish=yes, and it uses "jc18_21.csv" to create the visualisations.


## Some phenomena discovered from the data

### Growth trends of Citibike ridership over the period from 2018 to 2021
It was expected to see a decline in the total number of rides during 2020 because of the COVID-19 outbreak.

However, it was found that the biggest decline was in the number of subscriber riders, while the numbers of casual customers kept increasing, it even increased with a higher rate in 2021

### Overall growth of ridership between 2018 and 2021
Despite the pandemic, rides have almost doubled between 2018 and 2021


### Distribution of rides vs riders age and gender
Birth year data shows that many riders have given false information about their birth year. 

A large percentage of them has specified 1969 as their birth year, I guess because 1969 is a special year for the Americans as it marks the moon landing.

### Popular location for Citibike rides
As expected, the most popular stations for the riders are located in the areas with the median age of the population is less than 36 years.