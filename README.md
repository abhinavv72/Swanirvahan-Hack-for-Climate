# Swanirvahan Hack for Climate 2.0 - ICT IOC
## Helping Chemical Engineers Create Stronger Cement for Sustainable Applications

### Overview
In the "Swanirvahan Hack for Climate 2.0 - ICT IOC" project, we aim to develop machine learning models that can accurately predict the strength of cement, which is a crucial factor in sustainable construction. Our objective was to create models that minimize the Root Mean Squared Error (RMSE) between the predicted and actual cement strength, using a provided dataset of various components and features related to cement production.

### Data Description
- `train.csv`: This file contains the training dataset, where the target variable is the 'Strength' of the cement. It includes various features that might influence the strength, such as the amounts of different components used in the cement mixture.
- `test.csv`: The test dataset for which we need to predict the 'Strength'. This file contains the same features as the training set but without the target variable.
- `sample_submission.csv`: A sample submission file in the correct format, demonstrating how to structure predictions for the competition.

### Models
We employed several advanced machine learning models and techniques to address this challenge:
- **Gradient Boosting Regressor**: This model is known for its effectiveness in handling tabular data and its ability to capture complex non-linear relationships.
- **Feature Engineering**: We implemented extensive feature engineering, including creating interaction features and applying non-linear transformations to better capture the underlying patterns in the data.
- **Hyperparameter Tuning**: We fine-tuned the models using techniques like grid search to optimize their performance.
- **Ensemble Techniques**: We experimented with ensemble methods like stacking and blending to combine the strengths of multiple individual models.

### Installation
To run this project, ensure you have Python installed on your system. You can then install the necessary libraries using the following command:
```bash
pip install pandas scikit-learn xgboost
