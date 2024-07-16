# Road to Data Engineering Project: AudioBook Business Intelligence
This project is from [Road to Data Engineer](https://school.datath.com/courses/road-to-data-engineer-2-0-2023) course. Road to Data Engineer is a course that provides fundamental to advanced knowledge in the Data Engineer track. In this workshop it allows us to build automated data pipelines of AudioBook Business.

## Project Overview
<img src="picture/process-overview.png" width=100% height=40%>

### Components of this workshop
1. Data Collection: Python (Google Colab), Pandas, REST API
2. Data Wrangling and Cleansing: Apache Spark (Colab and PySpark)
3. Data Storage: Google Cloud Storage (GCS)
   - Create bucket
   - Upload data
4. Automated Data Pipeline: Apache Airflow
   - Import modules
   - Define the default arguments
   - Define the DAG
   - Create tasks
   - Set the task dependencies
5. Building Data Warehouse: BigQuery (integrated with Airflow)
   - Create dataset
   - Import data
   - Explore data on BigQuery using SQL
6. Building Dashboard: Google Data Studio (Usin data from BigQuery)
   - Create table in BigQuery (if not exist)
   - Create a view to provide a specific subset of data for visualization
   - Create a dashboard
  
## Dashboard
### Dashboard: Overview
Dashboard summary:
- Business income
- Number of customers
- Number of purchases in each country
- Revenue of each country
- Bestsellers
- Best selling book category

<img src="picture/dashboard-1.png" width=100% height=40%>

### Dashboard: Searching
Dashboard summary:
In this dashboard, we can select a country, year, and minimum revenue to see the sales data in specific range.

<img src="picture/dashboard-2.png" width=100% height=40%>
