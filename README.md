# CardioGoodFitness – Customer Analytics

End-to-end customer analytics project analyzing treadmill purchase data to generate actionable business recommendations and segmentation insights.

---

## 📌 Project Overview

This project presents an end-to-end exploratory data analysis (EDA) of customer purchase data for CardioGoodFitness, a retail company specializing in treadmill products.

The objective is to analyze customer demographics, income levels, fitness ratings, and usage behavior to uncover purchasing patterns across different treadmill models. The insights derived from this analysis support strategic marketing, product positioning, and revenue optimization decisions.

This project demonstrates the practical application of data analytics techniques in solving real-world business problems.

---

## 🎯 Problem Statement

CardioGoodFitness offers multiple treadmill models targeting different customer segments. However, the company lacks clear insights into:

- Which customer profiles prefer premium vs. entry-level models
- How income and fitness level influence purchasing decisions
- What factors drive higher usage and mileage expectations
- How to segment customers for targeted marketing strategies

Without structured data analysis, marketing efforts remain generalized rather than personalized, limiting revenue growth and customer retention opportunities.

The goal of this project is to perform detailed customer segmentation analysis and generate actionable business recommendations.

---

## 📊 Dataset Description

The dataset contains customer-level purchase data capturing demographic, financial, and behavioral attributes of treadmill buyers.

It includes information such as:

- Age  
- Gender  
- Education  
- Marital Status  
- Income  
- Self-rated fitness level  
- Expected weekly usage  
- Expected weekly miles  
- Treadmill model purchased  

This dataset enables analysis of customer segmentation, product preferences, and purchasing behavior patterns.

---

## 🛠️ Tools & Technologies

- Python  
- Pandas (Data Manipulation)  
- NumPy (Numerical Computation)  
- Matplotlib & Seaborn (Data Visualization)  
- Jupyter Notebook  

---

## 🔎 Methodology

### 1️⃣ Data Cleaning & Preparation
- Checked for missing values  
- Validated data consistency  
- Verified data types  
- Performed preprocessing  

### 2️⃣ Exploratory Data Analysis (EDA)
- Descriptive statistical analysis  
- Distribution analysis of income, age, and usage  
- Product-wise comparison of customer attributes  
- Correlation analysis between income, fitness, and miles  

### 3️⃣ Data Visualization
- Income distribution by product model  
- Age vs product preference analysis  
- Fitness level impact on mileage  
- Gender-based purchase trends  

---

## 📈 Key Insights

- Customers aged 25–35 are the primary buyers of treadmills.  
- TM195 is mostly purchased by customers with lower fitness levels.  
- TM798 is preferred by high-income customers with advanced fitness levels.  
- Male customers tend to use treadmills more frequently than female customers.  
- Customers with higher income are more likely to purchase TM798.  

---

## 💡 Business Recommendations

- High-income customers prefer TM798. Marketing campaigns for TM798 should target premium customer segments.  
- TM195 is mostly purchased by beginner fitness users and can be promoted as an entry-level treadmill.  
- Customers with higher weekly usage are more likely to purchase TM798. Subscription-based service offers can be introduced for these customers.  
- The 25–35 age group shows higher purchasing behavior and should be targeted in promotional activities.  

---

## 🚀 Business Impact

If implemented, these recommendations can:

- Increase premium product sales  
- Improve marketing ROI  
- Enhance customer personalization  
- Strengthen competitive positioning  
- Optimize inventory planning  

---

## 📁 Repository Structure
├── CardioGoodFitness.csv
├── CardioGoodFitness - Customer Treadmill Purchase Analysis.ipynb
└── README.md

## How to Run the Project

### 1. Clone the repository

git clone https://github.com/your-username/cardiogoodfitness-customer-analytics.git

### Install required libraries

pip install pandas numpy matplotlib seaborn

### Launch Jupyter Notebook

jupyter notebook

Open the analysis notebook and run all cells.
