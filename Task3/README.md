# Task 3: Heart Disease Prediction

## Objective
Build a binary classification model to predict heart disease risk based on patient health data.

## Dataset
- **Source**: UCI Heart Disease Dataset
- **Patients**: 303
- **Features**: 13 clinical features
- **Target**: 0 = No Disease, 1 = Heart Disease
- **Disease Prevalence**: 45.5%

## Features Used
| Feature | Description |
|---------|-------------|
| age | Age in years |
| sex | Gender (0=female, 1=male) |
| cp | Chest pain type (0-3) |
| trestbps | Resting blood pressure |
| chol | Cholesterol level |
| fbs | Fasting blood sugar >120mg/dl |
| restecg | Resting ECG results |
| thalach | Maximum heart rate achieved |
| exang | Exercise induced angina |
| oldpeak | ST depression induced by exercise |
| slope | Slope of peak exercise ST segment |
| ca | Number of major vessels (0-3) |
| thal | Thalassemia (3=normal, 6=fixed, 7=reversible) |

## Models Tested
1. Logistic Regression
2. Decision Tree
3. Random Forest

## Results (Best Model: Random Forest)

| Metric | Score |
|--------|-------|
| Test Accuracy | 85.2% |
| Cross-Validation | 83.1% (±5.2%) |
| ROC-AUC | 0.912 |

## Top 5 Important Features
1. cp (Chest Pain Type)
2. ca (Number of Major Vessels)
3. thal (Thalassemia)
4. thalach (Max Heart Rate)
5. age

## Key Clinical Insights
- Chest pain type 3 has 85% disease rate
- High cholesterol (>240) increases risk by 35%
- Average age with disease: 56.7 vs 52.1 without
- Men have higher risk than women (55% vs 35%)

## Visualizations Included
1. Target distribution charts
2. Age distribution by disease
3. Correlation heatmap
4. Key features box plots
5. Chest pain analysis
6. ROC curves (all models)
7. Confusion matrices
8. Feature importance chart
9. Model comparison bar chart

## How to Use
1. Input patient's clinical measurements
2. Model predicts heart disease risk
3. High-risk patients flagged for further screening

## Limitations
- Small dataset (303 patients)
- Missing lifestyle factors (smoking, diet, exercise)
- Needs validation on diverse populations

## Files
- `Task3_Heart_Disease_Prediction.ipynb` - Complete implementation

## Author
[Your Name]
AI/ML Intern - DevelopersHub Corporation
