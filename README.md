# Data-Analysis-of-Building-Energy-Benchmarking-Data
Course: DATA 601 Instructor: Syed Tauhid Ullah Shah  <div>
Objective: Analyze the City of Calgary’s Building Energy Benchmarking dataset using Python, Regex, Pandas, NumPy, and Matplotlib. Tasks include data cleaning, regex extraction, aggregation, outlier detection, and visualization.
<div>
METHODOLOGY<br>
1. Data Cleaning and Preprocessing<br>
  
  - Removed columns more than 40% of missing values.<br>
  - Converted text-based numeric columns to digit formt using Regex.<br>
  - Postal codes of Canada has been standardized.<br>
  - Outliers in Total Greenhouse gas emissions using the IQR method.<br>
</div>
<div>
2. Regex in Data Cleaning and Extraction <br>

  - Extracting numeric values from text-based columns.<br>
  - Removing unwanted characters like commas,spaces.<br>
  - Postal code standardizing, converted them to uppercase, removed non-numeric and special characters and the formatted.<br>
 </div>
 <div>
3. Data Analysis<br>
   
   - Visualization of top energy-consuming and highest GHG-emitting properties.<br>
   - Correlation analysis between building size, energy use, and emissions.<br>
   - Conducted statistical,T-tests to compare ENERGY STAR Scores between different property types.<br>
    
</div>
<div>
CHALLENGES FACED<br>
  
  - High amount of mssing values in some columns.<br>
  - Inconsistent data formats due to the values inside the column.<br>
  - Highly skewed distributions amoung the columns.<br>
</div>
<div>
INSIGHTS <br>
  
  - Strong correlation (0.72) exists between property size and total energy consumption.<br>
  - Greenhouse gas emission increased from 2021 to 2023.<br>
  - Large properties are not using energy inefficiently.<br>
  - Statistically significant difference in ENERGY STAR Scores exists between offices and ice rinks.<br>
</div>



