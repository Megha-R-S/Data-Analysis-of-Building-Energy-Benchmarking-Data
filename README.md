# Data-Analysis-of-Building-Energy-Benchmarking-Data
Course: DATA 601 Instructor: Syed Tauhid Ullah Shah  <div>
Objective: Analyze the City of Calgary’s Building Energy Benchmarking dataset using Python, Regex, Pandas, NumPy, and Matplotlib. Tasks include data cleaning, regex extraction, aggregation, outlier detection, and visualization.
<div>
## Methodology
1. Data Cleaning and Preprocessing
  - Removed columns more than 40% of missing values.
  - Converted text-based numeric columns to digit formt using Regex.
  - Postal codes of Canada has been standardized.
  - Outliers in Total Greenhouse gas emissions using the IQR method.
2. Regex in Data Cleaning and Extraction 
  - Extracting numeric values from text-based columns.
  - Removing unwanted characters like commas,spaces.
  - Postal code standardizing, converted them to uppercase, removed non-numeric and special characters and the formatted.
3. Data Analysis
   - Visualization of top energy-consuming and highest GHG-emitting properties.
  - Correlation analysis between building size, energy use, and emissions.
  - Conducted statistical,T-tests to compare ENERGY STAR Scores between different property types.
    
</div>
<div>
## Challenges Faced
  - High amount of mssing values in some columns.
  - Inconsistent data formats due to the values inside the column.
  - Highly skewed distributions amoung the columns.
## Insights
  - Strong correlation (0.72) exists between property size and total energy consumption.
  - Greenhouse gas emission increased from 2021 to 2023.
  - Large properties are not using energy inefficiently.
  - Statistically significant difference in ENERGY STAR Scores exists between offices and ice rinks.
</div>
