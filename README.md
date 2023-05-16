# Data Analysis for Marijuana Arrests

This project focuses on the analysis of data related to marijuana arrests. It aims to provide insights and uncover patterns and trends in marijuana-related arrests using a data-driven approach.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Data Analysis](#data-analysis)
- [How to Use](#how-to-use)
- [Dependencies](#dependencies)

## Project Overview

Marijuana arrests have been a topic of interest and debate in many regions. This project aims to explore the data related to marijuana arrests and conduct a thorough analysis to gain insights into various aspects of marijuana-related law enforcement.

The inital exploratory questions of this project include the following:

-  What is the distribution of the "released" variable? How many arrestees were released with a summons versus not released?
-  How does the distribution of the "colour" variable look like? What is the racial composition of the arrestees?
-  How does the number of observations vary across different years in the "year" variable?
-  What is the range of ages among the arrestees? Are there any outliers?
-  What is the distribution of the "sex" variable? How many female and male arrestees are there?
-  How many arrestees are employed versus unemployed?
-  What is the citizenship status of the arrestees? How many are citizens and how many are not?
-  How many police databases, on average, did the arrestees' names appear in the "checks" variable?
-  Is there any correlation between the "released" variable and other variables such as race, age, sex, employment, citizenship, or number of checks?
-  Is there a significant difference in the average number of checks between different racial groups?
-  Is there a significant difference in the average age between male and female arrestees?
-  Are there any notable trends or patterns in the data over the years?

## Data Source

The analysis is based on a comprehensive dataset obtained from [[source](https://www.kaggle.com/datasets/utkarshx27/arrests-for-marijuana-possession/code)], which provides detailed information about marijuana-related arrests. The dataset includes relevant attributes such as year, race, whether arrestee was released or not, age, gender, whether employed or unemployed, wether a citizen or not, and number of police data bases (of previous arrests, previous convictions, parole status, etc. – 6 in all) on which the arrestee's name appeared.

## Data Analysis

The project utilizes various data analysis techniques, including descriptive statistics, data visualization, and exploratory data analysis (EDA). These techniques help uncover meaningful insights and patterns within the dataset, enabling a deeper understanding of marijuana arrests.

Python programming language and popular libraries such as panda and Plotly are employed to perform the data analysis tasks. The Jupyter Notebook environment is used to document and present the analysis process.

## How to Use

To reproduce or further explore the analysis:

1. Clone this repository to your local machine.
2. Ensure you have the required dependencies mentioned in the next section.
3. Open the Jupyter Notebooks in the `notebooks/` directory using Jupyter Notebook or JupyterLab.
4. Execute the code cells in the notebooks to perform the analysis and generate visualizations.
5. Feel free to modify the notebooks or add your own analysis as needed.

## Dependencies

The following dependencies are required to run the analysis notebooks:

- Python
- pandas
- Plotly 
- Jupyter Notebook 

Please ensure that these dependencies are installed in your Python environment before running the notebooks
