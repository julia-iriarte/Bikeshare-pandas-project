
## Bikeshare Data: Pandas Project

Bicycle-sharing systems allow people to borrow a bike from point A and return it at point B. These systems are very interesting and give us a lot of information to improve the systems itself, the prices, the logistics, etcetera.


### The Code

I wrote code to provide the following information:

1. Popular times of travel (i.e., occurs most often in the start time)
- most common month
- most common day of week
- most common hour of day

2. Popular stations and trip
- most common start station
- most common end station
- most common trip from start to end (i.e., most frequent combination of start station and end station)

3. Trip duration
- total travel time
- average travel time

4. User info
- counts of each user type
- counts of each gender (only available for NYC and Chicago)
earliest, most recent, most common year of birth (only available for NYC and Chicago)


### The Datasets

In this project, I used data provided by Motivate, a bike share system provider for many major cities in the United States, to uncover bike share usage patterns. I compared the system usage between three large cities: Chicago, New York City, and Washington, DC.

The datasets have randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:

- Start Time (e.g., 2017-01-01 00:07:57)
- End Time (e.g., 2017-01-01 00:20:53)
- Trip Duration (in seconds - e.g., 776)
- Start Station (e.g., Broadway & Barry Ave)
- End Station (e.g., Sedgwick St & North Ave)
- User Type (Subscriber or Customer)

The Chicago and New York City files also have the following two columns:

- Gender
- Birth Year

The original files are large and they can be accessed here([Chicago](https://www.divvybikes.com/system-data), [New York City](https://www.citibikenyc.com/system-data), [Washington](https://www.capitalbikeshare.com/system-data)). These files had more columns and they differed in format in many cases. Some data wrangling was performed before I made my analysis.

### Origin of the database and project
This is a project from Udacity's Programming for Data Science Nanodegree Program. The goal of this project was to explore a database using Pandas. This project was already validated.

Pandas documentation website has been used for this project.
https://pandas.pydata.org/docs/index.html