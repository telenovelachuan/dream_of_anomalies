A data science project on the website streaming dataset to apply anomaly detection techniques to discover abnormal data samples

# Feature explorative ideas

1. Plot all data points

The pattern of the entire dataset looks two-phase splitted. Before 2/25/2014, all data points oscillates between 40 and 55, while after 2/25/2014 they shifted downward and oscillates between 35 and 40.

2. Extract feature
	- the hour in timestamp
	- whether it's during daylight
	- the day of the week
	- whether it is a week day
	
3. Plot values during day and during night respectively

4. Plot values during weekday and weekends

Both Value frequencies during weekends and weekdays conform to normal distributions. During weekends the bell peaks at 42, while during weekdays it peaks at 38

5. Plot value distribution histogram of all combinations of day/night and weekday/weekend

