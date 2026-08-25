# Telecom Customer Churn Analysis Using Pandas

## 📌 Project Overview

This project analyzes customer churn data to understand customer behavior and identify the factors associated with customer churn.

The analysis was performed using **Python, Pandas, NumPy, Matplotlib, and Seaborn**. The project includes data cleaning, exploratory data analysis, and visualizations to identify patterns related to customer churn.

## 🎯 Objectives

* Analyze the overall customer churn rate.
* Understand churn patterns across different customer groups.
* Identify the relationship between customer tenure and churn.
* Analyze churn based on contract type and payment method.
* Explore how different telecom services are associated with customer churn.
* Generate visual insights that can help understand customer retention.

## 🛠️ Tools & Technologies

* **Python**
* **Pandas** – Data cleaning and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook**

## 📂 Dataset

The project uses a telecom customer churn dataset containing customer information such as:

* Gender
* Senior Citizen
* Tenure
* Contract
* Payment Method
* Phone Service
* Multiple Lines
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming TV
* Streaming Movies
* Churn
* Total Charges

## 🔍 Data Cleaning

The following preprocessing steps were performed:

* Loaded the dataset using Pandas.
* Checked the structure and information of the dataset.
* Converted the `TotalCharges` column into a numerical data type.
* Replaced blank values in `TotalCharges` with `0`.
* Checked for missing values.
* Checked for duplicate records.
* Converted the `SeniorCitizen` values from `1/0` into `yes/no` for easier interpretation.

## 📊 Exploratory Data Analysis

Several visualizations were created to understand customer churn.

### 1. Overall Customer Churn

A count plot and pie chart were used to analyze the overall churn distribution.

**Key finding:**
Approximately **26.54% of customers have churned**.

### 2. Churn by Gender

Customer churn was analyzed across different genders to identify any noticeable differences.

### 3. Churn by Tenure

A histogram was used to study the relationship between customer tenure and churn.

**Key finding:**
Customers who have used the services for a longer period are more likely to stay, while customers with shorter tenure show higher churn.

### 4. Churn by Contract Type

Customer churn was compared across:

* Month-to-month
* One-year
* Two-year contracts

**Key finding:**
Customers with **month-to-month contracts are more likely to churn** compared with customers having one-year or two-year contracts.

### 5. Churn by Services

The following services were analyzed:

* Phone Service
* Multiple Lines
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming TV
* Streaming Movies

**Key findings:**

* Most customers use Phone Service.
* Customers without Online Security, Online Backup, Device Protection, and Tech Support show higher churn counts.
* Fiber optic customers have a comparatively high number of churned customers.
* Service-related features show noticeable differences in churn across customer groups.

### 6. Churn by Payment Method

Customer churn was analyzed across different payment methods.

**Key finding:**
Customers using **Electronic Check** show a comparatively higher churn count than customers using other payment methods.

## 📈 Key Insights

Based on the analysis:

1. **26.54% of customers have churned.**
2. Customers with **shorter tenure** are more likely to churn.
3. **Month-to-month contract** customers have a higher likelihood of churn.
4. Customers without services such as **Online Security, Online Backup, Device Protection, and Tech Support** show higher churn counts.
5. **Fiber optic** customers show a comparatively high number of churned customers.
6. Customers using **Electronic Check** have a higher churn count compared with other payment methods.

## 📁 Project Structure

```text
Telecom-Churn-Analysis/
│
├── Telecom churn analysis with pandas.ipynb
├── customer churn.csv
└── README.md
```

## 🚀 How to Run the Project

1. Clone this repository.
2. Make sure Python is installed.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Open the Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `Telecom churn analysis with pandas.ipynb`.
6. Make sure `customer churn.csv` is in the same directory as the notebook.
7. Run the cells sequentially to reproduce the analysis.

## 📌 Conclusion

This project demonstrates how **Pandas, Matplotlib, and Seaborn** can be used to clean, analyze, and visualize telecom customer data.

The analysis highlights important churn patterns related to **tenure, contract type, telecom services, and payment methods**, providing useful insights into customer retention and churn behavior.
