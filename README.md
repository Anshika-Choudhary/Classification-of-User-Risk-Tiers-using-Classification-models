# Classification-of-User-Risk-Tiers-using-Classification-models
# Risk Tier Classification Based on User Behavior

This project involves classifying users into **risk tiers** (e.g., Low, Medium, High) based on their behavior patterns using **Machine Learning models** -specifically **Logistic Regression** and **Random Forest**. The dataset is synthetically generated to simulate user behavioral features.

---

## Objectives

- Predict user **risk tier** from behavioral data
- Compare performance of **Logistic Regression** and **Random Forest**
- Tune models using **GridSearchCV**
- Evaluate using key classification metrics
- Export final predictions to a CSV file


##  Dataset

The dataset used is synthetic and simulates behavioral features such as:
- Login attempts
- Transaction volume
- Session duration
- Activity frequency
- ... (and more)

Target variable: `risk_tier` (categorical: e.g., `Low`, `Medium`, `High`)

---

## ⚙️ Models Used

| Model                | Type             | Notes                          |
|---------------------|------------------|--------------------------------|
| Logistic Regression | Linear Model     | Scaled; interpreted probabilistically |
| Random Forest       | Ensemble (Tree)  | Non-linear; handles feature interactions |

---

## Evaluation Metrics

- **Accuracy**
- **F1-Score (Macro Average)**
- **Confusion Matrix**
- **GridSearchCV** (5-fold) for hyperparameter tuning

---

## Output Visuals

- Confusion Matrix Heatmaps for both models
- Bar plot comparing Accuracy and F1-Score

