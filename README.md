# Elevate-Labs-Task-5
# Heart Disease Prediction using Decision Tree and Random Forest

This task involves building and analyzing classification models to predict the presence of heart disease using the UCI Heart Disease dataset. The models used are Decision Tree and Random Forest classifiers.

## Dataset

The dataset (`heart.csv`) contains 14 clinical features such as age, cholesterol, chest pain type, maximum heart rate, and more. The target variable indicates the presence (1) or absence (0) of heart disease.

## Task Workflow

1. **Data Loading and Exploration**  
   - Summary statistics and data types inspection  
   - Class distribution visualization  
   - Correlation heatmap to understand feature relationships  
   - Boxplots and countplots to visualize feature behavior against the target

2. **Preprocessing**  
   - Splitting data into training and testing sets (80/20 split)

3. **Model Building**  
   - Decision Tree Classifier  
   - Random Forest Classifier

4. **Model Evaluation**  
   - Accuracy score and classification report on test set  
   - Cross-validation with 5-fold CV for performance robustness  
   - Visualization of Decision Tree  
   - Overfitting analysis using max depth variation  
   - Feature importance plot for Random Forest

## Results

- Decision Tree Test Accuracy and CV Accuracy: **100.00%**
- Random Forest Test Accuracy and CV Accuracy: **99.71%**
- Top important features: `cp`, `ca`, `thalach`, `oldpeak`, `thal`

## Visualization Highlights

- Decision Tree visualization helps interpret the decision rules.
- Feature importance plot from Random Forest reveals the most influential clinical features.
- Overfitting analysis shows how model performance changes with tree depth.

## Requirements

- Python 3.x
- pandas, numpy, matplotlib, seaborn
- scikit-learn

## Conclusion

Both models perform exceptionally well on this dataset, with Random Forest offering better generalization due to its ensemble nature. This task demonstrates the application of tree-based classifiers for medical data analysis and feature interpretation.
