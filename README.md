# Predictive Healthcare System using Machine Learning

## Overview

This project presents a Predictive Healthcare System developed using Machine Learning techniques to analyse heart disease risk factors and predict the presence of heart disease. The implementation is performed using Python in a Jupyter Notebook environment.

The project demonstrates a complete machine learning pipeline including:

- Data loading and preprocessing
- Missing value imputation
- Data visualisation
- Feature engineering
- Feature scaling
- Feature selection
- Handling class imbalance using SMOTE
- Model training and evaluation
- Performance comparison of multiple classification algorithms

---

## Dataset Information

The dataset used in this project is:

- `heart_disease.csv`

The dataset contains patient health-related attributes such as:

- Age
- Gender
- Blood Pressure
- Cholesterol Level
- BMI
- Smoking Habits
- Diabetes
- Stress Level
- Sleep Hours
- Alcohol Consumption
- Heart Disease Status

The target variable is:

- `Heart Disease Status`
  - `1 = Heart Disease Present`
  - `0 = No Heart Disease`

---

## Technologies and Libraries Used

### Programming Language
- Python

### Environment
- Jupyter Notebook
- Google Colab

### Python Libraries
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn

---

## Machine Learning Workflow

### 1. Data Loading and Exploration
- Loaded dataset using pandas
- Displayed dataset overview
- Checked data types and missing values
- Generated descriptive statistics

### 2. Data Preprocessing
- Imputed numerical missing values using median
- Imputed categorical missing values using mode
- Verified successful imputation

### 3. Data Visualisation
- Histograms for numerical features
- Count plots for categorical features
- Distribution analysis

### 4. Feature Engineering
- One-Hot Encoding for categorical variables
- Target variable conversion into binary format

### 5. Feature Scaling
- Standardisation using StandardScaler

### 6. Feature Selection
- Applied SelectKBest with ANOVA F-test
- Selected top 10 important features

### 7. Handling Imbalanced Data
- Applied SMOTE (Synthetic Minority Oversampling Technique)
- Balanced minority and majority classes

### 8. Model Training
The following machine learning models were implemented:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### 9. Model Evaluation
Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## Model Performance Summary

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|------|------|------|------|------|------|
| Logistic Regression | 58.95% | 17.90% | 31.27% | 22.77% | 48.15% |
| Decision Tree | 62.30% | 20.45% | 32.82% | 25.20% | 51.10% |
| Random Forest | 74.30% | 18.09% | 9.30% | 12.29% | 50.18% |

---

## Visualisations Included

The notebook contains multiple visualisations including:

- Feature distribution plots
- Count plots
- Feature importance plots
- SMOTE class balancing visualisation
- Confusion matrices

---

## Project Structure

```bash
Predictive-Healthcare-System/
│
├── UC_13587.ipynb
├── heart_disease.csv
└── README.md
```

---

## How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/REPOSITORY-NAME.git
```

### Step 2: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

### Step 3: Open Jupyter Notebook

```bash
jupyter notebook
```

### Step 4: Run the Notebook

Open:

```bash
UC_13587.ipynb
```

Run all cells sequentially.

---

## Key Learning Outcomes

This project demonstrates practical implementation of:

- Healthcare data analytics
- Machine learning classification
- Data preprocessing techniques
- Feature engineering
- Handling imbalanced datasets
- Model evaluation and comparison
- Data visualisation

---

## Future Improvements

Possible future enhancements include:

- Hyperparameter tuning
- Deep learning implementation
- Deployment using Flask or Streamlit
- Real-time prediction system
- Integration with healthcare dashboards

---

## Author

Academic Machine Learning Project

Developed for educational and research purposes.

---

## License

This project is intended for academic and educational use only.
