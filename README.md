# Power-Bi
Repostry where i post the visualitaion of the data ssets using Power Bi
# 1. Perform Basic Data Cleaning
Remove Duplicates:

Go to Transform Data in Power BI.
In the query editor, select the columns where duplicates might exist, then click Remove Duplicates under the "Home" tab.
Handle Missing Values:

To remove null values: Use Remove Rows in the query editor.
To replace missing values: Select the column and use Replace Values.
Correct Data Types:

In the query editor, change the data type by selecting the column and using the Data Type dropdown.
Fix Outliers:

Filter or adjust extreme values (e.g., sales that are too high or low).
# 2. Segment the Visuals Using Country, Region, and Market
Create a Slicer for each of the categories Country, Region, and Market:
Go to Visualizations pane and select Slicer.
Drag the Country field into the slicer to allow stakeholders to filter by country.
Repeat for Region and Market.
This will allow filtering the data by Country, Region, or Market.

# 3. Analyze the Data by Visualizing the Percentage of Shipping Based on Ship Mode
Create a Pie Chart or Donut Chart:
Select Pie Chart or Donut Chart from the Visualizations pane.
Drag the Ship Mode field into the Legend.
Drag the Sales or Order Quantity field into the Values field.
This will show the percentage of shipping based on each ship mode.

# 4. Give the Report to See Sales Over the City, State, Region, and Market
Create Multiple Maps:

Add a Filled Map or Shape Map to represent sales geographically.
Drag the City field to Location and Sales to Value.
Repeat for State, Region, and Market.
Alternatively, create a Bar Chart or Table:

Create a Bar Chart for City, State, Region, and Market with Sales or Order Quantity in the Values field.
This will visualize sales across different cities, states, regions, and markets.

# 5. Create Tables for All the Visualizations
For each visualization, add a Table:
Select Table from the Visualizations pane.
Add the necessary fields for each table (e.g., City, Sales, Ship Mode).
Examples:
Sales by Region Table: Show Region, Sales, Quantity.
Ship Mode Breakdown Table: Show Ship Mode, Sales, Percentage.
Geographical Sales Table: Show City, State, Sales, Market, etc.
