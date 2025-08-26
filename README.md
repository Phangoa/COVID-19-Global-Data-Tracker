COVID-19 Global Data Tracker
Project Overview
This project is a comprehensive data analysis and visualization initiative aimed at tracking and analyzing key global trends related to the COVID-19 pandemic. The core of this project is a data report generated through a Jupyter Notebook, which serves as a practical demonstration of a full data science workflow. The analysis focuses on a selection of five countries: Kenya, India, the United States, South Africa, and Lesotho.
The project's key objectives are:
•	Data-driven Insights: To provide a clear and concise understanding of COVID-19's impact through quantitative analysis.
•	Data Storytelling: To effectively communicate complex data trends using visualizations and a narrative summary.
•	Reproducibility: To ensure the entire analysis pipeline, from data acquisition to visualization, is transparent and easily reproducible.
The final output is a living document that can be updated with the latest data to provide continuous insights into the pandemic's evolution.
Getting Started
Prerequisites
To run the analysis and generate the report, you need to have Python and Jupyter Notebook installed on your system. The following Python libraries are required:
•	pandas
•	matplotlib
•	seaborn
•	plotly
You can install these dependencies using pip:
pip install pandas matplotlib seaborn plotly

Running the Analysis
1.	Launch Jupyter: Open your terminal or command prompt and run the following command to start the Jupyter Notebook server:
2.	jupyter notebook

3.	Open the File: Your web browser will open a new tab with the Jupyter dashboard. Navigate to the location where you saved the .ipynb file and open it.
4.	Run Cells: Execute each cell sequentially from top to bottom by clicking the "Run" button in the toolbar or by pressing Shift + Enter. The notebook will load the data, perform the analysis, and display all outputs, including plots and statistical summaries.
Data Source
The data used in this project is sourced from Our World in Data, a reliable public resource for COVID-19 statistics. The dataset is a daily-updated CSV file, ensuring that the analysis reflects the latest available information.
•	Data URL: https://raw.githubusercontent.com/owid/covid-19-data/master/public/data/owid-covid-data.csv
Notebook Structure
The Jupyter Notebook is organized into the following sections to provide a clear, step-by-step narrative of the analysis:
1.	Introduction: An overview of the project's goals and scope.
2.	Setup and Data Loading: Imports required libraries and loads the raw dataset.
3.	Data Cleaning and Preprocessing: Steps to prepare the data for analysis, including filtering and handling missing values.
4.	Exploratory Data Analysis (EDA): Creation of new features and metrics for deeper insights.
5.	Visualizations and Reporting: The main section showcasing various charts to communicate findings.
Key Features and Findings
•	Time-series plots to track the progression of total_cases and total_vaccinations.
•	A bar chart to compare the latest case counts across the selected countries.
•	A choropleth map to visualize global COVID-19 case density.
The analysis provides a clear, visual report that can be easily understood and shared with others.
