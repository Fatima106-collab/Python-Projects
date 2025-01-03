# Project 1: 
# (Title: Customer Insights and Visualization ): https://github.com/Fatima106-collab/Python-Projects/blob/main/project%201Python.ipyn
* Description
This project explores and analyzes customer data using Python's Pandas and NumPy libraries. It includes advanced data manipulation techniques, the creation of pivot tables, and visualizations using Matplotlib and Seaborn. The goal is to extract meaningful insights, such as identifying patterns and trends in customer behavior based on their location.

* Key Features
    * Data Import and Exploration: Loaded the dataset from a CSV file with encoding handling.
    * Displayed key statistics using .head(), .info(), .tail(), and .describe().
    * Analyzed column values and their distributions.

* Data Transformation and Manipulation:
  *  Created pivot tables to summarize data by Country, City, and Rate using aggregation functions (sum, mean).
  *  Added new columns dynamically, such as Full name.
  *  Grouped data by Country and City to compute statistics.

* Data Cleaning: Handled missing values by dropping rows with null values.
* Data Visualization:
  *  Visualized customer distribution by City and Country using Matplotlib and Seaborn.
  *  Created bar plots for top 10 cities by customer count.
  *  Enhanced visualizations with custom titles, labels, and color palettes.
    
* Technologies Used
  * Python
  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn

* Dataset
Customers.csv: Contains customer information, including FirstName, LastName, City, Country, and Rate.

* Visual Outputs:
Pivot table summarizing customer rates by Country and City.
Bar charts representing customer distribution by cities and countries.
Top 10 cities visualized using Seaborn for better insights

# Project 2: 
# (Title: Advanced Customer Analysis): https://github.com/Fatima106-collab/Python-Projects/blob/main/Project%202%20Python.ipynb
* Description
This project focuses on analyzing customer data from the AdventureWorks dataset. It involves data exploration, cleaning, and filtering to uncover key insights about customers based on their education level and annual income. Additionally, it demonstrates the use of Python's visualization libraries to present the findings effectively.

* Key Features
  * Data Import and Exploration:
Loaded the dataset from a CSV file with encoding handling.
Explored the data structure using .info() and .head() to understand its contents.

* Data Cleaning and Transformation:
Converted the AnnualIncome column to numeric values for accurate analysis.
Filtered data to focus on specific criteria, such as customers with a Graduate Degree earning over $50,000.
Removed rows with missing values to ensure data integrity.

* Data Filtering:
Applied conditions to analyze subsets of data, such as filtering by education level and income thresholds.

* Data Visualization:
Used Matplotlib and Seaborn to visualize trends and patterns within the dataset.

* Technologies Used
  * Python
  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn

* Dataset
AdventureWorks_Customers.csv: Contains customer information, including FirstName, EducationLevel, and AnnualIncome.

* Key Insights :
  * Distribution and characteristics of customers based on their education levels.
  * Analysis of income levels, specifically targeting higher-earning customers with advanced education.

# Project 3: 
# Title: ( Weather Data Analysis with Pandas ): https://github.com/Fatima106-collab/Python-Projects/blob/main/Project%203.ipynb
* Description
This project focuses on analyzing a weather dataset using Python's Pandas library. It demonstrates data exploration, cleaning, and statistical analysis to extract meaningful insights. The project includes solving real-world data analysis questions and performing advanced data filtering and aggregation.

* Key Features
   * Data Exploration: Identified unique values in columns such as Weather and Wind Speed.
   * Displayed data counts, unique counts, and descriptive statistics.

* Data Cleaning and Transformation:
   * Renamed columns for clarity (e.g., Weather renamed to Weather Condition).
   * Checked for missing values and summarized the dataset’s completeness.

* Statistical Analysis:
  * Calculated statistical measures such as mean, standard deviation, and variance for key columns like Pressure and Relative Humidity.
  * Grouped data to analyze specific weather conditions and patterns.

* Data Filtering:
  * Extracted specific records based on conditions such as:
    * Weather being clear.
    * Wind Speed above 24 km/h and visibility at 25 km.
    * Visibility above 40 km or specific weather conditions like fog.

* Advanced Querying:
 * Answered practical queries including:
   * Instances where Weather is clear and Relative Humidity is greater than 50.
   *  Records with combined conditions on weather and visibility.

* Technologies Used
Python
Pandas

* Dataset
Weather DataSet.csv: Contains weather-related data, including Weather, Wind Speed_km/h, Visibility_km, Rel Hum_%, and Press_kPa.

* Key Insights
  * Extracted and analyzed instances of specific weather conditions like clear weather or fog.
  * Identified correlations between weather conditions, visibility, and humidity.
  * Demonstrated data manipulation techniques and insightful querying.

# Project 4: https://github.com/Fatima106-collab/Python-Projects/blob/main/Netflix.ipynb
# Title: ( Title: Netflix Data Analysis )
* Description
This project involves analyzing a Netflix dataset to uncover insights about TV shows and movies available on the platform. The analysis includes data cleaning, exploration, and answering key questions about Netflix's content library. Visualizations are also employed to represent trends effectively.

* Key Features
   * Data Exploration and Cleaning:
   *  Inspected the dataset for duplicates and null values.
   *  Removed duplicate entries to ensure data accuracy.
   *  Used Seaborn's heatmap to visualize null values in the dataset.

* Date Parsing and Transformation:
Converted Release_Date into a datetime format to extract meaningful time-based insights.

* Data Analysis and Filtering:
  * Answered questions like:
* "What is the show ID and director for 'House of Cards'?"
* "How many movies and TV shows were released each year?"
* "What are the top 10 directors contributing to Netflix's library?"
* "Which titles were TV shows released in India only?"
* "How many movies or shows feature Tom Cruise?"
Filtered records based on specific conditions like category, type, and country.

* Visualizations:
  * Created bar graphs to display:
* Number of TV shows and movies released by year.
* Distribution of content categories (e.g., movies vs. TV shows).
* Visualized data distributions and trends using Seaborn's count plots and Pandas plotting.

* Technologies Used
   *  Python
   *  Pandas
   *  Seaborn
   *  Matplotlib


# Project 5: https://github.com/Fatima106-collab/Python-Projects/blob/main/Netflix.ipynb
# Title: ( Title: Car Data Analysis )
* Description
This project explores and processes a dataset of cars using Python's Pandas library. It demonstrates key data analysis techniques, including cleaning, filtering, and transformation, to derive actionable insights and prepare data for further analysis.

* Key Features
* Data Exploration:
  * Loaded and reviewed the dataset's structure, size, and previewed records.
  * Checked for missing values across all columns.

* Data Cleaning:
 * Addressed missing values in the Cylinders column by replacing them with the mean value.

* Data Analysis:
  * Analyzed the frequency of car manufacturers (Make).

* Filtered records based on specific criteria:
    * Cars originating from Asia or Europe.
    * Cars with Weight greater than 4000.

* Data Transformation:
   * Applied a lambda function to simulate a hypothetical increase in city mileage (MPG_City) by adding 3 to each value.

* Technologies Used
    * Python
    * Pandas

































