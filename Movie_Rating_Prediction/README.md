# Movie Rating Prediction – CODSOFT Data Science Internship

This project is part of the **CODSOFT Data Science Internship**.  
The goal of this project is to predict the **IMDb rating of a movie** based on features like genre, director, and actors using machine learning techniques in Python.

---

## Objective

To analyze historical movie data and develop a regression model that estimates the ratings given to movies by users or critics.  
This project enables exploration of **data preprocessing, feature engineering, and regression modeling** while providing insights into the factors influencing movie ratings.

---

## Dataset

- File used: `IMDb Movies India.csv`  
- Columns included:
  - Name
  - Year
  - Duration
  - Genre
  - Rating
  - Votes
  - Director
  - Actor 1
  - Actor 2
  - Actor 3

---

## Steps Followed

1. **Data Loading** – Loaded dataset using Pandas.
2. **Exploratory Data Analysis (EDA)** – Checked column info, missing values, and initial statistics.
3. **Data Cleaning** – Removed rows with missing `Rating` or key features.
4. **Feature Selection** – Selected relevant features: `Genre`, `Director`, `Actor 1`, `Actor 2`, `Actor 3`.
5. **Encoding** – Converted categorical text features into numeric values using Label Encoding.
6. **Train-Test Split** – Split data into training (80%) and testing (20%) sets.
7. **Model Training** – Trained a **Linear Regression** model on training data.
8. **Evaluation** – Evaluated model performance using:
   - Mean Squared Error (MSE)
   - R2 Score
   - Comparison of Actual vs Predicted ratings

---

## Tools & Technologies Used

- Python 3.x  
- Pandas  
- NumPy  
- Scikit-learn (LinearRegression, LabelEncoder, train_test_split)  
- Google Colab  

---

## Results

The model successfully predicts movie ratings based on genre, director, and actors.  
The comparison of **Actual vs Predicted ratings** demonstrates the predictive capability of the regression model.  
MSE and R2 Score indicate the model performance.

---

## Notes

This project demonstrates **real-world data cleaning, feature engineering, and regression modeling** skills applicable to data science and machine learning roles.


