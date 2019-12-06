# Feature explorative ideas

1. Plot all data points

The pattern of the entire dataset looks two-phase splitted. Before 2/25/2014, all data points oscillates between 40 and 55, while after 2/25/2014 they shifted downward and oscillates between 35 and 40.

![entire_data_plot](https://github.com/telenovelachuan/dream_of_anomalies/blob/master/reports/figures/feature%20exploration/all%20values%20distribution.png)

2. Try to generate 4 new features:
	- the hour in timestamp
	- whether the data point is during daylight
	- the day of the week
	- whether the data point is a week day
	
3. Plot values that are during day and during night respectively

4. Plot values that are during weekday and weekends

	It can be observed that both Value frequencies during weekends and weekdays conform to normal distributions. During weekends, the bell shape peaks at 42, while during weekdays it shifts a little bit and peaks at 38
	
![4_ctg_data_plot](https://github.com/telenovelachuan/dream_of_anomalies/blob/master/reports/figures/feature%20exploration/distribution%20of%204%20categories.png)

5. Plot value distribution histogram of all combinations of day/night and weekday/weekend
![4_ctg_distr_plot](https://github.com/telenovelachuan/dream_of_anomalies/blob/master/reports/figures/feature%20exploration/value%20frq%20histogram%20of%20all%204%20categories.png)
