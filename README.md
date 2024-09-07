# Data Cleaning and Exploration Project

## Project Overview
This project involves cleaning and exploring a dataset related to sales data. The primary goal is to extract insights and answer key business questions through data manipulation and visualization using Python libraries, specifically pandas and matplotlib.

## Key Tasks Completed
- **Data Cleaning**:
  - Dropped NaN values from the DataFrame.
  - Removed rows based on specific conditions.
  - Changed the types of columns (using `to_numeric`, `to_datetime`, and `astype`).

- **Data Exploration**:
  - Answered five high-level business questions:
    1. What was the best month for sales? How much was earned that month?
    2. What city sold the most products?
    3. What time should we display advertisements to maximize the likelihood of customer purchases?
    4. What products are most often sold together?
    5. What product sold the most, and why do you think it sold the most?
  
- **Data Manipulation Techniques**:
  - Concatenated multiple CSV files into a single DataFrame.
  - Added new columns for enhanced analysis.
  - Parsed cells as strings to create new columns using `.str`.
  - Employed the `.apply()` method for data transformations.
  - Utilized `groupby` to perform aggregate analysis.

- **Visualization**:
  - Plotted bar charts and line graphs to visualize results.
  - Labeled graphs for clarity and better interpretation of findings.

## Technologies Used
- Python
- pandas
- matplotlib

## How to Run the Project
1. Clone the repository.
2. Ensure you have the required libraries installed:
   ```bash
   pip install pandas matplotlib
