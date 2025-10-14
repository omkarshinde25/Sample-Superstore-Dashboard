# Data Visualization Project: Sample Superstore

## Project Overview
This project demonstrates a data visualization solution using the Sample Superstore dataset.  
The data was extracted from an Excel workbook, cleaned through an ETL (Extract, Transform, Load) process, and then loaded into Power BI for visualization.  
The analysis provides insights into regional sales performance, product category trends, and profitability across time and regions.

## Dataset Information
File Type: Excel Workbook (.xlsx)  
Records: 9994 rows  
Columns: 21 fields  
Fields Included: Order ID, Order Date, Ship Mode, Customer Name, Segment, Country, City, State, Postal Code, Region, Category, Sub-Category, Sales, Quantity, Discount, Profit, and others  
Source: Public dataset commonly used for analytics and business intelligence projects

## Data Preparation and ETL Process
1. **Extract:** The dataset was imported from the Excel file into Power BI.  
2. **Transform:** Data cleaning was performed using Power Query in Power BI, which included:  
   - Removing 42 duplicates rows and blank values  
   - Standardizing date formats and column names  
   - Correcting data types for numerical and categorical fields  
   - Filtering unnecessary columns for performance optimization  
3. **Load:** The cleaned and structured data was loaded into the Power BI model for analysis and dashboard creation.

## Technologies Used
Data Source: Microsoft Excel  
ETL and Transformation: Power BI Power Query  
Visualization and Reporting: Microsoft Power BI  

## Visualization Highlights and Insights

### Filled Map Chart  
**Purpose:** Visualize regional distribution across the United States using color-coded areas.  
<img src="https://github.com/omkarshinde25/Data-Visualization-Project-Sample-Superstore/blob/main/Chart%20Photos/Filled%20Map%20Chart.png" width="800"> <br>

**Insights:**  
- Divides the U.S. into four regions: Central, East, South, and West.  
- Provides a clear geographical overview of business operations or sales territories.  
- Useful for region-based performance comparisons.

---

  ### Gauge Chart  
**Purpose:** Compare actual sales and profit to target values.  
<img src="https://github.com/omkarshinde25/Data-Visualization-Project-Sample-Superstore/blob/main/Chart%20Photos/Guage%20Chart.png" width="800"> <br>

**Insights:**  
- **Target Sales:** 2.30M of 4.59M achieved.  
- **Target Profit:** 286K of 572K achieved.  
- Useful for monitoring KPIs and progress toward goals.  

---

### Line Chart  
**Purpose:** Display sales trends by region from 2014–2017.  
<img src="https://github.com/omkarshinde25/Data-Visualization-Project-Sample-Superstore/blob/main/Chart%20Photos/Line%20Chart.png" width="800"> <br>

**Insights:**  
- West region shows strong growth trend.  
- Central region fluctuates but improves by 2017.  
- Helps forecast regional sales patterns.  

---

###  Scatter Chart  
**Purpose:** Show relationship between Sales and Profit by category.  
<img src="https://github.com/omkarshinde25/Data-Visualization-Project-Sample-Superstore/blob/main/Chart%20Photos/Scatter%20Chart.png" width="800"> <br>

**Insights:**  
- Technology yields high profit for given sales.  
- Furniture and Office Supplies lag behind.  
- Highlights profitability efficiency by category.  

---

### Map with Pie Chart  
**Purpose:** Combine location-based insights with category-wise contribution visualization.  
<img src="https://github.com/omkarshinde25/Data-Visualization-Project-Sample-Superstore/blob/main/Chart%20Photos/Map%20with%20Pie%20Chart.png" width="800"> <br>

**Insights:**  
- Each city’s pie represents sales share across Furniture, Office Supplies, and Technology.  
- Larger circles indicate higher total sales volume.  
- Helps identify which categories dominate in specific regions.  

---

### Pie and Donut Charts  
Purpose: Show proportional sales contribution by region and category  
<img src="https://github.com/omkarshinde25/Data-Visualization-Project-Sample-Superstore/blob/main/Chart%20Photos/Pie%20Chart.png" width="800"> <br>
<img src="https://github.com/omkarshinde25/Data-Visualization-Project-Sample-Superstore/blob/main/Chart%20Photos/Donut%20Chart.png" width="800"> <br>

