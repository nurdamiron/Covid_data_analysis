# COVID-19 Data Analysis and Visualization

This project analyzes a COVID-19 dataset containing information about patients, including demographic and clinical data, and visualizes various aspects of the data.

## Dataset Columns

The dataset contains the following columns:

- USMER
- MEDICAL_UNIT
- SEX
- PATIENT_TYPE
- DATE_DIED
- INTUBED
- PNEUMONIA
- AGE
- PREGNANT
- DIABETES
- COPD
- ASTHMA
- INMSUPR
- HIPERTENSION
- OTHER_DISEASE
- CARDIOVASCULAR
- OBESITY
- RENAL_CHRONIC
- TOBACCO
- CLASIFFICATION_FINAL
- ICU

## Preprocessing and Data Wrangling

The preprocessing and data wrangling steps include:

1. Checking for missing values
2. Filling missing values
3. Converting the date column to datetime format
4. Filtering data based on specific conditions
5. Calculating age groups
6. Grouping data by specific columns and aggregating

## Analysis and Constructive Questions

The analysis answers several constructive questions, such as:

1. What is the total number of deaths in the dataset?
2. What is the distribution of deaths by age group?
3. What is the distribution of deaths by sex?
4. What are the most common comorbidities among deceased patients?

## Visualization

Several visualizations are generated using Matplotlib and Seaborn:

1. Distribution of deaths by age group
2. Distribution of deaths by sex
3. Most common comorbidities among deceased patients
4. Distribution of ICU admissions by age group
5. Distribution of intubations by age group
6. Correlation matrix between comorbidities

## Usage

You can use this code by downloading the dataset, modifying the URL in the code, and executing the code in a Python environment with the required libraries installed (numpy, pandas, matplotlib, seaborn).
