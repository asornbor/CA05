# CA05_kNN_Recommender

## Overview

This project explores the application of the k-Nearest Neighbors (kNN) algorithm to build a recommendation system. The focus is on creating a movie recommendation system that suggests similar movies based on user preferences. This approach represents a practical application of machine learning techniques to enhance user experiences on digital platforms.

## Data Source

The dataset comprises movie ratings, providing insights into user preferences and behaviors:

 - **Data Characteristics:** Includes user IDs, movie IDs, ratings, movie types.
 - **Types of Movies:** 7 Types of movies.
 - **IMBD Rating scale:** 1 to 10, where 10 represents the highest affinity.

Data can be accessed at the following URL:
[https://github.com/ArinB/MSBA-CA-Data/raw/main/CA05/movies_recommendation_data.csv](https://github.com/ArinB/MSBA-CA-Data/raw/main/CA05/movies_recommendation_data.csv)

## Objectives

 1. **Data Preparation:** Load the dataset and perform necessary preprocessing steps, including handling missing values, encoding categorical variables, and normalizing the data if required.

 2. **Building the Recommendation Model:**
      - Utilize the kNN algorithm to develop the recommendation system. The model should identify similar movies based on user ratings.
      - Optimize the model by selecting an appropriate value for k (the number of neighbors).

 3. **Recommendation Demonstration:** Demonstrate the recommendation system by selecting a few movies and displaying the top recommendations for each.

## Deliverables

 - A fully executed Jupyter notebook that includes the model development and evaluation process.
 - This README file, detailing the project's overview, data source, objectives, methodology, and outcomes.

## Installation and Usage

- Ensure Jupyter Notebook or JupyterLab is installed to run the `.ipynb` file. Dependencies include `pandas`, `numpy`, and `scikit-learn`. Install these packages via pip or conda if not already present.

      pip install pandas numpy scikit-learn 

To run the notebook:

 *  Clone the repository or download the .ipynb file.
 *  Open the notebook in Jupyter Notebook/Lab.
 *  Execute the cells in sequence to conduct the analysis and view the recommendations. Start from the beginning for a comprehensive step-by-step execution.
