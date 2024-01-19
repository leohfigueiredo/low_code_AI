# low_code_AI
Codes for AI - Jupyter notebooks

# Heart Disease Mortality Data Analysis

This repository contains a Jupyter Notebook (`Chapter_2.ipynb`) that explores and analyzes the "Heart Disease Mortality Data Among US Adults (35+) by State/Territory and County -- 2018-2020" dataset from the Centers for Disease Control and Prevention (CDC).

## Dataset Information

The dataset is loaded into a Pandas dataframe and includes information about heart disease mortality rates, stratified by various factors such as race, ethnicity, and geographic location.

## Notebook Overview

1. **Loading the Dataset:**
   - Download the dataset from the CDC using its API and load it into a Pandas dataframe.

2. **Data Exploration:**
   - View the first five rows of the dataset using the `head()` method.
   - Use the `info()` method to display information about each column, including data types and null values.

3. **Downloading Data to Colab:**
   - Download the dataset as a CSV file to the Colab Notebook environment using the `!wget` command.

4. **Loading Data from CSV:**
   - Load the downloaded CSV file into a new Pandas dataframe.
   - Display the first five rows and information about the dataframe.

5. **Handling Null Values:**
   - Check for null values in each column and display the count of null values.
   - Explore the unique values in the "Stratification2" column.

6. **Data Visualization:**
   - Use Seaborn to create a violin plot for the "Stratification2" feature.
   - Generate a distribution plot for heart disease counts.

## How to Use

1. Open the Jupyter Notebook (`Chapter_2.ipynb`) in your preferred environment.
2. Execute the cells sequentially to run the code and visualize the results.
3. Modify and extend the analysis based on your research questions or objectives.

## Dependencies

- Python 3
- Pandas
- Seaborn
- Jupyter Notebook

## Note

- The dataset is sourced from the CDC and is publicly available. Ensure compliance with the data usage policies outlined by the CDC.

Feel free to explore, analyze, and contribute to this project. If you have any questions or suggestions, please open an issue or reach out to the project maintainers.
