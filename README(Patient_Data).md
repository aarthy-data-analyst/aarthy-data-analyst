🏥 Hospital Patient Data Cleaning and Analysis

📌 Project Overview

This project focuses on cleaning and analysing hospital patient data using Python and its data analysis libraries.

The main objective is to improve data quality by identifying and handling missing values, duplicate records, inconsistent data and incorrect data formats.

This project also explores patient information to generate meaningful insights that can support better healthcare data analysis.

🎯 Project Objectives

Identify and handle missing values.

Detect and remove duplicate records.

Correct inconsistent data.

Handle incorrect data types.

Calculate patient length of stay.

Identify outliers in numerical columns.

Perform Exploratory Data Analysis (EDA).

Generate meaningful insights from patient data.

🛠️ Tools and Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

📂 Dataset Information

The dataset contains hospital patient-related information.

The analysis covers available patient details such as:

	Patient ID

	Patient Name (if included)

	Age

	Gender

	Blood group

	Department

	Doctor

	Admission Date

	Discharge Date

	Diagnosis

	Treatment

	Room_Type

	Length of Stay

	Total_Bill

	Insurance

	Payment_Mode

	Patient Rating

	Readmission

	Emergency

Note: The actual columns depend on the original dataset.

🧹 Data Cleaning Process

The following cleaning techniques were performed:

Checked the dataset structure using df.info().

Identified missing values using df.isnull().sum().

Checked duplicate records.

Handled missing values in the Location column.

Corrected inconsistent values.

Converted date columns into appropriate date formats.

Calculated Length of Stay using admission and discharge dates.

Checked numerical columns for outliers.

📊 Exploratory Data Analysis

The following analysis can be performed:

Patient distribution by gender.

Patient distribution by age group.

Number of patients by location.

Average length of hospital stay.

Patient rating analysis.

Comparison of patient admissions.