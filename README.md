# BI_360-PowerBI_Project

[Live Dashboard Link](https://app.powerbi.com/view?r=eyJrIjoiNDkwNTM4ZWMtODEwYy00ZjI1LTg5Y2UtMzlhNjI5YTY2MzNmIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## 𝐏𝐫𝐨𝐛𝐥𝐞𝐦 𝐒𝐭𝐚𝐭𝐦𝐞𝐧𝐭:
AtliQ Hardware, a rapidly expanding global consumer electronics company, has been grappling with unwieldy Excel files for data analytics. This outdated approach has been hindering effective decision-making and causing significant losses. In response, they urgently sought agile, data-driven decision-making.

## Tech stacks
* SQL
* PowerBi Desktop
* Excel
* DAX language
* DAX studio (for optimizing the report) 
* Project charter file


## 𝐎𝐛𝐣𝐞𝐜𝐭𝐢𝐯𝐞:
Develop an interactive report offering invaluable insights across finance, sales, marketing, supply chain, and executive teams, using provided mockup dashboards as a reference.

## Company’s background
AltiQ Hardware is a company that has grown vastly in recent years, and opened business all over the globe. It is a company that sells, computers and computer accessories through three mediums/channel

Retailers

Direct

Distributors

Recently the company has faced a unforeseen loss by opening a store in America based on surveys, intuition, and some Excel analysis also the company’s competitors have a handful of analytics teams to perform analysis and make data-driven decisions. So, the AltiQ hardware has no other option other than building its analytics team for data-driven insights and decisions in the future to survive better in the industry.

Project kick-off session, where you should get clear of what and why this project is and all other questions you have with regards to the project


## 𝐀𝐩𝐩𝐫𝐨𝐚𝐜𝐡:
➡️ Project Planning

➡️ Data Collection, Exploration, Transformation

➡️ Data Modeling

➡️ Dashboard Preparation

➡️ Data Validation & Stakeholder Feedback Implementation.


## Data Sources
The dashboard gathers data from two primary sources:

    1. Excel/CSV Files: Targets and Market Share data and related information are sourced from Excel and CSV files.

    2. MySQL Database: Facts and Dimensions for all departments are retrieved from a MySQL database.


## Dataset Understanding.
Understanding what data is available will be more helpful while doing analysis. before jumping on to the analysis get good understanding of what are data available.

Dimension table: It will have static data like details of customers and products

### Dimension Tables

`dim_customer`

  - Contains details of customers across markets and platforms.
  - 27 distinct markets.
  - 75 distinct customers.
  - 2 types of platforms: Brick & Mortar (Physical/offline store) and e-commerce (Online Store).
  - Three channels: Retailer, Direct, and Distributors.


`dim_market`

- Contains details of markets, sub-zones, and regions.
- 27 distinct markets.
- 7 sub-zones.
- 4 regions: APAC, EU, NA, LATAM.


`dim_product`

- Contains details of product divisions, categories, and variants.
- Divisions: P & A, Peripherals, Accessories, PC, Notebook, Desktop, N & S, Networking, Storage.
- 14 different categories (e.g., Internal HDD, keyboard).
- Different variants available for the same product.


### Fact Tables


`fact_forecast_monthly`

- Used for forecasting customer needs in advance.
- Helps improve customer satisfaction and reduce warehouse storage costs.
- Denormalized for analytical use.
- Date of the month replaced by start date.
- Columns include forecast quantity needed by the customer.

`fact_sales_monthly`

- Similar to fact_forecast_monthly with actual sold quantities.


### Additional Tables
`gdb056`

- freight_cost: Details of travel and other costs for each market by fiscal year.
- gross_price: Details of gross prices with product code.
- manufacturing_cost: Details of manufacturing costs with product code and year.
- Pre_invoice_dedutions: Details of pre-invoice deduction percentages for each customer by year.
- Post_invoice_deductions: Details of post-invoice and other deductions.

`This dataset provides comprehensive information about customers, markets, products, and various costs. The dimension tables offer static data, while the fact tables provide transactional and forecasting - insights. Analyzing this dataset can lead to valuable insights for optimizing sales, costs, and customer satisfaction.`



## Data Model
Data modeling plays a vital role and is considered as the basement of report. All the visuals will be build upon the data model.

Poor data modeling affects the over all performance of the report.

In this project, we have followed Snowfall data modeling method.

## Dashboard designing
Based on the mock ups received as requirement, the team will start designing the visuals and create measure as and when required

  ### Home view
  In Home view, all the views button will be available. User will land on specific view page by clicking the button
 
  ![image](https://github.com/manishhemnani06/Business-360-Brick-mortar-and-e-commerce-/assets/116347164/4761faab-7d68-415d-ae37-c88a0965dd80)
  
 ### Finance View

  ![image](https://github.com/manishhemnani06/Business-360-Brick-mortar-and-e-commerce-/assets/116347164/d8a0ba7b-8990-4d8a-8467-a0a778e5ddc5)

  
 ### Sales View
 
  ![image](https://github.com/manishhemnani06/Business-360-Brick-mortar-and-e-commerce-/assets/116347164/8bfa69cc-8f16-4b43-a649-4777c820ad97)


###  Marketing View

  ![image](https://github.com/manishhemnani06/Business-360-Brick-mortar-and-e-commerce-/assets/116347164/6d8155dc-ce4a-4d04-9a54-d39fb22598c0)

###  Supply chain View

![image](https://github.com/manishhemnani06/Business-360-Brick-mortar-and-e-commerce-/assets/116347164/3c4b88c3-ef05-4dc5-9a38-c8024fe3a04a)

  
###  Executive View

![image](https://github.com/manishhemnani06/Business-360-Brick-mortar-and-e-commerce-/assets/116347164/95453fb5-21c1-4b51-9750-935870099db3)


## Key Achievements
  1. Customized Dashboard: Developed a multi-functional Power BI dashboard to specifically meet AtliQ Hardware's needs, allowing them to gain insights into their various departments.

  2. Data Integration: Data was sourced from disparate locations, including Excel/CSV files and a MySQL database, and seamlessly integrated into Power BI for comprehensive analysis.

  3. Data Model and Visualizations: A robust data model was developed within Power BI, enabling the creation of visually appealing and interactive visualizations to represent key performance indicators (KPIs).

  4. Performance Optimization: The dashboard's performance was significantly improved using DAX Studio, resulting in a 5% increase in report efficiency.

  5. Data-Driven Decisions: AtliQ Hardware can now analyze trends across different departments, empowering them to make data-driven decisions.






