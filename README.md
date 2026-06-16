# Titanic Survival Prediction using Machine Learning

## Project Description

This project uses machine learning techniques to predict whether a passenger survived the Titanic disaster. The dataset was obtained from the Kaggle Titanic competition and includes passenger information such as age, sex, passenger class, fare, family relationships, and embarkation port.

The project follows a complete machine learning workflow:

* Exploratory Data Analysis (EDA)
* Data Cleaning
* Feature Engineering
* Model Training
* Model Evaluation
* Cross-Validation
* Prediction on New Data

Three machine learning models were trained and compared:

* Logistic Regression
* Random Forest
* Gradient Boosting

The final model was selected based on evaluation metrics and 5-fold cross-validation performance.

---

## Dataset

Source: Kaggle Titanic Competition

Files used:

* train.csv
* test.csv

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/titanic-ml.git
```

2. Navigate to the project folder:

```bash
cd titanic-ml
```

3. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Run the notebook cells sequentially.

---

## Data Preprocessing

The following preprocessing steps were performed:

* Missing Age values filled using the median.
* Missing Embarked values filled using the mode.
* Cabin column removed due to excessive missing values.
* Name, Ticket, and PassengerId removed.
* Created FamilySize feature.
* Created IsAlone feature.
* Encoded categorical variables into numerical values.

---

## Model Evaluation

| Model               | Accuracy | F1 Score | ROC-AUC |
| ------------------- | -------: | -------: | ------: |
| Logistic Regression |   82.68% |    0.756 |   0.852 |
| Random Forest       |   81.56% |    0.759 |   0.837 |
| Gradient Boosting   |   80.45% |    0.720 |   0.821 |

5-fold cross-validation was used to obtain a more reliable estimate of model performance.

---

## Best Score

Best single-split Accuracy: **82.68% (Logistic Regression)**

Best cross-validation performance: **Gradient Boosting Classifier**

---

## Future Improvements

* Hyperparameter tuning using GridSearchCV.
* Advanced feature engineering.
* Experimentation with XGBoost and LightGBM.
* Feature importance analysis.

---

## Author

Machine Learning Titanic Classification Project
