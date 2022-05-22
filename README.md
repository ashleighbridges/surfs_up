# surfs_up

## Overview
The purpose of this project was to analyze the temperatures during the months of June and December in recent years to ensure the location picked for the surf shop will be sustainable year-round. I created two queries - first to pull the raw data and create a DataFrame containing the temperatures for June, and then used the .describe() method to find the statistics (including count, mean, standard deviation, minimum, maximum, and quartiles) for the June temperatures. After completing the June analysis, I refactored the existing code to do the same for the December data.

## Results
For the month of June, we had 1700 total temperatures to use for our analysis. The average temperature in the month of June is 74.9°, with a minimum recorded temperature of 64.0° and a maximum recorded temperature of 85.0°.

![june_stats](https://user-images.githubusercontent.com/100883212/169712926-636cc76e-ce36-41bb-9d2b-d2c1619283c4.png)

For the month of December, we had 1517 total temperatures to use for our analysis. The average temperature in the month of December is 71.0°, with a minimum recorded temperature of 56.0° and a maximum recorded temperature of 83.0°.

![dec_stats](https://user-images.githubusercontent.com/100883212/169712980-f4971495-f111-401d-90eb-d8b1504198ec.png)

## Summary
From our analysis, we can see that there isn't much of a difference in average temperature between June and December. The minimum temperature recorded in December was 8° colder than the minimum recorded temperature in June, which is to be expected and may lead to a few less busy days in the surf shop during the winter months, but overall the shop should be a popular destination year-round due to the consistently warm climate!

One statistic that would be helpful to compare for more analysis would be the average number of daylight hours in each month. Since surfing cannot take place during darker hours, we would need to look into adjusting the shop operating plan during the months where there are fewer hours of daylight to conserve costs and ensure the months with more daylight hours will offset them. Another important factor in surfing is wind. Being able to compare average wind speeds for each month to have a better idea of which months provide the best surfing weather on average would be vital to creating a successful business plan.
