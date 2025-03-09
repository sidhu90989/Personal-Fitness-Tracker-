# Personal Fitness Tracker 

This repository contains a Jupyter Notebook (`fitness_tracker.ipynb`) that performs an analysis of fitness-related data. The dataset includes information about users' exercise routines, calories burned, and other related metrics. The notebook explores the dataset, performs data cleaning, visualization, and provides insights into the data.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset Overview](#dataset-overview)
3. [Data Cleaning](#data-cleaning)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
5. [Visualization](#visualization)
6. [Conclusion](#conclusion)
7. [Requirements](#requirements)
8. [Usage](#usage)

## Introduction
The goal of this project is to analyze fitness data to understand the relationship between various factors such as age, gender, height, weight, exercise duration, heart rate, body temperature, and calories burned. The analysis aims to provide insights that could help in predicting calories burned based on these factors.

## Dataset Overview
The dataset consists of two main CSV files:
- `calories.csv`: Contains user IDs and the corresponding calories burned.
- `exercise.csv`: Contains user IDs, gender, age, height, weight, exercise duration, heart rate, and body temperature.

The combined dataset has 15,000 instances and 9 columns.

### Columns Description
1. **User_ID**: Unique identifier for each user.
2. **Gender**: Gender of the user.
3. **Age**: Age of the user.
4. **Height**: Height of the user in centimeters.
5. **Weight**: Weight of the user in kilograms.
6. **Duration**: Duration of the user's exercise/activity.
7. **Heart_Rate**: Heart rate per minute of the user.
8. **Body_Temp**: Body temperature of the user in Celsius.
9. **Calories**: Calories burned in kilocalories.

## Data Cleaning
The notebook performs basic data cleaning steps, including:
- Merging the `calories.csv` and `exercise.csv` datasets on `User_ID`.
- Checking for missing values and ensuring data integrity.

## Exploratory Data Analysis (EDA)
The notebook includes an exploratory data analysis to understand the distribution of various features:
- Descriptive statistics for numerical columns.
- Visualization of data distributions using box plots.
- Checking for outliers and understanding their impact on the dataset.

## Visualization
The notebook uses various visualization techniques to explore the data:
- **Box Plots**: To visualize the distribution of numerical features and identify outliers.
- **Heatmap**: To check for null values in the dataset.

## Conclusion
The analysis provides a comprehensive overview of the fitness dataset, highlighting key insights and relationships between different features. The visualizations help in understanding the data distribution and identifying potential areas for further analysis or model building.

## Requirements
To run the notebook, you need the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install these libraries using pip:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fitness-tracker-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd fitness-tracker-analysis
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook fitness_tracker.ipynb
   ```
5. Run the notebook cells to perform the analysis.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- The dataset used in this analysis is sourced from [Kaggle].
- Special thanks to the open-source community for providing the tools and libraries used in this project.

---

