
## 1. Data Preparation and Modeling

### 1.1 Data Preparation

1. **Connect to Data Source:** Obtain the 'Fact Company sales_2017 CSV' file.
2. **Clean, Transform, and Load Data:**
   - Shape and Transform Tables: Remove unwanted columns, blank rows, and set headers.
   - Rename Columns: Create user-friendly naming conventions.
   - Resolve Inconsistencies and Nulls: Replace values, change data types, remove duplicates, and filter blank values.
   - Evaluate and Transform Column Data Types: Detect correct data types and format columns accordingly.
   - Append Tables: Add 'Sales 2018' and 'Sales 2019' tables and apply transformations.
   - Merge Tables: Merge 'Sales details' table using the common column 'order ID'.
   - Pivot and Unpivot Table: Unpivot 'Cost table' columns and pivot 'Type' column with cost amount.
   - Conditional Column: Add 'Month number' column with month numbers.
   - Data Profiling: Understand data structure, anomalies, and value distribution.
   - Files from Folders: Access data from folders.

### 1.2 Data Modeling

1. **Creating Relationships:** Establish relationships between tables in the Model View focusing on the fact and dimension tables.
2. **Common Date Table:** Add a date dimension table to analyze data precisely.
3. **Setting Hierarchies:** Set hierarchies for date columns to facilitate analysis.
4. **Data Granularity:** Adjust granularity for proper data relationships.
5. **Model Calculations with DAX:** Utilize DAX for calculated columns, measures, iterator functions, and time intelligence.
6. **Optimize Model Performance:** Ensure efficient DAX measures, small model size, and low cardinality.

## 2. Visualize and Analyze the Data

### 2.1 Visualization Techniques

1. **Area Chart:** Display revenue across product categories.
2. **Combo Chart and Treemap:** Analyze correlation between sales and revenue.
3. **Card and Gauge Visual:** Present important metrics and set target values.
4. **Custom Tooltips:** Enhance interactivity with custom tooltips.
5. **Slicing and Filtering:** Apply quick filters using slicer visuals.
6. **Sync Slicers:** Synchronize slicer visuals across multiple pages.
7. **Drillthrough & Drilldowns:** Dive into details and hierarchies for deeper analysis.
8. **Adding Bookmark and Buttons:** Navigate between pages and apply bookmarked views.
9. **Page Navigation:** Link pages for seamless navigation.
10. **Edit Interactions:** Make visuals interactive by adjusting interactions.
11. **Analyze Feature:** Utilize built-in features to understand data distributions.
12. **Identify Outliers:** Identify and label outliers using scatter plots and DAX expressions.
13. **Create Groups, Bins, and Clusters:** Organize data for analysis.
14. **Forecast Feature:** Predict future trends using forecasting tools.
