# Eniac Electronics Discount Strategy Review
Skills gained: Data extraction and querying, Data analysis & visualization, Market research 

Languages & tools leveraged: Python's pandas (data cleaning & transforming), Matplotlib (visualization), Seaborn (Visualization), Regex (object pattern identification), Google slides (presentation)

## Situation ##
Eniac, a Spanish electronics retailer specializing in Apple products, is re-evaluating its discount strategy. The board and CEO believe the current discounts are too aggressive, leading to lower revenue. They aim to shift focus to high-quality products and compete in the high-priced product market rather than offering cheap products.

## Task ##
The task involves analyzing the discounts and revenues for Eniac's products using Python, specifically leveraging pandas for data manipulation and matplotlib and seaborn for visualization. The analysis will identify issues in the current discount strategy and provide recommendations for improvement.

## Action ##
The following steps were taken to analyze and visualize the data:

### Data Loading and Inspection: ###
Loaded the CSV files using pandas.
Inspected the data for nulls, missing values, incorrect data types, and duplicates.

### Data Cleaning: ###
Handled null values appropriately.
Corrected data types where necessary.
Removed duplicate entries.
Dropped columns with corrupt data.
Applied regular expressions to clean and standardize text data (e.g., product names, categories) and to extract useful information from strings, such as discount percentages or product codes embedded within descriptions.

### Data Merging: ###
Merged multiple tables to create a comprehensive dataset for analysis.

### Data Analysis and Visualization: ###
Conducted exploratory data analysis (EDA) to understand discount patterns and revenue impacts.
Created visualizations using matplotlib and seaborn to illustrate key insights.
Analyzed the relationship between discount rates and revenue generation.

### Recommendations: ###
Provided strategic recommendations on the discount strategy based on the visualizations and analysis.

## Result ##
The analysis and visualizations were used to brief the CEO on the following key points:

Current Discount Strategy: The discounts currently offered are indeed resulting in lower revenue generation.
Revenue vs. Discount: There is an inverse relationship between discount rates and revenue, suggesting that higher discounts do not necessarily lead to higher sales volumes.
Product Positioning: Shifting focus to high-quality, high-priced products aligns with the company's goal to compete in the premium market segment.

## Defining Strategies ##
### Discount Strategy ###
Keeping discounts offered to high-end products to minimum.
Diversifying product range.
Optimize marketing strategies especially during festive seasons.

### Data-Collection Strategy###
Implement robust data validation at the point of entry to avoid corrupt and invalid data.
Regularly audit the data for inconsistencies and rectify issues promptly.
Ensure proper data documentation and standardization to facilitate accurate analysis in the future.
