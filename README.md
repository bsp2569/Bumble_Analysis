# Bumble User Behavior Analysis – Exploratory Data Analysis (EDA)

This project explores a real-world Bumble user dataset to uncover demographic patterns, lifestyle attributes, and behavioral trends that influence engagement on the platform. The analysis covers complete data cleaning, transformation, feature understanding, and insight generation with a business-oriented perspective.


## Project Overview

Dating platforms thrive on understanding user behavior. This analysis aims to answer questions such as:
	•	Who are the dominant user demographics?
	•	How do lifestyle attributes (diet, drinking habits, fitness levels) vary across users?
	•	Which cities/states have the highest concentration of users?
	•	How do factors like income, height, or activity levels shape user engagement?

The notebook performs full-scale EDA to derive these insights.


**1. Data Cleaning**
	•	Identified missing data and calculated missing value percentages.
	•	Dropped columns with more than 50% null values.
	•	Imputed numeric columns (e.g., height, income) using median grouped by gender and age.
	•	Converted inconsistent data types to correct formats (e.g., last_online to datetime).

**2. Data Transformation**
	•	Standardized numerical fields.
	•	Processed categorical features (diet, pets, body_type, etc.).
	•	Parsed and cleaned lifestyle-related fields.

**3. Outlier Detection**
	•	Used IQR (Interquartile Range) to detect anomalies in:
	•	Height
	•	Income
	•	Age
	•	Implemented corrective handling where necessary.

**4. Exploratory Data Analysis**
	•	Demographic distributions (age groups, gender balance).
	•	Lifestyle insights (diet, drinking behavior, fitness, pets).
	•	Geographic distribution (city & state-level trends).
	•	Activity patterns based on last_online.


# Key Insights
	•	Age 26–35 is the largest user group.
	•	Men form a higher proportion across all age ranges.
	•	Most users fall within 0–50k income, with 26–35 age group earning slightly higher.
	•	“Likes dogs and cats” is the most common pet preference.
	•	Users with restricted diets (vegan/vegetarian) tend to drink less frequently.
	•	San Francisco, Oakland, and Berkeley host the highest number of users.
	•	California is the top state by user volume.

## Tech Stack
	•	Python
	•	Pandas
	•	NumPy
	•	Matplotlib / Seaborn
	•	Jupyter Notebook
