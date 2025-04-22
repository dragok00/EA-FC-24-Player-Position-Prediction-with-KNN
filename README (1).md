
# EA FC Player Position Prediction with KNN

This project uses a K-Nearest Neighbors (KNN) classifier to predict a football player’s position based on their in-game attributes from EA FC player data.

## Overview

- **Goal:** Predict the playing position (e.g., ST, CM, CB) of players using selected performance attributes.
- **Dataset:** EA FC player statistics (presumably from Kaggle or a similar source).
- **Model:** KNN classifier trained on normalized feature vectors.
- **Notebook:** Built and run in Google Colab.

## Key Features

- Data cleaning and preprocessing
- Feature selection and normalization
- Train/test split
- KNN implementation with hyperparameter tuning
- Model evaluation (accuracy, confusion matrix)

## Usage

1. Open the notebook in Google Colab.
2. Upload the dataset or mount Google Drive.
3. Run all cells to preprocess data and train the model.
4. Modify `k` to experiment with different neighbor values.

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Output

- Model accuracy score
- Confusion matrix visualization
- Predicted vs actual position comparison
