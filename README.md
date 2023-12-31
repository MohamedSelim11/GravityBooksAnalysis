# Gravity-Books-SSAS-Project
The Gravity Books SSAS (SQL Server Analysis Services) project extends the capabilities of the Gravity Books Data Warehouse by providing a powerful analytical layer. 
It leverages SSAS Tabular mode for data modeling and serves as the foundation for creating interactive reports and dashboards using Power Pivot and Power BI.

# Project Components
SSAS Tabular Model: The analytical model used to explore and analyze data. Power Pivot: An Excel add-in for creating reports and data analysis. 
Power BI: A business analytics tool for creating interactive dashboards and reports.

# SSAS Tabular Model
![Screenshot (150)](https://github.com/MohamedSelim11/GravityBooksAnalysis/assets/127447294/3c5e27b5-aa2e-487d-beea-83d2d87a88fe)

The SSAS Tabular model is built on top of the Gravity Books Data Warehouse and is responsible for providing a user-friendly and high-performance way to explore data.

# Data Sources
The data sources for the SSAS Tabular model are the following:
Data Warehouse: The denormalized data from the Gravity Books Data Warehouse.

# Data Model
The SSAS Tabular model includes the following key components:
Tables: The denormalized tables from the data warehouse, including the Book Dimension, Customer Dimension, and Date Dimension.

Relationships: Relationships defined between tables to enable drill-down and data exploration.

Measures: Calculated measures that provide aggregate data for analysis, such as total sales, average order quantity, etc.

# Power Pivot Reports
![Screenshot (154)](https://github.com/MohamedSelim11/GravityBooksAnalysis/assets/127447294/2f924ced-f35b-415e-baee-f38874edebe1)

![Screenshot (155)](https://github.com/MohamedSelim11/GravityBooksAnalysis/assets/127447294/518ad0b3-b15a-4e08-b71a-37782e25ed2c)

![Screenshot (157)](https://github.com/MohamedSelim11/GravityBooksAnalysis/assets/127447294/9ff8dfe2-f798-42b2-9b3e-2e13f79460fd)


Power Pivot is used to create interactive reports within Microsoft Excel. 
These reports leverage the SSAS Tabular model to provide a user-friendly interface for data analysis.

How to Use Power Pivot Open Microsoft Excel.
Go to the Power Pivot tab. Import data from the SSAS Tabular model. 
Create PivotTables, PivotCharts, and other visualizations using the imported data. Explore and analyze data interactively.

# Power BI Dashboards
![Screenshot (152)](https://github.com/MohamedSelim11/GravityBooksAnalysis/assets/127447294/229b92f5-4ef9-4e6a-8a1f-c356b4192fda)

Power BI is employed for creating dynamic and visually appealing dashboards that enable data-driven decision-making.

# Data Connection
Power BI connects to the SSAS Tabular model as a data source.

# Creating Dashboards
Open Power BI Desktop. Connect to the SSAS Tabular model. Design and create dashboards by adding visualizations such as charts, graphs, and tables. Publish the dashboard to the Power BI service for sharing and collaboration. Conclusion The Gravity Books SSAS project, integrated with Power Pivot and Power BI, empowers users to extract valuable insights from the data warehouse. It offers interactive reports and dashboards, making it easier to analyze the bookstore's operations, customer behavior, and book sales trends. Users can access this information in a user-friendly, self-service manner.
