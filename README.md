# Developer Survey Analysis & Visualization

## Overview
This project focuses on analyzing and visualizing data from a **developer survey** using various techniques, including data acquisition, exploration, wrangling, exploratory data analysis (EDA), and visualization. The goal is to extract insights about developer demographics, technologies, and work preferences, presenting them in an interactive dashboard.

## Repository Contents
- **Data Processing Notebook** (`Data Processing - Acquisition, Exploration, and Wrangling.ipynb`)
- **EDA Notebook** (`Exploratory Data Analysis.ipynb`)
- **Visualization Notebook** (`Data Visualization.ipynb`)
- A viewable **PDF of the Dashboard**  (can access the dashboard online here : [**Dashboard Link**](https://app.powerbi.com/view?r=eyJrIjoiMzdlY2ZkZTEtMGI1NS00MjQ3LWE3YTctOTQ4YzMyNTVmMDE2IiwidCI6ImI0MmFhYTY2LTA2NWMtNDE2NS05MGE3LTgwMjIyMmViY2U1MSJ9) )
- Raw data csv compressed to .gz
- Processed data csv compressed to .gz

## How to Use
1. Clone the repository
2. Open the Jupyter notebooks to explore the analysis steps.
3. Visit the dashboard link to interact with the visualizations.
   
## Process
### 1. Data Processing - Acquisition, Exploration, Wrangling
- Loaded the raw survey data acquired from a public url as a csv file into the analysis environment. ([URL](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DA0321EN-SkillsNetwork/LargeData/m1_survey_data.csv))
- Performed an initial exploration of the dataset.
- Handled missing values, duplicates, and data inconsistencies.
- Transformed and structured data for better analysis.
- Saved the processed data as a CSV file for performing EDA

### 2. Exploratory Data Analysis (EDA)
- Loaded the processed data to perform EDA
- Conducted descriptive statistics and initial observations.
- Identified patterns, correlations, and trends in developer responses.
- Generated summary statistics and visualizations to understand data distribution.

### 3. Data Visualization
- Created meaningful plots using libraries like Matplotlib, Seaborn and Plotly
- Used different chart types (bar charts, pie charts, wordcloud, tree maps etc.) to represent key insights.
- Highlighted important findings with interactive visual elements.

### 4. Dashboard
- The data visualizations presented in the notebook are enhanced and built into a dashboard of 3 pages using PowerBI for better user interaction and exploration.
- [Link to the dashboard](https://app.powerbi.com/view?r=eyJrIjoiMzdlY2ZkZTEtMGI1NS00MjQ3LWE3YTctOTQ4YzMyNTVmMDE2IiwidCI6ImI0MmFhYTY2LTA2NWMtNDE2NS05MGE3LTgwMjIyMmViY2U1MSJ9)

## Technologies Used
- **Python** - Pandas, NumPy, Matplotlib, Seaborn, Plotly
- **Dashboard Tool** - PowerBI

## Conclusion
This project demonstrates the entire data analysis pipeline, from data acquisition and preparation to visualization and dashboard development. The insights extracted help in better understanding developer trends and making data-driven decisions.

Refer this [project](https://github.com/monishab2001/Medical-Insights-Dashboard) for an **interactive** dashboard built in **Power BI** with advanced features, customized views and dynamic visualizations.


