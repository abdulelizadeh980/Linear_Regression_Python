# 🦠 Covid-19: 7-Day Forecast Using Linear Regression  
Predicting next 7-days 2019-nCoV cumulative **Confirmed**, **Infected**, **Recovered**, and **Death** cases using a Linear Regression model.

![Linear Regression Visual](images/Linear_Regression_Visual.png)

---

## 👋 Welcome

This project analyzes the **Novel Coronavirus 2019 (Covid-19)** dataset and uses a **Linear Regression Model** to forecast the next **7 days** of cumulative case counts.  
The goal is to develop an analytical understanding of the outbreak pattern and evaluate whether healthcare systems are prepared for possible scenarios.

---

## 📚 Category  
**Linear Regression (Supervised Machine Learning)**

---

## 📂 Dataset  
**Dataset Name:** Novel Corona Virus 2019 Dataset  
**Source:** Kaggle  
**Link:** https://www.kaggle.com/datasets/sudalairajkumar/novel-corona-virus-2019-dataset  

### 📄 Dataset Description

| Column Name       | Description |
|-------------------|-------------|
| **SNo** | Serial Number |
| **ObservationDate** | Observation date in `mm/dd/yyyy` |
| **Province/State** | Province or State *(əyalət və ya ştat)* |
| **Country/Region** | Country or region |
| **Last Update** | Last update date time in UTC |
| **Confirmed** | Cumulative number of confirmed cases |
| **Deaths** | Cumulative number of deaths |
| **Recovered** | Cumulative number of recovered cases |
| **Infected** | `Confirmed - Recovered - Deaths` *(not a separate column in dataset)* |

---

## 🎯 Task

You are a **Data Scientist at the World Health Organization (WHO)**.  
Due to the outbreak of 2019-nCoV, WHO needs an early predictive model to understand how the virus will spread in the coming days.

Your tasks are:

### ✔ Analyze the Covid-19 dataset  
### ✔ Build a Linear Regression model  
### ✔ Predict the next 7 days cumulative:  
- Confirmed cases  
- Recovered cases  
- Death cases  
- *(Infected = Confirmed − Recovered − Deaths)*  

### ✔ Visualize the results using clear and meaningful charts  
### ✔ Evaluate model performance

---

## 🛠 Steps to Follow (Project Workflow)

### 1️⃣ Import required libraries  
- pandas  
- numpy  
- matplotlib / seaborn  
- scikit-learn (LinearRegression, metrics)

### 2️⃣ Load and explore the dataset  
- Check shape, missing values, data types  
- Understand data distribution and trends  

### 3️⃣ Clean and preprocess data  
- Parse dates  
- Handle missing values  
- Aggregate by date (global or country-level)  
- Create `Infected` column  
- Generate time index for regression  

### 4️⃣ Apply Linear Regression model  
- Train model using time as input feature  
- Build separate models for Confirmed, Recovered, and Deaths  

### 5️⃣ Evaluate model performance  
Metrics include:  
- **R² Score**  
- **Mean Squared Error (MSE)**  
- **Mean Absolute Error (optional)**  

### 6️⃣ Predict and visualize results  
- Predict next 7 days cumulative values  
- Plot:  
  - Actual vs Predicted  
  - Trend line for the next 7 days  

---

## 📊 Output Example

### 📈 Graph  
- Actual vs Predicted cumulative cases  
- Forecast extension for next 7 days  

### 📅 Table  
**Next 7 Days Forecast** with values for:  
- Confirmed  
- Recovered  
- Deaths  
- (Infected calculated automatically)

### 📐 Model Metrics  
- **R² score**  
- **MSE**  

---

## ✅ Summary

This project demonstrates the full pipeline of a data science prediction workflow:  
✔ Data cleaning  
✔ Feature engineering  
✔ Linear Regression modeling  
✔ Evaluation  
✔ Forecasting  
✔ Visualization  

It provides a clear and interpretable way to understand Covid-19 growth using a baseline ML model.

---

Feel free to explore, modify, or improve this project!
