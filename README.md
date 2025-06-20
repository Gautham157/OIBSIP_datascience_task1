# OIBSIP_datascience_task1
# Iris Flower Classification - OIBSIP Data Science Task 1

#Overview

This project is developed as part of the OIBSIP (Oasis Infobyte) internship under the Data Science domain. The goal is to build a machine learning model that can classify Iris flowers into three species — **Setosa**, **Versicolor**, and **Virginica** — using their sepal and petal measurements.



#Dataset

The dataset used is provided in Excel format (`Iris.xls`) and includes the following features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
- Species (target)

The dataset is small, clean, and widely used for beginner-level classification tasks in machine learning.

---

#Tools and Libraries

- **Python**  
- **Pandas**, **NumPy** – data handling  
- **Seaborn**, **Matplotlib** – data visualization  
- **Scikit-learn** – machine learning model building and evaluation  
- **Jupyter Notebook / Google Colab** – development environment

---

#Steps Performed

#1. Data Loading & Inspection
- Loaded the dataset from Excel using `pandas.read_excel()`
- Renamed the columns for readability
- Checked for missing values and duplicates
- Verified data types and summary statistics

# 2. Data Cleaning
- Dropped unnecessary unnamed index columns (if present)
- Handled any duplicates to ensure quality
- Ensured target variable was correctly formatted as categorical

# 3. Exploratory Data Analysis (EDA)
- Visualized feature relationships using pairplots
- Generated a correlation heatmap to understand feature importance

# 4. Data Preprocessing
- Split the data into features (X) and target (y)
- Applied `StandardScaler` to normalize the feature values
- Performed a train-test split (80% train, 20% test)

# 5. Model Building
- Trained a **Random Forest Classifier** on the scaled training data
- Made predictions on the test set

# 6. Model Evaluation
- Evaluated the model using:
  - **Accuracy Score**
  - **Classification Report** (precision, recall, f1-score)
  - **Confusion Matrix**




