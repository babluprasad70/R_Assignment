**Movehub City Ranking**

*Overview:*
This repository contains R scripts (Quarto) for analyzing and modeling based on factors affecting the quality of life and cost of living in different cities. The analysis focuses on predicting Movehub Rating, a measure of quality of life, based on various features such as cost of living, crime rate, and environmental factors.

*Contents:*
Quarto script: Main R script containing the analysis, testing, and modeling code.
File directory: Contains the 3 datasets used for analysis.
README.md: Provides an overview of the project.

*Different aataset Merging Visualization:*
![Screenshot 2024-04-04 015541](https://github.com/babluprasad70/R_Assignment/assets/126379428/2fb4f042-ec57-463e-bf2b-b0ed885237e9)

*Task performed:*

<img width="620" alt="Task Performed_mermaid" src="https://github.com/babluprasad70/R_Assignment/assets/126379428/da6247cb-11dd-4a2a-8b26-e7aa208c37da">


*Running the Analysis:*
To run the analysis:

Install the required R packages if not already installed. (Ensure to install leaflet, ggplot2, corrplot, and MASS packages)
Execute the script to perform the analysis.

*Description:*
Basic analysis: Includes boxplot and ANOVA tests to check for significant effects.
Geographical Distribution Mapping: Creates Leaflet maps to visualize the geographical distribution of top cities based on quality of life and crime rating.
Correlation Analysis: Calculates the overall correlation between different numerical features and Movehub Rating.
Linear Regression Modeling: Applies linear regression modeling to predict Movehub Rating based on all available features.
Stepwise Regression Modeling: Implements stepwise regression to select significant features for the linear model, comparing its performance with the initial linear model.

*Results:*
The final Stepwise Regression model achieved a better R-squared score compared to the initial linear model, indicating improved performance in predicting Movehub Rating.

*Data Source:*
The dataset used in this analysis can be found on Kaggle, as well as mentioned in the Quarto file. It includes information on various features such as cost of living, crime rate, and environmental factors for different cities.
- https://www.kaggle.com/datasets/blitzr/movehub-city-rankings
- https://simplemaps.com/data/world-cities
