# Employee Attrition Prediction Pipeline

An end-to-end data science project designed to predict employee attrition using the classic IBM HR Analytics dataset. This project aims to identify key drivers behind employee turnover and build predictive models to help HR teams proactively retain high-value talent.

## 📊 Business Problem
Employee turnover is costly. Beyond recruitment and training expenses, losing key team members disrupts productivity and lowers morale. This project analyzes organizational data to discover why employees leave and leverages Machine Learning to predict attrition before it happens.

## 🚀 Key Features & Highlights
- **Exploratory Data Analysis (EDA):** Deep dive into demographic, job-related, and financial factors influencing attrition.
- **Data Preprocessing:** Handled categorical variables (One-Hot Encoding), scaled numerical features, and addressed class imbalance using **SMOTE** (Synthetic Minority Over-sampling Technique).
- **Predictive Modeling:** Built and evaluated multiple classification algorithms (Logistic Regression, Random Forest, and XGBoost).
- **Business-Focused Metrics:** Prioritized **Recall** and **F1-Score** to minimize false negatives (failing to identify an employee who is about to leave).

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Imbalanced-Learn (SMOTE)
- **Visualization:** Matplotlib, Seaborn

## 📈 Key Insights from EDA
- **Overtime:** Employees working overtime show a significantly higher rate of attrition compared to those who do not.
- **Monthly Income:** There is a clear threshold where lower-income brackets correlate heavily with higher turnover.
- **Job Role:** Sales Representatives and Laboratory Technicians experience higher attrition rates compared to Managerial roles.

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone [https://github.com/Khushi-Veshnav/Week-2-Project.git](https://github.com/Khushi-Veshnav/Week-2-Project.git)
