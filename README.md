Titanic Mini-EDA Project

Project Overview

This project involves performing a comprehensive Exploratory Data Analysis (EDA) on the Titanic dataset to uncover deeper insights into passenger survival rates. The analysis focuses on data cleaning, feature engineering, and advanced visualizations to tell a data-driven story.

Objectives

The primary goal is to build a Jupyter Notebook that delivers cleaned data and professional visualizations. Key tasks include:
  Data Cleaning: Handling missing values through imputation and removing irrelevant features.
  Feature Engineering: Using groupby and custom categories to find deeper insights.
  Storytelling: Creating multiple visualizations to represent the data's narrative.
  
Requirements

1. Data Cleaning
   
   Age Imputation: Missing age values are filled using the mean age of the passengers.
   Column Removal: Irrelevant columns, such as "Cabin," are dropped to streamline the analysis.
2. Analysis Questions
   
   The project explores survival rates across several dimensions:
   Age Group: Categorizing passengers into groups like Child, Teen, and Adult.
   Embarkation Port: Analyzing survival based on where passengers boarded the ship.
   Family Size: Calculating family size as the sum of siblings, spouses, parents, and children (SibSp + Parch).
   
3. Visualizations
   
   The following professional visualizations are included:
   
   Age Distribution: A histogram showing the age spread of passengers.
   Correlation Heatmap: A heatmap to identify relationships between different dataset features.
   Survival by Family Size: A bar plot visualizing survival probability based on family size.
   
Technologies Used

   Python: The primary programming language.
   Pandas: Used for data manipulation and cleaning.
   Seaborn & Matplotlib: Used for creating advanced and professional visualizations.

How to Run

To ensure portability and ease of use, this project utilizes the built-in Titanic dataset from the Seaborn library, eliminating the need for local file management or external downloads.
    Open the Jupyter Notebook (.ipynb).
    Install the required libraries: pip install pandas seaborn matplotlib.
    Run the cells sequentially to perform the analysis and generate visualizations.
