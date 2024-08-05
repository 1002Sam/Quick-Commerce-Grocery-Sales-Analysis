# Quick-Commerce-Grocery-Sales-Analysis
The Project involves the analysis of grocery sales data from BlinkIT, India's Last Minute App, to derive insights and visualize key metrics using Power BI. The primary objective is to define key performance indicators (KPIs) and create interactive visualizations to solve impending business problem and derive actionable insights for strategic descision making to stakeholders. 

![BlinkIt_Dashboard](https://github.com/user-attachments/assets/6b9699c4-6e6e-48d9-9b0e-2d3cc3527e0c)


## Dataset Information:
The dataset contains fields such as Item Fat Content, Item Identifier, Item Type, Outlet Establishment Year, Outlet Identifier, Outlet Location Type, Outlet Size, Outlet Type, Item Visibility, Item Weight, Sales, and Rating.

## Data Cleaning and Preprocessing
1. Loading Data: Imported data into Power BI and utilized Power Query for data transformation.
2. Data Quality: Ensured 100% valid entries with no errors or empty cells.
3. Data Consistency: Standardized values in Item Fat Content (e.g., converting ‘LF’ and ‘low fat’ to ‘Low Fat’).
4. Handling Missing Values: Identified missing values in Item Weight (16%) and planned to replace them using the mean of weights of specific items.

## Dashboard Building
1. Text and Formatting: Added titles and formatted KPIs with appropriate measures, colors, currency, decimals, backgrounds, and images.
2. Visualizations:
a. Donut Chart: Sales by Item Fat Content with interactive metrics.
b. Clustered Bar Chart: Item Fat Content by Item Location by Metrics.
c. Stacked Bar Chart: Item Type vs Metrics.
d. Line Chart: Total Sales by Outlet Establishment Year.
e. Funnel Chart: Sales by Outlet Location.
f. Matrix Chart: All Metrics by Outlet Type.
g. Slicers: For filtering by Outlet Location, Outlet Size, and Item Type.

## Measures/DAX Calculations
### Defined the following KPIs using DAX: Total Sales, Average Sales, Number of Items, and Average Rating.

## Conclusion
The project successfully demonstrates the use of Power BI for data cleaning, preprocessing, and visualization. The interactive dashboard provides valuable insights into grocery sales, enabling better decision-making for stakeholders.