Analysis:  
1. The West region contributes the highest percentage of overall sales and profit.  
2. Technology holds the largest share among all product categories.  
3. Furniture records high sales but lower profits due to discounts and higher shipping costs.

---

### UK Population Analysis by Region – 2024  
**Purpose:** Show population distribution across UK regions for 2024.  
<img src="https://github.com/omkarshinde25/Data-Visualization-Project-Sample-Superstore/blob/main/Chart%20Photos/UK%20Population%20Analysis%20by%20Region%20%E2%80%93%202024.png" width="800"> <br>

**Insights:**  
- Highlights population clusters in major cities like London, Birmingham, and Manchester.  
- Each dot’s size and color represent the 2024 population estimate.  
- Useful for demographic, economic, or market analysis across the UK.  

---

### Stacked Column Chart  
Purpose: Show sales by sub-category across different regions  
<img src="https://github.com/omkarshinde25/Data-Visualization-Project-Sample-Superstore/blob/main/Chart%20Photos/Stacked%20Column%20Chart.png" width="800"> <br>

Analysis:  
1. Technology products such as Phones and Accessories contribute the highest sales across all regions.  
2. Office Supplies show moderate yet consistent performance across regions.  
3. Furniture sales vary significantly, with higher sales in the West compared to the Central region.

---

### Ribbon Chart  
Purpose: Display yearly sales trends across regions  
<img src="https://github.com/omkarshinde25/Data-Visualization-Project-Sample-Superstore/blob/main/Chart%20Photos/Ribbon%20Chart.png" width="800"> <br>

Analysis:  
1. The West region maintains a leading position in total sales across multiple years.  
2. The East region shows consistent growth, reflecting expanding market reach.  
3. The Central region experiences fluctuations, indicating unstable sales trends.

---

### Map Chart  
Purpose: Visualize regional distribution of sales in the U.S.  
<img src="https://github.com/omkarshinde25/Data-Visualization-Project-Sample-Superstore/blob/main/Chart%20Photos/Map%20Chart.png" width="800"> <br>

Analysis:  
1. States such as California, New York, and Texas dominate in total sales volume.  
2. Western and Eastern states generate more revenue than Central and Southern regions.  
3. Underperforming regions highlight areas where marketing and distribution can be improved.

---

### Column Chart  
Purpose: Display sorted sales by sub-category  
<img src="https://github.com/omkarshinde25/Data-Visualization-Project-Sample-Superstore/blob/main/Chart%20Photos/Column%20Chart.png" width="800"> <br>

Analysis:  
1. Phones, Chairs, and Storage are the top-selling sub-categories.  
2. Low-performing items like Fasteners, Labels, and Envelopes have minimal sales contribution.  
3. The visualization helps identify top revenue-generating sub-categories for inventory planning.

---

### Funnel Chart  
Purpose: Illustrate hierarchical contribution to total sales  
<img src="https://github.com/omkarshinde25/Data-Visualization-Project-Sample-Superstore/blob/main/Chart%20Photos/Funnel%20Chart.png" width="800"> <br>

Analysis:  
1. Technology leads the funnel hierarchy, followed by Furniture and Office Supplies.  
2. Within Technology, Phones and Accessories dominate the total revenue share.  
3. The funnel helps track how each category contributes to the overall sales pipeline.

---

## Overall Dashboard Insights
1. The dataset contains 9994 records and 21 columns covering multiple dimensions of sales, region, and product data.  
2. West and East regions perform best in both sales and profitability, while Central lags behind.  
3. Technology is the most profitable category, whereas Furniture, despite high sales, has low profit margins.  
4. Yearly trends show overall business growth with seasonal variations.  
5. The dashboard supports drill-down, filters, and slicers for dynamic analysis by region, category, or time.

## Features
- Interactive Power BI dashboard with multiple chart types  
- Data cleaned and transformed using ETL in Power Query  
- Drill-down and filter functionalities for deeper insights  
- Geo-mapping for regional performance visualization  
- Analytical insights based on a dataset of 9994 records and 21 fields

## Getting Started
1. Download the Excel dataset (SampleSuperstore.xlsx).  
2. Open the Power BI report file (SampleSuperstore.pbix).  
3. The data will load automatically through Power BI after cleaning via the ETL process.  
4. Explore the dashboard using filters and slicers to view specific insights.

