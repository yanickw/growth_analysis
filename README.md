# Growth Analysis
*GROWTH ANALYSIS* analyzes stock traded companies financials and user data to identify trends and advise in order to help company's growth using a time series and Prophet for forecast.

## Requirements

This application was writen in Jupyter Lab 3.3.2 using Python 3.9.7

**Operating System:**

-   Window 10 (or higher) using Gitbash.
-   MacOS 10.14 (or higher) using a terminal.
-   Linux Ubuntu 22.04 (or higher) using a terminal.

**Will need to be installed:**

_jupyter lab_  3.3.2

```
$ pip install jupyterlab
```

_pandas_  1.4.2
```
$ pip install pandas
```

_numpy_  1.22.3

```
$ pip install numpy
```


hvPlot 0.8.0 

```
$ pip install hvplot
```

prophet

```
$ conda install -c conda-forge prophet

```

----------

## Installation

To install the application you will need to clone the GitHub repository.

```
$ git clone https://github.com/yanickw/growth_analysis

```

----------

## Get Started

Using the `forecasting_net_prophet` Notebook:

Open a gitbash, navigate to your github cloned repositery. Start **Jupyter Lab**

```
$ jupyter lab
```

### 1. Find Patterns in Search Traffic

1. To get started load the .csv file containing the internet search trends and vizualise it.
2. Compare the latest month with the median across all months.

Find out if there was an increase or decrease in traffic.

### 2. Mine the Search Traffic Data for Seasonality.

1. Group the hourly search data to plot the average traffic by the day of the week.
2. Visualize this traffic as a heatmap to find out the concentration of searches within a day to focus your marketing efforts.
3. Group the search data by the week of the year to see the sale trend by seasons or holidays for sales and marketing efforts.

### 3. Relate the Search Traffic to Stock Price Patterns

1. Import stock closing cost data and concatenate with search trend.
2. Visualize both to find common trend by comparing curves.
3. Construct a correlation table to find predictable relationship.

### 4. Create a Time Series Model using Prophet
1. Set up the internet search data for a Prophet forecasting model.
2. Estimate the model and plot the forecast
3. Plot the individual time series components of the model using a plot components to visualize trend, weekly, yearly and daily charts.

### 5. Forecast Revenue by Using Time Series Models
1. Create daily historical sales Dataframe from daily sales data
2. Interpret the model output to identify any seasonal patterns in the company's revenue.
3. Produce a sales forecast for a set time period using the yhat_upper, yhat_lower and yhat.


----------

## Contributors

This application originated from a Berkeley Bootcamp.

For any inquieries, feedbacks or comments about this project please email me at  [yanickw@gmail.com](mailto:yanickw@gmail.com)

I can also be reached on  [LinkedIn](https://www.linkedin.com/in/yanickwilisky/)  or  [Twitter](https://twitter.com/yanickwilisky).

----------

## License

MIT License

Copyright (c) 2022 Yanick Wilisky

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.