# Sales Prediction Using Python – CODSOFT Data Science Internship

This project is part of the **CODSOFT Data Science Internship** program.  
The objective of this task is to build a machine learning model that predicts product sales based on advertising expenditure using **Simple Linear Regression**.

---

## Objective

To analyze the relationship between **TV advertising spend** and **product sales** and develop a regression model that can accurately forecast sales.  
This project demonstrates how data-driven decisions can help businesses optimize advertising strategies and maximize revenue.

---

## Dataset

- File name: `advertising.csv`  
- Source: ISLR (Introduction to Statistical Learning) Dataset  
- Columns:
  - TV – Advertising budget spent on TV
  - Radio – Advertising budget spent on Radio
  - Newspaper – Advertising budget spent on Newspaper
  - Sales – Product sales

For this project, **TV advertising spend** was used as the independent variable and **Sales** as the target variable.

---

## Steps Followed

1. **Data Loading** – Loaded dataset using Pandas.
2. **Exploratory Data Analysis (EDA)** – Analyzed dataset structure, statistics, and column information.
3. **Feature Selection** – Selected TV as input feature and Sales as target.
4. **Train-Test Split** – Split data into 80% training and 20% testing sets.
5. **Model Training** – Trained a Simple Linear Regression model.
6. **Prediction** – Predicted sales values on test data.
7. **Evaluation** – Evaluated model using:
   - Mean Squared Error (MSE)
   - R2 Score
8. **Visualization** – Plotted regression line to visualize the relationship between TV advertising and sales.

---

## Tools & Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Google Colab  

---

## Results

The model successfully learned the relationship between TV advertising spend and product sales.  
The regression line and R2 score demonstrate a strong positive correlation, indicating that increased TV advertising leads to higher sales.

---


---

## Conclusion

This project provided hands-on experience in **regression analysis, data preprocessing, model evaluation, and business-oriented machine learning applications**.  
It highlights how data science can support strategic decision-making in real-world business scenarios.


