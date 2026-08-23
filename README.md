# Geothermal Temperature Prediction

## Project Overview
An interactive Machine learning project for predicting subsurface temperature using Python and scikit-learn based on geological and well related data.

## Problem Statement
Accurate estimation of subsurface temperature is important for geothermal resource assessment. This project investigates whethermachine learning can be used to predict temperature from available subsurface parameters.

## Objectives
Explore the geothermal dataset
Clean and preprocess the data
Train machine learning models
Evaluate model performance
Identify the most important predictive features

## Dataset
The dataset contains measurements of subsurface temperature, depth, longitude and latitude of the wells, and other relevant parameters.

Source: https://geology.utah.gov/energy-minerals/geothermal/ngds/

## Methodology

The project follows these steps:

1. Data collection
2. Data cleaning
3. Exploratory data analysis
4. Feature selection
5. Model training
6. Model evaluation
7. Results visualization

## Tools and Technologies
**Python**
**NumPy**
**Pandas**
**Matplotlib**
**Scikit-learn**
**Jupyter Notebook**

## Results
## Key Findings
**Finding 1**
The linear regression model achieved an **R² score of 0.613**, indicating that drilling depth explains approximately 61% of the variation in corrected subsurface temperature within the test dataset.

**Finding 2**
The model achieved a **Mean Absolute Error (MAE) of 13.72°C**, meaning that the predicted temperatures differed from the observed temperatures by approximately 13.7°C on average.

**Finding 3**
The **Root Mean Squared Error (RMSE) was 18.16°C**, indicating that larger prediction errors were present in the test dataset.

The results suggest that there is a meaningful relationship between drilling depth and subsurface temperature, but depth alone is not sufficient to accurately explain all temperature variations.

The results also suggest that incorporating additional geological, spatial, and geothermal parameters could potentially improve predictive performance.

## Limitations
The model uses **drilling depth as the primary predictor**, while subsurface temperature can also be influenced by geological structure, lithology, fluid movement, geothermal gradient, elevation, and spatial variations.

The relatively high **MAE (13.72°C)** and **RMSE (18.16°C)** indicate that the model has substantial prediction errors and should not be considered sufficiently accurate for direct geothermal resource assessment without further development.

Only a **linear regression model** was evaluated in this initial study. More complex machine learning models may be able to capture nonlinear relationships between depth and temperature.

The quality and completeness of the input dataset can influence the reliability of the predictions.

The model's performance may not generalize to other geothermal fields or geological settings because the relationship between depth and temperature can vary spatially and geologically.

## Future Improvements
The model performance was evaluated using a single train-test split. Further validation, such as **cross-validation**, would provide a more robust estimate of model performance.

Future work should investigate additional predictor variables and compare multiple machine learning algorithms to determine whether prediction accuracy can be improved.

## How to Run

Clone the repository and install the required Python packages.

## Author
Emeryne Odero
MSc Energy Engineering
