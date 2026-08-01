# 📊 Telecom Customer Churn Analysis

## 📌 Project Overview

Customer churn is one of the biggest challenges faced by telecommunication companies. Losing existing customers increases acquisition costs and negatively impacts revenue. This project performs an exploratory analysis of a telecom customer dataset to identify the characteristics and behaviors associated with customer churn.

The analysis includes data cleaning, preprocessing, exploratory data analysis (EDA), visualization, and statistical hypothesis testing to generate business insights that can support customer retention strategies.

---

## 🎯 Objectives

The main objectives of this project are to:

- Explore and understand the telecom customer dataset.
- Perform data cleaning and preprocessing.
- Identify numerical and categorical variables.
- Analyze customer churn patterns.
- Visualize important relationships between variables.
- Perform statistical hypothesis testing.
- Generate actionable business insights for customer retention.

---

## 📂 Dataset

The project uses the **Telecom Customer Churn Dataset**, which contains customer information from a telecommunications company.

### Dataset Summary

- **Rows:** 3,333 customers
- **Columns:** 20 features
- **Target Variable:** `Churn`

### Features Include

- Account Length
- Area Code
- International Plan
- Voice Mail Plan
- Number of Voice Mail Messages
- Day, Evening, Night and International Minutes
- Calls
- Charges
- Customer Service Calls
- Churn

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook

### Libraries

- pandas
- numpy
- matplotlib
- seaborn
- scipy
- sqlalchemy
- psycopg2

---

## 📊 Project Workflow

### 1. Data Loading

- Import libraries
- Load dataset
- Display first and last records

### 2. Data Understanding

- Dataset shape
- Data types
- Summary statistics
- Missing values
- Duplicate records
- Unique values

### 3. Data Preprocessing

- Rename columns
- Prepare variables for analysis
- Detect potential outliers

### 4. Exploratory Data Analysis (EDA)

#### Univariate Analysis

- Customer churn distribution
- Account length
- International plan
- Voice mail plan
- Customer service calls
- Day minutes

#### Bivariate Analysis

- Churn vs International Plan
- Churn vs Voice Mail Plan
- Churn vs Account Length
- Churn vs Customer Service Calls
- Churn vs Day Minutes
- Churn vs Day Charges

#### Multivariate Analysis

- Correlation Heatmap
- Pairplot
- Scatter Plot

---

## 📈 Statistical Analysis

The project applies statistical tests to validate relationships between variables.

### Chi-Square Test

Used to determine whether there is a significant association between:

- International Plan and Churn
- Voice Mail Plan and Churn

### Independent T-Test

Used to compare churned and retained customers regarding:

- Day Minutes
- Customer Service Calls

---

## 🔍 Key Insights

The analysis highlights several important findings:

- Customers with an International Plan tend to have higher churn rates.
- Frequent Customer Service Calls are strongly associated with customer churn.
- Customers with higher daytime usage are more likely to leave the company.
- The dataset is moderately imbalanced, with more retained customers than churned customers.
- Correlation analysis identifies the strongest relationships among numerical variables.

---

## 📁 Project Structure

```
Telecom-Churn-Analysis/
│
├── telecom_churn.csv          # Dataset
├── task2.ipynb                # Jupyter Notebook
├── README.md                  # Project documentation
```

---

## 🚀 How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/yourusername/Telecom-Churn-Analysis.git
```

2. Navigate to the project folder

```bash
cd Telecom-Churn-Analysis
```

3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scipy sqlalchemy psycopg2-binary
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

5. Open **task2.ipynb** and run all cells.

---

## 📌 Business Value

This project helps telecommunication companies:

- Understand customer behavior.
- Identify factors contributing to customer churn.
- Improve customer retention strategies.
- Support data-driven business decisions.

---

## 👩‍💻 Author

**Alimata ZOUNGRANA**

Computer Science & Engineering Student

Aspiring Data Analyst | Data Science Enthusiast

---

## ⭐ Acknowledgements

This project was completed as part of a data analysis internship to demonstrate practical skills in:

- Data Cleaning
- Exploratory Data Analysis
- Statistical Analysis
- Data Visualization
- Business Insight Generation
