# App Usage and Mental Health Data Analysis with Machine Learning

## Overview

This repository contains a Jupyter Notebook for analyzing the relationship between mobile app usage and mental health. The analysis leverages machine learning techniques to uncover patterns and insights from the data, providing valuable information for understanding how app usage affects mental well-being.

## Graphs
![image](https://github.com/user-attachments/assets/9181ab91-b291-483e-a86f-80760356b75c)
![image](https://github.com/user-attachments/assets/37d3487a-9978-4a04-a4da-3fbfb41cbacd)

open appusage-mentalhealth_data-analisys-with-ML/notus-js/index.html in a browser to see it dynamically


## Contents

- **app_usage_mental_health_analysis.ipynb**: The main Jupyter Notebook containing the analysis, visualizations, and machine learning models.
- **data/**: Directory containing the datasets used for analysis.
- **results/**: Directory for storing output results, visualizations, and model performance metrics.
- **README.md**: This README file.

## Dataset

The dataset used in this analysis includes user behavior data related to mobile app usage and mental health scores. The scores are derived from a predictive model that classifies mental health based on app usage time.

### Data Description

- **User  ID**: Unique identifier for each user.
- **Device Model**: The model of the mobile device used.
- **Operating System**: The operating system of the device (e.g., Android, iOS).
- **App Usage Time (min/day)**: Average daily usage time of mobile applications in minutes.
- **Screen On Time (hours/day)**: Average daily screen-on time in hours.
- **Battery Drain (mAh/day)**: Average daily battery drain in milliampere-hours (mAh).
- **Number of Apps Installed**: Average number of applications installed on the device.
- **Data Usage (MB/day)**: Average daily data usage in megabytes (MB).
- **Age**: Age of the user.
- **Gender**: Gender of the user.
- **User  Behavior Class**: Classification of user behavior.

### Health Score Classification

which use this sheet metric https://www.webmd.com/mental-health/gaf-scale-facts as classificatory means

The health scores are transformed from a range of 0-100 to a range of 0-10, with classifications as follows:

| Original Range (0-100) | Transformed Range (0-10) | Classification   |
|-------------------------|--------------------------|-------------------|
| 0-10                    | 0.0-1.0                  | Very Low          |
| 11-20                   | 1.1-2.0                  | Low               |
| 21-30                   | 2.1-3.0                  | Moderately Low    |
| 31-40                   | 3.1-4.0                  | Moderate          |
| 41-50                   | 4.1-5.0                  | Moderately High   |
| 51-60                   | 5.1-6.0                  | High              |
| 61-70                   | 6.1-7.0                  | High              |
| 71-80                   | 7.1-8.0                  | Very High         |
| 81-90                   | 8.1-9.0                  | Excellent         |
| 91-100                  | 9.1-10.0                 | Superior          |

## Installation

To run the Jupyter Notebook, you will need to have R and Jupyter installed. You can set up your environment as follows:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/appusage-mentalhealth_data-analysis-with-ML.git
   cd appusage-mentalhealth_data-analysis-with-ML
   ```
2. upload csv file to the collab notebook:
3. run all cells
4. See the graphs in appusage-mentalhealth_data-analisys-with-ML/notus-js/index.html in a browser




   
