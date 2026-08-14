# 🚗 Car Price Prediction with Machine Learning

## 🎯 Task 3 — Car Price Prediction with Machine Learning

### 📌 Objective

The objective of this project is to build a **machine learning regression model** that predicts the selling price of a used car based on features such as:

* 🚘 Brand
* 📅 Car Age
* 🛣️ Mileage
* ⛽ Fuel Type
* ⚙️ Transmission
* 📋 Other relevant vehicle features

The project follows a complete machine learning workflow, from data cleaning and exploratory data analysis to model training, evaluation, and feature importance analysis.

---

## 🛠️ Tech Stack

* 🐍 Python
* 🐼 Pandas
* 🔢 NumPy
* 🤖 Scikit-learn
* 📊 Matplotlib
* 🎨 Seaborn
* 📓 Jupyter Notebook / Google Colab

---

## 📂 Dataset

A suitable used-car dataset is used for this project. The dataset contains information about used cars and their selling prices.

Important attributes include:

* 🚘 Car Name
* 💰 Selling Price
* 📅 Year
* 🛣️ Present Price / Mileage
* ⛽ Fuel Type
* ⚙️ Transmission
* 👤 Owner
* 📊 Other available vehicle-related features

The dataset is cleaned and prepared before applying machine learning models.

---

## 🧹 Data Cleaning

The following data-cleaning steps are performed:

* 🔍 Inspect the dataset structure and data types.
* ❌ Check and handle missing/null values.
* ♻️ Identify and remove duplicate records.
* 🧹 Standardize inconsistent categorical values such as `"Petrol"` and `"petrol"`.
* 🔎 Check for inconsistent or invalid values.
* 📊 Prepare the dataset for further analysis and modelling.

---

## ⚙️ Feature Engineering

New features are created to improve the model:

### 📅 Car Age

Car age is calculated from the `Year` column using the current/reference year.

**Car Age = Reference Year − Manufacturing Year**

This provides a more meaningful representation of vehicle age.

### 🚘 Brand Extraction

The **brand name is extracted from the car name** column.

For example:

```text
Toyota Corolla → Toyota
Honda City → Honda
Maruti Swift → Maruti
```

The extracted brand can then be used as a categorical feature.

---

## 🔎 Exploratory Data Analysis (EDA)

The following analyses are performed:

### 💰 Selling Price Distribution

A distribution plot is used to understand the spread of car selling prices and identify possible outliers.

### ⛽ Price vs Fuel Type

A box plot is used to compare selling prices across different fuel types.

### 📅 Price vs Car Age

A scatter plot is used to analyse the relationship between car age and selling price.

This helps determine whether older cars generally have lower resale values.

---

## 🔤 Categorical Encoding

Categorical variables are converted into numerical form so that they can be used by machine learning algorithms.

**One-Hot Encoding** is used for categorical features such as:

* ⛽ Fuel Type
* ⚙️ Transmission
* 🚘 Brand

This allows categorical information to be incorporated into the regression models without assigning artificial numerical rankings.

---

## 🔥 Feature Correlation

A **correlation heatmap** is created using Seaborn to analyse relationships between numerical features and the selling price.

The heatmap helps identify:

* 📈 Positively correlated features
* 📉 Negatively correlated features
* 🔗 Relationships between independent variables
* 💰 Features that may have a strong relationship with selling price

---

## ✂️ Train-Test Split

The cleaned dataset is divided into:

* 🟢 **Training Data** — used to train the machine learning models
* 🔵 **Testing Data** — used to evaluate model performance on unseen data

`train_test_split` from Scikit-learn is used for splitting the dataset.

---

## 🤖 Machine Learning Models

At least two regression models are trained and compared.

### 1️⃣ Linear Regression

Linear Regression is used as a baseline regression model to understand the relationship between the input features and selling price.

### 2️⃣ Random Forest Regressor

Random Forest Regressor is used to capture more complex and non-linear relationships between vehicle characteristics and selling price.

The performance of both models is compared using standard regression evaluation metrics.

---

## 📏 Model Evaluation

The models are evaluated using:

### 📉 Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted prices.

**Lower MAE = Better Performance**

### 📐 Root Mean Squared Error (RMSE)

Measures the square root of the average squared prediction error.

**Lower RMSE = Better Performance**

### 🎯 R² Score

Measures how well the model explains the variation in selling prices.

**Higher R² = Better Performance**

The three metrics are used together to determine the best-performing regression model.

---

## 🏆 Best Model

The model with:

* ✅ Lower MAE
* ✅ Lower RMSE
* ✅ Higher R² score

is selected as the **best-performing model**.

The final notebook contains the actual evaluation results and justification for the selected model.

---

## 📊 Feature Importance

A feature importance chart is created for the best-performing model, particularly when using a tree-based model such as Random Forest.

The chart helps identify which features contribute most significantly to predicting the selling price of a used car.

---

## 📁 Project Structure

```text
Car-Price-Prediction/
│
├── 📓 Car_Price_Prediction.ipynb
├── 📊 car_data.csv
└── 📄 README.md
```

---

## 🚀 How to Run

1. 📥 Download or obtain the selected used-car dataset.
2. 📂 Upload the dataset to Google Colab or place it in the project directory.
3. 📓 Open `Car_Price_Prediction.ipynb`.
4. ▶️ Run the notebook cells sequentially.
5. 🧹 Perform data cleaning and preprocessing.
6. ⚙️ Perform feature engineering and EDA.
7. 🔤 Encode categorical variables.
8. 🤖 Train the regression models.
9. 📏 Evaluate the models using MAE, RMSE, and R².
10. 🏆 Identify the best-performing model.
11. 📊 Analyse the feature importance of the selected model.

---

## ✅ Task Checklist

* [x] 📥 Download a suitable used-car dataset.
* [x] 🧹 Handle null values.
* [x] ♻️ Remove duplicate records.
* [x] 🔤 Standardize inconsistent categorical values.
* [x] 📅 Calculate car age from the year column.
* [x] 🚘 Extract brand from the car name.
* [x] 📊 Analyse selling price distribution.
* [x] ⛽ Create price vs fuel type box plot.
* [x] 📅 Create price vs car age scatter plot.
* [x] 🔤 Encode categorical variables.
* [x] 🔥 Create feature correlation heatmap.
* [x] ✂️ Perform train-test split.
* [x] 🤖 Train at least two regression models.
* [x] 📉 Evaluate models using MAE.
* [x] 📐 Evaluate models using RMSE.
* [x] 🎯 Evaluate models using R² score.
* [x] 🏆 Select the best-performing model.
* [x] 📊 Create a feature importance chart.
* [x] 📝 Maintain a clean and commented Jupyter Notebook.

---

## 🏁 Conclusion

This project demonstrates a complete **machine learning regression workflow** for predicting used-car selling prices.

The project covers **data cleaning, feature engineering, exploratory data analysis, categorical encoding, correlation analysis, model training, model evaluation, and feature importance analysis**.

By comparing multiple regression algorithms using MAE, RMSE, and R² score, the project identifies the model that provides the most effective predictions for used-car prices.

---

## 👩‍💻 Author

**Garvita Jain**

*Data Science Internship — Task 3*
