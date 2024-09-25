# 911 Calls Data Analysis
## Project Overview
This project analyzes a dataset of 911 calls to uncover patterns and insights. The data used in this project comes from Montgomery County in the US, and it includes the following information:

Timestamps
Location
Emergency type
Description
The goal is to explore the data, identify trends, and gain insights into 911 calls, such as:

## The most common reasons for calls
Seasonal or time-based patterns in calls
Dataset Information
The dataset used is publicly available and contains the following key columns:

lat: Latitude of the call
lng: Longitude of the call
desc: Description of the emergency
zip: Zipcode of the call
title: Reason for the call
timeStamp: Time of the call
twp: Township
addr: Address of the call
e: Dummy variable
Key Features
Data Cleaning & Preprocessing:

## Handle missing data and incorrect data types.
Extract necessary features from the dataset (e.g., extracting hour, month, and day of the week from the timestamp).
Exploratory Data Analysis (EDA):

## Identify the most common reasons for 911 calls.
Analyze temporal trends such as:
Calls by day of the week
Calls by month
Geographical analysis based on latitude and longitude.
Visualizations:

## Use visual tools such as line plots, heatmaps, and bar charts to show patterns in the data.
Map visualizations for geographical analysis.
Requirements
The project utilizes Python and the following libraries:

Pandas: For data manipulation and cleaning.
Matplotlib: For creating static visualizations.
Seaborn: For statistical data visualization.
Plotly: For interactive visualizations.
