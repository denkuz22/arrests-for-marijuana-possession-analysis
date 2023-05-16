# Data Analysis for Marijuana Arrests

This project focuses on the analysis of data related to marijuana arrests. It aims to provide insights and uncover patterns and trends in marijuana-related arrests using a data-driven approach.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Data Analysis](#data-analysis)
- [Results and Findings](#results-and-findings)
- [How to Use](#how-to-use)
- [Dependencies](#dependencies)

## Project Overview

Marijuana arrests have been a topic of interest and debate in many regions. This project aims to explore the data related to marijuana arrests and conduct a thorough analysis to gain insights into various aspects of marijuana-related law enforcement.

The inital exploratory questions of this project include the following:

- 1 What is the distribution of the "released" variable? How many arrestees were released with a summons versus not released?
- 2 How does the distribution of the "colour" variable look like? What is the racial composition of the arrestees?
- 3 How does the number of observations vary across different years in the "year" variable?
- 4 What is the range of ages among the arrestees? Are there any outliers?
- 5 What is the distribution of the "sex" variable? How many female and male arrestees are there?
- 6 How many arrestees are employed versus unemployed?
- 7 What is the citizenship status of the arrestees? How many are citizens and how many are not?
- 8 How many police databases, on average, did the arrestees' names appear in the "checks" variable?
- 9 Is there any correlation between the "released" variable and other variables such as race, age, sex, employment, citizenship, or number of checks?
- 10 Is there a significant difference in the average number of checks between different racial groups?
- 11 Is there a significant difference in the average age between male and female arrestees?
- 12 Are there any notable trends or patterns in the data over the years?

## Data Source

The analysis is based on a comprehensive dataset obtained from [[source](https://www.kaggle.com/datasets/utkarshx27/arrests-for-marijuana-possession/code)], which provides detailed information about marijuana-related arrests. The dataset includes relevant attributes such as year, race, whether arrestee was released or not, age, gender, whether employed or unemployed, wether a citizen or not, and number of police data bases (of previous arrests, previous convictions, parole status, etc. – 6 in all) on which the arrestee's name appeared.

## Data Analysis

The project utilizes various data analysis techniques, including descriptive statistics, data visualization, and exploratory data analysis (EDA). These techniques help uncover meaningful insights and patterns within the dataset, enabling a deeper understanding of marijuana arrests.

Python programming language and popular libraries such as panda and Plotly are employed to perform the data analysis tasks. The Jupyter Notebook environment is used to document and present the analysis process.

## Results and Findings

Throughout the analysis, several key findings and insights emerge, including:

- Temporal trends in marijuana arrests, indicating changes in enforcement patterns over time
- Demographic disparities, such as variations in arrest rates based on age, gender, and race
- Geographical hotspots for marijuana-related arrests, highlighting areas with higher enforcement activities
- Potential effects of marijuana legalization on arrest rates

The analysis provides a comprehensive understanding of marijuana arrests, offering valuable insights into the social, legal, and law enforcement aspects of this topic.

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
