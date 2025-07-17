# Risk Tier Classification Based on User Behavior

This project focuses on classifying users into risk tiers**Low**, **Medium**, and **High**—based on synthetic behavioral data using machine learning models. The classification helps in identifying potentially risky users for applications such as credit scoring, fraud detection, and user access control in cybersecurity systems.

## Objective

To  evaluate  performance of classification models that can accurately segment users based on their behavioral patterns into different risk categories.

## Models Used

- **Logistic Regression**
- **Random Forest Classifier**

Both models were trained and tested on the dataset, and performance metrics such as accuracy, precision, recall, F1-score, and confusion matrix were used for evaluation.

## Methodology

1. **Data Preparation**
   - Loaded and explored synthetic user behavior dataset.
   - Performed EDA

2. **Model Training**
   - Trained Logistic Regression and Random Forest classifiers.
   - Used `train_test_split` for model validation.
3. **Hyperparameter Tuning**
   - Applied **GridSearchCV** to both models to find optimal parameters.
   - Improved performance by fine-tuning model settings such as:
     - `C` for Logistic Regression
     - `n_estimators`, `max_depth`, etc., for Random Forest

4. **Model Evaluation**
   - Confusion matrices and classification reports were generated.
   - Performance comparison was done visually using bar plots.

## Results

- Random Forest outperformed Logistic Regression in terms of all evaluation metrics.
- Visual comparison of metrics highlighted the effectiveness of the ensemble approach for this classification task.

