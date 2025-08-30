# Housing Price Prediction: A Machine Learning Approach
This repository contains a Jupyter Notebook (dang-huy-bui-assignment-3 (2).ipynb) that demonstrates a complete machine learning workflow for predicting housing prices. The project is a solution to a classic Kaggle competition, using a comprehensive pipeline from data loading and preprocessing to model training and submission file generation.

Project Structure
The Jupyter Notebook is organized into the following key steps:

Loading Data: Imports the necessary libraries and loads the training and testing datasets from CSV files.

Data Preprocessing: Handles missing values and performs feature engineering to prepare the data for the model. This includes dropping certain columns and applying transformations.

Model Training: Utilizes a RandomForestRegressor model to train on the preprocessed training data. The model is configured with specific parameters to optimize its performance.

Prediction: Uses the trained model to generate price predictions for the test dataset.

Evaluation & Submission: Creates a submission.csv file in the output/ directory, formatted for submission to the Kaggle competition. It includes a sample of the final output to verify the format.

Dependencies
This notebook requires the following Python libraries:

pandas

numpy

sklearn (Scikit-learn)
