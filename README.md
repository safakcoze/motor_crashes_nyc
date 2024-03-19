# Analyse Motor Vehicle Crashes in New York City, USA

- [Introduction](#Introduction)
- [Python Libraries and Data Used](#Python-Libraries-and-Data-Used)
- [Motor Crashes by Year and Time of Day](#Motor-Crashes-by-Year-and-Time-of-Day)
- [Density Heatmap by Plotly](#Density-Heatmap-by-Plotly)

## Introduction

![Motor_Crashes](https://github.com/safakcoze/motor_crashes_nyc/assets/139701981/5bc94909-ccbe-418c-a6d4-b808f04c0a3d)

**Keywords**: *Motor Crashes, New York City, Urban Transportation, Open Source Data, Python, Data Analysis*

## Python Libraries and Data Used

List of python libraries used, version, and its purpose for the analysis.

| Library    |     Version | Purpose  |
|------------|-------------|----------|
| numpy      |     1.21.5  | array computing with Python|
| pandas     |     1.4.2   | data structures for data analysis and statistics|
| geopandas  |    0.14.1   | geographic pandas extensions|
|matplotlib| 3.5.1| Python plotting package|
|plotly| 5.6.0 |An open-source, interactive data visualization library for Python|

List the data sets used in the notebook. Specify sources. Indicate data formats for each input data set. Describe the most relevant columns/variables for the analysis per each input dataset.

| Dataset  |  Format | Source  | Description | Selected/used variables |
|-----------|---------|---------|-------------|------------------------ |
| [Motor Vehicle Collisions](https://data.cityofnewyork.us/browse?q=motor+vehicle) | CSV | [NYC Open Data](https://opendata.cityofnewyork.us/) | Motor Vehicle Collisions in New York, USA | `CRASH DATE`, `CRASH TIME`, `BOROUGH`|
| [Borough Boundaries](https://data.cityofnewyork.us/City-Government/Borough-Boundaries/tqmj-j8zm) | GeoJson | [NYC Open Data](https://opendata.cityofnewyork.us/) | Borough boundaries in NYC | `borough_name`, `geometry` |

## Motor Crashes by Year and Time of Day

![yearly_motor_crashes](https://github.com/safakcoze/motor_crashes_nyc/assets/139701981/314dc6cb-5516-4b30-8ff7-424f3feabf7b)

![hourly_motor_crashes](https://github.com/safakcoze/motor_crashes_nyc/assets/139701981/623bd5ef-a13d-4593-9fcd-c2c30df42fdf)

### Density Heatmap by Plotly

![plotly_hist](https://github.com/safakcoze/motor_crashes_nyc/assets/139701981/d19e9d5d-17df-483e-bd38-2c0a299c911a)

