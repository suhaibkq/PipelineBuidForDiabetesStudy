# 🤖 Diabetes Prediction Using ML Pipeline

## 📌 Project Overview

This project demonstrates how to streamline a machine learning workflow using `Pipeline` and `make_pipeline` from `scikit-learn`, applied to a diabetes classification task. Using the **Pima Indians Diabetes Dataset**, we aim to build an efficient and reproducible machine learning pipeline that predicts whether a patient is diabetic based on health metrics.

## 🧪 Context

Diabetes is a global health concern, with increasing prevalence across populations. Early detection is key to managing the disease and preventing severe complications such as cardiovascular disorders and nerve damage.

Researchers at Bio-Solutions Lab aim to use machine learning to better understand the condition among women and build predictive models for early intervention. This case study focuses on building a structured pipeline to support reproducibility and code modularity.

## 🎯 Objective

- Use the `Pipeline` and `make_pipeline` utilities in `scikit-learn`
- Implement preprocessing + model building in a unified flow
- Evaluate model performance on a diabetes classification problem

## 📊 Dataset

- **File**: `pima-indians-diabetes.csv`
- **Target**: `Outcome` (0 = Not Diabetic, 1 = Diabetic)

### Data Dictionary

| Feature         | Description |
|----------------|-------------|
| Pregnancies     | Number of times pregnant |
| Glucose         | Plasma glucose concentration |
| BloodPressure   | Diastolic blood pressure (mm Hg) |
| SkinThickness   | Triceps skinfold thickness (mm) |
| Insulin         | 2-Hour serum insulin (mu U/ml) |
| BMI             | Body mass index |
| Pedigree        | Diabetes pedigree function |
| Age             | Age in years |
| Outcome         | 0 = No diabetes, 1 = Diabetes |

## 🧰 Technologies Used

- Python 3
- Pandas, NumPy
- Scikit-learn
- Matplotlib & Seaborn (for EDA)

## 🔍 Workflow

1. **Data Loading & Cleaning**
   - Loaded the dataset and checked for nulls
   - Treated zero values in specific columns as missing

2. **Exploratory Data Analysis (EDA)**
   - Visualized distribution of features
   - Correlation analysis between features and outcome

3. **Pipeline Construction**
   - Used `Pipeline` and `make_pipeline` from `sklearn.pipeline`
   - Steps included imputation, scaling, and classification

4. **Model Training**
   - Logistic Regression as the classifier
   - Train/test split for evaluation

5. **Evaluation Metrics**
   - Accuracy, Confusion Matrix, ROC-AUC Score

## 📈 Results

- **Accuracy**: ~78% using basic Logistic Regression pipeline
- **Observations**:
  - Glucose, BMI, and Age were highly influential
  - Pipelines helped simplify and streamline preprocessing steps

## 🚀 Future Work

- Integrate GridSearchCV with pipeline for hyperparameter tuning
- Try ensemble models (e.g., Random Forest, Gradient Boosting)
- Deploy pipeline using joblib or pickle for production inference

## 📁 Repository Structure

```
├── Pipeline and make_pipeline-1.ipynb    # Main notebook
├── pima-indians-diabetes.csv            # Dataset
├── README.md                            # Project documentation
```

## 👨‍💻 Author

**Suhaib Khalid**  
ML Practitioner
