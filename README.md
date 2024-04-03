**Movehube City Ranking**

*Overview:*

This repository contains R scripts for analyzing and modeling on the basis of factors affecting the quality of life and cost of living in different cities. The analysis focuses on predicting Movehub Rating, a measure of quality of life, based on various features such as cost of living, crime rate, and environmental factors.

Contents:
Quarto script: Main R script containing the analysis and modeling code.
File: Directory containing the dataset used for analysis.
README.md: This file providing an overview of the project.

![data_stream_flow](https://github.com/babluprasad70/R_Assignment/assets/126379428/0052cc96-bd62-4c27-be08-d086addef24e)


To run the analysis:

Installed the required R packages if not already installed. (Ensure to install leaflet, ggplot2, corrplot, and MASS packages)
Execute the script to perform the analysis.

Description:

- Some basic analysis like boxplot, AVONA test for checking signifiant affect.
- Geographical Distribution Mapping: The script creates Leaflet maps to visualize the geographical distribution of top cities based on quality of life and crime rating.
- Correlation Analysis: Calculates the overall correlation between different numerical features and Movehub Rating.
- Linear Regression Modeling: Applies linear regression modeling to predict Movehub Rating based on all available features.
- Stepwise Regression Modeling: Implements stepwise regression to select significant features for the linear model, comparing its performance with the initial linear model.

Results:
The final selected model achieved a better R-squared score compared to the initial linear model, indicating improved performance in predicting Movehub Rating.

Data Source
The dataset used in this analysis can be found in the kaggle as well same i have mentioned in Quarto file It includes information on various features such as cost of living, crime rate, and environmental factors,etc for different cities.
