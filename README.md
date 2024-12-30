# Sales Data Analysis Project

This project involves analyzing 12 months of electronics store sales data to answer key business questions. The dataset contains hundreds of thousands of purchases broken down by month, product type, cost, purchase address, and more.

## Overview

The analysis was performed using:
- **Python Pandas**: For data cleaning and analysis.
- **Python Matplotlib**: For data visualization.

## Data Cleaning

Before analysis, the data was cleaned to ensure accuracy and consistency. Tasks included:
1. Dropping `NaN` values from the DataFrame.
2. Removing rows based on specific conditions.
3. Changing column data types using methods such as `to_numeric`, `to_datetime`, and `astype`.

## Questions Answered

During the analysis, we explored five high-level business questions:
1. **What was the best month for sales? How much was earned that month?**
2. **What city sold the most product?**
3. **What time should we display advertisements to maximize the likelihood of customers buying products?**
4. **What products are most often sold together?**
5. **What product sold the most? Why do you think it sold the most?**

## Methods and Techniques

To answer these questions, we used various Python methods and techniques:
- **Concatenating multiple CSV files** to create a single DataFrame using `pd.concat`.
- **Adding new columns** to enhance the dataset.
- **Parsing strings in cells** to generate new columns with `.str`.
- Applying transformations and calculations using the `.apply()` method.
- Performing aggregate analysis with `groupby`.
- Visualizing data with bar charts and line graphs using **Matplotlib**.
- Labeling graphs for clarity and effective storytelling.

## Results

This analysis provided actionable insights such as:
- Identifying the most profitable month for sales.
- Pinpointing the city with the highest product sales.
- Determining the optimal time to display advertisements.
- Uncovering trends in products often purchased together.
- Highlighting the most sold product and understanding the reasons behind its success.

## How to Run

1. Install Python and Jupyter Notebook on your system.
2. Install the required libraries:
   ```bash
   pip install pandas matplotlib
