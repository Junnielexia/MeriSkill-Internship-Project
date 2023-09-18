# Task
## Title of the project 2: “Diabetes Patients”
 
## About Dataset
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether a patient has diabetes based on certain diagnostic measurements included in the dataset. Several
constraints were placed on the selection of these instances from a larger database. In particular, all patients
here are females at least 21 years old of Pima Indian heritage.
2 From the data set in the (.csv) File We can find several variables, some of them are independent (several medical predictor variables) and only one target dependent variable (Outcome).


I apologize for missing that part. Including Key Performance Indicators (KPIs) and charts in your Power BI dashboard is crucial for presenting the insights effectively. Here's an updated version of your documentation with a section on KPIs and charts:

# Diabetes Patients Data Analysis with Power BI

## Introduction
This data analysis project focuses on exploring and analyzing a dataset of diabetes patients originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether a patient has diabetes based on certain diagnostic measurements included in the dataset. The dataset comprises diagnostic measurements for females at least 21 years old of Pima Indian heritage. The project aims to gain insights from the data and build a predictive model to classify diabetes outcomes, utilizing Power Query and Power BI for data manipulation, visualization, and dashboard creation.

## Data Source
The dataset used in this project was obtained from the National Institute of Diabetes and Digestive and Kidney Diseases. It is available as a CSV file named "diabetes_data.csv."

## Technologies Used
- Power Query
- Power BI
- Python (for advanced data analysis)
- Jupyter Notebook
- Libraries: pandas, numpy, scikit-learn

## Data Exploration
In this section, we perform an initial exploration of the dataset to understand its structure and characteristics.

- **Pregnancies**: The number of pregnancies the patient has had.
- **Glucose**: The patient's glucose level.
- **BloodPressure**: The patient's blood pressure.
- **SkinThickness**: The patient's skin thickness.
- **Insulin**: The patient's insulin level.
- **BMI**: The patient's Body Mass Index.
- **DiabetesPedigreeFunction**: A function that represents the likelihood of diabetes based on family history.
- **Age**: The age of the patient.
- **Outcome**: The target variable, with 0 indicating non-diabetic and 1 indicating diabetic.

![Screenshot (287)](https://github.com/Junnielexia/MeriSkill-Internship-Project/assets/95970546/e76e955e-9f55-4856-a867-806e0ffb92ca)

## Data Preprocessing with Power Query
Data preprocessing is essential to clean and prepare the dataset for analysis and modeling. Power Query is used for this purpose, including steps such as:
- Handling missing values
- Renaming columns
- Changing data types
- Calculating derived columns if necessary
  
### Patient ID column
using index column command i created a patients id column to help organize the data for easy analysis.

### Age group column  
```
if [Age] >= 21 and [Age] <= 30 then "21-30"
else if [Age] > 30 and [Age] <= 40 then "31-40"
else if [Age] > 40 and [Age] <= 50 then "41-50"
else if [Age] > 50 and [Age] <= 60 then "51-60"
else "60+"

```
![Screenshot (288)](https://github.com/Junnielexia/MeriSkill-Internship-Project/assets/95970546/9f4b0d00-584c-46b5-a106-dd2da9688aa7)

### BMI Category
```
if [BMI] = 0 then "Unknown"
    else if [BMI] < 18.5 then "Underweight"
    else if [BMI] >= 18.5 and [BMI] < 24.9 then "Normal"
    else if [BMI] >= 24.9 and [BMI] < 29.9 then "Overweight"
    else "Obese"
```
### Insulin Level Category
```
if [Insulin] = 0 then "Unknown"
    else if [Insulin] < 50 then "Low"
    else if [Insulin] >= 50 and [Insulin] < 100 then "Normal"
    else if [Insulin] >= 100 and [Insulin] < 200 then "Elevated"
    else "High"
```
### Blood Pressure Category
```
if [BloodPressure] = 0 then "Unknown"
  else if [BloodPressure] < 120 and [BloodPressure] >= 80 then "Normal"
  else if [BloodPressure] >= 120 and [BloodPressure] < 130 then "Elevated"
  else if [BloodPressure] >= 130 and [BloodPressure] < 140 then "Stage 1 Hypertension"
  else if [BloodPressure] >= 140 and [BloodPressure] < 180 then "Stage 2 Hypertension"
  else if [BloodPressure] >= 180 then "Hypertensive Crisis"
  else "Unknown"
```

## Data Visualization with Power BI
Power BI is employed for data visualization, allowing for the creation of interactive and informative visualizations. Possible visualizations include:
- Histograms and box plots for numeric features
- Bar charts for categorical features (if applicable)
- Scatter plots to explore relationships between variables
- Line charts to visualize trends over time (if applicable)
Create interactive visualizations that allow users to explore the impact of the "DiabetesPedigreeFunction" on diabetes outcomes dynamically. This can enhance the user experience of your Power BI report.
## Key Performance Indicators (KPIs)
Key Performance Indicators are important metrics that provide a quick snapshot of the dataset's critical aspects. Some suggested KPIs for this project might include:
- **Average Glucose Level**: The average glucose level among the patients.
- **Average BMI**: The average BMI of the patients.
- **Percentage of Diabetic Patients**: The percentage of patients who are diabetic.

## Charts for the Dashboard
To create an effective dashboard, consider including the following charts:
- **Pie Chart**: Showing the distribution of diabetic and non-diabetic patients.
- **Line Chart**: Visualizing trends in glucose levels or BMI over time.
- **Bar Chart**: Displaying the number of pregnancies for different age groups.

## Data Analysis with Python (Optional)
While Power BI is excellent for visualization and KPI tracking, more advanced data analysis can be performed using Python and Jupyter Notebook. This may include feature selection, machine learning model development, and evaluation.

## Recommendations
Based on the analysis, provide recommendations or insights regarding diabetes risk factors or potential interventions. These recommendations can be derived from the analysis and insights gained from the dataset.

## Summary
Summarize the key findings, insights, and the impact of this analysis on understanding and potentially addressing diabetes in the specific demographic group. Mention any potential next steps for further research or interventions.



