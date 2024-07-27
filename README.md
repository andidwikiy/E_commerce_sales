# E_commerce_sales
#### Tasks
The code addresses two main tasks in analyzing an e-commerce sales dataset:

1. **Case #1: Product and Sales Analysis**
   - **Objective**: To provide an overview of the e-commerce sales performance by product category. This includes calculating the count of products, average review scores, total reviews, and monthly sales for each product category. 
   - **Steps**:
     - Import and extract the dataset from a ZIP file.
     - Load the data into a DataFrame.
     - Analyze and transform the data by grouping it by product categories.
     - Calculate product counts, average reviews, and total reviews for each category.
     - Aggregate monthly sales data and rename columns for clarity.
     - Merge the results into a comprehensive DataFrame and export it to an Excel file.
     - Visualize the data using bar graphs to show monthly sales trends by category.

2. **Case #2: Price Classification and Sales Visualization**
   - **Objective**: To classify products into price categories ('Regular', 'Middle', 'Luxury') and analyze how these classifications impact sales. 
   - **Steps**:
     - Classify products based on their price into 'Regular', 'Middle', and 'Luxury' categories using binning.
     - Count the number of items in each price classification for each product category.
     - Visualize the distribution of items in each price category with stacked bar charts.
     - Aggregate and visualize sales data according to the new price classifications, showing trends across months for each product category.
     - Filter and sort data for specific categories, such as 'Books', to examine detailed sales information.

#### Skills Demonstrated
- **Data Handling**: Efficiently managing and processing large datasets using `pandas`.
- **Data Aggregation and Transformation**: Grouping, summarizing, and transforming data to meet specific analysis needs.
- **Data Classification**: Using binning techniques to create meaningful categories based on numerical values.
- **Data Visualization**: Creating clear and informative visualizations with `seaborn` and `matplotlib` to represent trends and insights.
- **File Export**: Exporting processed data to Excel for further use or reporting.
- **Data Exploration**: Investigating and understanding data through summary statistics and initial visualizations.
