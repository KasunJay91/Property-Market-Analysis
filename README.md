Property Market Analysis Project
![Summary](https://github.com/user-attachments/assets/15bb793e-00e4-4443-b2f3-db8717f9a402)

Overview
As a BI Analyst, I successfully delivered a comprehensive Property Market Analysis Dashboard for a real estate company to provide actionable insights into rental values, housing values, school distributions, transport accessibility, and crime rates across key regions in Australia. This project aimed to empower the client with data-driven decision-making tools to optimise their property management strategies and provide value-added services to their customers.
The project involved designing an efficient ETL pipeline for automated data loading into a data warehouse, building a scalable data model, and creating interactive dashboards using Power BI. Advanced DAX calculations and drill-through capabilities were implemented to meet stakeholder requirements for in-depth analysis and reporting.

Project Environment and Workflow
•	Environment: SSMS and Power BI.
•	Data Source: Data collected from external sources, including rental value datasets, housing value statistics, school databases, transport logs, and crime records in Excel format.
•	ETL Pipeline: Designed and implemented an automated ETL pipeline using SSIS to extract, transform, and load data into the data warehouse.
•	Data Modelling: Built a Snowflake Schema with staging, dimension, and fact tables for optimised querying and reporting.
•	Visualization: Developed interactive Power BI dashboards with advanced analytics and drill-through navigation.
________________________________________
Project Requirements and Deliverables
1.	Stakeholder Requirements:
o	Comprehensive insights into average rental and housing values by state, city, and suburb.
o	Analysis of school distributions and types, transport station locations, and crime incident trends.
o	Interactive and intuitive dashboards with drill-through capabilities for detailed regional and property-specific insights.
o	SSRS links to detailed paginated reports for external sharing.
2.	Data Integration:
o	Extracted data from multiple Excel files covering states (NSW, VIC, SA).
o	Consolidated data into Load tables, followed by staging and dimension tables using SSIS.
o	Applied derived column transformations to create business keys, such as State_Code_Suburb_Merge, for relational joins.
o	Automated ETL workflows to ensure data integrity and consistency during regular updates.
3.	Data Modelling:
o	Designed a Snowflake Schema with:
	Dimension Tables: Geography, Transport, School, Property Categories.
	Fact Tables: Rental Values, Housing Values, Crime Data.
o	Established relationships between tables for seamless analysis.
o	Enhanced the data model to support dynamic queries and scalability.
4.	Advanced Analytics and Visualisation:
o	Developed calculated measures using DAX, such as average rental and housing values, distribution percentages, and incident rates.
o	Created drill-through capabilities to explore suburb-level insights, rental and housing trends, and crime incident distributions.
o	Enabled interactive filtering options by state, city, suburb, and property categories.
o	Integrated heatmaps and geospatial visuals for enhanced storytelling.
5.	Reporting:
o	Designed detailed dashboards in Power BI.
