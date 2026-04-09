# Spotify Genre Prediction with Machine Learning

## Overview
This project develops an end-to-end machine learning pipeline for Spotify track genre prediction using structured audio features and metadata. The work focuses on data preprocessing, feature engineering, model comparison, hyperparameter tuning, and performance evaluation to build a reliable music classification workflow.

## Objective
The goal of this project is to predict the genre of Spotify tracks from a combination of numerical audio attributes and text-based metadata. The project was designed to explore how feature engineering and model selection can improve classification performance on real-world music data.

## Dataset
The dataset contains Spotify track-level information, including audio characteristics and metadata such as artist and title-related fields. These features were used to build supervised learning models for genre prediction.

## Project Workflow
1. Performed exploratory data analysis to understand feature distributions, missing values, and target structure.
2. Built feature engineering steps to create more informative predictors from the original dataset.
3. Applied preprocessing pipelines for text and numerical features.
4. Trained and compared multiple machine learning models.
5. Tuned model settings and evaluated performance on validation and test-style outputs.

## Feature Engineering
Key feature engineering steps included:
- Creating derived variables such as song age and transformed duration features.
- Combining raw audio variables into richer predictors.
- Generating text-based features from metadata.
- Adding cluster-distance style features to improve representation of track similarity.

## Modeling Approach
The project compares multiple machine learning models for genre classification, including:
- Linear SVC
- Logistic Regression
- Random Forest
- AdaBoost

A structured preprocessing pipeline was used to handle text and numeric features together, making the workflow reproducible and easier to evaluate.

## Tools and Libraries
- Python
- pandas
- NumPy
- scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Results
The final workflow showed that carefully engineered features improved model usefulness and helped simpler models generalize better. Among the tested approaches, linear models performed strongly and delivered competitive validation and leaderboard-style results.

## Skills Demonstrated
- End-to-end machine learning workflow design
- Data cleaning and preprocessing
- Feature engineering
- Text and numerical pipeline integration
- Model comparison and evaluation
- Hyperparameter tuning
- Analytical communication of results

## Future Improvements
Possible next steps for this project include:
- testing additional ensemble and gradient boosting methods
- improving text feature extraction from metadata
- expanding feature engineering with domain-specific music features
- refining class imbalance handling and validation strategy

## How to Run
1. Open the notebook in Jupyter Notebook or JupyterLab.
2. Install the required Python libraries.
3. Run the notebook cells in sequence to reproduce preprocessing, training, and evaluation steps.

## Project Summary
This project demonstrates the ability to take a raw music dataset and turn it into a structured machine learning pipeline with clear analytical reasoning, reproducible preprocessing, and measurable predictive performance.
