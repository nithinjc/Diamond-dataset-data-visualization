# Ford Gobike System Data visualization project 
## Nithin Jacob Cherian

# Project aim
This project is a part of Udacity Nanodegree program in Data Analytics. It is to practice the data visualization skills that were introduced in the chapter. Data visulization is an integral part of Data analysis and is repeatetively done in different stages of the complete data analysis process. It consists of exploratory and explainatory steps.

# Data
Ford GoBike System Data : https://www.fordgobike.com/system-data
This dataset contains information about individual trips done in past many months covering the greater San Francisco Bay area .

## Bike Trip parameters
Trip Duration (seconds) , Start Time and Date , End Time and Date , Start Station ID , Start Station Name , Start Station Latitude , Start Station Longitude ,  End Station ID , End Station Name,  End Station Latitude , End Station Longitude , Bike ID , User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual) , Member Year of Birth, Member Gender

# Questions to be answered: 
1. Which are the top 10 busy stations (start and end)
2. How long does the average trip take?
3. Does the trip durations vary with months or seasons?
4. Does the above depend on if a user is a subscriber or customer? 

### Summary of findings :
1. Most recorded start station - Markt St at 10th St, Most recorded end station - Caltrain (Townsend) St. Ford could plan to expand facilities based on this data with preference to these stations.
2. The plot shows that the most of the trips were short trips of around 10 min). 
3. March shows some high trip durations. In general all months have similar plots. Need for a deeper analysis.Summer has the longest trip duration , with average above 13.9 mins and winter has the least average trip duration with 12.8 min. To sum up, there is no significant difference of average trip duration in terms of four seasons. It is probably because the weather in San Francisco bay area does not change that much.
4. The number of subscribers are lesser compared to the normal customers. An interesting point is that subscribers tend to rent the bikes for longer trips, above 300 minutes.

# References

- https://stackoverflow.com/questions/26942476/reading-csv-zipped-files-in-python : Work with zip files
- pandas datetimeindex : https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DatetimeIndex.html
