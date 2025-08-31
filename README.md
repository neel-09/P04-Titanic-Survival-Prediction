## Titanic Survival Prediction

*A machine learning project to predict the survival of passengers on the Titanic using a classification model.*

# 1. Project Overview
   
This project tackles the classic Kaggle problem of predicting which passengers survived the sinking of the Titanic. It is a binary classification problem where the model must predict one of two outcomes: survived (1) or did not survive (0). The project demonstrates a full machine learning workflow, from exploratory data analysis to model training and evaluation.


# 2. Dataset
   
The project uses the well-known Titanic dataset, which contains information on passengers who were aboard the ship. The data includes both numerical and categorical features that are crucial for predicting survival.


**Key Features:**

**Pclass:** Passenger class (1st, 2nd, or 3rd)

**Sex:** Passenger's gender

**Age:** Passenger's age

**SibSp:** Number of siblings/spouses aboard

**Parch:** Number of parents/children aboard

**Fare:** Ticket fare

**Embarked:** Port of embarkation

**Target Variable:**

**Survived:** Survival status (0 = Did not survive, 1 = Survived)


# 3. Methodology
   
The project follows a standard machine learning workflow for classification tasks:

**Exploratory Data Analysis (EDA):** The notebook includes visualizations and statistics to understand the relationship between different features and the survival rate.

**Data Preprocessing:** Missing values are handled, and categorical features are converted into a numerical format suitable for a machine learning model.

**Model Training:** A classification model (Random Forest) is trained on the preprocessed training data.

**Model Evaluation:** The model's performance is measured using accuracy and other relevant metrics, such as a confusion matrix.


# 4. Results
   
The trained classifier provides a baseline for predicting passenger survival.

**Accuracy: [82.12%]**

Interpretation: This is the percentage of passengers that the model correctly classified as either survivors or non-survivors.


# 5. Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn (for visualization)

Scikit-learn (for the classification model)


# 6. How to Run the Project
   
To run this project, you need to have Python and the required libraries installed.

Clone the repository:

```bash
git clone https://github.com/neel-09/Titanic-Survival-Prediction.git
```

Navigate to the project directory:

```bash
cd Titanic-Survival-Prediction
```

Run the Jupyter Notebook:
Open the ```Project 4.ipynb``` file in Jupyter Notebook and run the cells.
