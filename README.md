# Customer Data Analysis

## Project Overview

This project focuses on exploring and analyzing customer data using **Python, Pandas, and NumPy**. The dataset contains demographic, financial, educational, and household information for over **18,000 customers**.

The analysis aims to understand customer characteristics, identify patterns, and prepare the dataset for further analysis and visualization.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Dataset

The dataset includes information such as:

* Customer ID
* First & Last Name
* Birth Date
* Gender
* Marital Status
* Email Address
* Annual Income
* Number of Children
* Education Level
* Occupation
* Home Ownership

## Data Analysis

The project includes:

* Dataset exploration and structure analysis
* Data cleaning and preparation
* Handling missing and invalid values
* Data type conversion
* Descriptive statistics
* Customer filtering based on specific criteria
* Analysis of education and income
* Exploratory Data Analysis (EDA)

## Example Analysis

One of the analysis scenarios focuses on identifying customers who have:

* **Graduate Degree education**
* **Annual Income of $50,000 or more**

This helps demonstrate how customer segments can be identified using multiple conditions.

#  Netflix Movies & TV Shows Data Analysis with Python

##  Project Overview
This project performs an end-to-end Exploratory Data Analysis (EDA) on the **Netflix Movies and TV Shows dataset** using Python. The primary goal is to clean the dataset, analyze trends, handle missing values, and answer key business and content questions using modern data analysis techniques.

---

##  Tools & Libraries Used
* **Python** 🐍
* **Pandas**: Data manipulation, cleaning, and time-series transformation.
* **Seaborn & Matplotlib**: Data visualization and missing values heatmaps.

---

##  Key Data Operations & Analyses
1. **Data Inspection & Exploration**: Checked dimensions, column data types, and total record counts.
2. **Data Cleaning**:
   * Identified and removed duplicate records to maintain data integrity.
   * Visualized missing data distribution (Directors, Cast, Country) using **Seaborn Heatmaps**.
3. **Feature Engineering**: Converted `Release_Date` to `datetime` objects to extract and analyze yearly trends.
4. **Business Insights & Querying**:
   * **Content Distribution**: Calculated the ratio of Movies vs. TV Shows.
   * **Temporal Trends**: Identified peak release years for Netflix content.
   * **Geographic Filtering**: Filtered specific regional content (e.g., TV Shows released in India).
   * **Director Insights**: Identified Top 10 directors with the highest contribution to Netflix.
   * **Actor Search**: Extracted specific movie records based on cast members (e.g., Tom Cruise).

---

##  Sample Visualizations & Insights
* **Peak Content Release**: Analyzed release trends over time.
* **Category Breakdown**: Evaluated the dominant category (Movies vs. TV Shows).

---

# Weather Conditions Analysis Using Python

## Project Overview

This project analyzes historical weather data using Python to explore weather conditions, temperature, humidity, wind speed, visibility, and atmospheric pressure.

The analysis focuses on understanding the distribution of different weather conditions and identifying patterns and relationships between weather variables.

---

## Project Objectives

The main objectives of this project are to:

* Explore and understand the weather dataset.
* Analyze different weather conditions.
* Identify unique wind speed values.
* Calculate descriptive statistics.
* Investigate visibility, humidity, and pressure.
* Filter records based on multiple conditions.
* Identify patterns across different weather variables.
* Extract meaningful insights from the data.

---

## Dataset

The dataset contains **8,784 hourly weather records** with **8 variables**:

| Column           | Description                      |
| ---------------- | -------------------------------- |
| Date/Time        | Date and time of the observation |
| Temp_C           | Temperature in Celsius           |
| Dew Point Temp_C | Dew point temperature            |
| Rel Hum_%        | Relative humidity                |
| Wind Speed_km/h  | Wind speed                       |
| Visibility_km    | Visibility distance              |
| Press_kPa        | Atmospheric pressure             |
| Weather          | Recorded weather condition       |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Data Exploration

The project includes several exploratory data analysis techniques:

### Dataset Structure

* Dataset shape
* Column names
* Data types
* Number of unique values
* Missing value detection
* Frequency analysis

### Weather Conditions Analysis

The dataset contains **50 different weather-condition labels**, including:

* Clear
* Mainly Clear
* Mostly Cloudy
* Cloudy
* Rain
* Snow
* Fog
* Thunderstorms
* Freezing Rain
* Drizzle

The most frequently recorded weather conditions were:

* Mainly Clear
* Mostly Cloudy
* Cloudy
* Clear

---

## Statistical Analysis

Several descriptive statistics were calculated, including:

* Mean Visibility
* Standard Deviation of Atmospheric Pressure
* Variance of Relative Humidity

For example, the average visibility in the dataset is approximately:

**27.66 km**

The standard deviation of atmospheric pressure is approximately:

**0.84 kPa**

---

## Data Filtering

The project also demonstrates how to filter data using multiple conditions.

Examples include:

* Weather conditions exactly equal to `Clear`
* Wind speed exactly equal to `4 km/h`
* Wind speed greater than `24 km/h`
* Visibility equal to `25 km`
* Weather condition equal to `Fog`
* Clear weather with relative humidity above `50%`
* Visibility above `40 km`

These operations demonstrate the use of Boolean indexing and conditional filtering in Pandas.

---

## Key Findings

Some of the initial findings from the analysis include:

* **Mainly Clear** was the most frequently recorded weather condition.
* **Clear** weather occurred **1,326 times**.
* **Fog** occurred **150 times** as an exact weather condition.
* The dataset contains **34 unique wind-speed values**.
* There are no missing values across the dataset.
* Average visibility was approximately **27.66 km**.
* The dataset contains multiple combined weather conditions such as `Rain,Fog`, `Snow,Fog`, and `Freezing Rain,Fog`.

---

## Future Improvements

To make the analysis more comprehensive, future improvements could include:

* Monthly and seasonal weather analysis.
* Temperature trend visualization.
* Correlation analysis between weather variables.
* Weather-condition distribution charts.
* Analysis of extreme weather conditions.
* Interactive dashboard using Power BI.
* Predictive modeling for weather conditions.

---

## Conclusion

This project demonstrates practical use of Python and Pandas for data exploration, statistical analysis, conditional filtering, and extracting insights from a real-world weather dataset.

It also provides a foundation for more advanced analysis and visualization of weather patterns.

