# NYPD Shooting Data Analysis
Gun violence remains a critical and complicated issue in the United States that needs careful examination to promote effective government decision-making and society-wide discussion. This project analyzes the shooting incidents in New York City from 2006 to 2022. By inspecting the patterns, trends, and contributing variables associated with these incidents, we hope to provide data-driven insights to stakeholders, politicians, and communities aiming to create safer surroundings.
# Data Source
The dataset "NYPD_Shooting_Incident_Data__Historic_.csv" is obtain from DATA.GOV at the link https://catalog.data.gov/dataset/nypd-shooting-incident-data-historic.
The CSV file of the dataset and its metadata file "metadata.json" can be found in the "data-review-and-cleaning" folder.
# Data Processing Pipeline
This project follows the data processing pipeline shown below:
<img width="809" alt="Screenshot 2023-11-21 at 4 38 00 PM" src="https://github.com/jianghuayu007/FinalProject-BigData-I535/assets/133912130/85002210-30b0-4fcd-91a3-56e27789868f">
# Working Environment Setup
To practice clouding computing and virtualization, we created a virtual machine on the Jetstream2 platform with the following parameters: 
Image – Ubuntu 20.04, 
Flavor – m3.small, 
Root disc size – 20GB (default for selected flavor), 
Web Desktop enabled.
We launched the Jupyter Notebook server on the browser of the Web Destop for data cleaning and analysis.
# Data Overview and Cleaning
For data overview, we use the Python script "dataset-review.ipynb" to examine the total number of datapoints, attributes, the number of null values and non-null values, and the percentage of null values of each attribute. For data cleaning, we use the Python script "data-cleaning/ipynb" to check for duplicates and drop unwanted columns. Both scripts can be found in the "data-review-and-cleaning" folder.
# Data Visualization
Data analysis results are visualized using Tableau 2023.1. The Tableau pakaged workbook "final-project-visualization.twbx" and exported visualization images can be found in the "data-visualization" folder.
