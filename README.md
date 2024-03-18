# Data engering Project 
***
This is my project for the data engineering zoomcamp final project.
## Project Description : Games Sales Analysis (End to End pipline)
The project is about analyzing the sales of video games from different platforms and regions. The data is collected from the Kaggle website. The data is in the form of a CSV file. The data is then loaded into GCS using **MAGE** as a orchestration tool. The data is then loaded into BigQuery ,and using **DBT** we can transform the data and then visualize the data using **Tableau**
## Data Source
The data is collected from the Kaggle website. The data is in the form of a CSV file. [kaagle](https://www.kaggle.com/gregorut/videogamesales)
## Data Engineering Tools
-**Mage** : For orchestration  <br>
-**Dockers** : For containerization  <br>
-**GCS** : Data Lake  <br>
-**BigQuery** : For data warehousing<br>
-**DBT** : For transformation  <br>
-**Tableau** : For visualization  <br>
## Data Engineering Pipeline
The data engineering pipeline is as follows:
1. The data is collected from the Kaggle website.
2. The data is then loaded into GCS using **MAGE** as a orchestration tool.
3. The data is then loaded into BigQuery.
4. Using **Dbt** Transform 
5. Create a **Dashboard** from the result of **DBT**
