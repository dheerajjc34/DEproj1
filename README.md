The goal of this project is to analyze Spotify data to generate insights using cloud-based tools and technologies. The main steps in the project are:

Data Source:

The dataset used for this project was obtained from Kaggle and uploaded to this GitHub repository.

Data Pipeline:

A data pipeline was developed to retrieve the dataset from GitHub.
Upon successful retrieval, the data is processed using Databricks.

Databricks Cluster:

The data is processed using a Databricks cluster.
The Databricks notebook contains all the processing steps required to clean and transform the data.

Data Storage:

After processing, the data is stored in Azure Data Lake Storage (ADLS).

Data Visualization:

Power BI was connected to ADLS to create a dashboard for visualizing the insights derived from the processed data.

Tools and Technologies used:
GitHub: For version control and dataset storage.
Kaggle: As the source for the dataset.
Databricks: For data processing and transformation.
Azure Data Lake Storage (ADLS): For storing the processed data.
Power BI: For creating dashboards and visualizations.


Results
The final dashboard created in Power BI provides insights into various aspects of the Spotify dataset, including popular songs, artists, and trends over time.
