# EL_Task5

# Heart Disease Prediction using Decision Trees and Random Forests

This project uses machine learning techniques to predict the presence of heart disease based on clinical features. The dataset used is the **Heart Disease** dataset (commonly from the UCI repository), and the analysis is performed using Decision Tree and Random Forest classifiers.

## 📊 Dataset

The dataset (`heart.csv`) includes the following features:

- `age`, `sex`, `cp` (chest pain type), `trestbps` (resting blood pressure), `chol` (cholesterol), `fbs` (fasting blood sugar), etc.
- `target`: 1 indicates presence of heart disease, 0 indicates absence.

## Project Workflow

1. **Train a Decision Tree Classifier**  
   - Visualizes the trained decision tree.
   
2. **Overfitting Analysis**  
   - Trains trees of varying depth and plots train/test accuracy to show overfitting or underfitting.
   
3. **Train a Random Forest Classifier**  
   - Compares performance with the Decision Tree.

4. **Feature Importance Visualization**  
   - Displays which features most influence model predictions.

5. **Model Evaluation with Cross-Validation**  
   - Evaluates models using 5-fold cross-validation for robust accuracy measurement.

## 📈 Performance

| Metric        | Decision Tree |  Random Forest |	
|---------------|---------------|----------------|
| Accuracy      | 0.976         | 0.976          |
| Precision     | 0.957         | 0.977          |
| Recall        | 1             | 0.977          |
| F1-score      | 0.978         | 0.977          |

> Values will vary slightly depending on the train/test split.

## 📊 Visualization

- Variation of accuracy of the Decision Tree Classifier model vs max_depth
- Feature importances from the trained Random Forest.

