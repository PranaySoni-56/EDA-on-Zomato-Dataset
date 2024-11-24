# EDA-on-Zomato-Dataset
This project focuses on performing Exploratory Data Analysis (EDA) on the Zomato restaurant dataset to gain insights into various restaurant features, locations, ratings, and cuisines. The dataset includes details about restaurants, such as name, location, rating, cost for two people, cuisines, and more.
Steps Involved in EDA:
Data Loading and Inspection:
The dataset is first loaded using Pandas to inspect its structure. Key columns like Restaurant Name, Location, Cuisines, Rating, and Cost for Two are analyzed for missing values and data types.

Data Cleaning:

Handling Missing Values: Missing or null values are identified and dealt with through removal or imputation.
Data Type Conversion: Ensuring columns like Rating are in appropriate formats (e.g., float), and converting categorical data as needed.
Descriptive Statistics:
Summary statistics (mean, median, mode) are computed for numerical columns such as Cost for Two and Rating. This helps in understanding the distribution and central tendencies of the data.

Univariate Analysis:

Distribution of ratings, cost, and other numerical features are visualized using histograms and box plots.
Frequency distribution of categorical features (e.g., cuisines, location) is analyzed with bar charts.
Bivariate Analysis:
Relationships between features such as Rating vs Cost for Two are explored using scatter plots, and correlations are examined to understand any patterns or trends.

Geographical Analysis:
Restaurants are grouped based on locations, and insights such as restaurant density by region or average ratings per location are derived.

Key Insights from EDA:
Most restaurants have moderate to high ratings.
Popular cuisines and regions with a higher density of restaurants are identified.
A correlation between cost and rating can be explored.

This EDA helps to better understand customer preferences, restaurant distribution, and factors influencing restaurant ratings.
