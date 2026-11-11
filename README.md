# Healthcare-Data-Analysis
Healthcare Data Cleaning and Transformation
# Healthcare Data Analysis and Insights

## 1. Project Overview
This project focuses on analyzing healthcare data to understand patient health profiles, medical histories, and healthcare costs.

The project uses Microsoft Excel for data cleaning, data transformation, data analysis, and visualization.

## 2. Project Objectives
- Identify and handle missing values.
- Clean and organize healthcare data.
- Transform data into meaningful formats.
- Analyze patient health conditions.
- Explore healthcare charges and patient trends.
- Create charts and an interactive dashboard.

## 3. Dataset Description
The dataset consists of three tables:

- Customer Names
- Medical Examinations
- Hospitalisation Details

Customer ID is used as the common field to connect the tables.

## 4. Tools Used
- Microsoft Excel
- Excel Formulas
- Pivot Tables
- Charts and Visualizations

## 5. Data Cleaning Steps
1. Checked the number of missing values (?) in each column.
2. Filled missing month values with Sep.
3. Replaced missing year values with the rounded average year.
4. Filled missing smoker, Hospital tier, and City tier values using the mode.
5. Replaced missing State ID values with Unknown.

## 6. Data Transformation Steps
1. Split customer names into Title, First Name, and Last Name.
2. Converted NumberOfMajorSurgeries into numerical values.
3. Checked and standardized Heart Issues and smoker columns.
4. Created a new Weight Status column based on BMI.
5. Created a new Diabetes Status column based on HbA1C.
6. Combined year, month, and date into Date of Birth.
7. Calculated customer age as of 8 June 2023.
8. Formatted healthcare charges as US Dollar currency.

## 7. Data Analysis and Visualization
The next stage of this project includes:
- Creating a combined Healthcare table using VLOOKUP.
- Analyzing patient health conditions using Pivot Tables.
- Comparing healthcare charges.
- Creating charts and an interactive dashboard.

## 8. Project Outcome
The objective is to prepare clean and transformed healthcare data for meaningful analysis and better understanding of patient health conditions and healthcare costs.
