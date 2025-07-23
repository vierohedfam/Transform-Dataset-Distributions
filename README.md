# Cost of Living
The project performs a series of transformations on the 'cost_of_living' dataset to change the distribution of its data.

## Dataset Used
- <a href="https://github.com/vierohedfam/Transform-Dataset-Distributions/blob/main/cost_of_living%20%5BMConverter.eu%5D.csv"> Superstore Data</a>

## Process
### Dataset Distribution
- Creating a Histogram of 'cost_index', 'monthly_income', 'purchasing_power_index'
### Normalize Data
- Selecting Numeric Columns
- Filling Missing Values
- Applying Normalization
- Visualizing Normalized Data
### Standardize Data
- Selecting Numeric Columns (re)
- Filling Missing Values.
- Applying Standardization
- Visualizing Standardized Data
### Transforming Skewed Data - Log Transformation
- Initial Visualization of 'monthly_income'
- Checking Initial Skewness of 'monthly_income'
- Visualization and Skewness After Log Transformation of 'monthly_income'
- Visualization and Skewness After Log Transformation of 'cost_index'
### Transforming Skewed Data - Box-Cox Transformation
- Applying Box-Cox Transformation of 'monthly_income'
- Visualization and Skewness After Box-Cox Transformation of 'monthly_income'
### Binning Individual Variables
- Displaying Descriptive Statistics for the Dataset
- Defining Boundaries and Bin Labels for 'cost_index'
- Applying Binning for 'cost_index'
- Defining Boundaries and Bin Labels for 'monthly_income'
- Applying Binning for 'monthly_income'
- Displaying the DataFrame with the New Binned Column

## Dashboard
![Cost Living](https://github.com/user-attachments/assets/d3cc0391-c602-485b-ac57-a89575355840)
