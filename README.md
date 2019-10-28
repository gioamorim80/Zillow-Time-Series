# Zillow-Research-Time-Series
Flatiron Data Science Bootcamp Module 4 Final Project

In this project we use the data made available by Zillow on their Zillow Home Value Index (ZHVI), according to their website, "a smoothed, seasonally adjusted measure of the median estimated home value". The data covers the ZHVI for over 14k zipcodes across the US and from year 1997 to 2018.

The goal of the project is to use this data to analyse, model and predict returns in order to decide which major coast city is the best option for investors: San Francisco, CA or New York City, NY, as well as recommend the best 5 zipcodes to invest on.

The first part of the project is selecting the best city overall to invest. To do this we have calculated the ROI for 2 and 5 years time-lags. We model this ROI data using the auto_arima function to select the optimal order and ran a SARIMAX model to get the predictions and inform our recommendations.

The second part of the project is to identify which are the 5 best zipcodes to invest in each of these cities. We again have calculated the ROI for 2 and 5 years and selected the 5 zipcodes in each city that showed the best mean returns in the last 6 months of the data set for each time-lag investment.
