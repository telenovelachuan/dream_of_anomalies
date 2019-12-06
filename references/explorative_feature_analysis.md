# Feature explorative ideas

1. Plot all data points

The pattern of the entire dataset looks two-phase splitted. Before 2/25/2014, all data points oscillates between 40 and 55, while after 2/25/2014 they shifted downward and oscillates between 35 and 40.

2. Try to generate 4 new features:
	- the hour in timestamp
	- whether the data point is during daylight
	- the day of the week
	- whether the data point is a week day
	
3. Plot values that are during day and during night respectively

4. Plot values that are during weekday and weekends

	It can be observed that both Value frequencies during weekends and weekdays conform to normal distributions. During weekends, the bell shape peaks at 42, while during weekdays it shifts a little bit and peaks at 38

5. Plot value distribution histogram of all combinations of day/night and weekday/weekend
