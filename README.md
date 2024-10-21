# Junk Property Classification

This project is focused on classifying whether a property is "junk" or not based on various features. The dataset contains information like property type, location, price index, and other relevant details. We use a **Random Forest Classifier** to predict the probability of a property being classified as junk.

## Project Overview

The goal of this project is to predict whether a property qualifies as junk based on given features using a machine learning model. We employ a **Random Forest** model, fine-tuned using parameters like `max_depth`, `min_samples_leaf`, `min_samples_split`, and `n_estimators`. The data undergoes preprocessing steps before being fed into the model.

## Key Steps

1. **Data Preprocessing**: 
   - We clean and prepare the dataset for model training by handling missing values and adjusting features.
   
2. **Model Training**: 
   - The `RandomForestClassifier` is used to build the model. We experiment with different parameter combinations to find the best fit for our data.

3. **Prediction**: 
   - After training, the model predicts the probability of a property being "junk". The results are rounded to three decimal places and added back to the dataset.

4. **Output**:
   - The final predictions, including the junk classification probabilities, are saved in a CSV file.

## Files

- `Junk_Property.ipynb`: The main notebook containing the code for data preprocessing, model training, and prediction.
- `Amit_Jangir_2(P5).csv`: The output file containing predictions for each property.
