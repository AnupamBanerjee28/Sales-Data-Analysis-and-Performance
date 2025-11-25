# Sales-Data-Analysis-and-Performance

## **1. Project Overview**

This project involves an end-to-end business intelligence solution to analyze sales performance across the Indian market. The primary goal was to transform raw transactional data into actionable insights via a dynamic and interactive dashboard, enabling stakeholders to monitor key performance indicators (KPIs) and identify growth opportunities or areas for cost optimization.

## **2. Key Features and Insights**

**•	KPI Monitoring:** Real-time tracking of Total Sales, Gross Profit, Discount Rate, and Units Sold.

**•	Geographic Analysis:** Visualizing sales distribution and performance segmented by Region and City.

**•	Product/Category Deep Dive:** Analyzing the profitability and sales volume across different product categories (e.g., Electronics, Clothing, Furniture) and individual product names.

**•	Channel and Payment Analysis:** Identifying top-performing sales channels (Online vs. Retail) and preferred customer payment methods.

**•	Time-Series Analysis:** Tracking sales and profit trends over time to identify seasonality and growth rates.

## **3. Skills and Tools Used**

**Category**	                 **Tool / Skill**	                              **Description**

Business Intelligence    	Power BI (.pbix)	          Primary tool used for data modeling,                                                           visualization, and dashboard deployment.

Data Source	              CSV (sales_data_india.csv)	         Raw transactional data                                                                     containing all sales records.

Data Modeling	         DAX (Data Analysis Expressions)	  Used to create calculated measures                                                               (e.g., Profit Margin %, Discount                                                               Impact, YTD Sales) and complex                                                                               column logic.

Data Processing	        Power Query (M Language)	            Utilized for Extract, Transform,                                                                   and Load (ETL) processes,                                                                     including data type                                                                                 conversion, column                                                                                   standardization,                                                                               and null value                                                                                         handling.

Analysis	        Sales Analytics, Profitability Analysis	          Interpreting sales metrics                                                                             to provide clear,                                                                               data-driven                                                                                     recommendations.

## **4. Process Workflow**

**1.	Data Ingestion (ETL):** Loaded the sales_data_india.csv into Power BI using Power Query. Applied transformations to clean date formats, handle currency consistency, and derive necessary calculated columns.

**2.	Data Modeling:** Established relationships between different tables (if other dimension tables were used, though the current model uses a single fact table structure) and ensured the model schema was optimized for performance.

**3.	DAX Development:** Created essential measures like Total Sales, Total Profit, Gross Margin %, and Repeat Customer Rate.

**4.	Visualization Design:** Designed a visually appealing and responsive dashboard layout, utilizing appropriate chart types (e.g., bar charts for category comparison, cards for KPIs, map visuals for regional data) to tell the data story effectively.

**5.	Validation:** Cross-verified dashboard figures against source data to ensure accuracy and consistency.


![Image Alt](image_url)
