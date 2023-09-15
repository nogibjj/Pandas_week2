# Mini-Project 2: Analyzing Car Data with Pandas
### by Titus Robin
[![CI](https://github.com/nogibjj/Pandas_week2/actions/workflows/python_ci_cd.yml/badge.svg)](https://github.com/nogibjj/Pandas_week2/actions/workflows/python_ci_cd.yml)

## Purpose

The objective of this project is to leverage Pandas to load and manipulate a DataFrame. We have employed a `pd.DataFrame` as sample data, conducted various data analysis tasks using functions like `pandas_descriptive_stats_*()`, and created a scatter plot for data visualization.

## Dataset

Our dataset focuses on information related to different car models, encompassing attributes such as:

- Miles per gallon (mpg)
- Number of cylinders (cylinders)
- Gear type (gear)
- And more...

## Functions

We've developed a set of functions designed to extract essential statistics from the Pandas DataFrame:

1. `pandas_descriptive_stat_mean`: Computes the mean value of a specified column.
2. `pandas_descriptive_stat_median`: Calculates the median value of a specified column.
3. `pandas_descriptive_stat_std`: Determines the standard deviation of a specified column.
4. `pandas_descriptive_stat_max`: Finds the maximum value of a specified column.

Additionally, a dedicated test file is provided to validate the accuracy of these descriptive statistics.

## Visualization

To gain valuable insights from the dataset, we've crafted a scatter plot that visually compares two variables: "Miles per Gallon" and "Horsepower." This visualization aids in understanding the relationship between these attributes.
<img width="615" alt="Screen Shot 2023-09-13 at 4 38 39 PM" src="https://github.com/nogibjj/Pandas_week2/assets/143838819/0da1ad49-08d2-4538-8e07-39ce74937a98">

## Automation

We have implemented automation practices and tools to enhance efficiency and maintain code quality:

1. **Devcontainer**: Inside the `.devcontainer` folder, you'll find two crucial files:

   - `Dockerfile`: This file defines environment variables to ensure a consistent development environment for all collaborators, mitigating potential conflicts and version mismatches.
   - `devcontainer.json`: A JSON file specifying environment variables and installed extensions within the virtual environment.

2. **Makefile**: Our `Makefile` contains instructions for several tasks, including:

   - Installing required packages (specified in `requirements.txt`).
   - Enforcing code formatting using the `black` formatter.
   - Running tests for functions (files starting with "Check...").
   - Linting the code with `pylint`.

3. **GitHub Actions**: We've integrated GitHub Actions using the `main.yml` file, enabling automated tasks based on events such as pushes and pull requests. The workflow covers installing packages, code formatting, linting, and testing.

4. **Requirements.txt**: The `requirements.txt` file enumerates the essential Python packages for the project. While it currently comprises generic Python packages, it can be tailored to include specific dependencies as required for future project scopes.

This project is aimed at demonstrating efficient data analysis using the Pandas library while emphasizing code quality through automation and testing.


