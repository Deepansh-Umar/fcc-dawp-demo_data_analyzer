# Demographic Data Analyzer

This project analyzes demographic data from the 1994 Census database using Pandas.  
It provides insights into race distribution, education levels, income, work hours, and occupations.

## Problem Statement

Write a function called `calculate_demographic_data()` that analyzes a dataset and outputs the following:

- Count of each race represented in the dataset.
- Average age of men.
- Percentage of people with a Bachelor's degree.
- Percentage of people with advanced education (Bachelors, Masters, Doctorate) earning more than 50K.
- Percentage of people without advanced education earning more than 50K.
- Minimum number of hours worked per week.
- Percentage of people working minimum hours who earn more than 50K.
- The country with the highest percentage of people earning more than 50K, and that percentage.
- The most popular occupation among people who earn more than 50K in India.

## Requirements

- Use Pandas for data analysis.
- Round all decimal values to the nearest tenth.
- Read data from the provided CSV file (`adult.data.csv`).
- Return a dictionary containing all calculated values.
- Optionally print the results if `print_data=True`.

## Dataset Sample

| age | workclass        | fnlwgt | education   | education-num | marital-status     | occupation        | relationship   | race   | sex    | capital-gain | capital-loss | hours-per-week | native-country | salary  |
|-----|------------------|--------|-------------|---------------|--------------------|-------------------|----------------|--------|--------|--------------|--------------|---------------|----------------|---------|
| 39  | State-gov        | 77516  | Bachelors   | 13            | Never-married      | Adm-clerical      | Not-in-family  | White  | Male   | 2174         | 0            | 40            | United-States  | <=50K   |
| 50  | Self-emp-not-inc | 83311  | Bachelors   | 13            | Married-civ-spouse | Exec-managerial   | Husband        | White  | Male   | 0            | 0            | 13            | United-States  | <=50K   |
| ... | ...              | ...    | ...         | ...           | ...                | ...               | ...            | ...    | ...    | ...          | ...          | ...           | ...            | ...     |

---

Feel free to reach out if you want me to add installation or usage instructions!
