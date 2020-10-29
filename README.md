# Accessing the Public Data API with Python (Jupyter Notebook & Pandas)

I've updated the [API Version 2.0 Python Sample Code](https://www.bls.gov/developers/api_python.htm), on the bls.gov site to use Pandas/Jupyter Notebooks. The older sample code uses prettytables to output text files which aren't very functional for further analysis. This reworked example is also designed to be more user friendly and explanatory for novices looking to utilize the bls public API.

The provided example requests data for two time series, [CUUR0000SA0 (Consumer Price Index)](https://data.bls.gov/timeseries/CUUR0000SA0?output_view=pct_1mth) and [SUUR0000SA0 (Chained Consumer Price Index for All Urban Consumers: All Items in U.S. City Average)](https://fred.stlouisfed.org/series/SUUR0000SA0), for the years 2011 through 2014.

### Finding other time series data codes:
Information on codes for other time series data can be found [here](https://www.bls.gov/help/hlpforma.htm#AP), however it can be fairly complicated. An easier approach is to find the time series you're looking for on https://fred.stlouisfed.org/, then note the code at the end of the URL. (ie: https://fred.stlouisfed.org/series/CUUR0000SA0L2).
