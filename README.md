# Titanic Survival Prediction

## Project Type

Machine Learning | Beginner-Friendly | End-to-End Project

---

## Objective

The goal of this project is to build a machine learning model that predicts whether a passenger survived the Titanic disaster based on features like age, gender, ticket, class, and fare.

---

## Dataset

* Dataset: Titanic dataset
* Features include:

  * Age
  * Passenger_Id
  * Ticket
  * Sex
  * Fare
  * Passenger Class (Pclass)
  * Embarked
  * Cabin
  * Parch (Parents + Children)
  * SibSp (Siblings + Spouse)
* Target variable: **Survived (0 = No, 1 = Yes)**

---

## Steps Performed

### 1. Data Cleaning

* Handled missing values in Age and Embarked
* Dropped Cabin column due to excessive missing values

### 2. Exploratory Data Analysis (EDA)

* Analyzed survival rate based on gender, age, fare and passenger class
* Visualized distributions using graphs

### 3. Feature Engineering

* Converted categorical variables into numerical format
* Extracted titles (Mr, Miss, etc.) from passenger names
* Created a column Is_rare

### 4. Model Building

* Used Logistic Regression as the baseline model
* Used RandomForest Classifier to improve the model

### 5. Model Evaluation

* Evaluated model using accuracy and confusion matrix

---

## Model Used

* Logistic Regression
* Random Forest

---

## Results

* Achieved an accuracy of approximately **83%** (depending on preprocessing and splits)

---

## Key Insights

* Female passengers had a significantly higher survival rate than males
* Passengers in 1st class had better chances of survival
* Age and fare also influenced survival probability

---

## How to Run

1. Clone this repository
2. Install required libraries:

   ```
   pip install -r requirements.txt
   ```
3. Open the notebook and run all cells

---

## Future Improvements

* Try advanced models like Decision Tree and Random Forest
* Perform deeper feature engineering
* Hyperparameter tuning for better accuracy

---

## Project Structure

```
Titanic-Project/
│
├── data/
├── notebook/
├── README.md
├── requirements.txt
```

---

## Conclusion

This project demonstrates a complete machine learning workflow from data preprocessing to model evaluation. It serves as a strong foundation for beginners entering the field of machine learning.
