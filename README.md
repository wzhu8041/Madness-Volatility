# Madness-Volatility
Trying to quantify the unpredictability of the March Madness tournament and create a volatility metric to measure the unpredictability
This code:
- scrapes the data from ESPN (AP Top 25 Ranking) and Wikipedia (Upsets from March Madness Tournament)
- creates a database containing the cumulative changes in the AP Top 25 rankings for all weeks in an NCAA basketball season from 2003 to 2023
- creates another database containing the upsets in the March Madness tournament since 1983. We documented the difference in seeding and the round for each upset
- created a "madness" value by taking 2 to the power of the difference in seeding plus the round (1 being the round of 64, 2 being the round of 32, and so on)
- graphs the upsets by year and the AP changes by year (normalized in case we wanted to compare the two).


The error in cell 16 is just due to not being able to find the scraped files. This should be resolved by running the code again.
