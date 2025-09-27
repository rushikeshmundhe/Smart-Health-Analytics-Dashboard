Smart Health Analytics Dashboard
This repository contains a comprehensive data analysis and visualization project aimed at providing insights into healthcare datasets. The project includes Python scripts for data cleaning, processing, and exploratory data analysis (EDA), as well as a Power BI file for interactive visualizations.

Project Structure
Python Notebook: Data cleaning and processing.ipynb

This notebook handles data cleaning, processing, and exploratory data analysis for three datasets:
Appointments Dataset: Analyzes patient no-show rates and their correlation with various factors.
Insurance Dataset: Explores healthcare charges based on BMI, smoking habits, and other factors.
Diabetes Dataset: Investigates correlations between features and diabetes outcomes.
Key steps include:
Cleaning messy column names.
Handling missing or invalid data.
Feature engineering (e.g., BMI categories, pregnancy groups).
Generating insights and saving them as CSV files for further use.
Power BI File: healthcare.pbix

This file provides an interactive dashboard for visualizing healthcare data.
Key features:
Visualizations for patient no-show rates, insurance charges, and diabetes outcomes.
Filters and slicers for dynamic data exploration.
Insights derived from the cleaned datasets.
Datasets
The project uses the following datasets:

Appointments Dataset (KaggleV2-May-2016.csv):
Contains information about patient appointments, including no-show rates, SMS reminders, and appointment dates.
Insurance Dataset (insurance.csv):
Includes data on healthcare charges, BMI, smoking habits, and demographic details.
Diabetes Dataset (diabetes.csv):
Features medical data such as glucose levels, BMI, and diabetes outcomes.
Key Outputs
Cleaned Datasets:
clean_appointments.csv
clean_insurance.csv
clean_diabetes.csv
Insights:
insights_no_show_by_weekday.csv: Average no-show rates by weekday.
insights_charges_by_bmi.csv: Average healthcare charges by BMI category.
insights_diabetes_by_pregnancy.csv: Diabetes outcomes by pregnancy group.
How to Use
Python Notebook:
Open Data cleaning and processing.ipynb in Jupyter Notebook or VS Code.
Run the cells sequentially to clean the data, perform EDA, and generate insights.
Power BI Dashboard:
Open healthcare.pbix in Power BI Desktop.
Explore the interactive visualizations and insights.
Requirements
Python
pandas
numpy
matplotlib
seaborn
Install the required Python packages using:

Power BI
Power BI Desktop (latest version)
Insights and Visualizations
Python Notebook
Appointments Dataset:
Distribution of patient ages.
No-show rates by age group and weekday.
Impact of SMS reminders on no-show rates.
Insurance Dataset:
Average charges by BMI category.
Charges comparison between smokers and non-smokers.
Scatterplot of charges vs. age.
Diabetes Dataset:
Correlation heatmap of features.
Glucose levels and BMI by diabetes outcome.
Pregnancy groups vs. diabetes outcome.
Power BI Dashboard
Interactive charts and graphs for healthcare data.
Filters for dynamic exploration of insights.
Contribution
Feel free to fork this repository, make improvements, and submit pull requests. Contributions are welcome!


<img width="1268" height="702" alt="Screenshot 2025-09-27 213934" src="https://github.com/user-attachments/assets/f921e9fb-0a64-4c7d-9266-a9a56018afb1" />
<img width="1284" height="715" alt="Screenshot 2025-09-27 213951" src="https://github.com/user-attachments/assets/249c5764-57c1-445d-a99d-843f13c85ba6" />
<img width="1274" height="711" alt="Screenshot 2025-09-27 214006" src="https://github.com/user-attachments/assets/752d5d9a-97ae-48ea-af4e-b2e942f67d0c" />
<img width="1288" height="724" alt="Screenshot 2025-09-27 214025" src="https://github.com/user-attachments/assets/df455637-94f7-48df-a1cb-5aa8fe793120" />


