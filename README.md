# Hawaii Climate Analysis

## Database Setup
The database used for this analysis is stored in a SQLite database file named hawaii.sqlite. 
The following tables are reflected into SQLAlchemy ORM:
* Station
* Measurment

## Exploratory Precipitation Analysis
1. The most recent date recorded in the dataset is obtained using SQLAlchemy ORM and is used as a reference point for further analysis.
2. A query is performed to retrieve the precipitation data for the last 12 months, starting from the most recent data point in the database. The data is then visualized using Pandas and Matplotlib, plotting precipitation values over time.
3.  Summary statistics for the precipitation data, including count, mean, standard deviation, minimum, 25th percentile, median, 75th percentile, and maximum, are calculated using Pandas.

## Exploratory Station Analysis
1. A query is designed to calculate the total number of weather stations in the dataset.
2. The most active stations are identified by listing the stations and their corresponding observation counts, sorted in descending order.
3. For the most active station, the lowest, highest, and average temperatures are calculated using SQLAlchemy functions.
4. Temperature observations for the most active station in the last 12 months are queried and plotted as a histogram to visualize the frequency distribution of temperatures.
