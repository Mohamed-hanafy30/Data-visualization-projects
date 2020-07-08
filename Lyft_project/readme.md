# (Data Visualization Ford GoBike)


## by (Mohamed abdelrazik hanafy)




## Dataset


i have download dataset from this [link](https://s3.amazonaws.com/baywheels-data/index.html) and i use **Modifing and combine CSV for Ford.ipynb** to combine csv files
for each year and concatinate all files into one csv file called data which i use in **exploration.ipynb**

## Brief summary for Dataset

### Ford GoBike System Data

- This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

- Note that this dataset will require some data wrangling in order to make it tidy for analysis. There are multiple cities covered by the linked system, and multiple data files will need to be joined together if a full year’s coverage is desired.



- This dataset includes 519,700 trips with 15 features such as locations, time, and user attributes. There are start and end stations. I noticed that most trips happen on the same stations, so I subset the dataset by choosing top 10 trips start stations with the most trips.


## Summary of Findings



### First:Univariate Exploration

1. The relationship between total number of rides and month of years. according to the graph rides decrease in march april may and june due to rain and we can look at this climate report for sanfrancisco over the year. 

2. The total number of rides decrease on weekends

3. Rides on moring and afternoon is more than at night due to high traffic for people going to work in moring and return to their home in afternoon.

4. The duration of trips is around 650 seconds about 10.7 minutes.


### Second: Bivariate Exploration

1. after we focus on top 10 srations i found that the number of rides for each station during the day is the same as for entier population

## Key Insights for Presentation



The stations with the most trips are located in San Francisco and connect to public transportations including Caltrain, Bart and Ferry. User types play a key factor on the number of trips in each location and time group.