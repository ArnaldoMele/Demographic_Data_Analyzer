# Demographic Data Analyzer 

This project is part of the **Data Analysis with Python** certification by **freeCodeCamp**. It focuses on extracting insights from a 1994 Census database using **Pandas** to answer key demographic questions and identify social trends.

##  Dataset Description

The analysis is performed on a dataset with the following key columns:
* `age`, `sex`, and `race`: Core demographic identifiers.
* `education`: Educational attainment (Bachelors, Masters, etc.).
* `occupation`: Professional background.
* `hours-per-week`: Labor commitment.
* `native-country`: Geographic origin.
* `salary`: Income classification (`<=50K` or `>50K`).

##  Functionality

The script `demographic_data_analyzer.py` processes the data to answer specific research questions:

### 1. Population Statistics
* **Race Representation**: Counts the number of individuals for each race.
* **Gender Analysis**: Calculates the average age of men within the dataset.
* **Education Levels**: Determines the percentage of the population with a Bachelor's degree.

### 2. Income & Education Correlation
* **Advanced Education**: Calculates the percentage of people with advanced degrees (Bachelors, Masters, or Doctorate) who earn more than 50K.
* **Lower Education**: Calculates the percentage of people without advanced degrees (Bachelors, Masters, or Doctorate) who earn more than 50K.

### 3. Work & Geographic Insights
* **Minimum Work Hours**: Identifies the lowest number of hours worked per week and the percentage of those workers earning >50K.
* **Highest Earning Country**: Detects which country has the highest percentage of high earners and calculates that specific value.
* **Regional Analysis**: Identifies the most popular occupation for high earners specifically in India.

## Testing
* **Testing**: Unit tests are provided in `test_module.py` and can be run via `main.py` to ensure all calculations (averages, percentages, and counts) are accurate.

