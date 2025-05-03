Refer the following analysis steps which need to be applied to the given data set.

Load and Query Time-Series Data (1)

Feature Engineering in Time Series (2)

Exploring Components (2)

Resampling and Interpolation (3)

Stationarity, Trend, and Seasonality (2)

Autocorrelation and Partial Autocorrelation (2)

Identify patterns for modelling. (3)


1. Load and Query Time-Series Data
   a. Load the time-series dataset from the given URL and display the first five rows. What
   function is used to load a CSV file in Python using pandas?
   b. Convert the 'Date' column into a DateTime object and set it as an index. Why is it necessary
   to convert the date column into a DateTime format in time series analysis?
   c. Query the dataset for the minimum temperature recorded on January 5, 1985. What
   command would you use in pandas to retrieve this information?
   d. Extract all data from the year 1985. How do you filter data for a specific year using pandas?
   e. Generate the summary statistics of the dataset. What key statistical insights can be obtained
   from this summary?

2. Feature Engineering in Time Series
   a. Create a new feature for the month and day of the week from the date column. What Python
   function extracts the month from a DateTime column?
   b. Implement a lag feature by shifting the temperature values by one day. Why are lag features
   useful in time series modeling?
   c. Develop a rolling mean with a window of 7 days. How does a rolling mean help in
   smoothing the time series data?
   d. Create an expanding window feature that calculates the cumulative mean of temperature
   values. What is the difference between rolling and expanding windows?

3. Exploring Temporal Relationships
   a. Plot the time series data using a line chart. What insights can you gather from the trend?
   b. Create a scatter plot with lagged values (e.g., temperature at day t vs. temperature at    day t-1). What pattern would you expect in a strongly correlated time series?
   c. Generate an autocorrelation plot of the time series data. What does a significant
   autocorrelation at lag-1 indicate?
   d. Visualize the histogram and density plot of the temperature values. What can you infer
   about the distribution of temperature data?
   e. Use a box plot to observe the monthly temperature distribution. How do box plots help in
   detecting seasonality in time series data?
   f. Create a heatmap to visualize the yearly trend in temperature variations. How do heatmaps
   aid in identifying long-term trends?

4. Resampling and Interpolation
   a. Resample the data to hourly frequency using upsampling. What happens to missing values
   in upsampled data?
   b. Perform linear interpolation on the upsampled data. How does linear interpolation differ
   from polynomial interpolation?
   c. Downsample the dataset to a monthly frequency by taking the average temperature. How
   does downsampling affect time series data?
   d. Group the data by year and compute the annual mean temperature. What statistical insights
   can you derive from grouped data?

5. Stationarity, Trend, and Seasonality
   a. Apply the Augmented Dickey-Fuller (ADF) test to check for stationarity. What null
   hypothesis does the ADF test evaluate?
   b. If the time series is non-stationary, apply differencing to remove trend components. How
   do you interpret the results of the ADF test after differencing?
   c. Decompose the time series into trend, seasonality, and residual components. What key
   observations can be made from the decomposition?
   d. What are the possible transformations that can be applied to make a non-stationary time
   series stationary?


6. Autocorrelation and Partial Autocorrelation
   a. Compute and plot the Autocorrelation Function (ACF) of the dataset. What does a slow
   decay in the ACF plot indicate?
   b. Compute and plot the Partial Autocorrelation Function (PACF). How can the PACF be
   used to determine the order of an AR model?
   c. Compare the ACF and PACF plots. What conclusions can you draw regarding the nature
   of the time series?
