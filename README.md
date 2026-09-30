
Weather Data Analysis

Exploratory data analysis (EDA) of hourly weather data using Python, NumPy and Pandas.

About the Project

This project analyses hourly weather records for the year 2012 (8,784 rows). It covers data inspection, unique-value counts, filtering with single and multiple conditions, and group-wise statistics to understand how weather conditions relate to temperature, humidity, wind speed, visibility and pressure.

Dataset

File: Weather_Data.csv (8,784 rows, 8 columns, no missing values)

Column	Description
Date/Time	Date and hour of the record
Temp_C	Temperature (°C)
Dew Point Temp_C	Dew point temperature (°C)
Rel Hum_%	Relative humidity (%)
Wind Speed_km/h	Wind speed (km/h)
Visibility_km	Visibility (km)
Press_kPa	Atmospheric pressure (kPa)
Weather	Weather condition (Clear, Fog, Snow, etc.)
What the Notebook Covers

Basic exploration

Viewing the head, shape, index, columns, data types and info()
Unique values and their counts using unique(), nunique() and value_counts()
Checking null values with isnull() and notnull()
Renaming a column (Weather to Weather Condition)

Statistics

Mean of visibility, standard deviation of pressure, variance of relative humidity

Filtering

Rows where the weather is exactly "Clear", "Snow" or "Fog"
Partial matching with str.contains()
Wind speed exactly 4 km/h
Multiple conditions using & and | (for example, wind speed above 24 and visibility 25)

Group-wise analysis (groupby)

get_group() for a single weather condition
Mean, minimum and maximum of each column for every weather condition
Tech Stack
Python
NumPy
Pandas
Jupyter Notebook
Project Structure
Weather-Data-Analysis/
├── WeatherData.ipynb    # Analysis notebook
├── Weather_Data.csv     # Dataset
└── README.md
Future Improvements
Add visualizations with Matplotlib and Seaborn (temperature trends, weather condition counts)
Analyse patterns by month and season
Build a Power BI dashboard for the dataset
Author

Sahildev0013 - GitHub
