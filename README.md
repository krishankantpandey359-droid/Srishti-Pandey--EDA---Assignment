# Exploratory Data Analysis on Cars Dataset

## Project Overview

This project is based on Exploratory Data Analysis (EDA) performed on the Cars dataset from Kaggle.

The main objective of this project is to understand the dataset, examine its features, check data types and records, identify duplicate values, remove irrelevant columns, analyze numerical features, detect outliers, and clean the dataset using the IQR method.

Exploratory Data Analysis helps us understand the structure and quality of data before using it for further analysis or machine learning.

---

## Problem Statement

We have used the Cars dataset from Kaggle with features including make, model, year, engine details, transmission, driven wheels, mileage, popularity, and price.

The purpose of this project is to perform systematic data exploration and preprocessing on the dataset.

The analysis includes:

- Understanding the dataset
- Checking the available columns
- Understanding each feature
- Checking data types
- Checking non-null records
- Finding unique values
- Removing duplicate rows
- Removing irrelevant columns
- Selecting numerical columns
- Detecting outliers
- Visualizing outliers using boxplots
- Removing outliers using the IQR method
- Comparing the dataset before and after cleaning

---

## Dataset

The project uses the **Cars dataset from Kaggle**.

The original dataset contains:

- **11,914 rows**
- **16 columns**

The dataset contains both categorical and numerical features related to different cars.

---

## Features in the Dataset

The dataset contains the following expected columns:

| Column | Description |
|---|---|
| Make | Company or manufacturer of the car |
| Model | Model or version of the car |
| Year | Year of the car model |
| Engine Fuel Type | Type of fuel used by the engine |
| Engine HP | Horsepower produced by the engine |
| Engine Cylinders | Number of cylinders present in the engine |
| Transmission Type | Type of transmission, such as manual or automatic |
| Driven Wheels | Type of wheel drive |
| Number of Doors | Number of doors present in the car |
| Market Category | Category of the car |
| Vehicle Size | Size category of the vehicle |
| Vehicle Style | Style or body type of the vehicle |
| Highway MPG | Average mileage of the car on the highway |
| City MPG | Average mileage of the car in the city |
| Popularity | Popularity rating of the car |
| MSRP | Manufacturer's Suggested Retail Price of the car |

---

## Technologies Used

The following technologies and Python libraries are used in this project:

- Python
- Jupyter Notebook
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

---

## Importing Required Libraries

The required Python libraries are imported before starting the analysis.

```python
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
from scipy import stats
import warnings

warnings.filterwarnings("ignore")# Srishti-Pandey--EDA---Assignment
Exploratory Data Analysis of Cars Dataset | EDA Practical Day 14 | Data Cleaning, Outlier Detection &amp; Visualization
