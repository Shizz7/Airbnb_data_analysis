# Airbnb_data_analysis
This project, encapsulated in main.ipynb, performs an in-depth analysis of Airbnb listing data, focusing on understanding various factors that influence rental prices. The notebook covers data loading, preprocessing, exploratory data analysis (EDA), and drawing conclusions based on the findings.

Features

1. Data Loading and Initial Inspection: Reads compressed_data.csv and displays initial rows and column information.

2. Missing Value Handling: Identifies and handles missing values, specifically by filling reviews per month with 0 and last review with the minimum date, and dropping rows with missing NAME or host name.

3. Irrelevant Column Removal: Drops columns like license and house_rules that are deemed unnecessary for the analysis.

4. Data Type Conversion: Cleans and converts price and service fee columns from string (with '$') to float.

5. Duplicate Removal: Ensures data quality by removing duplicate rows.

6. Exploratory Data Analysis (EDA):
 
 1.Visualizes the distribution of listings across different neighbourhood group and room type  categories.

 2. Analyzes the relationship between room type and price using box plots.

 3. Examines the distribution of prices to identify outliers and understand pricing patterns.

Installation

To run this notebook, you'll need the following Python libraries:

1. pandas
2. numpy
3. seaborn
4. matplotlib

Data Source

The analysis uses data from [compressed_data.csv](https://github.com/TheiScale/YouTube-Video-Notes/blob/main/Air%20bnb%20Project/compressed_data.csv.gz). This dataset appears to contain detailed information about Airbnb listings, including pricing, host details, location, and review metrics.

Conclusion

The analysis reveals insights into Airbnb pricing dynamics. Notably, while shared rooms exhibit a wide price spread, their median price can be surprisingly higher than private rooms and even entire homes/apartments, suggesting potential pricing inconsistencies or outliers within shared room listings. Overall, significant price variations exist across all room types, with high-value outliers present in every category.
