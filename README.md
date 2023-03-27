# BeverCapstoneProject
Analysis of Housing Prices Using Machine Learning

Author: Samantha J. Bever

Date: March 14, 2023


## Data Set
Link to data set: https://vincentarelbundock.github.io/Rdatasets/articles/data.html

Using data set called "Housing prices in Ames, Iowa"

## Report
Link to OverLeaf report: https://www.overleaf.com/read/yvgfrmwhpsph

## File Descriptions
Ames_Housing_Original.csv = the original csv file from data source (listed above)
Ames_Housing_WorkingFile.xlsx = Excel file used to clean the original data into a usable format for analysis (see details below about cleaning process)
Ames_Housing_Cleaned.csv = After data was cleaned in Ames_Housing_WorkingFile.xlsx, I moved the cleaned data to this csv file
BeverCapstoneProject.ipynb = Python Notebook used for statistics, visualizations, and more data cleaning

# Excel Working File
## Excel Cleaning Process
1.	Removed the columns I won’t be using.
2.	Filtered my data set down to only residential property sales.
3.	Replaced exterior quality, exterior condition, and kitchen quality values with a rating scale of 1-5 to match a similar scale used for interior quality and condition. Originally, these were labeled as Ex, Gd, TA, Fa, Po for Excellent, Good, Typical/Average, Fair, and Poor.
4.	Replaced abbreviated neighborhood names with their full names.
5.	Removed the 1 duplicate row found in data set.

## Excel Visualizations
### Count of Sales Per Zone
Using the full, original data set, I created a pivot chart to see how many sales there were per zone type. After seeing this, I narrowed the scope of this project down to just residential property sales.

### Count of Sales Per Neighborhood
Using the cleaned data, I created a pivot chart (pie) to see how many sales there were per neighborhood. This shows us which markets were the most active during this time frame.

### Average Price Per Neighborhood
Using the cleaned data, I created a pivot chart (bar) to see what the average sale price was per neighborhood.

# Python Notebook
1. Review Data & Statistics (loaded cleaned csv file into Python notebook)
2. Vizualizations & Finding Outliers
3. Remove Outliers & Look at Distributions Without Outliers
4. Visualizations & Correlations




